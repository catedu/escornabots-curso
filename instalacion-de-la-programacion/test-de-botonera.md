# Test de botonera

Antes de seguir es muy importante que aprendas a realizar el test de botonera. Lo tienes perfectamente explicado en [este enlace de la web oficial escornabot](https://escornabot.com/web/es/content/comprobacion-y-configuracion-de-las-lecturas-de-botonera).

* **Abre arduino**, un **nuevo proyecto** y **borra el código que aparezca**.

* **Pega el siguiente código:**

```
    #define KEYBOARD_PIN A4  
    #define KEYBOARD_WIRES 2 // change to 3 in old buttonsets with 3 wires

    void setup() {
      pinMode(KEYBOARD_PIN, KEYBOARD_WIRES == 2 ? INPUT_PULLUP : INPUT);
      Serial.begin(9600);
    }

    void loop() {
      Serial.println(analogRead(KEYBOARD_PIN));
      delay(200);
    }
```

![](/assets/13-testbotonera.png)

* **Conecta el Arduino Nano** al ordenador mediante un cable USB.
* En la pestaña herramientas **selecciona como placa "Arduino Nano"**.
* En la pestaña herramientas **selecciona como procesador "Atmega328P"**.
* En la pestaña herramientas **selecciona el puerto del PC** al que lo has conectado, en mi caso "COM14".



> **En las últimas versiones del IDE Arduino** hay un cambio que afecta a las placas que utilizamos y **debemos seleccionar en procesador; "ATmega328P \(Old Bootloader\)" **
>
> Toda la información en [esta entrada](https://www.arduino.cc/en/Guide/ArduinoNano)



![](/assets/14-testbotonera.png)

Ya tenemos todo listo para cargar el código.

* Primero le **damos al botón de verificar**, lo tienes en la **parte superior izquierda con un símbolo de una "V"**, al pulsar se abrirá una ventana para que guardes el proyecto con el nombre que te apetezca:



![](/assets/15-testbotonera.png)

> En la parte inferior nos tiene que aparecer el mensaje en Azul de compilado.



![](/assets/16-testbotonera-e1528627720378.png)



* Con este paso hemos confirmado que el código lo tenemos copiado de manera correcta.
* Ahora **vamos a subir el código** a nuestra placa, para eso **pulsaremos en el botón con forma de flecha** que tenemos al lado de verificar:



![](/assets/17-testbotonera-subir.png)



* Si todo ha ido bien en la parte inferior nos **tiene que aparecer en azul "Subido"** y ningún mensaje de error:



![](/assets/18-testbotonera-subir.png)

* Ahora **abrimos el monitor serie pulsando en la lupa que hay en la parte superior derecha** y nos aparece una ventana con un valor en torno a 1023. **Cada vez que dejemos pulsado un botón este valor cambiará**, anota el valor de cada botón.

> Recuerda, **la parte delantera** del robot **son los motores y el cableado**. La **parte trasera, la bola**.



![](/assets/19-testbotonera-subir.png)

