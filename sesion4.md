<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tablas</title>
</head>
<body>
    <h1>actividad 4</h1>
    <h2>Mariana Garzon Guerra</h2>

    <table border="1" cellpadding="8" cellspacing="15" >
        <thead>
          <tr>
            <th>Código</th>
            <th>Nombre</th>
            <th colspan="2">Descripción</th>
            <th>Precio</th>
            <th>Stock</th>
            <th>Fecha de creación</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>A1000</td>
            <td>Freidora de aire</td>
            <td>-Capacidad
                4 Litros <br>
                -Tipo de Base
                Recubrimiento Antiadherente <br>
                </td>
                <td>-Recomendaciones
                    Antes de usar la cesta por primera vez, cubre la superficie con aceite vegetal. Calienta descubierta a una temperatura de 150ºC, por 10 a 15 minutos.</td>
            <td>$311.600</td>
            <td>40 U</td>
            <td>12/04/23</td>

          </tr>
          <tr>
            <td>Cafetera Cafe City 6 Tazas</td>
            <td>A1023</td>
            <td>Tiene capacidad para 6 tazas de café en una sola preparación. <br>
                Sistema antigoteo Cuenta con sistema antigoteo que permite retirar la jarra mientras el café se prepara evitando derrames. <br>
                Porta filtro extraíble El porta filtro es de fácil acceso y extraíble para facilitar su limpieza.</td>
            <td>$99.900</td>
            <td>96 U</td>
            <td>10/06/23</td>
          </tr>

          <tr>
            <td>Horno Y Freidora De Aire</td>
            <td>A213917</td>
            <td>El horno Oster® de 25L con función de freír con aire te permite crear una variedad de comidas deliciosas y perfectamente crujientes, sin exceso de aceite o grasas. Utiliza un 99.5% menos aceite*.</td>
            <td>$559.000</td>
            <td>164 U</td>
            <td>12/02/22</td>
          </tr>

          <tr>
            <td>Parrilla Electrica</td>
            <td>A102876</td>
            <td>-1500 watts
                -Capacidad de 8 Porciones <br>
                -Superficie Antiadherente <br>
                -Superficie de cocción <br>
                -19 x 75 x 10.25' <br>
                -Canal para eliminar el exceso de grasa <br>
                -Bandeja de goteo removible</td>
            <td>$228.900</td>
            <td>2 U</td>
            <td>21/06/21</td>
          </tr>

          <tr>
            <td>Waflera Mini Anti Aderente Electrica</td>
            <td>A101735</td>
            <td>Mini Waflera de 350 W de potencia, bajo consumo de energía, fácil de operar, fácil de transportar, para satisfacer las necesidades de diferentes ocasiones como viajes y desayunos sorpresas</td>
            <td>$42.998</td>
            <td>48 U</td>
            <td>12/01/23</td>
          </tr>

          <tr>
            <td>Aire acon inver</td>
            <td>A320275</td>
            <td>Tecnología de Enfriamiento Inverter</td>
            <td>$1.747.908</td>
            <td>101 U </td>
            <td>12/10/22</td>
          </tr>

          <tr>
            <td>Lavadora SAMSUNG</td>
            <td>A17246</td>
            <td>-Panel de control:
                Digital <br>
                -Capacidad de carga
                19 kg (42 lb) <br>
                -Tipo de Motor
                Convencional con poleas <br>
                -Peso
                43 kg</td>
            <td>$2.189.778</td>
            <td>130 U </td>
            <td>31/12/22</td>
          </tr>

          <tr>
            <td>Televisor SAMSUNG </td>
            <td>A33995</td>
            <td>-Panel de control:
                Digital <br>
                -Capacidad de carga
                19 kg (42 lb) <br>
                -Tipo de Motor
                Convencional con poleas <br>
                -Peso
                43 kg</td>
            <td>$2.189.778</td>
            <td>130 U </td>
            <td>31/12/22</td>
          </tr>
          <tr>
            <td>Cámara Instax Mini Evo </td>
            <td>A101994</td>
            <td>- Produce impresiones de tamaño de tarjeta de crédito <br>

                - Sensor CMOS de 1/5 ", resolución 2560x1920 <br>
                
                - Lente fija de 28 mm f / 2 (equivalente a 35 mm) <br>
                
                - Monitor LCD de 2.7 "con 230k puntos <br>
                
                - Bluetooth para la operación de teléfonos inteligentes <br>
                
                - Aplicación para imprimir y agregar filtros <br>
                - Flash integrado y espejo Selfie</td>
            <td>$979.900</td>
            <td>1 U </td>
            <td>18/11/21</td>
          </tr>
          <tr>
            <td>Celular Xiaomi Redmi Note 12S 256Gb </td>
            <td>A102723</td>
            <td>- Libre de fábrica para cualquier compañía. <br>
                - Procesador: Mediatek Helio G96. <br>
                - GPU: ARM Mali-G57 MC2
                - Pantalla: 6,43' AMOLED FHD+ <br>
                - Tasa de refresco Hasta 90Hz <br>
                - Resolución: 2400 x 1080 FHD+ <br>
                - Sensor de Huellas Digitales LATERAL para desbloqueo <br>
                - Memoria Interna de 256 GB <br>
                - Memoria RAM de 8 GB <br>
                - Cámara Trasera: 3 Cámaras 108 MP + 8 MP +2 MP <br>
                - Cámara Frontal : 16 MP <br>
                - Puerto carga Tipo C</td>
            <td>$799.900</td>
            <td>5 U </td>
            <td>31/05/22</td>
          </tr>
          
        </tbody>
   
    
</body>
</html>



