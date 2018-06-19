# Modificar Velocidad

Ya aprendimos en el apartado [cambiar los valores de la botonera](/instalacion-de-la-programacion/cambiar-los-valores-de-la-botonera.md) como **entrar en la pestaña "Configuration.h"** de la programación.

Abrimos esa pestaña y localizamos la siguiente línea:

> `#define STEPPERS_STEPS_PER_SECOND 1000`

![Modificar Velocidad](/assets/modificar-velocidad.png)

Esta línea nos define los pasos por segundo que va a realizar el motor cada vez que pulsemos en el botón de ir adelante o atrás. **Si aumentamos el valor, aumentará la velocidad** y si disminuimos el valor, disminuye la velocidad.

El **límite está en torno a los 2300 steps**, dependerá del voltaje de las pilas que el valor sea mayor o menor.

> **Juego **- Dejar que los peques busquen por ellos mismos el límite del valor de los steps de su robot.

---

[![Licencia Creative Commons](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
[Escornabot](http://escornabot.com/web/), un robot gallego Open Source.  
Bajo licencia [Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License.](https://creativecommons.org/licenses/by-nc-sa/4.0/)
La recopilación de material de este curso ha sido elaborada por [Pablo Rubio Martínez](https://legacy.gitbook.com/@pablorubiomartinez)





