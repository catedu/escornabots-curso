# Portapilas 4 unidades AA

El portapilas **proporciona la energía para el movimiento** del robot.

![](/assets/portapilas-AA.jpg)


Lleva **4 pilas del tipo AA**, hay que fijarse al introducir las pilas para hacerlo en el sentido correcto. Parece algo evidente pero no sería la primera, ni la última vez que una persona las coloca mal y se coge un buen calentón.


Una regla que suelo usar con los peques:

* La **parte plana de la pila**, va siempre **en el lado del muelle**
* La parte de la pila que tiene un saliente, en el otro lado.

> Recuerda el cuadro de conexiones:

| PIN Arduino NANO | Portapilas | ¿Por qué? |
| :--- | :--- | :--- |
| VIN | Cable rojo \(+\) | El portapilas contiene 4 pilas de 1,5 V así que la entrada de corriente será de 6V y este es el **único PIN que admite corriente desde 6V a 12V.** |
| GND | Cable negro \(-\) | Tierra o masa |

La terminación de los cables se puede [crimpar para tener un conector macho](https://twitter.com/pablorubma/status/1025662847265779713) en el extremo.



