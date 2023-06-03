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
            <td>
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
            <td>
                <span id="row2-button" class="toggle-button" onclick="toggleContent('row2')">Show</span>
            </td>
        </tr>
        <tr id="row1-content" class="toggle-content">
            <td></td>
            <td>Row 1, Column 2</td>
        </tr>
        <tr>
            <td>
                <span id="row3-button" class="toggle-button" onclick="toggleContent('row3')">Show</span>
            </td>
            <td>
                <span id="row4-button" class="toggle-button" onclick="toggleContent('row4')">Show</span>
            </td>
        </tr>
        <tr id="row3-content" class="toggle-content">
            <td>Row 2, Column 1</td>
            <td>Row 2, Column 2</td>
        </tr>
        <tr>
            <td>
                <span id="row5-button" class="toggle-button" onclick="toggleContent('row5')">Show</span>
            </td>
            <td>
                <span id="row6-button" class="toggle-button" onclick="toggleContent('row6')">Show</span>
            </td>
        </tr>
        <tr id="row5-content" class="toggle-content">
            <td>Row 3, Column 1</td>
            <td>Row 3, Column 2</td>
        </tr>
        <tr id="row6-content" class="toggle-content">
            <td>Row 4, Column 1</td>
            <td>Row 4, Column 2</td>
        </tr>
        <tr id="row6-content" class="toggle-content">
            <td>Row 4, Column 1</td>
            <td>Row 4, Column 2</td>
        </tr>
        <tr id="row6-content" class="toggle-content">
            <td>Row 4, Column 1</td>
            <td>Row 4, Column 2</td>
        </tr>
        <tr id="row6-content" class="toggle-content">
            <td>Row 4, Column 1</td>
            <td>Row 4, Column 2</td>
        </tr>
        <tr id="row6-content" class="toggle-content">
            <td>Row 4, Column 1</td>
            <td>Row 4, Column 2</td>
        </tr>
    </table>
</body>

El costo promedio de la arepa es 2500 COP. El costo de la materia prima diario es en total de:






