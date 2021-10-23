# Algoritmo-de-Dijkstra
implementacion del Algoritmo de Dijkstra en python utilizando min heap

## Descripcion
En el código implementado en Python se utiliza una representación de un **grafo** en forma 
de diccionario, de forma en que las claves son sus nodos, y el valor de cada clave es otro 
diccionario que contiene los nodos a los que está conectado, el nodo clave y el valor 
asociado es la distancia. Para calcular el camino más corto de otro grafo simplemente modifique el diccionario

### Estructura de datos
Para el resultado se utiliza varias estrucutras que tienen un maximo de tamaño O(n) donde n es el numero de nodos del grafo.

### Ejemplo
El resultado del algoritmo de Dijkstra para el grafo dado en el codigo es:

```python
s=['a', 'c', 'b', 'd', 'e', 'f', 'g', 'z'] 

distancia={'a': 0, 'b': 4, 'c': 3, 'd': 6, 'e': 7, 'g': 12, 'f': 11, 'z': 16}

previos={'a': None, 'b': 'a', 'c': 'a', 'd': 'c', 'e': 'd', 'g': 'e', 'f': 'd', 'z': 'g'}}
```