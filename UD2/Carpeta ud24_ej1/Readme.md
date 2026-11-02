# UD 2.4 · Divs

## Ejercicio 1. Mi portfolio con divs   

### Parte B — display: de columna a fila

#### Elección de display flex
He elegido `display: flex` porque con `inline-block` hay que vigilar los espacios en blanco del HTML, y calcular a mano para que los anchos, paddings, bordes, etc. no pasen de 800 px, mientras que con flex basta con aplicar la regla al contenedor para que las tarjetas se coloquen en fila sin huecos extraños, y es más fácil alinearlas. Por lo que me parece más cómodo y fácil de mantener.

### Parte C — Reto: block, inline y none

#### ¿qué diferencia hay entre margin y padding? 
El padding es el espacio dentro de la caja, entre el contenido y el borde, y el fondo lo cubre. El margin es el espacio fuera del borde que separa la caja de las demás.

#### ¿por qué saltaba la tercera tarjeta de línea? 
Porque cada tarjeta ocupaba 272px en conjunto de todo por lo que sumaban entre las 3 816px que no caben en los 800px de ancho que hay, por eso la tercera pasaba de línea.

#### ¿qué propiedades ignoraba el `<span>` y por qué?
El `<span>` ignoraba al `width`, `height` y los márfenes. Todo esto porque es un elemento que se comporta como texto, por lo que, solo ocupa lo que mide su contenido, no admite otro tipo de dimensiones propias.

#### ¿qué hace display: none con el espacio que ocupaba la caja?
La caja se elimina por completo al aplicarse, no ocupa ningún espacio, así que las otras tarjetas ocupan su sitio
