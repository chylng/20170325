<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>input元素之email</title>
</head>
<body>
<!-- required：内容为必填项，格式较松散 
	image为图片按钮，有submit功能；img为图片标签，两者要区分开
	-->
	<h1>火锅店开业，发送邮箱赢100元现金券！</h1>
	<form id="myForm"  name="myForm" action="http://www.163.com" method="" target="_blank">
		邮箱：<input type="email" name="email" value="" required=""><br><br>
		请输入电话：<input type="tel"><br><br>
		请输入网址：<input type="url"><br><br>
		<input type="image" src="../img/51.png" alt="" width="160">
	</form>
	<figure>
	<!-- figure为多媒体标签 -->
		<img src="../img/dc.png" alt="">
	</figure>
</body>
</html>
