<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Francisco's GitHub Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            text-align: center;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #fff;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        .name {
            font-size: 2.5em;
            margin: 20px 0 10px 0;
            color: #2c3e50;
        }
        .subtitle {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 20px;
        }
        .stats {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 30px 0;
        }
        .stat-card {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            min-width: 200px;
        }
        .stat-number {
            font-size: 2em;
            font-weight: bold;
            color: #3498db;
        }
        .stat-label {
            color: #7f8c8d;
            margin-top: 5px;
        }
        .section {
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        .section h2 {
            color: #2c3e50;
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }
        .skill-badge {
            background: linear-gradient(45deg, #3498db, #2980b9);
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            box-shadow: 0 3px 10px rgba(52, 152, 219, 0.3);
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 20px;
            border-left: 5px solid #3498db;
            transition: transform 0.3s;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }
        .contact {
            text-align: center;
        }
        .contact a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px;
            background: #3498db;
            color: white;
            border-radius: 50%;
            text-decoration: none;
            transition: background 0.3s;
        }
        .contact a:hover {
            background: #2980b9;
        }
        .github-stats {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 30px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <img src="https://github.com/oscardelaluzgalicia-arty.png" alt="Francisco's Avatar" class="avatar">
            <h1 class="name">Hola, soy Francisco 👋</h1>
            <p class="subtitle">Ingeniero en Tecnologías de la Información | Backend | Datos | Automatización</p>
            <p>🚀 Construyendo soluciones reales con código, datos e infraestructura</p>
        </div>

        <!-- GitHub Stats -->
        <div class="github-stats">
            <img src="https://github-readme-stats.vercel.app/api?username=oscardelaluzgalicia-arty&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=oscardelaluzgalicia-arty&layout=compact&theme=radical&hide_border=true" alt="Top Languages">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=oscardelaluzgalicia-arty&theme=radical&hide_border=true" alt="GitHub Streak">
        </div>

        <!-- About -->
        <div class="section">
            <h2>👨‍💻 Sobre mí</h2>
            <p>Ingeniero en tecnologías de la información con experiencia en entornos profesionales. Me enfoco en comprender el funcionamiento de los sistemas para implementar soluciones prácticas, eficientes y orientadas a resultados.</p>
            <p>He trabajado en la instalación y mantenimiento de redes empresariales, sistemas de videovigilancia (CCTV) y administración de servidores, desarrollando habilidades en soporte técnico, resolución de incidencias y atención directa a usuarios.</p>
            <p>Me caracterizo por ser analítico, constante y orientado a la mejora continua. Actualmente enfoco mi crecimiento en automatización de procesos y desarrollo de software, con el objetivo de optimizar operaciones y generar soluciones de valor.</p>
        </div>

        <!-- Skills -->
        <div class="section">
            <h2>🛠️ Stack Tecnológico</h2>
            <div class="skills">
                <span class="skill-badge">Python</span>
                <span class="skill-badge">Java</span>
                <span class="skill-badge">JavaScript</span>
                <span class="skill-badge">C++</span>
                <span class="skill-badge">C#</span>
                <span class="skill-badge">Node.js</span>
                <span class="skill-badge">Express</span>
                <span class="skill-badge">HTML</span>
                <span class="skill-badge">CSS</span>
                <span class="skill-badge">Bootstrap</span>
                <span class="skill-badge">MySQL</span>
                <span class="skill-badge">PostgreSQL</span>
                <span class="skill-badge">MongoDB</span>
                <span class="skill-badge">Vercel</span>
                <span class="skill-badge">Linux</span>
                <span class="skill-badge">Nginx</span>
                <span class="skill-badge">Git</span>
                <span class="skill-badge">GitHub</span>
                <span class="skill-badge">Bitbucket</span>
                <span class="skill-badge">Postman</span>
                <span class="skill-badge">VS Code</span>
                <span class="skill-badge">Android Studio</span>
                <span class="skill-badge">Jira</span>
                <span class="skill-badge">Power BI</span>
                <span class="skill-badge">Canva</span>
                <span class="skill-badge">Microsoft Office</span>
            </div>
        </div>

        <!-- Certifications -->
        <div class="section">
            <h2>📜 Certificaciones</h2>
            <div class="projects">
                <div class="project-card">
                    <h3>Copilot: domina la IA en Microsoft 365</h3>
                    <p>Archivo: PDF</p>
                    <a href="assets/Copilot%20domina%20la%20IA%20en%20Microsoft%20365.pdf" target="_blank">Ver certificado</a>
                </div>
                <div class="project-card">
                    <h3>Mindfulness & Worklife Balance</h3>
                    <p>Archivo: PDF</p>
                    <a href="assets/Mindfulness%20%26%20Worklife%20Balance.pdf" target="_blank">Ver certificado</a>
                </div>
                <div class="project-card">
                    <h3>Power BI</h3>
                    <p>Archivo: PDF</p>
                    <a href="assets/Power%20BI.pdf" target="_blank">Ver certificado</a>
                </div>
            </div>
        </div>

        <!-- Contact -->
        <div class="section contact">
            <h2>📬 Conecta conmigo</h2>
            <a href="https://www.linkedin.com/in/francisco-de-la-luz-b004483b5/" target="_blank">
                <img width="30px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"/>
            </a>
            <a href="mailto:oscardelaluzgalicia@gmail.com">
                <img width="32px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg"/>
            </a>
        </div>

        <!-- Snake Animation -->
        <div class="section">
            <h2>🐍 Contribuciones</h2>
            <p align="center">
                <img src="https://github.com/oscardelaluzgalicia-arty/oscardelaluzgalicia-arty/blob/output/github-contribution-grid-snake.svg" alt="snake">
            </p>
        </div>
    </div>
</body>
</html>
