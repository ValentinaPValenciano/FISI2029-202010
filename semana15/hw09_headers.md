# HW09 Headers (c++)

150 puntos

Cree un script "tarea.sh" que:
    1.  compile un archivo "main.cpp" incluyendo el encabezado "funciones.h"
    2.  ejecute el archivo "a.out" y redireccione la salida a un archivo "datos.txt"
    3.  ejecute un script de python que grafique "datos.txt" y guarde el resultado en un bonito archivo "grafico.pdf" con las debidas etiquetas de los datos.

## main.cpp  20pts
Vamos a simular el movimiento rectilineo uniformemente acelerado de una piedra con 
altura inicial = 0 m y velocidad inicial 20 m/s hacia arriba. La evolucion temporal va a estar dada por
una funcion dentro de "funciones.h". Utilice "cout" para imprimir en pantalla tiempo y altura
mientras que la altura de la piedra sea positiva.

## funciones.h 20pts
La evolucion temporal se implementa como una funcion RungeKutta4 que es invocada desde main.cpp

## grafica.py 20pts
Grafica los datos.

## script.sh 20pts
Ejecuta todo.

## grafico.pdf 20pts
Si todo se genera automaticamente bien, y el grafico es bonito, 20 pts.


## Subir a GIT 50pts
Suba a su repositorio (el mismo de las clases anteriores) la carpeta de trabajo, esta debe contener "tarea.sh", "main.cpp", "funciones.h", "grafica.py".
Entregar el enlace de esta carpeta.
Por cada archivo adcional se restan 20 puntos. EJ. datos.txt, grafico.pdf y otras cosas que se les ocurran.
