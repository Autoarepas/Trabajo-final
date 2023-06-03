
Para conocer los requerimientos para la producción se necesitan los siguientes ingredientes:

<head>
    <title>Tabla Oculta</title>
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

        .hidden {
            visibility: hidden;
        }
    </style>
    <script>
        function toggleContent(rowId) {
            var rowValues = document.getElementsByClassName(rowId + '-value');
            for (var i = 0; i < rowValues.length; i++) {
                if (rowValues[i].classList.contains('hidden')) {
                    rowValues[i].classList.remove('hidden');
                } else {
                    rowValues[i].classList.add('hidden');
                }
            }
        }
    </script>
</head>
<body>
    <table>
        <tr>
            <th onclick="toggleContent('row1')">Título 1</th>
            <th onclick="toggleContent('row2')">Título 2</th>
        </tr>
        <tr>
            <td class="row1-value">Valor 1</td>
            <td class="row2-value">Valor 2</td>
        </tr>
        <tr>
            <td class="row1-value">Valor 3</td>
            <td class="row2-value">Valor 4</td>
        </tr>
        <tr>
            <td class="row1-value">Valor 5</td>
            <td class="row2-value">Valor 6</td>
        </tr>
    </table>
</body>
</html>
