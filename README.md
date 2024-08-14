<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Page Web Personnelle</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            color: #00008b;
            text-align: center;
        }
        header {
            background-color: #4682b4;
            padding: 20px;
            color: white;
            text-shadow: 2px 2px #000;
        }
        nav {
            margin: 20px;
        }
        nav a {
            color: #00008b;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.2em;
        }
        section {
            margin: 20px;
            padding: 20px;
            border: 2px dashed #87cefa;
            background-color: #e6e6fa;
        }
        .socials {
            margin: 20px 0;
        }
        .socials img {
            width: 50px;
            height: 50px;
            margin: 0 10px;
            vertical-align: middle;
        }
        footer {
            background-color: #4682b4;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-shadow: 1px 1px #000;
        }
        .project {
            font-weight: bold;
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenue sur ma page web personnelle !</h1>
    </header>

    <nav>
        <a href="#projets">Projets</a>
        <a href="#reseaux">Réseaux Sociaux</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="projets">
        <h2>Mes Projets</h2>
        <p class="project">Streaming</p>
        <p>Je suis passionné par le streaming et je travaille actuellement à développer ma communauté en ligne. Je partage mes expériences, jeux et discussions intéressantes sur ma chaîne de streaming.</p>
        <p class="project">Musique</p>
        <p>En parallèle, je poursuis un projet dans la musique avec l'objectif de créer et partager mes compositions originales avec le monde.</p>
    </section>

    <section id="reseaux">
        <h2>Réseaux Sociaux</h2>
        <div class="socials">
            <a href="https://www.twitch.tv/nocysolo" target="_blank">
                <img src="https://www.iconfinder.com/icons/1532556/download/png/64" alt="Twitch">
            </a>
            <a href="https://www.youtube.com/@nocy_solo" target="_blank">
                <img src="https://www.iconfinder.com/icons/1218731/download/png/64" alt="YouTube">
            </a>
            <a href="https://www.instagram.com/nocy_solo" target="_blank">
                <img src="https://www.iconfinder.com/icons/1532569/download/png/64" alt="Instagram">
            </a>
        </div>
    <footer>
        <p>&copy; 2024 Nocy</p>
    </footer>

</body>
</html>
