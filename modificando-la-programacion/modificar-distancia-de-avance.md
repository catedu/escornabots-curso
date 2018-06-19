# Modificar Velocidad de avance

Este apartado además de servir para trabajar medidas, reglas de tres o distancias. Nos permite modificar el avance para jugar en tableros que ya tengamos de otros robots con casillas de 15 cm.

Con la programación abierta y situados en la pestaña "Configuration.h" localizamos la siguiente línea:

>`#define STEPPERS_LINE_STEPS 1738`

![Modificar Distancia](/assets/Modificar-distancia.png)

El **valor 1738 equivale a un avance de 10cm** cada vez que pulsemos los botones para desplazarnos adelante o atrás.

Realizando una regla de tres simple, podemos ver que **el valor de avance de 1cm será de 174 **(se redondea el valor porque los decimales no se van a tener en cuenta)

Sabiendo el avance de un centímetroo podemos cambiar el valor para que desplace la distancia que queramos.

> **Juego **- Practicar reglas de tres para que calculen diferentes distancias con marcas en el suelo que deben ir alcanzando.

---

[![Licencia Creative Commons](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
[Escornabot](http://escornabot.com/web/), un robot gallego Open Source por [Pablo Rubio Martínez](https://legacy.gitbook.com/@pablorubiomartinez).  Bajo licencia [Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License.](https://creativecommons.org/licenses/by-nc-sa/4.0/)



