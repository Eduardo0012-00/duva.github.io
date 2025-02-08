<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        .message {
            text-align: center;
            font-size: 2em;
            color: #ff69b4;
            font-style: italic; 
        }
        .image {
            margin-bottom: 20px;
        }
        .buttons {
            display: flex;
            gap: 10px;
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .yes {
            background-color: #ff69b4;
            color: white;
        }
        .no {
            background-color: #cccccc;
            color: black;
        }
    </style>
    <script>
        function redirectToYouTube() {
            window.location.href = "https://youtu.be/juvFdrsO8Rw?si=G-K_Z7iUFR8imwF6"; 
        }
        function redirectToAnotherYouTube() {
            window.location.href = "https://youtu.be/c3ds4gMuEeY?si=S3gaIJllOJmgvM1e"; 
        }
    </script>
</head>
<body>
    <div class="image">
        <img src="https://i.pinimg.com/736x/e1/f2/f4/e1f2f426dcce3d9ce4e4c04f6705180b.jpg"
        " alt="Imagen de San Valentín" width="300">
    </div>
    <div class="message">
        ¿Quieres ser mi san Valentín?
    </div>
    <div class="buttons">
        <button class="yes" onclick="redirectToYouTube()">Sí</button>
        <button class="no" onclick="redirectToAnotherYouTube()">No</button>
    </div>
</body>
</html>
