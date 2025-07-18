<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- SEO Básico -->
  <title>Transporte MX – Transporte de Materiales en Zona Metropolitana de Monterrey</title>
  <meta name="description" content="Transporte MX ofrece servicio de transporte de materiales a granel en la Zona Metropolitana de Monterrey. Flota 3.5T, torton y tráiler. Cotiza rápido y seguro." />
  <meta name="keywords" content="transporte materiales, logística Monterrey, camión 3.5T, torton, tráiler, cotización transporte" />

  <!-- Favicon -->
  <link rel="icon" href="img/favicon.ico" type="image/x-icon" />

  <!-- Open Graph & Twitter -->
  <meta property="og:type" content="website" />
  <meta property="og:title" content="Transporte MX – Transporte de Materiales en Monterrey" />
  <meta property="og:description" content="Servicio seguro y puntual de transporte de materiales en la Zona Metropolitana de Monterrey. Cotiza hoy." />
  <meta property="og:image" content="https://tudominio.com/img/hero.jpg" />
  <meta property="og:url" content="https://tudominio.com" />
  <meta property="og:site_name" content="Transporte MX" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Transporte MX – Transporte de Materiales en Monterrey" />
  <meta name="twitter:description" content="Servicio seguro y puntual de transporte de materiales en la Zona Metropolitana de Monterrey. Cotiza hoy." />
  <meta name="twitter:image" content="https://tudominio.com/img/hero.jpg" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans antialiased text-gray-800">

  <!-- Navbar -->
  <header class="bg-white shadow">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center p-4">
      <div class="text-2xl font-bold text-blue-700">Transporte MX</div>
      <button id="btn-menu" class="md:hidden p-2 text-blue-700" aria-label="Abrir menú">☰</button>
      <nav id="menu" class="hidden md:flex space-x-6">
        <a href="#" class="hover:text-blue-500">Inicio</a>
        <a href="#nosotros" class="hover:text-blue-500">Nosotros</a>
        <a href="#servicios" class="hover:text-blue-500">Servicios</a>
        <a href="#cotiza" class="hover:text-blue-500">Cotizar</a>
        <a href="#contacto" class="hover:text-blue-500">Contacto</a>
      </nav>
    </div>
  </header>
  <script>
    document.getElementById('btn-menu').onclick = () =>
      document.getElementById('menu').classList.toggle('hidden');
  </script>

  <!-- Hero -->
  <section class="bg-cover bg-center h-80 sm:h-96 md:h-screen" style="background-image: url('hero.jpg');">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 h-full flex flex-col justify-center items-start text-white">
      <h1 class="text-2xl sm:text-3xl md:text-5xl font-bold mb-2 drop-shadow-lg">Transporte de Materiales</h1>
      <p class="text-base sm:text-lg lg:text-xl mb-4 max-w-xl drop-shadow">Seguro, puntual y eficiente en toda la Zona Metropolitana</p>
      <a href="#cotiza" class="bg-blue-600 hover:bg-blue-700 transition-colors text-white px-4 py-2 sm:px-6 sm:py-3 rounded shadow">
        Solicita tu cotización
      </a>
    </div>
  </section>

  <!-- Nosotros: Misión & Visión -->
  <section id="nosotros" class="py-16 bg-white">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl sm:text-4xl font-bold mb-8">Quiénes Somos</h2>
      <div class="flex flex-col md:flex-row md:space-x-12">
        <div class="md:w-1/2 mb-8 md:mb-0">
          <h3 class="text-2xl font-semibold mb-4">Misión</h3>
          <p class="text-gray-700 leading-relaxed">
            Proveer soluciones de transporte de materiales a granel con seguridad y puntualidad, 
            contribuyendo al desarrollo de proyectos de construcción en la Zona Metropolitana de Monterrey.
          </p>
        </div>
        <div class="md:w-1/2">
          <h3 class="text-2xl font-semibold mb-4">Visión</h3>
          <p class="text-gray-700 leading-relaxed">
            Ser la empresa líder en logística y transporte de materiales en todo México, 
            reconocida por nuestra eficiencia, compromiso ambiental y atención al cliente.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Nuestros Servicios -->
  <section id="servicios" class="py-16 bg-gray-100">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl sm:text-4xl font-bold mb-8">Nuestros Servicios</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="p-6 bg-white rounded shadow hover:shadow-lg transition-shadow">
          <img src="camion-35t.png" alt="Camión 3.5T" class="w-full h-auto rounded mb-4">
          <h3 class="text-xl sm:text-2xl font-semibold mb-2">Camión 3.5T</h3>
          <p class="text-sm sm:text-base text-gray-700">Transporte local y regional de materiales ligeros.</p>
        </div>
        <div class="p-6 bg-white rounded shadow hover:shadow-lg transition-shadow">
          <img src="torton.png" alt="Torton" class="w-full h-auto rounded mb-4">
          <h3 class="text-xl sm:text-2xl font-semibold mb-2">Torton</h3>
          <p class="text-sm sm:text-base text-gray-700">Carga de hasta 10 toneladas en rutas urbanas.</p>
        </div>
        <div class="p-6 bg-white rounded shadow hover:shadow-lg transition-shadow">
          <img src="trailer.png" alt="Tráiler" class="w-full h-auto rounded mb-4">
            <h3 class="text-xl sm:text-2xl font-semibold mb-2">Tráiler</h3>
            <p class="text-sm sm:text-base text-gray-700">Servicios de largo alcance con capacidad de 20+ toneladas.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Cobertura -->
  <section class="py-16">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl sm:text-4xl font-bold mb-8">Cobertura</h2>
      <img src="mapa-mty.png" alt="Zona Metropolitana de Monterrey" class="w-full h-auto max-w-3xl mx-auto rounded shadow mb-4">
      <p class="text-base sm:text-lg text-gray-700">
        Operamos en CDMX y Área Metropolitana. 
        <strong class="text-blue-600">Próximamente: Nacional</strong>
      </p>
    </div>
  </section>

  <!-- Cotiza tu Envío (Formulario) -->
  <section id="cotiza" class="py-16 bg-blue-50">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-xl">
      <h2 class="text-3xl sm:text-4xl font-bold text-center mb-6">Cotiza tu Envío</h2>
      <form action="https://formspree.io/f/manbnavo" method="POST" class="bg-white p-8 rounded shadow space-y-4">
        <input type="hidden" name="_captcha" value="false">
        <div>
          <label class="block font-medium mb-2">Tipo de Material</label>
          <input name="material" type="text" class="w-full border p-2 rounded" placeholder="Ej: Arena, grava, tierra" required>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div>
            <label class="block font-medium mb-2">Origen</label>
            <input name="origen" type="text" class="w-full border p-2 rounded" placeholder="Dirección de carga" required>
          </div>
          <div>
            <label class="block font-medium mb-2">Destino</label>
            <input name="destino" type="text" class="w-full border p-2 rounded" placeholder="Dirección de descarga" required>
          </div>
        </div>
        <div>
          <label class="block font-medium mb-2">Volumen estimado</label>
            <input name="volumen" type="text" class="w-full border p-2 rounded" placeholder="Ej: 5 m³" required>
        </div>
        <div>
          <label class="block font-medium mb-2">Contacto (email o teléfono)</label>
          <input name="_replyto" type="text" class="w-full border p-2 rounded" placeholder="Correo o teléfono" required>
        </div>
        <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white py-3 rounded font-medium">
          Enviar solicitud
        </button>
      </form>
    </div>
  </section>

  <!-- Contacto -->
  <footer id="contacto" class="bg-gray-800 text-white py-12">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-2">
      <h3 class="text-2xl sm:text-3xl font-bold">Contáctanos</h3>
      <p class="text-base">📞 +52 55 1234 5678</p>
      <p class="text-base">✉️ info@transportesmx.com</p>
      <p class="text-base">📍 Calle Ficticia 128, CDMX</p>
    </div>
  </footer>

</body>
</html>
