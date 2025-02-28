<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        table {
            width: 80%;
            margin: 50px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            text-align: left;
            border: 1px solid transparent;
        }
        th {
            background-color: #333;
            color: white;
            font-size: 20px;
        }
        td {
            background-color: #fff;
            color: #333;
        }
        .image-container {
            width: 150px;
            height: 150px;
            margin: 0 auto;
            border-radius: 50%;
            overflow: hidden;
        }
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .header {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .section-title {
            font-size: 20px;
            font-weight: bold;
            color: #333;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <th colspan="2">Hoja de Vida</th>
        </tr>
        <tr>
            <td rowspan="3" style="width: 150px;">
                <div class="image-container">
                    <img src="https://www.w3schools.com/w3images/avatar2.png" alt="Foto">
                </div>
            </td>
            <td class="header">Juan Pérez</td>
        </tr>
        <tr>
            <td><strong>Profesión:</strong> Ingeniero de Software</td>
        </tr>
        <tr>
            <td><strong>Email:</strong> juan.perez@email.com</td>
        </tr>
    </table>

    <table>
        <tr>
            <td colspan="2" class="section-title">Experiencia Laboral</td>
        </tr>
        <tr>
            <td><strong>Empresa:</strong> Tech Solutions</td>
            <td><strong>Fecha:</strong> 2020 - Actualidad</td>
        </tr>
        <tr>
            <td colspan="2">Desarrollador Full Stack</td>
        </tr>
        <tr>
            <td colspan="2">Responsable de la creación y mantenimiento de aplicaciones web y móviles.</td>
        </tr>
    </table>

    <table>
        <tr>
            <td colspan="2" class="section-title">Educación</td>
        </tr>
        <tr>
            <td><strong>Título:</strong> Ingeniería en Sistemas</td>
            <td><strong>Institución:</strong> Universidad de Tecnología</td>
        </tr>
        <tr>
            <td><strong>Año:</strong> 2016 - 2020</td>
            <td><strong>Promedio:</strong> 9.5</td>
        </tr>
    </table>

    <table>
        <tr>
            <td colspan="2" class="section-title">Habilidades</td>
        </tr>
        <tr>
            <td colspan="2">JavaScript, Python, React, Node.js, SQL, HTML/CSS</td>
        </tr>
    </table>
</body>
</html>
