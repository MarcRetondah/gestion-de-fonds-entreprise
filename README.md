<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Votre Entreprise - Produits Dérivés</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <a class="navbar-brand" href="#">Votre Entreprise</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#accueil">Accueil</a></li>
                <li class="nav-item"><a class="nav-link" href="#services">Nos Services</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Accueil -->
    <header class="bg-primary text-white text-center">
        <div class="container">
            <h1 class="display-4">Votre Entreprise</h1>
            <p class="lead">Gestion de Produits Dérivés à La Défense, Paris</p>
        </div>
    </header>

    <!-- Nos Services -->
    <section id="services" class="py-5">
        <div class="container">
            <h2 class="text-center">Nos Services</h2>
            <div class="row">
                <div class="col-lg-4">
                    <div class="card mb-5 mb-lg-0">
                        <img class="card-img-top" src="image1.jpg" alt="Image Service 1">
                        <div class="card-body">
                            <h5 class="card-title">Gestion de Portefeuille</h5>
                            <p class="card-text">Description du service de gestion de portefeuille.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="card mb-5 mb-lg-0">
                        <img class="card-img-top" src="image2.jpg" alt="Image Service 2">
                        <div class="card-body">
                            <h5 class="card-title">Conseil en Investissement</h5>
                            <p class="card-text">Description du service de conseil en investissement.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="card">
                        <img class="card-img-top" src="image3.jpg" alt="Image Service 3">
                        <div class="card-body">
                            <h5 class="card-title">Analyses Financières</h5>
                            <p class="card-text">Description du service d'analyses financières.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center">Contactez-nous</h2>
            <div class="row">
                <div class="col-md-4">
                    <p>Adresse: La Défense, Paris</p>
                </div>
                <div class="col-md-4">
                    <p>Email: contact@votre-entreprise.com</p>
                </div>
                <div class="col-md-4">
                    <p>Téléphone: +XX XXXX XXXX</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-4 bg-dark text-white text-center">
        <div class="container">
            <p>&copy; 2024 Votre Entreprise - Produits Dérivés</p>
        </div>
    </footer>

    <!-- Bootstrap JS, Popper.js, and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    padding: 150px 0;
}

.card {
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

#contact {
    padding: 80px 0;
}

footer {
    padding: 20px 0;
}
