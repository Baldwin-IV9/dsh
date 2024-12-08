<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Diseño Profesional</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background-color: ##C0C0C0;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #020124, #020124);
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5em;
    }

    nav {
      text-align: center;
      background: #020124;
      padding: 10px 0;
    }

    nav ul {
      list-style-type: none;
    }

    nav ul li {
      display: inline;
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1.2em;
      font-family: 'Open Sans', sans-serif;
      font-weight: bold;
      position: relative; /* Necesario para posicionar la barra debajo */
      padding-bottom: 5px; /* Espacio para la barra */
      transition: color 0.3s ease; /* Transición para el cambio de color */
    }

    nav ul li a:hover {
      color: #f39c12; /* Color dorado al pasar el ratón */
    }

    /* Barra dorada que aparecerá debajo al hacer clic */
    nav ul li a::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 0%;
      height: 3px; /* Altura de la barra */
      background-color: #f39c12; /* Color dorado de la barra */
      transition: width 0.3s ease; /* Animación para que la barra se deslice */
    }

    /* Efecto al hacer clic: la barra se expande */
    nav ul li a:active::after {
      width: 100%; /* La barra se expande completamente */
    }

    .intro {
      background: url('https://cdn.discordapp.com/attachments/1283594013810888737/1315213083089698826/1000014694-removebg.png?ex=67569722&is=675545a2&hm=ab9ee9b187671287c8039ad01b1e1a1e7fc9a44e5167debc5adcc0228532909c&') no-repeat center center/cover;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    .intro h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    .intro p {
      font-size: 1.2em;
    }

    .services {
      display: flex;
      justify-content: space-around;
      margin: 40px 0;
    }

    .service-box {
      background: #ecf0f1;
      width: 30%;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .service-box img {
      width: 100px;
      margin-bottom: 20px;
    }

    .service-box h3 {
      margin-bottom: 10px;
    }

    .service-box p {
      color: #7f8c8d;
    }

    footer {
      background: #020124;
      color: white;
      text-align: center;
      padding: 20px;
      position: relative;
    }

    footer a {
      color: #f39c12;
      text-decoration: none;
    }

    footer a:hover {
      color: white;
    }

    @media (max-width: 768px) {
      .services {
        flex-direction: column;
        align-items: center;
      }

      .service-box {
        width: 80%;
        margin-bottom: 20px;
      }

      header h1 {
        font-size: 2em;
      }

      .intro h2 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Bienvenidos a Dark Star Hunters</h1>
  </header>

  <nav>
    <ul>
      <li><a href="https://darkstarhunters.tiiny.site/">🏠 Inicio</a></li>
      <li><a href="https://discord.gg/GQ8xJeZDpU">💬 Servidor</a></li>
      <li><a href="">🧊 Creditos</a></li>
      <li><a href="#">📗 Wiki</a></li>
    </ul>
  </nav>

  <section class="intro">
    <h2></h2>
    <p></p>
  </section>

  <section class="services">
    <div class="service-box">
      <img src="https://i.ibb.co/5sK7LNP/f80f1e1e401ce65ae98e86914c4dfbfb.jpg" alt="Servicio 1">
      <h3>Wiki Blox</h3>
      <p> Informacion sobre frutas, armas y razas de blox fruits.</p>
    </div>
    <div class="service-box">
      <img src="https://i.ibb.co/hDtZVRq/Background-Eraser-20241208-030609852.png" alt="Servicio 2">
      <h3>Servidor</h3>
      <p>En nuestro servidor de discord es donde reclamaras los sorteos y conviviras con los demas miembros.</p>
    </div>
    <div class="service-box">
      <img src="https://i.ibb.co/9cYXLFD/Background-Eraser-20241208-030246894.png" alt="Servicio 3">
      <h3>Sorteos</h3>
      <p>Sorteos frecuentes de frutas fisicas y permamentes.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2024. Todos los derechos reservados. "Dark Star Hunters"</p>
  </footer>

</body>
</html>
