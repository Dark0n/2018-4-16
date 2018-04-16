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
