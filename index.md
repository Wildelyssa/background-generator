<!DOCTYPE html>
<html>
<head>
	<title>Background Generator</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<style>
		body {
				font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;, sans-serif;
				text-align: center;
				text-transform: uppercase;
				letter-spacing: 1em;
				color: grey;
				color: rgba(0 0 0 0.5);
				background: linear-gradient(to right, hotpink, cyan);
				padding-top: 20vh;
		}
		h1 {
			font-size: 6vh;
			width: 100%;
		}
		h3, p {
			text-transform: none;
			letter-spacing: 0.01em;
		}
	</style>
</head>
<body id="gradient">
	<h1>Background Generator</h1>
	<p>Click on the squares to select your colours</p>
	<input type="color" name="colo1" value="#00ff00" class="colour1">
	<input type="color" name="color2" value="#ff0000" class="colour2">
	<h2>Current CSS Background</h2>
	<h3></h3>
<script type="text/javascript" src="script.js"></script>
</body>
</html>