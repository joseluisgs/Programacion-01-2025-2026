
### **Batería de Ejercicios: Fundamentos de Programación con Pseudocódigo DAW**

- [**Batería de Ejercicios: Fundamentos de Programación con Pseudocódigo DAW**](#batería-de-ejercicios-fundamentos-de-programación-con-pseudocódigo-daw)
  - [**Bloque I: Primeros Contactos, Inferencia y Constantes**](#bloque-i-primeros-contactos-inferencia-y-constantes)
  - [**Bloque II: Interacción y Casting Explícito**](#bloque-ii-interacción-y-casting-explícito)
  - [**Bloque III: Representación de la Información y Enumeraciones**](#bloque-iii-representación-de-la-información-y-enumeraciones)
  - [**Bloque IV: Cálculos, Conversiones y Asignación Explícita**](#bloque-iv-cálculos-conversiones-y-asignación-explícita)
  - [**Bloque V: Operadores Lógicos y Ternarios Básicos**](#bloque-v-operadores-lógicos-y-ternarios-básicos)
  - [**Bloque VI: Manejo de Nulos y Coalescencia Nula**](#bloque-vi-manejo-de-nulos-y-coalescencia-nula)
  - [**Bloque VII: Prioridad y Expresiones Aritméticas**](#bloque-vii-prioridad-y-expresiones-aritméticas)
  - [**Bloque VIII: Expresiones Lógicas y Condicionales**](#bloque-viii-expresiones-lógicas-y-condicionales)
  - [**Bloque IX: Estructuras, Enum y Lógica Avanzada**](#bloque-ix-estructuras-enum-y-lógica-avanzada)
  - [**Bloque X: Desafíos Avanzados de Datos y Ajustes**](#bloque-x-desafíos-avanzados-de-datos-y-ajustes)
  - [**Bloque XI: Lógica Relacional y Leyes de De Morgan**](#bloque-xi-lógica-relacional-y-leyes-de-de-morgan)


**Instrucciones:** Para cada ejercicio, escribe el código completo en pseudocódigo DAW dentro de la función `Main`. 

#### **Bloque I: Primeros Contactos, Inferencia y Constantes**

**Ejercicio 1: Mensaje, Tipos Literales y Comentarios**
Crea un programa que muestre en la consola el texto: "Bienvenidos al curso DAW". Muestra en líneas separadas un valor entero (42), un valor decimal (3.1416) y un valor lógico (`true`). Incluye al inicio del bloque `Main` un comentario multilínea explicando el propósito del código.

**Ejercicio 2: Declaración Explícita y Convenciones**
Declara una variable `int` para `cantidadArticulos` (inicializa con 150) y una `string` para `nombreProveedor` (inicializa con "Tech Solutions"). Muestra el contenido de ambas variables, aplicando la convención `camelCase`.

**Ejercicio 3: Inferencia de Tipos (`var`)**
Utiliza la palabra clave `var` para declarar e inicializar tres variables: una con el valor 200, otra con 500.75, y una tercera con `false`. Muestra los valores de estas variables. **Justifica en un comentario por qué la inicialización es obligatoria al usar `var`**.

**Ejercicio 4: Constantes Fijas Esenciales**
Declara una constante `const decimal` para el valor de $\pi$ (3.14159) y otra `const int` para el número de días en una semana (7). Muestra ambos valores. Utiliza la convención **MAYÚSCULAS\_CON\_GUIONES** para las constantes.

---

#### **Bloque II: Interacción y Casting Explícito**

**Ejercicio 5: Capturando y Concatenando Nombre**
Solicita al usuario que ingrese su nombre y almacénalo en una variable `string`. Luego, muestra un saludo personalizado utilizando el operador de concatenación (`+`).

**Ejercicio 6: Leyendo Edad, Casting y Operador Ternario (Mayoría de Edad)**
Pide al usuario que introduzca su edad. La entrada debe ser leída como texto y **convertida explícitamente a `int`**. Utiliza el **operador ternario (`? :`)** para determinar y asignar a una variable `string` si la persona es "Mayor de edad" o "Menor de edad" (considerando >= 18). Muestra el mensaje resultante.

**Ejercicio 7: Leyendo Decimales y Conversión de Texto**
Solicita al usuario la temperatura ambiental actual (la cual puede tener decimales). Lee la entrada como texto y **conviértela explícitamente a `decimal`**. Muestra la temperatura convertida con un mensaje descriptivo.

**Ejercicio 8: Combinando Fragmentos y Tipos**
Declara una variable `string` con el valor "Éxito". Agrega a esta secuencia el texto " en la programación" utilizando el operador de concatenación. Muestra el resultado final. Adicionalmente, concatena el resultado con el valor entero 100 y explica el **casting implícito** que ocurre.

**Ejercicio 9: Suma de Dos Entradas Numéricas**
Pide al usuario dos números enteros. Lee y convierte ambas entradas. Muestra el resultado de su suma.

---

#### **Bloque III: Representación de la Información y Enumeraciones**

**Ejercicio 10: Detalles de un Producto (Selección de Tipos)**
Define las variables necesarias (`string`, `decimal`, `int`, `bool`) para almacenar: Código de producto, Nombre del producto, Precio unitario, Cantidad en inventario, y si ¿El producto está en oferta?. Asigna valores de ejemplo y muestra toda la información.

**Ejercicio 11: Ficha Descriptiva de una Película**
Declara variables con tipos apropiados para representar: Título de la película, Año de lanzamiento, Calificación promedio (ej. 7.5), Duración en minutos, y si ¿Es apta para todos los públicos?. Asigna datos y muéstralos.

**Ejercicio 12: Características de un Libro**
Define variables para almacenar: Título del libro, Número de páginas, Precio de venta, ¿Está disponible en stock?, y Número de edición. Asigna datos de ejemplo y visualiza la información.

**Ejercicio 13: Registro de Dispositivos Electrónicos**
Para un dispositivo, declara variables que guarden: Categoría, Modelo, Número de serie, Capacidad de almacenamiento en GB, Precio de compra, y si ¿Requiere una batería externa para funcionar?. Asigna valores y muestra todos los detalles.

**Ejercicio 14: Estados Posibles de una Tarea (Enum)**
Define una **enumeración** llamada `EstadoTarea` con los valores `INICIADA`, `EN_PROGRESO`, `FINALIZADA`, `PENDIENTE`, `CANCELADA`. Declara una variable que pueda tomar uno de estos valores y asígnale `EstadoTarea.EN_PROGRESO`. Muestra el estado actual de la tarea.

---

#### **Bloque IV: Cálculos, Conversiones y Asignación Explícita**

**Ejercicio 15: Aplicando un Ajuste de Precio (Asignación Explícita)**
Declara `precioBase` con 100.0 (`decimal`). Calcula y almacena en `precioFinal` el valor de `precioBase` después de aplicar un ajuste del 15% (multiplicando por 0.85). **Utiliza la asignación explícita**: `precioFinal = precioBase * 0.85;`. Muestra `precioFinal`.

**Ejercicio 16: Secuencia de Modificaciones con Asignación Explícita**
Declara `elementosIniciales` con 50 (`int`). Aumenta su valor en 10 utilizando asignación explícita. Luego, duplica su valor, también con asignación explícita. Muestra el valor final de `elementosIniciales`. (Ej: `elementosIniciales = elementosIniciales + 10;`)

**Ejercicio 17: Distribución de Cantidades y Sobrantes (Módulo y División Entera)**
Se tienen 125 unidades de un recurso (`int`) y se deben distribuir entre 8 destinatarios (`int`). Calcula cuántas unidades recibe cada destinatario (división entera, `/`) y cuántas unidades sobran (operador módulo, `%`). Muestra ambos resultados.

**Ejercicio 18: Cálculo de Saldo con Pérdida de Datos (Casting Explícito)**
Declara una variable `saldoCuenta` con `1500.75` (`decimal`) y `costoTransaccion` con `50` (`int`). Calcula el `saldoFinal`. Luego, fuerza la conversión del `saldoFinal` a un tipo **`int` (parte entera)** para guardarlo en `saldoParaReporte`. Muestra ambos saldos y explica en un comentario el efecto de la conversión explícita en la precisión.

**Ejercicio 19: Costo Total de una Compra con decimales**
Pide al usuario la cantidad de un producto (`int`) y su precio unitario (`decimal`). Calcula el costo total del pedido (`decimal`). Muestra el costo total.

---

#### **Bloque V: Operadores Lógicos y Ternarios Básicos**

**Ejercicio 20: Detección de Paridad con Operador Ternario**
Pide al usuario un número entero (`int`). Utiliza el **operador ternario (`? :`)** y el operador módulo (`%`) para asignar a una variable `string` si el número es "Par" o "Impar". Muestra el resultado.

**Ejercicio 21: Requisito de Acceso Dual (AND)**
Declara `usuarioActivo` con `true` y `tieneCredencial` con `false`. Utiliza el operador lógico **AND (`&&`)** para determinar si el acceso es concedido (ambas verdaderas). Muestra el resultado lógico.

**Ejercicio 22: Inversión de una Afirmación Lógica (NOT)**
Declara `condicionInicial` con `false`. Utiliza el operador lógico **NOT (`!`)** para obtener el valor contrario (negación). Almacena y muestra el nuevo valor.

**Ejercicio 23: Verificación de Rango Básico (OR)**
Pide al usuario un número entero. Determina si este número es **menor que 0 O es mayor que 100**. Muestra el resultado lógico.

**Ejercicio 24: Conversión de Tipo Booleano a String**
Tienes un valor `bool` llamado `estadoValidacion` con `true`. Conviértelo explícitamente a un tipo `string` para poder concatenarlo con un mensaje. Muestra el resultado final (ej. "Estado: True").

**Ejercicio 25: Selección de Máximo con Operador Ternario**
Declara dos variables enteras `numA` con 10 y `numB` con 20. Utiliza el **operador ternario (`? :`)** para asignar a una tercera variable (`valorMaximo`) el mayor de los dos números. Muestra `valorMaximo`.

---

#### **Bloque VI: Manejo de Nulos y Coalescencia Nula**

**Ejercicio 26: Manejo de Valores Ausentes con Coalescencia Nula (Enteros)**
Declara una variable entera que **pueda ser nula** (`int? puntuacionExtra`) y asígnale el valor `null`. Declara otra variable entera `puntuacionBase` con 0. Utiliza el **operador de coalescencia nula (`??`)** para asignar a `puntuacionExtra` el valor de `puntuacionBase` si `puntuacionExtra` es `null`. Muestra `puntuacionExtra`.

**Ejercicio 27: Texto Predeterminado para Nombres Ausentes (Cadenas)**
Declara una secuencia de texto que **pueda ser nula** (`string? nombreOpcional`) y asígnale `null`. Declara otra secuencia de texto `nombreDefecto` con "Anónimo". Asigna a `nombreOpcional` un valor por defecto si es `null`, utilizando el operador de coalescencia nula (`??`). Muestra el resultado, demostrando cómo se evita el valor `null`.

**Ejercicio 28: Procesamiento de Entrada Numérica con Respaldo**
Declara una variable `int?` llamada `entradaNumerica` y asígnale **`null`** (simulando una entrada no válida). Utiliza el **operador de coalescencia nula (`??`)** para asignar a una variable `numeroProcesado` el valor de `entradaNumerica` o `0` como valor por defecto. Muestra `numeroProcesado` y verifica si es un número par (usando `%`) y muestra el resultado lógico.

---

#### **Bloque VII: Prioridad y Expresiones Aritméticas**

**Ejercicio 29: Cálculo de Puntuación Acumulada Compleja**
Un jugador tiene una `puntuacionInicial` con 100 (`decimal`). Suma 25 puntos. Luego, el valor actual se reduce en un 10% (multiplicando por 0.9). Finalmente, gana 7 puntos extra. **Utiliza asignación explícita** para todas las modificaciones. Calcula y muestra el valor final de la puntuación.

**Ejercicio 30: Evaluación de Expresión Aritmética con Precedencia**
Calcula el resultado de la expresión: `20 + 5 * 3 - 8 / 2 + 1`. Almacena el resultado en una variable entera y muéstralo, **mostrando el orden de las operaciones basado en la precedencia**.

**Ejercicio 31: Alterando el Orden de las Operaciones con Paréntesis**
Calcula el resultado de la expresión: `(20 + 5) * 3 - 8 / 2 + 1`. Almacena el resultado en una variable entera y muéstralo. Explica en un comentario cómo el uso de **paréntesis** alteró la precedencia respecto al ejercicio anterior.

**Ejercicio 32: Secuencia Compleja de Modificaciones Numéricas (Asignación Explícita)**
Declara una variable numérica `x` con valor 5. Realiza la siguiente serie de operaciones sobre `x`, **utilizando la asignación explícita (`=`)** en cada paso, y muestra `x` después de cada uno: 1. `x` se multiplica por 3. 2. `x` se le resta 7. 3. `x` se divide entre 2 (división entera). 4. `x` se le suma 4.

**Ejercicio 33: Cálculo de Crecimiento Compuesto Simplificado**
Un capital inicial de 1000.0 se invierte a un interés anual del 5%. Declara una constante `const decimal INTERES_ANUAL = 0.05;`. Calcula el capital acumulado después de 2 años, utilizando la fórmula simplificada `CapitalFinal = CapitalInicial * (1 + INTERES_ANUAL) * (1 + INTERES_ANUAL)`. Muestra el capital final.

---

#### **Bloque VIII: Expresiones Lógicas y Condicionales**

**Ejercicio 34: Lógica de Acceso Multi-Criterio con Precedencia**
Declara `credencialesValidas = true`, `licenciaActiva = false`, y `nivelAcceso = 5`. Determina si el usuario cumple la condición de tener: `credencialesValidas` **Y** (`licenciaActiva` **O** `nivelAcceso` es mayor o igual a 3). Almacena y muestra el resultado lógico.

**Ejercicio 35: Determinación Condicional de un Incentivo con Ternario**
Declara `ventasMes = 12000.0` y `añosServicio = 6`. Utiliza el **operador ternario (`? :`)** para asignar a `montoBono` (`decimal`) un valor de 1000.0 si (`ventasMes` >= 10000.0 **Y** `añosServicio` >= 5); de lo contrario, asigna 0.0. Muestra `montoBono`.

**Ejercicio 36: Precedencia en Operaciones Lógicas Complejas**
Declara tres variables lógicas: `c1` con `true`, `c2` con `false`, `c3` con `true`. Evalúa la expresión `!c1 || c2 && c3`. Almacena el resultado en una variable lógica y muéstralo, explicando el orden de precedencia (NOT, AND, OR).

**Ejercicio 37: Expresión Lógica de Rango Climático (OR/AND)**
Declara `temp = 25`, y `hum = 60`. Evalúa la expresión que verifica si **(ambiente cálido y seco: `temp` > 30 Y `hum` < 50) O (ambiente frío y húmedo: `temp` < 20 Y `hum` > 70)**. Almacena el resultado en una variable lógica y muéstralo.

**Ejercicio 38: Combinación de Tipos y Casting Explícito en Aritmética**
Declara un número entero `unidades` con 10 y un número con decimales `pesoUnitario` con 2.5. Calcula el `pesoTotal` (`decimal`). Luego, convierte `pesoTotal` a un tipo numérico entero para guardarlo en una variable `pesoEntero` **(casting explícito)**. Muestra ambos resultados.

---

#### **Bloque IX: Estructuras, Enum y Lógica Avanzada**

**Ejercicio 39: Ficha Completa de un Empleado con Enumeración**
Diseña una **enumeración** para `EstadoCivil` (`SOLTERO`, `CASADO`, `DIVORCIADO`, `VIUDO`). Declara variables para un empleado (Identificador, Nombre, Salario Base, Antigüedad, Contrato Indefinido) y asigna un valor del `enum` para `EstadoCivil`. Muestra todos los datos.

**Ejercicio 40: Control de Calidad de Componentes Avanzado (AND/Rango/NOT)**
Un componente es "válido" si: 1. Su peso está entre 10.0 y 15.0 (inclusive) **Y** 2. Su resistencia es estrictamente mayor a 200.0 **Y** 3. Su color **NO** es "Rojo".
Declara `peso = 12.5`, `resistencia = 210.0`, y `color = "Azul"`. Almacena en una variable lógica si el componente es "válido". Muestra el resultado.

**Ejercicio 41: Cálculo de la Nota Final Ponderada Compleja**
Calificaciones: `evaluacion1 = 7.5`, `evaluacion2 = 8.0`, `proyectoFinal = 9.0`. Declara constantes para los pesos (25% y 50%). Calcula y muestra la nota final ponderada (`decimal`).

**Ejercicio 42: Conversión de Temperatura con Criterio Múltiple y Ternario Anidado**
Pide al usuario una temperatura en grados Celsius (`decimal`). Utiliza el **operador ternario (`? :`) anidado** para asignar el resultado (`string` o `decimal`) basado en estas condiciones:
1. Si es < 0, convertir a Kelvin (C + 273.15).
2. Si es >= 0 Y < 100, convertir a Fahrenheit (C \* 9/5 + 32).
3. Si es 100 o más, el resultado es la secuencia de texto "Punto de Ebullición". Muestra el resultado.

**Ejercicio 43: Determinación de Elegibilidad Compleja (Precedencia Avanzada)**
Evalúa la elegibilidad con `edad = 22`, `ingresosAnuales = 28000.0`, `tieneAntecedentesPenales = false`. La elegibilidad es: **((`edad` >= 18 Y `ingresosAnuales` > 30000.0) O (`edad` >= 25 Y `ingresosAnuales` > 20000.0)) Y (`tieneAntecedentesPenales` es `false`)**. Almacena y muestra el resultado lógico, utilizando paréntesis para la correcta agrupación de condiciones.

---

#### **Bloque X: Desafíos Avanzados de Datos y Ajustes**

**Ejercicio 44: Verificación de un Código de Identificación Numérico (Rango y Módulo)**
Un código es válido si: 1. Es un número entero de 4 dígitos (entre 1000 y 9999 inclusive) **Y** 2. El último dígito es 0 o 5 (usando el operador módulo, `%`). Pide al usuario el número, almacena la verificación lógica y muéstrala.

**Ejercicio 45: Validación Simplificada de Fecha (Mes y Día)**
Declara `dia = 29`, `mes = 2`. Determina si esta combinación de día y mes es válida, asumiendo un año no bisiesto. Las condiciones son: Mes 2 $\leq$ 28, Meses 4, 6, 9, 11 $\leq$ 30, Resto $\leq$ 31. Además, el mes debe estar entre 1 y 12 y el día debe ser $> 0$. Almacena y muestra el resultado lógico de si la fecha es válida.

**Ejercicio 46: Operación de Balance y Detección de Deuda con Ternario**
Tienes un `balanceActual = 150.75` y un `montoGasto = 200.0`.
1. Calcula el `balanceFinal` (`decimal`).
2. Utiliza el **operador ternario (`? :`)** para asignar a una variable `string` el mensaje "En deuda" si el `balanceFinal` es negativo, o "Balance positivo" en caso contrario.
3. Muestra `balanceFinal` y el mensaje.

**Ejercicio 47: Cálculo de un Precio Final con Múltiples Ajustes**
Define `const decimal IVA_APLICABLE = 0.21` y `const decimal DESCUENTO_FIJO_EUROS = 5.0`. Pide el `precioUnitario` y `cantidadComprada` (`decimal`).
1. Calcula `subtotal` y `precioConIVA`.
2. Si `precioConIVA` $\leq 20.0$, aplica un `descuentoAdicional` del 10% (multiplicando por 0.9) **ANTES** de cualquier otro ajuste.
3. Luego, aplica el `DESCUENTO_FIJO_EUROS` **solo si** el precio actual es $> 50.0$ (utiliza el operador condicional anidado o la asignación condicional). Muestra el `precioFinal` tras todos los cálculos.

---

#### **Bloque XI: Lógica Relacional y Leyes de De Morgan**

**Ejercicio 48: Negación de un AND (Ley de De Morgan I)**
Una pieza es "defectuosa" si su `peso` > 500.0 **Y** su `longitud` < 10.0.
Declara `peso = 520.0`, `longitud = 12.0`. Expresa la condición que indica que la pieza **NO es defectuosa**, utilizando la **Ley de De Morgan** (transformando NOT (A AND B) en (NOT A) OR (NOT B)). Muestra el resultado lógico.

**Ejercicio 49: Negación de un OR (Ley de De Morgan II)**
Un evento se considera "urgente" si `esCritico` es `true` **O** `afectaClientes` es `true`.
Declara `esCritico = false`, `afectaClientes = false`. Expresa la condición que indica que el evento **NO es urgente**, utilizando la **Ley de De Morgan** (transformando NOT (A OR B) en (NOT A) AND (NOT B)). Muestra el resultado lógico.

**Ejercicio 50: Identificando un Valor Fuera de Rango (Lógica Invertida)**
Pide al usuario un número entero `valor`. Queremos determinar si este valor **NO está entre 10 y 20** (ambos inclusive). Crea una expresión lógica que determine esto, expresando directamente la condición de "estar fuera de rango". Muestra el resultado.