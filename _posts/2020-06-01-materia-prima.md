Para conocer los requerimientos para la producción se necesitan los siguientes ingredientes:

<head>
    <title>Centered Retractable Table</title>
    <style>
        table {
            border-collapse: collapse;
            margin: 0 auto;
        }

        table, th, td {
            border: 1px solid black;
            text-align: center;
        }

        th, td {
            padding: 8px;
        }

        .toggle-content {
            display: none;
        }

        .toggle-button {
            cursor: pointer;
            text-decoration: underline;
        }
        .color-cell {
            background-color: #DAF7A6; 
        }
    </style>
    <script>
        function toggleContent(rowId) {
            var content = document.getElementById(rowId + '-content');
            var button = document.getElementById(rowId + '-button');
            if (content.style.display === 'none') {
                content.style.display = 'table-row';
                button.innerHTML = 'Ocultar';
            } else {
                content.style.display = 'none';
                button.innerHTML = 'Mostrar';
            }
        }
    </script>
</head>
<body>
    <table>
        <tr>
            <th>Producto</th>
            <th>Cantidad por unidad</th>
            <th>Costo unitario</th>
        </tr>
        <tr>
            <td style="text-align: center" colspan="3">                
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Harina</span>
            </td>
        </tr>
        <tr id="row1-content" class="toggle-content">
            <td style="text-align: center">Harina</td>
            <td style="text-align: center">57.6 g</td>
            <td style="text-align: center">3.64 COP/g</td>
        </tr>
        <tr>
            <td style="text-align: center" colspan="3">
                <span id="row2-button" class="toggle-button" onclick="toggleContent('row2')">Queso</span>
            </td>
        </tr>
        <tr id="row2-content" class="toggle-content">
            <td style="text-align: center">Queso</td>
            <td style="text-align: center">28.8 g</td>
            <td style="text-align: center">17 COP/g</td>
        </tr>
        <tr>
            <td style="text-align: center" colspan="3">
                <span id="row3-button" class="toggle-button" onclick="toggleContent('row3')">Mostrar</span>
            </td>
        </tr>
        </tr>
        <tr id="row3-content" class="toggle-content">
            <td style="text-align: center">Azucar</td>
            <td style="text-align: center">3.2 g</td>
            <td style="text-align: center">4.5 COP/g</td>
        </tr>
        <tr>
            <tr>
            <td style="text-align: center" colspan="3">
                <span id="row4-button" class="toggle-button" onclick="toggleContent('row4')">Mostrar</span>
            </td>
        </tr>
        <tr id="row4-content" class="toggle-content">
            <td style="text-align: center">Sal</td>
            <td style="text-align: center">1.6 g</td>
            <td style="text-align: center">2.33 COP/g</td>
        </tr>
        <tr>
            <tr>
            <td style="text-align: center" colspan="3">
                <span id="row5-button" class="toggle-button" onclick="toggleContent('row5')">Mostrar</span>
            </td>
        </tr>
        </tr>
        <tr id="row5-content" class="toggle-content">
            <td style="text-align: center">Mantequilla</td>
            <td style="text-align: center">12.8 g</td>
            <td style="text-align: center">15.65 COP/g</td>
        </tr>
        <tr>
            <tr>
            <td style="text-align: center" colspan="3">
                <span id="row6-button" class="toggle-button" onclick="toggleContent('row6')">Mostrar</span>
            </td>
        </tr>
        </tr>
        <tr id="row6-content" class="toggle-content">
            <td style="text-align: center">Agua</td>
            <td style="text-align: center">56 ml</td>
            <td style="text-align: center">4.88 COP/L</td>

El costo promedio de la arepa es 2500 COP. El costo de la materia prima diario es en total de:






