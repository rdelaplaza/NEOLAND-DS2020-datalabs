# Solución: reparto de una mano de cartas de una baraja

- 2 minutos

El código siguiente es una posible solución para el desafío de la unidad anterior.

PythonCopiar

```python
import random

suits = ["Hearts", "Spades", "Clubs", "Diamonds"]
ranks = ["2", "3", "4", "5", "6", "7", "8", "9", "10", "Jack", "Queen", "King", "Ace"]
deck = []

for  suit in suits:
  for rank in ranks:
    deck.append(f'{rank} of {suit}')

print(f'There are {len(deck)} cards in the deck.')

print('Dealing ...')

hand = []

while len(hand) < 5:
    card = random.choice(deck)
    deck.remove(card)
    hand.append(card)

print(f'There are {len(deck)} cards in the deck.')
print('Player has the following cards in their hand:')
print(hand)
```

Este código no es más que *una* posible solución. Si el resultado coincide con la salida y cada vez que ejecuta el programa se reparte al jugador un conjunto de cartas diferente, ha realizado el ejercicio correctamente.

Si es así, enhorabuena. Vaya a la prueba de conocimientos de la unidad siguiente.

 Importante

Si ha tenido problemas para realizar este desafío, quizás deba revisar las unidades anteriores antes de continuar. Para comprender las ideas que analizamos en módulos posteriores, debe comprender los conceptos de este módulo.



## Comprobación de conocimientos

\1. 

Tiene una lista de cinco elementos y quiere recuperar los tres últimos elementos. ¿Qué herramienta segmento usar?



```
my_list[1:4]
```



```
my_list[:2]
```



```
my_list[:-3]
```



```
my_list[-3:]
```

Correcto.

\2. 

¿Cuál de las siguientes funciones auxiliares puede usar para que la lista simule una cola?



```
remove()
```



```
pop()
```

La función `pop()` selecciona y quita un elemento de una lista. Este comportamiento es similar al funcionamiento de una cola.



```
del()
```



```
clear()
```

\3. 

¿Cuál es la forma más sencilla de averiguar si un valor pertenece a una lista?



Usar la función auxiliar `find()`.



Usar el operador `in`.

Correcto.



Usar el operador `is`.



Usar la función auxiliar `contains()`.