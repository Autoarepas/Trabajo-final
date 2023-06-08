---
layout: post
title: Realización del primer MES
thumbnail-img: /assets/img/odoo.png
subtitle: Análisis del comportamiento de la empresa con los datos actuales
---

Utilizando los datos dados por los empleados y lideres de la empresa se procede a recopilar los datos para realizar un sistema de ejecuión de manufactura (MES) y se recopilarán en una simulación de la linea de producción para conocer la eficiencia general de este proceso.

## Tiempos de producción diaria

Se realiza la simulación de producción de una semana de la empresa con los datos obtenidos se tienen los valores de eficiencia y tiempo demorado del uso de la maquina:

<img src="/Trabajo-final/assets/img/eficiencia inicial.jpg" alt="Eficiencia">

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
            <td>66%</td>
        </tr>
        <tr>
            <td>Moldeado de la arepa</td>
            <td>70%</td>
        </tr>
        <tr>
            <td>Cocinado en el horno</td>
            <td>86%</td>
        </tr>
        <tr>
            <td>Empaquetado de la arepa</td>
            <td>66%</td>
        </tr>
    </table>
</body>
