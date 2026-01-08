

### **Práctica: Análisis Comparativo de Lenguajes de Programación: Java, Python y PHP**

**Instrucciones:** Para cada sección, completa las tablas y responde a las preguntas utilizando la información de los materiales del curso y tu propia investigación. Justifica tus respuestas y proporciona ejemplos de código cuando sea necesario.

---

#### **1. Introducción: Java, Python y PHP en el Desarrollo de Software**

Java, Python y PHP son lenguajes de programación de alto nivel ampliamente utilizados en la industria. Cada uno tiene sus fortalezas y dominios de aplicación, lo que se deriva de sus características intrínsecas en cuanto a su diseño, sistema de tipos, mecanismos de traducción y paradigmas de programación. En esta práctica, explorarás estas diferencias y similitudes.

#### **2. Clasificación de Lenguajes de Programación**

**2.1. Según su Mecanismo de Traducción (Compilados, Interpretados, Mixtos)**

Cada lenguaje utiliza un proceso diferente para convertir el código fuente en instrucciones que la máquina pueda entender.
*   **Tarea:** Completa la siguiente tabla, describiendo el mecanismo de traducción principal de cada lenguaje, el proceso que sigue el código fuente para ser ejecutado y los tipos de archivos intermedios o finales que se generan.
*   **Pregunta de razonamiento:** ¿Qué implicaciones prácticas tiene cada mecanismo de traducción (compilado, interpretado, mixto) en términos de la velocidad de ejecución del programa y su portabilidad a diferentes sistemas operativos o arquitecturas de hardware? Justifica tu respuesta para cada lenguaje.

**Tabla 1: Mecanismo de Traducción**

| Característica         | Java | Python | PHP  |
| :--------------------- | :--- | :----- | :--- |
| **Clasificación**      |      |        |      |
| **Proceso de Trad.**   |      |        |      |
| **Archivos generados** |      |        |      |
| **Portabilidad**       |      |        |      |

**2.2. Según su Sistema de Tipos (Rigidez, Momento de Verificación, Declaración)**

El sistema de tipos de un lenguaje es crucial para la seguridad y el rendimiento del código.
*   **Tarea:** Completa la siguiente tabla, indicando si el lenguaje es de tipado fuerte o débil, si la verificación de tipos se realiza de forma estática (en compilación) o dinámica (en ejecución), y si la declaración de variables es explícita o se basa en inferencia (implícita).
*   **Pregunta de razonamiento:** Compara las ventajas y desventajas de un sistema de tipado estático y fuerte (como en Java) frente a uno dinámico y fuerte (como en Python) o dinámico y débil (como en PHP/JavaScript). ¿Cómo influyen estas diferencias en la detección de errores y en la flexibilidad del desarrollo?

**Tabla 2: Sistema de Tipos**

| Característica                                  | Java | Python | PHP  |
| :---------------------------------------------- | :--- | :----- | :--- |
| **Rigidez** (Fuerte/Débil)                      |      |        |      |
| **Momento de Verificación** (Estático/Dinámico) |      |        |      |
| **Declaración** (Explícito/Implícito)           |      |        |      |

**2.3. Paradigmas de Programación**

Los lenguajes pueden soportar diferentes filosofías para la construcción de programas.
*   **Tarea:** Completa la siguiente tabla, identificando el paradigma de programación principal asociado a cada lenguaje y mencionando al menos otros dos paradigmas que soporten, si aplica.
*   **Pregunta de razonamiento:** Un proyecto de desarrollo web complejo que involucra una interfaz de usuario interactiva y lógica de negocio en el servidor, ¿podría beneficiarse de la naturaleza multiparadigma de Python o Java/PHP? Explica cómo la capacidad de combinar diferentes paradigmas podría ser una ventaja en este contexto.

**Tabla 3: Paradigmas de Programación**

