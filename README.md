# css<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AluraBooks</title>
  <link rel="stylesheet" href="reset.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet"
  />
  <link rel="stylesheet" href="styles.css" />
</head>:root {
  --cor-de-fundo: #ebecee;
  --branco: #ffffff;
  --laranja: #eb9b00;
  --azul-degrade: linear-gradient(97.54deg, #002f52 35.49%, #326589 165.37%);
  --fonte-principal: "Poppins";
}body {
    background-color: var(--cor-de-fundo);
    font-family: var(--fonte-principal);
}body {
    background-color: var(--cor-de-fundo);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}<section class="banner"></section><section class="banner">
  <h2>Já sabe por onde começar?</h2>
  <p>Encontre em nossa estante o que precisa para seu desenvolvimento!</p>
</section><section class="banner">
  <h2>Já sabe por onde começar?</h2>
  <p>Encontre em nossa estante o que precisa para seu desenvolvimento!</p>
  <input type="search" placeholder="Qual será sua próxima leitura?" />
</section><section class="banner">
  <h2 class="banner__titulo">Já sabe por onde começar?</h2>
  <p class="banner__texto">
    Encontre em nossa estante o que precisa para seu desenvolvimento!
  </p>
  <input
    type="search"
    class="banner__pesquisa"
    placeholder="Qual será sua próxima leitura?"
  />
</section>@import url("styles/header.css");
@import url("styles/banner.css");.banner {
  background: var(--azul-degrade);
  color: var(--branco);
  text-align: center;
  padding: 2.5em 2em;
}.banner__titulo {
  font-size: 18px;
  font-weight: 700;
}.banner__texto {
  font-weight: 500;
  margin: 1em 0;
}.banner__pesquisa {
  background-color: transparent;
  border: 1px solid var(--branco);
}.banner__pesquisa {
  background-color: transparent;
  border: 1px solid var(--branco);
  color: var(--branco);
  border-radius: 24px;
}.banner__pesquisa {
  background-color: transparent;
  border: 1px solid var(--branco);
  color: var(--branco);
  border-radius: 24px;
  padding: 1em;
  width: 100%;
}.banner__pesquisa::placeholder {
}.banner__pesquisa::placeholder {
  font-family: var(--fonte-principal);
  font-size: 14px;
  font-weight: 400;
}.banner__pesquisa::placeholder {
  font-family: var(--fonte-principal);
  font-size: 14px;
  font-weight: 400;
  text-align: center;
  color: var(--branco);
}.banner__pesquisa::placeholder {
  font-family: var(--fonte-principal);
  font-size: 14px;
  font-weight: 400;
  text-align: center;
  color: var(--branco);
  background: url("../img/Lupa.svg") no-repeat;
}.banner__pesquisa::placeholder {
  font-family: var(--fonte-principal);
  font-size: 14px;
  font-weight: 400;
  text-align: center;
  color: var(--branco);
  background: url("../img/Lupa.svg") no-repeat;
  background-position: 1em;
}<section class="carrossel"></section><section class="carrossel">
  <h2 class="carrossel__titulo">Novos lançamentos</h2>
</section>@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");.carrossel__titulo {
  color: var(--laranja);
  background-color: var(--branco);
  text-align: center;
  text-transform: uppercase;
  font-size: 18px;
  font-weight: 700;
  padding: 1em 0 0.5em 0;
}<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AluraBooks</title>
  <link rel="stylesheet" href="reset.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap"
    rel="stylesheet"
  />
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"
  />
  <link rel="stylesheet" href="styles.css" />
</head>  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
</body><h2 class="carrossel__titulo">Novos lançamentos</h2>
<!-- Slider main container -->
<div class="swiper">
  <!-- Additional required wrapper -->
  <div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide">Slide 1</div>
    <div class="swiper-slide">Slide 2</div>
    <div class="swiper-slide">Slide 3</div>
    ...
  </div>
  <!-- If we need pagination -->
  <div class="swiper-pagination"></div>

  <!-- If we need navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>

  <!-- If we need scrollbar -->
  <div class="swiper-scrollbar"></div>
</div><div class="swiper-slide"><img src="img/Apachekafka.svg" /></div>
<div class="swiper-slide"><img src="img/Liderança.svg" /></div>
<div class="swiper-slide"><img src="img/Javascript.svg" /></div>
<div class="swiper-slide"><img src="Guia Front-end.svg" /></div>
<div class="swiper-slide"><img src="Portugol.svg" /></div>
<div class="swiper-slide"><img src="Acessibilidade.svg" /></div><div class="swiper-wrapper">
  <!-- Slides -->
  <div class="swiper-slide">
    <img
      src="img/Apachekafka.svg"
      alt="Livro sobre apache kafka e spring boot da alura books"
    />
  </div>
  <div class="swiper-slide">
    <img
      src="img/Liderança.svg"
      alt="Livro sobre liderança em design design da alura books"
    />
  </div>
  <div class="swiper-slide">
    <img
      src="img/Javascript.svg"
      alt="Livro sobre javascript assertivo da alura books"
    />
  </div>
  <div class="swiper-slide">
    <img src="Guia Front-end.svg" alt="Livro Guia front end" />
  </div>
  <div class="swiper-slide">
    <img src="Portugol.svg" alt="Livro sobre portugol" />
  </div>
  <div class="swiper-slide">
    <img src="Acessibilidade.svg" alt="livro sobre acessibilidade" />
  </div>
