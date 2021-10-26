<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Dimensiones CSS</title>
	
	<link rel="stylesheet" href="dimensiones.css">
</head>
<body>
	<div>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti voluptate amet dicta cum incidunt molestiae, ad perspiciatis, delectus pariatur rem aliquid quibusdam ipsum laborum reprehenderit totam cumque, quasi, harum! Blanditiis.</p>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor sequi aliquid magni excepturi ad, tenetur, quod similique, <a href="http://google.es" target="_blank">commodi delectus</a> architecto nihil dolorem vel soluta maiores ut, nam. Error, quas, nam.</p>
	</div>
</body>
</html>










* {
	box-sizing: border-box;
}

body {
	padding: 0;
	margin: 0;
}

div {
	width: 400px;  
	padding-top: 20px;  
	padding-right: 5px; 
	padding-bottom: 5px;
	padding-left: 0px;
	border-width: 10px;  
	border-style: solid; 
	border-color: #fc00fc;
	margin: 0; 
}
p {
	width: 50%;
	padding: 0;
	border: 1px solid #333;
	margin: 20%;
}
