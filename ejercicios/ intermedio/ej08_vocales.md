Algoritmo ContarVocales
	Definir texto Como Cadena
	Definir vuelta, longitudTexto, contador Como Entero
	Definir letra Como Cadena
	contador <- 0
	Escribir 'Ingrese una palabra o frase corta:'
	Leer texto
	longitudTexto <- Longitud(texto)
	Para vuelta<-1 Hasta longitudTexto Con Paso 1 Hacer
		letra <- Subcadena(texto,vuelta,vuelta)
		letra <- Minusculas(letra)
		Si letra='a' O letra='e' O letra='i' O letra='o' O letra='u' Entonces
			contador <- contador+1 // Convierte a minúscula para facilitar la comparación
		FinSi
	FinPara
	Escribir '-----------------------------------'
	Escribir 'El texto contiene ', contador, ' vocal(es).'
FinAlgoritmo
