<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
  <style>
  .wrapper{
	margin: 100px;
	width: 100px;
	position: relative;
}
.wrapper:hover:before{
	content: "";
	position: absolute;
	top: -12px;
	left: -12px;
	right:-12px;
	bottom: -12px;
	outline: 4px solid black;
	outline-offset: 5px;
	border:4px solid black;
}
.content{
	top: 50px;
	width: 300px;
	position: relative;
}
.content:hover:after{
	content: "surprise";
	width: 80px;
	height: 80px;
	background-color: green;
	position: absolute;
	top: -100px;
	left: 180px;
}
</style>
</head>
<body>
		<div class="wrapper">
			this is magic.
		</div>
		<div class="content">Move the mouse over this sentence</div>
</body>
</html>
