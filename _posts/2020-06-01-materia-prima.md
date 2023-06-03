
Para conocer los requerimientos para la producción se necesitan los siguientes ingredientes:

<head>
    <title>Centered Retractable Table with Images</title>
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
            <th>Image 1</th>
            <th>Image 2</th>
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
            <td>
                <img src="image1.jpg" alt="Image 1" width="200" height="150">
            </td>
            <td>
                <img src="image2.jpg" alt="Image 2" width="200" height="150">
            </td>
        </tr>
        <tr id="row2-content" class="toggle-content">
            <td>
                <img src="image3.jpg" alt="Image 3" width="200" height="150">
            </td>
            <td>
                <img src="image4.jpg" alt="Image 4" width="200" height="150">
            </td>
        </tr>
    </table>
</body>
