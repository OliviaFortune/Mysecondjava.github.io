<html>
<body>

<h2>JavaScript Statements</h2> 

<p>JavaScript code blocks are written between { and }</p>

<button type="button" onclick="myFunction()">Click Me!</button>
<button type="button" onclick="myFunction1()">Click Me!</button>

<p id="demo1"></p>
<p id="demo2"></p>


<script>

function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  
}
function myFunction1() {
  document.getElementById("demo2").innerHTML = "Hello Dolly again!";
  
}

</script>

</body>
</html>
