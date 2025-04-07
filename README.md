<!DOCTYPE html>
<html>
	<head>
		<script>
			function add(){
			var num1, num2;
			num1=Number(document.form1.txtNum1.value);
			num2=Number(document.form1.txtNum2.value);
			document.form1.txtTotal.value=num1 + num2;
			}
			function sub(){
			var num1, num2;
			num1=Number(document.form1.txtNum1.value);
			num2=Number(document.form1.txtNum2.value);
			document.form1.txtTotal.value=num1 - num2;
			}
			function mult(){
			var num1, num2;
			num1=Number(document.form1.txtNum1.value);
			num2=Number(document.form1.txtNum2.value);
			document.form1.txtTotal.value=num1 * num2;
			}
			function div(){
			var num1, num2;
			num1=Number(document.form1.txtNum1.value);
			num2=Number(document.form1.txtNum2.value);
			document.form1.txtTotal.value= num1 / num2;
            }
		</script>
	</head>
	<body>
	<form name="form1">
		Enter operand 1:
		<input type="text" name="txtNum1" size=8><br><br>
		Enter operand 2:
		<input type="text" name="txtNum2" size=8><br><br>
		<input type="button" value="+" onclick="add()">
		<input type="button" value="-" onclick="sub()">
		<input type="button" value="*" onclick="mult()">
		<input type="button" value="/" onclick="div()"><br><br>
		<input type="text" name="txtTotal">
	</form>
	</body>
</html>
	
