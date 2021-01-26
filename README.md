<!DOCTYPE html>
<html>
<head>
	<title></title>
	<meta charset="utf-8"></meta>
</head>
<body>
<script src="codigo.js"></script>
	
</body>
</html>


____
HTML
__


JAVASCRIP



function mayoredad() {

	let edad=prompt("que edad tienes");
	

	if(edad>=18){

		document.write("puede ingresar a la fiesta");


	} 


	else{

		document.write("usted es menor de edad no puede ingresar <br>")
	}

	// body...
}

function ingreso(){
let ingresos=prompt("hora de ingreso");

if(ingresos>2){
	document.write("  y no pagar entrada")
}else{

	document.write("   debe  pagar entrada");
}

}

mayoredad();
ingreso();
