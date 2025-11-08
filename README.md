<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lembre-se que você vai morrer</title>
  
  <!-- Fonte Cinzel do Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      height: 100vh;
      background-color: #000; /* Fundo preto */
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Cinzel', serif; /* Fonte aplicada */
      overflow: hidden;
    }

    .neon-text {
      color: #fff;
      font-size: 3em;
      text-align: center;
      letter-spacing: 3px;
      text-transform: uppercase;
      text-shadow:
        0 0 5px #fff,
        0 0 10px #fff,
        0 0 20px #fff,
        0 0 40px #ff5555,
        0 0 80px #ff5555,
        0 0 90px #ff5555;
      animation: glow 2s ease-in-out infinite alternate;
      padding: 0 10px;
    }

    @keyframes glow {
      from {
        text-shadow:
          0 0 5px #fff,
          0 0 10px #fff,
          0 0 20px #fff,
          0 0 40px #ff5555,
          0 0 80px #ff5555,
          0 0 90px #ff5555;
      }
      to {
        text-shadow:
          0 0 10px #fff,
          0 0 20px #fff,
          0 0 30px #fff,
          0 0 60px #ff5555,
          0 0 100px #ff5555,
          0 0 120px #ff5555;
      }
    }
  </style>
</head>
<body>
  <div class="neon-text"> Lembre-se que você vai morrer </div>
</body>
</html>