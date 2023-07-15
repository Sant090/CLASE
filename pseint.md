// primera parte
Algoritmo promedio

	definir objeto1 Como Real
	definir objeto2 Como Real
	definir objeto3 Como Real
	definir resultado Como Real
	
	Escribir "precio del objeto en la tienda 1"
	leer objeto1
	Escribir "precio del objeto en la tienda 2"
	leer objeto2
	Escribir "precio del objeto en la tienda 3"
	leer objeto3
	resultado = (objeto1+objeto2+objeto3)/3
	escribir "el promedio del precio de los 3 objetos es " resultado
FinAlgoritmo




// parte 2
Algoritmo conversion

	Definir metros Como Entero
	definir centimetros Como Real
	definir milimetros Como Real
	definir pulgadas Como Real
	
	escribir "cantidad de metros para convertir"
	leer metros
	
	centimetros = metros*100
	milimetros = metros*1000
	pulgadas = metros* 39.3701
	
	escribir metros, " metros, equivalen a " centimetros, " centimetros," milimetros, " milimetros y " pulgadas, " pulgadas. "
FinAlgoritmo
