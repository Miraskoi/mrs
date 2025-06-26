<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Анимация Айгерим</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1a1a1a, #2a2a2a);
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      font-family: 'Segoe UI', sans-serif;
    }

    .glow-text {
      font-size: 4rem;
      font-weight: bold;
      background: linear-gradient(90deg, #ff5f6d, #ffc371);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-align: center;
      animation: glow 2s ease-in-out infinite alternate;
      margin: 20px 0;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #ff5f6d, 0 0 20px #ff5f6d, 0 0 30px #ffc371;
      }
      to {
        text-shadow: 0 0 20px #ffc371, 0 0 30px #ff5f6d, 0 0 40px #ff5f6d;
      }
    }
  </style>
</head>
<body>
  <div class="glow-text">Айгерим Л</div>
  <div class="glow-text">Айгерим Ч</div>
</body>
</html>
