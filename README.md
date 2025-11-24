<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Árvore de Natal Black – Compre Agora</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Kit completo: árvore preta 1,80 m, 200 bolas douradas, pisca-pisca warm white. Entrega em 48 h.">
  <meta name="theme-color" content="#000000">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{background:#000;color:#fff;font-family:Inter,Arial,sans-serif;line-height:1.4}
    header{height:100vh;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden}
    header video{width:100%;height:100%;object-fit:cover;filter:brightness(.5)}
    .overlay{position:absolute;top:0;left:0;width:100%;height:100%;background:linear-gradient(0deg,#000 60%,transparent 100%)}
    .cta{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);text-align:center;z-index:2}
    .cta h1{font-size:2.8rem;font-weight:800;margin-bottom:.6rem;text-shadow:0 2px 8px #000}
    .cta p{font-size:1.2rem;margin-bottom:1.4rem}
    .btn{background:#ffcc00;color:#000;font-weight:800;padding:1rem 3rem;border:none;border-radius:50px;font-size:1.2rem;cursor:pointer;transition:.3s;box-shadow:0 4px 14px rgba(255,204,0,.4)}
    .btn:hover{transform:scale(1.08)}
    section{padding:4rem 1rem;max-width:900px;margin:auto}
    h2{font-size:2rem;margin-bottom:1rem}
    ul{list-style:none}
    ul li{margin-bottom:.6rem}
    ul li::before{content:"✔ ";color:#ffcc00;margin-right:.5rem}
    .price{font-size:2.5rem;font-weight:800;color:#ffcc00;margin:.8rem 0}
    footer{background:#111;text-align:center;padding:1.2rem;font-size:.85rem;color:#666}
    @media(max-width:600px){
      .cta h1{font-size:2.2rem}
      .btn{padding:.9rem 2.4rem;font-size:1.1rem}
    }
  </style>
</head>

<body>
  <header>
    <video autoplay muted loop playsinline>
      <source src="video.mp4" type="video/mp4">
      <!-- fallback caso o vídeo não carregue -->
      <img src="arvore.jpg" alt="Árvore de Natal preta">
    </video>
    <div class="overlay"></div>
    <div class="cta">
      <h1>ÁRVORE DE NATAL BLACK</h1>
      <p>Kit completo: 1,80 m preta fosca + 200 bolas douradas + pisca-pisca warm white</p>
      <div class="price">R$199,90</div>
      <button class="btn" onclick="openCheckout()">COMPRAR AGORA</button>
    </div>
  </header>

  <section>
    <h2>O que vem no kit</h2>
    <ul>
      <li>Árvore 1,80 m pvc premium (preto fosco)</li>
      <li>200 bolas douradas 4 cm shatterproof</li>
      <li>Pisca-pisca 200 LEDs warm white</li>
      <li>Base metálica reforçada + saia dourada</li>
      <li>Manual de montagem 5 min</li>
    </ul>
    <p style="margin-top:1.2rem">Entrega em 48 h úteis – Frete grátis Sul/Sudeste.</p>
  </section>

  <footer>
    © 2025 Black Tree Store – WhatsApp: <a href="https://wa.me/5511937530931" style="color:#ffcc00">(11) 9 3753-0931</a>
  </footer>

  <!-- Gumroad overlay checkout -->
  <script src="https://gumroad.com/js/gumroad-embed.js"></script>
  <script>
    function openCheckout() {
      // Substitua pelo seu link do produto Gumroad
      window.open('https://gum.co/arvoreblack', '_blank');
    }
  </script>
</body>
</html>
