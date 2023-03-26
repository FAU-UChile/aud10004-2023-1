# ayudantia-03

martes 28 marzo 2023

## resumen de fórmulas

## ejercicio-01: diseñando una mesa redonda

quiero diseñar una mesa redonda para 6 personas. estimo que una persona ocupa un espacio de al menos $80(cm)$

- ¿cuál es el perímetro que debe tener la mesa para albergar 6 personas?
- ¿qué radio y diámetro debe tener?
- quiero pintar cada sector individual de la mesa con colores distintos ¿qué ángulo debo formar para dividir la mesa en 6 partes iguales?

<details>
<summary>--- solución ---</summary>

el perímetro sería 6 veces el espacio estimado por persona:

$$p = 6 \cdot 80(cm) = 480(cm) = 4.8(m)$$

el radio lo podemos calcular usando la relación fundamental de $\pi$:

$$\pi = \frac{perímetro}{diámetro} = \frac{p}{2r}$$

$$\therefore \ p = 2 \pi r$$

en el punto anterior calculamos que $p=480(cm)$, por lo que podemos calcular el radio:

$$r=\frac{p}{2\pi}=\frac{480(cm)}{2\pi} \approx 76.4(cm)$$

el diámetro es el doble del radio:

$$d=2r \approx 2\cdot 76.4(cm) \approx 152.8(cm)$$

si se quiere dividir la mesa en 6 partes iguales, debemos dividir los $360°$ totales en 6.

$$ \alpha = 360°/6 = 60° $$

por lo que es necesario que dibujar ángulos de 60° grados.

</details>

## ejercicio-02: diseñando una rampa

necesito construir una rampa provisoria para poder llevar a un amigo que usa silla de ruedas hacia adentro de mi casa. compraré una madera gruesa para hacer la rampa.

mi amigo me dice que las rampas no deben tener más de $10°$ de inclinación, si no, pueden ser peligrosas.

la entrada de mi casa tiene una altura de 50 centrímetros. 

¿de qué largo debo comprar la madera para no sobrepasar los $10°$ de inclinación?

¿qué espacio del patio debo desocupar para poner la rampa?


<details>
<summary>--- solución ---</summary>

la rampa para entrar a la casa generará un triángulo rectángulo con uno de los lados de $50cm$ y un ángulo de $10°$.

usando la relación trigonométrica del seno del ángulo:

$$sin(x) = \frac{cateto_{opuesto}}{hipotenusa}$$

$$sin(x) = \frac{b}{c}$$

$$sin(10°) = \frac{50(cm)}{c}$$

$$c = \frac{50(cm)}{sin(10°)}$$

$$c \approx 287.94(cm)$$ 

$$c \approx 2.88(m) $$ 

por lo tanto debo comprar una madera de un largo mayor a $2.88(m)$ para no sobrepasar los $10°$ de inclinación.

--- OJO --- al usar la calculadora para obetener el valor de $sin(10°)$ es necesario asegurar que la calculadora esté en modo 'deg' (grados) y no en modo 'rad' (radianes).

para calcular el espacio del patio que debo desocupar para poner la rampa tenemos dos opciones:

opción 1: 

ya tenemos dos lados del triángulo así que es posible utlizar el teorema de pitágoras para calcular el lado que nos falta.

$$a^2+b^2=c^2$$

$$a = \sqrt{c^2-b^2}$$

$$a = \sqrt{287.94(cm)^2 - 50(cm)^2}$$

$$a \approx 283.56(cm)$$

$$a \approx 2.84(m)$$

opción 2: 

es posible utilizar la relación trigonométrica de la tangente del ángulo:

$$tan(x) = \frac{cateto_{opuesto}}{cateto_{adyacente}}$$

$$tan(x) = \frac{b}{a}$$

$$tan(10°) = \frac{50(cm)}{a}$$

$$a = \frac{50(cm)}{tan(10°)}$$

$$c \approx 283.56(cm)$$ 

$$c \approx 2.84(m) $$ 

</details>










