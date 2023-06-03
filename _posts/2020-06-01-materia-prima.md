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
    </style>
    <script>
        function toggleContent(rowId) {
            var content = document.getElementById(rowId + '-content');
            var button = document.getElementById(rowId + '-button');
            if (content.style.display === 'none') {
                content.style.display = 'table-row';
                button.innerHTML = 'Hide';
            } else {
                content.style.display = 'none';
                button.innerHTML = 'Show';
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
            <td colspan="3">
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
        </tr>
        <tr id="row1-content" class="toggle-content">
            <td>Harina</td>
            <td>57.6 g</td>
            <td>Row 1, Column 3</td>
        </tr>
        <tr>
            <td colspan="3">
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
        </tr>
        <tr id="row4-content" class="toggle-content">
            <td>Queso</td>
            <td>28.8 g</td>
            <td>Row 2, Column 3</td>
        </tr>
        <tr>
            <td colspan="3">
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
        </tr>
        </tr>
        <tr id="row7-content" class="toggle-content">
            <td>Azucar</td>
            <td>3.2 g</td>
            <td>Row 3, Column 3</td>
        </tr>
        <tr>
            <tr>
            <td colspan="3">
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
        </tr>
        <tr id="row10-content" class="toggle-content">
            <td>Sal</td>
            <td>1.6 g</td>
            <td>Row 4, Column 3</td>
        </tr>
        <tr>
            <tr>
            <td colspan="3">
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
        </tr>
        </tr>
        <tr id="row10-content" class="toggle-content">
            <td>Mantequilla</td>
            <td>12.8 g</td>
            <td>Row 4, Column 3</td>
        </tr>
        <tr>
            <tr>
            <td colspan="3">
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
        </tr>
        </tr>
        <tr id="row10-content" class="toggle-content">
            <td>Agua</td>
            <td>56 ml</td>
            <td>Row 4, Column 3</td>
        </tr>
    </table>
</body>

El costo promedio de la arepa es 2500 COP. El costo de la materia prima diario es en total de:






