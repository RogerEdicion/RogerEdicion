## Hi there 👋

<!--
**RogerEdicion/RogerEdicion** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabla de Precios de Servicios</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 50px 0;
            font-size: 18px;
            text-align: left;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
        }
        th, td {
            padding: 12px 15px;
        }
        th {
            background-color: #FFDDC1;
            color: #333;
        }
        tr:nth-child(even) {
            background-color: #f3f3f3;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Servicio</th>
                <th>Precio (USD)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Edición de video (max 2 mins)</td>
                <td>7 USD x video</td>
            </tr>
            <tr>
                <td>Content Specialist (30 videos)</td>
                <td>410 USD</td>
            </tr>
            <tr>
                <td>Content Specialist (60 videos)</td>
                <td>750 USD</td>
            </tr>
            <tr>
                <td>Edición de video + Posteo (30 videos)</td>
                <td>310 USD</td>
            </tr>
            <tr>
                <td>Edición de video + Posteo (60 videos)</td>
                <td>540 USD</td>
            </tr>
            <tr>
                <td>Edición de video + Posteo (120 videos)</td>
                <td>780 USD</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
