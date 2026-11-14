Algoritmo Cálculo_de_Promedio
	// Definición de variables
    Definir suma, promedio Como Real
	Definir nota1, nota2, nota3, notaminima Como Real
	Definir aprobado, desaprobado Como logico
	//pedir las notas
	Escribir "porfavor ingerse las 3 notas que desea saber el promedio enter 10 a 100";
	Leer nota1;
	Leer nota2;
	leer nota3;
	// suma de notas y saber el promedio
	suma <- nota1+nota2+nota3
	promedio <-suma/3
	//evaluacion logica para saber el estado de estudiante
	aprobado <- promedio >= 60
	notaminima <- 60
	desaprobado <- promedio < 60
	//Mostrar resultado
	Si aprobado Entonces
        // Verificamos si pasó exactamente con el mínimo
        Si promedio == notaminima Entonces
            Escribir "¡Estado: Aprobado raspando con la nota mínima!"
			Escribir "Su promedio es: ", promedio
        Sino
            Escribir "¡Estado: Aprobado!"
			Escribir "Su promedio es: ", promedio
        FinSi
    SiNo
        Escribir "Estado: Desaprobado"
		Escribir "Su promedio es: ", promedio
    FinSi
FinAlgoritmo
