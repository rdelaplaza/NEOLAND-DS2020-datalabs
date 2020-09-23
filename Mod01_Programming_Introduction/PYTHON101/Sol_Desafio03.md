# Solución: manipular las cadenas y darles formato

- 1 minuto

El código siguiente es una posible solución para el desafío de la unidad anterior.

PythonCopiar

```python
first_value = '  FIRST challenge         '
second_value = '-  second challenge  -'
third_value = 'tH IR D-C HALLE NGE'

fourth_value = 'fourth'
fifth_value = 'fifth'
sixth_value = 'sixth'

# First challenge
first_value = first_value.strip()
first_value = first_value.lower()
first_value = first_value.title()
first_value = f'{first_value:^30}'

# Second challenge
second_value = second_value.replace('-', '')
second_value = second_value.strip()
second_value = second_value.capitalize()

# Third challenge
third_value = third_value.replace(' ', '')
third_value = third_value.replace('-', ' ')
third_value = third_value.swapcase()
third_value = f'{third_value:>30}'

print(first_value)
print(second_value)
print(third_value)

# Fourth challenge - use only the print() function (no f-strings)
print(fourth_value, fifth_value, sixth_value, sep='#', end='!')

# Fifth challenge - use only a single print() function.  Create tabs and new lines using f-strings.
print(f'\n\t{fourth_value}\n\t{fifth_value}\n\t{sixth_value}')
```

Si código genera el resultado siguiente, la tarea habrá sido correcta.

ResultadosCopiar

```output
       First Challenge        
Second challenge
               Third challenge
fourth#fifth#sixth!
        fourth
        fifth
        sixth
```

Independientemente de si ha usado la solución que se muestra aquí, si obtiene el resultado que quiere, lo ha hecho correctamente. Ahora puede ir a la prueba de conocimientos de la unidad siguiente.

 Importante

Si ha tenido problemas para realizar este desafío, quizás deba revisar las unidades anteriores antes de continuar. Todas las ideas nuevas que se analizarán en el resto de módulos dependerán de que comprenda las ideas presentadas en este.



