getting-started
===============


<html>    
<head>

<script src="jquery.js"></script>

<LINK href="bootstrap/css/bootstrap.css" rel="stylesheet" type="text/css">
<script src="bootstrap/js/bootstrap.js"></script>

<link href="twitter-bootstrap-60b202d/docs/assets/css/bootstrap1.css" rel="stylesheet">
<link href="bootstrap/css/bootstrap.css" rel="stylesheet">
<script src="bootstrap/js/bootstrap.min.js"></script>
<link href="bootstrap-editable-1.4.4/bootstrap-editable/css/bootstrap-editable.css" rel="stylesheet">
<script src="bootstrap-editable-1.4.4/bootstrap-editable/js/bootstrap-editable.min.js"></script>


<script type="text/javascript">
function drop()
{document.getElementById("bcd").style.display="inline";
}
</script>


</head>


<body>  



<table border="1" class="table" border spacing:100px; border-collapse:collapse; style="margin-left:100px; float:right; margin:auto; width 100px; height:200px; background-color:#ffc40d;">  
    

    <thead>  
          <tr style="width:20px">  
            <th background-color:#006DCC; style="float:center width:20px;">Job Requirement no.   </th>  
            <th style="float:center;">Job Requirement details   </th>  
            <th style="float:center;">Next Action</th>  
             
          </tr>  
        </thead>  
        <tbody>  
          <tr>  
            <td width="10%">
  	<a href="#" id="user" datatype="number" style='float:center'>001</a>
<script>
$.fn.editable.defaults.mode = 'inline';
		$("#user").editable();		
</script>

</td>
		  
           <td style="float:center">
<div id="rep"><button id="kbc" onClick="drop()">Edit</button></div>



<div id="bcd" style="display:none">
<Form name="myForm" action="demo_form.asp" onsubmit="return validateForm()" >
<h1>Qualifications</h1>
<input  type="text">
<p>Date(from)</p>
<input  type="text">
<p>Date(to)</p>
<input  type="text">
<button onClick="submit()">Submit</button>
</form>
</div>


</td>  
   
		<td style="float:center"><button onClick="next()">next</button></td>  
               </tr>  
    </tbody>  
      </table>  

</body>  
</html>  

