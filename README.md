<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S.E.D. | Services Events Decorations</title>
    <link rel="stylesheet" href="Styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
</head>
<body>
    <header class="header">
        <div class="header-container">
            <div class="logo-nav">
                <img src="Imj/iCono/ICONO.png" alt="S.E.D Logo" class="logo-img">
                <button class="menu-toggle" aria-label="Menú">
                    <i class="fas fa-bars"></i>
                </button>
                <nav class="nav">
                    <a href="index.html" class="nav-link">Inicio</a>
                    <a href="coleccion.html" class="nav-link">Colección</a>
                    <a href="experiencia.html" class="nav-link">Experiencia</a>
                    <a href="about us.html" class="nav-link">Nosotros</a>
                    <a href="search.html" class="nav-link search-link">Buscar...</a>
                </nav>
            </div>
        </div>
        <!-- Navegación móvil -->
        <nav class="nav-mobile">
            <a href="index.html" class="nav-link">Inicio</a>
            <a href="coleccion.html" class="nav-link">Colección</a>
            <a href="experiencia.html" class="nav-link">Experiencia</a>
            <a href="about us.html" class="nav-link">Nosotros</a>
            <a href="search.html" class="nav-link">Buscar...</a>
        </nav>
    </header>

    <!-- Sidebar de Búsqueda -->
    <div id="search-sidebar" class="search-sidebar">
        <div class="search-content">
            <button class="close-search" onclick="closeSearch()">×</button>
            <div class="search-container">
                <input type="text" id="searchInput" placeholder="Buscar en S.E.D..." class="search-input">
                <button class="search-button" onclick="performSearch()">
                    <i class="fas fa-search"></i>
                </button>
            </div>
            <div class="recent-searches">
                <h3>Búsquedas recientes</h3>
                <div class="search-tags">
                    <span class="tag">Bodas</span>
                    <span class="tag">Eventos Corporativos</span>
                    <span class="tag">Decoración Floral</span>
                </div>
            </div>
            <div id="searchResults" class="search-results">
                <!-- Los resultados se mostrarán aquí -->
            </div>
        </div>
    </div>

    <main>
        <section id="hero" class="hero">
            <div class="hero-slider">
                <div class="slide active">
                    <video autoplay muted loop playsinline>
                        <source src="videos/1.mp4" type="video/mp4">
                        Tu navegador no soporta el elemento de video.
                    </video>
                </div>
                <div class="slide">
                    <video autoplay muted loop playsinline>
                        <source src="videos/2.mp4" type="video/mp4">
                        Tu navegador no soporta el elemento de video.
                    </video>
                </div>
                <div class="slide">
                    <video autoplay muted loop playsinline>
                        <source src="videos/61068ce77db4479fffbfefed7a2c28ea.mp4" type="video/mp4">
                        Tu navegador no soporta el elemento de video.
                    </video>
                </div>
            </div>
            <div class="hero-content">
                <h1>ELEGANCIA EN CADA DETALLE</h1>
                <p>Transformamos espacios en experiencias inolvidables</p>
            </div>
        </section>

        <section id="servicios" class="services">
            <h2>Nuestros Servicios</h2>
            <div class="services-grid">
                <div class="service-card">
                    <img src="Imj/boda.jpg" alt="Bodas">
                    <h3>Bodas</h3>
                    <p>Creamos el día perfecto para tu historia de amor</p>
                </div>
                <div class="service-card">
                    <img src="Imj/corporativo.jpg" alt="Eventos Corporativos">
                    <h3>Eventos Corporativos</h3>
                    <p>Impulsa tu marca con eventos memorables</p>
                </div>
                <div class="service-card">
                    <img src="Imj/tematica.jpg" alt="Fiestas Temáticas">
                    <h3>Fiestas Temáticas</h3>
                    <p>Diseños únicos para momentos especiales</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="footer-content">
            <div class="footer-section">
                <h3>S.E.D</h3>
                <p>Transformamos espacios en experiencias inolvidables desde 2021</p>
            </div>
            <div class="footer-section">
                <h3>Síguenos</h3>
                <div class="social-links">
                    <a href="https://www.instagram.com/service.e.d?igsh=ZzZ3NmQ3emlidTFx" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="https://web.facebook.com/profile.php?id=61572442831216" target="_blank"><i class="fab fa-facebook"></i></a>
                    <a href="https://www.tiktok.com/@s.e.d.decorations0" target="_blank"><i class="fab fa-tiktok"></i></a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2024 S.E.D. Todos los derechos reservados.</p>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script src="js/menu.js"></script>
    <script src="js/search.js"></script>
    <script src="js/slider.js"></script>
</body>
</html>
