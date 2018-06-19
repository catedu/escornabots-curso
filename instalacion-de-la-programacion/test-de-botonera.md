# Test de botonera

Antes de seguir es muy importante que aprendas a realizar el test de botonera. Lo tienes perfectamente explicado en [este enlace de la web oficial escornabot](https://escornabot.com/web/es/content/comprobacion-y-configuracion-de-las-lecturas-de-botonera).

* **Abre arduino**, un **nuevo proyecto** y **borra el código que aparezca**.
* **Pega el código del enlace anterior**.

![Test Botonera Escornabot](/assets/13-testbotonera.png)

* **Conecta el Arduino Nano** al ordenador mediante un cable USB.
* En la pestaña herramientas **selecciona como placa "Arduino Nano"**.
* En la pestaña herramientas **selecciona como procesador "Atmega328P"**.
* En la pestaña herramientas **selecciona el puerto del PC** al que lo has conectado, en mi caso "COM14".

![Seleccionar Placa Arduino](/assets/14-testbotonera.png)

Ya tenemos todo listo para cargar el código.

* Primero le **damos al botón de verificar**, lo tienes en la **parte superior izquierda con un símbolo de una "V"**, al pulsar se abrirá una ventana para que guardes el proyecto con el nombre que te apetezca:

![Verificar Código Test Botonera](/assets/15-testbotonera.png)

> En la parte inferior nos tiene que aparecer el mensaje en Azul de compilado.

![Test Botonera Compilado](/assets/16-testbotonera-e1528627720378.png)

* Con este paso hemos confirmado que el código lo tenemos copiado de manera correcta.
* Ahora **vamos a subir el código** a nuestra placa, para eso **pulsaremos en el botón con forma de flecha** que tenemos al lado de verificar:

![Test Botonera Subir](/assets/17-testbotonera-subir.png)

* Si todo ha ido bien en la parte inferior nos **tiene que aparecer en azul "Subido"** y ningún mensaje de error:

![Test Botonera Subido](/assets/18-testbotonera-subir.png)

* Ahora **abrimos el monitor serie pulsando en la lupa que hay en la parte superior derecha** y nos aparece una ventana con un valor en torno a 1023. **Cada vez que dejemos pulsado un botón este valor cambiará**, anota el valor de cada botón.

> Recuerda, **la parte delantera** del robot **son los motores y el cableado**. La **parte trasera, la bola**.

![Monitor Serie Arduino](/assets/19-testbotonera-subir.png)

---

[![Licencia Creative Commons](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
[Escornabot](http://escornabot.com/web/), un robot gallego Open Source por [Pablo Rubio Martínez](https://legacy.gitbook.com/@pablorubiomartinez).  Bajo licencia [Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License.](https://creativecommons.org/licenses/by-nc-sa/4.0/)

