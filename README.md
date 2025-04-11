<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Werkzeug Shop für Handwerker - Empfohlene Werkzeuge mit Amazon Partnerprogramm">
    <title>Werkzeug Shop - Empfohlene Werkzeuge</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Werkzeug Shop</h1>
            <p>Empfohlene Werkzeuge für Handwerker und Heimwerker. Alle Links führen zu Amazon!</p>
        </div>
    </header>

    <section class="product-list">
        <div class="container">
            <h2>Top Empfohlene Werkzeuge</h2>

            <!-- Produkt 1 -->
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Akku-Bohrschrauber">
                <h3>Akku-Bohrschrauber</h3>
                <p>Ein vielseitiges Werkzeug für jede Werkstatt. Ideal für Bohr- und Schraubarbeiten.</p>
                <a href="https://www.amazon.de/dp/B08D6PWTZ8?tag=deinaffiliatecode" target="_blank">Jetzt bei Amazon kaufen</a>
            </div>

            <!-- Produkt 2 -->
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Winkelschleifer">
                <h3>Winkelschleifer</h3>
                <p>Perfekt für das Schleifen und Trennen von Materialien wie Metall und Stein.</p>
                <a href="https://www.amazon.de/dp/B08D6PWTZ8?tag=deinaffiliatecode" target="_blank">Jetzt bei Amazon kaufen</a>
            </div>

            <!-- Produkt 3 -->
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Bohrhammer">
                <h3>Bohrhammer</h3>
                <p>Unverzichtbar für das Bohren in Beton und Mauerwerk. Extrem leistungsstark.</p>
                <a href="https://www.amazon.de/dp/B08D6PWTZ8?tag=deinaffiliatecode" target="_blank">Jetzt bei Amazon kaufen</a>
            </div>

        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Werkzeug Shop - Alle Links sind Affiliate-Links zu Amazon. Wir erhalten eine kleine Provision, wenn du über diese Links einkaufst.</p>
        </div>
    </footer>
</body>
</html>
/* Allgemeine Einstellungen */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

/* Werkzeuge Abschnitt */
.tools {
    background-color: white;
    padding: 20px 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

.tool {
    background-color: #fff;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    display: inline-block;
    width: 30%;
    margin-right: 3%;
    text-align: center;
}

.tool img {
    max-width: 100%;
    height: auto;
}

.tool h3 {
    font-size: 1.5em;
    margin-top: 10px;
}

.tool p {
    font-size: 1em;
    margin: 10px 0;
}

.tool a {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #5cb85c;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.tool a:hover {
    background-color: #4cae4c;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

footer p {
    font-size: 1em;
}

