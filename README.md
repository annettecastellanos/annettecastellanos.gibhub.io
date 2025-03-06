<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Mini-Página Web</title>
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        h1, h2, h3 {
            color: #333;
        }

        p {
            font-size: 1.1em;
            line-height: 1.6;
            color: #555;
        }

        /* Menú de navegación */
        .menu {
            list-style-type: none;
            background-color: #333;
            padding: 10px;
            margin: 0;
            text-align: center;
        }

        .menu li {
            display: inline;
            margin-right: 20px;
        }

        .menu li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
        }

        .menu li a:hover {
            color: #f4f4f4;
        }

        /* Secciones */
        .seccion {
            padding: 20px;
            margin: 20px 0;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Tabla */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 8px;
            text-align: left;
        }

        th {
            background-color: #f4f4f4;
        }

        /* Estilos del video */
        video {
            width: 100%;
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <!-- Menú de navegación -->
    <ul class="menu">
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#acerca">Acerca de</a></li>
        <li><a href="#servicios">Servicios</a></li>
        <li><a href="#contacto">Contacto</a></li>
    </ul>

    <!-- Sección principal -->
    <div class="seccion" id="inicio">
        <h1>Bienvenido a Mi Página Web</h1>
        <h2>Una pequeña introducción sobre el propósito de esta página</h2>
        <p>Este es un ejemplo de una página web sencilla creada para poner en práctica las habilidades de HTML y CSS.</p>
    </div>

    <!-- Sección Acerca de -->
    <div class="seccion" id="acerca">
        <h2>Acerca de</h2>
        <p>Esta página está diseñada para demostrar el uso de diferentes elementos HTML y técnicas de maquetación, como tablas, imágenes, videos y menús de navegación.</p>
    </div>

    <!-- Contenido multimedia -->
    <div class="seccion">
        <h2>Contenido Multimedia</h2>
        <h3>Imagen Ejemplo</h3>
        <img src="https://via.placeholder.com/400" alt="Imagen de ejemplo" title="Imagen ejemplo" width="400">

        <h3>Video de Ejemplo</h3>
        <video controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Tu navegador no soporta el video.
        </video>
    </div>

    <!-- Tabla informativa -->
    <div class="seccion">
        <h2>Tabla de Ejemplo</h2>
        <table>
            <thead>
                <tr>
                    <th>Día</th>
                    <th>Actividad</th>
                    <th>Hora</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Lunes</td>
                    <td>Reunión de equipo</td>
                    <td>10:00 AM</td>
                </tr>
                <tr>
                    <td>Martes</td>
                    <td>Desarrollo web</td>
                    <td>2:00 PM</td>
                </tr>
                <tr>
                    <td>Miércoles</td>
                    <td>Revisión de código</td>
                    <td>11:00 AM</td>
                </tr>
            </tbody>
        </table>
    </div>

    <!-- Sección de contacto -->
    <div class="seccion" id="contacto">
        <h2>Contacto</h2>
        <p>Para más información, visita nuestra página de contacto.</p>
        <a href="https://www.ejemplo.com" target="_blank">Visita nuestro sitio web</a>
    </div>

</body>
</html>
