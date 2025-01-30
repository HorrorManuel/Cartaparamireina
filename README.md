# Cartaparamireina<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Mi Amor</title>
    <link rel="stylesheet" href="diseño.css">
    
</head>
<body>
   </a>
    <div class="carta">
        <h1>Para mi hermosa princesa 💖</h1>
        <p class="mensaje">Eres mi persona especial, la que ilumina mis días aunque a veces estés triste. Quiero recordarte que eres increíble, fuerte y mereces toda la felicidad del mundo. 🥰</p>
        <button id="mostrarMensaje">Haz clic aquí</button>
        <p id="mensajeOculto" class="oculto">Nunca olvides que estoy aquí para ti, en las buenas y en las malas. Te amo con todo mi corazón. 💕</p>
    </div>
    <script src="script.js"></script>
</body>
</html>

body {
    font-family: 'Arial', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #ffe4e1;
    margin: 0;
}

.carta {
    background: white;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

h1 {
    color: #ff69b4;
}

.mensaje {
    font-size: 18px;
    color: #333;
}

button {
    background: #ff1493;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 10px;
    font-size: 16px;
}

button:hover {
    background: #ff69b4;
}

.oculto {
    display: none;
    margin-top: 10px;
    font-size: 16px;
    color: #ff1493;
}

document.getElementById("mostrarMensaje").addEventListener("click", function() {
    var mensaje = document.getElementById("mensajeOculto");
    if (mensaje.style.display === "none" || mensaje.style.display === "") {
        mensaje.style.display = "block";
    } else {
        mensaje.style.display = "none";
    }
});


