El TP2 fue desarrollado utilizando una estructura dinámica para cada categoría léxica, comentario/s y caracter/cadena no reconocida.

Dentro del archivo funciones.h se encuentra declarados todos los struct y las funciones para cada
categoría léxica, comentario/s y caracter/cadena no reconocida.

La elección de cada estructura dinámica se realizó de acuerdo a lo solicitado en el tp, utilizando una pila cuando no se requería ningún orden o busqueda dentro de la estructura, una cola para los puntos que requería respetar el orden de aparición en el archivo a realizar el análisis léxico, y una lista cuando se debía recorrer la estructura dinámica.

Por cada reporte pedido se generó un archivo.c cuyo nombre está relacionado con la categoría, dentro del cual se encuentra la definición de la función de generación de los nodos y la función necesaria para imprimir por consola la información requerida.

El hecho de utilizar una función para cada categoría y no unificar struct o funciones similares fue con el propósito de darle mayor expresividad al código.
