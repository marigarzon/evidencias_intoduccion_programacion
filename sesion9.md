<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

# Actividad: Propiedades de espaciado y unidades de medida

**preguntas**

1. ¿Qué es la propiedad margin?

R\ Esta propiedad se utiliza para controlar el espacio exterior alrededor de un elemento. Puedes definir márgenes en la parte superior, derecha, inferior e izquierda de un elemento individualmente o de manera conjunta. Los valores pueden ser especificados en píxeles, porcentajes, ems, etc.

2. ¿Qué es la propiedad padding?
R\ El padding se utiliza para controlar el espacio interno dentro de un elemento, es decir, el espacio entre el contenido del elemento y su borde. Al igual que con margin, puedes definir valores de relleno para la parte superior, derecha, inferior e izquierda por separado o de manera conjunta.

3. ¿Qué es la propiedad border?
R\ La propiedad border se utiliza para establecer las propiedades de borde de un elemento. Puedes definir el ancho, el estilo y el color del borde. Por ejemplo, border: 2px solid #000; establece un borde de 2 píxeles de ancho, de estilo sólido y color negro.

4. ¿Qué es la propiedad border-radius?
R\ Esta propiedad se utiliza para redondear las esquinas de un elemento, como un cuadro o un botón. Puedes especificar el radio de redondeo para cada una de las cuatro esquinas individualmente o de manera conjunta.


5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?


R\ Unidades de medida comunes que se pueden utilizar para estas propiedades de espaciado incluyen:

- Píxeles (px): Una unidad de medida fija. Por ejemplo, margin: 10px; establece un margen de 10 píxeles.

- Porcentajes (%): Los porcentajes se refieren a un porcentaje del tamaño del elemento padre. Por ejemplo, width: 50%; hará que el ancho del elemento sea el 50% del ancho de su contenedor.

- Ems (em): Esta unidad se basa en el tamaño de fuente actual del elemento. Un valor de 1em es igual al tamaño de fuente actual. Por ejemplo, padding: 1em; establecerá el relleno igual al tamaño de fuente actual.

- Rems (rem): Similar a em, pero se basa en el tamaño de fuente del elemento raíz (generalmente el tamaño de fuente del elemento html).

```HTML
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

```css
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
//Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.//

.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

//Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.//
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

//Border: Agrega un borde de 5 píxeles de color rojo.//
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

//Border-radius: Agrega un radio de esquina de 10 píxeles.//
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

//Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%//

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```



