# 2018-4-16
HTML 事件
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>W3Cschool教程(w3cschool.cn)</title>
</head>
<body>

<button onclick="getElementById('demo').innerHTML=Date()">
</button>
<p id="demo"></p>

</body>
</html>

字符串长度
<!DOCTYPE html>
<html>
<head> 
<meta charset="utf-8"> 
<title>W3Cschool教程(w3cschool.cn)</title> 
</head>
<body>

<script>
var txt = "Hello World!";
document.write("<p>" + txt.length + "</p>");
var txt="ABCDEFGHIJKLMNOPQRSTUVWXYZ";
document.write("<p>" + txt.length + "</p>");
</script>

</body>
</html>

字符串可以是对象
<!DOCTYPE html>
<html>
<head> 
<meta charset="utf-8"> 
<title>W3Cschool教程(w3cschool.cn)</title> 
</head>
<body>

<p id="demo"></p>
<script>
  var x = "John";
  var y = new String("John");
  document.getElementById("demo").innerHTML = typeof x + "" + typeof y;
</script>

</body>
</html>
