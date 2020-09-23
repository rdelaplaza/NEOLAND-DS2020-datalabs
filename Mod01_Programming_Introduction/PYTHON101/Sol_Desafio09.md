# Soluciones: Relleno de las funciones que faltan

- 2 minutos

El código siguiente es una solución posible para el desafío de la unidad anterior.

En primer lugar, cree un código nuevo denominado processor.py en la misma carpeta de trabajo.

Luego cree las dos funciones siguientes en ese archivo:

PythonCopiar

```python
def process_numbers(unprocessed_list):
    
    processed_list = []
    if isinstance(unprocessed_list, list) == False:
        return processed_list
    
    for item in unprocessed_list:
        if isinstance(item, int):
            processed_list.append(item)
        elif isinstance(item, str):
            if item.isnumeric():
                converted_item = int(item)
                processed_list.append(converted_item)
    
    processed_list.sort()
    return processed_list


def process_names(unprocessed_list):
    
    processed_list = []

    if isinstance(unprocessed_list, list) == False:
        return processed_list
    
    for item in unprocessed_list:
        if isinstance(item, str):
            if item.isnumeric() == False:
                processed_list.append(item)
    
    processed_list.sort()
    return processed_list
```

Ahora, al ejecutar el código en el archivo challenge.py, debería obtener la salida correcta.

Este código es simplemente *una solución posible* porque no hemos especificado detalles sobre la implementación de las funciones en el módulo `processor`. Siempre que las funciones `process_numbers()` y `process_names()` cumplan los requisitos de la unidad anterior, lo conseguirá.

Si ha sido así, enhorabuena. Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si ha tenido problemas para realizar este desafío, debería revisar las unidades anteriores antes de continuar. La comprensión de todas las ideas nuevas que se tratan en módulos posteriores está sujeta a que se hayan entendido las que se han explicado en este.



## Comprobación de conocimientos

\1. 

¿Cuál de las siguientes afirmaciones *no* es un buen motivo para crear una función?



Cuando se deba encapsular la función que se necesita a menudo en un solo lugar.



Cuando se necesite ayudar a partir un problema más grande en partes más pequeñas y fáciles de administrar.



Cuando se necesite compartir la funcionalidad entre uno o varios programas mediante la incorporación a un módulo.



Cuando se necesite almacenar información que se usará en todo el programa.

Esta respuesta es correcta. Almacenar información no es un buen motivo para crear una función.

\2. 

¿Cómo se puede hacer que un argumento de entrada sea opcional?



Con la incorporación de la palabra clave **requerido**.



Con el suministro de un valor predeterminado que se debe usar si el autor de la llamada no pasa un argumento.

Correcto.



Con el uso de argumentos de palabra clave.



Con la comprobación de su valor para ver si es igual que **None**.