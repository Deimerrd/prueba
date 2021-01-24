# prueba
se realiza un algoritmo en donde en una fiesta solo pueden entrar mayores de edad a la fiesta y si estra despues de  las 2am la entrada es gratis de lo contrario no

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
