<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Space World | Explorando el Universo</title> 
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      color: white;
      background: radial-gradient(circle at bottom, #0d0d2b, #000);
      background-image: url('https://images.unsplash.com/photo-1446776811953-b23d57bd21aa?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80');
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
    }

    header {
      background-color: rgba(0, 0, 51, 0.8);
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #00f0ff;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      color: #00f0ff;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 10px 0;
    }

    nav a {
      color: #00f0ff;
      margin: 0 20px;
      text-decoration: none;
      font-size: 1.2rem;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffffff;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: rgba(0, 0, 0, 0.5);
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.3rem;
      max-width: 700px;
      margin: auto;
    }

    .section {
      padding: 60px 20px;
      background-color: rgba(0, 0, 51, 0.7);
      margin: 20px;
      border-radius: 12px;
    }

    .section h3 {
      font-size: 2rem;
      color: #00f0ff;
    }

    .section p {
      font-size: 1.1rem;
      line-height: 1.8;
    }

    footer {
      background-color: #000020;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <header>
    <h1>SPACE WORLD</h1>
  </header>

  <nav>
    <a href="#empresa">La Empresa</a>
    <a href="#cohetes">Cohetes</a>
    <a href="#ingenieria">Ingeniería Aeroespacial</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <div class="hero">
    <h2>Explora el futuro desde las estrellas</h2>
    <p>Space World es líder en tecnología espacial, diseño de cohetes y sistemas de propulsión para misiones fuera del planeta. Bienvenido al futuro de la exploración aeroespacial.</p>
  </div>

  <section class="section" id="empresa">
    <h3>What do we do</h3>
    <p>This personal project was founded in 2020 and serves as a Wikipedia-like source of information that combines passion, science, and technology to create innovative space exploration solutions. Our mission is to open up the universe to humanity through the development of reusable rockets, orbital stations, and interplanetary platforms.</p>
  </section>

  <section class="section" id="cohetes">
    <h3>Cohetes de Nueva Generación</h3>
    <p>Desde nuestros laboratorios de ingeniería, desarrollamos cohetes con motores iónicos, propulsión nuclear y sistemas de aterrizaje automático. Cada lanzamiento representa un paso hacia una civilización multiplanetaria.</p>
  </section>

  <section class="section" id="ingenieria">
    <h3>Ingeniería Aeroespacial</h3>
    <p>Colaboramos con universidades, agencias espaciales y empresas tecnológicas para liderar la ingeniería aeroespacial del siglo XXI. Nuestro enfoque incluye robótica, materiales inteligentes y navegación interplanetaria.</p>
  </section>

  <section class="section" id="contacto">
    <h3>Contacto</h3>
    <p>Si compartes nuestra visión y quieres colaborar o trabajar con nosotros, escríbenos a <a href="mailto:info@spaceworld.com" style="color:#00f0ff;">info@spaceworld.com</a>.</p>
  </section>

  <footer>
    &copy; 2045 Space World. Todos los derechos reservados.
  </footer>
</body>
</html>
