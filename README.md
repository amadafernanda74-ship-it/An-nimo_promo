<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Loja da Juciana</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #ff4081;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 1.5em;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .produto {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }

    .produto img {
      max-width: 100%;
      border-radius: 5px;
    }

    .produto h2 {
      margin: 10px 0;
      color: #333;
    }

    .produto p {
      color: #666;
    }

    .produto a {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #ff4081;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    .produto a:hover {
      background-color: #e91e63;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    #musica {
      position: fixed;
      bottom: 10px;
      right: 10px;
    }
  </style>
</head>
<body>

<header>🌸 Loja da Juciana</header>

<div class="container">
  <div class="produto">
    <img src="imagem-produto1.jpg" alt="Produto 1">
    <h2>Produto 1</h2>
    <p>Descrição do Produto 1.</p>
    <a href="https://link-do-produto1.com" target="_blank">Comprar</a>
  </div>

  <div class="produto">
    <img src="imagem-produto2.jpg" alt="Produto 2">
    <h2>Produto 2</h2>
    <p>Descrição do Produto 2.</p>
    <a href="https://link-do-produto2.com" target="_blank">Comprar</a>
  </div>

  <!-- Adicione mais produtos aqui -->
</div>

<footer>
  © 2025 Loja da Juciana — Todos os direitos reservados
</footer>

<div id="musica">
  <audio controls loop>
    <source src="sua-musica.mp3" type="audio/mpeg">
    Seu navegador não suporta o elemento audio.
  </audio>
</div>

<script>
  window.addEventListener('load', function() {
    var audio = document.querySelector('#musica audio');
    // audio.play(); // Descomente se quiser autoplay
  });
</script>

</body>
</html>
