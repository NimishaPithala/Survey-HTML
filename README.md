<!DOCTYPE HTML>
<html>
<head>
<title>Student Survey form</title>
</head>
<style>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}
form {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #FFF8DC;
  padding: 10px;
}
footer {
  background-color:salmon;
  padding: 10px;
  text-align: center;
  color: black;
}
</style>
<body>
<form action="http://google.co.in">
<div align="center" >
<h1 style="background-color:salmon;">Student Survey form</h1>
<p style="color:black;" >
<b>Enter your name:</b>
</p>
<input type="text" name="UserName" size=40 maxlength=40 value="">
</br></br>
<p style="color:black;">
<b>Enter your department:</b>
</p>
<input type="text" name="Deptt" size=35 maxlength=35 value=""> </br> </br>
<p style="color:black;">
<b>Tell us a little about yourself:</b>
</p>
<textarea name="Comments" cols=30 rows=4></textarea> </br> 
<p style="color:black;">
<b>Are you happy with college facilities?</b>
</p>
<input type="radio" name="exe" value=1>Yes
<input type="radio" name="exe" value=2>No
<p style="color:black;">
<b>What do you prefer for college materials  and information?</b>
</p>
<!--Checkbox lets you select multiple options -->
<input type="checkbox" name="Books">Books
<input type="checkbox" name="Web">Online resources
<input type="checkbox" name="Professor notes">Notes
</p>
</br>
<input type=submit value="Submit form">
</div>
</form>
<footer>
  <p><b>JNTUH</b></p>
  <a href=" https://www.jntuhceh.ac.in/" target="_blank"><b>Visit our website<b></a> 

</footer>
</body>
</html>
