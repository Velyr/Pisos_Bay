!DOCTYPE html>
<html>
<head>
	<title> Ejecicio de Bay </title>
	<style> 
	body 
	
	{background-color: #FAAAAAAA;
	}
	</style>
	
</head>

<body> 
	
	<h1> Embelleciendo tu espacio </h1>
	<p> Pisos para tu casa </p> 

	<script>
		var metros = parseInt(prompt(" cuantos metros cuadrados requieres? "));
		var piso = prompt(" Elige el tipo de piso\n1 es madera, 2 es loseta, 3 es vinilico " );
		var m2_madera = 60; 
		var m2_loseta = 70;
		var m2_vinilico = 35;
		var m2_total;
			
	if(piso == 1) 
	{
	m2_total = metros * m2_madera;
	}
	
	else if(piso == 2)
	{
	m2_total = metros * m2_loseta;
	}		
	
	else if(piso == 3)
	{
	m2_total = metros * m2_vinilico;
	}
		
	document.write("El costo del piso <strong> de madera es $ "  + m2_total + " m2 </strong> " );
	


		</script>
		
</body>

</html>
