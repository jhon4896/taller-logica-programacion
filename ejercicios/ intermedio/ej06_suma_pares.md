Algoritmo SumaNumerosPares
	// definir variabes
	Definir numeroEntero, suma, vuelta Como Entero
	suma <- 0
	// ingerso de datos
	Escribir 'Ingrese un número entero '
	Leer numeroEntero
	// fromula
	Para vuelta<-1 Hasta numeroEntero Con Paso 1 Hacer
		Si vuelta MOD 2=0 Entonces
			suma <- suma+vuelta
		FinSi
	FinPara
	// resultado
	Escribir 'La suma de los números pares entre 1 y ', numeroEntero, ' es: ', suma
FinAlgoritmo

