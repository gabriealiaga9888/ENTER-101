
## READ09 ##

**¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?**

PRIMITIVOS:

string → "Hola"
number → 42, 3.14
boolean → true, false
undefined → let x;
null → let y = null;
bigint → 123n
symbol → Symbol('id')

OBJETOS:
Object, Array, Function

**¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?**

COMPLEXO BASICO

```javascript
if (condición) {
    // Código a ejecutar si la condición es verdadera
} else {
    // Código a ejecutar si la condición es falsa
```

RESPUESTA EJEMPLO

```javascript
let edad = 20;

if (edad >= 18) {
    console.log("Eres mayor de edad.");
} else {
    console.log("Eres menor de edad.");
}
```

**¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?**

```javascript
let suma = 5 + 3; // 8
let potencia = 2 ** 3; // 8
```
Aritméticos: +, -, *, /, %, 

**¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?**

En JavaScript, las variables se declaran usando las palabras clave var, let o const. La diferencia principal entre ellas radica en su alcance (scope) y mutabilidad (si pueden ser modificadas después de su declaración).

