---
layout: post
title: Realización del primer MES
thumbnail-img: /assets/img/odoo.png
subtitle: Análisis del comportamiento de la empresa con los datos actuales
---

Utilizando los datos obtenidos por los empleados y lideres de la empresa, se procede a organizarlos por medio de la herramienta de ejecuión de manufactura (MES) y se realizará una simulación de la linea de producción para conocer la eficiencia general de este proceso en el momento actual.

## Tiempos de producción diaria

Realizando la simulación de la linea de producción por una semana, esta genera una gráfica general de rendimiento en cuestión de horas

<img src="/Trabajo-final/assets/img/eficiencia inicial.jpg" alt="Eficiencia" style="width:300px;height:300px;">

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
            <th>Proceso</th>
            <th>Rendimiento </th>
        </tr>
        <tr>
            <td>Preparación de la masa</td>
            <td>66</td>
        </tr>
        <tr>
            <td>Moldeado de la arepa</td>
            <td>70</td>
        </tr>
        <tr>
            <td>Cocinado en el horno</td>
            <td>86</td>
        </tr>
        <tr>
            <td>Empaquetado de la arepa</td>
            <td>66</td>
        </tr>
    </table>
</body>

Analizando los valores de rendimiento se puede observar que la maquina que está trabajando más tiempo es el horno, por lo que significa que tiene el proceso mas lento entre todas y retiene el producto durante la linea de producción, por lo que el proceso critico a solucionar es este.
