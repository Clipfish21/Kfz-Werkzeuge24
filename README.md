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
    input, textarea {
      border: 1px solid #ccc;
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
        <a href="#diagnosegeraete" class="hover:text-orange-400">Diagnosegeräte</a>
        <a href="#vag" class="hover:text-orange-400">VAG</a>
        <a href="#audi" class="hover:text-orange-400">Audi</a>
        <a href="#bmw" class="hover:text-orange-400">BMW</a>
        <a href="#zubehoer" class="hover:text-orange-400">Werkstatt Zubehör</a>
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
      <h3 class="text-3xl font-bold mb-10 text-center">Kategorien</h3>
      <div class="flex justify-center flex-wrap gap-6 text-center">
        <a href="#diagnosegeraete" class="bg-white px-6 py-3 rounded shadow hover:bg-orange-100">Diagnosegeräte</a>
        <a href="#vag" class="bg-white px-6 py-3 rounded shadow hover:bg-orange-100">VAG Werkzeuge</a>
        <a href="#audi" class="bg-white px-6 py-3 rounded shadow hover:bg-orange-100">Audi Werkzeuge</a>
        <a href="#bmw" class="bg-white px-6 py-3 rounded shadow hover:bg-orange-100">BMW Werkzeuge</a>
        <a href="#zubehoer" class="bg-white px-6 py-3 rounded shadow hover:bg-orange-100">Werkstatt Zubehör</a>
      </div>
    </div>
  </section>

  <!-- Vorheriger Content bleibt erhalten -->

  <section id="zubehoer" class="py-16 bg-white">
    <div class="container mx-auto">
      <h3 class="text-3xl font-bold mb-10 text-center">Werkstatt Zubehör</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/81x2yS9lJNL._AC_SL1500_.jpg" alt="Werkzeugkiste" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Stanley Werkzeugkiste</h4>
          <p class="mb-3">Robuste Box mit viel Stauraum für alle Werkzeuge.</p>
          <a href="https://www.amazon.de/dp/B001GQ2RWU?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/71H97HzexPL._AC_SL1500_.jpg" alt="Batterieladegerät" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">NOCO Genius Ladegerät</h4>
          <p class="mb-3">Intelligentes Batterieladegerät für 6V und 12V Batterien.</p>
          <a href="https://www.amazon.de/dp/B07W8ZVX4J?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/71QpN2eCDGL._AC_SL1500_.jpg" alt="Wagenheber" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Hydraulischer Wagenheber</h4>
          <p class="mb-3">Stabiler Rangierwagenheber für sicheres Arbeiten am Fahrzeug.</p>
          <a href="https://www.amazon.de/dp/B07D6SYXP2?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>
      </div>
    </div>
  </section>

  <section id="kontakt" class="py-16 bg-gray-100">
    <div class="container mx-auto max-w-xl">
      <h3 class="text-3xl font-bold text-center mb-6">Kontakt</h3>
      <form class="bg-white p-6 rounded shadow space-y-4" action="mailto:niehausleon@gmail.com" method="POST" enctype="text/plain">
        <div>
          <label for="name" class="block mb-1 font-semibold">Name</label>
          <input type="text" id="name" name="name" class="w-full px-4 py-2 rounded" required>
        </div>
        <div>
          <label for="email" class="block mb-1 font-semibold">E-Mail</label>
          <input type="email" id="email" name="email" class="w-full px-4 py-2 rounded" required>
        </div>
        <div>
          <label for="message" class="block mb-1 font-semibold">Nachricht</label>
          <textarea id="message" name="message" rows="5" class="w-full px-4 py-2 rounded" required></textarea>
        </div>
        <button type="submit" class="bg-orange-500 text-white px-6 py-2 rounded hover:bg-orange-600">Absenden</button>
      </form>
    </div>
  </section>

  <footer class="bg-gray-900 text-white py-6 mt-10">
    <div class="container mx-auto text-center">
      <p class="mb-2">&copy; 2025 WerkzeugWelt – Alle Rechte vorbehalten.</p>
      <p class="text-sm">Diese Seite nutzt Partnerlinks zu Amazon. Als Amazon-Partner verdiene ich an qualifizierten Käufen.</p>
    </div>
  </footer>
</body>
</html>
