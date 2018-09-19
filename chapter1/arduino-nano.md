# Arduino NANO

Es el **cerebro del  robot** y donde [cargaremos nuestro código](/instalacion-de-la-programacion.md) a través de una conexión Micro o Mini-USB para conectarlo a nuestro ordenador.

Tiene dos filas de pinchos o patillas soldados en cada lateral y lo pondremos sobre la [protoboard](/chapter1/protoboard-170-puntos.md).

![](https://roboticafacil.es/wp-content/uploads/2017/04/Arduino-Nano-V3-2-e1492726589312.jpg)  

**Cada pincho esta conetado a un PIN que viene marcado con un nombre concreto y tiene una función concreta.**. En esta imagen, sacada de la web de [Luis Llamas](https://www.luisllamas.es) puedes ver la correspondencia:

![](https://www.luisllamas.es/wp-content/uploads/2015/11/aduino-pinout-nano.png)

# ¿Qué necesitas saber?

**No hace falta comprender el funcionamiento** completo de la placa, con **entender porque vamos a utilizar los pines donde conectaremos Escornabot es suficiente**. Si alguien tiene interés en adquirir conocimiento extra, durante el curso tendrá enlaces a páginas web donde poder conseguirlo.

### [Placa botonera](/chapter1/placa-botonera.md)

Utilizaremos tres cables \(también llamados hilos\), aunque con dos sería suficiente:

| PIN Arduino NANO | ¿Por qué? |
| :--- | :--- |
| 5V | 5V - Alimentar la placa botonera |
| A4 | Sig - Transmitir las ordenes de los botones a la placa Arduino NANO para que luego esta de las ordenes a los motores. |
| GND | GND - Aunque no es correcto del todo lo llamaremos tierra o masa que es un término más conocido. |

### [Porta Pilas](/chapter1/portapilas-4-unidades-aa.md)

| PIN Arduino NANO | ¿Por qué? |
| :--- | :--- |
| VIN | El portapilas contiene 4 pilas de 1,5 V así que la entrada de corriente será de 6V y este es el **único PIN que admite corriente desde 6V a 12V.** |
| GND | Tierra o masa |

### [Drivers ULN2003](/chapter1/drivers-uln2003.md)

| PIN Arduino NANO | ¿Por qué? |
| :--- | :--- |
| VIN | En esta placa van conectados los motores y necesitaremos conectarlo a este pin para poder coger corriente del Porta Pilas que conectaremos justo encima de los dos cables de corriente de los drivers. |
| GND | Tierra o masa |
| D9, D8, D7, D6 \(en algunas placas 9, 8, 7, 6\) | **Conexión del motor izquierdo** al Arduino Nano para poder recibir las ordenes de los movimientos y transmitirlas posteriormente al motor. |
| D5, D4, D3, D2 \(en algunas placas 5, 4, 3, 2\) | **Conexión del motor derecho** al Arduino Nano para poder rescibir las ordenes de los movimientos y transmitirlas posteriormente al motor. |

### [Buzzer 5V](/chapter1/buzzer-5v.md)

| PIN Arduino NANO | ¿Por qué? |
| :--- | :--- |
| D10 \(en algunas placas 10\) | Para poder recibir las ordenes del Arduino NANO y ejecutar los pitidos según las pulsaciones de los botones. |
| GND | Tierra o masa |












