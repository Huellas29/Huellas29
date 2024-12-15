<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Huellas en el Camino</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FEF5E7;
            color: #000;
        }

        header {
            background-color: #F8C471;
            text-align: center;
            padding: 20px;
        }

        header img {
            width: 120px;
            border-radius: 50%;
        }

        header h1 {
            margin: 10px 0;
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
        }

        nav {
            background-color: #FEF5E7;
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            margin: 0 15px;
            color: #000;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2em;
            color: #F8C471;
        }

        section p {
            font-size: 1.2em;
            margin: 15px 0;
        }

        .contacto, .donar {
            margin: 20px 0;
            padding: 10px 20px;
            background-color: #F8C471;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
        }

        .contacto:hover, .donar:hover {
            background-color: #d9905d;
        }

        footer {
            background-color: #F8C471;
            text-align: center;
            padding: 10px;
            color: #fff;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        iframe {
            margin-top: 20px;
            width: 80%;
            max-width: 600px;
            height: 300px;
            border: none;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            nav a {
                font-size: 1em;
            }

            section h2 {
                font-size: 1.5em;
            }

            section p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo de Huellas en el Camino">
        <h1>Huellas en el Camino</h1>
        <p>Pequeños Gestos, Grandes Cambios</p>
    </header>

    <nav>
        <a href="#sobre-nosotros">Sobre Nosotros</a>
        <a href="#contacto">Contacto</a>
        <a href="#donar">Dona Ahora</a>
    </nav>

    <section id="sobre-nosotros">
        <h2>¿Quiénes Somos?</h2>
        <p>Somos una fundación comprometida con mejorar la calidad de vida de los animales callejeros. A través de campañas educativas, rescates y servicios veterinarios, trabajamos para construir un futuro mejor para ellos.</p>
        <p>¡Tu apoyo marca la diferencia!</p>
    </section>

    <section id="video">
        <h2>Conoce Nuestro Trabajo</h2>
        <iframe src="https://www.youtube.com/embed/tu_video_intro" title="Video de Huellas en el Camino"></iframe>
    </section>

    <section id="contacto">
        <h2>Contáctanos</h2>
        <p>Teléfonos: 3144749214 / 3212479378</p>
        <p>Email: huellasenelcamino29@gmail.com</p>
        <p>Horario: Atención 24 horas</p>
        <button class="contacto" onclick="window.open('https://wa.me/573144749214', '_blank')">Habla con Nosotros</button>
    </section>

    <section id="donar">
        <h2>Apoya Nuestra Causa</h2>
        <p>Tu donación nos ayuda a continuar salvando vidas y generando conciencia.</p>
        <button class="donar" onclick="window.open('https://wa.me/573144749214', '_blank')">Dona Ahora</button>
    </section>

    <footer>
        <p>Síguenos en <a href="https://www.tiktok.com/@huellas_en_el_camino" target="_blank">TikTok</a></p>
        <p>&copy; 2024 Huellas en el Camino. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
