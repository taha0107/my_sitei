# my_sitei<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalp İçinde D</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        .heart-container {
            position: relative;
            width: 200px;
            height: 200px;
        }

        /* Kalp şekli */
        .heart {
            width: 100%;
            height: 100%;
            background-color: red;
            clip-path: polygon(50% 0%, 100% 35%, 80% 100%, 50% 75%, 20% 100%, 0% 35%);
            position: absolute;
        }

        /* D harfi */
        .letter {
            position: absolute;
            top: 30%;
            left: 50%;
            transform: translateX(-50%) translateY(-50%);
            font-size: 80px;
            font-weight: bold;
            color: white;
        }

    </style>
</head>
<body>
    <div class="heart-container">
        <div class="heart"></div>
        <div class="letter">D</div>
    </div>
</body>
</html>
