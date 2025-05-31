<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>María Fernanda Apaza Meza</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Rectángulo blanco de cabecera */
    header {
      background-color: white;
      width: 100%;
      padding: 40px 20px;
    }

    header h1 {
      margin: 0;
      font-weight: bold;
      color: #fe470a;
    }

    header p {
      margin: 5px 0 0 0;
      font-weight: bold;
      color: #fe470a;
    }

    /* Menú */
    nav {
      background-color: #fe470a;
      padding: 10px 20px;
    }

    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-start;
    }

    nav ul li {
      margin-right: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }

    /* Secciones del contenido */
    section {
      padding: 40px 20px;
    }

    h2 {
      color: #fe470a;
    }

    footer {
      background-color: #f0f0f0;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <!-- RECTÁNGULO BLANCO SUPERIOR -->
  <header>
    <h1>María Fernanda Apaza Meza</h1>
    <p>Estudiante de Administración de Negocios en la UCSP</p>
  </header>

  <!-- MENÚ DE NAVEGACIÓN -->
  <nav>
    <ul>
      <li><a href="#sobre-mi">Sobre mí</a></li>
      <li><a href="#experiencia">Experiencia</a></li>
      <li><a href="#formacion">Formación</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <!-- SECCIONES -->
  <section id="sobre-mi">
    <h2>Sobre mí</h2>
    <p>Aquí puedes escribir una breve presentación sobre ti, tus intereses, pasiones o lo que te gustaría que las personas sepan al visitar tu web personal.</p>
  </section>

  <section id="experiencia">
    <h2>Experiencia</h2>
    <p>Aquí puedes listar tu experiencia laboral, voluntariado o cualquier otro proyecto importante que hayas desarrollado.</p>
  </section>

  <section id="formacion">
    <h2>Formación</h2>
    <p>Incluye aquí tu educación académica, cursos importantes o certificaciones relevantes.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Puedes agregar tu correo electrónico, LinkedIn u otros medios para que las personas te contacten.</p>
  </section>

  <footer>
    &copy; 2025 María Fernanda Apaza Meza. Todos los derechos reservados.
  </footer>

</body>
</html>
