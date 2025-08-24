<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evolución de la Tecnología Educativa</title>
    <!-- Incluir Tailwind CSS desde CDN para un diseño moderno y responsive -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Estilo para la fuente 'Inter' para una mejor legibilidad */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
        }
        /* Estilos para el efecto de sombra y animacion */
        .card-shadow {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease-in-out;
        }
        .card-shadow:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="p-4 sm:p-8">
    <div class="max-w-4xl mx-auto bg-white rounded-3xl p-6 sm:p-10 card-shadow">
        <header class="text-center mb-10">
            <h1 class="text-3xl sm:text-5xl font-bold text-gray-800 mb-2">Evolución de la Tecnología Educativa</h1>
            <p class="text-lg text-gray-600">Un viaje a través de los paradigmas clave.</p>
        </header>

        <!-- Contenedor para las fases -->
        <div class="space-y-8">
            <!-- Fase 1: Momentos Iniciales -->
            <div class="bg-gray-50 rounded-2xl p-6 card-shadow">
                <h2 class="text-2xl font-semibold text-gray-700 mb-2">1. Momentos Iniciales</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    Este período no se enfoca en una sola herramienta, sino en ideas pedagógicas que sentaron las bases para el uso de la tecnología en la educación.
                    <br><span class="font-medium text-gray-500">Cuándo y Dónde:</span> Desde la Antigua Grecia (siglo V a.C.) hasta el siglo XVIII.
                </p>
                <div class="mt-4">
                    <h3 class="font-bold text-gray-700">Aportes Clave:</h3>
                    <ul class="list-disc list-inside text-gray-600">
                        <li><span class="font-semibold">Los Sofistas:</span> Enfoque en la elocuencia y el debate como método de enseñanza.</li>
                        <li><span class="font-semibold">Juan Amós Comenio:</span> Uso de medios visuales como ilustraciones en libros (p. ej., Orbis Pictus) para facilitar el aprendizaje.</li>
                        <li><span class="font-semibold">Jean-Jacques Rousseau:</span> Énfasis en que la enseñanza debe adaptarse al niño y a su desarrollo natural.</li>
                    </ul>
                </div>
            </div>

            <!-- Fase 2: Los Medios Audiovisuales -->
            <div class="bg-gray-50 rounded-2xl p-6 card-shadow">
                <h2 class="text-2xl font-semibold text-gray-700 mb-2">2. Los Medios Audiovisuales</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    En esta etapa, la tecnología se centra en la incorporación de recursos como la radio, el cine y la televisión para facilitar la enseñanza.
                    <br><span class="font-medium text-gray-500">Aportes Clave:</span>
                    <ul>
                      <li><span class="font-semibold">Radio:</span> Permitió la educación a distancia.</li>
                      <li><span class="font-semibold">Cine y televisión:</span> Ofrecieron experiencias visuales y sonoras que enriquecieron el aprendizaje.</li>
                    </ul>
                </p>
            </div>

            <!-- Fase 3: El Enfoque Conductista -->
            <div class="bg-gray-50 rounded-2xl p-6 card-shadow">
                <h2 class="text-2xl font-semibold text-gray-700 mb-2">3. El Enfoque Conductista</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    Se enfoca en la respuesta a estímulos y la retroalimentación inmediata, utilizando la tecnología para automatizar y optimizar este proceso.
                    <br><span class="font-medium text-gray-500">Aportes Clave:</span>
                    <ul>
                      <li><span class="font-semibold">B. F. Skinner:</span> Propuso la instrucción programada y las máquinas de enseñar para que los estudiantes avanzaran a su propio ritmo, recibiendo refuerzo por cada respuesta correcta.</li>
                    </ul>
                </p>
            </div>

            <!-- Fase 4: El Enfoque Sistémico -->
            <div class="bg-gray-50 rounded-2xl p-6 card-shadow">
                <h2 class="text-2xl font-semibold text-gray-700 mb-2">4. El Enfoque Sistémico</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    Este enfoque no prioriza a un solo componente, sino que se centra en cómo todos los elementos de un sistema educativo interactúan para lograr un objetivo común.
                    <br><span class="font-medium text-gray-500">Clave del Sistema:</span> La interdependencia y la coordinación entre profesores, estudiantes, materiales, y las herramientas tecnológicas.
                    <br><span class="font-medium text-gray-500">Objetivo:</span> Aumentar la eficacia de todo el sistema educativo.
                </p>
            </div>

            <!-- Fase 5: El Momento Actual -->
            <div class="bg-gray-50 rounded-2xl p-6 card-shadow">
                <h2 class="text-2xl font-semibold text-gray-700 mb-2">5. El Momento Actual</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    Esta fase se caracteriza por la integración estratégica de la tecnología para personalizar y transformar el aprendizaje.
                    <br><span class="font-medium text-gray-500">Principios Clave:</span>
                    <ul>
                      <li><span class="font-semibold">Personalización:</span> El aprendizaje se adapta a las necesidades de cada estudiante (gracias a la IA).</li>
                      <li><span class="font-semibold">Aprendizaje Híbrido:</span> Combinación de clases presenciales y virtuales.</li>
                      <li><span class="font-semibold">Gamificación:</span> Uso de juegos y dinámicas lúdicas para aumentar la motivación.</li>
                      <li><span class="font-semibold">Colaboración:</span> Fomento del trabajo en equipo a través de herramientas digitales.</li>
                    </ul>
                    <br><span class="font-medium text-gray-500">Herramientas Esenciales:</span>
                    <ul>
                      <li><span class="font-semibold">IA (Inteligencia Artificial):</span> Sistemas de tutoría y asistentes virtuales.</li>
                      <li><span class="font-semibold">RV (Realidad Virtual) y RA (Realidad Aumentada):</span> Para experiencias inmersivas y prácticas virtuales.</li>
                      <li><span class="font-semibold">LMS (Sistemas de Gestión del Aprendizaje):</span> Plataformas como Google Classroom y Moodle.</li>
                      <li><span class="font-semibold">Herramientas Colaborativas:</span> Padlet, Miro y Genially.</li>
                    </ul>
                </p>
            </div>
        </div>
        
    </div>
</body>
</html>
