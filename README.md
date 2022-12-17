<!DOCTYPE html>
<html>
<head>
<style type="text/css">

.circle{
  width: 100px;
  height:100px;
  border-radius: 50%;
  margin: 20px;
  float: left;
}

#red-circle{
  background-color: red;
}

#blue-circle{
  background-color: blue;
}

#green-circle{
  background-color: green;
}

</style>

</head>
<body>

<div class="circle" id="red-circle">
</div>

<div class="circle" id="blue-circle">
</div>

<div class="circle" id="green-circle">
</div>



<script type="text/javascript">

document.getElementById("red-circle").onclick = function(){
document.getElementById("red-circle").style.display ="none";
}

document.getElementById("blue-circle").onclick = function(){
document.getElementById("blue-circle").style.display ="none";
}

document.getElementById("green-circle").onclick = function(){
document.getElementById("green-circle").style.display ="none";
}


</script>
</body>
</html>

