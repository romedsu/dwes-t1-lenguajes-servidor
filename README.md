# dwes-t1-lenguajes-servidor

### PHP -Omar,Pablo,Aitor-

### Descripcion: 
PHP, que se originó en 1994, fue creado por Rasmus Lerdorf como un conjunto de herramientas para gestionar su propia página web. Inicialmente llamado "Personal Home Page", permitía realizar tareas simples como rastrear visitas y gestionar formularios.
Con el tiempo, Lerdorf amplió el proyecto y lanzó PHP 3 en 1997, lo que marcó un hito importante en su desarrollo. Esta versión mejoró la funcionalidad del lenguaje y atrajo a una comunidad más amplia de desarrolladores.
Desde entonces, PHP ha evolucionado continuamente y se ha convertido en uno de los lenguajes más utilizados para el desarrollo web, gracias a su capacidad para crear contenido dinámico, interactuar con bases de datos y su facilidad de integración con diversas tecnologías. Su código abierto y el apoyo de una gran comunidad han contribuido a su popularidad duradera en la industria.
 

### Usos comunes:
 
Desarrollo web: Crear páginas dinámicas y aplicaciones web.
Gestión de bases de datos: Interactuar con bases de datos como MySQL.
Sistemas de gestión de contenido (CMS): Plataformas como WordPress y Joomla están construidas en PHP.
Generación de formularios: Manejar datos de formularios y validación.
APIs: Crear servicios web y APIs RESTful.
E-commerce: Desarrollar tiendas en línea y plataformas de comercio.
 
### Caracteristicas:
 
Sencillo de aprender: Tiene una sintaxis fácil, lo que lo hace accesible para principiantes.
Lenguaje del lado del servidor: Se ejecuta en el servidor y genera HTML que se envía al navegador.
Compatible con múltiples bases de datos: Soporta diversas bases de datos como MySQL, PostgreSQL, y SQLite.
Gran comunidad y soporte: Amplia documentación y una comunidad activa que proporciona recursos y librerías.
Interoperabilidad: Se puede integrar fácilmente con HTML, JavaScript y CSS.
Flexible y extensible: Permite la creación de extensiones y la integración con otros lenguajes.
Manejo de sesiones y cookies: Facilita la gestión de sesiones de usuario y almacenamiento de cookies.
Código abierto: Es gratuito y está disponible para su modificación y distribución.

### Ejemplos de uso
 
Sistemas de Gestión de Contenido (CMS): PHP se utiliza en plataformas como WordPress, Joomla y Drupal, permitiendo a los usuarios crear y gestionar sitios web sin necesidad de conocimientos técnicos profundos.
E-commerce: Muchas tiendas en línea, como Magento y WooCommerce, están construidas con PHP, facilitando la gestión de productos, pagos y pedidos.
Aplicaciones Web Dinámicas: PHP se usa para crear aplicaciones que requieren interacción del usuario, como foros, redes sociales y plataformas de colaboración.
Formularios de Contacto: PHP puede procesar datos de formularios, enviando correos electrónicos o guardando información en bases de datos.
Sistemas de Autenticación: Muchas aplicaciones web utilizan PHP para gestionar el registro, inicio de sesión y recuperación de contraseñas de usuarios.
Generación de Contenido Dinámico: PHP permite generar páginas web personalizadas en función de la información del usuario, como recomendaciones de productos basadas en el historial de navegación.
APIs RESTful: PHP se puede utilizar para crear APIs que permiten la comunicación entre diferentes aplicaciones, facilitando el intercambio de datos.
Manejo de Archivos: PHP permite la manipulación de archivos en el servidor, como subir, leer o escribir datos en archivos de texto.
Sistemas de Reservas: Muchas aplicaciones de reservas de hoteles y restaurantes utilizan PHP para gestionar la disponibilidad y las reservas de clientes.
Dashboards y Paneles de Control: PHP se utiliza para crear interfaces que muestran datos analíticos y estadísticas en tiempo real.

