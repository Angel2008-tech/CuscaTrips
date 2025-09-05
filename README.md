<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cuscatrips - Viajes en El Salvador</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-green-600 text-white shadow-md">
    <div class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold">Cuscatrips</h1>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#inicio" class="hover:text-yellow-300">Inicio</a></li>
          <li><a href="#tours" class="hover:text-yellow-300">Viajes</a></li>
          <li><a href="#nosotros" class="hover:text-yellow-300">Nosotros</a></li>
          <li><a href="#contacto" class="hover:text-yellow-300">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="inicio" class="bg-cover bg-center h-[70vh] flex items-center justify-center text-center" style="background-image: url('https://images.unsplash.com/photo-1526772662000-3f88f10405ff?auto=format&fit=crop&w=1400&q=80');">
    <div class="bg-black bg-opacity-50 p-6 rounded-xl">
      <h2 class="text-4xl md:text-6xl font-bold text-white mb-4">Descubre El Salvador</h2>
      <p class="text-lg text-gray-200 mb-6">Playas, montañas y cultura con Cuscatrips</p>
      <a href="#tours" class="bg-yellow-400 text-black px-6 py-3 rounded-full font-semibold hover:bg-yellow-300 transition">Explorar Viajes</a>
    </div>
  </section>

  <!-- Viajes -->
  <section id="tours" class="py-16 container mx-auto">
    <h3 class="text-3xl font-bold text-center mb-10">Nuestros Viajes</h3>

    <div class="grid md:grid-cols-3 gap-8">

      <!-- Playas -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1589191871081-54d3d8e5c59a?auto=format&fit=crop&w=800&q=80" alt="Playa El Tunco" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">Playa El Tunco</h4>
            <p class="text-gray-600 mb-3">Surf, ambiente bohemio y atardeceres mágicos.</p>
            <p class="text-green-700 font-bold">Desde $35 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1580635516006-77d3e7e5e2ad?auto=format&fit=crop&w=800&q=80" alt="Costa del Sol" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">Costa del Sol</h4>
            <p class="text-gray-600 mb-3">Playas amplias, arena blanca y un ambiente relajante.</p>
            <p class="text-green-700 font-bold">Desde $38 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1604933747697-4a74d2c4aa0f?auto=format&fit=crop&w=800&q=80" alt="El Cuco" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">El Cuco</h4>
            <p class="text-gray-600 mb-3">Un paraíso costero ideal para descansar y disfrutar del mar.</p>
            <p class="text-green-700 font-bold">Desde $42 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <!-- Montañas -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1628126234360-99d19a7fc7f6?auto=format&fit=crop&w=800&q=80" alt="Ruta de las Flores" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">Ruta de las Flores</h4>
            <p class="text-gray-600 mb-3">Coloridos pueblos, café y gastronomía local.</p>
            <p class="text-green-700 font-bold">Desde $40 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1614695111268-924d1a9c0a4c?auto=format&fit=crop&w=800&q=80" alt="La Palma" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">La Palma</h4>
            <p class="text-gray-600 mb-3">Arte, cultura y paisajes montañosos únicos.</p>
            <p class="text-green-700 font-bold">Desde $36 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1631033502700-51c96a6a96ab?auto=format&fit=crop&w=800&q=80" alt="Cerro Verde" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">Cerro Verde</h4>
            <p class="text-gray-600 mb-3">Senderismo y vistas espectaculares de volcanes y lagos.</p>
            <p class="text-green-700 font-bold">Desde $45 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <!-- Sitios Culturales -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1610563166151-7db1c0f4952d?auto=format&fit=crop&w=800&q=80" alt="Suchitoto" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">Suchitoto</h4>
            <p class="text-gray-600 mb-3">Arquitectura colonial, arte y cultura viva.</p>
            <p class="text-green-700 font-bold">Desde $33 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1578301978693-2e2f07af38d8?auto=format&fit=crop&w=800&q=80" alt="San Andrés" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">San Andrés</h4>
            <p class="text-gray-600 mb-3">Sitio arqueológico que muestra la grandeza maya-pipil.</p>
            <p class="text-green-700 font-bold">Desde $32 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-lg overflow-hidden flex flex-col">
        <img src="https://images.unsplash.com/photo-1629976068137-4cb84ce8b063?auto=format&fit=crop&w=800&q=80" alt="Joya de Cerén" class="h-48 w-full object-cover">
        <div class="p-5 flex-1 flex flex-col justify-between">
          <div>
            <h4 class="text-xl font-semibold mb-2">Joya de Cerén</h4>
            <p class="text-gray-600 mb-3">La “Pompeya de América”, Patrimonio de la Humanidad.</p>
            <p class="text-green-700 font-bold">Desde $30 por persona</p>
          </div>
          <a href="https://wa.me/50312345678" target="_blank" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded-lg font-semibold hover:bg-green-500 transition">Reservar</a>
        </div>
      </div>

    </div>
  </section>

  <!-- Nosotros -->
  <section id="nosotros" class="bg-green-100 py-16">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Sobre Nosotros</h3>
      <p class="max-w-2xl mx-auto text-lg text-gray-700">
        En <span class="font-semibold">Cuscatrips</span> creemos que viajar es más que moverse de un lugar a otro: es conectar con la cultura, la naturaleza y la historia de El Salvador. Nuestro equipo te guiará para que vivas experiencias auténticas, seguras y memorables.
      </p>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="py-16 container mx-auto">
    <h3 class="text-3xl font-bold text-center mb-10">Contáctanos</h3>
    <form class="max-w-xl mx-auto bg-white p-8 rounded-2xl shadow-lg">
      <div class="mb-4">
        <label class="block text-left font-semibold">Nombre</label>
        <input type="text" class="w-full border rounded-lg px-3 py-2 mt-2" placeholder="Tu nombre">
      </div>
      <div class="mb-4">
        <label class="block text-left font-semibold">Correo</label>
        <input type="email" class="w-full border rounded-lg px-3 py-2 mt-2" placeholder="tu@correo.com">
      </div>
      <div class="mb-4">
        <label class="block text-left font-semibold">Mensaje</label>
        <textarea class="w-full border rounded-lg px-3 py-2 mt-2" rows="4" placeholder="Escribe tu mensaje..."></textarea>
      </div>
      <button type="submit" class="bg-green-600 text-white px-6 py-3 rounded-full font-semibold hover:bg-green-500 transition">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-green-700 text-white text-center py-6">
    <p>&copy; 2025 Cuscatrips. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
