# Solución: Adivinación de números mejorada

- 1 minuto

El código siguiente es una posible solución para el desafío de la unidad anterior.

PythonCopiar

```python
import random

value = random.randint(1, 10)
count = 0
guess = 0
print('Guess a number between 1 and 10')

while guess != value:
    count += 1
    guess = input(f'Enter guess #{count}: ')

    if guess.isnumeric():
        guess = int(guess)
    else:
        print('Numbers only, please!')
        continue

    if guess > value:
        print('Your guess is too high, try again!')
    elif guess < value:
        print('Your guess is too low, try again!')

else:
    print(f'You guessed it in {count} tries!')
```

Este código no es más que *una posible solución*. Debe haber usado la instrucción `while` para recorrer en bucle la lógica del juego y la instrucción `continue` para cuando el usuario no escribe un valor numérico.

Además, debe haber hecho un seguimiento de los intentos y haber mostrado el intento actual. Debe haber proporcionado sugerencias útiles como "demasiado alto" y "demasiado bajo" cuando la suposición del usuario es incorrecta.

ResultadosCopiar

```output
Guess a number between 1 and 10
Enter guess #1: 5
Your guess is too high, try again!
Enter guess #2: 3
Your guess is too high, try again!
Enter guess #3: bob
Numbers only, please!
Enter guess #4: 2
You guessed it in 4 tries!
```

Si ha sido así, enhorabuena. Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si ha tenido problemas para realizar este desafío, quizás deba revisar las unidades anteriores antes de continuar. Todas las ideas nuevas que se abordan en los demás módulos dependen de su comprensión de las ideas presentadas en este.



## Comprobación de conocimientos

\1. 

¿Cuándo se usa la instrucción `while`?



Cuando se necesita recorrer en iteración un bloque de código hasta que una condición deje de ser `True`.

Correcto.



Cuando se necesita recorrer en iteración un bloque de código hasta que una condición es `True`.



Cuando se necesita crear una ramificación del código.



Cuando se necesita llamar a una subrutina.

\2. 

¿Qué instrucción se debe usar para cuando la expresión booleana `while` ya no sea `True`?



La instrucción `break`.



La instrucción `else`.

La instrucción `else` se ejecutará cuando la expresión booleana `while` deje de ser `True`.



La instrucción `continue`.



goto

\3. 

¿Cuál de los siguientes operadores de asignación realizará una operación de multiplicación y asignación?



x=



^=



$=



*=

Correcto.

