### Guía del Lenguaje DAW

Esta guía proporciona una visión general de los conceptos básicos del lenguaje DAW, diseñado para ser sencillo y fácil de aprender.
Con ella podrás entender la sintaxis y las estructuras fundamentales necesarias para comenzar a programar. Es importante seguir las convenciones y buenas prácticas recomendadas para escribir código claro y mantenible.

- [Guía del Lenguaje DAW](#guía-del-lenguaje-daw)
  - [0. Comentarios](#0-comentarios)
  - [1. Estructura del Programa](#1-estructura-del-programa)
  - [2. Tipos de Datos](#2-tipos-de-datos)
  - [3. Variables y Constantes](#3-variables-y-constantes)
  - [4. Conversión de Tipos (Casting)](#4-conversión-de-tipos-casting)
  - [5. Enumeraciones](#5-enumeraciones)
  - [6. Operadores](#6-operadores)
  - [7. Precedencia de Operadores](#7-precedencia-de-operadores)
  - [8. Entrada y Salida](#8-entrada-y-salida)


-----

#### 0\. Comentarios

Notas que el programa ignora y sirven para explicar el código.

  * **Comentario de una línea:** Empieza con `//`.
    ```csharp
    // Esto es un comentario de una sola línea.
    int edad = 30; // También al final de una línea.
    ```
  * **Comentario de varias líneas:** Empieza con `/*` y finaliza con `*/`.
    ```csharp
    /*
    Este es un comentario
    que ocupa varias líneas.
    */
    ```

-----

#### 1\. Estructura del Programa

Todo el código se escribe dentro de un bloque principal `Main`, que es el punto de entrada que se ejecuta al iniciar el programa. Cada instrucción termina con punto y coma (`;`). El código es sensible a mayúsculas y minúsculas y los bloques de código se delimitan con llaves `{}`.
Además, se recomienda usar indentación (tabulaciones o espacios) para mejorar la legibilidad.

```csharp
Main {
    // Aquí va el código de nuestro programa.
    writeLine("¡Hola, mundo!");
}
```

-----

#### 2\. Tipos de Datos

Definen qué valores puede almacenar una variable. Los principales son:

  * **`int`**: Almacena números enteros. Su valor por defecto es `0`.
  * **`decimal`**: Almacena números con decimales de alta precisión. Su valor por defecto es `0.0`.
  * **`string`**: Almacena texto. Su valor por defecto es `""` (cadena vacía).
  * **`bool`**: Almacena `true` o `false`. Su valor por defecto es `false`.

-----

#### 3\. Variables y Constantes

Usaremos la convención **`camelCase`** para variables y `readonly`, y **`MAYUSCULAS_CON_GUIONES`** para constantes.

  * **Variables:** Contenedores cuyo valor puede cambiar. Es una buena práctica inicializarlas siempre. Son almacenadas en memoria y tienen un tipo fijo, deben declararse antes de usarse y su tipo no puede cambiar. Son de Lectura y Escritura, es decir, se pueden leer y modificar.
    ```csharp
    Main {
      int edad = 20;
      string nombre = "Ana";
    }
    ```
    * Declaración: `tipo nombre = valor_inicial;` Ejemplo: `int contador = 0;`
    * Asignación: `nombre = "Pedro";` (cambia el valor de la variable)
    * Inicialización: Asignar un valor al declararla.
   
     ```csharp
     Main {
      int contador;        // Declaración sin inicializar (no recomendado)
      contador = 0;       // Asignación posterior
      int total = 100;    // Declaración e inicialización en una línea (recomendado)
    }
    ```

  * **Inferencia de Tipos con `var`:** El compilador deduce el tipo a partir del valor. La variable debe ser inicializada y su tipo no puede cambiar después.
    ```csharp
    Main {
      var edad = 25;        // Se infiere que es int
      var nombre = "Juan";  // Se infiere que es string
      // var x;      // ERROR: no se puede inferir sin un valor
      // edad = "Pedro";  // ERROR: una vez es int, no puede ser string
    }
    ```
  * **Variables Nulas (`?`):** Para permitir que una variable almacene `null` (ausencia de valor), se añade `?`. `null` es diferente de un valor por defecto como `0` o `""`. Debes tener cuidado al usar variables que pueden ser `null` para evitar errores en tiempo de ejecución.
    ```csharp
    Main {
      string apellido = "";        // Caja con una cadena vacía
      string? segundoApellido = null; // La caja está vacía, no hay valor
      int? edadOpcional = null;
    }
    ```
  * **Constantes (`const`):** Valores fijos que no pueden cambiar y deben inicializarse al declararse. Son útiles para valores que no deben modificarse.
    ```csharp
    Main {
      const decimal PI = 3.1416m;
      const int MAX_ALUMNOS = 30;
    }
    ```
  * **Variables de solo lectura (`readonly`):** Su valor se asigna una sola vez (al declarar o después) y luego no puede cambiar. 
    ```csharp
    Main {
      readonly string version = "1.0";
      readonly int anoNacimiento;
      anoNacimiento = 1990; // Se asigna una vez
      // anoNacimiento = 1991; // ERROR: ya fue asignado
    }
    ```
-----

#### 4\. Conversión de Tipos (Casting)

Es el proceso de cambiar un valor de un tipo a otro.

  * **Conversión Implícita:** El lenguaje la realiza automáticamente si no hay riesgo de perder datos.
    ```csharp
    Main {
      int numeroInt = 10;
      decimal numeroDecimal = numeroInt; // Conversión implícita de int a decimal
    }
    ```
  * **Conversión Explícita:** Se indica manualmente con `(tipo)` cuando puede haber pérdida de información.
    ```csharp
    Main {
      decimal numeroDecimal = 9.8m;
      int numeroInt = (int)numeroDecimal; // Se trunca la parte decimal, el resultado es 9
    }

-----

#### 5\. Enumeraciones

Permite crear un tipo de dato con un conjunto de constantes con nombre, haciendo el código más legible.

```csharp
Main {
  // Definición de la enumeración
  enum DiasSemana { LUNES, MARTES, MIERCOLES, JUEVES, VIERNES, SABADO, DOMINGO }

  // Uso de la enumeración
  var hoy = DiasSemana.Miercoles;
  writeLine("Hoy es " + hoy); // Muestra "Hoy es MIERCOLES"

  var mañana = DiasSemana.Jueves;
  writeLine("Mañana es " + mañana); // Muestra "Mañana es JUEVES"
}
```


-----

#### 6\. Operadores

  * **Operadores Aritméticos:** `+`, `-`, `*`, `/`, `%` (módulo o resto).
    *La división `/` se comporta diferente según el tipo:*
    ```csharp
    Main {
      int resultadoEntero = 9 / 2;      // Resultado: 4 (división entera)
      decimal resultadoDecimal = 9.0 / 2.0; // Resultado: 4.5 (división decimal)
    }
    ```
  * **Operadores de Asignación:** `=`, `+=`, `-=`, `*=`, `/=`, `%=`. Modifican el valor de una variable.
    ```csharp
    Main {
      int contador = 0;
      contador += 5; // Equivale a contador = contador + 5; Ahora contador es 5
      contador *= 2; // Equivale a contador = contador * 2; Ahora contador es 10
    }
    ```
  * **Operadores de Comparación:** `==`, `!=`, `>`, `<`, `>=`, `<=`. Devuelven `bool`.
    ```csharp
    Main {
      int a = 5;
      int b = 10;
      bool esIgual = (a == b);      // false
      bool esDiferente = (a != b);  // true
      bool esMayor = (a > b);       // false
      bool esMenorIgual = (a <= b); // true
    }
    ```
  * **Operadores Lógicos:** `&&` (Y), `||` (O), `!` (NO).
    ```csharp
    Main {
      bool esMayor = true;
      bool tienePermiso = false;
      bool puedeEntrar = esMayor && tienePermiso; // Resultado: false
      bool puedeSalir = esMayor || tienePermiso; // Resultado: true
      bool noEsMayor = !esMayor; // Resultado: false
    }
    ```
  * **Concatenación de Cadenas:** El operador `+` une cadenas de texto.
    ```csharp
    Main {
      int edad = 20;
      // Para operaciones matemáticas, usar paréntesis:
      writeLine("Dentro de 5 años tendrás " + (edad + 5)); // Muestra "Dentro de 5 años tendrás 25"
    }
    ```
  * **Operador Ternario (`? :`):** Selecciona entre dos valores según una condición.
    ```csharp
    Main {
      int edad = 20;
      string mensaje = (edad >= 18) ? "Eres mayor de edad" : "Eres menor de edad";
      writeLine(mensaje); // Muestra "Eres mayor de edad"
    }
    ```
  * **Operador de Nulidad (`??`):** Proporciona un valor por defecto si una variable es `null`.
    ```csharp
    Main {
      string? nombre = null;
      string nombreFinal = nombre ?? "Desconocido";
      writeLine(nombreFinal); // Muestra "Desconocido"
    }
    ```

-----

#### 7\. Precedencia de Operadores

Indica el orden en que se ejecutan las operaciones. Se puede alterar usando paréntesis `()`.

1.  `()`
2.  `*`, `/`, `%`
3.  `+`, `-`
4.  Operadores de comparación (`>`, `==`, etc.)
5.  `!` (NOT)
6.  `&&` (AND)
7.  `||` (OR)


```csharp
Main {
  // Sin paréntesis, la multiplicación va primero
  int resultado1 = 5 + 2 * 3; // 5 + 6 = 11
  // Con paréntesis, la suma va primero
  int resultado2 = (5 + 2) * 3; // 7 * 3 = 21
  writeLine("Resultado1: " + resultado1); // Muestra 11
  writeLine("Resultado2: " + resultado2); // Muestra 21
}
```

-----

#### 8\. Entrada y Salida

  * **Salida (`writeLine`):** Muestra texto o valores en la consola.
    ```csharp
    Main {}
      string nombre = "Ana";
      writeLine("Hola, " + nombre);
    }
    ```
  * **Entrada (`readLine`):** Lee texto introducido por el usuario. **Siempre devuelve un `string`**, por lo que necesita casting explícito para convertirlo a otros tipos.
    ```csharp
    Main {
      // Leer un string
      writeLine("Introduce tu nombre:");
      string nombreUsuario = readLine();

      // Leer un entero (int)
      writeLine("Introduce tu edad:");
      int edadUsuario = (int)readLine();

      // Leer un decimal
      writeLine("Introduce el precio:");
      decimal precioProducto = (decimal)readLine();

      // Leer un booleano (bool)
      writeLine("¿Estás de acuerdo? (true/false):");
      bool acuerdo = (bool)readLine();
    }
    ```