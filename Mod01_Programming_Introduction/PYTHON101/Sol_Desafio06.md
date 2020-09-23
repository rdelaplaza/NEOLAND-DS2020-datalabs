# Solución: Adivinación de números

- 1 minuto

El código siguiente es una posible solución para el desafío de la unidad anterior.

PythonCopiar

```python
import random

value = random.randint(1, 5)
count = 0
guess = 0
while guess != value:
    count += 1
    guess = input('Guess a number between 1 and 5: ')
    if guess.isnumeric():
        guess = int(guess)
else:
    print(f'You guessed it in {count} tries!')
```

Este código no es más que *una posible solución*. Si la solución genera el mismo resultado que el desafío al usar la instrucción `while`, lo ha hecho correctamente.

Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si ha tenido problemas para realizar este desafío, quizás deba revisar las unidades anteriores antes de continuar. Todas las ideas nuevas que se abordan en los demás módulos dependen de su comprensión de las ideas presentadas en este.

