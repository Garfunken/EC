# EC
Emsambly projects

En este repositorio colgaré ejercicios de programas hechos en ensamblador

## Encuestas

### [Ejercicio 1](https://github.com/Garfunken/EC/blob/master/Ejercicio%201.txt)

Diseñar un programa ensamblador que encienda alternativamente todos los
leds rojos en posiciones pares y todos los leds rojos en posiciones impares de la
placa DE2. 

### [Ejercicio 2](https://github.com/Garfunken/EC/blob/master/Ejercicio%202.txt)

Diseñar un programa ensamblador que encienda alternativamente cada uno de
los leds verdes de la placa DE2.

### [Ejercicio 3](https://github.com/Garfunken/EC/blob/master/Ejercicio%203.txt)

Diseñar un programa ensamblador que muestre en la placa DE2 un cero en el
primer display "siete-segmentos" y lo rote por los cuatro primeros displays
"siete-segmentos".

### [Ejercicio 4](https://github.com/Garfunken/EC/blob/master/Ejercicio%204.txt)

Diseñar un programa ensamblador que encienda en la placa DE2 los leds rojos
correspondientes a los interruptores que no estén activados.

## Interrupciones

### [Ejercicio 5](https://github.com/Garfunken/EC/blob/master/Ejercicio%205)

Utilizando interrupciones, diseñar un programa ensamblador del NIOS II que
encienda alternativamente, de uno en uno, todos los leds rojos de la placa DE2.
Inicialmente, el movimiento de encendido será hacia la izquierda comenzando
por el led rojo situado en la posición menos significativa. Cuando se pulse el
botón KEY1 la dirección del movimiento cambiará hacia la derecha. Cuando se
pulse el botón KEY2 la dirección de movimiento cambiará de nuevo hacia la
izquierda.

En el diseño del programa deben utilizarse dos tipos de interrupciones: las del
temporizador y las del panel de botones. Por un lado, el temporizador será
configurado para lanzar una interrupción periódicamente que indicará que
debe realizarse un desplazamiento en los leds. Por otro lado, el panel de
botones será configurado para lanzar una interrupción cuando se pulse un
botón.