| Característica          | Java | Python | PHP  |
| :---------------------- | :--- | :----- | :--- |
| **Paradigma Principal** |      |        |      |
| **Otros Paradigmas**    |      |        |      |

**2.4. Según su Nivel de Abstracción**

*   **Pregunta de razonamiento:** Basándote en la clasificación de lenguajes según su cercanía al lenguaje humano, ¿en qué categoría general se encuentran Java, Python y PHP? Explica brevemente qué implica esta clasificación en términos de su facilidad de uso y dependencia del hardware.

#### **3. Elementos Fundamentales del Lenguaje**

**3.1. Estructura Básica y Sintaxis ("Hola Mundo")**

*   **Tarea:** Proporciona el código de un programa simple que muestre "Hola, mundo!" en la consola para cada uno de los tres lenguajes. Identifica las partes principales de su estructura (e.g., clases, funciones, indentación) y señala las reglas sintácticas básicas (final de sentencia, delimitadores de bloque, sensibilidad a mayúsculas y minúsculas).

| Java (Hola Mundo) | Python (Hola Mundo) | PHP (Hola Mundo) |
| :---------------- | :------------------ | :--------------- |
| ```java           | ```python           | ```php           |
|                   |                     |                  |
|                   |                     |                  |
| ```               | ```                 | ```              |

*   **Pregunta de razonamiento:** ¿Cómo maneja cada lenguaje la delimitación de bloques de código (e.g., llaves, indentación)? ¿Qué ventaja o desventaja percibes en cada enfoque?

**3.2. Declaración de Variables**

*   **Tarea:** Proporciona un ejemplo de cómo se declara e inicializa una variable de tipo entero y una de tipo cadena en cada lenguaje.
*   **Pregunta de razonamiento:** ¿Cuál es la principal diferencia en la forma de declarar variables entre Java y Python/PHP, considerando el concepto de "tipado explícito" e "inferencia de tipos"?

**3.3. Tipos de Datos Básicos**

*   **Tarea:** Nombra los tipos de datos básicos para representar enteros, números reales (con decimales), cadenas de texto y valores booleanos en cada lenguaje.
*   **Pregunta de razonamiento:** Java especifica un tamaño y formato idéntico para sus tipos primitivos en todas las plataformas. ¿Por qué esta característica es importante para la portabilidad de los programas Java, y cómo podría diferir en Python o PHP (donde todos los tipos son objetos)?

**3.4. Comentarios**

*   **Tarea:** Muestra cómo se escriben comentarios de una sola línea y de múltiples líneas en cada lenguaje.

| Java (Comentarios) | Python (Comentarios) | PHP (Comentarios) |
| :----------------- | :------------------- | :---------------- |
| ```java            | ```python            | ```php            |
|                    |                      |                   |
|                    |                      |                   |
| ```                | ```                  | ```               |

*   **Pregunta de razonamiento:** ¿Por qué los comentarios son considerados "esenciales para la legibilidad, el desarrollo y el mantenimiento colaborativo" en cualquier lenguaje de programación?

**3.5. Operadores**

*   **Tarea:** Para cada lenguaje, proporciona un ejemplo de cómo se utilizarían los operadores de suma (`+`), igualdad (`==`) y AND lógico (`&&` o `and`).
*   **Pregunta de razonamiento:** Explica brevemente el concepto de "precedencia de operadores" y por qué es importante para la evaluación de expresiones. ¿Cómo se puede modificar el orden de precedencia natural en cualquiera de estos lenguajes?

#### **4. Conclusión y Aplicabilidad**

*   **Pregunta de razonamiento:** Considerando todas las características analizadas (mecanismo de traducción, sistema de tipos, paradigmas, sintaxis), ¿para qué tipo de proyectos o escenarios crees que Java, Python y PHP son más adecuados respectivamente? Justifica tu respuesta destacando al menos dos características distintivas de cada lenguaje que lo hagan idóneo para dicho escenario.

