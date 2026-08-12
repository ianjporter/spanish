<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grocery Shopping Vocabulary Deck</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #34495e;
            --accent: #3498db;
            --light: #ecf0f1;
            --white: #ffffff;
            --warning-accent: #e74c3c;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--light);
            color: var(--primary);
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem;
            margin: 0;
        }
        h1 {
            text-align: center;
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        .controls {
            margin-bottom: 2rem;
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            justify-content: center;
        }
        button, select {
            padding: 0.5rem 1rem;
            font-size: 1rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            background-color: var(--accent);
            color: var(--white);
            transition: background-color 0.3s ease;
        }
        button:hover, select:hover {
            background-color: #2980b9;
        }
        .flashcard-container {
            width: 100%;
            max-width: 500px;
            height: 300px;
            perspective: 1000px;
            margin-bottom: 2rem;
        }
        .flashcard {
            width: 100%;
            height: 100%;
            position: relative;
            transition: transform 0.6s;
            transform-style: preserve-3d;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            border-radius: 12px;
        }
        .flashcard.is-flipped {
            transform: rotateY(180deg);
        }
        .flashcard-face {
            position: absolute;
            width: 100%;
            height: 100%;
            -webkit-backface-visibility: hidden;
            backface-visibility: hidden;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: var(--white);
            border-radius: 12px;
            padding: 2rem;
            box-sizing: border-box;
            text-align: center;
        }
        .flashcard-back {
            transform: rotateY(180deg);
            background-color: var(--secondary);
            color: var(--white);
        }
        .word {
            font-size: 2.2rem;
            font-weight: bold;
            margin-bottom: 1rem;
            word-break: break-word;
        }
        .type-badge {
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            background: rgba(0,0,0,0.1);
            padding: 4px 8px;
            border-radius: 4px;
        }
        .flashcard-back .type-badge {
            background: rgba(255,255,255,0.2);
        }
        .navigation {
            display: flex;
            gap: 1rem;
            align-items: center;
        }
        .counter {
            font-size: 1.2rem;
            font-weight: bold;
            min-width: 80px;
            text-align: center;
        }
    </style>
</head>
<body>

    <h1>Grocery Shopping Vocabulary Deck</h1>
    
    <div class="controls">
            
        </select>
        <button onclick="shuffleCards()">Shuffle Deck</button>
    </div>

    <div class="flashcard-container" onclick="flipCard()">
        <div class="flashcard" id="flashcard">
            <div class="flashcard-face flashcard-front">
                <div class="word" id="es-word">Cargando...</div>
                <div class="type-badge" id="es-type">...</div>
            </div>
            <div class="flashcard-face flashcard-back">
                <div class="word" id="en-word">Loading...</div>
                <div class="type-badge" id="en-type">...</div>
            </div>
        </div>
    </div>

    <div class="navigation">
        <button onclick="prevCard()">&#8592; Previous</button>
        <div class="counter" id="counter">0 / 0</div>
        <button onclick="nextCard()">Next &#8594;</button>
    </div>

    <script>
        // Vocabulary Database
        // Paste your arrays below. Tag standard items with type: "noun", "verb", or "phrase".
        // Tag profanities with type: "profanity-noun", "profanity-verb", or "profanity-phrase".
        const allVocab = [

// --- NOUNS: Transportation & The City (150 Nouns) ---
    // Vehicles & Modes of Transit
    { es: "el transporte", en: "transportation", type: "noun" },
    { es: "el vehículo", en: "vehicle", type: "noun" },
    { es: "el coche", en: "car (Spain/Mexico)", type: "noun" },
    { es: "el carro", en: "car (LatAm)", type: "noun" },
    { es: "el automóvil", en: "automobile", type: "noun" },
    { es: "el autobús", en: "bus", type: "noun" },
    { es: "el camión", en: "truck / bus (Mexico)", type: "noun" },
    { es: "el colectivo", en: "bus (South America) / minibus", type: "noun" },
    { es: "la guagua", en: "bus (Caribbean / Canary Islands)", type: "noun" },
    { es: "el tren", en: "train", type: "noun" },
    { es: "el metro", en: "subway / metro", type: "noun" },
    { es: "el tranvía", en: "streetcar / tram", type: "noun" },
    { es: "el taxi", en: "taxi", type: "noun" },
    { es: "la bicicleta", en: "bicycle", type: "noun" },
    { es: "la motocicleta", en: "motorcycle", type: "noun" },
    { es: "la moto", en: "motorbike", type: "noun" },
    { es: "la furgoneta", en: "van", type: "noun" },
    { es: "la camioneta", en: "pickup truck / SUV", type: "noun" },
    { es: "el avión", en: "airplane", type: "noun" },
    { es: "el helicóptero", en: "helicopter", type: "noun" },
    { es: "el barco", en: "boat / ship", type: "noun" },
    { es: "el ferry", en: "ferry", type: "noun" },
    { es: "el transbordador", en: "ferry / shuttle", type: "noun" },
    { es: "el patinete", en: "scooter", type: "noun" },
    { es: "el monopatín", en: "skateboard", type: "noun" },

    // People
    { es: "el peatón", en: "pedestrian (male)", type: "noun" },
    { es: "la peatona", en: "pedestrian (female)", type: "noun" },
    { es: "el conductor", en: "driver", type: "noun" },
    { es: "el chofer", en: "chauffeur / driver", type: "noun" },
    { es: "el pasajero", en: "passenger", type: "noun" },
    { es: "el ciclista", en: "cyclist", type: "noun" },
    { es: "el piloto", en: "pilot", type: "noun" },
    { es: "el viajero", en: "traveler", type: "noun" },
    { es: "el turista", en: "tourist", type: "noun" },
    { es: "el agente de tránsito", en: "traffic officer", type: "noun" },

    // Infrastructure, Streets & Navigation
    { es: "la calle", en: "street", type: "noun" },
    { es: "la avenida", en: "avenue", type: "noun" },
    { es: "el bulevar", en: "boulevard", type: "noun" },
    { es: "el callejón", en: "alley", type: "noun" },
    { es: "la carretera", en: "highway / road", type: "noun" },
    { es: "la autopista", en: "freeway / expressway", type: "noun" },
    { es: "el carril", en: "lane", type: "noun" },
    { es: "la acera", en: "sidewalk (Spain/LatAm)", type: "noun" },
    { es: "la banqueta", en: "sidewalk (Mexico)", type: "noun" },
    { es: "la vereda", en: "sidewalk / path (South America)", type: "noun" },
    { es: "el cruce", en: "crossing / intersection", type: "noun" },
    { es: "la intersección", en: "intersection", type: "noun" },
    { es: "la esquina", en: "corner", type: "noun" },
    { es: "la cuadra", en: "block (LatAm)", type: "noun" },
    { es: "la manzana", en: "block (Spain) / apple", type: "noun" },
    { es: "la rotonda", en: "roundabout (Spain/LatAm)", type: "noun" },
    { es: "la glorieta", en: "roundabout (Mexico)", type: "noun" },
    { es: "el puente", en: "bridge", type: "noun" },
    { es: "el túnel", en: "tunnel", type: "noun" },
    { es: "el paso de cebra", en: "crosswalk (zebra crossing)", type: "noun" },
    { es: "el paso de peatones", en: "crosswalk", type: "noun" },
    { es: "el semáforo", en: "traffic light", type: "noun" },
    { es: "la señal", en: "sign / signal", type: "noun" },
    { es: "el letrero", en: "sign / billboard", type: "noun" },
    { es: "el mapa", en: "map", type: "noun" },
    { es: "la dirección", en: "address / direction", type: "noun" },
    { es: "el norte", en: "north", type: "noun" },
    { es: "el sur", en: "south", type: "noun" },
    { es: "el este", en: "east", type: "noun" },
    { es: "el oeste", en: "west", type: "noun" },
    { es: "el destino", en: "destination", type: "noun" },
    { es: "el origen", en: "origin", type: "noun" },
    { es: "la distancia", en: "distance", type: "noun" },
    { es: "el kilómetro", en: "kilometer", type: "noun" },
    { es: "la milla", en: "mile", type: "noun" },

    // Logistics, Travel & Traffic
    { es: "el tráfico", en: "traffic", type: "noun" },
    { es: "el tránsito", en: "traffic / transit", type: "noun" },
    { es: "el atasco", en: "traffic jam (Spain)", type: "noun" },
    { es: "el embotellamiento", en: "traffic jam (LatAm)", type: "noun" },
    { es: "el peaje", en: "toll", type: "noun" },
    { es: "la multa", en: "fine / ticket", type: "noun" },
    { es: "la infracción", en: "infraction / violation", type: "noun" },
    { es: "la velocidad", en: "velocity / speed", type: "noun" },
    { es: "el límite", en: "limit", type: "noun" },
    { es: "el viaje", en: "trip", type: "noun" },
    { es: "el recorrido", en: "route / tour", type: "noun" },
    { es: "el trayecto", en: "journey / route", type: "noun" },
    { es: "la estación", en: "station", type: "noun" },
    { es: "la parada", en: "stop (bus/train)", type: "noun" },
    { es: "la terminal", en: "terminal", type: "noun" },
    { es: "el andén", en: "platform (train)", type: "noun" },
    { es: "la taquilla", en: "ticket office", type: "noun" },
    { es: "el billete", en: "ticket (Spain)", type: "noun" },
    { es: "el boleto", en: "ticket (LatAm)", type: "noun" },
    { es: "el pasaje", en: "fare / ticket", type: "noun" },
    { es: "el abono", en: "pass / subscription", type: "noun" },
    { es: "la tarjeta", en: "card", type: "noun" },
    { es: "la tarifa", en: "fare / rate", type: "noun" },
    { es: "la ruta", en: "route", type: "noun" },
    { es: "el horario", en: "schedule", type: "noun" },

    // City Locations & Places
    { es: "el centro", en: "downtown / center", type: "noun" },
    { es: "las afueras", en: "outskirts / suburbs", type: "noun" },
    { es: "el suburbio", en: "suburb", type: "noun" },
    { es: "el barrio", en: "neighborhood", type: "noun" },
    { es: "el vecindario", en: "neighborhood (vicinity)", type: "noun" },
    { es: "la plaza", en: "plaza / square", type: "noun" },
    { es: "el parque", en: "park", type: "noun" },
    { es: "el monumento", en: "monument", type: "noun" },
    { es: "el edificio", en: "building", type: "noun" },
    { es: "el rascacielos", en: "skyscraper", type: "noun" },
    { es: "el aeropuerto", en: "airport", type: "noun" },
    { es: "el puerto", en: "port / harbor", type: "noun" },
    { es: "el estacionamiento", en: "parking lot (LatAm)", type: "noun" },
    { es: "el aparcamiento", en: "parking lot (Spain)", type: "noun" },
    { es: "el garaje", en: "garage", type: "noun" },
    { es: "el parquímetro", en: "parking meter", type: "noun" },
    { es: "el ayuntamiento", en: "city hall", type: "noun" },
    { es: "la alcaldía", en: "mayor's office", type: "noun" },
    { es: "la policía", en: "police (force/station)", type: "noun" },
    { es: "la estación de bomberos", en: "fire station", type: "noun" },
    { es: "el banco", en: "bank", type: "noun" },
    { es: "el hospital", en: "hospital", type: "noun" },
    { es: "la farmacia", en: "pharmacy", type: "noun" },
    { es: "la gasolinera", en: "gas station", type: "noun" },
    { es: "la estación de servicio", en: "service station", type: "noun" },

    // Vehicle Parts & Maintenance
    { es: "el motor", en: "engine / motor", type: "noun" },
    { es: "la rueda", en: "wheel", type: "noun" },
    { es: "la llanta", en: "tire (LatAm) / rim", type: "noun" },
    { es: "el neumático", en: "tire (Spain)", type: "noun" },
    { es: "el volante", en: "steering wheel", type: "noun" },
    { es: "el freno", en: "brake", type: "noun" },
    { es: "el acelerador", en: "accelerator", type: "noun" },
    { es: "el embrague", en: "clutch", type: "noun" },
    { es: "el espejo", en: "mirror", type: "noun" },
    { es: "el retrovisor", en: "rearview mirror", type: "noun" },
    { es: "el asiento", en: "seat", type: "noun" },
    { es: "el cinturón de seguridad", en: "seatbelt", type: "noun" },
    { es: "el maletero", en: "trunk (Spain)", type: "noun" },
    { es: "el baúl", en: "trunk (LatAm)", type: "noun" },
    { es: "el capó", en: "hood (of a car)", type: "noun" },
    { es: "la puerta", en: "door", type: "noun" },
    { es: "el parabrisas", en: "windshield", type: "noun" },
    { es: "el limpiaparabrisas", en: "windshield wiper", type: "noun" },
    { es: "el faro", en: "headlight", type: "noun" },
    { es: "la bocina", en: "horn (LatAm)", type: "noun" },
    { es: "el claxon", en: "horn (Spain/LatAm)", type: "noun" },
    { es: "la placa", en: "license plate (LatAm)", type: "noun" },
    { es: "la matrícula", en: "license plate (Spain)", type: "noun" },
    { es: "la gasolina", en: "gasoline", type: "noun" },
    { es: "el combustible", en: "fuel", type: "noun" },
    { es: "el tanque", en: "tank", type: "noun" },
    { es: "la llave", en: "key", type: "noun" },
    { es: "el seguro", en: "insurance", type: "noun" },
    { es: "la licencia", en: "license", type: "noun" },
    { es: "el casco", en: "helmet", type: "noun" },

    // --- VERBS: Moving, Traveling & Driving (50 Verbs) ---
    { es: "viajar", en: "to travel", type: "verb" },
    { es: "conducir", en: "to drive (Spain/LatAm)", type: "verb" },
    { es: "manejar", en: "to drive (LatAm)", type: "verb" },
    { es: "caminar", en: "to walk", type: "verb" },
    { es: "andar", en: "to walk / to go", type: "verb" },
    { es: "correr", en: "to run", type: "verb" },
    { es: "pasear", en: "to go for a walk / to stroll", type: "verb" },
    { es: "cruzar", en: "to cross", type: "verb" },
    { es: "parar", en: "to stop", type: "verb" },
    { es: "detenerse", en: "to stop oneself", type: "verb" },
    { es: "esperar", en: "to wait", type: "verb" },
    { es: "subir", en: "to get on / to go up", type: "verb" },
    { es: "bajar", en: "to get off / to go down", type: "verb" },
    { es: "montar", en: "to ride (bike/horse)", type: "verb" },
    { es: "ir", en: "to go", type: "verb" },
    { es: "venir", en: "to come", type: "verb" },
    { es: "llegar", en: "to arrive", type: "verb" },
    { es: "salir", en: "to leave / to go out", type: "verb" },
    { es: "partir", en: "to depart", type: "verb" },
    { es: "doblar", en: "to turn", type: "verb" },
    { es: "girar", en: "to spin / to turn", type: "verb" },
    { es: "seguir", en: "to follow / to continue", type: "verb" },
    { es: "continuar", en: "to continue", type: "verb" },
    { es: "perderse", en: "to get lost", type: "verb" },
    { es: "encontrar", en: "to find", type: "verb" },
    { es: "tomar", en: "to take (transportation)", type: "verb" },
    { es: "coger", en: "to take/catch (Spain - CAUTION: offensive in some LatAm)", type: "verb" },
    { es: "aparcar", en: "to park (Spain)", type: "verb" },
    { es: "estacionar", en: "to park (LatAm)", type: "verb" },
    { es: "volar", en: "to fly", type: "verb" },
    { es: "navegar", en: "to sail / to navigate", type: "verb" },
    { es: "acelerar", en: "to accelerate / to speed up", type: "verb" },
    { es: "frenar", en: "to brake", type: "verb" },
    { es: "chocar", en: "to crash", type: "verb" },
    { es: "alquilar", en: "to rent (Spain)", type: "verb" },
    { es: "rentar", en: "to rent (LatAm)", type: "verb" },
    { es: "cargar", en: "to load / to charge", type: "verb" },
    { es: "llenar", en: "to fill (a tank)", type: "verb" },
    { es: "reparar", en: "to repair", type: "verb" },
    { es: "arreglar", en: "to fix", type: "verb" },
    { es: "revisar", en: "to check / to inspect", type: "verb" },
    { es: "reservar", en: "to reserve", type: "verb" },
    { es: "cancelar", en: "to cancel", type: "verb" },
    { es: "planear", en: "to plan", type: "verb" },
    { es: "abordar", en: "to board (plane/train)", type: "verb" },
    { es: "transbordar", en: "to transfer", type: "verb" },
    { es: "retroceder", en: "to back up / go in reverse", type: "verb" },
    { es: "adelantar", en: "to pass (another car)", type: "verb" },
    { es: "multar", en: "to fine / to ticket", type: "verb" },
    { es: "guiar", en: "to guide", type: "verb" },


  ];

        let currentDeck = [...allVocab];
        let currentIndex = 0;

        const cardElement = document.getElementById('flashcard');
        const esWordElement = document.getElementById('es-word');
        const enWordElement = document.getElementById('en-word');
        const esTypeElement = document.getElementById('es-type');
        const enTypeElement = document.getElementById('en-type');
        const counterElement = document.getElementById('counter');

        function updateCard() {
            if (currentDeck.length === 0) {
                esWordElement.textContent = "No cards";
                enWordElement.textContent = "No cards";
                esTypeElement.textContent = "";
                enTypeElement.textContent = "";
                counterElement.textContent = "0 / 0";
                return;
            }

            cardElement.classList.remove('is-flipped');
            
            setTimeout(() => {
                const card = currentDeck[currentIndex];
                esWordElement.textContent = card.es;
                enWordElement.textContent = card.en;
                esTypeElement.textContent = card.type;
                enTypeElement.textContent = card.type;
                counterElement.textContent = `${currentIndex + 1} / ${currentDeck.length}`;
            }, 150);
        }

        function flipCard() {
            if (currentDeck.length > 0) {
                cardElement.classList.toggle('is-flipped');
            }
        }

        function nextCard() {
            if (currentDeck.length > 0) {
                currentIndex = (currentIndex + 1) % currentDeck.length;
                updateCard();
            }
        }

        function prevCard() {
            if (currentDeck.length > 0) {
                currentIndex = (currentIndex - 1 + currentDeck.length) % currentDeck.length;
                updateCard();
            }
        }

        function filterCards() {
            const filterValue = document.getElementById('typeFilter').value;
            
            if (filterValue === 'all') {
                currentDeck = [...allVocab];
            } else if (filterValue === 'clean') {
                // Exclude any type starting with 'profanity-'
                currentDeck = allVocab.filter(word => !word.type.startsWith('profanity-'));
            } else if (filterValue === 'profanity-only') {
                // Include only types starting with 'profanity-'
                currentDeck = allVocab.filter(word => word.type.startsWith('profanity-'));
            } else {
                // Filter by specific clean category (noun, verb, phrase)
                currentDeck = allVocab.filter(word => word.type === filterValue);
            }
            
            currentIndex = 0;
            updateCard();
        }

        function shuffleCards() {
            for (let i = currentDeck.length - 1; i > 0; i--) {
                const j = Math.floor(Math.random() * (i + 1));
                [currentDeck[i], currentDeck[j]] = [currentDeck[j], currentDeck[i]];
            }
            currentIndex = 0;
            updateCard();
        }

        updateCard();
    </script>
</body>
</html>
