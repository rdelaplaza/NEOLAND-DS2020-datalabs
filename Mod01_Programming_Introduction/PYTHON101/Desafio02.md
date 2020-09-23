# Desafío: Ejecución de código de bifurcación en función de datos proporcionados por el usuario

- 5 minutos

Los desafíos de codificación de estos módulos reforzarán lo que ha aprendido y le ayudarán a tener más confianza antes de continuar.

### Paso 1: Agregar un archivo nuevo

Cree un archivo de código nuevo para este desafío. Por ejemplo, puede crear un archivo denominado `challenge.py`.

### Paso 2: Escribir código en el archivo nuevo para resolver el desafío

Escriba un programa corto que imprima un mensaje entre varios al usuario en función de su entrada.

En primer lugar, pregunte al usuario si quiere continuar o no.

Si el usuario responde con `no` o `n`, imprima la frase `Exiting`.

Obtenga la salida siguiente en este escenario de `no`. El usuario ha especificado `no` cuando se le solicitó.

ResultadosCopiar

```output
Would you like to continue? no
Exiting
```

Si el usuario responde con `yes` o `y`, imprima la frase `Continuing ...` y `Complete!`.

Obtenga la salida siguiente en este escenario de `yes`. El usuario ha especificado `yes` cuando se le solicitó.

ResultadosCopiar

```output
Would you like to continue? yes
Continuing ...
Complete!
```

Si el usuario responde con cualquier otra cosa, imprima la frase `Please try again and respond with yes or no.`.

Obtenga la salida siguiente en este último escenario. El usuario ha especificado `bob` cuando se le solicitó.

ResultadosCopiar

```output
Would you like to continue? bob 
Please try again and respond with yes or no.
```

Tanto si tiene dificultades y necesita echar un vistazo a la solución como si finaliza el ejercicio correctamente, continúe para ver una solución a este desafío.

## Comprobación de conocimientos

\1. 

¿Qué problema hay en la línea de código `if x == 3`?



Utiliza `==` en lugar de `=` para comprobar la igualdad.



Falta la palabra clave `then` al final.



Faltan los paréntesis que rodean la expresión booleana.



Falta `:` al final.

Las instrucciones if válidas deben terminar con un carácter de dos puntos.

\2. 

¿Cuál es el resultado de la siguiente expresión booleana cuando `x = 6`: `x > 3 or x < 5`?



```
True
```

Puesto que 6 es mayor que 3, esa parte de la expresión booleana completa es `True`. Por lo tanto, toda la expresión booleana será `True`, puesto que se usó un `or`.



```
False
```



Esta sintaxis no es correcta para una expresión booleana.

\3. 

¿Cuál es el resultado de la siguiente expresión booleana cuando `x = 6`: `not x`?



```
True
```



```
False
```

Dado que `bool(6)` se evalúa como `True`, al agregar el operador `not` se evaluaría como `False`.



Esta sintaxis no es correcta para una expresión booleana.