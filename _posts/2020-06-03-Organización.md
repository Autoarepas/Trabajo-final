---
layout: post
title: Nueva organización
thumbnail-img: /assets/img/imagen_organizacion.jpg
subtitle: Utilización del MES para la organización y optimización de la producción en la empresa
---

Utilizando como referencia las maquinas mostradas y luego de una extensa búsqueda de valores promedio para las mismas, se obtuvieron los siguientes resultados en minutos por semana de producción

<head>
    <title>Centered Table Example</title>
    <style>
        table {
            border-collapse: collapse;
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
            <th>Máquina</th>
            <th>Produccón</th>
            <th>Tiempo de <br> subida</th>
            <th>Tiempo de <br> bajada</th>
            <th>Paradas</th>
            <th>MTBF</th>
            <th>MTTR</th>
        </tr>
        <tr>
            <td>Dosificación</td>
            <td>Dosificador por peso automático <br> lineal de 4 cabezales <br> 5g-1000g </td>
            <td>25s/1000g C/U</td>
            <td>2300</td>
            <td>17</td>
            <td>1</td>
            <td>2283</td>
            <td>17</td>   
        </tr>
        <tr>
            <td>Mezcla</td>
            <td>Mezcladora planetaria: <br> para el amasado de productos de <br> alta viscosidad y tixotropia</td>
            <td>10 minutos</td>
            <td>5800</td>
            <td>35</td>
            <td>1</td>
            <td>5765</td>
            <td>35</td>
        </tr>
        <tr>
            <td>Laminación</td>
            <td>Laminadora de masa <br> C: 430x1700 mm</td>
            <td>20 Unidades/min</td>
            <td>9000</td>
            <td>35</td>
            <td>1</td>
            <td>8965</td>
            <td>35</td>
        </tr>
        <tr>
            <td>Corte</td>
            <td>Laminadora industria para <br> arepas rellenas 40 c,</td>
            <td>4 Unidades/s</td>
            <td>9000</td>
            <td>35</td>
            <td>1</td>
            <td>8965</td>
            <td>35</td>
        </tr>
        <tr>
            <td>Horneado</td>
            <td>Horno tunel 1 nivel 40 <br> trabajables </td>
            <td>500 Unidades/h</td>
            <td>9000</td>
            <td>280</td>
            <td>1</td>
            <td>8720</td>
            <td>280</td>
        </tr>
    </table>
</body>

A partir de esto se les calcula el porcentaje de disponibilidad
