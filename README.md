<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Barra de Navegação</title>
  <style>
    /* Estilos básicos */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* Barra de navegação */
    nav {
      background-color: #666464;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    /* Logo ou nome do site */
    .logo {
      color: rgb(12, 12, 12);
      font-size: 1.5em;
      font-weight: bold;
      text-decoration: none;
    }

    /* Lista de links */
    .nav-links {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;    
      gap: 20px;
    }

    .nav-links li a {
      color: rgb(13, 13, 13);
      text-decoration: none;
      font-size: 1em;
      transition: color 0.3s ease;
    }

    .nav-links li a:hover {
      color: #440e39;
    }

    /* Responsividade (exemplo simples) */
    @media (max-width: 600px) {
      .nav-links {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>

  <nav>
    <a href="#" class="logo">Início</a></li>
    <ul class="nav-links">
    
      <li><a href="Migaz.html"></a></li>
      <li><a href="https://animesonlinecc.to/episodio/">Episodios</a></li>
      <li><a href="https://animesonlinecc.to/generos/">Gêneros</a></li>
    </ul>
  </nav>


  <div style="padding: 20px;">
    <h1>Animes Online</h1>
    <p></p>
  </div>

</body>
</html>


    <!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Galeria de Imagens</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fcfbfb;
      margin: 0;
      padding: 0;
    }

    h1 {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
      margin: 0;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      padding: 20px;
    }

    .galeria img {
      width: 100%;
      height: 400px;
      object-fit: cover;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease;
    }

    .galeria img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>



  <div class="galeria">
    <img src="https://br.web.img2.acsta.net/img/9c/0f/9c0f6e33b4fafe1a3490b3fe4b4d7cce.jpg" alt="Imagem 1">
    <img src="https://comicboom.com.br/shop/wp-content/uploads/2025/06/sololevelin07.webp" alt="Imagem 2">
    <img src="https://www.quadrorama.com.br/wp-content/uploads/2024/08/77-3.png" alt="Imagem 3">
    <img src="https://dicasgeeks.com.br/wp-content/uploads/2018/05/95445cd55c37ce2ff04ef1adde79f50c1459210457_full.jpg" alt="Imagem 3">
  </div>

</body>
</html>
