<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day ❤️</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            padding: 50px;
        }
        button {
            background-color: #ff4d4d;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #cc0000;
        }
        #message {
            margin-top: 20px;
            font-size: 24px;
            color: #cc0000;
        }
    </style>
</head>
<body>
    <h1>สุขสันต์วันวาเลนไทน์ ❤️</h1>
    <p>กดปุ่มนี้เพื่อรับข้อความพิเศษจากฉันถึงเธอ!</p>
    <button onclick="showMessage()">กดเลย!</button>
    <p id="message"></p>

    <script>
        function showMessage() {
            const messages = [
                "รักเธอที่สุดในโลกกกกกก ❤️",
                "🌹",
                "สุขสันต์วันวาเลนไทน์นะคะ 💕",
                "ขอบคุณที่อยู่ข้างๆเค้าเสมอ 🥰",
                "ขอให้เรารักกันตลอดไปนะ 💞"
            ];
            const randomMessage = messages[Math.floor(Math.random() * messages.length)];
            document.getElementById("message").textContent = randomMessage;
        }
    </script>
</body>
</html>
