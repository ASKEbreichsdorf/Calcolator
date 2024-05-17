 <!DOCTYPE html>
 <html>
	<head>
			<title>Intro to Javaskript</title>
			<script>
				function add2Numbers()
				{
					var num1 = document.getElementById('num1').value * 1.0;
					var num2 = document.getElementById('num2').value * 1.0;
					document.getElementById("result").innerHTML= num1 + num2;
				}

				function sub2Numbers()
				{
					var num1 = document.getElementById('num1').value * 1.0;
					var num2 = document.getElementById('num2').value * 1.0;
					document.getElementById("result").innerHTML= num1 - num2;
				}

				function mul2Numbers()
				{
					var num1 = document.getElementById('num1').value * 1.0;
					var num2 = document.getElementById('num2').value * 1.0;
					document.getElementById("result").innerHTML= num1 * num2;
				}
				
				function div2Numbers()
				{
					var num1 = document.getElementById('num1').value * 1.0;
					var num2 = document.getElementById('num2').value * 1.0;
					document.getElementById("result").innerHTML= num1 / num2;
				}

				function dur2Numbers()
				{
					var num1 = document.getElementById('num1').value * 1.0;
					var num2 = document.getElementById('num2').value * 1.0;
					document.getElementById("result").innerHTML= (num1 + num2) / 2;
				}



			</script>
	</head>
	<body>
		<h1 id="myheading">
			Das ist ein selbstgemachter Taschenrechner
		</h1>
		<form>
		  <label for="num1">First Number:</label>
		  <input type="text" id="num1" name="num1"><br><br>
		  <label for="num2">Second Number:</label>
		  <input type="text" id="num2" name="num2"><br><br>
		</form>
		<p>
		</p>
		<button onclick="add2Numbers()">
			Addieren
		</button>
		<button onclick="sub2Numbers()">
			Subtrahieren
		</button>
		<button onclick="mul2Numbers()">
			Multiplizieren
		</button>
		<button onclick="div2Numbers()">
			Dividieren
		</button>
		<button onclick="dur2Numbers()">
			Durchschnitt
		</button>

		
		<p id="result">
		</p>
	</body>
</html>
