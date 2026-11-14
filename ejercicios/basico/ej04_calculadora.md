Algoritmo Calculadora_Básica
	// Definición de variables
    Definir numero1, numero2, opcion Como Entero
    Definir resultado Como Real
    // Entrada de números
    Escribir "porfavor Ingrese el primer número entero:"
    Leer numero1
    Escribir "porfavor Ingrese el segundo número entero:"
    Leer numero2
    // Mostrar el menú de opciones
    Escribir "Seleccione la operación a realizar:"
    Escribir "1: Suma"
    Escribir "2: Resta"
    Escribir "3: Multiplicación"
    Escribir "4: División"
    Leer opcion
    // Estructura para evaluar la opción seleccionada
    Segun opcion Hacer
        1:
            resultado <- numero1 + numero2
            Escribir "El resultado de la suma es: ", resultado
        2:
            resultado <- numero1 - numero2
            Escribir "El resultado de la resta es: ", resultado
        3:
            resultado <- numero1 * numero2
            Escribir "El resultado de la multiplicación es: ", resultado
        4:
            // Validación para evitar la división por cero
            Si numero1 = 0 o numero2 = 0 Entonces
                Escribir "Error: No se puede dividir entre cero."
            SiNo
                resultado <- numero1 / numero2
                Escribir "El resultado de la división es: ", resultado
            FinSi
        De Otro Modo:
            Escribir "Opción no válida. Debe elegir un número del 1 al 4."
    FinSegun
FinAlgoritmo
