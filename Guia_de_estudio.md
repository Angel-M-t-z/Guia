
![Alt](https://d1yjjnpx0p53s8.cloudfront.net/styles/logo-thumbnail/s3/072016/untitled-1_237.png?itok=LaVxt7WP "UMB")
![Alt](https://www.conalepmex.edu.mx/images/2018/01/11/sitio-interes4-edomexgob.png "Gobierno del Estado de México")

### <p align = center> UNIVERSIDAD MEXIQUENSE DEL BICENTENARIO 
### <p align = center> UNIDAD DE ESTUDIOS SUPERIORES SAN JOSÉ DEL RINCON  
#
### <p align = center> Asignatura: 
## <p align = center> FUNDAMENTOS DE PROGRAMACIÓN
#
### <p align = center> Proyecto:
# <p align = center> Fundamentos de programación: Guía de lenguajes
#
### <p align = center> Carrera: Ingeniería en Sistemas Computacionales
#
### <p align = center> Nombre del alumno: Miguel Ángel Pascual Martínez
#
### <p align = center> Nombre del Docente: Eduardo Becerril Romero
#
### <p align = center> Grupo: 13SC111
#
### <p align = right> Fecha: 17 de enero de 2023

#
#
#
#


# <p align = center> INTRODUCCIÓN

<!--- <p align = justify> si agrego esta linea el programa no me lee las negritas que quiero especificar --->

El presente proyecto es realizado en el primer semestre universitario de la carrera Ingeniería en Sistemas Computacionales, elaborado en la ultima evaluación parcial de la asignatura **Fundamentos de Programación**. Este proyecto tiene como motivo transmitir conocimientos basicos de la programación a aquellos que van entrando en este mundo, el proyecto contiene conceptos basicos, así como herramientas utilizadas para la programación (herramientas como editores de texto), además de que informa sobre algunos lenguajes de programación, su historia, sus usos, su aplicabilidad, ventajas y desventajas, con el objetivo de que el lector interesado en el mundo de la programación pueda resolver algunas de sus dudas y que pueda elegir cual lenguanje de programación le llama más la atención para iniciar con el desarrollo de software.

# <p align = center> OBJETIVOS

1. Brindar al lector información escencial que le aporte conocimientos básicos pero escenciales si desea integrarse al desarrollo de software.
2. Informar sobre algunos de los paradigmas de programación que existen.
3. Brindar información importante de lenguajes de programación que estan teniendo más impacto en el mundo de la programación.
4. Dar a conocer algunos ejemplos de algoritmos desarrollados en diferentes lenguajes de programación.

# <p align = center> ÍNDICE

1. Introducción
2. Objetivos
3. Índice
4. Conceptos básicos
    * Programación
        - ¿Qué es?
        - ¿Para qué sirve?
        - Historia
    - Algoritmos
    - Diagramas de flujo
    - Lenguaje de programación
    - Paradigmas de programación
        - Programación Orientada a Objetos
        - Programación Orientada a Eventos
        - Programación Reactiva
    - Lenguajes compilados
    - Lenguajes interpretados
5. Editores de texto
    - Visual Studio Code
    - Atom
    - Sublime Text
6. Guía de lenguajes
7. Python
    - ¿Qué es python?
    - Paradigmas que se pueden implementar
    - Aplicaciones comunes del lenguaje
    - Pros y contras vs otros lenguajes
    - Instalación
    - Configuración
        - Entorno (Sistema operativo)
        - Entorno (Editor de texto)
    - Hola mundo
    - Comandos de ejecución de un programa
    - 10 Algoritmos de ejemplo
8. C++
    - ¿Qué es c++?
    - Paradigmas que se pueden implementar
    - Aplicaciones comunes del lenguaje
    - Pros y contras vs otros lenguajes
    - Instalación
    - Configuración
        - Entorno (Sistema operativo)
        - Entorno (Editor de texto)
    - Hola mundo
    - Comandos de compilación y ejecución de un programa
    - 10 Algoritmos de ejemplo
9. Javascript
    - ¿Qué es javascript?
    - Paradigmas que se pueden implementar
    - Aplicaciones comunes del lenguaje
    - Pros y contras vs otros lenguajes
    - Instalación
    - Configuración
        - Entorno (Sistema operativo)
        - Entorno (Editor de texto)
    - Hola mundo
    - Proceso de ejecución de un programa
    - 10 Algoritmos de ejemplo
10. PHP
    - ¿Qué es PHP?
    - Paradigmas que se pueden implementar
    - Aplicaciones comunes del lenguaje
    - Pros y contras vs otros lenguajes
    - Instalación
    - Configuración
        - Entorno (Sistema operativo)
        - Entorno (Editor de texto)
    - Hola mundo
    - Proceso de ejecución de un programa
    - 10 Algoritmos de ejemplo
11. Ensamblador
    - ¿Qué es ensamblador?
    - Paradigmas que se pueden implementar
    - Aplicaciones comunes del lenguaje
    - Pros y contras vs otros lenguajes
    - Instalación
    - Configuración
        - Entorno (Sistema operativo)
        - Entorno (Emulador emu8086)
    - Hola mundo
    - Proceso de ejecución de un programa con emu8086
    - 5 Algoritmos de ejemplo
12. Conclusiones
13. Bibliografía

# <p align = center> CONCEPTOS BÁSICOS
## <p align = center> PROGRAMACIÓN
### ¿QUÉ ES?
La programación es el proceso de darle instrucciones a un computador para que éste realice una tarea en especifico, las instrucciones son dadas a través de software de desarrollo conocido mejor como lenguaje de programación.

### ¿PARA QUÉ SIRVE?
La programación sirve para crear soluciones a problematicas haciendo uso de la tecnologia. Se requiere de un algoritmo (que serian los pasos a seguir para resolver el problema) y de un lenguaje de programación para indicarle a un computador las instrucciones a seguir en base al algoritmo para resolver la problematica.

### HISTORIA
El primer hallazgo de algo relacionado con la programación lo encontramos en 1801 de la mano de Joseph Marie Jacquard y su telar programable. Con el se da a luz al primer sistema de programación, integrado en un telar que leía el código introducido y automatizaba los procesos.

Sin embargo, la programación tal y como la conocemos nace en 1957 con el conocido científico John W. Backus, cuando creó el primer lenguaje de programación de alto nivel, Fortran. Su finalidad era clarificar y facilitar la comprensión (ante los lenguajes erráticos e indescifrables que había en la época), acercándolo a una notación matemática normal.

Más tarde, en 1964 nació BASIC, familia de lenguajes de programación que surgió como una herramienta de apoyo enfocada a la enseñanza pero que acabo adquiriendo una relevancia sorprendente, hasta el punto de que, a día de hoy, sigue siendo utilizado en programas como “Gambas” o “Visual Basic”.

La década de los 70 fue realmente importante en términos de programación:

En 1970 tuvo lugar la creación de Pascal, que al igual que BASIC, nació como una herramienta de enseñanza que pronto pasó a utilizarse para el desarrollo de aplicaciones. A pesar de que su influencia se ha visto reducida con el paso del tiempo, se sigue utilizando sobre todo en escuelas de programación.
En 1972 llegó el lenguaje C, y el resto es historia. C fue creado por Dennis Ritchie como un lenguaje básico de programación, de un nivel no muy complejo, que pronto adquiriría una relevancia vital, hasta acabar convirtiéndose en uno de los lenguajes más utilizados en la actualidad.
Finalmente en 1979 tiene lugar otro hito histórico para la programación: se crea el lenguaje C++ con la idea de añadir al lenguaje C mecanismos para manipular objetos.
Con la llegada de 1990 y la década de internet, fueron numerosos los nuevos lenguajes de programación que surgieron. Muchos de ellos alcanzaron una gran popularidad y siguen siendo masivamente utilizados actualmente. Entre ellos destacamos algunos como HTML, Python, Visual Basic, Java, JavaScript o PHP que están presentes en casi la totalidad de páginas web y aplicaciones en la actualidad.


Finalmente, desde la entrada en el siglo XXI, la creación de lenguajes de programación se ha visto mermada como consecuencia de la gran completitud de los lenguajes ya diseñados. Hechos relevantes fueron los siguientes:

Creación de C# en 2001.
Scratch, lenguaje de programación creado en 2006 con una complejidad más reducida para facilitar un aprendizaje más visual para niños, adolescentes y adultos.
Go de Google en 2009
Kotlin en 2012, hoy bautizado como uno de los mejores lenguajes para programar en Android.
Swift en 2013, creado por Apple para programar en iOS.
Actualmente, son muchos los lenguajes de programación utilizados, cada uno especializado en una función diferente. 

## <p align = center> ALGORITMOS
Un algoritmo son los pasos a seguir para dar solución a un determinado problema, es preciso, claro y finito, es decir tiene un inicio y un final.

## <p align = center> DIAGRAMAS DE FLUJO
Un diagrama de flujo es la representación gráfica de un algoritmo, un diagrama de flujo esta constituido por diferentes figuras, cada una simbolizando algo en espeficico, por ejemplo los ovalos representan el inicio y final del diagrama, un rectángulo representa un proceso, un romboide representa una entrada o salida de datos, un rombo simboliza una decisión y las flechas son usadas para dar a conocer el sentido del flujo del diagrama.

## <p align = center> LENGUAJE DE PROGRAMACIÓN
El lenguaje de programación es un software de desarrollo, el cual es utilizado para poder darle instrucciones a un computador para que realice tareas indicadas por un programador. Existen distintos lenguajes de programación, cada uno con un cierto proposito y con una forma diferente o similar de especificar las instrucciones, esto se le conoce como sintaxis, y por lo general es parecido al lenguaje humano, sin embargo algunos lenguajes de programación tienen su sintaxis más parecida al lenguaje máquina, con esto se puede diferenciar al lenguaje de programación entre un lenguaje de alto nivel (más parecido al lenguaje humano y es fácil de comprender) y lenguaje de bajo nivel (más parecido al lenguaje máquina y es un poco complejo de entender). Otra manera en que se clasifican los lenguajes de programación es en base a su forma de ejecución, se dividen en lenguajes de programación compilados e interpretados.

## <p align = center> PARADIGMAS DE PROGRAMACIÓN
Un paradigma de programación es tan solo la manera o estilo en que se programa, puede ser usando objetos, eventos, procedimientos, funciones, entre otras cosas, pero algunas de las más conocidas son las siguientes:

### PROGRAMACIÓN ORIENTADA A OBJETOS
La programación orientada o objetos o POO consiste en la implementación de objetos para dar solución a la problematica que se quiere resolver. Un objeto es la abstracción de un elemento de la vida real, éste tiene un identificador, atributos y comportamientos. La POO posee cuatro pilares, los cuales son la encapsulación, la abstracción, el polimorfismo y la herencia.

### PROGRAMACIÓN ORIENTADA A EVENTOS
En la programación orientada a eventos se encuentran tres elementos importantes, los eventos, los componentes y los metodos. Es un paradigma el cual se enfoca en funcionar dependiendo de los sucesos o acciones que ocurren en el programa y que son causados por los usuarios o por el programa. Los eventos son las acciones que ocurren, como dar clic sobre algo, introducir texto, etc, y cada acción es hecha por el usuario o el mismo programa, los componentes son los elementos con los cuales se puede interactuar y causar un tipo de evento en cada uno, y por ultimo los metodos son las funciones que cada elemento posee, por ejemplo un cuadro de texto, al ingresar un texto, éste puede tener un metodo que lo almacene, otro que lo borre, otro que lo evalue, etc.

### PROGRAMACIÓN REACTIVA
La programación reactiva es un paradigma enfocado en el trabajo con flujos de datos finitos o infinitos de manera asíncrona. Algunos de los elementos escenciales que los programas reactivos deben tener es que deben ser:
**Responsivos:** deben de asegurar la calidad del servicio cumpliendo unos tiempos de respuesta establecidos.
**Resilientes:** mantenerse responsivos incluso cuando se enfrentan a situaciones de error.
**Elásticos:** mantenerse responsivos incluso ante aumentos en la carga de trabajo.
**Orientados a mensajes:** minimizan el acoplamiento entre componentes al establecer interacciones basadas en el intercambio de mensajes de manera asíncrona.
La motivación detrás de este nuevo paradigma procede de la necesidad de responder a las limitaciones de escalado presentes en los modelos de desarrollo actuales, que se caracterizan por su desaprovechamiento del uso de la CPU.

## <p align = center> LENGUAJES COMPILADOS
Los lenguajes de programación compilados son aquellos que deben pasar a través de un copilador que convierte los codigos dados por el programador a un lenguaje que el ordenador pueda comprender, de esta manera la ejecución de los programas suele ser mas rápida en comparación de los lenguajes interpretados.

## <p align = center> LENGUAJES INTERPRETADOS
Los lenguajes de programación interpretados son aquellos que no necesitan pasar a través de un compilador, por lo que al ejecutarse, un interprete va interpretando el código línea por línea del programa en el momento de la ejecución, esto hace que su ejecución sea más lenta que la de los lenguajes compilados, pero con el paso del tiempo se ha ido haciendo cada vez más rapida en su ejecución.

# <p align = center> EDITORES DE TEXTO

## <p align = center> VISUAL STUDIO CODE

## <p align = center> ATOM

## <p align = center> SUBLIME TEXT

# <p align = center> GUÍA DE LENGUAJES

## <p align = center> Python
### ¿QUÉ ES PYTHON?
Python es un lenguaje de programación de alto nivel, esta clasificado entre los lenguajes interpretados, pero también puede ser compilado para ejecutarse, soporta paradigmas como la POO, su sintaxis es muy parecida al lenguaje natural, por ello se considera como lenguaje de alto nivel, además con Python se pueden programar diversidad de programas, tales como páginas web, aplicaciones, e incluso inteligencia artificial. 

### PARADIGMAS QUE SE PUEDEN IMPLEMENTAR
Python es un lenguaje de programación multiparadigma, es decir que soporta varios paradigmas de programación (programación orientada a objetos, programación orientada a procedimientos y programación funcional).

### APLICACIONES COMUNES DEL LENGUAJE
Python es utilizado por empresas de todo el mundo para construir aplicaciones web, analizar datos, automatizar operaciones y crear aplicaciones empresariales fiables y escalables, además de que también suele ser muy usado para crear AI.

### PROS Y CONTRAS VS OTROS LENGUAJES
**Ventajas:**
* Lenguaje de alto nivel
* Multiparadigma
* Posee diversas bibliotecas y frameworks
* Portablilidad
* Gratis y de código abierto
* Baja curva de aprendizaje
* Comunidad fuerte
**Desvnetajas:**
* Lentitud
* Consumo de memoria
* Desarrollo móvil

### INSTALACIÓN
Para poder hacer la instalación correcta de python, unicamente se debe hacer lo siguiente:

### CONFIGURACIÓN
#### ENTORNO (SISTEMA OPERATIVO)
Al momento de instalar Python, en el sistema se agregan variables de entorno, esto para que el sistema pueda buscar con esa variable lo que queremos hacer cuando vamos a ejecutar un programa escrito en Python, si no se agrega cuando hacemos la instalación, se debe hacer manualmente copiando la ruta de la carpeta de Python, yendo a la configuración avanzada del sistema en en caso de windows, en el apartado de variables de entorno, en Path se da clic en editar, posteriormente en nueva y se coloca la ruta de la carpeta de Python, por último se guarda y el sistema podra verificar en ella cuando se ejecute un programa escrito en Python.

#### ENTORNO (EDITOR DE TEXTO)

### HOLA MUNDO
Para imprimir un "Hola mundo" en Python, se escribe la siguiente línea de código:
```python
print("Hola mundo")
```
Ahora para poder ejecutar el comando, se va a la terminal de Windows, se navega entre los directorios hasta llegar en aquella carpeta que contenga el archivo .py
Al encontrar el archivo, se escribe lo siguiente:
```
> python _Nombre_del_archivo.py
```
Al darle enter, el programa sera interpretado por el interprete de Python y hará lo que le hemos especificado con el código.
![Imprimir Hola Mundo](https://drive.google.com/file/d/1MbxisEDWfTk8GM1lIZuLlCsDqXvg6iGm/view?usp=share_link "Hola mundo")

## <p align = center> C++

## <p align = center> JavaScript

## <p align = center> PHP

## <p align = center> Ensamblador

# <p align = center> CONCLUSIONES
Este proyecto contiene temas escenciales sobre la programación, como el concepto de qué es, sus aplicaciones, historia, como esta relacionada con los algoritmos y diagramas de flujo. Para la programación se hacen uso de lenguajes de programación, tambien se especifica en este proyecto que es un lenguaje de programación, como se clasifican, como es el comportamiento de cada uno, los diversos paradigmas de programación que podemos utilizar, algunas de las herramientas que un desarrollador puede usar para construir sus propios programas, y sobre todo, se muestran ejemplos claros para poder usar los lenguajes de programación. En otras palabras, este proyecto es una guía completa para que una persona que apenas esta comenzado en el mundo de la programación pueda tomar como base para entender un poco de cómo funciona el desarrollo de software. 

# <p align = center> BIBLIOGRAFÍA
Syltec. (2023). ENGINEERING SYLTEC MAKING FUTURE. Obtenido de [https://syltec.es/blog/2021/10/05/programacion-un-poco-de-historia-y-conceptos-clave/#:~:text=Historia%20de%20la%20programaci%C3%B3n,introducido%20y%20automatizaba%20los%20procesos.](https://syltec.es/blog/2021/10/05/programacion-un-poco-de-historia-y-conceptos-clave/#:~:text=Historia%20de%20la%20programaci%C3%B3n,introducido%20y%20automatizaba%20los%20procesos. "Programación, un poco de historia y conceptos clave")

Andres. (2023). Curriculos Exploratorios en Tic. Obtenido de [http://contenidos.sucerman.com/nivel3/dispositivos/unidad1/leccion2.html](http://contenidos.sucerman.com/nivel3/dispositivos/unidad1/leccion2.html "¿Qué es la programación orientada a eventos?")

Iñiga J. (2023). Profile. Obtenido de [https://profile.es/blog/que-es-la-programacion-reactiva-una-introduccion/](https://profile.es/blog/que-es-la-programacion-reactiva-una-introduccion/ "¿Qué es la programación reactiva? Una introducción")

### PYTHON
Greyrat R. (2023). Barcelona Geeks. Obtenido de [https://barcelonageeks.com/paradigmas-de-programacion-en-python/](https://barcelonageeks.com/paradigmas-de-programacion-en-python/ "Paradigmas de programación en Pyhton")

Visus A. (2023). Esic. Obtenido de [https://www.esic.edu/rethink/tecnologia/para-que-sirve-python#:~:text=El%20lenguaje%20de%20programaci%C3%B3n%20Python,aplicaciones%20empresariales%20fiables%20y%20escalables.](https://www.esic.edu/rethink/tecnologia/para-que-sirve-python#:~:text=El%20lenguaje%20de%20programaci%C3%B3n%20Python,aplicaciones%20empresariales%20fiables%20y%20escalables. "¿Para qué sirve Python? Razones para utilizar este lenguaje de programación")

KeepCoding. (2023). KeepCoding. Obtenido de [https://keepcoding.io/blog/ventajas-y-desventajas-de-python/](https://keepcoding.io/blog/ventajas-y-desventajas-de-python/ "Ventajas y desventajas de Python")