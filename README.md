<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hackers Academy</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">

  <style>
    body {
      background-color: #000;
      color: #0f0;
      font-family: "Courier New", monospace;
    }

    .navbar {
      background-color: #000 !important;
      border-bottom: 2px solid #0f0;
    }

    .nav-link, .navbar-brand {
      color: #0f0 !important;
    }

    .nav-link:hover {
      color: #7CFC00 !important;
    }

    .btn-hacker {
      background-color: #0f0;
      color: #000;
      font-weight: bold;
    }

    .carousel-caption h2 {
      text-shadow: 0 0 10px #000;
      font-weight: bold;
    }

    .card {
      background-color: #111;
      border: 1px solid #0f0;
      color: #0f0;
    }

    .card img {
      height: 200px;
      object-fit: cover;
    }

    footer {
      background-color: #000;
      border-top: 2px solid #0f0;
    }

    input, textarea {
      background-color: #111 !important;
      border: 1px solid #0f0 !important;
      color: #0f0 !important;
    }
  </style>
</head>

<body data-spy="scroll" data-target="#navbar">

<!-- NAVBAR -->
<nav id="navbar" class="navbar navbar-expand-lg navbar-dark fixed-top">
  <a class="navbar-brand font-weight-bold" href="#">HACKERS ACADEMY</a>

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#menu">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="menu">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item"><a class="nav-link" href="#Home">INICIO</a></li>
      <li class="nav-item"><a class="nav-link" href="#Services">SERVICES</a></li>
      <li class="nav-item"><a class="nav-link" href="#Team">OUR TEAM</a></li>
      <li class="nav-item"><a class="nav-link" href="#Contact">CONTACT</a></li>
      <li class="nav-item">
        <a class="btn btn-hacker ml-3" href="#Join">JOIN US</a>
      </li>
    </ul>
  </div>
</nav>

<!-- CAROUSEL -->
<div id="Home" class="carousel slide mt-5" data-ride="carousel">

  <ol class="carousel-indicators">
    <li data-target="#Home" data-slide-to="0" class="active"></li>
    <li data-target="#Home" data-slide-to="1"></li>
    <li data-target="#Home" data-slide-to="2"></li>
  </ol>

  <div class="carousel-inner">

    <div class="carousel-item active">
      <img src="imagen1.jpg" class="d-block w-100">
      <div class="carousel-caption">
        <h2>Bienvenido a la Ruta Hacker</h2>
        <p>Aprende ciberseguridad desde cero</p>
        <a class="btn btn-hacker" href="#">Iniciar Ruta Hacker</a>
      </div>
    </div>

    <div class="carousel-item">
      <img src="imagen16.webp" class="d-block w-100">
      <div class="carousel-caption">
        <h2>Domina el Pentesting</h2>
        <p>Conviértete en un experto en ataques reales</p>
        <a class="btn btn-hacker" href="#">Aprender más</a>
      </div>
    </div>

    <div class="carousel-item">
      <img src="imagen3.jpg" class="d-block w-100">
      <div class="carousel-caption">
        <h2>Ciberseguridad Profesional</h2>
        <p>Forma parte de la élite digital</p>
        <a class="btn btn-hacker" href="#">Unirme</a>
      </div>
    </div>

  </div>

  <a class="carousel-control-prev" href="#Home" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#Home" role="button" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>

</div>

