<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>María Fernanda Apaza Meza</title>
  <style>
    :root {
        --background-light: #FE470A;
        --text-light: #333;
        --background-dark: #FFB51F;
        --text-dark: #FE470A  
    }
    
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #FFB51F;
      color: orange;
      TRANSITION: 0.3s;
    }
  
    header, footer {
      text-align: center;
      background-color: #FE470A;
      color: white
      padding: 1rem;
    }
    
    nav {
      background-color: #FFB51F;
      padding: 1rem;
      text-align: center;
    }
    
    nav a {
      color: #fe470a;
      text-decoration: none;
      margin-right: 20px;
      font-weight: bold;
    }
    section {
      background-color: white;
      margin: 20px;
      padding: 20px;
      border-radius: 10px;
    }
    .section-title {
      color: #fe470a;
      font-weight: bold;
      font-size: 1.5em;
      margin-bottom: 10px;
    }
    .divider {
      border-top: 1px solid #ccc;
      margin: 10px 0;
    }
    .section-text {
      color: black;
      font-size: 0.95em;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #f0f0f0;
      padding: 15px;
      border-radius: 10px;
    }
    .card-title {
      color: #fe470a;
      font-weight: bold;
      font-size: 1.2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>María Fernanda Apaza Meza</h1>
    <p>Estudiante de Administración de Negocios en la UCSP</p>
  </header>
  <nav>
    <a href="#sobremi">Sobre mí</a>
    <a href="#cursos-universitarios">Cursos Universitarios</a>
    <a href="#cursos-adicionales">Cursos Adicionales</a>
    <a href="#idiomas">Idiomas</a>
    <a href="#amigos">Amigos y Compañeros</a>
    <a href="#contacto">Contacto</a>
  </nav>
  <section id="sobremi">
    <div class="section-title">Sobre mí</div>
    <div class="divider"></div>
    <p class="section-text">
      Hola soy Mafer, una estudiante de la carrera de Administración de Negocios en la 
      <a href="https://ucsp.edu.pe/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
        Universidad Católica San Pablo
      </a>. Me describiría como una persona muy sociable, por ende, trabajo muy bien en equipos.
    </p>
  </section>
  <section id="cursos-universitarios">
    <div class="section-title">Cursos Universitarios</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Economía General</div></div>
      <div class="card"><div class="card-title">Fundamentos de la Administración</div></div>
      <div class="card"><div class="card-title">Pensamiento Crítico</div></div>
      <div class="card"><div class="card-title">Derecho Empresarial</div></div>
      <div class="card"><div class="card-title">Fundamentos del Marketing</div></div>
      <div class="card"><div class="card-title">Matemática Financiera</div></div>
      <div class="card"><div class="card-title">Análisis Financiero</div></div>
      <div class="card"><div class="card-title">Introducción a las Ciencias de la Computación II</div></div>
    </div>
  </section>
  <section id="cursos-adicionales">
    <div class="section-title">Cursos Adicionales</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">PMBA</div></div>
      <div class="card"><div class="card-title">Ruta del Progreso</div></div>
    </div>
  </section>
  <section id="idiomas">
    <div class="section-title">Idiomas</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Inglés</div></div>
      <div class="card"><div class="card-title">Francés</div></div>
    </div>
  </section>
  <section id="amigos">
    <div class="section-title">Amigos y Compañeros</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Valentina Bedregal</div></div>
      <div class="card"><div class="card-title">Piero Chahuares</div></div>
      <div class="card"><div class="card-title">Krislet Juarez</div></div>
      <div class="card"><div class="card-title">Mariano Mendoza</div></div>
      <div class="card"><div class="card-title">Sergio Palomino</div></div>
      <div class="card"><div class="card-title">Vanessa Yesán</div></div>
    </div>
  </section>
  <section id="contacto">
    <div class="section-title">Contacto</div>
    <div class="divider"></div>
    <p class="section-text">- maria.apaza.meza@ucsp.edu.pe</p>
  </section>
</body>
</html>
