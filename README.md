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
    .servicio, .contacto {
      background: #fff;
      margin: 20px auto;
      padding: 20px;
      max-width: 600px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    button {
      background: #333;
      color: #fff;
      border: none;
      padding: 10px 20px;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background: #555;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
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
      <p>Identidades visuales, logotipos y material publicitario con estilo minimalista y profesional.</p>
      <button>Ver Portafolio</button>
    </div>
  </section>

  <section id="desarrollo">
    <div class="servicio">
      <h2>Desarrollo Web</h2>
      <p>Construcción de sitios web modernos, responsivos y optimizados para SEO.</p>
      <button>Solicitar Demo</button>
    </div>
  </section>

  <section id="contacto">
    <div class="contacto">
      <h2>Contáctanos</h2>
      <form action="#" method="post">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo" required>
        <textarea name="mensaje" rows="5" placeholder="Escribe tu mensaje..." required></textarea>
        <button type="submit">Enviar Mensaje</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2026 Agencia Creativa - Todos los derechos reservados</p>
  </footer>
</body>
</html>
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
    .servicio, .contacto {
      background: #fff;
      margin: 20px auto;
      padding: 20px;
      max-width: 600px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    button {
      background: #333;
      color: #fff;
      border: none;
      padding: 10px 20px;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background: #555;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    .mensaje-confirmacion {
      margin-top: 15px;
      color: green;
      font-weight: bold;
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
      <p>Identidades visuales, logotipos y material publicitario con estilo minimalista y profesional.</p>
      <button>Ver Portafolio</button>
    </div>
  </section>

  <section id="desarrollo">
    <div class="servicio">
      <h2>Desarrollo Web</h2>
      <p>Construcción de sitios web modernos, responsivos y optimizados para SEO.</p>
      <button>Solicitar Demo</button>
    </div>
  </section>

  <section id="contacto">
    <div class="contacto">
      <h2>Contáctanos</h2>
      <form id="form-contacto">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo" required>
        <textarea name="mensaje" rows="5" placeholder="Escribe tu mensaje..." required></textarea>
        <button type="submit">Enviar Mensaje</button>
      </form>
      <div id="confirmacion" class="mensaje-confirmacion" style="display:none;">
        ¡Gracias por tu mensaje! Nos pondremos en contacto pronto.
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2026 Agencia Creativa - Todos los derechos reservados</p>
  </footer>

  <script>
    const form = document.getElementById('form-contacto');
    const confirmacion = document.getElementById('confirmacion');

    form.addEventListener('submit', function(event) {
      event.preventDefault(); // Evita el envío real
      confirmacion.style.display = 'block'; // Muestra el mensaje
      form.reset(); // Limpia el formulario
    });
  </script>
</body>
</html>
