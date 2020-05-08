## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos:  Son distintas formas eficientes de organizar los datos, que podemos utilizar según los requerimientos de nuestras tareas
 u objetivos, para que la búsqueda de un dato en particular sea rápida. 

* Lista Enlazada: Es una lista de datos que, aparte de información, contienen un link al dato o nodo siguiente, formando una lista de nodos, que 
pueden estar simple o doblemente enlazados. Estos útimos tienen un link al nodo anterior, y otro al nodo siguiente, y permiten desplazarse de 
atrás hacia adelante.


* Árbol: Al igual que las listas,  un árbol se compone por nodos que contienen datos y links a otros nodos. Tienen un nodo raíz, que es el nodo 
superior; que a su vez es un nodo padre, es decir que tiene nodos hijos, que a su vez pueden ser padres. Esto se repite hasta llegar a las hojas 
del árbol, que son nodos sin hijos. En un árbol, sólo se puede ir en dirección hacia los hijos, y no puede haber nodos sueltos, todos tienen
que estar conectados. El tipo de árbol más utilizado es el árbol binario, en el cual cada nodo sólo puede tener hasta 2 hijos.

* Closures:  son funciones dentro de funciones, que tienen acceso a variables que están por fuera de su scope. Pueden tener sus propias variables, usar las del objeto
global, y las de la función que la contiene. La función externa no puede acceder a las variables definidas dentro de la función interna, pero 
las variables de la función interna sólo existen cuando la función externa es ejecutada. 

* Contexto de Ejecución: es el contexto en el que se ejecuta nuestro código, puede estar en el contexto global (fuera de funciones), dentro
de una función, dentro de un closure.


* Variable THIS: This toma su valor dependiendo del lugar donde se encuentre,  cuando la función no es parte del prototipo de una función 
constructora, el valor de this será igual al objeto window. Cuando se usa this dentro de un método, el valor de this será equivalente al
 elemento en el que se ejecuta al método.

* Hoisting:   las declaraciones de variables y funciones son "movidas" al comienzo del código por defecto, para que JavaScript pueda operarlas.
Las variables son declaradas, pero no tienen un valor, hasta llegar al espacio del código en que se les ha asignado uno.

* Pasar por valor y por referencia: al pasar por valor se crea una copia local de la variable dentro de la función. En cambio al pasar
 por referencia se manipula directamente la variable, y los cambios realizados dentro de la función  afectan a la variable por fuera de la misma .


* Algoritmo:  un algoritmo es una serie de instrucciones que, al seguirlas nos permiten resolver problemas. En una computadora, es la serie de 
pasos que tiene que seguir para  completar una tarea. Hay muchas formas de completar una misma tarea, pero hay formas mucho más eficaces
que otras, porque son más rápidas, o usan menos  recursos, o son más fáciles, etc. Es importante recurrir a la eficacia a la hora de resolver
problemas. 

* Big O notation: es una expresión matemática que nos dice cuanto tiempo tarda un algoritmo en ejecutarse, tomando el peor caso posible, osea
el caso en el que se tardaría más tiempo. Es una manera de clasificar los algoritmos por su eficacia, complejidad y velocidad. 

* Inmediatly Invoked Function Expression (IIFF): es una forma de ejecutar la función inmediatamente después de definirla, utilizando (). Se usa
para asegurarse de que las variables  sólo son accesibles desde dentro del scope de la función.

