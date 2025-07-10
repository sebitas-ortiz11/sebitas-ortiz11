## Hi there 👋

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil de Seguridad Informática - [Tu Nombre] ¡Animado!</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

        :root {
            --primary-color: #2980b9;
            --secondary-color: #34495e;
            --accent-color: #3498db;
            --bg-light: #ecf0f1;
            --bg-dark: #ffffff;
            --text-color: #333;
            --border-color: #ddd;
        }

        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: var(--bg-light);
            color: var(--text-color);
            overflow-x: hidden; /* Evita barras de desplazamiento horizontales */
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            background: var(--bg-dark);
            padding: 30px 40px;
            border-radius: 12px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
            opacity: 0; /* Inicialmente invisible para la animación */
            transform: translateY(20px);
            animation: fadeInRise 0.8s ease-out forwards;
        }

        @keyframes fadeInRise {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1, h2, h3 {
            color: var(--secondary-color);
            padding-bottom: 10px;
            margin-bottom: 20px;
            position: relative;
        }

        h1 {
            text-align: center;
            color: var(--primary-color);
            font-size: 2.8em;
            font-weight: 700;
            margin-bottom: 30px;
        }

        h1::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: var(--accent-color);
            margin: 10px auto 0;
            border-radius: 2px;
        }

        h2 {
            font-size: 2em;
            margin-top: 50px;
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin-top: 35px;
            color: var(--accent-color);
        }

        p {
            margin-bottom: 15px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background: var(--bg-light);
            margin-bottom: 10px;
            padding: 12px 20px;
            border-left: 5px solid var(--accent-color);
            border-radius: 6px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        ul li:hover {
            transform: translateX(10px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .project-item {
            background: var(--bg-dark);
            border: 1px solid var(--border-color);
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }

        .project-item h3 {
            margin-top: 0;
            border-bottom: none;
            color: var(--primary-color);
            font-weight: 600;
        }

        .project-item a {
            font-weight: 600;
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: var(--primary-color);
            text-decoration: underline;
        }

        .contact-info a {
            display: inline-block;
            margin-right: 20px;
            font-weight: bold;
            padding: 10px 15px;
            border: 2px solid var(--accent-color);
            border-radius: 25px;
            transition: background-color 0.3s ease, color 0.3s ease, transform 0.3s ease;
        }

        .contact-info a:hover {
            background-color: var(--accent-color);
            color: white;
            transform: translateY(-3px);
            text-decoration: none;
        }

        .stats-images {
            text-align: center;
            margin-top: 40px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .stats-images img {
            max-width: 48%; /* Para dos imágenes por fila en pantallas grandes */
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .stats-images img:hover {
            transform: scale(1.03);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
        }

        .icon {
            margin-right: 10px;
            color: var(--accent-color);
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            h1 {
                font-size: 2em;
            }
            h2 {
                font-size: 1.5em;
            }
            h3 {
                font-size: 1.2em;
            }
            .stats-images img {
                max-width: 90%; /* Una imagen por fila en pantallas pequeñas */
            }
            .contact-info a {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><i class="fas fa-shield-alt icon"></i> Mi Perfil de Seguridad Informática</h1>

        <p>
            <i class="fas fa-hand-sparkles icon"></i> ¡Hola! Soy <strong>[Tu Nombre Completo]</strong>
        </p>
        <p>
            Soy un <strong>[Tu Título/Rol, ej. Analista de Seguridad, Ingeniero de Ciberseguridad, Ethical Hacker en formación]</strong> apasionado por la protección de sistemas y datos. Mi objetivo es construir y asegurar infraestructuras robustas, identificar vulnerabilidades y contribuir a un entorno digital más seguro.
        </p>
        <p>
            En este espacio, encontrarás una muestra de mis **proyectos, herramientas y contribuciones** en diversas áreas de la seguridad informática. Estoy siempre en busca de nuevos desafíos y oportunidades para aplicar y expandir mis conocimientos.
        </p>

        ---

        <h2><i class="fas fa-rocket icon"></i> Mis Habilidades Clave</h2>
        <ul>
            <li><i class="fas fa-bug icon"></i> <strong>Análisis de Vulnerabilidades:</strong> Escaneo, testing y reporte de debilidades en sistemas y aplicaciones.</li>
            <li><i class="fas fa-user-secret icon"></i> <strong>Pentesting:</strong> Pruebas de intrusión (web, red, móvil) y explotación controlada.</li>
            <li><i class="fas fa-network-wired icon"></i> <strong>Seguridad de Redes:</strong> Configuración segura de firewalls, IDS/IPS, VPNs y segmentación.</li>
            <li><i class="fas fa-magnifying-glass-chart icon"></i> <strong>Análisis Forense Digital:</strong> Recuperación y análisis de evidencia digital.</li>
            <li><i class="fas fa-code icon"></i> <strong>Programación Segura:</strong> Desarrollo de código con enfoque en la prevención de vulnerabilidades (Python, [Otros lenguajes relevantes]).</li>
            <li><i class="fas fa-cloud icon"></i> <strong>[Añade otras habilidades relevantes, ej. Cloud Security (AWS/Azure), SIEM, Respuesta a Incidentes, Reversing Engineering].</strong></li>
        </ul>

        ---

        <h2><i class="fas fa-tools icon"></i> Herramientas y Tecnologías</h2>
        <ul>
            <li><i class="fas fa-terminal icon"></i> <strong>Sistemas Operativos:</strong> Linux (Kali, Parrot), Windows Server.</li>
            <li><i class="fas fa-cogs icon"></i> <strong>Frameworks/Herramientas:</strong> Metasploit, Nmap, Wireshark, Burp Suite, OWASP ZAP, Nessus, OpenVAS.</li>
            <li><i class="fas fa-file-code icon"></i> <strong>Lenguajes de Scripting:</strong> Python, Bash, PowerShell.</li>
            <li><i class="fas fa-server icon"></i> <strong>Virtualización:</strong> VMware, VirtualBox, Docker.</li>
            <li><i class="fas fa-shield-halved icon"></i> <strong>[Añade otras herramientas y tecnologías con las que estés familiarizado].</strong></li>
        </ul>

        ---

        <h2><i class="fas fa-folder-open icon"></i> Mis Proyectos Destacados</h2>

        <div class="project-item">
            <h3><a href="[Enlace a tu repositorio en GitHub]" target="_blank"><i class="fab fa-github icon"></i> Nombre del Proyecto 1</a></h3>
            <p><strong>Descripción:</strong> [Breve descripción del proyecto, qué problema resuelve o qué demuestra].</p>
            <p><strong>Tecnologías:</strong> [Lenguajes, herramientas, frameworks utilizados].</p>
            <p><strong>Objetivo de Seguridad:</strong> [Qué aspecto de la seguridad aborda].</p>
            <p><strong>Estado:</strong> [Completado/En Progreso].</p>
        </div>

        <div class="project-item">
            <h3><a href="[Enlace a tu repositorio en GitHub]" target="_blank"><i class="fab fa-github icon"></i> Nombre del Proyecto 2</a></h3>
            <p><strong>Descripción:</strong> [Breve descripción].</p>
            <p><strong>Tecnologías:</strong> [Tecnologías utilizadas].</p>
            <p><strong>Objetivo de Seguridad:</strong> [Qué aspecto de la seguridad aborda].</p>
            <p><strong>Estado:</strong> [Completado/En Progreso].</p>
        </div>

        <div class="project-item">
            <h3><a href="[Enlace a tu repositorio en GitHub]" target="_blank"><i class="fab fa-github icon"></i> Nombre del Proyecto 3</a></h3>
            <p><strong>Descripción:</strong> [Breve descripción].</p>
            <p><strong>Tecnologías:</strong> [Tecnologías utilizadas].</p>
            <p><strong>Objetivo de Seguridad:</strong> [Qué aspecto de la seguridad aborda].</p>
            <p><strong>Estado:</strong> [Completado/En Progreso].</p>
        </div>

        ---

        <h2><i class="fas fa-chart-line icon"></i> Futuros Proyectos e Intereses</h2>
        <p>
            Estoy constantemente aprendiendo y explorando nuevas áreas dentro de la ciberseguridad. Algunos de mis próximos intereses incluyen:
        </p>
        <ul>
            <li><i class="fas fa-lightbulb icon"></i> <strong>[Idea de Proyecto Futuro 1]:</strong> [Breve descripción de lo que te gustaría explorar o construir].</li>
            <li><i class="fas fa-flask icon"></i> <strong>[Idea de Proyecto Futuro 2]:</strong> [Breve descripción].</li>
            <li><i class="fas fa-book-reader icon"></i> <strong>[Área de Interés 1]:</strong> [Ej. Seguridad en contenedores, Blockchain Security, AI/ML en ciberseguridad].</li>
            <li><i class="fas fa-globe-americas icon"></i> <strong>[Área de Interés 2]:</strong> [Ej. Red Teaming, GRC (Governance, Risk, and Compliance)].</li>
        </ul>

        ---

        <h2><i class="fas fa-handshake icon"></i> Conéctate Conmigo</h2>
        <p>
            Estoy abierto a nuevas oportunidades y colaboraciones. ¡No dudes en contactarme!
        </p>
        <div class="contact-info">
            <a href="[Tu Enlace a LinkedIn]" target="_blank"><i class="fab fa-linkedin icon"></i> LinkedIn</a>
            <a href="mailto:[Tu Correo Electrónico]"><i class="fas fa-envelope icon"></i> Correo Electrónico</a>
            </div>

        ---

        <h2><i class="fas fa-code-branch icon"></i> Mis Estadísticas de GitHub (Opcional)</h2>
        <p>Puedes mostrar tus estadísticas de GitHub aquí. Recuerda reemplazar <code>[Tu_Usuario_GitHub]</code> con tu nombre de usuario real.</p>
        <div class="stats-images">
            <img src="https://github-readme-stats.vercel.app/api?username=[Tu_Usuario_GitHub]&show_icons=true&theme=dark&hide_border=true&line_height=25" alt="Your GitHub Stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[Tu_Usuario_GitHub]&layout=compact&theme=dark&hide_border=true" alt="Top Langs">
        </div>
    </div>
</body>
</html>
