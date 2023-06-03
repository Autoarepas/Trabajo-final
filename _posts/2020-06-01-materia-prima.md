
Para conocer los requerimientos para la producción se necesitan los siguientes ingredientes:

<head>
    <title>Drop-down Table</title>
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

        .dropdown-content {
            display: none;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
        <tr class="dropdown">
            <td>Row 1</td>
            <td>
                <div class="dropdown-content">
                    <p>Dropdown Content 1</p>
                    <p>Dropdown Content 2</p>
                    <p>Dropdown Content 3</p>
                </div>
            </td>
        </tr>
        <tr class="dropdown">
            <td>Row 2</td>
            <td>
                <div class="dropdown-content">
                    <p>Dropdown Content 4</p>
                    <p>Dropdown Content 5</p>
                    <p>Dropdown Content 6</p>
                </div>
            </td>
        </tr>
        <tr class="dropdown">
            <td>Row 3</td>
            <td>
                <div class="dropdown-content">
                    <p>Dropdown Content 7</p>
                    <p>Dropdown Content 8</p>
                    <p>Dropdown Content 9</p>
                </div>
            </td>
        </tr>
    </table>
</body>
