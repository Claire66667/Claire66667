<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rap Média</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-color: #1e1e1e;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            text-decoration: none;
            color: #ff5722;
            margin: 0 15px;
            font-size: 1.2em;
        }
        .container {
            padding: 20px;
        }
        .section-title {
            font-size: 1.8em;
            margin-bottom: 15px;
            border-bottom: 2px solid #ff5722;
            display: inline-block;
        }
        .articles, .artists {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .card {
            background-color: #1e1e1e;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .card img {
            width: 100%;
            height: auto;
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            margin: 0;
            font-size: 1.5em;
        }
        .card-content p {
            margin: 10px 0 0;
        }
        footer {
            background-color: #1e1e1e;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
            color: #bbb;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rap Média</h1>
        <nav>
            <a href="#">Accueil</a>
            <a href="#">Articles</a>
            <a href="#">Artistes</a>
            <a href="#">Contact</a>
        </nav>
    </header>
    <div class="container">
        <section>
            <h2 class="section-title">Articles récents</h2>
            <div class="articles">
                <div class="card">
                    <img src="https://via.placeholder.com/300x200" alt="Article 1">
                    <div class="card-content">
                        <h3>Interview exclusive avec XXX</h3>
                        <p>Découvrez les coulisses de son dernier album...</p>
                    </div>
                </div>
                <div class="card">
                    <img src="https://via.placeholder.com/300x200" alt="Article 2">
                    <div class="card-content">
                        <h3>Top 10 des albums de l'année</h3>
                        <p>Retour sur les projets qui ont marqué 2023...</p>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <h2 class="section-title">Artistes populaires</h2>
            <div class="artists">
                <div class="card">
                    <img src="https://via.placeholder.com/300x200" alt="Artiste 1">
                    <div class="card-content">
                        <h3>Nom de l'artiste</h3>
                        <p>Style, albums et actualités...</p>
                    </div>
                </div>
                <div class="card">
                    <img src="https://via.placeholder.com/300x200" alt="Artiste 2">
                    <div class="card-content">
                        <h3>Nom de l'artiste</h3>
                        <p>Style, albums et actualités...</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Rap Média. Tous droits réservés.</p>
    </footer>
</body>
</html>
