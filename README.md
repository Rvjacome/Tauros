# Tauros
MazeSolverRobot

Este proyecto es un robot Resuelve laberinto para competencia
- - - 

### Introducción:

El robot está basado en la plataforma **Pololu Zumo Arduino**, al que se le incorporan tres sensores de distancia _VL6180_, uno en el frontal, y otros dos a cada lado. Cuenta con dos micromotorreductores de tipo N20 DC Motor with Magnetic Encoder - 6V with 1:150 Gear Ratio.
El programa lee las paredes del laberinto a través de los sensores Sharp IR distance sensor, con lo que puede determinar en que dirección se puede mover (no hay pared), hacia adelante, derecha, izquierda o dar la vuelta si es necesario. Cuando avanza cuenta los pasos del encoder con lo que puede saber cuanto se mueve y determinar si ha avanzado una casilla. Por otra parte, , garantizando que los giros son completos y se encuentra en la orientación de destino. Como se indicó anteriormente, a través del sensor _QTR_ frontal el robot puede saber cuando entra en la meta.

![Tseo]("Tauros diseño implementado")

### Materiales:
* Pololu Zumo (sin balda)
* Raspberry pi pico W
* N20 DC Motor with Magnetic Encoder - 6V with 1:150 Gear Ratio.
* sensor-sharp-gp2y0a02yk0f-20-150cm
* Piezas impresas 3D PLA
* Tornillos de 3mm de diámetro para sujeción de piezas
* Cables para conexionado


**Ejemplo de tablero y colocación de casillas (16,16), y orientación física:**

![Tablero](https://github.com/Rvjacome/Tauros/blob/main/Imagenes/Robot.jpeg " Diseño del Robot ")
   

### Giros:

Cada vez que el robot gira a la derecha su orientación inicial se incrementa en 90º, mientras que si gira a la izquierda su orientación inicial se decrementa 90º. No hay que decir que cuando da media vuelta supone un giro de 180º, o lo que es lo mismo dos giros de 90º. 


### Condiciones iniciales:



### Desplazamientos y giros:

### Programa:


### Construcción:


### Simulacion en Ros2 Humble:
![Tablero](https://github.com/Rvjacome/Tauros/blob/main/Imagenes/rviz2.jpeg " Diseño del Robot ")


### Piezas impresas:


### Referencias:


### Autor:
**Robinson Vinicio Jacome Bejarano**

### Agradecimientos:



### Licencia:
Todos estos productos están liberados mediante

[1]:https://www.pololu.com/product/2506


