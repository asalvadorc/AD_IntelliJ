# IntelliJ Idea Ultimate

Todos nuestros programas estarán realizados en **Kotlin**, lenguaje desarrollado por JetBrains, y que está por encima de Java, por lo que todos los programas, clases... , realizados en Java, los podremos utilizar sin problemas, y además nos permitirá una programación mucho más cómoda. Además, es el lenguaje que utilizará tanto en el módulo de **PMDM** como en el de **DI**.

**IntelliJ IDEA** es la herramienta ideal para **Kotlin** porque está diseñada pensando en él, especialmente porque lo desarrolló **JetBrains** (los creadores de Kotlin). Reduce el tiempo de configuración, nos da herramientas avanzadas para escribir y depurar código, y simplifica todo el proceso de desarrollo.

**IntelliJ IDEA** ya lo conocéis, porque lo habéis estado utilizando en el módulo de programación de primero, no obstante, en el **apartado de Instalación** tenéis algunas indicaciones sobre su descarga e instalación.

En el **apartado de Configuración** tenéis las indicaciones para crear cada uno de los proyectos correspondientes a cada UD de este módulo.


## Instalación

En el momento de realizar estos apuntes la última versión es la **2025**. El enlace para su descarga es **[https://www.jetbrains.com/idea/](https://www.jetbrains.com/idea/)**{.azul}.

![Idea 1](img/download.png)|![Idea 1](img/ultimate.png)
---------------------------|-----------------------------

Seleccionamos **Download** y descargamos la **versión Ultimate**, que es la que nos proporcionará todas las herramientas para poder trabajar sin problemas.

!!!Note "Licencia"
    Para obtener una licencia de **estudiante**, que elimine la restricción de una versión de prueba de 30 días, es neceasario que la solicitéis en el enlace correspondiente y rellenéis los datos del formulario:


    
    ![Idea 2](img/licencia.png)|![Idea 3](img/formulario.png)
    ---------------------------|-----------------------------


## Configuración

Cuando creamos un nuevo proyecto en IntelliJ IDEA, el IDE nos ofrece diferentes configuraciones y plantillas iniciales: Java, Kotlin, proyectos con **Gradle** o **Maven**, aplicaciones Android, entre otras.

**Gradle** y **Maven** son unas herramientas de automatización de construcción de proyectos (build tool) muy utilizadas en el desarrollo de software.Se encargan de compilar, ejecutar, probar y empaquetar un proyecto, además de gestionar de forma automática las librerías externas que necesita.

En este módulo nos centraremos en estas configuraciones:

- **Kotlin** simple para ejercicios básicos.
- **Kotlin con Gradle** para manejo avanzado de ficheros y bases de datos.
- **Kotlin con Maven** y complemento **Spring** para proyectos web y APIs con Spring Boot.


|Sin Gradle|Con Gradle|
|----------|----------|
|![Idea 1](img/new_project.png)|![Idea 2](img/new_project_gradle.png)|


## Estructura de los proyectos por UD

Por cada UD se crearán uno o varios proyectos con una estructura fija para facilitar su corrección.

### UD Ficheros

En esta unidad crearemos dos proyectos:

- Un proyecto **sin Gradle**, que llamaremos **Ficheros**, destinado a todos los ejemplos relacionados con el sistema de ficheros y el manejo de archivos. En este proyecto crearemos tres paquetes (sistema, contenido y formatos) para organizar los diferentes ejemplos.

- Un proyecto **con Gradle**, que llamaremos **Ficheros_Gradle**, en el que trabajaremos con ficheros de distintos formatos.

A lo largo del tema se irá indicando en qué carpeta debe colocarse cada ejemplo.


|Proyecto Ficheros |Proyecto Fichero_Gradle|
|----------|----------|
|![Idea 1](img/estruc_ficheros.png)|![Idea 2](img/estruc_ficheros_gradle.png)|



### UD BD Relacionales

Para esta unidad didáctica, crearemos un proyecto llamado **BDRelacionales**, configurado **con Gradle**. Este proyecto se utilizará para realizar todos los ejemplos y ejercicios relacionados con el acceso a bases de datos relacionales desde Kotlin.

Con el fin de mantener una estructura organizada y diferenciada según el tipo de base de datos, se crearán dos paquetes:

- **Postgres**: donde se incluirán todos los ejemplos orientados al uso de bases de datos PostgreSQL.
- **Sqlite**: donde se desarrollarán los ejemplos utilizando bases de datos SQLite, tanto embebidas como externas.

En cada tema se especificará en qué paquete debe desarrollarse cada ejercicio, según la base de datos utilizada.

![Idea](img/estruc_bdrela2.png)

### UD BD ORM

### UD BD NoSQL

### UD Componentes

## Formato entrega ejercicios

Los ejercicios podéis realizarlos:

En ese mismo proyecto: en este caso, es recomendable crear una carpeta aparte llamada ejercicios para localizarlos fácilmente.

En un proyecto diferente: este será el que me entregaréis para su corrección.
La estructura para cada UD será la siguiente:


<!--El siguiente vídeo muestra todo el proceso de instalación y creación del primer proyecto. Corresponde a una versión anterior, pero totalmente similar a la actual.-->

<!--
# Galería de imágenes

## Idea 1

![Idea 1](img/idea1.png)

## Idea 2

![Idea 2](img/idea2.png)

-->

_________

<!--
<iframe src="https://slides.com/aliciasalvador/2021-2022-tema1_instal_intellij/embed" width="576" height="420" title="Copy of 2021-2022 Tema1_Instal_IntelliJ" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
-->



