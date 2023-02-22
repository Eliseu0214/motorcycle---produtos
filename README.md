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
                            Produtos
                        </a>
                    </li>
                    <li>
                        <a href="" class="nav-links">
                            Customisação
                        </a>
                    </li>
                    <li>
                        <a href="" class="nav-links">
                            Eventos
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
      <div class="sidebar-overlay">
        <aside class="sidebar">
          <button class="sidebar-close">
            <i class="fas fa-times"></i>
          </button>
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
      <section class="products">
        <div class="filters">
          <div class="filters-container">
            <form class="input-form">
              <input type="text" class="search-input" placeholder="search..."/>
            </form>
            <article class="prod">
              <button class="prod-btn">Peças</button>
              <button class="prod-btn">Motos</button>
              <button class="prod-btn">Boutique</button>
            </article>
            <h4>Preço</h4>
            <form class="price-form">
              <input
                type="range"
                class="price-filter"
                min="0"
                value="50"
                max="100"
              />
            </form>
            <p class="price-value"></p>
          </div>
        </div>
        <div class="products-container"></div>
      </section>>
      <div class="page-loading">
        <h2>Carregando...</h2>
      </div>
      <script type="module" src="./src/pages/products.js"></script>
</body>
</html>
