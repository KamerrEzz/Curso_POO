## Curso de Programación Orientada a Objetos

Apuntes y código del [Curso de Programación Orientada a Objetos de Platzi](https://platzi.com/clases/oop/)

## 📚 Módulo 1. Bienvenida e Introducción

- ### ¿Por qué aprender Programación Orientada a Objetos?

  - Porque permite programar más rápido, esto se debe a que se hace un análisis previo de lo que se esta realizando.
  - Al saber analizar problemas y entender la programación orientada a objetos se puede avanzar y dejar de ser un programador Junior. Esto se debe a que varias de las preguntas más frecuentes de los reclutadores son *¿Qué es encapsulamiento, abstracción, herencia, polimorfismo?*
  - Saber POO permite dejar ala mala práctica de copiar y pegar código y tomar el control del proyecto y el código.

  En el curso de abordan 3 aspectos fundamentales:

  - **Analizar:** 
    - Observación
    - Entendimiento
    - Lectura: "leer" muy bien la situación del problema
  - **Plasmar:**
    - Diagramas: plasmar el análisis de una forma gráfica
  - **Programar:**
    - Desarrollar lo que se acaba de diagramar usando algún lenguaje de programación.
  
- ### ¿Qué resuelve la Programación Orientada a Objetos?

  Permite resolver muchos de los "huecos" que tiene la programación estructurada. Entre los problemas que resuelve están: 

  - El código muy largo.
  - Evita que si algo falla todo se rompa.
  - Reduce la dificultad de mantener el código.
  - Evita el código espagueti (demasiadas sentencias de control anidadas).

- ### Paradigma Orientado a Objetos

  La filosofía de **Orientación a Objetos** surge a partir de la necesitad de los programadores de plasmar soluciones a problemas en el código. Se basa en un  análisis del problema que se quiere abordar para posteriormente empezar a programar basándose a las conclusiones llegadas en dicho análisis. Esto ahorra el problema de no saber por donde empezar a resolver un problema con software.

  En dicho análisis se observan los problemas en forma de objetos para después llevar todo a una solución en código.

  **Paradigma:** teoría que suministra la base y modelo para resolver problemas.

  El **Paradigma de Programación Orientada a Objetos** se compone de 4 elementos:

  - **Clases**
  - **Propiedades**
  - **Métodos**
  - **Objetos**

  Además de esos 4 elementos , la POO también tiene 4 "Pilares":
  
  - **Encapsulamiento**
  - **Abstracción**
  - **Herencia**
  - **Polimorfismo**
  
- ### Lenguajes Orientados a Objetos

  Algunos lenguajes orientados a objetos son:

  - **Java:** orientado a objetos naturalmente, de hecho POO es su paradigma principal. Se usa principalmente en desarrollo de Apps para Android y Backend en servidores, APIs, etc. Extensión de archivo →  *.java*
  - **PHP:** es un leguaje interpretado creado para programación Web. Extensión de archivo → *.php*
  - **Python:** esta diseñado para ser fácil de usar, tiene una sintaxis amigable e intuitiva. Se puede usar en diversos campos como Backend, Data Science e Inteligencia Artificial. Extensión de archivo → *.py*
  - **JavaScript:** es un lenguaje interpretado. Esta orientado a objetos pero basándose en *prototipos*. Es un leguaje pensado para Web y actualmente puede usarse tanto en el Frontend como en el Backend. Extensión de archivo → *.js*
  - C#
  - Ruby
  - Kotlin

- ### Diagramas de Modelado

  Los **diagramas de modelado** son una especie de gráficos que sirven de intermediarios entre el análisis que se hace del problema que se quiere solucionar y el código que se va a generar para solucionar dicho problema.

  Hay 2 opciones de diagramas de modelado disponibles:

  - **OMT:** *(Object Modeling Techniques)*. Creado en 1991. Es una metodología para el análisis orientado a objetos. Lo que propone es que una vez se hace el análisis y se tienen identificados los objetos, atributos, métodos, etc; se pasa a plasmar cada objeto en un recuadro, se ponen todos los atributos y métodos dentro de dicho recuadro y luego se usa una serie de conectores para establecer las relaciones entre los diferentes objetos.

    ![OMT](https://i.imgur.com/GRHnJgt.png)

    Actualmente esta en desuso y no se recomienda emplearlo en ningún proyecto.

    

  - **UML:** *(Unified Modeling Language - Lenguaje de modelado unificado)*. Creado en 1997. Se podría resumir como la versión moderna de OMT, pues unifica las bases y técnicas de este y las mejora. Es el método para crear diagramas de modelado que se usa en la actualidad. Tiene muchas más capacidades que OMT, entre las cuáles están:

    - Clases
    - Casos de uso
    - Objetos
    - Actividades
    - Iteración
    - Estados
    - Implementación
    - Etc

    [Aprender más de UML](https://es.slideshare.net/still01/aprendiendo-uml-en-24-horas-16815956)

    ![UML](https://i.imgur.com/5Dy46xi.png)

    Aprender UML es importante pues permite plasmar de forma gráfica lo que se va a implementar en el código y como esta construido el proyecto.

    Algunas herramientas para trabajar con UML:

    - [StarUML](http://staruml.io/download)
    - [ArgoUML](https://argouml.uptodown.com/windows)
    - [Lucidchart](https://www.lucidchart.com/)

  

## 📚 Módulo 2. Orientación a Objetos

- ### Objetos

  Cuando hay un problema que se quiere resolver con Software lo primero que hay que hacer es **identificar los Objetos**.

  - **¿Cómo identificar a los Objetos?** Los **objetos** son aquellos que tienen propiedades y comportamientos. Siempre son sustantivos. Pueden ser físicos (un Usuario por ejemplo) o conceptuales, es decir, que no existen físicamente, son simbologías de procesos que lleva a cabo el software que se esta construyendo (una de Sesión de Usuario por ejemplo).
  - **¿Qué son las Propiedades?** También llamadas **atributos**. Son características o propiedades que describen a un objeto (por ejemplo: nombre, tamaño, forma, estado). Los tributos también son sustantivos.
  - **¿Qué son los comportamientos?** También se les conoce como **métodos**. Son todas las operaciones/acciones del objeto (por ejemplo: login(), logout(), makeReport()). Suelen ser verbos o sustantivo y verbo.

- ### Abstracción y Clases

  Una **Clase** es el modelo sobre el cuál se construye un objeto. Para definirlo de una forma más sencilla de entender, se puede pensar en un una clase como un molde que se usa para crear objetos. 

  En este punto se analizan Objetos, se establecen todos sus atributos y métodos y  en base a eso se crean Clases. Este proceso de abstraer los datos de un objeto para generar una clase (molde) se le conoce como **Abstracción**. En resumidas cuentas, la abstracción es ese proceso de analizar los objetos para identificar sus atributos y métodos comunes para en base a eso crear un molde llamando Clase.

- ### Modularidad

  Consiste en dividir un sistema en partes más pequeñas, cada una de esas partes se llaman **módulos**. Cada uno de esos módulos funciona de manera independiente, pero juntos conforman el sistema completo.

  La modularidad permite hacer más fácil el mantenimiento y la escalabilidad de un proyecto, pues mientras en las programación estructurada se tiene un sólo archivo muy grande en el que esta toda la lógica del sistema y en el que un error puede detener la ejecución de todo el programa, en la programación orientada a objetos las diferentes funciones de un sistema se dividen en módulos independientes, por lo que a la hora de solucionar bugs sólo hay que ubicar el módulo que esta fallando y repararlo sin tener que afectar al resto del código; y si se quieren añadir más funcionalidades al proyecto solo hay que crear nuevos módulos e integrarlos dentro del sistema.

  **Ventajas de la modularidad:**

  - Reutilizar código.
  - Se evitan colapsos.
  - Código más mantenible.
  - Mejor legibilidad en el código
  - Rápida resolución de problemas

  Las clases son el elemento que permite la modularidad en la POO, pues permiten dividir el problema en distintas clases/módulos y a su vez separar dichas clases en diferentes archivos.
  
- ### Analizando Uber en Objetos

  - **Análisis del problema:**

    ![Análisis del funcionamiento de Uber](https://i.imgur.com/1VwEKHN.png)

    

  - **Análisis de los Objetos:**

    |   **User**    |
    | :-----------: |
    |   **Route**   |
    |  **Driver**   |
    |   **UberX**   |
    | **UberPool**  |
    | **UberBlack** |
    |  **UberVan**  |
    |   **Trip**    |
    |   **Cash**    |
    |   **Card**    |
    |  **Paypal**   |

  

- ### Clases en UML y su sintaxis en código

  Las clases en UML son representadas por un rectángulo. En la parte superior se pone el nombre de la clase (verde), después los atributos (morado) y por último los comportamientos/métodos (azul).

  ![Definir Clases enUML](https://i.imgur.com/Li7Ndkf.png)

  - **Definir Clases en Java:**

    ````java
    class Person {
        String name = ""; /* Atributo */
        void walk() {} /* Comportamiento / método */
    }
    ````

  - **Definir Clases en Python:**

    ````python
    class Person:
        name = ""; # Atributo
        def walk(): # Comportamiento / método
    ````

  - **Definir Clases en JavaScript:**

    ````javascript
    function Person() {} /* "Clase" */
    
    Person.prototype.walk = function() { 
         /* Comportamiento / método */
    }
    ````

  - **Definir Clases en PHP:**

    ````php
    class Person {
        $name = ""; # Atributo
        function walk() {} # Comportamiento / método
    }
    ````

    

  





