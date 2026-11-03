# UD2.5 · Posicionamiento y overflow

## Ejercicio 3. Tarjeta de producto y caja con scroll

### ¿Qué elemento necesita position: relative para que la etiqueta se coloque respecto a la tarjeta?
Lo necesita el `.tarjeta` debido a que la etiqueta del -20% desaparece sino está el relative porque sube arriba de la ventana y no de la tarjeta.

### ¿Qué le pasa a la parte de la etiqueta que sobresale? Anota por qué y cómo lo arreglarías.
La parte de la etiqueta sobresale se corta con el `overflow: hidden` oculta todo lo que sale del contenedor.

Yo lo arreglaría quitando el `overflow: hidden` y cambiando el `top` y el `right` para definir que esté dentro de la tarjeta, y no sobresaliendo. 

### Prueba overflow: visible, hidden, scroll y auto. Anota en el README qué hace cada uno y deja auto.
`overflow: visible` permite ver todos los comentarios pero fuera de los bordes.
`overflow: hiddem` permite ver los comentarios que están dentro de los límites de la caja.
`overflow: scroll` permite deslizarte tanto arriba-abajo, como dereche-izquiera, permitiendo ver todos los comentarios sin cortarlos y que tampoco sobresalgan del texto.
`overflow: auto` como indica el nombre se recorta y si lo necesita le pone un scroll automáticamente, por eso le dejamos ese al final.

### Duplica una tarjeta y prueba visibility: hidden en una y display: none en la otra. Anota la diferencia respecto al hueco que dejan.
Con `visibility: hidden` simplemente la tarjeta se esconde, pero sigue estando su anchura y su altura, es **invisible**. Mientras que `display: none` la quita como si no existiera.
