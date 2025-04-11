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

        <!-- Produkt 1 -->
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/71kL+KoXqZL._AC_SL1500_.jpg" alt="Wagenheber" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Wagenheber</h4>
          <p class="mb-3">Sicher und stabil – entdecke die besten Modelle.</p>
          <a href="https://www.amazon.de/dp/B000VZCEUI?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>

        <!-- Produkt 2 -->
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/61bAByltGJL._AC_SL1500_.jpg" alt="Drehmomentschlüssel" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Drehmomentschlüssel</h4>
          <p class="mb-3">Präzision für jeden Handgriff in deiner Werkstatt.</p>
          <a href="https://www.amazon.de/dp/B01M0B3XK0?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>

        <!-- Produkt 3 -->
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/61AaD1xE0nL._AC_SL1000_.jpg" alt="OBD2-Diagnosegerät" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">OBD2-Diagnosegerät</h4>
          <p class="mb-3">Fehler auslesen wie ein Profi – auch mobil einsetzbar.</p>
          <a href="https://www.amazon.de/dp/B08GY8PQJL?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>

        <!-- Produkt 4 -->
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/71liDEnM5OL._AC_SL1500_.jpg" alt="Werkzeugkoffer" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Werkzeugkoffer</h4>
          <p class="mb-3">Alles in einem Set für Einsteiger und Profis.</p>
          <a href="https://www.amazon.de/dp/B07K1GVGNB?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>

        <!-- Produkt 5 -->
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/61LQIqH5VoL._AC_SL1000_.jpg" alt="Rangierwagenheber" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Rangierwagenheber</h4>
          <p class="mb-3">Ideal zum Reifenwechsel oder Arbeiten unter dem Auto.</p>
          <a href="https://www.amazon.de/dp/B004V4I6LI?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>

        <!-- Produkt 6 -->
        <div class="bg-white p-6 rounded-lg shadow-md text-center">
          <img src="https://m.media-amazon.com/images/I/71FLrO05bSL._AC_SL1500_.jpg" alt="Batterieladegerät" class="w-full h-48 object-contain mb-4">
          <h4 class="text-xl font-semibold mb-2">Batterieladegerät</h4>
          <p class="mb-3">Automatik-Ladegerät für alle Fahrzeugbatterien.</p>
          <a href="https://www.amazon.de/dp/B07Z5BRRRF?tag=dein-affiliate-id" class="text-orange-600 hover:underline" target="_blank">Bei Amazon ansehen</a>
        </div>

      </div>
    </div>
  </section>

  <section id="ratgeber" class="py-16 bg-white">
    <div class="container mx-auto text-center max-w-3xl">
      <h3 class="text-3xl font-bold mb-6">Kaufberatung & Tipps</h3>
      <p class="text-lg mb-6">Beim Kauf von Kfz-Werkzeugen solltest du auf Qualität, Handhabung und Einsatzbereich achten. Wichtige Fragen: Wird das Werkzeug oft genutzt? Muss es mobil sein? Ist eine genaue Messung erforderlich? Lies unseren <a href="#" class="text-orange-600 hover:underline">vollständigen Ratgeber hier</a>.</p>
    </div>
  </section>

  <section id="kontakt" class="py-16 bg-gray-100">
    <div class="container mx-auto max-w-xl">
      <h3 class="text-3xl font-bold text-center mb-6">Kontakt</h3>
      <form class="bg-white p-6 rounded shadow space-y-4">
        <div>
          <label for="name" class="block mb-1 font-semibold">Name</label>
          <input type="text" id="name" class="w-full px-4 py-2 rounded" required>
        </div>
        <div>
          <label for="email" class="block mb-1 font-semibold">E-Mail</label>
          <input type="email" id="email" class="w-full px-4 py-2 rounded" required>
        </div>
        <div>
          <label for="message" class="block mb-1 font-semibold">Nachricht</label>
          <textarea id="message" rows="5" class="w-full px-4 py-2 rounded" required></textarea>
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
