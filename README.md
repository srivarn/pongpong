# pongpong
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ping Pong Game</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        canvas {
            border: 2px solid black;
        }
    </style>
</head>
<body>
    <div class="container text-center">
        <canvas id="gameCanvas" width="800" height="400"></canvas>
        <button id="startButton" class="btn btn-primary">Start Game</button>
        <button id="pauseButton" class="btn btn-secondary">Pause Game</button>
        <button id="resetButton" class="btn btn-danger">Reset Game</button>
        <p>Use the arrow keys to control the paddles.</p>
    </div>

    <script src="pingpong.js"></script>
</body>
</html>
