Algoritmo SerieFibonacci
	Definir n, a, b, temp, vuelta Como Entero
	Escribir 'Ingrese la cantidad de términos de Fibonacci a mostrar:'
	Leer n
	a <- 0
	b <- 1
	Escribir 'Los primeros ', n, ' términos son:'
	Para vuelta<-1 Hasta n Con Paso 1 Hacer
		Si vuelta=1 Entonces
			Escribir a, ' 'Sin Saltar
		SiNo
			Si vuelta=2 Entonces
				Escribir b, ' 'Sin Saltar
			SiNo
				temp <- a+b
				a <- b
				b <- temp
				Escribir b, ' 'Sin Saltar
			FinSi
		FinSi
	FinPara
	Escribir ''
FinAlgoritmo // Salto de línea final
