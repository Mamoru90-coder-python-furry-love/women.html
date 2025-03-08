<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>З 8 Березня! 🌸</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            text-align: center;
            padding: 20px;
            color: white;
            overflow: hidden;
        }
        .card {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            display: inline-block;
            max-width: 90%;
            width: 400px;
            color: black;
            animation: fadeIn 1.5s ease-in-out;
        }
        h1 {
            color: #ff4f72;
            font-size: 26px;
            animation: bounce 1s infinite alternate;
        }
        p {
            font-size: 18px;
            color: #444;
        }
        .btn {
            background: #ff4f72;
            color: white;
            padding: 12px 20px;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            transition: 0.3s;
        }
        .btn:hover {
            background: #d12c58;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes bounce {
            from { transform: scale(1); }
            to { transform: scale(1.05); }
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>З 8 Березня, Дівчата! 💐</h1>
        <p>Нехай цей день буде наповнений радістю, ніжністю та посмішками! <br>
        Бажаю вам море щастя, весняного тепла і здійснення мрій! 💖</p>
        <button class="btn" onclick="playMusic()">🎶 Увімкнути музику</button>
    </div>

    <audio id="bgMusic" loop>
        <source src="https://www.bensound.com/bensound-music/bensound-littleidea.mp3" type="audio/mpeg">
        Ваш браузер не підтримує аудіо.
    </audio>

    <script>
        function playMusic() {
            let audio = document.getElementById("bgMusic");
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }
    </script>

</body>
</html>
