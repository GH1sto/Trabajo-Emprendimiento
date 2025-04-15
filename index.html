<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ahorrópolis - Juego Educativo Financiero</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #e2f0cb, #cbe2f0);
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4CAF50;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #388E3C;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 20px;
    }
    section {
      margin-bottom: 30px;
    }
    h2 {
      color: #2e7d32;
    }
    .card {
      background-color: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-bottom: 10px;
    }
    #jugar {
      display: none;
      text-align: center;
      padding: 20px;
    }
    #board {
      display: grid;
      grid-template-columns: repeat(5, 80px);
      grid-template-rows: repeat(5, 80px);
      gap: 5px;
      justify-content: center;
      margin: 20px auto;
    }
    .tile {
      background-color: #fff;
      border: 2px solid #4CAF50;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 12px;
      text-align: center;
      padding: 5px;
      position: relative;
    }
    .player {
      position: absolute;
      width: 15px;
      height: 15px;
      background-color: red;
      border-radius: 50%;
      bottom: 5px;
      right: 5px;
      transition: all 0.5s ease;
    }
    #rollButton {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    #dice {
      width: 50px;
      height: 50px;
      margin: 10px auto;
      font-size: 24px;
      background: white;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      border: 2px solid #388E3C;
    }
    #result {
      margin-top: 20px;
      font-size: 18px;
      font-weight: bold;
    }
    #triviaOptions button,
    #decisionOptions button,
    #minijuego button,
    #continueButton {
      margin: 5px;
      padding: 10px;
      border-radius: 5px;
      border: none;
      cursor: pointer;
      background-color: #4CAF50;
      color: white;
    }
    footer {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ahorrópolis – Un juego educativo financiero</h1>
  </header>
  <nav>
    <a href="#" onclick="mostrar('informacion')">Inicio</a>
    <a href="#" onclick="mostrar('jugar')">Jugar</a>
  </nav>
  <main>
    <section id="informacion">
      <div class="card">
        <h2>Instrucciones del Juego</h2>
        <p>Bienvenido a <strong>Ahorrópolis</strong>, un juego educativo financiero para jóvenes y adultos donde aprenderás sobre ahorro y finanzas personales de manera divertida.</p>
        <ul>
          <li><strong>🎲 Tablero tipo Monopoly:</strong> avanza lanzando un dado virtual.</li>
          <li><strong>💵 Gana Dinero:</strong> trabajos o inversiones exitosas.</li>
          <li><strong>⚠️ Pérdidas:</strong> gastos inesperados o malas decisiones.</li>
          <li><strong>📚 Educación Financiera:</strong> responde trivia para ganar premios.</li>
          <li><strong>🔀 Decisiones:</strong> elige cómo gastar, invertir o ahorrar.</li>
          <li><strong>🎯 Objetivo:</strong> alcanzar metas financieras antes que los demás.</li>
        </ul>
        <p>Haz clic en "Jugar" para comenzar tu aventura financiera. ¡Mucho éxito!</p>
      </div>
    </section>
    <section id="jugar">
      <h2>🎲 ¡Juega Ahorrópolis!</h2>
      <div class="card">
        <h3>Bienvenido a Ahorrópolis</h3>
        <p>Hola jugador, en este juego recorrerás un tablero donde cada casilla representa una situación financiera.</p>
        <ul>
          <li>🎲 Lanza el dado para avanzar.</li>
          <li>📚 Responde preguntas para ganar dinero.</li>
          <li>🔀 Toma decisiones para mejorar tus finanzas.</li>
          <li>💵 Acumula dinero a medida que avanzas.</li>
        </ul>
        <p>Ingresa tu nombre y presiona "Lanzar dado" para comenzar. ¡Buena suerte!</p>
      </div>
      <input type="text" id="playerName" placeholder="Ingresa tu nombre">
      <div id="money">💵 Dinero: $0</div>
      <div id="dice">🎲</div>
      <div id="board"></div>
      <button id="rollButton">Lanzar dado</button>
      <div id="result"></div>
      <div id="triviaOptions"></div>
      <div id="decisionOptions"></div>
      <div id="minijuego"></div>
      <div id="continueContainer"></div>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Ahorrópolis. Todos los derechos reservados. | Juan Yoandry Feliz </p>
  </footer>
  <script>
    const board = document.getElementById("board");
    const triviaPreguntas = [
      { pregunta: "¿Qué es un presupuesto?", opciones: [ { texto: "A) Lista de compras", correcta: false }, { texto: "B) Plan de ingresos y gastos", correcta: true }, { texto: "C) Contraseña bancaria", correcta: false } ] },
      { pregunta: "¿Qué es el interés compuesto?", opciones: [ { texto: "A) Ganancia sobre ganancia anterior", correcta: true }, { texto: "B) Pago mensual", correcta: false }, { texto: "C) Crédito rápido", correcta: false } ] },
      { pregunta: "¿Qué es una inversión?", opciones: [ { texto: "A) Gasto innecesario", correcta: false }, { texto: "B) Poner dinero para obtener ganancia futura", correcta: true }, { texto: "C) Comprar ropa", correcta: false } ] }
    ];

    const outcomes = [
      "💰 Gana Dinero: Recibes $200 por un trabajo exitoso.",
      "❌ Pérdida: Pagas $150 por un gasto inesperado.",
      "🔀 Decisión Financiera: ¿Ahorrar o gastar? Tú decides.",
      "📚 Educación Financiera",
      "🎁 Oportunidad: Ganas una beca. Avanzas 2 casillas.",
      "⚠️ Riesgo: No pagaste una deuda. Pierdes un turno.",
      "🏁 Reto: Ahorra $1000 en 3 turnos para bono de $500."
    ];

    const tiles = 25;
    let position = 0;
    let dinero = 0;
    let pierdeTurno = false;

    for (let i = 0; i < tiles; i++) {
      const tile = document.createElement("div");
      tile.className = "tile";
      tile.textContent = outcomes[i % outcomes.length].split(':')[0];
      tile.id = `tile-${i}`;
      board.appendChild(tile);
    }

    const player = document.createElement("div");
    player.className = "player";
    document.getElementById("tile-0").appendChild(player);

    document.getElementById("rollButton").addEventListener("click", () => {
      document.getElementById("rollButton").disabled = true;
      jugarTurno();
    });

    function jugarTurno() {
      if (pierdeTurno) {
        alert("Perdiste este turno. Espera al siguiente.");
        pierdeTurno = false;
        document.getElementById("rollButton").disabled = false;
        return;
      }

      const name = document.getElementById("playerName").value.trim();
      if (!name) {
        alert("Por favor ingresa tu nombre para jugar.");
        document.getElementById("rollButton").disabled = false;
        return;
      }

      document.getElementById("triviaOptions").innerHTML = "";
      document.getElementById("decisionOptions").innerHTML = "";
      document.getElementById("minijuego").innerHTML = "";
      document.getElementById("continueContainer").innerHTML = "";

      let diceDisplay = document.getElementById("dice");
      diceDisplay.textContent = "🎲";

      setTimeout(() => {
        const roll = Math.floor(Math.random() * 6) + 1;
        diceDisplay.textContent = roll;

        position += roll;
        if (position >= tiles) {
          position %= tiles;
          dinero += 100;
        }

        const newTile = document.getElementById(`tile-${position}`);
        newTile.appendChild(player);

        const outcome = outcomes[position % outcomes.length];
        document.getElementById("result").textContent = `🎲 ${name} lanzó: ${roll}. ${outcome}`;

        if (outcome.includes("Educación Financiera")) {
          const pregunta = triviaPreguntas[Math.floor(Math.random() * triviaPreguntas.length)];
          document.getElementById("result").textContent += `: ${pregunta.pregunta}`;

          pregunta.opciones.forEach(op => {
            const btn = document.createElement("button");
            btn.textContent = op.texto;
            btn.onclick = () => {
              if (op.correcta) {
                dinero += 100;
                alert("✅ ¡Correcto! Ganas $100.");
              } else {
                alert("❌ Incorrecto. No avanzas el próximo turno.");
                pierdeTurno = true;
              }
              document.getElementById("money").textContent = `💵 Dinero: $${dinero}`;
              document.getElementById("triviaOptions").innerHTML = "";
              mostrarBotonContinuar();
            };
            document.getElementById("triviaOptions").appendChild(btn);
          });
        } else if (outcome.includes("Decisión Financiera")) {
          const decisiones = [
            { texto: "Ahorrar: ganas $50.", efecto: () => dinero += 50 },
            { texto: "Gastar: pierdes $50.", efecto: () => dinero -= 50 }
          ];
          decisiones.forEach(dec => {
            const btn = document.createElement("button");
            btn.textContent = dec.texto;
            btn.onclick = () => {
              dec.efecto();
              alert("Elección tomada: " + dec.texto);
              document.getElementById("money").textContent = `💵 Dinero: $${dinero}`;
              document.getElementById("decisionOptions").innerHTML = "";
              mostrarBotonContinuar();
            };
            document.getElementById("decisionOptions").appendChild(btn);
          });
        } else if (outcome.includes("Reto")) {
          const minijuegos = [
            () => document.getElementById("minijuego").innerHTML = '<p>🧩 Minijuego: Adivina un número entre 1 y 3.</p><button onclick="verificarNumero(1)">1</button><button onclick="verificarNumero(2)">2</button><button onclick="verificarNumero(3)">3</button>',
            () => document.getElementById("minijuego").innerHTML = '<p>🧠 Minijuego: ¿Cuál es el símbolo del peso dominicano?</p><button onclick="verificarSimbolo(\'\$\')">$</button><button onclick="verificarSimbolo(\'RD$\')">RD$</button><button onclick="verificarSimbolo(\'€\')">€</button>',
            () => document.getElementById("minijuego").innerHTML = '<p>🎯 Minijuego: ¿Cuál de estas es una buena práctica financiera?</p><button onclick="verificarPractica(true)">Ahorrar regularmente</button><button onclick="verificarPractica(false)">Gastar todo</button>'
          ];
          const minijuego = minijuegos[Math.floor(Math.random() * minijuegos.length)];
          minijuego();
        } else {
          if (outcome.includes("Gana Dinero")) dinero += 200;
          if (outcome.includes("Pérdida")) dinero -= 150;
          if (outcome.includes("Riesgo")) pierdeTurno = true;
          if (outcome.includes("Oportunidad")) {
            position = Math.min(position + 2, tiles - 1);
            document.getElementById(`tile-${position}`).appendChild(player);
          }
          document.getElementById("money").textContent = `💵 Dinero: $${dinero}`;
          mostrarBotonContinuar();
        }
      }, 500);
    }

    function mostrarBotonContinuar() {
      const btn = document.createElement("button");
      btn.id = "continueButton";
      btn.textContent = "Siguiente turno";
      btn.onclick = () => {
        document.getElementById("continueContainer").innerHTML = "";
        document.getElementById("rollButton").disabled = false;
      };
      document.getElementById("continueContainer").appendChild(btn);
    }

    function verificarNumero(num) {
      const correcto = Math.floor(Math.random() * 3) + 1;
      if (num === correcto) {
        alert("🎉 ¡Correcto! Ganas $200.");
        dinero += 200;
      } else {
        alert("😓 Fallaste. Intenta mejor la próxima vez.");
      }
      document.getElementById("minijuego").innerHTML = "";
      document.getElementById("money").textContent = `💵 Dinero: $${dinero}`;
      mostrarBotonContinuar();
    }

    function verificarSimbolo(respuesta) {
      if (respuesta === "RD$") {
        alert("✅ ¡Correcto! Ganas $200.");
        dinero += 200;
      } else {
        alert("❌ Incorrecto.");
      }
      document.getElementById("minijuego").innerHTML = "";
      document.getElementById("money").textContent = `💵 Dinero: $${dinero}`;
      mostrarBotonContinuar();
    }

    function verificarPractica(correcta) {
      if (correcta) {
        alert("👏 ¡Muy bien! Ganas $200.");
        dinero += 200;
      } else {
        alert("❌ Esa no es una buena práctica.");
      }
      document.getElementById("minijuego").innerHTML = "";
      document.getElementById("money").textContent = `💵 Dinero: $${dinero}`;
      mostrarBotonContinuar();
    }

    function mostrar(id) {
      document.getElementById("informacion").style.display = id === 'informacion' ? 'block' : 'none';
      document.getElementById("jugar").style.display = id === 'jugar' ? 'block' : 'none';
    }
    mostrar('informacion');
  </script>
</body>
</html>
