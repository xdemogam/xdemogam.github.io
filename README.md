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
            background-color: black; /* Optional background */
        }
        .game-container {
            width: 80vw; /* Adjust width as needed */
            height: 80vh; /* Adjust height as needed */
            max-width: 1280px; /* Optional max width */
            max-height: 720px; /* Optional max height */
        }
        iframe {
            width: 100%;
            height: 100%;
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
