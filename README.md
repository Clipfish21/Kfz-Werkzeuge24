<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kfz Werkzeug & Zubehör</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background: url('https://cdn.pixabay.com/photo/2016/11/21/15/47/auto-1845650_1280.jpg') no-repeat center center fixed;
      background-size: cover;
    }
    .overlay {
      background-color: rgba(255, 255, 255, 0.85);
    }
    .primary-blue { background-color: #004c97; }
    .primary-blue-dark { background-color: #003b78; }
    .category-card:hover { transform: scale(1.02); transition: transform 0.2s ease-in-out; }
  </style>
</head>
<body class="text-gray-900">
  <div class="overlay">
    <!-- Header -->
    <header class="primary-blue text-white shadow-md sticky top-0 z-50">
      <div class="container mx-auto flex justify-between items-center p-4">
        <h1 class="text-2xl font-bold uppercase">Kfz Werkzeug & Zubehör</h1>
        <nav class="space-x-4">
          <a href="#start" class="hover:underline">Start</a>
          <a href="#produkte" class="hover:underline">Produkte</a>
          <a href="#kategorien" class="hover:underline">Kategorien</a>
          <a href="#kontakt" class="hover:underline">Kontakt</a>
        </nav>
      </div>
    </header>

    <!-- Hero -->
    <section id="start" class="text-center py-20">
      <h2 class="text-4xl font-bold mb-4">Professionelle Kfz-Teile & Werkzeuge</h2>
      <p class="mb-6">Top Qualität für Werkstatt und Hobby.</p>
      <a href="#produkte" class="bg-blue-600 text-white px-6 py-3 rounded hover:bg-blue-700">Jetzt entdecken</a>
    </section>

    <!-- Kategorien -->
    <section id="kategorien" class="py-16 bg-gray-100 bg-opacity-90">
      <div class="container mx-auto">
        <h3 class="text-3xl font-bold text-center mb-10">Unsere Kategorien</h3>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
          <div class="bg-white p-6 rounded shadow category-card">
            <h4 class="text-xl font-semibold mb-2">Diagnosegeräte</h4>
            <p>Professionelle Geräte zur Fahrzeugdiagnose für alle Marken.</p>
          </div>
          <div class="bg-white p-6 rounded shadow category-card">
            <h4 class="text-xl font-semibold mb-2">Spezialwerkzeuge für VAG</h4>
            <p>Herstellerspezifisches Werkzeug für VW, Audi, Seat, Skoda.</p>
          </div>
          <div class="bg-white p-6 rounded shadow category-card">
            <h4 class="text-xl font-semibold mb-2">BMW Spezialwerkzeug</h4>
            <p>Werkzeuglösungen für alle BMW Motoren und Baureihen.</p>
          </div>
          <div class="bg-white p-6 rounded shadow category-card">
            <h4 class="text-xl font-semibold mb-2">Audi Spezialwerkzeug</h4>
            <p>Präzisionswerkzeug für Audi Fahrzeuge – auch für neue Modelle.</p>
          </div>
          <div class="bg-white p-6 rounded shadow category-card">
            <h4 class="text-xl font-semibold mb-2">Werkstattzubehör</h4>
            <p>Alles von Werkzeugwagen über Wagenheber bis Ladegeräte.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Beispiel-Produkte -->
    <section id="produkte" class="py-16">
      <div class="container mx-auto">
        <h3 class="text-3xl font-bold text-center mb-10">Empfohlene Produkte</h3>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-gray-50 p-6 rounded shadow text-center">
            <img src="https://m.media-amazon.com/images/I/81x2yS9lJNL._AC_SL1500_.jpg" alt="Werkzeugkiste" class="w-full h-48 object-contain mb-4">
            <h4 class="text-lg font-bold mb-2">Stanley Werkzeugkiste</h4>
            <p class="mb-3 text-sm">Robuste Werkzeugbox mit extra viel Stauraum.</p>
            <a href="https://www.amazon.de/dp/B001GQ2RWU?tag=dein-affiliate-id" target="_blank" class="text-blue-600 hover:underline">Jetzt kaufen</a>
          </div>
          <div class="bg-gray-50 p-6 rounded shadow text-center">
            <img src="https://m.media-amazon.com/images/I/71H97HzexPL._AC_SL1500_.jpg" alt="Batterieladegerät" class="w-full h-48 object-contain mb-4">
            <h4 class="text-lg font-bold mb-2">NOCO Genius Batterielader</h4>
            <p class="mb-3 text-sm">Für 6V/12V Batterien mit Überladeschutz.</p>
            <a href="https://www.amazon.de/dp/B07W8ZVX4J?tag=dein-affiliate-id" target="_blank" class="text-blue-600 hover:underline">Jetzt kaufen</a>
          </div>
          <div class="bg-gray-50 p-6 rounded shadow text-center">
            <img src="https://m.media-amazon.com/images/I/71QpN2eCDGL._AC_SL1500_.jpg" alt="Wagenheber" class="w-full h-48 object-contain mb-4">
            <h4 class="text-lg font-bold mb-2">Hydraulischer Wagenheber</h4>
            <p class="mb-3 text-sm">Stabil, langlebig, ideal für jede Garage.</p>
            <a href="https://www.amazon.de/dp/B07D6SYXP2?tag=dein-affiliate-id" target="_blank" class="text-blue-600 hover:underline">Jetzt kaufen</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Kontaktformular -->
    <section id="kontakt" class="py-16 bg-gray-100 bg-opacity-95">
      <div class="container mx-auto max-w-xl">
        <h3 class="text-3xl font-bold text-center mb-6">Kontakt</h3>
        <form action="mailto:niehausleon@gmail.com" method="POST" enctype="text/plain" class="bg-white p-6 rounded shadow space-y-4">
          <div>
            <label class="block mb-1 font-semibold" for="name">Name</label>
            <input type="text" name="name" id="name" class="w-full px-4 py-2 rounded border" required>
          </div>
          <div>
            <label class="block mb-1 font-semibold" for="email">E-Mail</label>
            <input type="email" name="email" id="email" class="w-full px-4 py-2 rounded border" required>
          </div>
          <div>
            <label class="block mb-1 font-semibold" for="message">Nachricht</label>
            <textarea name="message" id="message" rows="5" class="w-full px-4 py-2 rounded border" required></textarea>
          </div>
          <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">Absenden</button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6 mt-10">
      <div class="container mx-auto text-center">
        <p class="mb-2">&copy; 2025 Kfz Werkzeug & Zubehör – Alle Rechte vorbehalten.</p>
        <p class="text-sm">Diese Seite enthält Affiliate-Links zu Amazon. Als Amazon-Partner verdiene ich an qualifizierten Käufen.</p>
      </div>
    </footer>
  </div>
</body>
</html>
