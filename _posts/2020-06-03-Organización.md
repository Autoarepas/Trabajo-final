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
            <th>Producción</th>
            <th>Up Time</th>
            <th>Down Time</th>
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


## Tiempos de producción y rendimiento de procesos

Realizando la simulación de la linea de producción por una semana, esta genera una gráfica general de rendimiento en cuestión de horas. Se presenta un esquema de la línea de producción
<div style="text-align:center">
  <img src="/Trabajo-final/assets/img/proceso propuesta.png" alt="Image" style="width:900px;height:450px;">
</div>
La gráfica general de Rendimiento
<div style="text-align:center">
  <img src="/Trabajo-final/assets/img/perfectos.jpg" alt="Image" style="width:900px;height:450px;">
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
            <td style="text-align: center">71%</td>
        </tr>
        <tr>
            <td style="text-align: center">Moldeado de la arepa</td>
            <td style="text-align: center">89%</td>
        </tr>
        <tr>
            <td style="text-align: center">Cocinado en el horno</td>
            <td style="text-align: center">95%</td>
        </tr>
        <tr>
            <td style="text-align: center">Empaquetado de la arepa</td>
            <td style="text-align: center">90%</td>
        </tr>
    </table>
</body>

Analizando los valores de rendimiento se puede observar que la maquina que está trabajando más tiempo es el horno, por lo que significa que tiene el proceso mas lento entre todos y retiene el producto durante la linea de producción, por lo que el proceso critico a solucionar es este. Cada proceso tiene diversos indices, con estos se evaluará cual es de todos es el proceso menos eficiente utilizando el indice global de eficiencia (OEE).

<ul>
    <li> <b><i>Preparación de la mezcla</i></b> </li>
    <img src="/Trabajo-final/assets/img/prepmasa.jpg" alt="Eficiencia">
    <li> <b><i>Moldeado de las arepas</i></b> </li>
    <img src="/Trabajo-final/assets/img/moldeo.jpg" alt="Eficiencia">
    <li> <b><i>Cocinado</i></b> </li>
    <img src="/Trabajo-final/assets/img/horno.jpg" alt="Eficiencia">
    <li> <b><i>Empaquetado</i></b> </li>
    <img src="/Trabajo-final/assets/img/empaquetamiento.jpg" alt="Eficiencia">
</ul>

Dando como resultado los siguientes tiempos de producción

<body>
    <table>
        <tr>
            <th style="text-align: center">Dia de producción</th>
            <th style="text-align: center"> Preparación de Masa</th>
            <th style="text-align: center"> Moldeado de Arepa</th>
            <th style="text-align: center"> Horno</th>
            <th style="text-align: center"> Empaquetado</th>
        </tr>
        <tr>
            <td style="text-align: center">Lunes-Jueves</td>
            <td style="text-align: center">15:12 min</td>
            <td style="text-align: center">25 min</td>
            <td style="text-align: center"> 60 min </td>
            <td style="text-align: center"> 47 min </td>
        </tr>
        <tr>
            <td style="text-align: center">Viernes</td>
            <td style="text-align: center">18:20 min</td>
            <td style="text-align: center">40 min</td>
            <td style="text-align: center">96 min </td>
            <td style="text-align: center"> 72 min </td>
        </tr>
        <tr>
            <td style="text-align: center">Sábado-Domingo</td>
            <td style="text-align: center"> 20:25 min</td>
            <td style="text-align: center">50 min</td>
            <td style="text-align: center">120 min </td>
            <td style="text-align: center">89 min </td>
        </tr>
    </table>
</body>

## Aumento en productividad

Una vez implementada la automatización a la empresa, se hace una comparación en el aumento en la productividad para las diferentes estaciones de operación.
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
            <th style="text-align: center">Aumento Productividad </th>
        </tr>
        <tr>
            <td style="text-align: center">Preparación de la masa</td>
            <td style="text-align: center">87%</td>
        </tr>
        <tr>
            <td style="text-align: center">Moldeado de la arepa</td>
            <td style="text-align: center">335%</td>
        </tr>
        <tr>
            <td style="text-align: center">Cocinado en el horno</td>
            <td style="text-align: center">297%</td>
        </tr>
        <tr>
            <td style="text-align: center">Empaquetado de la arepa</td>
            <td style="text-align: center">89%</td>
        </tr>
    </table>
</body>
