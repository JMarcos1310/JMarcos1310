<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Profesional - Juan Marcos Remigio</title>
    <style>
        /* Estilos generales */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1, h2, h3 {
            color: #2c3e50;
        }

        a {
            color: #3498db;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        .header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        .profile {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: white;
            margin-top: -30px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .profile img {
            border-radius: 50%;
            height: 150px;
            width: 150px;
        }

        .profile-info {
            flex: 1;
            margin-left: 20px;
        }

        .section {
            padding: 20px;
            background-color: white;
            margin-top: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section h2 {
            margin-top: 0;
            color: #2980b9;
        }

        .skills, .experience, .certifications, .education {
            margin-top: 10px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin: 5px 0;
        }

        .skills ul, .experience ul {
            column-count: 2;
        }

        .footer {
            text-align: center;
            padding: 10px;
            background-color: #2c3e50;
            color: white;
            margin-top: 20px;
        }

        @media (max-width: 768px) {
            .profile {
                flex-direction: column;
                align-items: center;
            }

            .profile-info {
                text-align: center;
                margin-left: 0;
                margin-top: 10px;
            }

            .skills ul, .experience ul {
                column-count: 1;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Juan Marcos Remigio Victoriano</h1>
        <p>Desarrollador Web</p>
    </div>

    <div class="container">
        <div class="profile">
            <img src="https://via.placeholder.com/150" alt="Juan Marcos Remigio">
            <div class="profile-info">
                <p><strong>Email:</strong> remigiojuanmarcos@gmail.com</p>
                <p><strong>Teléfono:</strong> 7201353744</p>
                <p><strong>LinkedIn:</strong> <a href="#">Juan Marcos Remigio</a></p>
                <p><strong>GitHub:</strong> <a href="#">JMarcos1310</a></p>
            </div>
        </div>

        <div class="section">
            <h2>Perfil Profesional</h2>
            <p>Desarrollador web con experiencia en la implementación de aplicaciones, diseño de interfaces y gestión de bases de datos. Orientado a la mejora continua y la optimización de procesos. Busco aportar mis habilidades en un entorno dinámico de desarrollo, contribuyendo al éxito del equipo mediante soluciones tecnológicas innovadoras.</p>
        </div>

        <div class="section">
            <h2>Habilidades</h2>
            <div class="skills">
                <ul>
                    <li>HTML, CSS, JavaScript</li>
                    <li>PHP, Laravel</li>
                    <li>Vue.js, Node.js</li>
                    <li>PostgreSQL, SQL Server</li>
                    <li>Linux, Git</li>
                    <li>Liderazgo, trabajo en equipo</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>Experiencia Profesional</h2>
            <div class="experience">
                <h3>Desarrollador Web - Like per Second SAS de CV</h3>
                <p><em>Feb 2024 - Presente</em></p>
                <ul>
                    <li>Implementación de microaplicaciones con Power Apps, mejorando la eficiencia operativa en un 25%.</li>
                    <li>Diseño y maquetación de interfaces en línea con los estándares de la industria.</li>
                    <li>Gestión y optimización de bases de datos mediante Directus.</li>
                    <li>Desarrollo de módulos personalizados para proyectos clave.</li>
                </ul>

                <h3>Soporte Técnico y Docente - Escuela Primaria Niños Héroes</h3>
                <p><em>Jun 2023 - Ene 2024</em></p>
                <ul>
                    <li>Mantenimiento preventivo y correctivo de equipos de cómputo.</li>
                    <li>Implementación de mejoras en la infraestructura de red.</li>
                    <li>Capacitación de alumnos en conceptos básicos de informática.</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>Certificaciones</h2>
            <div class="certifications">
                <ul>
                    <li>CCNAv7: Switching, Routing, and Wireless Essentials</li>
                    <li>Introducción a la Ciberseguridad</li>
                    <li>Hacking Ético y Ciberseguridad para Principiantes</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>Educación</h2>
            <div class="education">
                <p><strong>Licenciatura en Informática</strong></p>
                <p>Universidad Mexiquense del Bicentenario (2019 - 2024)</p>
            </div>
        </div>

        <div class="section">
            <h2>Proyectos</h2>
            <div class="projects">
                <ul>
                    <li><strong>Gestión de Inventario Escolar:</strong> Sistema web para la gestión de inventarios en una escuela primaria.</li>
                    <li><strong>Aplicación de Control de Asistencia:</strong> Desarrollo de una aplicación para automatizar el control de asistencia de empleados.</li>
                </ul>
            </div>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2024 Juan Marcos Remigio Victoriano</p>
    </div>
</body>
</html>
