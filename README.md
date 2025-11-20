<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrailFinder | Asistencia Digital para Rutas Naturales en España</title>
    
    <style>
        /* Estilos CSS para un diseño profesional y enfocado en la naturaleza */
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Roboto:wght@300;400&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F7F9FC; /* Fondo claro */
            color: #333;
            line-height: 1.6;
        }
        
        /* Sección Principal Emocional */
        header {
            background-color: #004D40; /* Verde Bosque Oscuro */
            color: white;
            padding: 80px 0;
            text-align: center;
            /* Placeholder: Imagen inspiradora de la naturaleza española (ej. Sierra Nevada) */
            background-image: linear-gradient(rgba(0, 77, 64, 0.7), rgba(0, 77, 64, 0.8)), url('path/to/inspirational-granada-bg.jpg'); 
            background-size: cover;
            background-position: bottom;
        }
        header h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3.5em;
            margin: 0;
            letter-spacing: 3px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        header h2 {
            font-weight: 300;
            font-size: 1.5em;
            margin-top: 15px;
        }
        
        /* Navegación */
        nav {
            background-color: #00796B; /* Teal Medio */
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        nav .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            padding: 18px 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 700;
            transition: color 0.3s;
            font-size: 0.9em;
        }
        
        /* Estructura Principal */
        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 0 20px;
        }
        .segment-card {
            background-color: white;
            padding: 40px;
            margin-bottom: 40px;
            border-radius: 10px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
            border-left: 6px solid #FFC107; /* Acento Dorado */
        }
        .segment-card h2 {
            font-family: 'Montserrat', sans-serif;
            color: #004D40;
            font-size: 2.2em;
            margin-top: 0;
            border-bottom: 2px solid #E0F2F1;
            padding-bottom: 10px;
        }
        
        /* Galería de Destinos */
        .destination-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .destination-item {
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            text-align: center;
        }
        .destination-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            display: block;
        }
        .destination-item h4 {
            font-family: 'Montserrat', sans-serif;
            color: #00796B;
            padding: 15px 10px;
            margin: 0;
            font-size: 1.1em;
        }

        /* Productos y Estrategia */
        .product-item, .strategy-item {
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 6px;
        }
        .product-item {
            background: #E0F2F1; /* Fondo Teal Claro para servicios */
            border-left: 4px solid #00796B;
        }
        .strategy-item {
            background: #F0F4F7; /* Fondo sutil para estrategia */
            border-left: 4px solid #004D40;
        }
        .product-item h4, .strategy-item h4 {
            color: #004D40;
            margin-top: 0;
            font-weight: 700;
        }
        .academic-justification {
            background-color: #fcebeb; /* Fondo para secciones académicas en español */
            border: 1px solid #e0b4b4;
            padding: 20px;
            border-radius: 5px;
            margin-top: 20px;
        }
        .academic-justification h3 {
            color: #c0392b;
        }

        /* Pie de Página */
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Feel the Freedom. Travel with TrailFinder.</h1>
        <h2>Your Adventure is Our Priority. Personalized Assistance across all Spain.</h2>
    </header>

    <nav>
        <div class="nav-container">
            <a href="#mission">Empresa</a>
            <a href="#destinations">Destinos</a>
            <a href="#segment1">Segmento 1</a>
            <a href="#segment2">Segmento 2</a>
            <a href="#justificacion">Justificación</a>
            <a href="#estrategia">Estrategia Comercial</a>
        </div>
    </nav>

    <div class="container">
        
        <section id="mission" class="segment-card">
            <h2>🌍 Our Mission: Expert Tourism Information & Assistance</h2>
            <p><strong>TrailFinder</strong> is not just an app; it is your digital guardian for Spain's most beautiful national parks and nature trails. Our headquarters are rooted in **Granada**, the gateway to the Sierra Nevada, but our **24/7 information and assistance services** cover every corner of Spain. We ensure your journey is **safe, affordable, and deeply authentic**.</p>
            <p><strong>Ubicación de la Sede:</strong> Granada, España. | <strong>Servicios:</strong> Información y Asistencia Turística especializada en Logística y Seguridad en Rutas Naturales.</p>
        </section>

        <section id="destinations" class="segment-card">
            <h2>⛰️ Discover Spain's Wilderness: Where We Guide You</h2>
            <p>From the high peaks of the Pyrenees to the volcanic trails of the Canaries, we specialize in the best of Spanish nature. **Your adventure starts here.**</p>
            
            <div class="destination-gallery">
                <div class="destination-item">
                    <img src="path/to/picos-de-europa-image.jpg" alt="Picos de Europa National Park, Asturias/Cantabria">
                    <h4>Picos de Europa: The Rugged North</h4>
                </div>
                <div class="destination-item">
                    <img src="path/to/sierra-nevada-image.jpg" alt="Sierra Nevada National Park, Granada">
                    <h4>Sierra Nevada: Peaks of the South (Near HQ)</h4>
                </div>
                <div class="destination-item">
                    <img src="path/to/ordesa-image.jpg" alt="Ordesa y Monte Perdido National Park, Pyrenees">
                    <h4>Ordesa Valley: Pyrenees Grandeur</h4>
                </div>
                <div class="destination-item">
                    <img src="path/to/teide-image.jpg" alt="Teide National Park, Tenerife, Canary Islands">
                    <h4>El Teide: Volcanic Island Trails</h4>
                </div>
            </div>
        </section>

        <hr>

        <section id="segment1" class="segment-card">
            <h2>🎒 The Brave Hearts: Budget Backpackers (18-30 yrs)</h2>
            <p><strong>Your Emotion: Freedom.</strong> We know you seek unforgettable adventures without breaking the bank. You want to explore freely and connect with the real Spain. We are here to remove the stress of logistics, so you can focus on the journey.</p>
            
            <h3>Our Specialized Services (Products)</h3>
            <div class="product-item">
                <h4>Routes of Pure Adventure & Savings</h4>
                <p>Discover **"Extreme Budget"** trails, connecting you with low-cost accommodation (albergues/campings) and smart travel hacks. **Travel smart, not rich.**</p>
            </div>
            <div class="product-item">
                <h4>Instant Safety & Support (24/7)</h4>
                <p>Our quick-chat assistance is your lifeline. No more doubts about bus times or emergency contacts. **Peace of mind is just a tap away.**</p>
            </div>
        </section>

        <hr>

        <section id="segment2" class="segment-card">
            <h2>🌳 The Conscientious Explorers: Responsible Ecotourists (30-50 yrs)</h2>
            <p><strong>Your Emotion: Integrity.</strong> You believe in travel that gives back. You want to delve deep into nature, ensuring your presence is respectful and sustainable. We provide the expert knowledge you need to travel with a clean conscience and high comfort.</p>
            
            <h3>Our Specialized Services (Products)</h3>
            <div class="product-item">
                <h4>Curated Sustainable Experiences</h4>
                <p>Access our **"Certified Low-Impact"** itineraries, detailing local conservation efforts and zero-waste trekking guidance. **Travel well, live better.**</p>
            </div>
            <div class="product-item">
                <h4>Premium Logistical Security</h4>
                <p>Enjoy **expert video consultations** with mountain guides for advanced weather checks and detailed equipment preparation. **Security is not an option; it's a guarantee.**</p>
            </div>
        </section>
        
        <hr>
        
        <section id="justificacion" class="segment-card">
            <h2>📝 JUSTIFICACIÓN ACADÉMICA DE LA SEGMENTACIÓN (BIG TASK 2)</h2>
            
            <div class="academic-justification">
                <h3>REQUISITO 3: BASES DE SEGMENTACIÓN (Segmentation Bases)</h3>
                <p>La selección de los dos segmentos para TrailFinder se sustenta en las siguientes bases:</p>
                <ul>
                    <li><strong>Geográfica:</strong> España (Parques Nacionales y zonas de Montaña/Naturaleza), lo cual delimita nuestro producto.</li>
                    <li><strong>Demográfica:</strong> Uso de la edad (18-30 vs 30-50) y el nivel de ingresos (sensibilidad al precio vs. poder adquisitivo medio-alto) para diferenciar las ofertas.</li>
                    <li><strong>Comportamental:</strong> Diferenciación clara por el beneficio buscado (Ahorro y Aventura vs. Sostenibilidad y Seguridad Premium).</li>
                    <li><strong>Psicográfica:</strong> Diferenciación por estilo de vida (Minimalista/Flexible vs. Consciente/Planificador).</li>
                </ul>

                <h3>REQUISITO 4: CRITERIOS DE SEGMENTACIÓN (Segmentation Criteria)</h3>
                <p>Nuestros segmentos cumplen con los criterios esenciales para ser efectivos:</p>
                <ul>
                    <li><strong>Medible (Measurable):</strong> <strong>SÍ.</strong> El volumen de turistas jóvenes y el número de visitantes en Parques Nacionales de España (Fuente: Turespaña, OAPN) son datos estadísticos accesibles que confirman el tamaño del mercado.</li>
                    <li><strong>Sustancial (Substantial):</strong> <strong>SÍ.</strong> La combinación del alto volumen del S1 (Mochileros) y el alto valor de gasto del S2 (Ecoturistas) asegura la rentabilidad del nicho.</li>
                    <li><strong>Accesible (Accessible):</strong> <strong>SÍ.</strong> Ambos segmentos son 100% dependientes de la tecnología móvil, lo que permite un impacto directo y eficiente a través de canales digitales.</li>
                    <li><strong>Compatible:</strong> <strong>SÍ.</strong> La segmentación es plenamente compatible con el concepto de la empresa (asistencia digital en rutas naturales).</li>
                </ul>
            </div>
        </section>

        <hr>

        <section id="estrategia" class="segment-card">
            <h2>📈 ESTRATEGIA COMERCIAL Y CANALES DE COMUNICACIÓN (REQUISITO 6)</h2>
            <p>La estrategia se basa en usar el medio más adecuado para la emoción y el comportamiento de cada segmento.</p>
            
            <div class="strategy-item">
                <h4>Estrategia S1: Mochileros Jóvenes (The Brave Hearts)</h4>
                <p><strong>Objetivo:</strong> Generar notoriedad viral y captación directa en el móvil.</p>
                <ul>
                    <li>**Instrumento Comercial:** **RR.SS (TikTok, Reels)**. *Justificación:* Alto consumo de contenido rápido y visual. Es el medio más económico y efectivo para llegar a ellos y comunicar la "Libertad".</li>
                    <li>**Instrumento Comercial:** **Marketing Directo (Push Notifications)**. *Justificación:* Comunicación funcional, urgente (seguridad) y de conversión (ofertas de albergues).</li>
                </ul>
            </div>
            
            <div class="strategy-item">
                <h4>Estrategia S2: Ecoturistas Responsables (The Conscientious Explorers)</h4>
                <p><strong>Objetivo:</strong> Establecer credibilidad y aportar valor experto.</p>
                <ul>
                    <li>**Instrumento Comercial:** **Marketing Directo (Expert Newsletters)**. *Justificación:* Les proporciona el contenido de valor y la experiencia que buscan, construyendo respeto y confianza ("Integridad").</li>
                    <li>**Instrumento Comercial:** **Medios de Masas/Nicho (Revistas Especializadas en Turismo Sostenible)**. *Justificación:* Suelen confiar en las publicaciones de prestigio, lo que valida la calidad de nuestro servicio premium.</li>
                </ul>
            </div>
        </section>

    </div>

    <footer>
        <p>Tarea de Marketing Turístico (Oussama Ramli). &copy; 2025 TrailFinder. | Sede en Granada, con rutas por toda España.</p>
    </footer>

</body>
</html>

