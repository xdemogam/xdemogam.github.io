<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fullscreen Modd.io Game</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: white; /* Background color */
        }
        .game-container {
            width: 100vw; /* Full width */
            height: 80vh; /* Adjust height */
            max-width: 1600px; /* Optional max width (change if needed) */
        }
        iframe {
            width: 100%; /* Fill container width */
            height: 100%; /* Fill container height */
            border: none;
        }
    </style>
</head>
<body>
    <div class="game-container">
        <iframe src="https://www.modd.io/play/demogamgomoke/" allowfullscreen></iframe>
    </div>
</body>
</html>
