Distribuciones de probabilidad
==============================

#### Finalidad :

Abstraer matemáticamente un tipo de experimento aleatorio. Y, con ello,
poder estimar de manera teórica lo que sucedería de manera experimental
mediante una estadística

#### ¿Cómo?:

Mediante variables aleatorias y distribuciones de probabilidad asociadas
a esas variables

Variables aleatorias
--------------------

Una variable aleatoria es una función que a cada suceso elemental de un
espacio muestral le asigna un número. Para hacer referencia a las
variables se usan las letras: *X*, *Y*, ...

#### Ejemplo:

Sea el experimento aleatorio “lanzar un dado”: El espacio muestral lo
componen las 6 caras del dado. Podemos asignar la variable *X* que a
cada cara le asocia el número que represente su cara.

<table>
<tbody>
<tr class="odd">
<td style="text-align: center;"></td>
<td style="text-align: center;"><span class="math inline"><em>X</em></span></td>
<td style="text-align: center;"></td>
</tr>
<tr class="even">
<td style="text-align: center;">Suceso</td>
<td style="text-align: center;"></td>
<td style="text-align: center;"><span class="math inline"><em>x</em><sub><em>i</em></sub></span></td>
</tr>
<tr class="odd">
<td style="text-align: center;">Cara 1</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">1</td>
</tr>
<tr class="even">
<td style="text-align: center;">Cara 2</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">2</td>
</tr>
<tr class="odd">
<td style="text-align: center;">Cara 3</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">3</td>
</tr>
<tr class="even">
<td style="text-align: center;">Cara 4</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">4</td>
</tr>
<tr class="odd">
<td style="text-align: center;">Cara 5</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">5</td>
</tr>
<tr class="even">
<td style="text-align: center;">Cara 6</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">6</td>
</tr>
</tbody>
</table>

#### Ejemplo:

Sea el experimento compuesto lanzar dos monedas. Podemos asignar la
variable aleatoria:
*Y* = {*N**ú**m**e**r**o* *d**e* *c**a**r**a**s*}

<table>
<tbody>
<tr class="odd">
<td style="text-align: center;"></td>
<td style="text-align: center;"><span class="math inline"><em>Y</em></span></td>
<td style="text-align: center;"></td>
</tr>
<tr class="even">
<td style="text-align: center;">Suceso</td>
<td style="text-align: center;"></td>
<td style="text-align: center;"><span class="math inline"><em>y</em><sub><em>i</em></sub></span></td>
</tr>
<tr class="odd">
<td style="text-align: center;">C,C</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">2</td>
</tr>
<tr class="even">
<td style="text-align: center;">C,X</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">1</td>
</tr>
<tr class="odd">
<td style="text-align: center;">X,C</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">1</td>
</tr>
<tr class="even">
<td style="text-align: center;">X,X</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;">0</td>
</tr>
</tbody>
</table>

### Tipos de variables aleatorias

Discretas:  
Toman un número finito o numerable de valores

Continuas:  
Toman valores en un rango continuo

#### Ejemplo de variables discreta:

Sea la *X =“El número de caras al lanzar dos dados”*. Los valores
posibles son 0, 1 o 2 (que es un conjunto finito de datos, en concreto 3
datos)

#### Ejemplo de variables continua:

*X = “Distancia al centro de la diana medida desde la posición en que
cae un dardo lanzado por un tirador experto”* . En este caso la variable
puede tomar cualquier valor en el rango entre 0 y el radio de la diana

Distribuciones de probabilidad
------------------------------

Llamaremos Distribución de probabilidad a la relación entre los valores
de la variable y sus probabilidades.

Estas relaciones se pueden indicar mediante funciones. El tratamiento de
estas funciones es diferente según las variables sean discretas o
continuas.

#### Ejemplo: 

Sea la variable *X = “Número obtenido al lanzar una dado”*  
A cada valor de la variable podemos asignarle su probabilidad:

<table>
<tbody>
<tr class="odd">
<td style="text-align: center;"></td>
<td style="text-align: center;"><span class="math inline"><em>P</em>(<em>X</em>)</span></td>
<td style="text-align: center;"></td>
</tr>
<tr class="even">
<td style="text-align: center;"><span class="math inline"><em>x</em><sub><em>i</em></sub></span></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"><span class="math inline"><em>P</em>(<em>x</em><sub><em>i</em></sub>)</span></td>
</tr>
<tr class="odd">
<td style="text-align: center;">1</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;"><span class="math inline">$\tfrac{1}{6}$</span></td>
</tr>
<tr class="even">
<td style="text-align: center;">2</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;"><span class="math inline">$\tfrac{1}{6}$</span></td>
</tr>
<tr class="odd">
<td style="text-align: center;">3</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;"><span class="math inline">$\tfrac{1}{6}$</span></td>
</tr>
<tr class="even">
<td style="text-align: center;">4</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;"><span class="math inline">$\tfrac{1}{6}$</span></td>
</tr>
<tr class="odd">
<td style="text-align: center;">5</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;"><span class="math inline">$\tfrac{1}{6}$</span></td>
</tr>
<tr class="even">
<td style="text-align: center;">6</td>
<td style="text-align: center;"><span class="math inline">→</span></td>
<td style="text-align: center;"><span class="math inline">$\tfrac{1}{6}$</span></td>
</tr>
</tbody>
</table>
