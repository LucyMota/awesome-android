Awesome Android
===============

A curated list of awesome Android frameworks, libraries and software.

## Contribuir

Por favor lea la siguiente [guía](CONTRIBUTING.md) para poder contribuir 
con el 
proyecto.

Este es un documento de acceso público en el que se pretende recopilar las mejores librerías, herramientas, libros, sitios webs para desarrollar y usar en proyectos Android.

## Listado 

- [Librerías](#librerias)

  - [Imágenes](#imagenes)
  - [Bases de datos](#bases-de-datos)
    - [greenDAO](#greendao)
  - [Conectividad Web](#conectividad-web)
    - [Volley](#volley)
    - [RoboSpice](#robospice)
  - [Bluetooth](#bluetooth)
    - [BluetoothSPP](#bluetoothspp)
  - [Realidad aumentada](#realidad-aumentada)
    - [Vuforia](#vuforia)
  - [Video Juegos](#video-juegos)
    - [LibGDX](#libgdx)

- [Herramientas](#herramientas)
    - [PID cat](#pid-cat)

- [Otros recursos](#otros-recursos)

  - [Libros](#libros)
  - [Redes sociales](#redes-sociales)
  - [Sitios webs](#sitios-webs)

## Librerias

### Imagenes

Listado de librerías sobre la carga y manipulación de imágenes:

TO DO:

### Bases de datos

Listado de librerías para relacionadas con las bases de datos y almacenamiento de información:

#### greenDAO

**Descripción:** greenDAO es un ORM que nos va a ayudar a crear y manejar el modelo de base de datos SQLite que vamos a usar en nuestra aplicación.

**URL del proyecto:** http://greendao-orm.com

**Vídeos:**
- **Caso práctico con greenDAO:** https://www.youtube.com/watch?v=GwWO-zDKJBo

**Tutoriales:** 
- http://greendao-orm.com/documentation/how-to-get-started

**Comentarios:**
- **Jackgris:** Le eh utilizado en varios proyectos, creo que esta muy bien armada, algo que me agrado, de una forma muy sencilla podes dejar el manejo del modelo totalmente separado del proyecto. Dejando visible en este unicamente el uso de las operaciones CRUD.

### Conectividad Web

Listado de librerías para facilitar la tarea de realizar solicitudes Web:

#### Volley

**Descripción:** Volley es una librería que hace fácil y más rápido el trabajo de hacer peticiones Web.

**URL del proyecto:** https://android.googlesource.com/platform/frameworks/volley/

**Vídeos:**
- **Charla sobre la librería:** https://www.youtube.com/watch?v=yhv8l9F44qo

**Tutoriales:** 
- http://www.androidhive.info/2014/05/android-working-with-volley-library-1/

**Comentarios:**
- **Juande:** Librería muy fácil de usar. Te quita todo el trabajo sucio.

#### RoboSpice

**Descripción:** Es una librería ayudar a tratar tareas que pueden demorar un largo tiempo en realizarce de forma sencilla, especialmente tratando peticiones a travez de la red.

**URL del proyecto:** https://github.com/stephanenicolas/robospice

**Vídeos:**
- https://www.youtube.com/watch?v=ONaD1mB8r-A

**Tutoriales:** 
- https://github.com/stephanenicolas/robospice/wiki

**Comentarios:**
- **Jackgris:** Sencilla de usar, con varios ejemplos, mucho trabajo y tiempo de desarrollo.

### Realidad aumentada

Listado de librerías para facilitar la tarea de realizar aplicaciones que deban utilizar realidad aumentada:

#### Vuforia

**Descripción:** Es una librería que nos va a dar una interfaz configurable para el uso de realidad aumentada en nuestras aplicaciones.

**URL del proyecto:** https://developer.vuforia.com/getting-started-overview

**Vídeos:**
- https://www.youtube.com/watch?v=iBk_3m7Zx4s

**Tutoriales:** 
- https://developer.vuforia.com/resources/dev-guide/getting-started-android-native-sdk

**Comentarios:**
- **Jackgris:** Una vez que configuramos nuestro entorno de desarrollo, no resulta complicado poder explotar los recursos del manejo de la realidad aumentada en nuestra aplicación.

### Bluetooth

Listado de librerías para facilitar la tarea de realizar aplicaciones que deban utilizar bluetooth:

#### BluetoothSPP

**Descripción:** Es una librería que nos va a dar una interfaz configurable para el uso del bluetooth en nuestras aplicaciones.

**URL del proyecto:** https://github.com/akexorcist/Android-BluetoothSPPLibrary

**Vídeos:**
- https://www.youtube.com/watch?v=XqxV9QOqkiI

**Tutoriales:** 
- http://tutorial.invention-zone.com/bluetooth-hc-05-module/

**Comentarios:**
- **Jackgris:** Lo poco que la eh utilizado, parece ser muy fácil de utilizar y bastante completa

## Video Juegos

Listado de framework que nos van a ser de utilidad en el desarrollo de video juegos en 2D y 3D en Android

### LibGDX

**Descripción:** Es un framework que nos va a dar una interfaz configurable para armar nuestros proyectos dedicados al desarrollo de video juegos 2D y 3D. Ademas de ayudarnos a que el mismo sea multiplataforma a pesar de trabajar con código nativo (Java) y aprovechar al máximo el rendimiento de la GPU utilizando OpenGL.

**URL del proyecto:** http://libgdx.badlogicgames.com

**Vídeos:**
- https://www.youtube.com/watch?v=IBsvuT7MzpY

**Tutoriales:** 
- https://github.com/Jackgris/wikiLibGDX_es
- https://github.com/libgdx/libgdx/wiki

**Comentarios:**
- **Jackgris:** Creo que esta herramienta acelera mucho el desarrollo de video juegos, es libre, utiliza Gradle (sistema de contrucción de proyecto apoyado por Google) y hace que sea muy facil portar nuestro proyecto a la Web, IOS, y Escritorio.

## Herramientas

Listado de herramientas que nos van a ser de utilidad en el desarrollo de aplicaciones Android

#### PID cat

**Descripción:** Esta herramientas es una mejora del script llamado logcat color que nos va a mostrar toda la salida de logcat en diferentes colores dependiendo del tipo, restringiendo unicamente a la salida que corresponde a nustra aplicación en nuestra terminal.

**URL del proyecto:** https://github.com/JakeWharton/pidcat

**Uso:** Como dice en la web del proyecto, una vez configurada,  unicamente debemos ejecutar el script seguido del nombre del paquete de nuestra aplicación, y podremos ver una hermosa salida del logcat coloreada unicamente de nuestra aplicación, sin que se mezcle con el resto de la salida del sistema.
Aclaración: al ser un script en Python, podremos utilizarlo en cualquier sistema que tengamos el SDK de Android y un interprete de Python instalado.

**Comentarios:**
- **Jackgris:** En mi caso que me gusta utilizar mucho el logcat cuando desarrollo, esta herramienta me ayuda a obtener una salida mucho más agradable y legible del mismo. A mi particularme me resulta de gran utilidad.

## Otros recursos

Listados de otros recursos que nos pueden resultar utiles a la hora de desarrollar en esta plataforma:

### Libros

TO DO:

### Redes sociales

Listado de perfiles importantes en redes sociales como G+, o Twitter y listas de correo.

- [Desarrolladores Android](http://desarrolladores-android.com/) lista de correo de desarrolladores Android de habla hispana (desde la cual se impulso este proyecto)

### Sitios webs

- [Android Developers](http://developer.android.com) sitio oficial
- [Aprendiendo de Android y Mas](http://aprendiendodeandroidymas.com/) blog
- [Sgoliver](http://www.sgoliver.net/) sitio web con mucha información y curso sobre Android
