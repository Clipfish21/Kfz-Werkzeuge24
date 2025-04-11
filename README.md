<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WerkzeugWelt – Kfz-Werkzeuge</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { font-family: 'Roboto', sans-serif; }
    .hero-bg {
      background: linear-gradient(120deg, #1f2937 0%, #374151 100%);
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">
  <header class="hero-bg text-white shadow-lg">
    <div class="container mx-auto flex justify-between items-center p-6">
      <h1 class="text-3xl font-bold">WerkzeugWelt</h1>
      <nav class="space-x-4 text-lg">
        <a href="#start" class="hover:text-orange-400">Start</a>
        <a href="#kategorien" class="hover:text-orange-400">Kategorien</a>
        <a href="#ratgeber" class="hover:text-orange-400">Ratgeber</a>
        <a href="#kontakt" class="hover:text-orange-400">Kontakt</a>
      </nav>
    </div>
  </header>

  <section id="start" class="text-center py-20 bg-white">
    <h2 class="text-5xl font-bold mb-4 text-gray-900">Die besten Kfz-Werkzeuge 2024</h2>
    <p class="text-lg mb-6">Finde das perfekte Werkzeug für deine Garage – getestet und empfohlen!</p>
    <a href="#kategorien" class="bg-orange-500 text-white px-6 py-3 rounded hover:bg-orange-600">Jetzt entdecken</a>
  </section>

  <section id="kategorien" class="py-16 bg-gray-50">
    <div class="container mx-auto">
      <h3 class="text-3xl font-bold mb-10 text-center">Werkzeug-Kategorien</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Wagenheber</h4>
          <p class="mb-3">Sicher und stabil – entdecke die besten Modelle.</p>
          <a href="#" class="text-orange-600 hover:underline">Mehr erfahren</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Drehmomentschlüssel</h4>
          <p class="mb-3">Präzision für jeden Handgriff in deiner Werkstatt.</p>
          <a href="#" class="text-orange-600 hover:underline">Mehr erfahren</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">OBD2-Diagnosegeräte</h4>
          <p class="mb-3">Fehler auslesen wie ein Profi – auch mobil einsetzbar.</p>
          <a href="#" class="text-orange-600 hover:underline">Mehr erfahren</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Steckschlüssel-Sätze</h4>
          <p class="mb-3">Für alle Schraubarbeiten am Auto bestens gerüstet.</p>
          <a href="#" class="text-orange-600 hover:underline">Mehr erfahren</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Poliermaschinen</h4>
          <p class="mb-3">Lackpflege wie vom Profi – strahlender Glanz garantiert.</p>
          <a href="#" class="text-orange-600 hover:underline">Mehr erfahren</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Batterieladegeräte</h4>
          <p class="mb-3">Sicher und effizient laden – auch unterwegs.</p>
          <a href="#" class="text-orange-600 hover:underline">Mehr erfahren</a>
        </div>
      </div>
    </div>
  </section>

  <section id="ratgeber" class="py-16 bg-white">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-bold mb-4">Kaufberatung & Tipps</h3>
      <p class="text-lg mb-6 max-w-2xl mx-auto">Welche Werkzeuge brauchst du wirklich? Worauf solltest du achten? In unserem Blog findest du praktische Tipps und fundierte Empfehlungen.</p>
      <a href="#" class="bg-orange-500 text-white px-6 py-3 rounded hover:bg-orange-600">Zum Ratgeber</a>
    </div>
  </section>

  <footer id="kontakt" class="bg-gray-900 text-white py-6">
    <div class="container mx-auto text-center">
      <p class="mb-2">&copy; 2025 WerkzeugWelt – Alle Rechte vorbehalten.</p>
      <p class="text-sm">Diese Seite nutzt Partnerlinks zu Amazon. Als Amazon-Partner verdiene ich an qualifizierten Käufen.</p>
    </div>
  </footer>
</body>
</html>
