### **Cuestionario: Razonamiento sobre Introducción a la Programación de Software**

**Instrucciones:** Lee cada pregunta con atención y proporciona una respuesta detallada, justificando tus afirmaciones con los conceptos aprendidos.

---

**1. Algoritmo vs. Programa en la Vida Real**
Imagina que necesitas un algoritmo para "preparar un café con una cafetera de cápsulas". Describe los pasos fundamentales de este algoritmo, asegurándote de que cumpla con las características esenciales de un algoritmo (preciso, definido, finito). Luego, explica cómo este algoritmo se transformaría en un "programa" para una cafetera inteligente, detallando la diferencia clave entre ambos conceptos.

**2. La Importancia Crucial del Análisis en el Desarrollo de Software**
En el caso práctico de Ada y Juan, Juan a menudo aborda el desarrollo de programas sentándose directamente a teclear código, lo que le lleva a "volver atrás, recodificar y rehacer gran parte del programa". Razona por qué la fase de "Análisis" es considerada la de "mayor importancia" en el desarrollo de software, y explica detalladamente qué riesgos y consecuencias negativas conlleva omitirla o realizarla de forma deficiente, tanto para el programador como para la calidad final del software.

**3. Comparativa de Paradigmas: POO vs. Imperativa/Estructurada**
Describe brevemente el paradigma de Programación Imperativa/Estructurada y la Programación Orientada a Objetos (POO). Analiza las principales ventajas que la POO ofrece sobre la Programación Imperativa/Estructurada cuando se desarrollan proyectos de software complejos, mencionando cómo sus pilares fundamentales (como polimorfismo, herencia y encapsulación) contribuyen a estas ventajas.

**4. Elección de Lenguaje según Nivel de Abstracción para Hardware Específico**
Un equipo de ingenieros necesita desarrollar un software para controlar un nuevo prototipo de robot que requiere interactuar directamente con registros de hardware y direcciones de memoria específicas para maximizar el rendimiento. Basándote en la clasificación de lenguajes según su cercanía al lenguaje humano (Nivel de Abstracción), ¿qué tipo de lenguaje de programación recomendarías para esta tarea y por qué? Menciona al menos dos desventajas significativas de tu elección para un proyecto de gran envergadura.

**5. Ventajas de los Lenguajes Mixtos en la Traducción**
Explica la diferencia fundamental entre un lenguaje compilado y un lenguaje interpretado en términos de su proceso de traducción y ejecución. Posteriormente, argumenta por qué un lenguaje mixto o intermedio, como se describe en las fuentes (ej. compilación a bytecode y ejecución en Máquina Virtual), ofrece ventajas significativas en términos de portabilidad y flexibilidad que los lenguajes puramente compilados o interpretados no poseen por sí solos.

**6. El Impacto del Sistema de Tipos en la Calidad del Software**
Un desarrollador inexperto te pregunta si es importante el "sistema de tipos" de un lenguaje. Explícale la relevancia de que un lenguaje sea de "Tipado Fuerte" y "Tipado Estático". Justifica cómo estas características pueden prevenir errores, mejorar el rendimiento y aumentar la seguridad y robustez del software, en comparación con un lenguaje de tipado débil y dinámico.

**7. Implicaciones del Uso de Tipos de Datos Incorrectos**
Un programa en pseudocódigo DAW necesita almacenar la edad de una persona (ej., "25 años") y la distancia entre dos ciudades (ej., "150.75 km"). Si un programador decide usar un tipo `string` para la edad y un `int` para la distancia, ¿qué problemas de almacenamiento de valores y operaciones podría encontrar en cada caso?. Sugiere el tipo de dato más adecuado para cada situación en pseudocódigo DAW, justificando tu elección.

**8. Diferenciando Variables y Constantes en Pseudocódigo DAW**
En el pseudocódigo DAW, describe la finalidad de las "variables" y las "constantes". Proporciona un ejemplo en pseudocódigo DAW de la declaración e inicialización de una variable que pueda cambiar y de una constante que no pueda cambiar, explicando por qué se utilizaría una `const` para un valor específico (ej., `PI = 3.14159`) en lugar de una variable.

**9. Evaluación de Expresiones y Uso de Paréntesis**
Dada la siguiente expresión en pseudocódigo DAW: `var resultado = 20 - 4 * 2 + 15 / 3;`.
1.  Calcula el valor de `resultado` siguiendo las reglas de precedencia de operadores. Muestra el orden de las operaciones.
2.  Si el programador deseara que la resta `(20 - 4)` se realizara antes que la multiplicación, ¿cómo modificaría la expresión y por qué crees que es una buena práctica de programación usar paréntesis incluso cuando la precedencia natural no lo exige?.

**10. El Valor Incalculable de los Comentarios en el Código**
Las fuentes indican que los comentarios son "esenciales para la legibilidad, el desarrollo y el mantenimiento colaborativo" de un programa. Razona con tus propias palabras la importancia de esta afirmación, especialmente en un escenario donde múltiples programadores trabajan en el mismo proyecto a lo largo del tiempo. ¿Qué ventajas prácticas aportan los comentarios y qué problemas podrían surgir si un código carece de ellos o son escasos?.

**11. Manejo de Nulos y Seguridad en el Código**
El concepto de null representa la ausencia de valor. Sin embargo, el pseudolenguaje DAW establece que es una práctica no recomendada evitar el uso de null en la medida de lo posible.
Basándote en las especificaciones del lenguaje DAW sobre valores nulos, contesta y justifica lo siguiente:
1. Riesgo Principal de null: Explica por qué se debe evitar el uso de valores nulos, detallando el principal riesgo que introduce esta práctica en el código y la complejidad que genera en el mantenimiento.
2. Alternativas y Seguridad: ¿Qué estrategias se ofrecen para garantizar que las variables estén siempre en un estado predecible y seguro, evitando la necesidad de null? 
3. Caso de Uso Justificado: Proporciona un escenario específico en el que el uso de null (declarado con el operador ?) está justificado o es útil, y explica la diferencia que representa ese null frente a un valor por defecto (como 0 o "").
