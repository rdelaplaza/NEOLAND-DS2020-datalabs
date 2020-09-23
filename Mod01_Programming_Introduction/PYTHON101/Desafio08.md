# Desafío: reparto de una mano de cartas de una baraja

- 5 minutos

En estos módulos de aprendizaje, los desafíos de codificación como este reforzarán lo que ha aprendido y le ayudarán a tener más confianza antes de continuar.

## Paso 1: adición de un nuevo archivo para este desafío

Use las técnicas que ha aprendido en módulos anteriores para agregar un nuevo archivo de código. Agréguelo a la carpeta dedicada a este módulo. Por ejemplo, puede crear un archivo denominado *challenge1.py*.

## Paso 2: creación de una lista para una baraja de cartas estándar

Use la técnica de la unidad anterior para enumerar cada combinación de palo y número en un conjunto de 52 cartas. En lugar de simplemente imprimir el valor de la carta, agréguela a una lista que represente una baraja.

Cuando termine, muestre el número de cartas de la baraja mediante la función que proporciona un recuento de los elementos de la lista.

ResultadosCopiar

```output
There are 52 cards in the deck.
```

## Paso 3: selección aleatoria de cinco cartas para agregarlas a la mano de un jugador

Después, cree una segunda lista para los resultados de repartir una mano de cartas. Para simular que se reparten cinco cartas aleatorias, use el método adecuado para elegir una carta. Agregue la carta a la lista que representa la mano del jugador. Quite la carta de la lista que representa la baraja.

Antes de simular el reparto de cartas, imprima este mensaje:

ResultadosCopiar

```output
Dealing ...
```

Después de simular el reparto, imprima el número de cartas de la lista que representa la baraja. Por último, imprima las cartas de la mano del jugador.

Cuando haya completado el proceso, debería ver algo similar a la salida siguiente. La salida será diferente porque las cartas se reparten de forma aleatoria.

ResultadosCopiar

```output
There are 52 cards in the deck.
Dealing ...
There are 47 cards in the deck.
Player has the following cards in their hand:
['Jack of Hearts', 'Queen of Hearts', '4 of Spades', 'Ace of Hearts', '9 of Diamonds']
```

Tanto si finaliza el ejercicio correctamente como si tiene dificultades y necesita echar un vistazo a la solución, continúe para ver una solución a este desafío.