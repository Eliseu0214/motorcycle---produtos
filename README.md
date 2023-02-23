<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
    <link href="products.css" rel="stylesheet"/>
</head>
<body>
  <nav class="navbar navbar-expand-lg bg-white-tertiary border border-warning-2">
    <div class="container-fluid">
       <a class="navbar-brand" href="#">
        <img src="./Logo.PNG" alt="Logo" width="100rem" height="80rem" class="d-inline-block align-text-top">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active text-warning" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-warning" href="#">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-warning" href="#">Customs</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-warning">Sobre/Eventos</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
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
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>  
</body>
</html>
