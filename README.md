[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16538641&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)

# Índice
- [Práctica 1: Introducción al desarrollo. Reflexiones](#práctica-1-introducción-al-desarrollo-reflexiones)
  - [Identificación de la Actividad](#identificación-de-la-actividad)
  - [Actividad: P 1.10: Reflexión y discusión sobre los resultados](#p-110-reflexión-y-discusión-sobre-los-resultados)
    - [1. Relación software y hardware](#1-relación-software-y-hardware)
    - [2. Del código fuente al ejecutable](#2-del-código-fuente-al-ejecutable)
    - [3. Generación de código intermedio](#3-generación-de-código-intermedio)
    - [4. Lenguajes de programación](#4-lenguajes-de-programación)
    - [5. Herramientas de desarrollo](#5-herramientas-de-desarrollo)

- [Referencias y Fuentes](#referencias-y-fuentes)
---

## Identificación de la Actividad
- **ID de la Actividad:** P1.1
- **Módulo:** `EDES`
- **Unidad de Trabajo:** Und 1
- **Fecha de Creación:** lunes, 7 de octubre de 2024, 00:00
- **Fecha de Entrega:** [Fecha de entrega]
- **Fecha de Cierre:** domingo, 20 de octubre de 2024, 23:59
- **Alumno:** 
  - **Nombre y Apellidos:** Daniel Villar Guttenberger
  - **Correo electrónico:** dvilgut2404@g.educaand.es
  - **Iniciales del Alumno:** DVG

#### Descripción de la actividad
Responder a unas preguntas sobre la Unidad 1 (herramientas, lenguajes, traductores, etc)y sobre las practicas que hemos hecho en relacion a la misma.

# P 1.10: Reflexión y discusión sobre los resultados

### 1. Relación software y hardware

#### 1.1. Primera parte

**1.1.1. ¿Cómo se ejecuta el código en el procesador?**  +
El procesador ejecuta las instrucciones que están almacenadas en RAM, recuperándolas de una a una y realizándolas rápidamente.

**1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?** 
La RAM almacena temporalmente datos sobre el estado del botón o el LED durante la ejecución del programa.

**1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?**
Los periféricos envían señales eléctricas al procesador. Al presionar un botón, el procesador interpreta la señal y controla el LED según las instrucciones del software.

#### 1.2. Segunda parte

**1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?** 
El procesador lee instrucciones de la RAM y responde a las entradas de los periféricos, como botones y LEDs, en ciclos rápidos.

**1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?**
Los datos se cargan en la RAM y son utilizados por el procesador. Al finalizar, los datos temporales se pierden a menos que se guarden en almacenamiento permanente.

**1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?** 
Las instrucciones del software guían al procesador en la manipulación de datos y en la interacción con los periféricos.

**1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?**
La simulación refleja interacciones básicas en un ordenador real, donde el procesador, la RAM y los periféricos colaboran en tareas más complejas.

### 2. Del código fuente al ejecutable

**2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?** 
El código fuente son las instrucciones legibles por humanos, no ejecutables directamente(lenguaje programación). El código objeto es la versión intermedia más cercana al lenguaje de máquina pero aún no ejecutable. Y el código ejecutable versión final que el ordenador puede ejecutar directamente.  

**2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?**
El ordenador no puede entender el código fuente porque solo entiende lenguaje de máquina (ceros y unos).

**2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?**  
El enlazado combina archivos de código objeto y bibliotecas en un único ejecutable, esencial para el funcionamiento del programa.

**2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?**
Sin código objeto no hay traducción del código fuente, por lo que no se puede ejecutar. Sin código ejecutable no hay archivo que el sistema operativo pueda ejecutar.

### 3. Generación de código intermedio

**3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?** 
Los código intermedio no es específico de hardware y se ejecuta en una maquina virtual que lo traduce. El código ejecutable tradicional es específico para un procesador y puede ejecutarse directamente sin traducción.

**3.2. ¿Por qué es útil tener una máquina virtual?**  
Es útil porque actúa como intermediario, permitiendo la ejecución de código intermedio en múltiples plataformas y asegurando consistencia entre los diferentes entornos que usemos.

**3.3. ¿Qué ventajas ofrece el código intermedio?**  
Ofrece:
Potabilidad: funciona en diferentes sistemas operativos sin recopilación. 
Seguridad: las máquinas virtuales controlan el acceso al sistema. Optimizan: permite técnicas como compilación Just-In-Time (JIT) para mejorar el rendimiento.

**3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?**  
Kolin, C#, Scala, Groovy, F#.

### 4. Lenguajes de programación

#### 4.1. Primera parte

Compara el proceso de ejecución entre el lenguaje **compilado** y el **interpretado**.  
**4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?**  
Los lenguajes compilados se traducen a código máquina antes de ejecutarse, permitiendo optimizaciones, mientras que los interpretados se analizan y ejecutan línea por línea, lo que puede hacerlos más lentos.

**4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?**
En lenguajes compilados, los errores se detectan en la fase de compilación. Si hay un error, el programa no se compila, y no se genera un ejecutable.
En los interpretados, se detectan durante la ejecución. Si hay un error, el intérprete lo muestra en el momento en que se encuentra con la línea en la que hay un error.

#### 4.2. Segunda parte

Compara un lenguaje de **alto nivel** con uno de **bajo nivel**.  
**4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?**  
Los lenguajes de alto nivel ofrecen mayor abstracción y son más intuitivos, mientras que los de bajo nivel requieren más manejo detallado del hardware.

**4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?**
Alto nivel es fácil de usar pero menos controlado; bajo nivel ofrece control y optimización, pero es más complejo.

#### 4.3. Tercera parte

Compara un lenguaje **orientado a objetos** vs **funcional**.  
**4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?**  
Utiliza objetos que encapsulan atributos y métodos, promoviendo la reutilización de código.

**4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?**
Se basa en funciones puras que no modifican el estado externo, promoviendo la inmutabilidad.

#### 4.4. Reflexión final

**4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?**  
En mi caso personal un lenguaje de alto nivel como Python me resulto más fácil gracias a ser de alto nivel es mas accesible por su sintaxis clara. Ademas es el primer lenguaje que uso y me ha sido relativamente fácil entenderlo comparado a otros lenguajes que he probado.

**4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?**  
Uno compilado es mejor para rendimiento y optimización. Como en aplicaciones de alto rendimiento.

**4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?**  
Alto nivel es preferido para rapidez y legibilidad; bajo nivel para control y optimización.

**4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?**
Puede parecer que trabajar con el paradigma orientado a objetos ofrezca naturalidad y organizacion frente al enfoque funcional que ofrece claridad y concisión, pero para usar el orientado a objetos requiere un cambio en la forma de organizar en nuestra mente a la hora de desarrollar software. En lo personal aun debo afianzar conceptos para que me resulte mas natural usarlo.

### 5. Herramientas de desarrollo

#### 5.1. Primera parte

Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.  
**5.1.1. ¿Qué hace cada una de las herramientas?**  
IDE facilita escritura y depuración de código. 
Git gestiona cambios y colaboración. 
Frameworks (como Django) estructura ny aceleran el desarrollo.
Bases de Datos almacenan y gestionan datos.

**5.1.2. ¿Qué tipo de tareas facilita?**  
IDE: Codificación y depuración.
Git: Control de versiones.
Frameworks: Desarrollo estructurado.
Base de datos: Consultas y almacenamiento de datos.

**5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?** 
IDE: Integración de herramientas.
Git: Gestión eficiente de versiones.
Frameworks: Bibliotecas específicas.
Bases de Datos: Gestión avanzada de datos.

**5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**  
Depende del IDE ya que si esta bien diseñado puede ser intuitivo y llegar a ser fácil. En mi caso me ha resultado complejo ya que hasta que no entiendes cual es la función y como usar el IDE te resulta difícil aprender a implementarlo.

**5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**  
En proyectos grandes donde se requiere gestión de múltiples archivos y depuración constante.

**5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**
Me da la sensación de que complican la interfaz con funcionalidades innecesarias. Ademas que se te hace pesado tantos recursos no sabes ni cuando usarlos.


#### 5.2. Segunda parte

Céntrate en una herramienta dentro de la misma categoría y compárala con otras:  
**5.2.1. ¿Qué herramienta se considera más útil y por qué?**  
He escogido editores de codigo. Teniendo encuenta los dos que he probado Notepad ++ y Visual Studi Code, diria que me resulta mas util visual studio code, ya que ofrece mas funcionalidades, personalización y es mas compelto.

**5.2.2. ¿Qué ventajas tiene una sobre la otra?**  
Notepad++ es mas ligero y rápido para usarse en tareas simples o edición rápida de archivos. Sin embargo VS Code ofreze mas opciones y para proyectos a gran escala es mucho mejor.

**5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?**  
Notepad me resulto mas intuitiva ya que aprendi a usarla solo sin tener concocimeintos previos de programacion ni de edicion de codigo y fue muy facil adaptarme a usarla.

**5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?**
Si el rendimiento, la verificación de errores y la optimización son importantes para tu proyecto, un compilador sería la mejor elección.

**5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?**
Django es beneficioso para proyectos en los que se necesita una solución completa y escalable en la que necesiten de interacción con base de datos y un enfoque en la seguridad y la rapidez de desarrollo

#### 5.3. Reflexión final

Con base en la experiencia de evaluación de las herramientas:  
**5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?**
Creo que tiene un gran impacto, ya que si no usamos las mejores herramientas en funcion de lo que necesite nuestro proyecto puede que tardemos mas o nuestros programas tarden mas en llegar a la version final del mismo, donde este completo y bien hecho.

**5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?**  
Una herramienta que me ahorre tiempo a la hora de errores ortograficos, o por ejemplo me ayude a organizar como voy realizando el trabajo por que parte voy y que voy necesitando.

**5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?**
 No sabia que me iba a encontrar, me sorprendio las diferencias que habian entre ambas mas haya del diseño. Las funciones que ofrecian cada una y lo completa que es la de VS code.


## Referencias y Fuentes
[Enlace temario UND1](https://revilofe.github.io/section3/u01/)

He usado chatgpt para orientarme en algunas preguntas o temas que no tenia claros. NO HAGO COPYPAST, me resulta una herramienta util para buscar informacion que no conozca o que me explique temas que no entiendo para asi poder realizar las actividades sabiendo lo que estoy haciendo.

- [Vuelta al indice](#Índice)