<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Noseve</title>
    <link rel="stylesheet" href="style.css">
    <script type="text/javascript" src="script.js"></script>
  </head>
  <body>
    <h1>Jonatan Hernández Gacía </h1>
    <h2>juju </h2>
    <p>This is a web page.</p>
    <p>Enter names in the fields, then click "Submit" to submit the form:</p>

<form id="frm1" action="/action_page.php">
  Num1: <input type="number" name="x"><br>
  Num2: <input type="number" name="y"><br><br>
  <input type="button" onclick="myFunction()" value="Submit">
</form>

<script>
function myFunction() {
  document.getElementById("frm1").submit();
}
</script>
  </body>
</html>