</div><script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<script>
  const swiper = new Swiper(".swiper", {
    // Optional parameters
    direction: "vertical",
    loop: true,

    // If we need pagination
    pagination: {
      el: ".swiper-pagination",
    },

    // Navigation arrows
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },

    // And if we need scrollbar
    scrollbar: {
      el: ".swiper-scrollbar",
    },
  });
</script><script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<script>
  const swiper = new Swiper(".swiper", {

  });
</script><script>
  const swiper = new Swiper(".swiper", {
    spaceBetween: 10,
    slidesPerView: 3,
  });
</script>.swiper-slide img {
}.swiper-slide img {
  width: 100%;
}<div class="swiper-slide">
  <img src="img/Guia Front-end.svg" alt="Livro Guia front end" />
</div>
<div class="swiper-slide">
  <img src="img/Portugol.svg" alt="Livro sobre portugol" />
</div>
<div class="swiper-slide">
  <img src="img/Acessibilidade.svg" alt="Livro sobre acessibilidade" />
</div>.swiper-button-prev,
.swiper-button-next {
  display: none;
}<script>
  const swiper = new Swiper(".swiper", {
    spaceBetween: 10,
    slidesPerView: 3,
    pagination: {

    },
  });
</script><script>
  const swiper = new Swiper(".swiper", {
    spaceBetween: 10,
    slidesPerView: 3,
    pagination: {
      el: ".swiper-pagination",
      type: "bullets",
    },
  });
</script>.swiper-pagination {
  position: initial;
  margin: 0.5em 0;
}<!-- If we need scrollbar -->
<div class="swiper-scrollbar"></div><div class="card"></div><div class="card">
  <div class="card__descrição"></div>
  <div class="card__botões"></div>
</div><div class="card__descrição">
  <div class="descrição">

  </div>
  <img src="img/Angular.svg" class="descrição__imagem" />
</div><div class="card__descrição">
  <div class="descrição">
    <h3 class="descrição__titulo">Talvez você também se interesse por...</h3>
    <h2 class="descrição__titulo-livro">Angular 11 e Firebase</h2>
    <p class="descrição__texto">
      Construindo uma aplicação integrada com a plataforma do Google.
    </p>
  </div>
  <img src="img/Angular.svg" class="descrição__imagem" />
</div><div class="card__botões">
  <ul class="botões">
    <li class="botões__item"></li>
    <li class="botões__item"></li>
  </ul>
  <a href="#" class="botões__ancora">Saiba mais</a>
</div><div class="card__botões">
  <ul class="botões">
    <li class="botões__item">
      <img src="img/Favoritos.svg" alt="Favoritar livro" />
    </li>
    <li class="botões__item">
      <img src="img/Compras.svg" alt="Adicionar no carrinho de compras" />
    </li>
  </ul>
  <a href="#" class="botões__ancora">Saiba mais</a>
