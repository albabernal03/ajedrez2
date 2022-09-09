<h1 align="center"> Reina y Caballo</h1>

<h2>Repositorio:</h2>

Este es el link del [repositorio](https://github.com/albabernal03/ajedrez2)
***

<h2>¿De qué trata esta tarea?</h2>

En la siguiente tarea, realizaremos un algoritmo para encontrar solución a los siguientes problemas:

(1) Encontrar un algoritmo que calcule el número según la cantidad de movientos las posibles soluciones válidas de movimiento para la ficha del caballo.

(2) Encontrar un algoritmo que calcule las posiblidades de colocar n reina sin que estas queden enfrentadas.

***


<h2>Indice</h2>

1. [Ejercicio 1](#id1)
2. [Ejercicio 2](#id2)

***
<h2>Resolución (Con uso del pseudocódigo)</h2>

## Ejercicio 1:<a name="id1"></a>
Para este ejercicio hemos desarrollado la siguiente fórmula matemática que nos permite resolver el ejercicio: 
Partimos del caso _1=1 donde el número de posibilidades válidas es 20 y para n >1 se cumple que [caso_n = 2*caso_(n-1)+(2**(n-2))*6]


## Ejercicio 2:<a name="id2"></a>

```
Algoritmo posicion reinas

Entrada:

i, j: entero --> COMPARABLE
k, l: entero --> COMPARABLE

Precondición:

i=!k #esta condición impone que la fila deben ser distintas
j=! #esta condicion impone que las columnas han de ser distintas
i-j =! k-l #si se cumple esta condición sabemos que las fichas no pueden esatr en la misma diagonal (diagonal descendente)
i+j =! k+l  #si se cumple esta condición sabemos que las fichas no pueden esatr en la misma diagonal (diagonal ascendente)

Realización:

Debe comprobarse que las precundiciones establecidas se cumplan


```
