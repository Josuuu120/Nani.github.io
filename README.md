<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        h1 {
            font-size: 2.5rem;
            margin: 20px 0;
        }
        .highlight {
            background-color: #cce5ff;
            padding: 5px 10px;
            border-radius: 5px;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }
        img {
            max-width: 150px;
            border-radius: 10px;
        }
        .buttons {
            display: flex;
            gap: 20px;
        }
        .button {
            background-color: #d1c4e9;
            color: black;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            border-radius: 10px;
            font-size: 1.2rem;
            font-weight: bold;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            cursor: pointer;
            border: none;
        }
        .button:hover {
            background-color: #b39ddb;
        }
    </style>
</head>
<body>
    <h1>¿PUEDO SER TU SAN VALENTÍN <span class="highlight">BELÉN (NANI)</span>?</h1>
    <div class="container">
        <div>
            <img src="https://via.placeholder.com/150" alt="Imagen 1">
            <img src="https://via.placeholder.com/150" alt="Imagen 2">
        </div>
        <div class="buttons">
            <!-- Formulario para la primera opción -->
            <form action="pagina1.html" method="get">
                <button type="submit" class="button">SÍ</button>
            </form>
            <!-- Formulario para la segunda opción -->
            <form action="pagina2.html" method="get">
                <button type="submit" class="button">SÍ</button>
            </form>
        </div>
    </div>
</body>
</html>
