Algoritmo CalcularFactorial
	Definir numeroEntero, vuelta Como Entero
	Definir factorial Como Real
	factorial <- 1
	Escribir 'Ingrese un número entero positivo:'
	Leer numeroEntero
	Si numeroEntero>=0 Entonces
		Para vuelta<-1 Hasta numeroEntero Con Paso 1 Hacer
			factorial <- factorial*vuelta
		FinPara
		Escribir '-----------------------------------'
		Escribir 'El factorial de ', numeroEntero, '! es: ', factorial
	SiNo
		Escribir 'Error: El número debe ser positivo o cero.'
	FinSi
FinAlgoritmo
