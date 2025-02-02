<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín, Mi Vannie? ❤️</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            margin: 0;
            padding: 0;
            background-image: url('https://www.transparenttextures.com/patterns/hearts.png');
            background-size: cover;
        }
        .container {
            margin-top: 50px;
        }
        h1 {
            color: #ff4d4d;
            font-size: 40px;
            text-shadow: 3px 3px 6px rgba(255, 0, 0, 0.5);
        }
        .gif-container {
            margin: 20px 0;
        }
        .message {
            font-size: 24px;
            color: #d14747;
            margin-bottom: 20px;
            font-weight: bold;
            background: #fff0f5;
            padding: 15px;
            border-radius: 15px;
            box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
        }
        .buttons {
            margin-top: 20px;
            position: relative;
        }
        button {
            font-size: 22px;
            padding: 12px 25px;
            margin: 10px;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            box-shadow: 4px 4px 12px rgba(0, 0, 0, 0.3);
        }
        .yes {
            background-color: #ff4d4d;
            color: white;
            transition: transform 0.2s;
        }
        .yes:hover {
            transform: scale(1.2);
        }
        .no {
            background-color: #ccc;
            color: black;
            position: absolute;
        }
        .heart {
            font-size: 60px;
            animation: heartbeat 1.5s infinite;
            color: red;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¿Quieres ser mi San Valentín, Mi Vannie? ❤️</h1>
        <div class="gif-container">
            <img src="https://media.giphy.com/media/ZBQhoZC0nqknSviPqT/giphy.gif" alt="Ositos abrazándose" width="300">
        </div>
        
        <p class="message">Mi Vannie, desde el primer día en que te vi, supe que eras alguien especial, mi cachetoncita. 💕 Cada momento contigo es mágico, mi wawita, y no hay nadie más con quien quiera compartir este día. Eres mi alegría, mi razón de sonreír y mi persona favorita en el mundo. 💖
        <br><br>Te prometo hacer de este día (y todos los demás) algo inolvidable. 🌹✨</p>
        <div class="heart">💘</div>
        <div class="buttons">
            <button class="yes" onclick="alert('¡Sabía que dirías que sí! ❤️ Te amo, Mi Vannie!')">Sí</button>
            <button class="no" onmouseover="moverBoton(this)">No</button>
        </div>
    </div>
    <script>
        function moverBoton(boton) {
            const x = Math.random() * (window.innerWidth - boton.clientWidth);
            const y = Math.random() * (window.innerHeight - boton.clientHeight);
            boton.style.left = `${x}px`;
            boton.style.top = `${y}px`;
        }
    </script>
</body>
</html>
