# Solución: Ejecución de código de bifurcación en función de datos proporcionados por el usuario

- 2 minutos

El código siguiente es una posible solución para el desafío de la unidad anterior.

PythonCopiar

```python
value = input('Would you like to continue? ')

if value == 'y' or value == 'yes':
    print('Continuing ...')
    print('Complete!')
elif value == 'n' or value == 'no':
    print('Exiting')
else:
    print('Please try again and respond with yes or no.')
```

Este código solo tiene *una solución posible* porque no se ha especificado que tuviera que usar los operadores lógicos. Podría haber resuelto este desafío mediante el uso de instrucciones if anidadas en su lugar. O bien, podría haber comprobado el escenario "no" antes del escenario "yes". Es posible que haya seleccionado un nombre de variable diferente para almacenar la entrada del usuario.

Si su salida coincide con la salida esperada en el desafío, lo ha realizado correctamente.

Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si ha tenido problemas para realizar este desafío, quizás deba revisar las unidades anteriores antes de continuar. Todas las ideas nuevas que se abordan en los demás módulos dependen de su comprensión de las ideas presentadas en este.

