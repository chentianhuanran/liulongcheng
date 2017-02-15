# liulongcheng
<!doctype html>
<html>
<head>
	<meta charset="utf-8">
	<title>js</title>
</head>
<body> 
<script type="text/javascript">
	
	var total = 0, count = 1;
	while (count <= 10) {
	  total += count;
	  count += 1;
	}
	document.write(total);
	
	var ss = "hhhhhh\nsdjoad";
	ss;
	
	var theNumber = Number(prompt("Pick a number", ""));//Number函数将用户输入的值转化成数字（此例中需要使用Number函数，是因为prompt函数的结果是一个字符串值）。类似的函数还有Strig和Boolean，它们也都是将值转换成相应的类型。
	alert("your number is the square root of " + (theNumber * theNumber));//显示上面获取到的数字的平方
	
	var num = prompt("pick a number:", "0");

	if(num < 10)
	  alert("small");
	else if (num < 100)
	  alert("Medium");
	else
	  alert("Large");/*
	  *该程序首先会判断num是否小于10，如果小于10，则执行输出“small”的分支，然后结束；
	  *如果不小于10，则执行包含第二个if的分支。如果第二个条件（小于100）成立，则表示该数字在10和100之间，输出“Medium”;
	  *如果不成立，则会执行第二个（即最后一个）else分支，输出“Large”。
	  */
	  
	for (var current = 20; ; current++) {
	  if(current % 7 == 0)//能被整除
	  break;//跳出当前循环
	}
	current;//值为：21，
	
	switch(prompt("sss")) {
	  case "rainy":
		alert("1");
		break;
	   case "sunny":
		alert("2");
		break;
	  case "cloudy":
		alert("3");
		break;
	  default:
		alert("4");
		break;
	}//调度，程序会根据switch给定的值跳转到相应的标签处。然后开始执行标签处的语句，紧接着
</script>
</body>
</html>
