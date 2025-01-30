<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Table Example</title>
    <style>
        table {
            width: 90%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
            text-align: left;
        }
    </style>
</head>
<body>

<h2>Sample HTML Table</h2>

<table>
    <thead>
        <tr>
            <th style="width:40%"></th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Step 1</td>
			<td rowspan="4"><img src="truck1.jpg" width="400"</td>
        </tr>
        <tr>
            <td>Step 2</td>
        </tr>
        <tr>
            <td>Step 3</td>
        </tr>
		<tr>
            <td>Step 5</td>
        </tr>
    </tbody>
</table>

</body>
</html>
