<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
 	<script src="script.js"></script>
	<link rel="stylesheet" type="text/css" href="mystyle.css">
 	<title>agent</title>
</head>
<body>
 	<div class="formcol row">
 		<input type="button" onclick="myFunction()" value="Submit">
        <div class="formcol form-left middle">
            <input type="text" id="first" size="12" name="col1x" />
            <label for="col1x" >Productivity</label>
        </div>
        <div class="formcol form-right middle">
            <input type="text" id="second" size="12" name="col2x" />
            <label for="col2x">Salary</label>
        </div>
        <input type="button" onclick="runFunction()" value="Run">
	</div>
	<div class="test">
		<input type="button" onclick="execTest1()" value="Teste1">
		<input type="button" onclick="execTest2()" value="Teste2">
	</div>
	<div id ="employees">
		
	</div>
</body>
</html>
