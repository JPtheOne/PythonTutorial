# PythonTutorial
## Manejo de variables

Los tipos de datos de python se usan para definir el tipo de variable. Los que soporta son: 
1. Tipos de dato numéricos: *int, float, complex*
2. Tipos de dato string: *str*
3. Tipo de dato de sequencia:*listas, tuplas*
4. Datos de mapeo: *diccionarios*

 El método **type()** sirve para imprimir a que tipo de dato pertenece una variable. A continuación se muestran ejemplos de declaración de estas variables mencionadas (P, 2023).
 
```
#Variables numéricas
number = 1234
pi = 3.1417
irrational = 100 +2j

#Variables string
greeting = "Hello World"
onequote = 'Hi!'

#Lista y tupla
everyDataList = [33, "Hello world", 1.618]
untouchable = ("Hi", 44, 22.324)
```
## Listas
Una lista en Python es un tipo de datos nativos construido dentro del lenguaje de programación Python. Estas listas son similares a matrices (o arrays) que se encuentran en otros lenguajes. Sin embargo, en Python se manejan como variables con muchos elementos. Las listas tienen las siguientes características principales:

1.Ordenada: esto quiere decir que los elementos dentro de ella están indexados y se accede a ellos a través de una locación indexada. 

2. Editable: los elementos dentro de una lista pueden editarse, añadir nuevos o eliminar los que ya tiene. 

3. Dinámica: las listas pueden contener diferentes tipos de datos y hasta de objetos. Esto significa que pueden soportar paquetes multidimensionales de datos, como un array o muchos objetos. 

4. No única: esencialmente, esto quiere decir que la lista puede contener elementos duplicados sin que arroje un error (Londoño,2023). 

Las listas poseen la ventaja de ser altamente manipulables a a través de métodos ya integrados en Python. A continuación se ofrece una lista de los métodos más comunes junto con su descripción.
1. append(): Agrega un elemento al final de la lista
2. clear(): Elimina todos los elementos de la lista
3. copy(): Devuelve una copia de la lsita
4. count(): Devuelve el número de elementos del valro que se dio como argumento.
5. extend(): Agrega los elementos de la lista (o de cualquier iterable) al final del a lista actual.
6. index(): Devuelve el índice del primer elemento con el valor específicado
7. insert(): Agrega un elemento en la posición dada
8. pop(): Quita el elemento de la posición dada
9. remove(): quita el elemento con el valor dado
10. reverse(): invierte el orden de la lista
11. sort(): ordena la lista

## Diccionarios 
Los diccionarios en Python nos permiten almacenar una serie de mapeos entre dos conjuntos de elementos, llamados keys and values (Claves y Valores).
De igual forma, posee ciertas características:
1.Todos los elementos en el diccionario se encuentran encerrados en un par de corchetes {}.
2.Cada elemento en un diccionario contiene una clave y un valor - es decir un par de clave-valor.
3.Cada par de clave-valor es denominado como elemento (item).
4. La ventaja de esto es que puedes acceder a todos los valores almacenados 
usando simplemente las claves (Torres,2021).

A continuación se presenta un ejemplo de declaración de un diccionario.
```
numVariables = {
                "integer": number, 
                "rational": pi,
                "complex": irrational,
                "string": greeting
                }
```
## Bibliografía
Londoño, P. (2023, 13 febrero). *Listas en Python: qué son, cómo crearlas y ordenarlas.* https://blog.hubspot.es/website/lista-python

P. (2022, 3 agosto). *Python Data Types (With Complete List).* DigitalOcean Community. https://www.digitalocean.com/community/tutorials/python-data-types

Torres, A. (2021, 27 septiembre). Comprensión de Diccionario en Python: Explicado con ejemplos. freeCodeCamp.org. https://www.freecodecamp.org/espanol/news/compresion-de-diccionario-en-python-explicado-con-ejemplos/
