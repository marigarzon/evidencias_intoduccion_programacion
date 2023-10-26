<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

Encabezado <header>
Tres párrafos <p>
Una imagen <img>
Un pie de página <footer>
Aplica los siguientes estilos usando selectores de etiqueta:

Color rojo a los encabezados <h1>
Color azul a los párrafos <p>
Borde grueso negro a la imagen <img>
Aplica los siguientes estilos usando seleccionadores de clase:

Color verde a los elementos con la clase ".destacado"
Tamaño de fuente grande a los elementos con la clase ".grande"
Aplica los siguientes estilos usando seleccionadores de ID:

Color amarillo al elemento con ID "#principal"
Sombra al elemento con ID "#sombras"
Aplica los siguientes estilos usando seleccionadores descendientes:

Color gris a los párrafos dentro de un <div>
Centrar el contenido de la sección <section>

```html
<!DOCTYPE html>
<html>
<head>
    <title>Ejemplo de Estilos CSS</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <header>
        <h1>Encabezado</h1>
    </header>

    <section>
        <p>Párrafo 1</p>
        <div>
            <p>Párrafo 2</p>
        </div>
        <p>Párrafo 3</p>
        <img src="golden.jpeg" alt="Golden retriever">
    </section>

    <footer>
        <p class="destacado">Pie de página</p>
    </footer>
</body>
</html>

```

```css
h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 2px solid black;
}


.destacado {
    color: green;
}

.grande {
    font-size: 1.5em;
}


#principal {
    color: yellow;
}

#sombras {
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

```



