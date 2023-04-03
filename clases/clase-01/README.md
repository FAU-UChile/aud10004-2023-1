# clase-01

unidad 0: números y ángulos

jueves 16 marzo 2023, presencial

## presentación docentes

- aarón montoya-moraga (elle) https://montoyamoraga.io/ https://github.com/montoyamoraga/
- ingeniería eléctrica UC https://www.ing.uc.cl/
- NYU ITP https://tisch.nyu.edu/itp
- Processing https://processing.org/
- p5.js https://p5js.org/
- School of machines https://www.schoolofma.org/
- Opera of the future https://www.media.mit.edu/groups/opera-of-the-future/
- Future sketches https://www.media.mit.edu/groups/future-sketches/
- Diseño UChile https://fau.uchile.cl/
- Diseño UDP https://diseno.udp.cl/
- Sinestesia https://www.sinestesia.cc/

- ignacio passalacqua (él)
- ingeniería eléctrica UC https://www.ing.uc.cl/

## inspiraciones varias

- Ada Lovelace https://es.wikipedia.org/wiki/Ada_Lovelace
- Andreas Refsgaard https://andreasrefsgaard.dk/
- Ciat-Lonbarde https://www.ciat-lonbarde.net/
- Constanza Piña https://es.wikipedia.org/wiki/Constanza_Pi%C3%B1a
- CW&T https://cwandt.com/
- Delight Lab https://www.instagram.com/delight_lab_oficial/
- Gaurav Patekar https://www.gauravpatekar.in/
- Katya Rozanova https://www.katyarozanova.com/
- Leo Fender https://es.wikipedia.org/wiki/Leo_Fender
- Limor Fried https://es.wikipedia.org/wiki/Limor_Fried
- Lisa Jamhoury https://lisajamhoury.com/
- Nicole L'Huillier https://nicolelhuillier.com/
- Rafael Benguria https://es.wikipedia.org/wiki/Rafael_Benguria
- Rhizomatiks Research https://research.rhizomatiks.com/
- Robert Moog https://es.wikipedia.org/wiki/Robert_Moog
- Schorr Guitars http://schorrguitars.de/

## preguntas para estudiantes:

30 segundos:

- por qué entraste a diseño?
- qué fue lo más emocionante que aprendiste el año pasado?
- y lo más difícil?
- qué quieres aprender este semestre?
- preguntas? comentarios?

## conjuntos numéricos

los números naturales son 1, 2, 3, ..., +infinito

los números enteros son -infinito, ... , -3, -2, -1, 0, 1, 2, 3, ..., +infinito

los números reales son los que tienen valores decimales, tanto los que se pueden escribir como fracción que son llamados (racionales), como los que no pueden ser escritos como fracción como PI que reciben el nombre de irracionales.

## infinitos

los números naturales son infinitos.

los números enteros también son infinitos, y nuestra primera impresión podría ser que son aún más infinitos que los naturales, pero pdemos asignar un número natural a cada número entero, y con eso, podemos contarlos y equipararlos, son igual de infinitos!

si analizamos los números reales, por ejemplo entre dos números enteros consecutivos 0 y 1, existen infinitos números reales entre 0 y 1, y eso es para cada par consecutivo de números enteros! por lo tanto no podemos asignar un número entero a cada número real, entre dos números reales siempre podemos encontrar infinitos números reales. con esto el infinito de los números reales es más infinito que el infinito de los enteros.

viernes 17 marzo 2023, presencial

## sistemas numéricos

los números romanos no tienen ni cero ni decimales. tienen distintos símbolos y maneras de combinarlos para representar cantidades, por ejemplo:

- I = uno
- II = dos
- III = tres
- IV = cuatro
- V = cinco
- VI = seis
- ...
- XII = doce
- ...
- XXVI = veintiseis
- ...
- LII = cincuenta y dos
- ...

hay solamente una manera de escribir cada número, siguiendo reglas específicas para escribir cada cifra.

