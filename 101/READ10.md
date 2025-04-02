
## READ10 ##

**¿Qué es “Control Flow” (Control de Flujo)?**

El control de flujo en programación determina el orden de ejecución del código. Se basa en estructuras como condicionales (if, else, switch), que permiten tomar decisiones según condiciones, y bucles (for, while, do...while), que repiten código mientras se cumpla una condición. También incluye return, break y continue para gestionar la salida de funciones y bucles. Su propósito es hacer que el programa se adapte a diferentes situaciones y no siga una ejecución lineal.

**¿Qué es una “function” (Función) de JavaScript?**

Las funciones permiten modularizar y organizar el código, mejorando su legibilidad y reusabilidad. Puedes llamarlas múltiples veces con diferentes argumentos sin tener que repetir el mismo código.

```javascript
function sumar(a, b) {
  return a + b;
}

console.log(sumar(3, 4)); // 7
```

**¿Cuántas veces se ejecutará un bucle “while”?**

Un bucle while en JavaScript se ejecutará mientras la condición especificada sea verdadera.

```javascript
let i = 0;
while (i < 5) {
  console.log(i);
  i++; // Incremento de i
}
```

**¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?**

Para agregar un elemento al final de un array en JavaScript, se utiliza el método push(). Este método añade uno o más elementos al final de un array y devuelve la nueva longitud del array.


```javascript
let frutas = ["manzana", "banana"];
frutas.push("naranja");

console.log(frutas); // ["manzana", "banana", "naranja"]
```
