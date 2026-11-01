# UD2.1 - Ejercicio 4: Identificadores y atributos
 
## Parte A - Selector de id

### Id repetido

```html
    <h1 id="corp">Identificadores y atributos</h1>
    <h2 id="corp">Subtítulo </h2>
```
```
Error: Duplicate ID corp.

From line 10, column 5; to line 10, column 18

</h1>↩    <h2 id="corp">Subtít
```

Convierto el id en una clase:

```html
    <h1 id="corp">Identificadores y atributos</h1>
    <h2 class="corp">Subtítulo corregido</h2>
```

### ¿Por qué se desaconseja usar selectores de id para estilizar?
-Esto es porque el id tiene que ser único en la página, por lo que para reutilizar en otros elementos se usa la clase.
