# UD 2.5 · Posicionamiento y overflow

## Ejercicio 2. Menú que se queda fijo  

### ¿Qué pasa con el contenido que había debajo? 
El contenido que había abajo se tapa por el `nav` esto porque tiene el `z-index` que hace que pase por encima, y al no estar pegado a la parte superior, la parte izquiera que lo tapa el `nav` no se ve, mientras que la derecha si.

### Diferencia entre fixed y sticky
La diferencia esque `fixed` solo flota en la página los elementos seleccionados, mientras que `sticky` selecciona toda la caja completa que se queda pegada a la parte que superior.
