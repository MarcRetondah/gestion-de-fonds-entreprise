<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Votre Entreprise - Produits Dérivés</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Navbar -->
    <nav>
        <div class="logo">Votre Entreprise</div>
        <ul>
            <li><a href="#accueil">Accueil</a></li>
            <li><a href="#services">Nos Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Accueil -->
    <header>
        <div class="hero">
            <h1>Votre Entreprise</h1>
            <p>Gestion de Produits Dérivés à La Défense, Paris</p>
        </div>
    </header>

    <!-- Nos Services -->
    <section id="services">
        <div class="services-container">
            <div class="service">
                <h3>Gestion de Portefeuille</h3>
                <p>Description du service de gestion de portefeuille.</p>
            </div>
            <div class="service">
                <h3>Conseil en Investissement</h3>
                <p>Description du service de conseil en investissement.</p>
            </div>
            <div class="service">
                <h3>Analyses Financières</h3>
                <p>Description du service d'analyses financières.</p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contactez-nous</h2>
        <p>Adresse: La Défense, Paris</p>
        <p>Email: contact@votre-entreprise.com</p>
        <p>Téléphone: +XX XXXX XXXX</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Votre Entreprise - Produits Dérivés</p>
    </footer>

</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

nav {
    background-color: #333;
    color: #fff;
    padding: 1em;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

header {
    background-color: #0077cc;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.hero h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

.services-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 50px 0;
}

.service {
    max-width: 300px;
    margin: 20px;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}
