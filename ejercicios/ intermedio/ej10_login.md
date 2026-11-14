Algoritmo ValidarContrasena
	Definir clave Como Cadena
	Definir intentos Como Entero
	Definir acceso Como Lógico
	intentos <- 3
	acceso <- Falso
	Mientras intentos>0 Y  NO acceso Hacer
		Escribir 'Ingrese la contraseña (Intentos restantes: ', intentos, '):'
		Leer clave
		Si clave='12345' Entonces
			acceso <- Verdadero
		SiNo
			intentos <- intentos-1
			Escribir 'Contraseña incorrecta.'
		FinSi
	FinMientras
	Si acceso Entonces
		Escribir '¡Bienvenido!'
	SiNo
		Escribir 'Cuenta bloqueada.'
	FinSi
FinAlgoritmo
