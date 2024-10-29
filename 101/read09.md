## 1. ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

JavaScript maneja varios tipos de datos, divididos en dos categorías principales: **tipos primitivos** y **tipos de referencia**.

### Tipos primitivos:

- **Number**: Representa valores numéricos, ya sea enteros o decimales.  
  Ejemplo: `let num = 42;`

- **String**: Representa texto. Los strings se delimitan con comillas simples (`'...'`), dobles (`"..."`), o acentos graves para interpolación de variables (`` `...` ``).  
  Ejemplo: `let str = 'Hello';`

- **Boolean**: Representa un valor de verdad, `true` o `false`.  
  Ejemplo: `let isTrue = true;`

- **Undefined**: Indica que una variable ha sido declarada pero no tiene valor asignado.

- **Null**: Representa la ausencia de un valor.

- **Symbol**: Introducido en ES6, representa un valor único e inmutable.

- **BigInt**: Representa números enteros de tamaño arbitrario, usando la sintaxis `n` al final del número (por ejemplo, `123n`).

### Tipo de referencia:

- **Object**: Los objetos en JavaScript son colecciones de pares clave-valor y pueden almacenar otros tipos de datos, incluidos arrays y funciones.  
  Ejemplo: `let obj = { name: 'John', age: 30 };`

## 2. ¿Cómo se utilizan las estructuras condicionales `if` y `else` en JavaScript, y qué propósito cumplen dentro de un programa?

Las estructuras condicionales `if` y `else` en JavaScript se utilizan para ejecutar diferentes bloques de código según ciertas condiciones. La estructura básica es:

```
if (condición) {
    // código si la condición es verdadera
} else {
    // código si la condición es falsa
}
```
## 3. ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

Los operadores en JavaScript incluyen:

### Operadores aritméticos:
Usados para realizar cálculos matemáticos.

- `+` (suma)
- `-` (resta)
- `*` (multiplicación)
- `/` (división)
- `%` (módulo)
- `++` (incremento)
- `--` (decremento)

**Ejemplo de uso:**


```let a = 10;
let b = 5;
let suma = a + b;  // 15
```

## 4. ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre `var`, `let` y `const` en cuanto a su alcance y mutabilidad?

- **`var`**: Declara una variable con alcance de función (o global si está fuera de una función). Puede ser redeclarada y modificada.

- **`let`**: Introducido en ES6, `let` declara una variable con alcance de bloque (dentro de `{ }`). Permite reasignación pero no redeclaración en el mismo bloque.

- **`const`**: Declara constantes. No permite reasignación ni redeclaración y su valor debe asignarse en el momento de su declaración.

