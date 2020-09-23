# Solución: Convertir la temperatura de Fahrenheit a Celsius

- 1 minuto

Este código es una posible solución al desafío presentado en la unidad anterior.

PythonCopiar

```python
fahrenheit = input('What is the temperature in Fahrenheit?  ')

if fahrenheit.isnumeric() == False:
    print('Input is not a number.')
    exit()

fahrenheit = int(fahrenheit)

celsius = int((fahrenheit - 32) * 5/9)
print('Temperature in celsius is ' + str(celsius))
```

Este código solamente es *una posible solución*, porque no se ha especificado qué nombre tendrían las variables ni otros pequeños detalles de implementación.

Puede considerar que lo ha superado si el programa funciona en el mejor de los escenarios y es capaz de controlar el peor de los escenarios.

Si así es, enhorabuena. Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si le costó trabajo terminar el desafío, le recomendamos revisar las unidades anteriores antes de continuar. Todas las ideas nuevas que se abordan en los demás módulos dependen de su comprensión de las ideas presentadas en este.