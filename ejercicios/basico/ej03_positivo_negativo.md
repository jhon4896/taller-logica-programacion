Algoritmo Positivo_Negativo_o_Cero
		// Definición de variables
		Definir Numero Como Entero
		// Entrada de datos
		Escribir "Ingrese un número entero:"
		Leer Numero
		// revision de el numero para saber si es psitivo, negativo o es 0
		Si Numero > 0 Entonces
			Escribir "El número ", Numero, " es Positivo."
		SiNo
			Si Numero < 0 Entonces
				Escribir "El número ", Numero, " es Negativo."
			SiNo
				Escribir "El número es Cero."
			FinSi
		FinSi
FinAlgoritmo
