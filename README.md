# Programación - 01 - Introducción a la Programación Software

Tema 01 Introducción a la Programación Software. 1DAW. Curso 2025-2026.

![imagen](https://raw.githubusercontent.com/joseluisgs/Programacion-00-2022-2023/master/images/programacion.png)

- [Programación - 01 - Introducción a la Programación Software](#programación---01---introducción-a-la-programación-software)
- [Contenido en Youtube](#contenido-en-youtube)
- [1. Fundamentos de la Programación](#1-fundamentos-de-la-programación)
  - [1.1. ¿Qué es Programar?](#11-qué-es-programar)
  - [1.2. Algoritmos](#12-algoritmos)
    - [1.2.1. Características Esenciales](#121-características-esenciales)
    - [1.2.2. Diferencia entre Algoritmo y Programa](#122-diferencia-entre-algoritmo-y-programa)
- [2. Lenguajes de Programación](#2-lenguajes-de-programación)
  - [2.1. Conceptos Fundamentales del Lenguaje](#21-conceptos-fundamentales-del-lenguaje)
  - [2.2. Paradigmas de Programación](#22-paradigmas-de-programación)
  - [2.3. Clasificación de Lenguajes de Programación](#23-clasificación-de-lenguajes-de-programación)
    - [2.3.1 Según su cercanía al lenguaje humano (Nivel de Abstracción)](#231-según-su-cercanía-al-lenguaje-humano-nivel-de-abstracción)
  - [2.3.2. Según su mecanismo de traducción (Compilados, Interpretados, Mixtos)](#232-según-su-mecanismo-de-traducción-compilados-interpretados-mixtos)
    - [2.3.3. Según su sistema de tipos (Rigidez, Momento de Verificación, Declaración, Sin Tipado)](#233-según-su-sistema-de-tipos-rigidez-momento-de-verificación-declaración-sin-tipado)
    - [2.3.4. Según Generaciones](#234-según-generaciones)
- [3. Elementos Básicos de un Programa](#3-elementos-básicos-de-un-programa)
  - [3.1. Estructura y Bloques Fundamentales de un Programa](#31-estructura-y-bloques-fundamentales-de-un-programa)
    - [3.1.1. Bloque Principal](#311-bloque-principal)
    - [3.1.2. Entrada y Salida Básica de Datos](#312-entrada-y-salida-básica-de-datos)
  - [3.2. Tipos de Datos](#32-tipos-de-datos)
  - [3.3 Variables y Constantes](#33-variables-y-constantes)
    - [3.3.1 Variables](#331-variables)
    - [3.3.4 Constantes](#334-constantes)
    - [3.3.5 Variables de solo lectura](#335-variables-de-solo-lectura)
    - [3.3.6 Valores nulos](#336-valores-nulos)
    - [3.3.7 Enumeraciones](#337-enumeraciones)
  - [3.4 Conversiones y Casting](#34-conversiones-y-casting)
    - [3.4.1 Conversión implícita](#341-conversión-implícita)
    - [3.4.2 Conversión explícita](#342-conversión-explícita)
    - [3.4.3 Comparación: implícito vs explícito](#343-comparación-implícito-vs-explícito)
    - [3.4.4 Casting con cadenas](#344-casting-con-cadenas)
    - [3.4.5 Tabla de conversiones en el pseudolenguaje](#345-tabla-de-conversiones-en-el-pseudolenguaje)
    - [3.4.6 Ejemplo didáctico de diferencias](#346-ejemplo-didáctico-de-diferencias)
    - [3.4.7 Pros y contras de los castings](#347-pros-y-contras-de-los-castings)
    - [3.4.8 Reglas prácticas para estudiantes](#348-reglas-prácticas-para-estudiantes)
  - [3.5 Operadores](#35-operadores)
    - [3.5.1 Operadores aritméticos](#351-operadores-aritméticos)
    - [3.5.2 Operadores de comparación](#352-operadores-de-comparación)
    - [3.5.3 Operadores lógicos](#353-operadores-lógicos)
      - [Leyes de De Morgan](#leyes-de-de-morgan)
    - [3.5.4 Concatenación de cadenas](#354-concatenación-de-cadenas)
    - [3.5.5 Operador ternario](#355-operador-ternario)
    - [3.5.6 Operador de coalescencia nula](#356-operador-de-coalescencia-nula)
  - [3.6 Expresiones y precedencia de operadores](#36-expresiones-y-precedencia-de-operadores)
    - [3.6.1 Precedencia de operadores](#361-precedencia-de-operadores)
    - [3.6.2 Expresiones con cadenas y números](#362-expresiones-con-cadenas-y-números)
    - [3.6.3 Expresiones booleanas complejas](#363-expresiones-booleanas-complejas)
    - [3.6.3 Expresiones booleanas complejas](#363-expresiones-booleanas-complejas-1)
  - [3.7 Entrada y salida de datos](#37-entrada-y-salida-de-datos)
    - [3.7.1 Salida de datos](#371-salida-de-datos)
    - [3.7.2 Entrada de datos](#372-entrada-de-datos)
    - [3.7.3 Entrada de números u otros tipos usando casting explícito](#373-entrada-de-números-u-otros-tipos-usando-casting-explícito)
- [4. El Lenguaje de Programación Pseudocódigo DAW](#4-el-lenguaje-de-programación-pseudocódigo-daw)
  - [Autor](#autor)
    - [Contacto](#contacto)
  - [Licencia de uso](#licencia-de-uso)


# Contenido en Youtube

- [Podcast](https://youtu.be/V1btrIVQvyw)
- [Resumen](https://youtu.be/55elQsN0mF4)
- [Análisis de Lenguajes](https://youtu.be/4h7z0VSSMas)
- [Tipos de Datos](https://youtu.be/5qcnOjamqTk)
- [NULL: El error millonario](https://www.youtube.com/watch?v=tU2aAE1e9p4)
- [Lenguaje DAW: Primeros Pasos](https://youtu.be/xu9iVQpgxvc)
- [Lista de Reproducción](https://www.youtube.com/watch?v=wKCdgacEr4Q&list=PLGIH-7eZDbVw6q2AdcAUe2r6YxJYBkfCi)




# 1. Fundamentos de la Programación

## 1.1. ¿Qué es Programar?

**Programar** es el proceso de crear software. Esta disciplina abarca desde la concepción inicial de una idea hasta que el programa está implementado y funcionando en un ordenador, enfocándose en los principios y metodologías para el desarrollo y mantenimiento de sistemas de software. Algunos autores consideran que el término "desarrollo de software" es más apropiado que "ingeniería de software".

**Definición de Programa Software**
Un **programa software** es la parte intangible o lógica de un sistema informático, un conjunto de programas que actúan sobre el hardware para ejecutar las tareas deseadas por el usuario. Los programas son métodos para resolver problemas, procesando información para obtener un resultado a partir de datos de entrada. Para que un programa comience a funcionar, sus instrucciones deben ser traducidas a un lenguaje que la máquina entienda.

![img01](/images/entrada_salid2.png)

**El Proceso de Desarrollo de Software**
El desarrollo de software implica una serie de etapas obligatorias para construir software fiable y de calidad. Estas fases se dividen en tres pasos genéricos: definición (qué desarrollar), desarrollo, y mantenimiento.
Las fases principales del desarrollo de una aplicación informática son:
*   **Fase de Resolución del Problema**:
    *   **Análisis**: Requiere que el problema sea definido y comprendido claramente. Se establecen los objetivos, el alcance y se realiza un estudio de viabilidad y costes. Se identifican los requisitos funcionales (qué funciones realizará la aplicación) y no funcionales (características de calidad del sistema). También implica analizar la documentación, investigar y recopilar información útil. La culminación es el Documento de Especificación de Requisitos del Software (ERS), que actúa como contrato entre cliente y desarrollador.
    *   **Diseño**: Se define "cómo" hacer la solución. Se convierte la especificación del análisis en un diseño detallado, indicando el comportamiento o la secuencia lógica de instrucciones que resuelvan el problema. Se descompone la aplicación en operaciones más sencillas y se asignan a módulos. Incluye el diseño arquitectónico, diseño detallado, diseño de datos y de interfaz de usuario. Es crucial realizar una **prueba o traza del programa** para asegurar la solución antes de la implementación.
*   **Fase de Implementación**:
    *   **Codificación o Construcción**: Consiste en transformar o traducir los resultados obtenidos a un determinado lenguaje de programación. Se escribe el **código fuente** siguiendo las reglas gramaticales y la sintaxis del lenguaje. El código debe ser modular, correcto, legible, eficiente y portable.
    *   **Pruebas de Ejecución y Validación**: Se implanta la aplicación en el sistema y se verifica su funcionamiento. Se utilizan diferentes datos de prueba para ver si el programa responde a los requerimientos. Incluye pruebas unitarias, de integración, funcionales, estructurales y beta testing.
    *   **Documentación**: Es vital para el desarrollo y mantenimiento. Se distinguen la **documentación interna** (comentarios en el código fuente) y **documentación externa** (manuales técnicos, de usuario, de instalación, diagramas).
*   **Fase de Explotación y Mantenimiento**:
    *   **Explotación (Despliegue)**: Los usuarios finales utilizan la aplicación. Implica instalación, puesta a punto y funcionamiento en el equipo del cliente.
    *   **Mantenimiento**: Periódicamente, se realizan evaluaciones y modificaciones para adaptar el programa a nuevas necesidades, corregir errores o actualizarlo.
    *   **Retirada del Software**: Ocurre cuando el software llega al final de su vida útil y no es rentable mantenerlo.

A lo largo de todo el proceso de desarrollo de software, se debe aplicar siempre un **modelo de ciclo de vida**. Estos modelos son la serie de pasos a seguir para desarrollar un programa.

![img02](/images/metodologias-desarrollo-software.jpeg)

## 1.2. Algoritmos

**Concepto de Algoritmo y sus Características**
Un **algoritmo** es una serie de pasos claros y ordenados que te permiten resolver un problema específico. No es un programa de computadora en sí mismo, sino la **idea** detrás del programa. Piensa en él como una receta de cocina: sin importar si la preparas en una estufa de gas, eléctrica o de leña, el resultado es el mismo porque la receta (el algoritmo) es independiente de la herramienta. Un algoritmo te dice **qué hacer** y en qué **orden**, sin importar la máquina o el lenguaje de programación.

### 1.2.1. Características Esenciales

Para que un algoritmo sea considerado de calidad, debe cumplir con las siguientes características:

* **Finito**: Siempre debe terminar en un número limitado de pasos. No puede ser un proceso infinito.
* **Preciso**: Cada paso debe ser claro y no dar lugar a ambigüedades.
* **Definido**: Si usas los mismos datos de entrada, el algoritmo siempre debe producir el mismo resultado.
* **Eficiente**: Debe utilizar la menor cantidad de recursos (tiempo y memoria) posible.
* **General**: Debe servir para resolver una clase de problemas, no solo un caso particular.
* **Correcto**: Debe resolver el problema para el cual fue diseñado.

Además de estas características fundamentales, un buen algoritmo debe ser **comprensible**, **modificable** y **reutilizable**, lo que facilita su uso y mantenimiento a lo largo del tiempo. Para lograrlo, es crucial que esté bien **estructurado** y **documentado** con comentarios. Finalmente, todo algoritmo debe ser **probado** para asegurar que funciona correctamente en todos los casos posibles.

![img03](/images/algoritmo.jpg)

**Reglas para el Diseño de Algoritmos (Abstracción, Modularidad)**
Para diseñar soluciones correctas y eficientes, se deben considerar los siguientes conceptos:
1.  **Abstracción**: Realizar un análisis del problema para descomponerlo en problemas más pequeños y de menor complejidad, describiendo cada uno de manera precisa.
2.  **Divide y vencerás**: Una filosofía general para resolver problemas, central en el enfoque de abstracción y modularidad.
3.  **Encapsulación**: Ocultar la información para poder implementarla de diferentes maneras sin que esto influya en el resto de elementos.
4.  **Modularidad**: Estructurar cada parte en módulos independientes, donde cada uno tendrá su función correspondiente. El diseño modular (top-down design) descompone un problema en subproblemas más sencillos.

Para representar los algoritmos gráficamente, se pueden usar herramientas como **diagramas de flujo** (que usan símbolos gráficos y se utilizan en fases de análisis) y **pseudocódigo** (basado en palabras clave en lenguaje natural y es la técnica más utilizada).

### 1.2.2. Diferencia entre Algoritmo y Programa
La **diferencia fundamental entre algoritmo y programa** radica en que el algoritmo es una descripción de los pasos para resolver un problema de forma genérica e independiente de la máquina y del lenguaje de programación. En cambio, el **programa** consiste en esos mismos pasos, pero escritos en un lenguaje de programación específico para que puedan ser ejecutados en un ordenador y obtener la solución. Los lenguajes de programación son solo un medio para expresar el algoritmo, y el ordenador es el procesador para ejecutarlo.

**Tabla 1: Comparación entre Algoritmo y Programa**

| Característica           | Algoritmo                                                     | Programa                                                 |
| :----------------------- | :------------------------------------------------------------ | :------------------------------------------------------- |
| **Nivel de Abstracción** | Genérico, independiente de la máquina y el lenguaje.          | Específico, escrito en un lenguaje de programación.      |
| **Formato**              | Secuencia de pasos lógicos, pseudocódigo, diagramas de flujo. | Código fuente, instrucciones en un lenguaje concreto.    |
| **Ejecución**            | No ejecutable directamente por una máquina.                   | Ejecutable por un ordenador después de ser traducido.    |
| **Objetivo**             | Describir la solución a un problema.                          | Implementar la solución para que una máquina la ejecute. |



# 2. Lenguajes de Programación

## 2.1. Conceptos Fundamentales del Lenguaje

Un **lenguaje de programación** es un idioma artificial, un conjunto de reglas sintácticas y semánticas, símbolos y palabras especiales establecidas para la construcción de programas. Estos elementos permiten al programador escribir secuencias de comandos para que una máquina realice un comportamiento deseado.

Los elementos que componen un lenguaje de programación son:
*   **Léxico (Alfabeto)**: Es el conjunto finito de símbolos permitidos y palabras especiales, el vocabulario del lenguaje: letras, dígitos, operadores, signos de puntuación y palabras reservadas. Estos símbolos se combinan para formar los elementos básicos del lenguaje, como identificadores, literales y operadores. Ejemplos de léxico son: `+`, `-`, `*`, `/`, `=`, `;`, `{}`, `()`, `if`, `else`, `while`, `for`, `int`, `decimal`, `string`, `bool`, etc.
*   **Sintaxis**: Son las normas de construcción que rigen la estructura de las declaraciones y expresiones válidas en el lenguaje. Se refiere a las posibles combinaciones de los símbolos y palabras especiales. Define cómo se deben organizar los elementos léxicos para formar sentencias correctas. Por ejemplo, en muchos lenguajes, una sentencia de asignación debe seguir la estructura `identificador = expresión;`. La sintaxis es crucial para que el compilador o intérprete pueda entender y procesar el código correctamente. Ejemplo de una sentencia sintácticamente correcta: `int numero = 10;`.
*   **Semántica**: Es el significado de las construcciones y define las acciones que se llevarán a cabo con las combinaciones de los símbolos. Es importante tener en cuenta que pueden existir sentencias sintácticamente correctas, pero semánticamente incorrectas. Por ejemplo, la sentencia `int numero = "texto";` es sintácticamente correcta, pero semánticamente incorrecta porque intenta asignar un valor de tipo cadena a una variable de tipo entero. La semántica asegura que las operaciones y combinaciones de elementos tengan sentido dentro del contexto del lenguaje y el problema que se está resolviendo.

## 2.2. Paradigmas de Programación

Un **paradigma de programación** es un modelo fundamental o una filosofía para el diseño y la implementación de programas. Este modelo determina cómo será el proceso de diseño y la estructura final del código. Son como las "reglas del juego" que guían cómo se aborda la solución de un problema. El objetivo es reducir la dificultad para el mantenimiento, mejorar el rendimiento del programador y, en general, mejorar la productividad y calidad de los programas.

**Tipos de Paradigmas**
Existen diversos paradigmas, y muchos lenguajes modernos son multiparadigma, combinando características de varios para ofrecer flexibilidad (ej. Python, JavaScript, Java, Kotlin, C#).
*   **Programación Imperativa/Estructurada**: Se basa en una serie de comandos que la computadora ejecuta en orden para cambiar el estado del programa. Utiliza estructuras como sentencias secuenciales, selectivas (condicionales) y repetitivas (bucles). Ejemplos incluyen C y Pascal.
*   **Programación Procedimental**: Un subtipo del paradigma imperativo. Los programas se organizan en procedimientos (o funciones) que manipulan el estado global del programa, buscando la modularidad. Ejemplos incluyen C, Pascal y BASIC.
*   **Programación Orientada a Objetos (POO)**: Es el paradigma más utilizado. Los programas se construyen como una colección de **objetos** que interactúan entre sí. Un objeto es una instancia de una **clase** que contiene datos (atributos) y métodos para operar sobre ellos. La POO promueve la reutilización de código, depuración más sencilla y mejor mantenimiento, basándose en pilares como el polimorfismo, la herencia y la encapsulación. Ejemplos: C++, Python, Kotlin, C#. Java es un lenguaje totalmente orientado a objetos.
*   **Programación Declarativa**: Los programas describen el **resultado deseado**, no el proceso paso a paso para lograrlo. Suelen ser lenguajes interpretados.
    *   **Lógica**: Utiliza reglas y afirmaciones de lógica formal para que la computadora deduzca la respuesta, muy usada en inteligencia artificial. Ejemplo: Prolog.
    *   **Funcional**: Se enfoca en el uso de **funciones matemáticas** que no cambian el estado ni los datos externos, promoviendo código modular y estructurado. Ejemplos: Lisp, Haskell, Scala.
*   **Programación de Eventos**: El flujo del programa es impulsado por **eventos** (clics, movimientos del ratón, etc.). Común en interfaces gráficas de usuario (GUI) y servidores.
*   **Programación Reactiva**: Un subtipo de la programación de eventos que gestiona flujos de datos asincrónicos y la propagación de cambios, ideal para aplicaciones en tiempo real.
*   **Programación Multiparadigma**: Lenguajes que admiten y combinan múltiples paradigmas, permitiendo elegir el mejor enfoque para cada parte del problema. Ejemplos: C++, JavaScript, Python, Kotlin, C#.

## 2.3. Clasificación de Lenguajes de Programación

Los lenguajes de programación pueden ser clasificados en función de lo cerca que estén del lenguaje humano o del lenguaje de los computadores.

### 2.3.1 Según su cercanía al lenguaje humano (Nivel de Abstracción)
*   **Lenguajes de Bajo Nivel**: Totalmente dependientes de la máquina; un programa no puede migrarse a otras máquinas. Aprovechan al máximo las características del hardware.
    *   **Lenguaje Máquina**: Instrucciones en combinaciones de unos y ceros (código binario). Es el único lenguaje que el ordenador entiende directamente (no necesita traducción). Fue el primer lenguaje, único para cada procesador (no portable), rápido pero difícil de manejar y depurar.

        **Tabla 2: Operaciones en Lenguaje Máquina**
        | Operación | Lenguaje máquina | Decimal |
        | :-------- | :--------------- | :------ |
        | SUMAR     | 00101101         | 45      |
        | RESTAR    | 00010011         | 19      |
        | MOVER     | 00111010         | 58      |

    *   **Lenguaje Ensamblador**: Sustituyó al lenguaje máquina, utilizando mnemotécnicos (códigos de operación) en lugar de binarios. Necesita un programa ensamblador que lo traduzca a lenguaje máquina para ejecutarse. Aunque más legible, sigue siendo de bajo nivel, dependiente del hardware y difícil de usar, interpretar y modificar.

        **Tabla 3: Operaciones en Lenguaje Ensamblador**
        | Operación   | Mnemotécnico |
        | :---------- | :----------- |
        | MULTIPLICAR | MUL          |
        | DIVIDIR     | DIV          |
        | MOVER       | MOV          |

*   **Lenguajes de Medio Nivel**: Término no universalmente aceptado, se refiere a lenguajes como C que pueden acceder a registros del sistema y direcciones de memoria (características de bajo nivel) mientras realizan operaciones de alto nivel.
*   **Lenguajes de Alto Nivel**: Cercanos al lenguaje natural (inglés), independientes de la arquitectura del ordenador. Permiten al programador abstraerse del funcionamiento interno de la máquina. Utilizan sentencias y órdenes derivadas del idioma inglés. Necesitan un traductor para ser entendidos por la máquina. Incorporan librerías, funciones predeterminadas y suelen ofrecer *frameworks*. La mayoría de los lenguajes actuales se engloban aquí. Ejemplos: C++, Java, Python, JavaScript, PHP.

## 2.3.2. Según su mecanismo de traducción (Compilados, Interpretados, Mixtos)
Los programas se traducen a código binario ejecutable mediante compilación o interpretación.
*   **Lenguajes Compilados**: Necesitan un **compilador** que traduce el código fuente completo a código objeto (o código máquina) en un solo paso, antes de la ejecución. La ejecución es eficiente. Requieren un enlazador para unir el código objeto con librerías. El código es más seguro, ya que el código fuente no es directamente accesible. Ejemplos: C y C++.
    
    Un compilador realiza varias fases:
    1.  Análisis Léxico: Agrupa el código fuente en *tokens*.
    2.  Análisis Sintáctico: Comprueba la estructura gramatical y genera un árbol sintáctico.
    3.  Análisis Semántico: Verifica la lógica y compatibilidad de tipos.
    4.  Generación de Código Intermedio: Un código de bajo nivel independiente de la arquitectura.
    5.  Optimización de Código: Mejora el código para mayor eficiencia.
    6.  Generación de Código Objeto: Convierte el código a lenguaje máquina específico.
    7.  Enlazador (Linker): Une el código objeto con librerías.

*   **Lenguajes Interpretados**: No generan código objeto. Un **intérprete** lee y ejecuta el código fuente línea a línea, o instrucción por instrucción, en el momento. Son menos eficientes en ejecución que los compilados, ya que se traducen en tiempo de ejecución. Requieren que el intérprete esté cargado en memoria. El código fuente es legible, lo que puede comprometer la seguridad. Ejemplos: Perl, PHP, Python, JavaScript.
*   **Lenguajes Mixtos o Virtuales (Intermediarios)**: Combinan características de ambos. El código fuente se compila a un código binario intermedio (no ejecutable) llamado **bytecode**. Este bytecode es luego interpretado por una **máquina virtual** para ejecutarlo en cualquier plataforma compatible. Son más portables, buscando "compilar una vez y ejecutar en cualquier sistema". Java y C# son ejemplos clave de lenguajes mixtos.

![img04](/images/compilado_interpretado.jpeg)

![img05](/images/lenguajes_traduccion.gif)

### 2.3.3. Según su sistema de tipos (Rigidez, Momento de Verificación, Declaración, Sin Tipado)
Un **tipo de dato** es una clasificación que define el conjunto de valores que una variable puede tomar y las operaciones válidas que se pueden realizar sobre esos valores. Esta clasificación es fundamental porque **determina la cantidad de memoria que el sistema operativo debe reservar** para la variable.

El **sistema de tipos** de un lenguaje de programación es un conjunto de reglas que definen cómo se manejan y verifican estos tipos de datos.

*   **Rigidez (Tipado Fuerte vs. Tipado Débil)**:
    *   **Tipado Fuerte**: Requiere que los tipos de datos sean compatibles para realizar operaciones, evitando conversiones automáticas o "implícitas" entre tipos no relacionados. Esto previene errores inesperados y hace el código más robusto. Ejemplos: Python, Java, C#, Ruby.
    *   **Tipado Débil**: Permite conversiones de tipo automáticas, lo que puede llevar a errores difíciles de detectar. Ejemplos: JavaScript, PHP, VBScript.
*   **Momento de Verificación (Tipado Estático vs. Tipado Dinámico)**:
    *   **Tipado Estático**: La verificación de tipos se realiza en **tiempo de compilación**. El tipo de cada variable debe ser conocido y, a menudo, declarado explícitamente antes de ejecutar el programa. Si hay un error de tipo, el programa no compilará. Garantiza mayor seguridad y rendimiento. Ejemplos: C++, Java, C#, Swift.
    *   **Tipado Dinámico**: La verificación de tipos se realiza en **tiempo de ejecución**. No es necesario declarar el tipo de una variable explícitamente; el intérprete lo determina automáticamente. Una misma variable puede cambiar de tipo durante la ejecución. Ofrece flexibilidad, pero los errores de tipo solo se descubren en ejecución. Ejemplos: Python, JavaScript, Ruby, PHP.
*   **Declaración (Tipado Explícito vs. Implícito - Inferencia)**:
    *   **Tipado Explícito**: El programador debe declarar manualmente el tipo de cada variable. Ejemplo en C++: `int numero = 10;`.
    *   **Tipado Implícito (Inferencia de Tipos)**: El compilador o intérprete deduce el tipo de la variable a partir del valor asignado, sin que el programador tenga que declararlo. Esto hace el código más conciso y rápido de escribir. Ejemplo en Python: `numero = 10;`.
*   **Lenguajes sin Tipado (Tipado Nulo)**: En lenguajes de muy bajo nivel, como el ensamblador, no existe un sistema de tipos formal. Las variables se manejan como secuencias de bits, y es responsabilidad del programador interpretar los datos.

**Tabla 4: Resumen de Sistemas de Tipado**
| Sistema de Tipado     | Descripción                                                       | Ejemplos de Lenguajes |
| :-------------------- | :---------------------------------------------------------------- | :-------------------- |
| **Estático y Fuerte** | Tipos verificados en compilación; no hay conversiones implícitas. | C++, Java, C#         |
| **Dinámico y Fuerte** | Tipos verificados en ejecución; no hay conversiones implícitas.   | Python, Ruby          |
| **Estático y Débil**  | Tipos verificados en compilación; sí hay conversiones implícitas. | C, VBScript (algunos) |
| **Dinámico y Débil**  | Tipos verificados en ejecución; sí hay conversiones implícitas.   | JavaScript, PHP       |

### 2.3.4. Según Generaciones
La evolución de los lenguajes de programación se puede dividir en 5 etapas o generaciones:
*   **Primera Generación**: Lenguaje máquina.
*   **Segunda Generación**: Creación de los primeros lenguajes ensambladores.
*   **Tercera Generación**: Creación de los primeros lenguajes de alto nivel (C, Pascal, Cobol).
*   **Cuarta Generación**: Lenguajes capaces de generar código por sí solos (RAD), con los cuales se pueden realizar aplicaciones sin ser experto. Incluyen lenguajes orientados a objetos, permitiendo la reutilización de código. Suelen tener acceso a bases de datos, capacidades gráficas y generación de código automática. Ej. Visual Studio, IntelliJ.
*   **Quinta Generación**: Lenguajes orientados a la inteligencia artificial (LISP).


# 3. Elementos Básicos de un Programa
En este apartado aprenderemos los conceptos fundamentales para entender cómo se estructura un programa, los tipos de datos básicos y sus operaciones y cómo manejar variables y constantes. Estos son los bloques de construcción esenciales para cualquier lenguaje de programación.

## 3.1. Estructura y Bloques Fundamentales de un Programa
En este tema aprenderemos los conceptos básicos de programación usando pseudocódigo DAW, un lenguaje simplificado parecido a C# y Java, pero con una sintaxis más amigable para principiantes. Nos centraremos en la estructura fundamental de un programa y los tipos de datos básicos.

Con este pseudolenguaje, aprenderemos los conceptos esenciales que luego podremos aplicar en lenguajes reales como C#, Java, Python o JavaScript, pues son comunes a todos ellos.

### 3.1.1. Bloque Principal

Todo programa tiene un **punto de entrada**, llamado `Main`. Dentro de este bloque se escriben las instrucciones que se ejecutan al iniciar el programa.

```c#
Main {
    // Esto es un comentario
    writeLine("¡Hola, mundo!");
}
```

**Explicación:**

* Las **llaves `{ }`** delimitan un bloque de código.
* Cada instrucción termina con un **punto y coma `;`**.
* La **indentación** (4 espacios por nivel) mejora la legibilidad y muestra jerarquía.
* Los **comentarios** no afectan la ejecución y sirven para explicar el código.

  * Una línea: `// Comentario`
  * Varias líneas: `/* Comentario */`

### 3.1.2. Entrada y Salida Básica de Datos

Antes de aprender variables y operaciones, es importante saber cómo mostrar y recibir información.

* `writeLine(...)` → Muestra un **texto** en la consola.
* `readLine()` → Permite **leer un texto** desde la consola.

**Notas:**

* Todo lo que se escribe o se lee se hace como **texto**.
* Por ahora no entraremos en cómo manipular números o concatenar, solo se entenderá que **la consola comunica texto**.
* Más adelante aprenderemos cómo convertir ese texto a otros tipos y trabajar con él.

```c#
Main {
  writeLine("Introduce tu nombre:"); // Muestra texto en la consola
  readLine(); // Lee lo que el usuario escribe como texto
}
```

## 3.2. Tipos de Datos

Un **tipo de dato** define **qué valores puede almacenar una variable**, qué operaciones podemos hacer con esos valores y cuánto espacio ocupa en memoria.

| Tipo    | Valores posibles  | Tamaño en memoria | Operaciones permitidas | Ejemplo de valor |
| ------- | ----------------- | ----------------- | ---------------------- | ---------------- |
| int     | Números enteros   | 4 bytes           | + - \* / %             | 20               |
| decimal | Números decimales | 8 bytes           | + - \* /               | 12.5             |
| bool    | true, false       | 1 byte            | AND, OR, NOT           | true             |
| string  | Texto             | Variable          | Se verá más adelante   | "Juan"           |

**Notas:**

* Cada tipo tiene un **conjunto de valores posibles**.
* Cada tipo ocupa **un espacio en memoria** (el ordenador reserva una "caja" para cada valor).
* Cada tipo permite **operaciones específicas** (por ejemplo, no podemos sumar `bool` con `int`).
* Los **valores por defecto** son importantes:

  * `int` → 0
  * `decimal` → 0.0
  * `bool` → false
  * `string` → "" (cadena vacía, **no nulo**)

**Ejemplos y contraejemplos de valores:**

**Correcto:**

  ```c#
  Main {
    int edad = 25;
    decimal precio = 19.99;
    bool activo = true;
    string nombre = "";
  }
  ```
**Incorrecto (no permitido para ese tipo):**

  ```c#
  Main {
    int edad = "veinticinco"; // texto no puede ir en int
    int edad = 12.5;     // decimal no cabe en int sin conversión
    bool activo = "si";  // texto no puede ir en booleano
  }
  ```

## 3.3 Variables y Constantes

En un programa necesitamos **guardar datos** en memoria para poder trabajar con ellos.
Esto lo hacemos con **variables**, **constantes** y **readonly**. Cada uno de estos elementos cumple un propósito distinto.


### 3.3.1 Variables

Una **variable** es un **contenedor en memoria** que almacena un valor de un tipo específico.

* Cada variable tiene un **nombre (alias)** que nos permite acceder a su contenido. Usamos este "nombre" porque aprender la dirección de memoria es complicado. Es mejor usar nombres descriptivos como edad, precioTotal, nombreUsuario. Esto nos ayudará por ejemplo a no usar direcciones como 0x1A2B3C4D (hexadecimal, y además difícil de recordar).
* Cada variable tiene un **tipo de dato** que define qué valores puede almacenar (int, decimal, bool, string).
* Cada variable tiene un **espacio en memoria** reservado según su tipo, que el sistema operativo gestiona automáticamente.
* El valor de la variable puede **cambiar durante la ejecución** → se dice que es de **lectura/escritura**.
* La memoria puede imaginarse como una **caja con etiqueta** (el nombre de la variable). Dentro de esa caja guardamos el valor actual. Podemos abrir la caja (leer el valor) o cambiar su contenido (asignar un nuevo valor) y lo grande o pequeño que sea el valor depende del tipo de dato.


**Valores por defecto de las variables**

En nuestro pseudolenguaje, **todas las variables siempre tienen un valor por defecto** al declararse:

| Tipo      | Valor por defecto   |
| --------- | ------------------- |
| `int`     | `0`                 |
| `decimal` | `0.0`               |
| `bool`    | `false`             |
| `string`  | `""` (cadena vacía) |

Esto significa que aunque no inicialices, la variable no queda “sin valor”.
Pero **es mala práctica depender de los valores por defecto**: siempre inicializa al declarar.

Veamos unos ejemplos:

**Ejemplo correcto:**

```c#
Main {
    int edad = 20;
    decimal consumo = 5.7;
    bool activo = true;
    string nombre = "Ana";
}
```

**Ejemplo usando valores por defecto:**

```c#
Main {
  int edad;            
  writeLine(edad);     // Muestra 0

  string apellido;     
  writeLine(apellido); // Muestra "" (cadena vacía)
}
```

**Contraejemplo (mala práctica):**

```c#
Main {
  decimal precio;
  writeLine(precio);  // Aunque imprime 0.0, es mala práctica no inicializarlo
}
```

**Nota didáctica**: siempre inicializa las variables para que el código sea **claro y entendible**.


**Inferencia de tipos en declaraciones**

En ocasiones, escribir siempre el tipo de la variable puede ser repetitivo.
Nuestro pseudolenguaje permite **inferir el tipo automáticamente** a partir del valor que se asigna en la declaración. Esto hace el código más conciso y legible. Pero **no elimina la necesidad de entender qué tipo tiene cada variable**.

Para ello se usa la palabra clave `var`.

* El **tipo real** de la variable se decide en el momento de la inicialización.
* Una vez asignado, **el tipo no puede cambiar** → la variable no es “dinámica”, sigue siendo de tipo fijo. Por ejemplo, si se infiere como `int`, no se puede luego asignar un `string`.


**Ejemplo de inferencia correcto**

```c#
Main {
  var edad = 25;        // Se infiere que es int
  var precio = 19.95;   // Se infiere que es decimal
  var activo = true;    // Se infiere que es bool
  var nombre = "Juan";  // Se infiere que es string

  writeLine(edad);      // Muestra 25
  writeLine(precio);    // Muestra 19.95
  writeLine(activo);    // Muestra true
  writeLine(nombre);    // Muestra Juan
}
```

**Restricciones**

* **Siempre debe haber una inicialización** al declarar con `var`.

  ```c#
  Main {
    var x;      // ERROR: no se puede inferir el tipo sin un valor
  }

* **Una vez inferido, el tipo es fijo y no se puede cambiar:**

  ```c#
  Main {
    var edad = 30;   // int
    edad = "Pedro";  // ERROR: no se puede convertir string a int
  }
  ```


✅ **Conclusión**: La inferencia de tipos hace el código más **claro y conciso**, pero no elimina la necesidad de conocer qué tipo tiene cada variable.


**Buenas prácticas de nombres (variables)**

* Usar **camelCase** para variables:
  `cantidadAlumnos`, `longitudPiscina`, `precioTotal`.
* Los nombres deben ser **descriptivos**, no letras sueltas ni palabras sin sentido.

**Ejemplo correcto:**

```c#
Main {
  int cantidadAlumnos = 25;
  decimal precioEntrada = 2.5;
}
```

**Contraejemplo:**

```c#
Main {
  int x = 25;        // Poco claro
  decimal p = 2.5;   // No describe su función
}
```


**Declaración e inicialización**

* **Declarar**: indicar el tipo y nombre de la variable.
* **Inicializar**: darle un valor inicial.
* **Asignar**: cambiar el valor posteriormente con `=`.
* El operador `=` es el operador de **asignación**.

**Ejemplo:**

```c#
Main {
  int edad;           // Declaración (vale 0 por defecto)
  edad = 18;          // Inicialización
  edad = 19;          // Nueva asignación
}
```

**Contraejemplo:**

```c#
Main {
  int edad;
  edad = "Juan";   // ERROR: no se puede asignar un string a un int
}
```

**Nota didáctica**:
El símbolo `=` no significa “igualdad matemática”. Significa **“asignar a la variable de la izquierda el valor de la derecha”**.
Al usar inferencia de tipos con `var`, la inicialización es obligatoria y con ello se declara e inicializa en un solo paso.


### 3.3.4 Constantes

Una **constante** es un contenedor, variable, pero cuyo valor **no puede cambiar nunca** después de declararse. Es decir, esta variable es de **solo lectura** y su valor es fijo.

* Se inicializa **obligatoriamente en el momento de la declaración**.
* El compilador sustituye el nombre de la constante por su valor en todo el programa. Es por ello que se llaman constantes literales o constantes en tiempo de compilación.
* Se usa la palabra clave `const` para declararla.

**Ejemplo:**

```c#
Main {
  const decimal PI = 3.1416;
  const int MAX_ALUMNOS = 30;

  writeLine(PI);          // Muestra 3.1416
  writeLine(MAX_ALUMNOS); // Muestra 30
}
```

**Contraejemplo:**

```c#
Main {
  const int edad;
  edad = 20;        // ERROR: la constante debe inicializarse al declararse

  PI = 3.14;        // ERROR: no se puede modificar
}
```

**Buenas prácticas de nombres (constantes)**

* Usar **MAYÚSCULAS\_CON\_GUIONES\_BAJOS**:
  `MAX_PLANTAS`, `PI`, `IVA`.


### 3.3.5 Variables de solo lectura

Un **readonly** es parecido a una constante, pero con una diferencia importante:

* Solo se puede **asignar una vez**, pero **no necesariamente en tiempo de compilación**. Es decir, su valor puede depender de cálculos o entradas que se conocen solo en tiempo de ejecución y una vez asignado, no puede cambiar.
* Puede inicializarse al declararse o en un paso de inicialización posterior.
* Después pasa a ser de **solo lectura**.
* Se usa la palabra clave `readonly` para declararla.

**Ejemplo:**

```c#
Main {
  readonly decimal salarioBase = 1200.0;
  readonly int añoNacimiento;

  añoNacimiento = 1990;  // Se puede asignar una vez
  writeLine(añoNacimiento);
}
```

**Contraejemplo:**

```c#
Main {
  añoNacimiento = 1991;  // ERROR: ya se había asignado
}
```

**Buenas prácticas de nombres (readonly)**
* Usar **camelCase**:
  `salarioBase`, `añoNacimiento`, `precioProducto`.

### 3.3.6 Valores nulos

En algunos casos, una variable puede **no tener ningún valor**.
En ese caso, decimos que su valor es **`null`**.
¿Por qué es util tener una zona de memoria que no apunta a ningún valor? Porque a veces necesitamos representar la ausencia de valor, por ejemplo, cuando un dato es opcional o aún no se ha asignado. Pero esto puede ser peligroso si intentamos usar la variable sin comprobar antes si tiene valor. Es uno de los errores más comunes en programación. Por eso es importante entender bien qué es `null` y cómo manejarlo correctamente.

Pero **es recomendable evitar usar `null` y los valores nulos en la medida de lo posible, ya que puede complicar el código y llevar a errores difíciles de detectar. En su lugar, es mejor usar valores por defecto o estructuras que representen la ausencia de valor de manera más segura.**

De hecho es conocido como **una de las fuente de errores y bugs más comunes en programación, el famoso error de referencia nula** (null reference error) o el "billion dollar mistake" (error de los mil millones de dólares) como lo llamó Tony Hoare, el inventor del concepto.

En nuestro lenguaje tendremos control de nulos en los tipos básicos y en las cadenas usando `?` (nullable). Esto indica que la variable puede ser `null` o tener un valor del tipo indicado.

* `null` significa que la **caja está vacía**, no apunta a ningún contenido.
* Diferencia:

  * `string nombre = "";` → caja con cadena vacía (longitud 0, pero existe un valor).
  * `string? nombre = null;` → caja vacía (no hay valor).

**Ejemplo:**

```c#
Main {
  string? apellido = null;   // Caja vacía
  string nombre = "";        // Caja con cadena vacía

  int edad = 0;              // Caja con valor 0
  int? altura = null;        // Caja vacía
  int? peso = 75;           // Caja con valor 75 pero puede ser null

  writeLine(nombre);   // Muestra nada (pero existe un valor)
  writeLine(apellido); // No muestra nada, está vacío, es null
  writeLine(edad);     // Muestra 0
  writeLine(altura);   // No muestra nada, está vacío, es null se podría operar con null
  writeLine(peso);     // Muestra 75

  edad = null;      // ERROR: int no puede ser null
  altura = 1.75;    // Ahora altura tiene un valor
  peso = null;      // Ahora peso está vacío

  writeLine(altura); // Muestra 1.75
  writeLine(peso);   // No muestra nada, está vacío, es null
}
```

**Importancia de `null`**
* `null` es útil cuando **todavía no tenemos un valor real** para la variable.
* Es una **práctica no recomendada**, pues puede complicar el código y llevar a errores difíciles de detectar.
* **Es peligroso** si intentamos usar la variable sin comprobar antes si tiene valor.
* En nuestro pseudolenguaje, los tipos básicos (`int`, `decimal`, `bool`) **nunca son null por defecto**: siempre tienen un valor inicial.
* Para cadenas (`string`) el valor por defecto es `""` (cadena vacía).
* Si queremos que una variable pueda ser `null`, debemos declararla con `?` (nullable). 
  Ejemplo: `string? apellido = null;` o `int? altura = null;`.
* Siempre es buena práctica **comprobar si una variable es null** antes de usarla. Operadores como `??` (operador de coalescencia nula) pueden ayudar a manejar valores null de forma segura.
* **Estamos suponiendo que no muestra nada, porque no tiene valor, pero en realidad en la consola podría mostrar "null" o lanzar un error si no se maneja bien**.
* **En la práctica, es mejor evitar usar `null` y los valores nulos en la medida de lo posible, usando valores por defecto o estructuras que representen la ausencia de valor de manera más segura**.


![img](/images/null.png)


**Recuerda la imagen anterior, si no quieres mancharte las manos al limpiarte 💩, asegúrate de que no está en nulo 🧨🤯.**


### 3.3.7 Enumeraciones
Una **enumeración (enum)** es un tipo de dato especial que permite definir un conjunto de valores constantes con nombres significativos. Es útil cuando queremos representar un grupo limitado de opciones o estados, haciendo el código más legible y fácil de mantener.

**Características de las enumeraciones:**
* Se definen con la palabra clave `enum`.
* Cada valor en la enumeración es un identificador único.
* Se usan para mejorar la claridad del código, evitando el uso de números mágicos o

```c#
Main {
  enum DiasSemana { LUNES, MARTES, MIERCOLES, JUEVES, VIERNES, SABADO, DOMINGO }
  
  DiasSemana hoy = DiasSemana.MIERCOLES;
  
  writeLine("Hoy es " + hoy); // Muestra "Hoy es MIERCOLES"
}
```

## 3.4 Conversiones y Casting

En nuestro pseudolenguaje, a veces necesitamos **cambiar el tipo de un valor** para poder usarlo en una operación o almacenarlo en una variable diferente. ¿Por qué? Porque no todos los tipos son compatibles entre sí, y a veces necesitamos convertir un tipo a otro para que la operación tenga sentido o simplemente por necesidades del programa.
Este proceso se llama **conversión de tipos** o **casting**.

Un **casting** es una instrucción que le indica al lenguaje que trate un valor de un tipo como si fuera de otro.

Existen dos tipos de conversiones:

1. **Conversión implícita** → la hace automáticamente el lenguaje, si es segura.
2. **Conversión explícita** → la indica el programador, si puede haber pérdida de información.


### 3.4.1 Conversión implícita

El pseudolenguaje convierte automáticamente un valor de un tipo a otro **siempre que no haya riesgo de pérdida de datos**.
No hace falta escribir nada especial, ocurre de manera automática cuando un tipo "cabe" en otro.

**Ejemplo válido**

```c#
Main {
  int a = 10;
  decimal b = a;      // Conversión implícita (int → decimal, no hay pérdida)
  writeLine(b);       // Muestra 10.0 (parte decimal .0 añadida automáticamente)
}
```

Aquí no hay problema: un número entero **cabe perfectamente** en un decimal.

**Ejemplos implícitos comunes**

```c#
Main {
  int edad = 20;
  string mensaje = "Edad: " + edad;     // int → string (concatenación, lo veremos más adelante)
  writeLine(mensaje);                   // "Edad: 20"

  decimal precio = 12.5;
  string texto = "Precio: " + precio;   // decimal → string (concatenación, lo veremos más adelante)
  writeLine(texto);                     // "Precio: 12.5"

  bool activo = true;
  string estado = "Activo: " + activo;  // bool → string (concatenación, lo veremos más adelante)
  writeLine(estado);                    // "Activo: true"
}
```

**Contraejemplo**

```c#
Main {
  decimal x = 9.8;
  int y = x;     // ERROR: no se puede convertir automáticamente de decimal a int, se pierde la parte decimal
}
```

Esto da error porque **podría perderse la parte decimal**.
Para hacerlo debemos usar **conversión explícita**.

### 3.4.2 Conversión explícita

Cuando una conversión **puede provocar pérdida de información** o **no es natural**, el programador debe indicarla de forma manual. Es tu deber como programador indicarlo y correr con el riesgo de la pñérdia de información.
Se escribe el tipo deseado entre paréntesis: `(tipo)`.

**Ejemplo correcto**

```c#
Main {
  decimal x = 9.8;
  int y = (int)x;     // Conversión explícita
  writeLine(y);       // 9 (se pierde la parte decimal .8, se trunca)
}
```

**Contraejemplo (olvidar el casting)**

```c#
Main {
  decimal x = 9.8;
  int y = x;          // ERROR: el lenguaje no permite esto sin casting, se pierde datos.
}
```

### 3.4.3 Comparación: implícito vs explícito

| Tipo de conversión | ¿Cuándo ocurre?          | ¿Pérdida de datos?   | Ejemplo         |
| ------------------ | ------------------------ | -------------------- | --------------- |
| **Implícito**      | Automática, si es segura | ❌ No                 | `int → decimal` |
| **Explícito**      | Manual, con `(tipo)`     | ✅ Puede perder datos | `(int)9.8 → 9`  |


### 3.4.4 Casting con cadenas

La cadena (`string`) es un tipo especial porque **toda entrada y salida se maneja como texto**.
Esto implica que casi siempre será necesario convertir **de valores a texto** o **de texto a valores**.


**De valor a texto (implícito, con concatenación)**

```c#
Main {
  int edad = 20;
  string mensaje = "Edad: " + edad;   // Conversión implícita int → string (concatenación)
  writeLine(mensaje);                 // "Edad: 20"
}
```

**De texto a valor (explícito)**

```c#
Main {
  string entrada = "25";
  int numero = (int)entrada;     // Conversión explícita string → int, puede fallar si el texto no es un número válido correcto
  writeLine(numero + 5);         // 30
}
```

**Contraejemplo (error si el texto no es válido):**

```c#
Main {
  string entrada = "hola";
  int numero = (int)entrada;     // ERROR: "hola" no es un número entero y provoca fallo en tiempo de ejecución
}
```

### 3.4.5 Tabla de conversiones en el pseudolenguaje

| De / A      | int       | decimal   | bool      | string    |
| ----------- | --------- | --------- | --------- | --------- |
| **int**     | —         | Implícita | ❌ No      | Implícita |
| **decimal** | Explícita | —         | ❌ No      | Implícita |
| **bool**    | ❌ No      | ❌ No      | —         | Implícita |
| **string**  | Explícita | Explícita | Explícita | —         |

Leyenda:

* ✅ Implícita → se convierte automáticamente.
* ❌ No → no existe conversión posible.
* Explícita → necesita `(tipo)` para forzarla.


### 3.4.6 Ejemplo didáctico de diferencias

Para entender estos ejemplos deberás comprender que cada tipo tiene asociado unos operadores que dictan cómo se realiza la operación asociada.

```c#
Main {  
  int a = 5;
  int b = 2;

  decimal div1 = (decimal)a / b;   // 2.5 (casting de a y división)
  int div2 = a / b;                // 2 (división entera)
  decimal div3 = a / b;            // 2.0 (porque a y b son enteros, luego se convierte)
}
```

**Explicación:**

* En `div1`, al convertir `a` en `decimal`, la operación se hace con decimales y se obtiene el valor exacto. Es la división decimal (5.0 / 2.0 = 2.5).
* En `div2`, al ser ambos enteros, se descarta la parte decimal. Es la división entera (5 / 2 = 2).
* En `div3`, primero se hace la división entera (resultado 2) y después se convierte a decimal (2.0). Es la división entera seguida de conversión (5 / 2 = 2 → 2.0).


### 3.4.7 Pros y contras de los castings

* ✅ **Implícitos**

  * Más cómodos.
  * No hay riesgo de pérdida de información.
* ⚠️ **Explícitos**

  * Se usan cuando la conversión puede perder información.
  * Dan más control, pero también pueden provocar errores.
* ❌ **Malas prácticas**

  * Confiar en que un texto siempre es convertible a número.
  * Usar casting innecesario cuando el tipo ya es el correcto.


### 3.4.8 Reglas prácticas para estudiantes

1. **Si es seguro, el lenguaje lo hace por ti** (implícito).
2. **Si puede perder datos, debes indicarlo tú** (explícito).
3. **Las cadenas son especiales**:

   * Mostrar cualquier valor como texto es fácil (implícito).
   * Convertir texto a número o booleano puede fallar (explícito).
4. **Mejor usar siempre el tipo correcto** desde el principio que abusar de casting.


## 3.5 Operadores

Los **operadores** son símbolos que nos permiten realizar operaciones con valores o variables. Todos los tipos de datos tienen operadores específicos que definen qué operaciones son válidas y cómo se comportan.

Recuerda que aunque varios tipos compartan un operador, el resultado de usarlo difiera en función del tipo de dato. Por ejemplo la división entera y la división decimal, o la suma entera con la suma de cadenas (concatenación).

En este apartado veremos los operadores básicos de nuestro pseudolenguaje.


### 3.5.1 Operadores aritméticos

Se usan con **valores numéricos** (`int` y `decimal`).

| Operador | Significado                     | Ejemplo     | Resultado                      |
| -------- | ------------------------------- | ----------- | ------------------------------ |
| `+`      | Suma                            | `3 + 5`     | `8`                            |
| `-`      | Resta                           | `10 - 4`    | `6`                            |
| `*`      | Multiplicación                  | `7 * 2`     | `14`                           |
| `/`      | División entera                 | `9 / 2`     | `4` (si ambos son `int`)       |
| `/`      | División decimal                | `9.0 / 2.0` | `4.5` (si alguno es `decimal`) |
| `%`      | Módulo (resto) — solo con `int` | `9 % 2`     | `1`                            |

🔎 **Reglas importantes**:

* Si ambos operandos son `int`, la división es entera (se pierde la parte decimal).
* Si al menos uno es `decimal`, la división conserva los decimales.
* El operador `%` solo se aplica a enteros.
* Si uno de los operandos es `decimal`, el resultado es `decimal`.

**Ejemplo en pseudocódigo:**

```c#
Main {
  int a = 9;
  int b = 2;

  writeLine(a / b);   // 4
  writeLine(a % b);   // 1

  decimal x = 9;
  decimal y = 2;
  writeLine(x / y);   // 4.5

  var res = x / b;  // res es decimal (9.0 / 2)
  writeLine(res);   // 4.5 
}

```

### 3.5.2 Operadores de comparación

Sirven para comparar valores y siempre devuelven un **booleano** (`true` o `false`).

| Operador | Significado       | Ejemplo  | Resultado |
| -------- | ----------------- | -------- | --------- |
| `==`     | Igual a           | `5 == 5` | `true`    |
| `!=`     | Distinto de       | `5 != 3` | `true`    |
| `>`      | Mayor que         | `7 > 4`  | `true`    |
| `<`      | Menor que         | `2 < 8`  | `true`    |
| `>=`     | Mayor o igual que | `5 >= 5` | `true`    |
| `<=`     | Menor o igual que | `3 <= 2` | `false`   |

**Ejemplo:**

```c#
Main {
  int edad = 20;
  bool esMayor = edad >= 18;
  writeLine(esMayor);    // true

  bool esMenor = edad < 18;
  writeLine(esMenor);    // false

  bool esIgual = edad == 20;
  writeLine(esIgual);    // true

  bool esDistinto = edad != 25;
  writeLine(esDistinto); // true

}
```

### 3.5.3 Operadores lógicos

Los **operadores lógicos** trabajan con valores booleanos (`true`, `false`).
En nuestro pseudolenguaje:

* `AND` (y lógico) → Símbolo: `&&`
* `OR` (o lógico) → Símbolo: `||`
* `NOT` (negación) → Símbolo: `!`

**Tabla de verdad del AND (&&)**

| A     | B     | A AND B |
| ----- | ----- | ------- |
| true  | true  | true    |
| true  | false | false   |
| false | true  | false   |
| false | false | false   |

El resultado es verdadero solo si **ambos son verdaderos**.


**Tabla de verdad del OR (||)**

| A     | B     | A OR B |
| ----- | ----- | ------ |
| true  | true  | true   |
| true  | false | true   |
| false | true  | true   |
| false | false | false  |

El resultado es verdadero si **al menos uno es verdadero**.


**Tabla de verdad del NOT (!)**

| A     | NOT A |
| ----- | ----- |
| true  | false |
| false | true  |

Invierte el valor lógico.

**Ejemplo práctico**

```c#
Main {
  bool tieneEdad = true;
  bool tieneDni = false;

  bool puedeEntrar = tieneEdad && tieneDni;  
  writeLine(puedeEntrar);  // false

  bool accesoAlternativo = tieneEdad || tieneDni;  
  writeLine(accesoAlternativo); // true

  writeLine(!tieneEdad);  // false

  // Algo más complicado
  bool esFinDeSemana = false;
  bool esFestivo = true;
  bool puedeDescansar = esFinDeSemana || esFestivo;
  writeLine(puedeDescansar); // true

  // Algo con and or y not
  bool tienePase = true;
  bool esVip = false;
  bool esArtista = true;
  bool puedeAcceder = tienePase && (esVip || esArtista);
  writeLine(puedeAcceder); // true
}

```

#### Leyes de De Morgan

Sirven para **negar expresiones lógicas compuestas**.

**Ley 1**

`NOT (A AND B) = (NOT A) OR (NOT B)`

| A     | B     | A AND B | NOT (A AND B) | NOT A | NOT B | (NOT A) OR (NOT B) |
| ----- | ----- | ------- | ------------- | ----- | ----- | ------------------ |
| true  | true  | true    | false         | false | false | false              |
| true  | false | false   | true          | false | true  | true               |
| false | true  | false   | true          | true  | false | true               |
| false | false | false   | true          | true  | true  | true               |

Negar un **AND** equivale a negar cada término y unirlos con **OR**.


**Ley 2**

`NOT (A OR B) = (NOT A) AND (NOT B)`

| A     | B     | A OR B | NOT (A OR B) | NOT A | NOT B | (NOT A) AND (NOT B) |
| ----- | ----- | ------ | ------------ | ----- | ----- | ------------------- |
| true  | true  | true   | false        | false | false | false               |
| true  | false | true   | false        | false | true  | false               |
| false | true  | true   | false        | true  | false | false               |
| false | false | false  | true         | true  | true  | true                |

Negar un **OR** equivale a negar cada término y unirlos con **AND**.


### 3.5.4 Concatenación de cadenas

El operador `+` también sirve para **unir cadenas de texto** (`string`). Es la **concatenación**. Además, realiza una conversión implícita de otros tipos a `string` cuando es necesario.

```c#
Main {
  string nombre = "Ana";
  string saludo = "Hola " + nombre;
  writeLine(saludo);   // Hola Ana
}
```

Importante: si concatenamos un número con un `string`, el número se convierte automáticamente a texto (casting implícito).

```c#
Main {
  int edad = 20;
  writeLine("Tienes " + edad + " años");
  // Tienes 20 años

  // cuidado que si no es el resultado de la operación no es el esperado
  writeLine("Dentro de 5 años tendrás " + edad + 5);
  // Dentro de 5 años tendrás 205

  // para que funcione como esperamos, usamos paréntesis
  writeLine("Dentro de 5 años tendrás " + (edad + 5));
  // Dentro de 5 años tendrás 25
}

```

### 3.5.5 Operador ternario
El operador ternario es una forma concisa de escribir una condición que asigna un valor u otro según se cumpla o no una condición. Es útil siempre que hagamos una comparación. Esta formado por tres partes, para realizar una asignación condicional.

La sintaxis es: `condición ? valor_si_verdadero : valor_si_falso`

**Ejemplo:**

```c#
Main {
  int edad = 20;
  string mensaje = (edad >= 18) ? "Eres mayor de edad" : "Eres menor de edad"; // Condición ? valor si verdadero : valor si falso
  writeLine(mensaje); // En este caso muestra "Eres mayor de edad" porque edad es 20 y se cumple la condición

  bool esPar = (edad % 2 == 0) ? true : false; // Comprueba si edad es par
  writeLine(esPar); // true porque 20 es para

  int numero = 5;
  string tipoNumero = (numero % 2 == 0) ? "par" : "impar";
  writeLine(tipoNumero); // impar porque 5 es importar
}

```

### 3.5.6 Operador de coalescencia nula
El operador de coalescencia nula (`??`) se utiliza para proporcionar un valor predeterminado en caso de que una variable sea `null`. Es especialmente útil cuando trabajamos con variables que pueden ser nulas (nullable). **Repetimos que la opción ideal es no usar nulos hasta que no sea absolutamente necesario**.

La sintaxis es: `variable ?? valor_por_defecto`


**Ejemplo:**

```c#
Main {
  string? nombre = null;
  string nombreFinal = nombre ?? "Desconocido"; // Si nombre es null, usa "Desconocido"
  writeLine(nombreFinal); // Muestra "Desconocido"

  int? edad = null;
  int edadFinal = edad ?? 18; // Si edad es null, usa 18
  writeLine(edadFinal); // Muestra 18
}

```

## 3.6 Expresiones y precedencia de operadores

Una **expresión** es cualquier combinación de **variables, literales y operadores** que el pseudolenguaje puede evaluar para producir un **resultado**.

Por ejemplo:

```c#
Main {
  int a = 5;
  int b = 2;
  int c = a + b * 3;
  writeLine(c); // ?

  var total = a + b * 3; // Inferencia de tipo según el resultado
  writeLine(total); // ?
}
```

El resultado **no es 21**, sino `11`, porque existen **reglas de precedencia**.

### 3.6.1 Precedencia de operadores

La **precedencia** indica qué operaciones se **realizan primero** cuando no usamos paréntesis.

| Nivel | Operadores                                   | Ejemplo         | Resultado               |         |     |        |             |
| ----- | -------------------------------------------- | --------------- | ----------------------- | ------- | --- | ------ | ----------- |
| 1     | `()`                                         | `(a + b) * 3`   | Suma primero            |         |     |        |             |
| 2     | `*` `/` `%`                                  | `5 + 2 * 3`     | Multiplicación primero  |         |     |        |             |
| 3     | `+` `-`                                      | `5 + 2 - 1`     | Izquierda a derecha     |         |     |        |             |
| 4     | Comparación `==`, `!=`, `>`, `<`, `>=`, `<=` | `3 + 2 > 4`     | Se evalúa la suma antes |         |     |        |             |
| 5     | Lógicos `NOT`                         | `!true`         | Negación                |         |     |        |             |
| 6     | Lógicos `AND`                       | `true && false` | AND después de NOT      |         |     |        |             |
| 7     | Lógicos `OR`                        | `true OR false` | OR al final             |         |     |        |             |


**Ejemplo paso a paso:**

```c#
Main {
  int a = 5;
  int b = 2;
  int c = 3;

  bool resultado = a + b * c > 10 && b < c;
  writeLine(resultado); // ?
}
```

**Paso 1: Operaciones aritméticas**

* `b * c` → `2 * 3 = 6`
* `a + 6` → `5 + 6 = 11`

**Paso 2: Comparaciones**

* `11 > 10` → `true`
* `b < c` → `2 < 3` → `true`

**Paso 3: Operadores lógicos**

* `true AND true` → `true`

**Resultado final:**

```c#
writeLine(resultado); // true
```


**Uso de paréntesis para cambiar el orden**

Si queremos que se sume primero antes de multiplicar:

```c#
Main {
  int total = (a + b) * c;
  writeLine(total); // (5 + 2) * 3 = 21
}
```

### 3.6.2 Expresiones con cadenas y números

Cuando mezclamos **cadenas** y **números**, el `+` se interpreta como **concatenación**:
```c#
Main {
  int edad = 20;
  string mensaje = "Tienes " + edad + " años";
  writeLine(mensaje); // Tienes 20 años
}
```

```c#
Main {
  int edad = 20;
  string mensaje = "Tienes " + edad + " años";
  writeLine(mensaje); // Tienes 20 años
  }
```

* Aquí ocurre un **casting implícito**: `edad` se convierte a `string`.
* Si quisiéramos hacer una operación aritmética antes, usaríamos paréntesis:

```c#
Main {
  int edad = 20;
  string mensaje = "Dentro de 5 años tendrás " + (edad + 5);
  writeLine(mensaje); // Dentro de 5 años tendrás 25
}
```

### 3.6.3 Expresiones booleanas complejas

```c#
Main {
  int edad = 20;
  string mensaje = "Dentro de 5 años tendrás " + (edad + 5);
  writeLine(mensaje); // Dentro de 5 años tendrás 25
}
```

### 3.6.3 Expresiones booleanas complejas

```c#
Main {
  bool a = true;
  bool b = false;
  bool c = true;

  bool resultado = a && !b || c;
  writeLine(resultado); // ?
}
```

**Paso 1: NOT**

* `!b` → `!false` → `true`

**Paso 2: AND**

* `a && true` → `true && true` → `true`

**Paso 3: OR**

* `true || c` → `true || true` → `true`

```c#
writeLine(resultado); // true
```
**Nota didáctica sobre expresiones**

* Siempre **respetar la precedencia** o usar paréntesis para evitar errores.
* Las **expresiones se pueden anidar**: una expresión puede contener otras expresiones.
* En pseudolenguaje, la **evaluación es estricta y secuencial** según la precedencia.

## 3.7 Entrada y salida de datos

En programación, distinguimos:

* **Entrada:** datos que el usuario introduce.
* **Salida:** datos que el programa muestra en pantalla.

En nuestro pseudolenguaje:

* **`writeLine(valor)`** → muestra información en pantalla.
* **`readLine()`** → lee texto introducido por el usuario.

> **Importante:** toda entrada y salida se maneja como **texto (`string`)**. Para usar números u otros tipos, necesitamos **casting explícito**.


### 3.7.1 Salida de datos

`writeLine` se utiliza para mostrar **mensajes, valores de variables o resultados de expresiones**.

**Ejemplos:**

```c#
Main {
  int edad = 25;
  writeLine(edad);          // Muestra: 25

  string nombre = "Ana";
  writeLine(nombre);        // Muestra: Ana

  writeLine("Hola, mundo!"); // Muestra: Hola, mundo!
  writeLine("Tienes " + edad + " años"); // Muestra: Tienes 25 años
}
```

**Explicación didáctica:**

* Cada variable apunta a una **zona de memoria**.
* `writeLine` accede al contenido de esa zona y lo muestra en pantalla.
* En nuestro pseudolenguaje, **todo se convierte a texto automáticamente** para mostrarlo, usa casting implícito.

**Contraejemplos (mala práctica)**

```c#
Main {
  int cantidad;
  writeLine(cantidad);    // Muestra 0, pero es mejor inicializar
}
```

```c#
Main {
  string apellido;
  writeLine(apellido);    // Muestra "", cadena vacía
}
```
> Nota: los valores por defecto evitan errores, pero **siempre debemos inicializar variables**.

### 3.7.2 Entrada de datos

`readLine()` permite **leer texto** desde el teclado.
```c#
Main {
  writeLine("Introduce tu nombre:");
  string nombre = readLine();
  writeLine("Hola " + nombre);
}
```
**Siempre devuelve un `string`**, aunque el usuario escriba un número.
**Siempre hay que usar casting explícito** para convertirlo a otro tipo si es necesario.

**Ejemplo básico**

```c#
Main {
  writeLine("Introduce tu nombre:");
  string nombre = readLine();
  writeLine("Hola " + nombre);
}
```

**Flujo de ejecución:**

1. Muestra `"Introduce tu nombre:"`.
2. Espera la entrada del usuario.
3. Almacena lo introducido en `nombre`.
4. Muestra `"Hola "` seguido del valor de `nombre`.


### 3.7.3 Entrada de números u otros tipos usando casting explícito

Para convertir un `string` leído a un número:

```c#
Main {
  writeLine("Introduce tu edad:");
  string input = readLine();
  int edad = (int)input;     // Casting explícito de string a int
  writeLine("En 5 años tendrás " + (edad + 5));
}
```

Otro ejemplo con decimales:

```c#
Main {
  writeLine("Introduce el precio:");
  string input = readLine();
  decimal precio = (decimal)input;   // Casting explícito a decimal
  decimal total = precio * 2;
  writeLine("El total es " + total);
}
```

Otro ejemplo con booleanos:

```c#
Main {
  writeLine("¿Estás de acuerdo? (true/false):");
  string input = readLine();
  bool acuerdo = (bool)input;   // Casting explícito a bool
  writeLine("Has respondido: " + acuerdo); // true o false
}
```

**Explicación didáctica:**

* `readLine()` devuelve texto.
* Para usarlo como número, **indicamos manualmente el tipo** con `(int)` o `(decimal)`.
* Esto evita errores y permite hacer operaciones aritméticas.

**Buenas prácticas en entrada y salida**

1. **Inicializa variables** aunque tengan valor por defecto.
2. **Mensajes claros** al usuario antes de pedir datos.
3. **Siempre usar casting explícito** cuando se lea un número.
4. Mantener **identación clara y constante**:

```c#
Main {
  writeLine("Introduce tu nombre:");
  string nombre = readLine();
  writeLine("Hola " + nombre);
}
```

5. Recordar que `writeLine` puede mostrar **valores de variables, textos literales y expresiones**.


# 4. El Lenguaje de Programación Pseudocódigo DAW
El pseudocódigo DAW es un lenguaje de programación diseñado para ser sencillo y fácil de entender, ideal para principiantes en programación. Combina elementos de varios lenguajes de programación populares, como C#, Java y Python, para ofrecer una sintaxis clara y concisa.

Se usará para aprender los conceptos fundamentales de la programación antes de pasar a lenguajes más complejos y con ello facilitar la transición a lenguajes de programación reales. Con él se pueden crear programas estructurados y modulares y resolver problemas de programación comunes.

[Lenguaje de pseudocódigo DAW](/lenguaje_daw.md)


## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/JoseLuisGS_)

[![Twitter](https://img.shields.io/twitter/follow/JoseLuisGS_?style=social)](https://twitter.com/JoseLuisGS_)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)
[![GitHub](https://img.shields.io/github/stars/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto

<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
 <a href="https://joseluisgs.dev" target="_blank">
        <img src="https://joseluisgs.github.io/img/favicon.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://distreau.com/github.svg" 
    height="30">
    </a> &nbsp;&nbsp;
        <a href="https://twitter.com/JoseLuisGS_" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://g.dev/joseluisgs" target="_blank">
        <img loading="lazy" src="https://googlediscovery.com/wp-content/uploads/google-developers.png" 
    height="30">
    </a>  &nbsp;&nbsp;
<a href="https://www.youtube.com/@joseluisgs" target="_blank">
        <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" 
    height="30">
    </a>  
</p>

## Licencia de uso

Este repositorio y todo su contenido está licenciado bajo licencia **Creative Commons**, si desea saber más, vea
la [LICENSE](https://joseluisgs.dev/docs/license/). Por favor si compartes, usas o modificas este proyecto cita a su
autor, y usa las mismas condiciones para su uso docente, formativo o educativo y no comercial.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
JoseLuisGS</span>
by <a xmlns:cc="http://creativecommons.org/ns#" href="https://joseluisgs.dev/" property="cc:attributionName" rel="cc:attributionURL">
José Luis González Sánchez</a> is licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License</a>.<br />Creado a partir de la obra
en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/joseluisgs" rel="dct:source">https://github.com/joseluisgs</a>.