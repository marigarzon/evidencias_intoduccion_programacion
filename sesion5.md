<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

# Actividad: Diseñar un formulario de pedido de un producto

Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
I- nformación de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.


**solucion**

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>formulario</title>
</head>
<body>
    
    <form>
        <label for="nombreProducto">Nombre del producto:</label>
        <input type="text" id="nombreProducto" name="nombreProducto" required><br><br>

        <label for="cantidad">Cantidad:</label>
        <input type="number" id="cantidad" name="cantidad" required><br><br>

        <label for="precioUnitario">Precio unitario:</label>
        <input type="number" id="precioUnitario" name="precioUnitario" step="0.01" required><br><br>

        <label for="precioTotal">Precio total:</label>
        <input type="number" id="precioTotal" name="precioTotal" step="0.01" required><br><br>

        <label for="direccionEnvio">Dirección de envío:</label>
        <input type="text" id="direccionEnvio" name="direccionEnvio" required><br><br>

        <label for="nombreContacto">Nombre de contacto:</label>
        <input type="text" id="nombreContacto" name="nombreContacto" required><br><br>

        <label for="correoElectronico">Correo Electrónico:</label>
        <input type="email" id="correoElectronico" name="correoElectronico" required><br><br>

        <label for="numeroTelefono">Número de Teléfono:</label>
        <input type="tel" id="numeroTelefono" name="numeroTelefono" required><br><br>

        <label for="metodoPago">Método de Pago:</label>
        <select id="metodoPago" name="metodoPago" required>
            <option value="tarjeta">Tarjeta de crédito</option>
            <option value="transferencia">Transferencia bancaria</option>
            <option value="efectivo">Efectivo</option>
        </select><br><br>

        <label for="fechaEntrega">Fecha de Entrega:</label>
        <input type="date" id="fechaEntrega" name="fechaEntrega" required><br><br>

        <label for="comentarios">Comentarios:</label>
        <textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea><br><br>

        <input type="submit" value="Enviar Pedido">
    </form>
</body>
</html>

</body>
</html>



