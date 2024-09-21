<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tulipanes Amarillos</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .tulipan {
            fill: yellow;
            stroke: black;
            stroke-width: 2px;
        }
        .hojas {
            fill: green;
        }
    </style>
</head>
<body>
    <svg width="200" height="400" viewBox="0 0 200 400" xmlns="http://www.w3.org/2000/svg">
        <!-- Tallo -->
        <rect x="95" y="150" width="10" height="200" fill="green" />
        
        <!-- Hojas -->
        <path class="hojas" d="M 90 200 Q 50 300 90 250 Q 70 270 110 250 Q 150 300 110 200 Z" />
        
        <!-- Pétalos del tulipán -->
        <path class="tulipan" d="M 100 150 Q 70 100 80 150 Q 50 120 60 150 Q 90 120 100 180 Q 110 120 140 150 Q 150 120 120 150 Q 130 100 100 150 Z" />
    </svg>
</body>
</html>
