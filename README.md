# PAG1
git clone https://github.com/JMCZ3008/JMCZ3008.github.io.git
cd JMCZ3008.github.io
git add .
git commit -m "Añadir página personal"

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #34495e;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            margin: 10px;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .green {
            background-color: #27ae60;
        }
        .blue {
            background-color: #2980b9;
        }
        .black {
            background-color: #2c3e50;
        }
        .card {
            background-color: white;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
            padding: 20px;
            margin: 10px 0;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenidos a Mi Página Personal</h1>
    </header>

    <nav>
        <a href="#sobre-mi">Sobre Mí</a>
        <a href="#blog">Blog</a>
        <a href="#recetas">Recetas</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="sobre-mi">
        <div class="card green">
            <h2>Sobre Mí</h2>
            <p>Aquí puedes agregar una breve biografía o descripción sobre ti mismo. Incluye información sobre tus intereses, tu carrera y cualquier otra cosa que te gustaría compartir.</p>
        </div>
    </section>

    <section id="blog">
        <div class="card blue">
            <h2>Blog</h2>
            <p>Aquí puedes compartir tus pensamientos y experiencias. Agrega tus artículos de blog con títulos, fechas y contenido.</p>
        </div>
    </section>

    <section id="recetas">
        <div class="card green">
            <h2>Recetas</h2>
            <p>Comparte tus platillos y recetas favoritas. Puedes agregar imágenes y descripciones de cada platillo.</p>
        </div>
    </section>

    <section id="proyectos">
        <div class="card blue">
            <h2>Proyectos</h2>
            <p>Describe tus proyectos y trabajos. Puedes agregar imágenes, descripciones y enlaces a tus proyectos.</p>
        </div>
    </section>

    <section id="contacto">
        <div class="card green">
            <h2>Contacto</h2>
            <p>Conéctate conmigo a través de mis redes sociales:</p>
            <ul>
                <li><a href="https://www.facebook.com" target="_blank">Facebook</a></li>
                <li><a href="https://www.twitter.com" target="_blank">Twitter</a></li>
                <li><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></li>
                <li><a href="https://www.instagram.com" target="_blank">Instagram</a></li>
            </ul>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Mi Página Personal. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
git push origin main

