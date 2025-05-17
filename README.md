Propósito del Proyecto:
Este proyecto es un traductor e intérprete de un lenguaje personalizado que reconoce estructuras similares a switch-case con comandos como imprimir y salir. Utiliza ANTLR4 para generar analizadores léxicos y sintácticos, y un Visitor personalizado en JavaScript para traducir el código fuente del lenguaje definido a código JavaScript.


Funcionalidades:
Detecta errores de sintaxis.
Muestra el árbol de derivación.
Genera una tabla de tokens.
Traduce el código fuente a JavaScript.
Ejecuta comandos como imprimir (equivalente a console.log) y salir (equivalente a return).


Instalacion:
Clona este repositorio: git clone https://github.com/lucasdominguez90/51961.git


Uso:
Escribí tu código en input.txt. Por ejemplo:
segun 2 hacer {
  caso 1:
    imprimir("Número uno")
    salir
  caso 2:
    imprimir("Número dos")
    imprimir("¡Exacto!")
    salir
  defecto:
    imprimir("Número desconocido")
    salir
} finsgun

    
Ejecutá el programa con Node:
node index.js

El programa:
Verificará si hay errores.
Mostrará el árbol de derivación y los tokens.
Imprimirá el código traducido a JavaScript.
Mostrará información extra del Visitor si hay.


