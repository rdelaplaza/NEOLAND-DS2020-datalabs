# Desafío: Adivinación de números mejorada

- 5 minutos

Amplíe el desafío anterior para incluir características adicionales, como sugerencias (demasiado bajo, demasiado alto) y comentarios (solo números).

### Paso 1: Agregar un nuevo archivo de código al directorio de trabajo

Suponiendo que continúa desde la unidad anterior, use las técnicas que ha aprendido en los módulos anteriores para agregar un nuevo archivo de código en la carpeta actual dedicada a este módulo. Por ejemplo, puede crear un archivo denominado `challenge2.py`.

### Paso 2: Escribir el código para implementar un juego de adivinación de números mejorado

Recompile el juego de adivinación de números, pero esta vez:

- Muestre el número del intento actual.
- Si el número propuesto es demasiado bajo, indíquele al usuario "El número es demasiado bajo, vuelva a intentarlo".
- Si el número propuesto es demasiado alto, indíquele al usuario "El número es demasiado alto, vuelva a intentarlo".
- Si el usuario escribe un valor no numérico, indíquele al usuario "Introduzca solo números".

Además, tome nota de la salida. Las solicitudes y los mensajes han cambiado en comparación con el desafío original.

Independientemente de cómo lo haga, el código debería producir una salida similar a la siguiente (debido a la respuesta y a las suposiciones generadas aleatoriamente):

ResultadosCopiar

```output
Guess a number between 1 and 10
Enter guess #1: 5
Your guess is too low, try again!
Enter guess #2: 8
Your guess is too high, try again!
Enter guess #3: 7
Your guess is too high, try again!
Enter guess #4: 6
You guessed it in 4 tries!
```

Si el usuario escribe un valor que no es numérico, muestre un mensaje de error. En la siguiente salida de ejemplo, el usuario escribe algunas cadenas y se le recuerda que solo debe introducir números.

ResultadosCopiar

```output
Guess a number between 1 and 10
Enter guess #1: Bob
Numbers only, please!
Enter guess #2: Beth
Numbers only, please!
Enter guess #3: 5
You guessed it in 3 tries!
```

Tanto si tiene dificultades y necesita echar un vistazo a la solución como si finaliza el ejercicio correctamente, continúe para ver una solución a este desafío.