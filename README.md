# ejemplo-desarrollo-web
html ,creacion y diseño
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agencia Creativa</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    header {
      background: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #444;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    .servicio {
      background: #fff;
      margin: 20px auto;
      padding: 20px;
      max-width: 600px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Agencia Creativa</h1>
    <p>Diseño, Desarrollo y Marketing Digital</p>
  </header>

  <nav>
    <a href="#diseno">Diseño</a>
    <a href="#desarrollo">Desarrollo Web</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="diseno">
    <div class="servicio">
      <h2>Diseño Gráfico</h2>
      <p>Creación de identidades visuales, logotipos y material publicitario con estilo minimalista y profesional.</p>
    </div>
  </section>

  <section id="desarrollo">
    <div class="servicio">
      <h2>Desarrollo Web</h2>
      <p>Construcción de sitios web modernos, responsivos y optimizados para SEO.</p>
    </div>
  </section>

  <section id="contacto">
    <div class="servicio">
      <h2>Contacto</h2>
      <p>Escríbenos a <strong>info@agenciacreativa.com</strong> para más información.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2026 Agencia Creativa - Todos los derechos reservados</p>
  </footer>
</body>
</html>
