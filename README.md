<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turismo Mágico - Descubre el Mundo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to right, #000000, #1a1a1a);
            color: #dcdcdc;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .navbar {
            background-color: #000;
        }
        .navbar-brand, .nav-link {
            color: #ffd700 !important;
            font-weight: bold;
        }
        .section-title {
            color: #ffd700;
            text-shadow: 1px 1px 2px #888;
        }
        .highlight {
            color: #c0c0c0;
        }
        .tour-card {
            background-color: #1e1e1e;
            border: 1px solid #333;
            transition: transform 0.3s;
        }
        .tour-card:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #111;
            padding: 20px;
            text-align: center;
            color: #aaa;
        }
        .testimonial {
            background-color: #2a2a2a;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Turismo Mágico</a>
            <div class="collapse navbar-collapse">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link" href="#inicio">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#destinos">Destinos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#paquetes">Paquetes</a></li>
                    <li class="nav-item"><a class="nav-link" href="#galeria">Galería</a></li>
                    <li class="nav-item"><a class="nav-link" href="#testimonios">Testimonios</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section id="inicio" class="container mt-5">
        <h1 class="section-title text-center mb-4 animate__animated animate__fadeInDown">Bienvenido a Turismo Mágico</h1>
        <p class="lead text-center highlight animate__animated animate__fadeInUp">Descubre los rincones más maravillosos del planeta con experiencias personalizadas, cómodas y memorables. Conectamos a los viajeros con culturas vibrantes, paisajes increíbles y aventuras inolvidables. Nuestra misión es ayudarte a explorar el mundo con total seguridad, confianza y diversión.</p>
        <div class="text-center">
            <img src="paisaje.avif" width="400px">
        </div>
    </section>

    <section id="destinos" class="container mt-5">
        <h2 class="section-title mb-4">Destinos Destacados</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card tour-card h-100">
                    <img src="torre.webp" width="300px" >
                    <div class="card-body">
                        <h5 class="card-title text-warning">París, Francia</h5>
                        <p class="card-text highlight">Explora la ciudad del amor con recorridos por la Torre Eiffel, el Louvre, y paseos por el Sena.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card tour-card h-100">
                    <img src="tokio.avif" width="400px">
                    <div class="card-body">
                        <h5 class="card-title text-warning">Tokio, Japón</h5>
                        <p class="card-text highlight">Sumérgete en una metrópolis futurista llena de tradición, tecnología, y delicias gastronómicas.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card tour-card h-100">
                    <img src="machu pichu.jpg" width="400px">
                    <div class="card-body">
                        <h5 class="card-title text-warning">Machu Picchu, Perú</h5>
                        <p class="card-text highlight">Recorre las antiguas ruinas incas en un viaje místico a través de la historia y la naturaleza.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="galeria" class="container mt-5">
        <h2 class="section-title mb-4">Galería de Experiencias</h2>
        <div class="row gallery">
            <div class="col-md-4">
                <img src="playa.jpg">
                <img src="montañas.avif">
            </div>
            <div class="col-md-4">
                <img src="Ciudades.jpg">
                <img src="bosque.jpg">
            </div>
            <div class="col-md-4">
                <img src="desierto.webp">
                <img src="lago.jpg">
            </div>
        </div>
    </section>

    <section id="testimonios" class="container mt-5">
        <h2 class="section-title mb-4">Testimonios de Viajeros</h2>
        <div class="testimonial">
            <p class="highlight">“Una experiencia inolvidable, atención de primera clase y destinos de ensueño. ¡Recomiendo totalmente a Turismo Mágico!”</p>
            <small>- Laura Gómez, México</small>
        </div>
        <div class="testimonial">
            <p class="highlight">“Viajar con Turismo Mágico fue una de las mejores decisiones. Me sentí segura, feliz y descubrí lugares que siempre soñé.”</p>
            <small>- Daniel Ruiz, Colombia</small>
        </div>
        <div class="testimonial">
            <p class="highlight">“Excelente organización, guías profesionales y una atención personalizada impresionante.”</p>
            <small>- Mariana Silva, Argentina</small>
        </div>
    </section>

    <section id="contacto" class="container mt-5 mb-5">
        <h2 class="section-title mb-4">Contáctanos</h2>
        <div class="row">
            <div class="col-md-6">
                <form>
                    <div class="mb-3">
                        <label for="nombre" class="form-label">Nombre</label>
                        <input type="text" class="form-control" id="nombre">
                    </div>
                    <div class="mb-3">
                        <label for="correo" class="form-label">Correo Electrónico</label>
                        <input type="email" class="form-control" id="correo">
                    </div>
                    <div class="mb-3">
                        <label for="mensaje" class="form-label">Mensaje</label>
                        <textarea class="form-control" id="mensaje" rows="4"></textarea>
                    </div>
                    <button type="submit" class="btn btn-warning">Enviar</button>
                </form>
            </div>
            <div class="col-md-6">
                <img src="vacaciones.webp" width="400px">
                <p class="mt-3 highlight">Síguenos en nuestras redes sociales para promociones, consejos y más aventuras.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 Turismo Mágico | Todos los derechos reservados | contact@turismomagico.com</p>
    </footer>

</body>
</html>