<!-- SERVICES -->
<section id="Services" class="container py-5">
  <h2 class="text-center mb-4">SERVICES</h2>

  <div class="card-deck">

    <div class="card">
      <img src="imagen4.jpg">
      <div class="card-body">
        <h5>Ethical Hacking</h5>
        <p>Aprende a vulnerar sistemas legalmente.</p>
        <a class="btn btn-hacker">Ingresar</a>
      </div>
    </div>

    <div class="card">
      <img src="imagen15.jpg">
      <div class="card-body">
        <h5>Pentesting Avanzado</h5>
        <p>Simulaciones de ataques reales.</p>
        <a class="btn btn-hacker">Ingresar</a>
      </div>
    </div>

    <div class="card">
      <img src="imagen6.jpg">
      <div class="card-body">
        <h5>Análisis Forense</h5>
        <p>Recupera y analiza evidencias digitales.</p>
        <a class="btn btn-hacker">Ingresar</a>
      </div>
    </div>

    <div class="card">
      <img src="imagen7 (2).jpg">
      <div class="card-body">
        <h5>OSINT</h5>
        <p>Investigación con información pública.</p>
        <a class="btn btn-hacker">Ingresar</a>
      </div>
    </div>

  </div>

  <div class="card-deck mt-4">

    <div class="card">
      <img src="imagen8 (2).jpg">
      <div class="card-body">
        <h5>Red Team</h5>
        <p>Ataques avanzados para evaluar defensas reales.</p>
        <a class="btn btn-hacker">Ingresar</a>
      </div>
    </div>

    <div class="card">
      <img src="imagen13.jpg">
      <div class="card-body">
        <h5>Seguridad Web</h5>
        <p>Protege aplicaciones web de vulnerabilidades críticas.</p>
        <a class="btn btn-hacker">Ingresar</a>
      </div>
    </div>

  </div>

</section>

<!-- TEAM -->
<section id="Team" class="container py-5">
  <h2 class="text-center mb-4">OUR TEAM</h2>

  <div class="card-deck">

    <div class="card">
      <img src="imagen10.jpg">
      <div class="card-body">
        <h5>ShadowFox</h5>
        <p>Pentester – “No existe sistema impenetrable”.</p>
      </div>
    </div>

    <div class="card">
      <img src="imagen11.jpg">
      <div class="card-body">
        <h5>ZeroDayHunter</h5>
        <p>Malware Engineer – “El código es mi arma”.</p>
      </div>
    </div>

    <div class="card">
      <img src="imagen14.jpg">
      <div class="card-body">
        <h5>RoninByte</h5>
        <p>Analista SOC – “Vigilo la red mientras duermes”.</p>
      </div>
    </div>

  </div>
</section>

<!-- CONTACT -->
<!-- CONTACT -->
<section id="Contact" class="container py-5">
  <h2 class="text-center mb-4">JOIN US / CONTACT</h2>

  <div class="row">

    <!-- COLUMNA DEL FORMULARIO -->
    <div class="col-md-6">
      <form>

        <div class="form-group">
          <label>Nombre</label>
          <input type="text" class="form-control" required>
        </div>

        <div class="form-group">
          <label>Correo</label>
          <input type="email" class="form-control" required>
        </div>

        <div class="form-group">
          <label>Mensaje</label>
          <textarea class="form-control" rows="4" required></textarea>
        </div>

        <button class="btn btn-hacker btn-block">Enviar</button>

      </form>
    </div>

    <!-- COLUMNA DEL MAPA -->
    <div class="col-md-6">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3900.9156040065547!2d-77.04279372518739!3d-12.127799688107438!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9105c82f1b55e4ed%3A0x27a21ad508ba3c8c!2sMiraflores%2C%20Lima!5e0!3m2!1ses!2spe!4v1708734023456!5m2!1ses!2spe" 
        width="100%" 
        height="350" 
        style="border:2px solid #0f0; border-radius: 6px;" 
        allowfullscreen=""
        loading="lazy">
      </iframe>
    </div>

  </div>
</section>


<!-- FOOTER -->
<footer class="text-center text-light py-4">
  <p class="mb-2">© 2025 Hackers Academy — Derechos reservados</p>

  <div>
    <a class="text-light mx-3" href="#"><i class="bi bi-github"></i></a>
    <a class="text-light mx-3" href="#"><i class="bi bi-youtube"></i></a>
    <a class="text-light mx-3" href="#"><i class="bi bi-linkedin"></i></a>
  </div>
</footer>

<!-- JS -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

<script>
  $('.carousel').carousel({
    interval: 2500,
    ride: "carousel"
  });
</script>

</body>
</html>
