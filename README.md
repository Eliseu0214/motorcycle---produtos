<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>

    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <nav class="nav-bar">
        <div class="nav-center">
            <div>
                <button class="toggle-nav">
                    <i class="fas fa-bars"></i>
                </button>
                <ul class="nav-links">
                    <li>
                        <a href="" class="nav-links">
                            Home
                        </a>
                    </li>
                    <li>
                        <a href="" class="nav-links">
                            Products
                        </a>
                    </li>
                    <li>
                        <a href="" class="nav-links">
                            Customs
                        </a>
                    </li>
                    <li>
                        <a href="" class="nav-links">
                            Events
                        </a>
                    </li>
                </ul>
            </div>
            <img src="Logo.PNG" class="nav-logo" alt="logo">
        </div>
    </nav>
    <section class="page-hero">
      <div class="section-center">
        <h3 class="page-hero-title">Home / Detalhe do produto</h3>
      </div>
    </section>
    <!--sidebar-->
    <div class="sidebar-overlay">
      <aside class="sidebar">
        <!--close-->
        <button class="sidebar-close">
          <i class="fas fa-times"></i>
        </button>
        <!--Links-->
        <ul class="sidebar-links">
          <li>
            <a href="index.html" class="sidebar-link">
              <i class="fas fa-home fa-fw"></i>
              Home
            </a>
          </li>
          <li>
            <a href="products.html" class="sidebar-link">
              <i class="fas fa-couch fa-fw"></i>
              Produtos
            </a>
          </li>
          <li>
            <a href="about.html" class="sidebar-link">
              <i class="fas fa-book fa-fw"></i>
              Sobre
            </a>
          </li>
        </ul>
      </aside>
    </div>
    <!--Cart-->
    <div class="cart-overlay">
      <aside class="cart">
        <button class="cart-close">
          <i class="fas fa-times"></i>
        </button>
        <header>
          <h3 class="text-slanted">Seu carrinho</h3>
        </header>
        <!--Cart items-->
        <div class="cart-items"></div>
        <!--Footer-->
        <footer>
          <h3 class="cart-total text-slanted">
            Total: R$ 12.99
          </h3>
          <button class="cart-checkout btn">Sair</button>
        </footer>
      </aside>
    </div>
    <!--Product info-->
    <section class="single-product">
      <div class="section-center single-product-center">
        <img
          src="./images/main-bcg.jpeg"
          class="single-product-img img"
        />
        <article class="single-product-info">
          <div>
            <h2 class="single-product-title">Sofá</h2>
            <p class="single-product-company text-slanted">
              by marcos
            </p>
            <p class="single-product-price">R$ 30.00</p>
            <div class="single-product-colors"></div>
            <p class="single-product-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </p>
            <button class="addToCartBtn btn" data-id="id">
              Adicionar ao carrinho
            </button>
          </div>
        </article>
      </div>
    </section>
    <!--page loading-->
    <div class="page-loading">
      <h2>Carregando...</h2>
    </div>
    <script type="module" src="./src/pages/product.js"></script>
</body>
</html>
