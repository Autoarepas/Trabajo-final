---
layout: post
title: Realización del primer MES
thumbnail-img: /assets/img/odoo.png
subtitle: Análisis del comportamiento de la empresa con los datos actuales
---

Utilizando los datos obtenidos por los empleados y lideres de la empresa, se procede a organizarlos por medio de la herramienta de ejecuión de manufactura (MES) y se realizará una simulación de la linea de producción para conocer la eficiencia general de este proceso en el momento actual.

## Tiempos de producción y rendimiento de procesos

Realizando la simulación de la linea de producción por una semana, esta genera una gráfica general de rendimiento en cuestión de horas

<div style="text-align:center">
  <img src="/Trabajo-final/assets/img/eficiencia inicial.jpg" alt="Image" style="width:800px;height:450px;">
</div>

De esta barra de datos se obtienen los siguientes valores de rendimiento:

<head>
    <title>Centered Table Example</title>
    <style>
        table {
            margin: 0 auto;
        }

        table, th, td {
            border: 1px solid black;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <th style="text-align: center">Proceso</th>
            <th style="text-align: center">Rendimiento </th>
        </tr>
        <tr>
            <td style="text-align: center">Preparación de la masa</td>
            <td style="text-align: center">66%</td>
        </tr>
        <tr>
            <td style="text-align: center">Moldeado de la arepa</td>
            <td style="text-align: center">70%</td>
        </tr>
        <tr>
            <td style="text-align: center">Cocinado en el horno</td>
            <td style="text-align: center">86%</td>
        </tr>
        <tr>
            <td style="text-align: center">Empaquetado de la arepa</td>
            <td style="text-align: center">66%</td>
        </tr>
    </table>
</body>

Analizando los valores de rendimiento se puede observar que la maquina que está trabajando más tiempo es el horno, por lo que significa que tiene el proceso mas lento entre todos y retiene el producto durante la linea de producción, por lo que el proceso critico a solucionar es este. Cada proceso tiene diversos indices, con estos se evaluará cual es de todos es el proceso menos eficiente utilizando el indice global de eficiencia (OEE).

<ul>
    <li> <b><i>Preparación de la mezcla</i></b> </li>
    <img src="/Trabajo-final/assets/img/preparación inicial.jpg" alt="Eficiencia">
    <li> <b><i>Moldeado de las arepas</i></b> </li>
    <img src="/Trabajo-final/assets/img/moldeado inicial.jpg" alt="Eficiencia">
    <li> <b><i>Cocinado</i></b> </li>
    <img src="/Trabajo-final/assets/img/cocinado inicial.jpg" alt="Eficiencia">
    <li> <b><i>Empaquetado</i></b> </li>
    <img src="/Trabajo-final/assets/img/empaquetado inicial.jpg" alt="Eficiencia">
</ul>

Como se puede observar el OEE va a tener valores similares al indice de rendimiento ya que no se tienen en cuenta valores de carga ni de mantenimiento ya que son procesos manuales y depende exclusivamente de la velocidad del personal, por lo que no existen registros de estos valores. De nuevo, el cocinado es el proceso que mas valor tiene en los indices en general, por lo que es la maquina que mas realiza trabajo, sin embargo como es la unica maquinaria este indice debe ser menor ya que debe tener indices de mantenimiento que no se pueden tener en cuenta debido a falta de datos.

## Costos totales

Los costos se obtienen a partir de la simulación ingresando los valores conocidos de la materia prima (mostrados en <a href="https://autoarepas.github.io/Trabajo-final/2020-10-01-materia-prima/">materia prima</a>), los costos del personal (2 personas con salario mínimo), entre otros costos fijos y variables se tienen los costos por dias de la semana:





