# ASD-Recursivo

Este proyecto implementa en Python los siguente algoritmos, los cuales son utilizados en el analisis sintactico:  

Algoritmo conjunto de primeros.
Algoritmo conjunto de Siguientes.
Algoritmo de conjuntos de predicción.

## Descripcion 
El programa permite calcular automaticamente los conjuntos a partir de una gramatica definia por el usuario. 

## Cómo ejecutar
Se abre el archivo desde la terminar de Windows o Linux. 


## Ejemplo de salida

Ejercicio1:
S : {'dos', 'uno', 'ε'}
A : {'dos', 'ε'}
B : {'tres', 'ε', 'cuatro', 'cinco'}


Ejercicio2:
S : {'$'}
A : {'uno', 'tres'}


Ejercicio3:
S -> A B uno : {'dos', 'uno'}
A -> ε : {'uno', 'tres'}

