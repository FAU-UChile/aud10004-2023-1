# control-01 pauta

martes 04 abril 2023

## ejercicio-01: números con base 10 y base 2 (3 puntos)

a) convierta el número binario $110110101_{(base2)}$ a su forma decimal (base 10).

$$110110101_{(base2)} \Rightarrow 1 \cdot 2^8 + 1 \cdot 2^7 + 1 \cdot 2^5 + 1 \cdot 2^4 + 1 \cdot 2^2 + 1 \cdot 2^0$$

$$= 256 + 128 + 32 + 16 + 4 + 1$$

$$= 437_{(base10)}$$

b) convierta el número decimal $131_{(base10)}$ a su forma binaria (base 2).

para convertir $131_{(base10)}$ a base dos, hacemos lo siguiente:

- Dividimos $131 \div 2 = 65$ con residuo $1$
- Dividimos $65 \div 2 = 32$ con residuo $1$
- Dividimos $32 \div 2 = 16$ con residuo $0$
- Dividimos $16 \div 2 = 8$ con residuo $0$
- Dividimos $8 \div 2 = 4$ con residuo $0$
- Dividimos $4 \div 2 = 2$ con residuo $0$
- Dividimos $2 \div 2 = 1$ con residuo $0$
- Dividimos $1 \div 2 = 0$ con residuo $1$

recopilando los residuos obtenemos:

$$\therefore \ 131_{(base10)} \Rightarrow 10000011_{(base2)}$$


## ejercicio-02 (3 puntos)

![triangulo](./img/tri.jpg)

considerando el triángulo de la figura anterior, calcule:

a) si $b=12$, $c=8$ y $\alpha = 63°$ ¿Cuál es la longitud del lado $a$?

usando el teorema del coseno:

$$b^2 + c^2 = a^2 + 2 \cdot b \cdot c\cdot \cos(\alpha)$$

$$12^2 + 8^2 = a^2 + 2 \cdot 12 \cdot 8 \cdot \cos(63°)$$

$$144 + 64 = a^2 + 192 \cdot \cos(63°)$$

$$208 = a^2 + 192 \cdot \cos(63°)$$

$$a = \sqrt{208 - 192 \cdot \cos(63°)}$$

$$a = 10.992$$

b) si $\alpha = 25°$, $\beta = 72°$ y $c = 12$ 
-   ¿cuánto mide $\gamma$? expresar resultado en grados y en **radianes**

    Los ángulos del triángulo suman 180°:

    $$\alpha + \beta + \gamma = 180°$$

    $$25° + 72° + \gamma = 180°$$

    $$\gamma = 180° - 25° - 72°$$

    $$\gamma = 83°$$

    Para pasar de grados a radianes hacemos:

    $$\frac{2 \pi}{360°} = \frac{X}{83°}$$

    $$X = \frac{2 \pi \cdot 83°}{360°}$$

    $$X \approx 0.461 \pi \ rad$$

    $$X \approx 1.44862 \ rad$$
    
-   ¿cuál es la longitud de $b$?

    usando el teorema del seno:

    $$\frac{b}{sin(\beta)} = \frac{c}{\sin(\gamma)}$$

    $$\frac{b}{sin(72°)} = \frac{12}{\sin(83°)}$$

    $$b = 12 \cdot \frac{sin(72°)}{\sin(83°)}$$

    $$a \approx 11.498$$

## ejercicio-03 (3 puntos)

necesito diseñar una rampa para uso con silla de ruedas. la entrada de mi casa es un escalon con una altura de 60 centímetros.

a) cual el largo de la rampa si tiene $18°$ de inclinación? y si tiene $12°$ de inclinación?
    
usando la relación trigonométrica del seno del ángulo, para los $18°$:

$$\sin(\beta) = \frac{cateto_{opuesto}}{hipotenusa}$$

$$\sin(\beta) = \frac{b}{c}$$

$$\sin(18°) = \frac{60(cm)}{c}$$

$$c = \frac{60(cm)}{\sin(18°)}$$

$$c \approx 194.164(cm)$$ 

por lo tanto, usando un ángulo de $18°$ la rampa tendrá un largo aproximado de $194.164(cm)$.

para la rampa de $12°$:

$$\sin(\beta) = \frac{b}{c}$$

$$\sin(12°) = \frac{60(cm)}{c}$$

$$c = \frac{60(cm)}{\sin(12°)}$$

$$c \approx 288.584(cm)$$ 

por lo tanto, usando un ángulo de $12°$ la rampa tendrá un largo aproximado de $288.584(cm)$.

b) si la rampa vale mil pesos chilenos por centímetro, cuál es la opcion más barata? cuanto es el precio?

la rampa más barata será la de $18°$ ya que es la que mide menos.

su costo será de:

$$costo \approx 194.164 \cdot 1000 $$

$$costo \approx \$ 194164 $$

## ejercicio-04: números hexadecimales (3 puntos)

a) dado el color RGB **#FC9BA4** representado en su forma hexadecimal (base 16), calcule el componente azul en forma decimal (base 10).

el componente azul es $A4_{(base16)}$, para convertirlo a su forma decimal hacemos la multiplicación por potencias de 16:

$$A4_{(base16)} \Rightarrow A \cdot 16^1 + 4 \cdot 16^0$$

convertimos las letras a su equivalente en base 10.

$$A4_{(base16)} \Rightarrow 10 \cdot 16^1 + 4 \cdot 16^0$$

y calculamos

$$= 160 + 4 = 164$$

$$\therefore \ A4_{(base16)} \Rightarrow 164_{(base10)}$$

por lo tanto este color tiene una intensidad 164 de azul.

b) cuál es el número máximo que se puede representar con 4 cifras hexadecimales? cuál es su equivalente en base 10?

el número hexadecimal más grande de cuatro cifras es $FFFF$.

para convertirlo a base 10 hacemos:

$$FFFF_{(base16)} \Rightarrow  F \cdot 16^3 + F \cdot 16^2 + F \cdot 16^1 + F \cdot 16^0$$

convertimos las letras a su equivalente en base 10.

$$FFFF_{(base16)} \Rightarrow  15 \cdot 16^3 + F \cdot 16^2 + 15 \cdot 16^1 + 15 \cdot 16^0$$

$$FFFF_{(base16)} \Rightarrow 65535_{(base10)}$$