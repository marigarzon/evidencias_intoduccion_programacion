<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

# Actividad: Propiedades de posicionamiento de CSS

1.¿Cuál es la diferencia entre los valores position: absolute y position: relative?
R\ 
position: absolute: Cuando se aplica a un elemento, este se posiciona de acuerdo a su ancestro posicionado más cercano (elemento padre con una posición diferente de static). Los valores de top, right, bottom y left se utilizan para determinar la posición exacta del elemento en relación con ese ancestro.
- position: relative: Este valor permite posicionar un elemento con respecto a su posición original en el flujo del documento. Puedes usar valores de top, right, bottom y left para desplazar el elemento desde su posición original, pero seguirá ocupando espacio en el flujo del documento, lo que puede afectar a otros elementos.

2. ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

R\
La propiedad z-index se utiliza para controlar el orden de apilamiento de elementos posicionados (con position diferente de static). Los elementos con un valor de z-index más alto se colocan en la parte superior de los elementos con un valor de z-index más bajo. Es importante recordar que z-index solo funciona en elementos posicionados (position diferente de static). Si dos elementos tienen el mismo ancestro y se superponen, el elemento con un valor de z-index más alto se mostrará encima.

3. ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

R\
display se utiliza para controlar cómo se muestra un elemento en una página web. Algunos valores comunes de display incluyen:

- block: Hace que el elemento ocupe todo el ancho disponible y comienza en una nueva línea. Los párrafos y encabezados son ejemplos de elementos en bloque.
- inline: Hace que el elemento se muestre en la misma línea que el contenido circundante, sin ocupar todo el ancho disponible. Los elementos span y a son ejemplos de elementos en línea.
- inline-block: Combina propiedades de elementos en bloque y en línea. Ocupa solo el espacio necesario y permite aplicar propiedades de bloque, como márgenes y relleno.
- none: Hace que el elemento desaparezca por completo de la visualización.
flex, grid, etc.: Introducen diseños flexibles o en cuadrícula, permitiendo un control más avanzado del diseño de la página.

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```