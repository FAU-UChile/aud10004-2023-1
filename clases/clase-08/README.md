# clase-08

jueves 11 mayo 2023, presencial

unidad 4: computadores y bits

## percepción de color

se estima que un humano puede distinguir hasta 10 millones de colores.

## daltonismo

habilidad reducida para ver colores o diferencias entre colores, que afecta aproximadamente al 8% de la población.

los más comunes son:

- rojo/verde
- azul/amarillo

## buenas prácticas en diseño

- dejar a la gente elegir los colores
- usar señales paralelas al color, como forma y orden.
- usar contraste en brillo además de contraste en color.
- incluir texto, incluso cuando el texto es obvio

## percepción de movimiento

hermanos Lumière en marzo de 1895 hicieron la primera función pública y pagada de imágenes en movimiento para 40 personas, lo que se denomina el nacimiento del cine.

las personas son capaces de percibir entre 10 y 12 imágenes por segundo como imágenes separadas, y tasas más grandes de refresco son percibidas como movimiento.

en cine se tiende a grabar a 24 cuadros por segundo.

en general se usa en computación tasas de refresco de 50 Hz hacia arriba.

https://www.youtube.com/watch?v=_SzGQkI-IwM

## modelo RGB

modelo aditivo, basado en los colores primarios rojo, verde y azul.

si usamos 8 bits para cada color, tenemos 24 bits en total, o sea, 2^24 posibilidades.

$$2^{24} = 16,777,216$$

## HSL y HSV/HSB

HSL viene de las siglas en inglés de:

- H: hue
- S: saturation
- L: lightness

HSV o HSB viene de la siglas en inglés de:

- H: hue
- S: saturation
- V: value / B: brighthness

## modelo CMYK

modelo substractivo, basado en los colores cyan, magenta, amarillo, y negro.

se le llama substractivo porque la tinta resta los colores rojo, verde y azul de la luz blanca.

## colores y computadores

un pixel RGB es capaz de brillar y con eso generar color.

si tenemos B bits de resolución por canal de color, entonces un pixel tiene 3B bits para representar su color.

entonces la cantidad de colores posibles en 1 pixel es:

$$colores_{pixel}= 2^{3 \cdot B}$$

si tenemos una pantalla de resolución 1080p, con 1920 por 1080 pixeles, entonces tenemos un total de.

$$pixeles = 1920 \cdot 1080 = 2,073,600$$

y cada uno de esos pixeles, puede ser de un color distinto, y necesitamos 3\*B bits de información para cada uno, y así definir su color.

si tenemos una tasa de refresco de 60 Hz, significa que tenemos 60 cuadros por segundo.

viernes 12 mayo 2023

## resolución

si tenemos voltajes entre 0V y 5V, y tenemos 8 bits.

## bibliografía

- https://www.cliffsnotes.com/study-guides/physics/light/characteristics-of-light
- https://en.wikipedia.org/wiki/Trichromacy
  https://en.wikipedia.org/wiki/Color_blindness
- https://en.wikipedia.org/wiki/HSL_and_HSV
- https://en.wikipedia.org/wiki/CMYK_color_model
- https://en.wikipedia.org/wiki/LMS_color_space
- https://en.wikipedia.org/wiki/Auguste_and_Louis_Lumi%C3%A8re
- https://en.wikipedia.org/wiki/Frame_rate
