<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio | Modelo</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0f0f0f;
      --text: #f4f4f4;
      --muted: #b5b5b5;
      --accent: #c8a46a;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Inter, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    header {
      display: grid;
      grid-template-columns: 1fr 1fr;
      min-height: 100vh;
    }
    .hero-image {
      background: <div <img src="Fotos/modelo_feminina_baixinha_cabelos_cacheados_pretos_com.jpeg"></div>center/cover no-repeat;
    }
    .hero-content {
      padding: 5rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    h1, h2 {
      font-family: 'Playfair Display', serif;
    }
    h1 { font-size: 3.2rem; margin-bottom: 1rem; }
    p { color: var(--muted); max-width: 520px; margin-bottom: 2rem; }
    .btn {
      display: inline-block;
      padding: 0.8rem 1.6rem;
      border: 1px solid var(--accent);
      color: var(--accent);
      text-decoration: none;
      width: fit-content;
      transition: all 0.3s ease;
    }
    .btn:hover { background: var(--accent); color: #000; }
    section { padding: 5rem; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 2rem;
    }
    .card {
      background: #161616;
      padding: 1.5rem;
      border-radius: 16px;
    }
    .card img { width: 100%; border-radius: 12px; }
    footer {
      padding: 2rem 5rem;
      border-top: 1px solid #222;
      color: var(--muted);
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    @media (max-width: 768px) {
      header { grid-template-columns: 1fr; }
      .hero-image { min-height: 60vh; }
      .hero-content, section { padding: 2.5rem; }
    }
  </style>
</head>
<body>

<header>
  <div class="hero-image"></div>
  <div class="hero-content">
    <h1>Modelo Editorial & Fashion</h1>
    <p>Modelo profissional com foco em moda, beleza e lifestyle. Estilo natural, elegante e contemporâneo.</p>
    <a href="#contato" class="btn">Contato</a>
  </div>
</header>

<section>
  <h2>Sobre</h2>
  <p>Experiência em editoriais, campanhas publicitárias, fotografia artística e conteúdo digital. Facilidade em atuar diante das câmeras e interpretar diferentes conceitos visuais.</p>
  <div class="grid">
    <div class="card"><strong>Altura</strong><br>1,72m</div>
    <div class="card"><strong>Medidas</strong><br>86 • 62 • 90</div>
    <div class="card"><strong>Olhos</strong><br>Castanhos</div>
    <div class="card"><strong>Cabelo</strong><br>Cacheado • Castanho escuro</div>
  </div>
</section>

<section>
  <h2>Galeria</h2>
  <div class="grid">
    <div class="card"><img src="Fotos/AQO0XOtpvLxFKagROPG6unsgx7givaBlxBx5Auv-75hmLq1JlcC8JZK-CvDqEivBnd9UzHlqxiCxMfpA_o4esHluDQIXaeiRsW1mm5QxtVBpaGsqafigw2Wga6soqjs-U-Iy0YE3_82WgMBtPfFXBh22pZNb4Q.jpeg"></div>
    <div class="card"><img src="Fotos/modelo_feminina_baixinha_cabelos_cacheados_pretos_com.jpeg"></div>
    <div class="card"><img src="Fotos/AQO0XOtpvLxFKagROPG6unsgx7givaBlxBx5Auv-75hmLq1JlcC8JZK-CvDqEivBnd9UzHlqxiCxMfpA_o4esHluDQIXaeiRsW1mm5QxtVBpaGsqafigw2Wga6soqjs-U-Iy0YE3_82WgMBtPfFXBh22pZNb4Q.jpeg"></div>
     <div class="card"><img src="Fotos/modelo_feminina_baixinha_cabelos_cacheados_pretos_com.jpeg"></div>
  </div>
</section>

<section>
  <h2>Trabalhos</h2>
  <div class="grid">
    <div class="card">Editorial de Moda</div>
    <div class="card">Campanhas Lifestyle</div>
    <div class="card">Beleza & Skincare</div>
    <div class="card">Conteúdo Digital</div>
  </div>
</section>

<section id="contato">
  <h2>Contato</h2>
  <p>Email: henriquedavidson11@gmail.com<br>Instagram: @dudu_duu_jc</p>
</section>

<footer>
  <span>© 2026 Portfólio da Modelo</span>
  <span>Design editorial minimalista</span>
</footer>

</body>
</html>
