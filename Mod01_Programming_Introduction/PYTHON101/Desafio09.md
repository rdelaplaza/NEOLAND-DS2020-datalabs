# Desafío: Rellenar las funciones que faltan

- 8 minutos

Los desafíos de código de estos módulos reforzarán la información que se ha obtenido y ayudarán a tener más confianza antes de continuar.

En este desafío, se creará un módulo nuevo que contendrá funciones que permitan que el código proporcionado funcione según lo previsto.

### Paso 1: Crear un archivo de código nuevo para este desafío

Use las técnicas que se han aprendido en los módulos anteriores para agregar un nuevo archivo de código en la carpeta actual dedicada a este módulo. Asigne al archivo el nombre challenge.py.

### Paso 2: Copiar el código de inicio en el archivo nuevo

Copie el código siguiente en el archivo nuevo challenge.py:

PythonCopiar

```python
import processor

my_list = [5, 'Dan', '4', 7, 'Steve', 'Amy', 'Rhonda', 4, '9', 'Jill', 7, 'Kim']
my_bad_list = 5

numbers = processor.process_numbers(my_list)
print(numbers)

names = processor.process_names(my_list)
print(names)

numbers = processor.process_numbers(my_bad_list)
print(numbers)

names = processor.process_names(my_bad_list)
print(names)
```

### Paso 3: Asegurarse de seguir las reglas del desafío

Regla 1: no se puede modificar en absoluto el código del archivo challenge.py. En su lugar, cree un nuevo módulo denominado processor.py en la misma carpeta de trabajo.

Regla 2: cuando se termine, la ejecución del archivo challenge.py debe generar la salida siguiente:

ResultadosCopiar

```output
[4, 4, 5, 7, 7, 9]
['Amy', 'Dan', 'Jill', 'Kim', 'Rhonda', 'Steve']
[]
[]
```

Regla 3: la función `process_numbers()` debe seleccionar todos los valores numéricos, incluso los que son cadenas, y devolverlos como una lista. Los valores deben convertirse en números e incluirse en la lista devuelta. La lista debe estar ordenada. La función debe controlar la posibilidad de que el parámetro de entrada no tenga el formato de lista. En ese caso, debe devolver una lista vacía.

Regla 4: la función `process_names()` debe seleccionar todos los valores de cadena que no sean numéricos y devolverlos como una lista. La lista debe estar ordenada. La función debe controlar la posibilidad de que el parámetro de entrada no tenga el formato de lista. En ese caso, debe devolver una lista vacía.

Tanto si tiene dificultades y necesita echar un vistazo a la solución como si finaliza el ejercicio correctamente, continúe para ver una solución a este desafío.