### Casos de Uso 
1. Meta Facebook
2. Wikipedia, the Free Encyclopedia
3. Etsy (*)


### Node.JS

## Autores
- Jorge Junquera Casarreal
- Samuel Moreira García

## Descripción 
Node.js es un **entorno de tiempo de ejecución de JavaScript multiplataforma y de código abierto** utilizado para la creación de sitios web dinámicos, creado por los mismo desarrolladores que JavaScript para llevarlo más allá que su utilización en el lado del cliente, permitiendo usarlo en el entorno del servidor. Este entorno permite escribir programas del lado del cliente y del servidor sin tener que aprender lenguajes diferentes.

## Usos comunes 
Node.js posee una gran cantidad de usos debido a su versatilidad ya que fue creado por los mismos desarrolladores de JavaScript para poder ejecutarlo fuera del entorno web mediante el motor V8 de Chrome por lo que, a parte de servir para crear servidores web, los agiliza y los capacita para trabajar con otros lenguajes de secuencia como es el caso de Python situando a Node.js como una excelente opción para grandes proyectos o que necesiten ser de gran rapidez.
Por otro lado, los principales usos comunes de este entorno son el **chat en tiempo real** ya que mediante su tecnología push sobre los sockets web permite una interacción entre los servidores y clientes, también el **streaming de datos** gracias a los módulos que tiene incorporados que permiten soportar el flujo de datos, también entre sus usos más comúnes cabe destacar, a parte de los que se han mencionado anteriormente:
- **Juegos real-time**
- **Aplicaciones de recolección de datos**
- **Aplicaciones de alto tráfico como es el caso de Twitter**

## Origen
Su origen se remonta al 29 de mayo del año 2009 cuando Ryan Dahl, su creador, lo presentó oficialmente definido como un entorno de tiempo de ejecución de JavaScript que se caracterizaba por ser de código abierto en el lado del servidor, en sus inicios funcionaba exclusivamente en Linux y Mac OS X.

## Nivel de adopción
Con el paso de los años, y cada vez más, Node.js está adquiriendo mucha popularidad ya que, hoy en día, el desarrollo web es muy popular y se utiliza en la mayoría de páginas web por no decir en todas, y su lenguaje principal es JavaScript dando gran importancia a Node.js que básicamente es su entorno principal, por lo que gracias a la llegada de Node.js permite usar Javascript también en el backend aparte del frontend, y facilitando mucho el desarrollo web ya que se puede realizar, actualmente, todo con Javascript.

## Características 
Las principales características por las que Node.js está siendo cada vez más popular con el paso de los años son: 
- Posee una **gran velocidad** gracias al motor de JavaScript V8 de Google Chrome.
- **Sin Búfer**, es decir, que todas las aplicaciones de Node.js nunca almacenan los datos en búfer, si no que los generan en chunks.
- **Asíncrono y controlado por eventos**, por lo que no se espera que una API devuelva los datos y también posee un mecanismo de notificación de eventos.
- Un **subproceso escalable** ya que Node.js usa un modelo de un solo subproceso con un bucle de eventos, por lo que, gracias a éste el servidor puede responder sin ningún tipo de bloqueo, de ahí a que sea asíncrono, convirtiendo a Node.js en un entorno mucho más escalable en comparación con los servidores tradicionales como HTTP de Apache.

## Ventajas e inconvenientes
Con respecto a las ventajas, como se comentó en el apartado de características se destacan principalmente:
- **Eficiencia y escalabilidad** permitiéndole manejar una alta concurrencia y un elevado numero de solicitudes a la vez de manera muy eficiente.
- **Unificación del lenguaje** ya que se puede utilizar Javascript tanto del lado del servidor (backend) como del lado del cliente (frontend) mejorando su productividad.
- **Amplio número de módulos** ya que Node.js cuenta con un elevado número de respositorios de paquetes y módulos facilitando la reutilización de código y, por ende, acelerando el desarrollo de las aplicaciones.
- **Comunidad activa** debido a la gran fama que ha adquirido este entorno, podemos encontrar en la web gran cantidad de recursos que nos pueden ayudar en caso de necesitar encontrar cualquier cosa o necesitar ayuda.

