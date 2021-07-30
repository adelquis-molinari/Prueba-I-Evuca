## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos: Se refiere a la manera de organizar los datos que tenemos en nuestro código. La más común es la de PILA, en donde el código se va apilando un arriba de otro y para ejecutar el primero se debe empezar por el ultimo en entrar asta llega al primero.

* Lista Enlazada: Son cuando vamos encadenando diferentes nodos dentro de un mismo objeto por medio de una propiedad.

* Árbol: Es otra forma de estructurar datos en los que los ordenamos por niveles donde tenemos una raíz (nodo superior) que tiene padres (nodos con hijos) desprende hijos (nodos con otros nodos) que tienen hojas (nodos sin hijos).

* Closures: Son funciones que pueden acceder a valores fuera de su ámbito de alcance.
ej.: var array =[];function sumarMas(){for (var i= 0; i < 10; i++){array.push(i)}}sumarMas();array

* Contexto de Ejecución: Se refiere al lugar donde un código se ejecuta es decir su contexto o entorno de ejecución, de inicio está el contexto global donde todos se pueden relacionar. Las funciones son un contexto local que tienen un scope y los valores pasados por parámetros están en un contexto tipo block.

* Variable THIS: La variable THIS hace referencia al objeto en donde está, es decir, var obj={this.nombre=Adelkis}; el this está haciendo referencia al obj que tiene como propiedad nombre a Adelkis.

* Hoisting: Es como JavaScript interpreta nuestro código antes de ejecutarlo, haciendo que las declaraciones de las variables se eleven (suban en el contexto de ejecución) y esperen por su inicialización no se mueve el código sino es cono lo interpreta o da su orden de prioridad.

* Pasar por valor y por referencia: cuando asignamos un dato a una variable lo pasamos por valor (var num = 1;) mientras que si lo asignamos por una variable lo hacemos por referencia (var num2= num); 

* Algoritmo: Son un conjunto de instrucciones bien definidas para poder realizar una tarea correctamente.

* Big O notation: es una forma para ver qué tan bueno es un algoritmo para ciertos casos, que tan malo es para otros y ver la complejidad del mismo.

* Inmediatly Invoked Function Expression (IIFF): son funciones que se ejecutan tan pronto como se define es decir que se auto ejecutan inmediatamente, ej.: (function(){var veloz ='soy rapido'; return veloz})();
Las variables declaradas por dentro de la función no pueden ser accedidas por fuera.
