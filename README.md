# hw2-js     
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>A-level</title>
</head>
<body>
	<header></header>
	<main>
		<script>
			var letters = []
			var string = "Backend As A Service"
			var lon = string.split (' ')
			console.log (lon)
			for (i = 0; i < lon.length; i++) {
				console.log ( letters.push( lon [i] [0] ))
			}
			var result = letters.join (' ')
			console.log (result)
		</script>
		<script>
			function check (arg) {
				console.log (
   					typeof arg === "number" ?
       				newDate().toLocaleString() :
       				"Неверный тип данных"
			)
		</script>
	</main>
	<footer></footer>
</body>
</html>
