# Drivers ULN2003

En el **conector blanco** de la placa pondremos ** los motores**. **Cada motor debe ir conectado al driver de su lado **o el robot se movera al contrario de las ordenes que le demos.

Encima del conector blanco tenemos **cuatro pines o pinchos** que son los que **conectaremos a los pines D9-D2 **de la placa Arduino NANO.

A la izquierda tenemos **dos pines o pinchos** que son los encargados de recibir la alimentación del portapilas, están **marcados con la serigrafía 5-12V  y  +/-**

![](/assets/driver-uln2003.jpg)

> Recuerda el cuadro de conexiones:

| PIN Arduino NANO | PIN Driver | ¿Por qué? |
| :--- | :--- | :--- |
| VIN | 5-12V \(+\) | En esta placa van conectados los motores y necesitaremos conectarlo a este pin para poder coger corriente del Porta Pilas que conectaremos justo encima de los dos cables de corriente de los drivers. |
| GND | 5-12V \(-\) | Tierra o masa |
| D9, D8, D7, D6 \(en algunas placas 9, 8, 7, 6\) | IN1, IN2, IN3, IN4 | **Conexión del motor izquierdo** al Arduino Nano para poder recibir las ordenes de los movimientos y transmitirlas posteriormente al motor. |
| D5, D4, D3, D2 \(en algunas placas 5, 4, 3, 2\) | IN1, IN2, IN3, IN4 | **Conexión del motor derecho** al Arduino Nano para poder rescibir las ordenes de los movimientos y transmitirlas posteriormente al motor. |



