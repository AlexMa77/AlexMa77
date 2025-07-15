<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mi Presentación Profesional</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet"/>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #282c34;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .section {
      padding: 30px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
    }
    .skills, .certificates {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .skill, .certificate {
      background: white;
      padding: 10px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .skill img, .certificate img {
      width: 40px;
      height: 40px;
      margin-bottom: 8px;
    }
    footer {
      background: #282c34;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>¡Hola! Soy [Tu Nombre]</h1>
    <p>Desarrollador Full Stack | Entusiasta de la tecnología</p>
  </header>

  <div class="section">
    <h2>Lenguajes y Tecnologías</h2>
    <div class="skills">
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python"/><p>Python</p></div>
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML"/><p>HTML</p></div>
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS"/><p>CSS</p></div>
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C"/><p>C</p></div>
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL"/><p>PostgreSQL</p></div>
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL"/><p>MySQL</p></div>
      <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React"/><p>React</p></div>
    </div>
  </div>

  <div class="section">
    <h2>Certificados</h2>
    <div class="certificates">
      <div class="certificate">
        <img src="https://img.icons8.com/color/48/certificate.png" alt="Certificado 1"/>
        <p><strong>[Nombre del Certificado]</strong><br/>[Institución]</p>
      </div>
      <div class="certificate">
        <img src="https://img.icons8.com/color/48/certificate.png" alt="Certificado 2"/>
        <p><strong>[Nombre del Certificado]</strong><br/>[Institución]</p>
      </div>
      <!-- Puedes duplicar este bloque para más certificados -->
    </div>
  </div>

  <footer>
    <p>© 2025 [Tu Nombre] - GitHub Portfolio</p>
  </footer>
</body>
</html>
