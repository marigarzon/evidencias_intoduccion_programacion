<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

# Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sitio web de Mariana</title>
</head>
<body>
<header>
<style>
    body {background-color: beige;}
</style>
<div align="center"> <h1>Mariana Garzon web</h1></div>
</header> 

<nav>
  <br>
  <button type="submit"> <a href="acerca.html">quienes somos</a></button>
  
  <button type="button"><a href="contacto.html">formulario</a></button>

</nav>
<main>
   <div align="center"> <p>Bienvenidos a mi sitio web - ALArte</p>
    <p>aqui podran encontrar informacion sobre nuestros productos</p>
</div>
</main>
<br><br><br><br><br>
    <footer>
        <p>Copyright 2023 - Mariana Garzon</p>
        <p>marianagarzonguerra@gmail.com</p>



    </footer>
</body>
</html>
```
- Acerca

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>nosotros</title>
</head>
<body>
    <header>
        <h1>sobre nosotros</h1>
    </header>

    <nav>
        <a href="index.html"></a>
        <a href="contacto.html"></a>
    </nav>

    <section>
        <h2>somos un emprendimiento de sublimacion, hacemos camisas, pocillos, gorras, etc.</h2>
        <p>fue fundada en 2022</p>

        <article>
            <p>https://www.instagram.com/alarte_col/?igshid=MzRlODBiNWFlZA%3D%3D</p>
            <p>abrir este enlace para ver la pagina</p>
        </article>
            
    </section>

    <footer>
        <p>Copyright 2023 - Mariana Garzon</p>
    </footer>
</body>
</html>
```

- Contacto

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contacto</title>

    <header>
        <h1>contacto</h1>
    </header>

    <nav>
        <a href="index.html"></a>
        <a href="acerca.html"></a>
    </nav>
    <main>
        <form>
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre"><br>

                <label for="email">Email:</label>
                <input type="text" id="email"><br>
              
                <label for="mensaje">Mensaje:</label>
                <input type="text" id="mensaje"><br>

                <input type="submit" value="enviar">
        </form>
        <aside>
            <h3>Girardota</h3>
            <p>antioquia</p>
        </aside>
    </main>

    <footer>
        <p>Copyright 2023 - Mariana Garzon</p>
    </footer>
</head>
<body>
    
</body>
</html>
```



 




