# Condicionales en JavaScript

## Integrantes
- Carla López Soriano
- Sergio Mancebo Campos
- Sergio Martí Montes

## Lenguaje asignado
JavaScript - Condicionales (if, else if, else).

## 1. ¿Cómo se declaran las variables?

En JavaScript se utilizan principalmente `let` y `const` para declarar variables.

- `let`: permite modificar el valor de una variable.
- `const`: no permite reasignar su valor una vez declarado.

Ejemplo: `let nota = 8;`

## 2. ¿Cómo se delimitan los bloques de código?

En JavaScript se utilizan llaves `{ }` para indicar dónde empieza y termina un bloque de código.

A diferencia de Python, la indentación no es obligatoria para definir los bloques.

## 3. ¿Qué cambia en la sintaxis respecto a Python?

- Las condiciones se escriben entre paréntesis `( )`.
- Se utilizan llaves `{ }` en lugar de los dos puntos `:` y la indentación para delimitar los bloques.
- Se escribe `else if` en lugar de `elif`.
- Se utiliza `console.log()` en lugar de `print()`.
- Es habitual terminar las instrucciones con punto y coma `;`.

## 4. ¿Qué parte de la lógica se mantiene igual?

La lógica de los condicionales es la misma en ambos lenguajes.

Se evalúa una condición y, si es verdadera, se ejecuta un bloque de código. Si es falsa, se comprueban las siguientes condiciones o se ejecuta el bloque `else`.

En ambos lenguajes, las condiciones se evalúan en orden y se ejecuta únicamente el primer bloque cuya condición se cumple.

## Ejemplo práctico

El programa evalúa la nota de un examen y muestra si el resultado es sobresaliente, aprobado o suspenso.

```javascript
let nota = 8;

if (nota >= 9) {
    console.log("Sobresaliente");
} else if (nota >= 5) {
    console.log("Aprobado");
} else {
    console.log("Suspenso");
}
```

**Resultado:** `Aprobado`
