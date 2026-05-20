<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Giorno - Gelato Artesanal</title>
  <style>
    /* Reset básico */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Georgia', serif; /* Tom mais clássico/artesanal */
    }
    body {
      background: #f1e6cf; /* Bege médio das paletas */
      color: #1a2d56; /* Azul marinho */
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #ffffff;
      padding: 15px 30px;
      border-bottom: 3px solid #1a2d56;
      margin-bottom: 20px;
    }
    header .logo {
      font-weight: 900;
      font-size: 24px;
      text-transform: uppercase;
      letter-spacing: 2px;
      color: #1a2d56;
    }
    header nav a {
      text-decoration: none;
      color: #1a2d56;
      margin-left: 20px;
      font-weight: 600;
      font-size: 13px;
      text-transform: uppercase;
    }
    header .icon {
      margin-left: 20px;
      cursor: pointer;
      font-size: 1.2rem;
    }

    main {
      max-width: 1000px;
      background: #1a2d56; /* Fundo Azul Marinho */
      border-radius: 0px;
      margin: 20px auto;
      display: flex;
      padding: 50px;
      gap: 30px;
      color: #f9f5e8; /* Texto em Bege Creme */
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    }
    main .text-area {
      flex: 1;
      display: flex;
      flex-direction: column;
      justify-content: center;
      gap: 20px;
    }
    main .text-area h1 {
      font-size: 45px;
      font-weight: 900;
      line-height: 1;
      text-transform: uppercase;
    }
    main .text-area small {
      font-size: 14px;
      opacity: 0.9;
      font-style: italic;
      font-family: 'Arial', sans-serif;
    }
    main .text-area button {
      background: #f9f5e8;
      color: #1a2d56;
      border: none;
      padding: 12px 25px;
      border-radius: 0px; /* Estilo mais seco/moderno */
      font-weight: 800;
      cursor: pointer;
      transition: 0.3s;
      width: fit-content;
      text-transform: uppercase;
      border: 2px solid #f9f5e8;
    }
    main .text-area button:hover {
      background: transparent;
      color: #f9f5e8;
    }
    main .img-area {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    main .img-area img {
      max-width: 100%;
      filter: drop-shadow(5px 5px 15px rgba(0,0,0,0.3));
    }

    nav.subnav {
      background: #ffffff;
      max-width: 1000px;
      margin: 10px auto;
      padding: 12px;
      overflow-x: auto;
      white-space: nowrap;
      font-size: 11px;
      font-weight: 800;
      letter-spacing: 0.1em;
      text-align: center;
      border: 1px solid #1a2d56;
    }
    nav.subnav span {
      margin: 0 10px;
      color: #1a2d56;
    }

    section.products {
      max-width: 1000px;
      margin: 20px auto;
      display: flex;
      justify-content: space-between;
      gap: 20px;
      padding-bottom: 50px;
    }
    section.products .product-card {
      background: #f9f5e8;
      flex: 1;
      padding: 25px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      text-align: center;
      border: 2px solid #1a2d56;
      position: relative;
    }
    section.products .product-card h2 {
        font-size: 18px;
        text-transform: uppercase;
        letter-spacing: 1px;
    }
    section.products .product-card img {
      max-width: 150px;
      height: auto;
    }
    section.products .product-card .qty-controls {
      display: flex;
      align-items: center;
      gap: 15px;
      margin: 10px 0;
    }
    section.products .product-card button.qty-btn {
      background: #1a2d56;
      color: white;
      border: none;
      width: 28px;
      height: 28px;
      cursor: pointer;
      font-size: 18px;
    }
    section.products .product-card input.qty-input {
      width: 30px;
      border: none;
      text-align: center;
      font-weight: 700;
      background: transparent;
      color: #1a2d56;
    }
    section.products .product-card button.add-cart-btn {
      background: #1a2d56;
      color: #f9f5e8;
      border: none;
      padding: 10px 15px;
      font-weight: 700;
      cursor: pointer;
      width: 100%;
      text-transform: uppercase;
      font-size: 12px;
      transition: opacity 0.3s;
    }
    section.products .product-card button.add-cart-btn:hover {
      opacity: 0.9;
    }

    @media (max-width: 800px) {
      main { flex-direction: column; padding: 20px; text-align: center; }
      main .text-area { align-items: center; }
      section.products { flex-direction: column; padding: 15px; }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">GIORNO</div>
  <nav>
    <a href="#">GELATOS</a>
    <a href="#">NOSSA HISTÓRIA</a>
    <a href="#">LOJAS</a>
  </nav>
</header>

<main>
  <div class="text-area">
    <h1>GELATO<br>ARTESANAL<br>ITALIANO</h1>
    <small>Feito diariamente com ingredientes frescos e selecionados para um sabor inesquecível.</small>
    <button>VER CARDÁPIO COMPLETO</button>
  </div>
  <div class="img-area">
    <img src="https://pin.it/2nZfyFTW0" alt="Gelato Giorno" />
  </div>
</main>

<nav class="subnav">
  <span>TRADIÇÃO</span> <span>•</span>
  <span>FRESCOR</span> <span>•</span>
  <span>QUALIDADE</span>  <span>•</span>
  <span>TRADIÇÃO</span> <span>•</span>
  <span>FRESCOR</span> <span>•</span>
  <span>QUALIDADE</span>
</nav>

<section class="products">
  <div class="product-card">
    <h2>BAUNILHA REAL</h2>
    <img src="https://pin.it/2nZfyFTW0" alt="Gelato Baunilha" />
    <div class="qty-controls">
      <button class="qty-btn" onclick="changeQty(this, -1)">−</button>
      <input type="text" class="qty-input" value="1" readonly />
      <button class="qty-btn" onclick="changeQty(this, 1)">+</button>
    </div>
    <button class="add-cart-btn">ADICIONAR - R$ 18</button>
  </div>

  <div class="product-card">
    <h2>CHOCOLATE BELGA</h2>
    <img src="https://pin.it/2nZfyFTW0" alt="Gelato Chocolate" />
    <div class="qty-controls">
      <button class="qty-btn" onclick="changeQty(this, -1)">−</button>
      <input type="text" class="qty-input" value="1" readonly />
      <button class="qty-btn" onclick="changeQty(this, 1)">+</button>
    </div>
    <button class="add-cart-btn">ADICIONAR - R$ 22</button>
  </div>

  <div class="product-card">
    <h2>PISTACHE SICILIANO</h2>
    <img src="https://pin.it/2nZfyFTW0" alt="Gelato Pistache" />
    <div class="qty-controls">
      <button class="qty-btn" onclick="changeQty(this, -1)">−</button>
      <input type="text" class="qty-input" value="1" readonly />
      <button class="qty-btn" onclick="changeQty(this, 1)">+</button>
    </div>
    <button class="add-cart-btn">ADICIONAR - R$ 25</button>
  </div>
</section>

<script>
function changeQty(button, delta) {
  const qtyInput = button.parentElement.querySelector('.qty-input');
  let currentQty = parseInt(qtyInput.value);
  currentQty += delta;
  if (currentQty < 1) currentQty = 1;
  qtyInput.value = currentQty;
}
</script>

</body>
</html>
