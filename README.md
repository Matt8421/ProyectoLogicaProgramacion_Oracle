# JS Game

Este es un juego simple desarrollado con HTML, CSS y JavaScript donde el usuario intenta adivinar un número.

## Descripción

El juego consiste en que el usuario ingrese un número del 1 al 10 y verifique si es el número correcto. Si no lo es, puede seguir intentando hasta que lo adivine. Una vez que el número es adivinado correctamente, el usuario puede iniciar un nuevo juego.

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript

## Lógica del Juego

1. **Generación del Número Secreto**:
    - Al iniciar el juego, se genera un número aleatorio entre 1 y 10 que el usuario debe adivinar.
    - Se asegura que el número generado no haya sido usado anteriormente en el juego actual.

2. **Verificación del Intento**:
    - El usuario ingresa un número y hace clic en "Intentar".
    - Si el número es correcto, se muestra un mensaje de éxito y se habilita el botón para iniciar un nuevo juego.
    - Si el número es incorrecto, se proporciona una pista indicando si el número secreto es mayor o menor que el número ingresado.

3. **Reinicio del Juego**:
    - Al hacer clic en "Nuevo juego", se reinician las condiciones iniciales, generando un nuevo número secreto y deshabilitando el botón de reinicio hasta que se adivine el nuevo número.