Por otro lado, no todo son cosas buenas, también posee algunos inconvenientes como es el caso de:
- **Uso intensivo de la CPU** ya que utiliza un solo hilo de ejecución por lo que puede perjudicar en el rendimiento de la aplicación en el caso de que ésta realice operaciones intensivas.
- **Madurez de algunas bibliotecas** ya que posee algunas que no son tan estables como el resto en comparación con otros frameworks más famosos por lo que debemos investigar realmente cada biblioteca antes de utilizarla en el desarrollo de nuestra aplicación.
- **Curva de aprendizaje** debido a que, si no estamos acostumbrados o no conocemos el lenguaje Javascript se nos complicará mucho el desarrollo de la aplicación y, tardaremos bastante tiempo en poder aprenderlo por lo que, al principio nos costará entender las funcionalidades y características de Node.js

## Ejemplos de uso 
Entre las empresas más notorias y conocidas que utilizan este entorno son:
- **Netflix**
- **Uber**
- **Walmart**
- **NASA**
- **PayPal o Ebay entre otras.**

## Bibliografía
- (https://nodejs.org/)
- (https://desarrolloweb.com/articulos/caracteristicas-nodejs.html)
- (https://ifgeekthen.nttdata.com/s/post/que-es-node-js-y-primeros-pasos-MCW4YDTW2NVVFJVPFT4EJSCSTE5Y?language=es)
- (https://blog.soyhenry.com/que-es-node-js-y-para-que-se-utiliza/)
- (https://www.itdo.com/blog/que-es-node-js-y-para-que-sirve/)
- (https://www.solbyte.com/blog/nodejs/)
- (https://www.luisllamas.es/historia-de-nodejs/#:~:text=El%2027%20de%20mayo%20de,Linux%20y%20Mac%20OS%20X.&text=Adem%C3%A1s%2C%20lo%20combinaba%20con%20un,E%2FS%20de%20bajo%20nivel.)

### Python

#### Autores
- José Manuel Morales Rivera
- Hugo González Reguero 
- Sergio Melendi García

#### Descripción
Python es un lenguaje de programación de alto nivel, interpretado y de propósito general, que se destaca por su legibilidad y simplicidad. Creado por Guido van Rossum y lanzado por primera vez en 1991, Python permite a los programadores expresar conceptos en menos líneas de código que muchos otros lenguajes, lo que facilita su aprendizaje y uso.

#### Autor
Guido van Rossum

#### Origen
El origen de Python, fue desarrollado inicialmente a fines de la década de 1980 y su primera versión fue lanzada en 1991 en Centrum Wiskunde & Informatica - CWI (Instituto Nacional de Investigación en Matemáticas y Ciencias de la Computación), en los Países Bajos

#### Usos Comunes
- Desarrollo Web: Usado en frameworks como Django y Flask para crear aplicaciones web.
- Ciencia de Datos: Herramientas como Pandas, NumPy y Matplotlib permiten analizar y visualizar datos.
- Inteligencia Artificial y Aprendizaje Automático: Bibliotecas como TensorFlow y scikit-learn son populares en este campo.
- Automatización de Tareas: Ideal para scripts que automatizan procesos repetitivos.
- Desarrollo de Juegos: Usado con bibliotecas como Pygame para crear videojuegos.
- Desarrollo de Aplicaciones de Escritorio: Con herramientas como Tkinter o PyQt.

#### Características
- Sintaxis Simple: Su diseño se centra en la legibilidad y la simplicidad, lo que facilita el aprendizaje.
- Tipado Dinámico: No es necesario declarar el tipo de variable, lo que permite mayor flexibilidad.
- Interpretado: No requiere un proceso de compilación, lo que agiliza la prueba y el desarrollo.
- Extensa Biblioteca Estándar: Incluye una amplia variedad de módulos y funciones predefinidas.
- Comunidad Activa: Gran cantidad de recursos, documentación y soporte comunitario.

#### Ventajas e inconvenientes
- Ventajas:
1. Fácil de aprender y usar: Su sintaxis clara y legible facilita el aprendizaje, especialmente para principiantes.
2. Versatilidad: Se puede usar en una amplia gama de aplicaciones, desde desarrollo web hasta análisis de datos y aprendizaje automático.
3. Amplia biblioteca estándar: Python cuenta con una extensa colección de bibliotecas que cubren muchas necesidades, lo que ahorra tiempo y esfuerzo.
4. Comunidad activa: Una gran comunidad de desarrolladores proporciona soporte, recursos y contribuciones constantes.
5. Desarrollo rápido de prototipos: La sintaxis concisa y la tipificación dinámica permiten crear prototipos rápidamente.
6. Portabilidad: El código Python puede ejecutarse en diferentes sistemas operativos sin modificaciones significativas.

- Inconvenientes:
1. Velocidad de ejecución: Al ser un lenguaje interpretado, Python puede ser más lento en comparación con lenguajes compilados como C++ o Java.
2. Gestión de memoria: La gestión automática de memoria puede ser una limitación en aplicaciones que requieren un control preciso de los recursos.
3. Desarrollo móvil y de juegos: No es tan comúnmente utilizado para el desarrollo de aplicaciones móviles o juegos de alto rendimiento.
4. Bloqueo global del intérprete (GIL): Puede limitar la capacidad de utilizar eficazmente varios núcleos de procesador en aplicaciones multihilo.

#### Ejemplos de uso
1. Hola Mundo: print("Hola, Mundo!")
2. Ciencia de datos: import pandas as pd

df = pd.read_csv('datos.csv') <- cargaría datos desde un csv

print(df.describe())

3. Juego con Pygame: import pygame

pygame.init()

A partir, de aquí se podrían usar diversos métodos de la librería de pygame que nos ayudarían a el desarrollo del código del juego.

#### Casos de uso reales observados
1. [Google](https://www.google.com/)
2. [Facebook](https://www.facebook.com/)
3. [Instagram](https://www.instagram.com/)
   
### Ruby

# participantes:
- Alejandro ruisanchez
- Alexis gonzalez
- Bruno perez

DESCRIPCION
Ruby fue creado por el programador japonés Yukihiro «Matz» Matsumoto, quien comenzó a trabajar en Ruby en 1993, y lo presentó públicamente en 1995. Combina una sintaxis inspirada en Python y Perl con características a Smalltalk. El lenguaje Ruby se utiliza principalmente en el desarrollo de aplicaciones web, pero también se puede utilizar para desarrollar otro tipo de aplicaciones de software, como veremos más adelante. Este lenguaje está disponible en plataformas como Windows, Linux y muchas otras, considerándose multiplataforma. Estar orientado a objetivos significa unciona con datos que el usuario creará en función de sus propias necesidades La simplicidad y la productividad son el foco de este lenguaje, por lo que aprender a programar en Ruby puede ser una gran opción para aquellos que buscan programar fácilmente

USOS COMUNES
Permite desarrollar distintos tipos de aplicaciones, a saber: aplicaciones de servicio web, clientes de correo electrónico, procesamiento de datos y aplicaciones de red. El lenguaje Ruby puede ser muy útil, ya que este lenguaje se puede utilizar para crear varios programas para desktop. Cuenta con dos frameworks:

Ruby on Rails muy popular que sirve para desarrollar aplicaciones web.
RubyGems es el sistema de empaquetado de Ruby. Facilita la distribución, instalación y actualización de aplicaciones. Se compone de fragmentos de códigos, que forman bibliotecas.
CARACTERISTICAS
Es un lenguaje de propósito general, es decir, con Ruby se pueden desarrollar todo tipo de aplicaciones diferentes: aplicaciones de servicio web, clientes de correo electrónico, procesamiento de datos en Backend, aplicaciones de red, etc.
Es un lenguaje interpretado, es decir, no es compilado, se necesita que el intérprete,evalué el código y lo traduzca en lenguaje de máquina entendible por un ordenador.
Es dinámico y flexible
Es de software libre (Open Source) y multiplataforma, se puede descargar totalmente gratis de la página oficial y ejecutarlo en diferentes sistemas operativos.
100% Orientado a Objetos
DESVENTAJAS
Rendimiento: Ruby es más lento que muchos otros lenguajes de programación. Su naturaleza interpretada y la flexibilidad que ofrece a menudo resultan en una ejecución más lenta en comparación con lenguajes compilados. – Escalabilidad: Las aplicaciones grandes pueden volverse difíciles de mantener. A medida que el tamaño y la complejidad de la aplicación crecen, puede ser un desafío mantener un código limpio y eficiente. – Menor uso en empresas: Menos demanda en comparación con lenguajes como Java o Python en entornos empresariales. Aunque Ruby es popular en startups y pequeñas empresas, no es tan ampliamente adoptado en grandes corporaciones.
VENTAJAS
Sintaxis sencilla: Ruby tiene una sintaxis natural y fácil de leer. Está diseñado para ser intuitivo, lo que reduce la cantidad de código necesario para realizar tareas y hace que el desarrollo sea más eficiente. – Productividad: Permite un desarrollo rápido de aplicaciones web, lo que acelera el proceso de desarrollo y reduce la cantidad de código duplicado. – Comunidad: Una comunidad activa que contribuye con bibliotecas y recursos. La comunidad de Ruby es conocida por ser amigable y colaborativa, proporcionando numerosos recursos de aprendizaje y soporte. – Flexibilidad: Es muy flexible y permite a los desarrolladores modificar partes del lenguaje según sus necesidades. Ruby permite una programación avanzada, lo que facilita la creación de código dinámico y reutilizable.
EJEMPLOS DE USO
twitter
airbnb
hulu
grupon
soundcloud
github
### Java

### C#
1. Descripción
C# es un lenguaje de programación orientado a objetos creado por Microsoft para la plataforma .NET. Combina la simplicidad de lenguajes como Java con la potencia de C++, y es ampliamente utilizado para desarrollar aplicaciones de escritorio, web, móviles y videojuegos.

2. Usos Comunes
Aplicaciones de escritorio (Windows Forms, WPF).
Aplicaciones web (ASP.NET).
Aplicaciones móviles (Xamarin).
Videojuegos (Unity).
Servicios en la nube (Azure).
3. Características
Orientado a objetos: Soporta herencia, encapsulación y polimorfismo.
Recolección de basura: Gestión automática de memoria.
Multiplataforma: Compatible con Windows, Linux y macOS mediante .NET Core.
Asincronía: Uso de async y await para programación asíncrona.
LINQ: Para consultas y manipulación de datos integradas en el lenguaje.
4. Ejemplo de Código
csharp
Copiar código
```c#
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Hola, Mundo!");

        Persona persona = new Persona("Juan", 30);
        persona.Saludar();
    }
}

class Persona
{
    private string nombre;
    private int edad;

    public Persona(string nombre, int edad)
    {
        this.nombre = nombre;
        this.edad = edad;
    }

    public void Saludar()
    {
        Console.WriteLine($"Hola, me llamo {nombre} y tengo {edad} años.");
    }
}
```
Este código muestra cómo crear una clase Persona y cómo invocar un método para imprimir un saludo en la consola.

---

### GO  *(Lenguaje de programación)*

![logo lenguaje de programación GO](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Go_Logo_Blue.svg/140px-Go_Logo_Blue.svg.png)

[Sitio web oificial](https://go.dev/)
#### Autores: *David Fraga, Guillermo Méndez-Trelles y Rodrigo Medina*

***

### ORIGEN
**GO** es un lenguaje de programación creado por *Google* en 2009 por los ingenieros *Robert Griesemer, Rob Pike y Ken Thompson*. Su principal objetivo era solucionar problemas de complejidad, lentitud en la compilación, dificultad en la concurrencia simultánea y en el desarrollo de software a gran escala, al igual que ocurría con otros lenguajes de programación, como *C++* y *Java*.

Su sintaxis se basa en diversos lenguajes existentes, combinando elementos de ***C, Pascal y Java***. 
Una de las principales causas de su éxito es su curva de aprendizaje fácil y escalable.

Se considera un lenguaje versátil y muy útil para desarrollar, desde aplicaciones web/móvil, sistemas operativos o servidores web.
Se trata de un lenguaje compilado y tipado, pero no dispone de herencia, palabras claves, ni clases (En su lugar utiliza estructuras).

Del mismo modo, se define como un lenguaje de **código abierto** y se caracteriza por su ligereza, simplicidad y rapidez,en contraste con otros lenguajes más pesados como *Java* o *C*.

Actualmente, se considera unos de los lenguajes más en alza con una gran popularidad en el desarrollo web, gracias a su modernidad, eficiencia y sencillez.

---

### NIVEL DE ADOPCIÓN
Go es un lenguaje de programación que cada vez tiene mayor nivel de adopcion. Aproximadamente **1,1 millones** de desarrolladores profesionales como lenguaje principal y alrededor de 2,7 millones como lenguaje secundario .

Es más utilizado en **China, Rusia y Estados Unidos**, y está entre los 10 lenguajes principales de los desarrolladores profesionales con una **participación del 7%**.

---

### USOS COMUNES
El lenguaje de programación de GO posee muchas finalidades, entre las que destacan:

* Aplicaciones web/móvil

* Compilación de plataforma cruzada

* Arquitectura tecnología de la información (IT)

* Bases de datos

* Inteligencia artificial

* Páginas web

* Debugs

* Configuración de servidores

* Sistemas operativos

* Soluciones en la nube 

---

### CARACTERÍSTICAS
* **Simplicidad**: Sintaxis clara, limpia y organizada.

* **Funcionalidades**: Cuenta con funcionalidades como la declaracion explicita de variables y el recolector de basura, orientado a la reduccion de latencia.

* **Facilidad de uso**: Esta estructurado para facilitar el trabajo lo maximo posible.
Por ejemplo, permite detectar errores en la sintaxis mientras compilamos el codigo y no cuando lo ejecutamos.

* **Compatibiidad**: Compatible con *Windows*, *Mac OS X*, *Linux* y *freeBDS*.

* Se trata de un proyecto de **codigo abierto** .

* Soporte miles de conexiones en el mismo programa. Pensado para usarse en el internet actual, dónde puedes tener un servidor que consuma menos recursos.

* **Lenguaje compilado**: No es interpretado como *JavaScript* , sino que el código fuente se tiene que compilar y generar código máquina, por lo que es más rápido a la hora de ejecutar .

* **Orientado a objetos**: No es un lenguaje orientado a objetos en el sentido clásico pero permite algunos principios de la POO, a través de su sistema de estructuras, tipos y métodos. Del mismo modo,  GO no permite herencia, ni clases.

---

### VENTAJAS E INCONVENIENTES
#### **Ventajas**: 
* **Simplicidad**

* **Facilidad de uso**

* **Curva de aprendizaje escalable**

* **Portabilidad**

* **Eficiencia**

* **Rendimiento**

#### **Desventajas**: 
* **Limitación de memoria**: Go no permite el control manual de la gestión de memoria .

* **Compilación y binarios grandes** : Las aplicaciones Go suelen generar binarios bastante grandes debido a que el compilador incluye todas las dependencias en el binario final .

* **Poca flexibilidad en la sintaxis**: Algunos desarrolladores encuentran que la sintaxis de Go es demasiado estricta o rígida .

* **No dispone de herencia, ni palabras claves**

---

### EJEMPLOS DE USO
* **Google**: Como el creador de GO, Google utiliza este lenguaje en varios de sus servicios y herramientas internas .

* **YouTube**: La plataforma de videos utiliza GO para manejar ciertas partes de su infraestructura, especialmente en el backend .

* **Docker**: La popular plataforma de contenedores está escrita en GO, lo que le permite ser eficiente y fácil de usar .

* **Twitch**: En varios componentes de su infraestructura debido a las ventajas que ofrece en términos de rendimiento, concurrencia y escalabilidad .

* **Trello**: La herramienta de gestión de proyectos utiliza GO en su backend para manejar la concurrencia y el rendimiento .

* **Dropbox**: Utiliza GO para algunos de sus servicios backend, aprovechando su eficiencia y capacidad de manejo de concurrencia .

* **SoundCloud**: La plataforma de música en streaming utiliza GO para algunos de sus servicios, beneficiándose de su rendimiento y escalabilidad .

* **Paypal**: Utiliza GO para varios propósitos en su infraestructura y desarrollo de software .

* **GitHub**: Algunas partes de la infraestructura de *GitHub* están escritas en GO, aprovechando su eficiencia para manejar grandes volúmenes de datos .

* **Netflix**: Utiliza Go para algunos de sus servicios backend, especialmente aquellos que requieren alta disponibilidad y rendimiento .

* **American express**: Utiliza el lenguaje de programación Go por varias razones que se alinean con sus necesidades tecnológicas y operativas .

* **Uber**: Utiliza el lenguaje de programación GO por varias razones que se alinean con sus necesidades de desarrollo y operación .




---

### Perl
- Autores
  - Sergio Rodriguez Cadavieco
  - Daniel Couce Garcia
  - Daniel Santamarta Reguera
- Origen
  - Surgio en 1987 a manos de Larry Wall con la idea de simplificar y automatizar tareas repetitivas en la administracion de servidores.
  - Se empezo a popularizar en la progamacion web con la version 4 entre 1991 y 1993, 1 año despues se desplegaria su 5º version siendo la mas utilizada hasta dia      de hoy.
  - Es un idioma basado en C, pero tambien esta inspirado en otros lenguajes como C++, Pascal o UnixShell entre otros.
    
- Usos Comunes
  - Administracion de sistemas operativos, gracias a que es mu potente en la creacion de pequeños programas.
  - Creacion de formularios web, se utiliza tambien para la creación de scripts CGI (Common Gateway Interface). Estos scripts realizan el intercambio de
     información entre aplicaciones externas y servicios de información.
    
- Ventajas
  - Es multiplataforma lo que nos permite trabajar en Unix, Windows o Mac OS y por tanto ejecutar el mismo codigo en cualquier sistema.
  - Nos permite manejar una enorme cantidad de datos.
  - Tiene una sintaxis concisa lo que ayuda a escribir programas complejos en pocas lineas de codigo.

- Desventajas
  - Al presentar una sintaxis compleja, puede ser dificil de aprender inicialmente.
  - Si el proyecto es muy grande puede volerse muy complicado de leer y entender.
  - Su flexibilidad es un arma de doble filo, al poder escribir codigo en diferentes estilos puede dificultar el trabajo en equipo
     
- Caracteristicas
  - Una de sus principales caracteristicas es su facilidad de uso ya que esta diseñado para realizar tareas repetitivas.
  - Es multiplataforma lo cual nos permite operar en multitud de sistemas operativos.
  - Es un lenguaje de alto nivel, diseñado originalmente para tareas de extracción y generación de informes.
  - Permite la programacion orientada a objetos, la procedimental y la funcional.
    
- Ejemplos de uso
  - [BugZilla](https://www.bugzilla.org/)
  - [Fronzen Bubble](https://play.google.com/store/apps/details?id=org.jfedor.frozenbubble&hl=es)
  - [DuckDuckGo](https://duckduckgo.com/)











### Rust

