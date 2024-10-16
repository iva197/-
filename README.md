<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Простой сайт</title>
  <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
        }
        #message {
            display: none; /* Скрываем текст изначально */
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
<button id="myButton">Нажми на меня</button>
<div id="message">Андрей пидор</div>
<script>
        document.getElementById('myButton').onclick = function() {
            this.style.display = 'none'; // Скрываем кнопку
            document.getElementById('message').style.display = 'block'; // Показываем текст
        };
    </script>
</body>
</html>
