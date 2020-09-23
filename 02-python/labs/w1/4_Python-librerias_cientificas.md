# Librerías científicas Python

## Objetivos
El objetivo de esta unidad será presentar las librerías científicas en Python más utilizadas por la comunidad, así como ejemplos de su uso.

2. Introducción
Desde su nacimiento, y más concretamente desde la rama de desarrollo 2.x, Python ha contado con el desarrollo de muchas librerías para el uso de la comunidad científica. En esta unidad vamos a presentar las más importantes desde el punto de vista de la ciencia de los datos en general y vamos a dejar para unidades posteriores el uso de otras librerías más específicas. Podéis consultar en la wiki oficial de Python una lista más exhaustiva de [librerías numéricas y científicas(https://wiki.python.org/moin/NumericAndScientific)].

2.1 NumPy
[NumPy](http://www.numpy.org/) nació con el nombre de [Numeric](https://wiki.python.org/moin/NumPy?action=show&redirect=Numeric) y, poco a poco, fue centralizando muchos otros desarrollos de otros autores (como [NumArray](https://wiki.python.org/moin/NumArray)) para acabar siendo la librería que hoy día conocemos como NumPy. En la actualidad NumPy está integrada en la [SciPy](http://www.scipy.org/install.html) stack aunque continúa siendo un paquete independiente de SciPy (más tarde hablaremos de este paquete).

NumPy es una librería de cálculo matricial en origen, aunque hoy en día implementa muchas otras funcionalidades interesantes como son herramientas para integrar código C/C++ y Fortran, funciones de álgebra lineal, transformaciones de Fourier, etc.

2.2 Matplotlib
[Matplotlib](http://matplotlib.org/) es una librería de representación de datos en 2D muy utilizada por la comunidad dada la gran calidad de las figuras generadas y por su capacidad de representación de datos de distinta índole. Un vistazo rápido a la [galería de ejemplos](http://matplotlib.org/gallery.html) nos convencerá de su gran potencia.

Esta librería puede ser utilizada mediante la interfaz Pyplot, que se integra muy bien con IPython y Notebook y tiene una sintaxis muy similar a [MATLAB](http://es.mathworks.com/products/matlab/), o bien con los objetos que proporciona la librería para utilizar toda su capacidad de personalización de dibujo.

Esa similitud con MATLAB ha ayudado a su diseminación, debido a que muchos usuarios científicos buscaban una alternativa de código abierto frente a MATLAB y que pudiera ser integrada con otras librerías en Python.

2.3 SciPy
[SciPy](http://www.scipy.org/) es una librería muy importante para la comunidad científica en Python. Como apuntábamos antes, ha ido incluyendo poco a poco otros paquetes importantes como NumPy, [SymPy](http://www.sympy.org/en/index.html), Matplotlib o el propio IPython en lo que se conoce como SciPy stack, o la pila de desarrollo de herramientas científicas en Python. La clara ventaja de integrar los diferentes paquetes en una librería es diseñar una interfaz común que permita la comunicación entre distintas librerías de desarrollo. Por ejemplo, imaginemos que queremos representar datos de forma matricial (usaremos NumPy para ello), que queremos calcular distancias (usaremos algoritmos incluidos en SciPy) y finalmente queremos representar esos resultados (Matplotlib fue diseñado para ello). Con tan solo tres líneas al principio de nuestro código, tendremos toda la potencia de estas librerías y los datos que manejen serán compatibles entre ellas.

Por último, el paquete principal de SciPy es la [SciPy library](http://www.scipy.org/scipylib/index.html).

2.4 Pandas
Pandas es una librería de Python que nos ofrece una interfaz de alto nivel para manipular y analizar datos. La librería ofrece estructuras de datos flexibles sobre las que cargar los datos e implementa operaciones sobre estas estructuras que resultan muy intuitivas de usar y, a la vez, son eficientes. Por este motivo, es una de las herramientas más utilizadas en el análisis de datos en Python. Pandas también forma parte del SciPy stack.

Como veremos más adelante, la estructura de datos principal de Pandas es el dataframe, una estructura que permite almacenar tablas bidimensionales.

3. Bibliografía
Tutorial de NumPy: https://docs.scipy.org/doc/numpy/user/quickstart.html
100 ejercicios resueltos de NumPy: http://www.labri.fr/perso/nrougier/teaching/numpy.100/
Pandas Tutorial: DataFrames in Python: https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python
Pandas cookbook: http://nbviewer.jupyter.org/github/jvns/pandas-cookbook/tree/v0.1/cookbook/
