# clase-02

unidad 1: triángulos y circunferencias

jueves 23 marzo 2023, presencial

## repaso clase anterior

preguntas? dudas? comentarios?

## definición de un triángulo

un triángulo es una figura geométrica en 2 dimensiones, vive en un plano.

para construir un triángulo, necesitamos tres rectas en un plano con inclinación distintas. estas tres rectas se intersectan en 3 puntos, que definen al triángulo.

los ángulos interiores de un triángulo miden 180 grados.

los ángulos exteriores miden la diferencia entre 3 veces ángulos de 360 grados, menos los 180 grados.

notación:

- lados a, b, c
- ángulos interiores $\alpha, \beta, \gamma$

## triángulo rectángulo

es un triángulo que posee un ángulo recto (1/4 circunferencia, 90 grados, pi/2 radianes).

por definición, ningún triángulo puede tener dos ángulos rectos o mayores a 90 grados, ya que no existiría una manera de cerrar el triángulo.

teorema de pitágoras:

$$a^{2}  + b^{2} = c^{2}$$

en texto, la suma de los cuadrados de los catetos es igual al cuadrado de la hipotenusa. otra forma de verlo, es que si dibujamos los cuadrados correspondientes al lado de cada triángulo, la suma de las áreas de los cuadrados de los catetos es igual a la área asociada a la hipotenusa.

## teorema del coseno

el teorema de pitágoras es un caso particular del teorema del coseno con gamma = 90 grados.

$$a^{2}  + b^{2} = c^{2} + 2 \cdot a \cdot b \cdot cos(\gamma)$$

analicemos este teorema, partamos por el lado izquierdo de la igualdad. tomamos dos lados cualquiera (a y b), los elevamos al cuadrado y los sumamos, listo. al lado derecho de la ecuación tenemos el otro lado (c) al cuadrado más una multiplicación entre 2, los lados a y b, y el coseno del ángulo que forman estos lados ($\gamma$).

este teorema aplica para todos los ángulos y lados del triángulo, escribamos el teorema con ángulo $\alpha$:

$$b^{2}  + c^{2} = a^{2} + 2 \cdot b \cdot c \cdot cos(\alpha)$$

y escribamos el teorema con ángulo $\beta$:

$$a^{2}  + c^{2} = b^{2} + 2 \cdot a \cdot c \cdot cos(\beta)$$

## teorema del seno

$$\frac{a}{sin(\alpha)} = \frac{b}{sin(\beta)} = \frac{c}{sin(\gamma)}$$

## funciones trigonométricas

nemotecnia: SOHCAHTOA

$$sin(x) = \frac{cateto_{opuesto}}{hipotenusa}$$

$$cos(x) = \frac{cateto_{adyacente}}{hipotenusa}$$

$$tan(x) = \frac{cateto_{opuesto}}{cateto_{adyacente}}$$

## operador módulo

% es el operador módulo que usamos en programación.

% resulta en el resto de una división.

## sistemas de ecuaciones

si tenemos N incógnitas, necesitamos hacer un sistema de N ecuaciones para poder despejar estos valores.

podemos tomar las coordenadas de los puntos como la solución de un sistema de 3 ecuaciones, que busca los puntos donde pareas de 3 rectas se intersectan.

## sistema cartesiano

ejes XY:

- X es horizontal, crece hacia derecha
- Y es vertical, crece hacia arriba

viernes 24 marzo 2023, presencial

## definición de una circunferencia

una circunferencia es una figura geométrica en 2 dimensiones, vive en un plano.

la circunferencia es el lugar geométrico equidistante a un punto central.

## radio y diámetro

la distancia entre el centro y cualquier punto de la circunferencia es llamado radio, y lo anotamos como R.

el doble del radio, es llamado diámetro, y corresponde a la recta de mayor longitud que podemos dibujar dentro de una circunferencia.

## pi

pi $\pi$ es un número irracional, no se puede expresar como una división entre dos números enteros distintos de 1. tiene infinitos decimales.

pi es un número que ocurre naturalmente en las circunferencias, al dividir el perímetro de una circunferencia, por su diámetro, entonces, por definición:

$$\frac{perímetro}{diámetro} = \pi$$

algunos aproximaciones típicass de $\pi$ incluyen:

$$\pi \approx 3.14159$$

$$\pi \approx 3.1416$$

$$\pi \approx 3.14$$

$$\pi \approx 3$$

## perímetro de una circunferencia

de esta ecuación que acabamos de definir, podemos reescribir para definir el perímetro de una circunferencia en función de la constante $\pi$ y del radio.

$$perímetro = diámetro \cdot \pi$$

y como el diámetro es igual a dos veces el radio:

$$perímetro = 2 \cdot \pi \cdot R$$

## tau

tau $\tau$ es otra manera de describir la relación entre el perímetro de una circunferencia y su diámetro, donde $\tau$ es el doble de $\pi$.

$$perímetro = 2 \cdot \pi \cdot R$$

$$perímetro = \tau \cdot R$$

y si despejamos tau:

$$ \tau = \frac{perímetro}{R}$$

## coordenadas y circunferencias

si definimos el centro del origen cartesiano en el centro de la circunferencia, podemos describir cada punto de la circunferencia, según su coordenada XY, y también según el radio y el ángulo de inclinación, de la siguiente forma:

$$ x = R \cdot cos(\theta)$$

$$ y = R \cdot sin(\theta)$$

## valores notables de sin y cos

$$sin(0^{o}) = 0$$