</div>.card {
  background: var(--branco);
}.card {
  background: var(--branco);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}.card {
  background: var(--branco);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 1em;
  padding: 1em;
}.card__descrição {
  display: flex;
  justify-content: space-between;
  margin-bottom: 0.5em;
}.card__botões {
  display: flex;
  justify-content: space-between;
}.botões {
  display: flex;
}.descrição__titulo {
  color: var(--laranja);
  font-weight: 700;
}:root {
  --cor-de-fundo: #ebecee;
  --branco: #ffffff;
  --laranja: #eb9b00;
  --azul-degrade: linear-gradient(97.54deg, #002f52 35.49%, #326589 165.37%);
  --fonte-principal: "Poppins";
  --azul: #002f52;
}.descrição__titulo-livro {
  color: var(--azul-degrade);
  font-size: 18px;
  font-weight: 700;
  margin: 0.5em 0;
}.descrição__texto {
  font-size: 14px;
}.botões__ancora {
  background-color: var(--laranja);
  padding: 1em 2.2em;
  color: var(--branco);
  font-weight: 700;
  text-decoration: none;
}.botões__item {
  margin: 0 0.5em;
}  <section class=”carrossel”>
    <h2 class="carrossel__titulo">Mais vendidos</h2>
    <div class="swiper">
      <!-- Additional required wrapper -->
      <!-- If we need pagination -->
      <div class="swiper-pagination"></div>

      <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide"><img src="img/ApacheKafka.svg"
            alt="Livro sobre apache kafka e spring boot da alura books"></div>
        <div class="swiper-slide"><img src="img/Liderança.svg" alt="Livro sobre liderança em design da alura books">
        </div>
        <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alurabooks">
        </div>
        <div class="swiper-slide"><img src="img/Guia Front-end.svg" alt="Livro Guia front end"></div>
        <div class="swiper-slide"><img src="img/Portugol.svg" alt="Livro sobre portugol"></div>
        <div class="swiper-slide"><img src="img/Acessibilidade.svg" alt="livro sobre acessibilidade"></div>
      </div>

      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>
    </div>

    <div class="card">
      <!-- 1º linha -->
      <div class="card__descrição">
        <!-- 1º coluna -->
        <div class="descrição">
          <img src="img/Estrelinhas.svg" alt="Avaliação 5 estrelas">
          <h3 class="descrição__titulo">Autora do Mês</h3>
          <h2 class="descrição__titulo-livro">Juliana Agarikov</h2>
          <p class="descrição__texto">Analista de sistemas e escritora, Juliana é especialista em Front-End.
          </p>
        </div>
        <!-- 2º coluna -->
        <img src="img/Escritora.svg" class="descrição__imagem">
      </div>

      <!-- 2º linha -->
      <div class="card__botões">
        <!-- 1º coluna -->
        <ul class="botões">
          <li class="botões__item"><img src="img/Favoritos.svg" alt="Favoritar livro"></li>
          <li class="botões__item"><img src="img/Compras.svg" alt="Adicionar no carrinho de compras"></li>
        </ul>
        <!-- 2º coluna -->
        <a href="#" class="botões__ancora">Saiba mais</a>
      </div>
    </div>



  </section>.classe:hover {
}.botao {
  background-color: var(--azul);
  color: white;
}

.botao:hover {
  background-color: var(--azul-claro);
  color: var(--azul);
}<section class="tópicos"></section><section class="tópicos">
  <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
  <ul class="tópicos__lista"></ul>
</section><section class="tópicos">
  <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
  <ul class="tópicos__lista">
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
    <li class="tópicos__item"></li>
  </ul>
</section><section class="tópicos">
  <h2 class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
  <ul class="tópicos__lista">
    <li class="tópicos__item"><a href="#" class="tópicos__link">Android</a></li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">Marketing Digital</a>
    </li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">Agile</a>
    </li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">Startups</a>
    </li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">HTML & CSS</a>
    </li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">Python</a>
    </li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">OO</a>
    </li>
    <li class="tópicos__item">
      <a href="#" class="tópicos__link">Java</a>
    </li>
  </ul>
</section>@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");
@import url("styles/topicos.css");.tópicos {
  background: var(--azul-degrade);
  text-align: center;
  padding: 1em 0;
}.tópicos__titulo {
  color: var(--branco);
  font-weight: 300;
  margin-bottom: 1em;
}.tópicos__lista {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}.tópicos__item {
    margin: 2em 0.5em;
}.tópicos__link {
  color: var(--branco);
  padding: 1em;
  background-color: var(--laranja);
  text-decoration: none;
  font-size: 14px;
  font-weight: 700;
}<section class="contato"></section><section class="contato">
  <h2>Fique por dentro das novidades!</h2>
  <p>Atualizações de e-books, novos livros, promoções e outros.</p>
  <input type="email" placeholder="Cadastre seu e-mail" />
</section><section class="contato">
  <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
  <p class="contato__texto"> Atualizações de e-books, novos livros, promoções e outros.</p>
  <input type="email" placeholder="Cadastre seu e-mail" class="contato__email"/>
</section>@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");
@import url("styles/topicos.css");
@import url("styles/contato.css");.contato {
  background-color: var(--branco);
  padding: 1em;
}.contato__titulo,
.contato__texto {
  background: var(--azul-degrade);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}.contato__titulo {
  font-size: 18px;
  font-weight: 500;
}.contato__texto {
  font-weight: 300;
  margin: 1em 0;
}.contato__email {
  padding: 1em;
  border: 1px solid var(--azul);
  border-radius: 24px;
  width: 90%;
  color: var(--azul);
}.contato__email::placeholder {
  font-family: var(--fonte-principal);
  color: var(--azul);
  background: url("../img/Email.svg") no-repeat;
  padding-left: 2em;
}<hr /><hr />

<footer class="rodapé">

</footer><hr />

<footer class="rodapé">
  <h2 class="rodapé__titulo">Grupo Alura</h2>
</footer>@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");
@import url("styles/topicos.css");
@import url("styles/contato.css");
@import url("styles/rodapé.css");hr {
  margin: 0;
}.rodapé {
  background-color: var(--branco);
  padding: 1em;
}<html lang="pt-BR">
  <head></head>
  <body>
    <div class="block">Bloco 1</div>
    <div class="block">Bloco 2</div>
    <div class="block">Bloco 3</div>
    <div class="block">Bloco 4</div>
  </body>
</html>