los números arábigos que usamos en "Occidente", son diez símbolos que combinamos para escribir cualquier cifra: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. una gracia de estos números es que la distancia entre cada cifra es la misma. son diez símbolos porque tenemos 10 dedos. existen otros sistemas donde se usan las tres falanges de cada dedo no-pulgar, y con eso tenemos 12 unidades por mano.

si analizamos el número 5781.2, podemos verlo como

$$5 \cdot 10^{3} + 7 \cdot 10^{2} + 8 \cdot 10^{1} + 1 \cdot 10^{0} + 2 \cdot 10^{-1}$$

imaginemos que empezamos contando desde 0, aumentamos de 1 en 1, cuando llegamos al 9 no quedan símbolos que podamos usar. para anotar el número siguiente a 9, como no hay espacio, volvemos esta cifra de unidades a cero, y aumentamos en 1 la siguiente posición de las decenas, resultando en el número 10. luego podemos mantener la cifra 1 de las decenas, e ir aumentando la cifra de las unidades, obteniendo 11, 12, 13, ..., 17, 18, 19. después de 19 una vez más tenemos el mismo problema, que 9 es el valor más grande posible de una cifra, así que para seguir avanzando, aumentamos en 1 de nuevo las decenas y así llegamos al número 20. etc...

cuando superamos el número máximo (9) que podemos anotar en las unidades, debemos aumentar las decenas. cuando llegamos al número máximo en las decenas, empezamos a aumentar las centenas, y así.

en un computador, usamos un sistema binario, donde hay dos símbolos 0 y 1, para representar las metáforas encendido/apagado, sí/no, presencia/ausencia.

si contamos de 0 a 8 en binario es:

- 0000 = cero
- 0001 = uno
- 0010 = dos
- 0011 = tres
- 0100 = cuatro
- 0101 = cinco
- 0110 = seis
- 0111 = siete
- 1000 = ocho

otro sistema que se usa en computación es el sistema hexadecimal, que tiene 16 símbolos:

- 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

este sistema es comúnmente usado en diseño para representar colores RGB en sistemas computacionales, por ejemplo: FF, A8, 7C.

## ángulos

los ángulos nos permiten describir rotaciones, inclinaciones y movimientos circulares.

comúnmente se usan letras griegas para denotar ángulos, como alpha, beta, gamma ($\alpha, \beta, \gamma$)

en geometría en este curso usaremos dos maneras de medir ángulos:

- en grados, donde una circurferencia completa equivale a 360 grados y un ángulo recto a 90 grados.
- en radianes, donde una circunferencia completa equivale a $2 \cdot \pi$ radianes y un ángulo recto a $\frac{\pi}{2}$ radianes.

para hacer conversiones entre ángulos, podemos usar la siguiente igualdad:

$$\frac{2 \cdot \pi \cdot radianes}{360 \cdot grados} = \frac{X \cdot radianes}{Y \cdot grados}$$

basta con tener X en radianes o Y en grados, para lograr despejar el otro valor.

por ejemplo, si queremos saber el equivalente en radianes de 45 grados, escribimos:

$$\frac{2 \cdot \pi \cdot radianes}{360 \cdot grados} = \frac{X \cdot radianes}{45 \cdot grados}$$

podemos dividir por radianes a ambos lados de la ecuación:

$$\frac{2 \cdot \pi}{360 \cdot grados} = \frac{X}{45 \cdot grados}$$

podemos multiplicar por grados a ambos lados de la ecuación:

$$\frac{2 \cdot \pi}{360} = \frac{X}{45}$$

podemos multiplicar por 45 a ambos lados:

$$\frac{2 \cdot 45 \cdot \pi}{360} = X$$

y ahora podemos expresar X así:

$$X = \frac{2 \cdot 45 \cdot \pi}{360}$$

y simplificar:

$$X = \frac{90 \cdot \pi}{360} = \frac{\pi}{4}$$

y así sabemos que 45 grados es equivalente a $\frac{\pi}{4}$ radianes.
