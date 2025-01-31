# san-valentin
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://www.w3schools.com/w3images/flowers.jpg'); /* Cambia esta URL por una imagen de flores que te guste */
            background-size: cover;
            background-position: center;
            color: white;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }

        h1 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        button {
            background-color: #ff4d4d;
            color: white;
            font-size: 1.2em;
            border: none;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #ff3333;
        }

        .message {
            display: none;
            margin-top: 20px;
            font-size: 1.5em;
            color: #ffccff;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>¿Quieres ser mi San Valentín?</h1>
        <button id="yesBtn">¡Sí!</button>
        <button id="noBtn">No</button>
        <p id="message" class="message">¡Por otro 14 de febrero juntas, linda <3</p>
    </div>

    <script>
        // Función para mostrar el mensaje cuando se hace clic en "Sí"
        document.getElementById("yesBtn").addEventListener("click", function() {
            document.getElementById("message").style.display = "block";
        });

        // Función para ocultar el mensaje si se hace clic en "No"
        document.getElementById("noBtn").addEventListener("click", function() {
            alert("¡Espero que reconsideres! 😢");
        });
    </script>

</body>
</html>
