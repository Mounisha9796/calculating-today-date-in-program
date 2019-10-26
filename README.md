<!DOCTYPE html>
<html>
<title>my page</title>
<head>
<script>
	function displayDate()
	{
		var date1=new date();
		document.getElementById("div1").innerHTML=date1;
	}
</script>
</head>
<body onload=dispalyDate()>
	<div id="div1">
	</div>
</body>
</html>

