# Modificar Velocidad de avance

Este apartado además de servir para trabajar medidas, reglas de tres o distancias. Nos permite modificar el avance para jugar en tableros que ya tengamos de otros robots con casillas de 15 cm.

Con la programación abierta y situados en la pestaña "Configuration.h" localizamos la siguiente línea:

>`#define STEPPERS_LINE_STEPS 1738`

![](/assets/Modificar-distancia.png)

El **valor 1738 equivale a un avance de 10cm** cada vez que pulsemos los botones para desplazarnos adelante o atrás.

Realizando una regla de tres simple, podemos ver que **el valor de avance de 1cm será de 174 **(se redondea el valor porque los decimales no se van a tener en cuenta)

Sabiendo el avance de un centímetroo podemos cambiar el valor para que desplace la distancia que queramos.

> **Juego **- Practicar reglas de tres para que calculen diferentes distancias con marcas en el suelo que deben ir alcanzando.












