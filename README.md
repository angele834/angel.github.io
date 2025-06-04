<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Municipio de Tekit, Yucatán</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #0e4d92;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #064374;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    section {
      padding: 20px;
    }

    .imagenes, .videos {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .imagenes img, .videos iframe {
      width: 100%;
      max-width: 300px;
      height: auto;
      border-radius: 10px;
    }

    footer {
      background-color: #0e4d92;
      color: white;
      text-align: center;
      padding: 15px;
    }

    @media (min-width: 600px) {
      .imagenes img, .videos iframe {
        max-width: 45%;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Bienvenidos a Tekit, Yucatán</h1>
  <p>La capital de la guayabera y tradición viva del Mayab</p>
</header>

<nav>
  <a href="#historia">Historia</a>
  <a href="#galeria">Galería</a>
  <a href="#video">Videos</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="historia">
  <h2>Historia de Tekit</h2>
  <p>
    Tekit es un municipio del estado de Yucatán conocido por su producción de guayaberas. Con raíces mayas profundas, su historia se remonta a tiempos prehispánicos. El nombre Tekit significa “Lugar de los regalos” en maya. Hoy en día, se distingue por su cultura, sus fiestas tradicionales y su gente trabajadora.
  </p>
</section>

<section id="galeria">
  <h2>Galería de Imágenes</h2>
  <div class="imagenes">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Iglesia_de_Tekit%2C_Yucat%C3%A1n.jpg" alt="Iglesia de Tekit">
    <img src="https://yucatanahora.mx/wp-content/uploads/2019/01/guayaberas-tekit.jpg" alt="Guayaberas en Tekit">
  </div>
</section>

<section id="video">
  <h2>Videos sobre Tekit</h2>
  <div class="videos">
    <iframe width="300" height="200" src="https://www.youtube.com/embed/89A5ceCz9Sg" title="Video de Tekit" frameborder="0" allowfullscreen></iframe>
    <iframe width="300" height="200" src="https://www.youtube.com/embed/z7ZZsZd3SDA" title="Fiestas en Tekit" frameborder="0" allowfullscreen></iframe>
  </div>
</section>

<section id="contacto">
  <h2>Contacto del Ayuntamiento</h2>
  <p>
    Dirección: Calle 20 x 27 y 29, Tekit, Yucatán, México<br>
    Teléfono: (999) 123-4567<br>
    Correo: info@tekit.gob.mx<br>
    Horario: Lunes a Viernes, 8:00 AM - 3:00 PM
  </p>
</section>

<footer>
  <p>&copy; 2025 Ayuntamiento de Tekit, Yucatán | Todos los derechos reservados</p>
</footer>

</body>
</html>
