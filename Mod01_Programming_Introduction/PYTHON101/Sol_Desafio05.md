# Solución: Crear una calculadora sencilla

- 1 minuto

Este código es una posible solución al desafío de la unidad anterior.

PythonCopiar

```python
print('Simple calculator!')

first_number = input('First number? ')

if first_number.isnumeric() == False:
    print('Please input a number.')
    exit()

operation = input('Operation? ')

second_number = input('Second number? ')

if second_number.isnumeric() == False:
    print('Please input a number.')
    exit()

first_number = int(first_number)
second_number = int(second_number)

result = 0
if operation == '+':
    result = first_number + second_number
    label = 'sum'
elif operation == '-':
    result = first_number - second_number
    label = 'difference'
elif operation == '*':
    result = first_number * second_number
    label = 'product'
elif operation == '/':
    result = first_number / second_number
    label = 'quotient'
elif operation == '**':
    result = first_number ** second_number
    label = 'exponent'
elif operation == '%':
    result = first_number % second_number
    label = 'modulus'
else:
    print('Operation not recognized.')
    exit()

print(label + ' of ' + str(first_number) + ' ' + operation + ' ' + str(second_number) + ' equals ' + str(result))
```

Este código es simplemente *una posible solución*, porque no hemos especificado el nombre de las variables, el orden en el que se deben realizar las comprobaciones validadas y otros detalles de la implementación.

Puede considerar que lo ha superado si el programa es capaz de controlar todos los escenarios descritos en el desafío.

ResultadosCopiar

```output
First number? 4
Operation? *
Second number? 5
product of 4 * 5 equals 20
```

Si así es, enhorabuena. Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si le costó trabajo terminar el desafío, le recomendamos revisar las unidades anteriores antes de continuar. Todas las ideas nuevas que se abordan en los demás módulos dependen de su comprensión de las ideas presentadas en este.



## Comprobación de conocimientos

\1. 

¿Qué función debe usarse cuando quiere evaluar si un valor es de tipo cadena?



La función `isstring()`



La función `type()`



La función `instanceof()`

Cuando quiera evaluar si un valor es de un tipo determinado, elija `instanceof()`.



La función `isnumeric()`

\2. 

Quiere determinar si un número se divide a partes iguales en otro número. ¿Qué operador usaría?



El operador `/`



El operador `^`



El operador `&`



El operador `%`

Si el módulo es *0*, el divisor se divide a partes iguales en el dividendo.

\3. 

Supongamos que tiene un valor *1468* en una variable llamada `interest_rate` y quiere redondear a `1.5`. ¿Cómo llamaría al método `round()`?



```
round(interest_rate)
```



```
round(interest_rate, 0)
```



```
round(interest_rate, 1)
```

Correcto.



```
round(interest_rate, 2)
```

1 de 3 preguntas es incorrecta. Corrija la pregunta 1.