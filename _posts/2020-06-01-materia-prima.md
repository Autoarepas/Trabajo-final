
Para conocer los requerimientos para la producción se necesitan los siguientes ingredientes:
<head>
    <title>Centered Dropdown Table</title>
    <style>
        table {
            margin: 0 auto; /* Centers the table horizontally */
        }

        th, td {
            padding: 10px;
            text-align: center;
        }

        .dropdown {
            position: relative;
            display: inline-block;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
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
            <th>Header 3</th>
        </tr>
        <tr>
            <td>
                <div class="dropdown">
                    <span>Row 1, Column 1</span>
                    <div class="dropdown-content">
                        <p>Dropdown Content 1</p>
                    </div>
                </div>
            </td>
            <td>
                <div class="dropdown">
                    <span>Row 1, Column 2</span>
                    <div class="dropdown-content">
                        <p>Dropdown Content 2</p>
                    </div>
                </div>
            </td>
            <td>
                <div class="dropdown">
                    <span>Row 1, Column 3</span>
                    <div class="dropdown-content">
                        <p>Dropdown Content 3</p>
                    </div>
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="dropdown">
                    <span>Row 2, Column 1</span>
                    <div class="dropdown-content">
                        <p>Dropdown Content 4</p>
                    </div>
                </div>
            </td>
            <td>
                <div class="dropdown">
                    <span>Row 2, Column 2</span>
                    <div class="dropdown-content">
                        <p>Dropdown Content 5</p>
                    </div>
                </div>
            </td>
            <td>
                <div class="dropdown">
                    <span>Row 2, Column 3</span>
                    <div class="dropdown-content">
                        <p>Dropdown Content 6</p>
                    </div>
                </div>
            </td>
        </tr>
        <!-- Add more rows and columns as needed -->
    </table>
</body>
