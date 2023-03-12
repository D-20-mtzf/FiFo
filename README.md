# Metodo fifo
FIFO (First In, First Out) es una estructura de datos que se utiliza en programación para organizar y gestionar un conjunto de elementos en el orden en que fueron añadidos. Es similar a una cola en la vida real: los elementos se agregan al final de la cola y se eliminan del frente.

## Ejemplo
En este ejemplo, creamos una clase FIFO que tiene tres métodos: agregar, eliminar y esta_vacia.

![](https://cdn.discordapp.com/attachments/980278659657138216/1084266507871207565/image.png)

El método agregar recibe un elemento y lo agrega al final de la cola, usando el método append() de la lista.
El método eliminar elimina el primer elemento de la cola y lo devuelve, utilizando el método pop(0) de la lista para eliminar el elemento en la primera posición.
el método esta_vacia simplemente comprueba si la cola está vacía, devolviendo True si la longitud de la lista de elementos es cero.

![](https://cdn.discordapp.com/attachments/980278659657138216/1084269276048916520/image.png)

En esta parte hacemos una instancia de la clase FIFO, agregamos tres valores enteros haciendo uso del método agregar para después eliminarlos uno por uno como lo es el método fifo.
Pero sucede que el método esta_vacia devuelve false por que aún queda un elemento en la fila.
