<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Pro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            margin: 15px 0;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .card img {
            max-width: 100%;
            border-radius: 8px;
        }
        .card h3 {
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gym Pro</h1>
        <p>Tu fuente de contenido fitness</p>
    </header>
    <nav>
        <a href="#home">Inicio</a>
        <a href="#workouts">Entrenamientos</a>
        <a href="#nutrition">Nutrición</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <section id="home">
            <div class="card">
                <img src="path/to/your/image.jpg" alt="Entrenamiento">
                <h3>Rutinas de entrenamiento</h3>
                <p>Encuentra las mejores rutinas de entrenamiento para todos los niveles.</p>
            </div>
        </section>
        <section id="workouts">
            <div class="card">
                <img src="path/to/your/image2.jpg" alt="Nutrición">
                <h3>Planes de nutrición</h3>
                <p>Descubre planes de nutrición adaptados a tus objetivos.</p>
            </div>
        </section>
        <section id="nutrition">
            <div class="card">
                <img src="path/to/your/image3.jpg" alt="Contacto">
                <h3>Consejos de expertos</h3>
                <p>Lee artículos y consejos de expertos en fitness y nutrición.</p>
            </div>
        </section>
        <section id="contact">
            <div class="card">
                <h3>Contacto</h3>
                <p>Puedes contactarnos a través de nuestras redes sociales o por correo electrónico.</p>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Gym Pro. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
