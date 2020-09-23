# Solución

- 1 minuto

El código siguiente es una posible solución para el desafío de la unidad anterior.

PythonCopiar

```python
print("Today's date?")
date = input()
print("Breakfast calories?")
breakfast = int(input())
print("Lunch calories?")
lunch = int(input())
print("Dinner calories?")
dinner = int(input())
print("Snack calories?")
snack = int(input())
total = breakfast + lunch + dinner + snack
print("Calorie content for " + date + ": " + str(total))
```

Este código no es más que *una posible solución*. Es posible que haya elegido nombres de variable diferentes o que haya intentado realizar la operación de suma en la última línea del código. Pero debería haber usado variables, la función `print()`, la función `input()`, la concatenación de cadenas, la suma, etc., para generar el resultado deseado.

Una vez más, la salida real podría ser diferente, en función de los valores especificados en cada solicitud.

ResultadosCopiar

```output
Today's date?
December 7th, 2020
Breakfast calories?
250
Lunch calories?
300
Dinner calories?
500
Snack calories?
150
Calorie content for December 7th, 2020: 1200
```

Si ha sido así, enhorabuena. Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si tiene problemas para completar este desafío, podría ser una buena idea revisar las unidades anteriores de este módulo antes de continuar. Las ideas nuevas que se abordarán en los siguientes módulos dependen de su comprensión de las ideas presentadas hasta ahora.