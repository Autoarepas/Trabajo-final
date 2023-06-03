
Para conocer los requerimientos para la producción se necesitan los siguientes ingredientes:

<head>
    <title>Retractable Table</title>
    <style>
        table {
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: left;
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
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr>
            <td>
                <span id="row1-button" class="toggle-button" onclick="toggleContent('row1')">Show</span>
            </td>
            <td></td>
        </tr>
        <tr id="row1-content" class="toggle-content">
            <td>Row 1</td>
            <td>Content 1</td>
        </tr>
        <tr>
            <td>
                <span id="row2-button" class="toggle-button" onclick="toggleContent('row2')">Show</span>
            </td>
            <td></td>
        </tr>
        <tr id="row2-content" class="toggle-content">
            <td>Row 2</td>
            <td>Content 2</td>
        </tr>
        <tr>
            <td>
                <span id="row3-button" class="toggle-button" onclick="toggleContent('row3')">Show</span>
            </td>
            <td></td>
        </tr>
        <tr id="row3-content" class="toggle-content">
            <td>Row 3</td>
            <td>Content 3</td>
        </tr>
    </table>
</body>
