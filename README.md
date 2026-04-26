<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Consultoria de Imagem</title>
  <link rel="stylesheet" href="./style.css" />
</head>
<body>

  <!-- MENU -->
  <header class="topbar" id="topo">
    <div class="container nav">
      <div class="logo">
        <img src="/ritacunha/Logo.jpg" alt="Logo Rita Cunha">
      </div>

      <button id="menuBtn" class="menuBtn" aria-label="Abrir menu" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>

      <nav id="menu" class="menu" aria-label="Menu principal">
        <a href="#sobre">SOBRE</a>
        <a href="#servicos">SERVIÇOS</a>
        <a href="#video">VÍDEO</a>
        <a href="#contato">CONTATO</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero">
    <h1>CONSULTORIA DE IMAGEM</h1>
  </section>

  <!-- CONSULTORIA -->
  <section class="section consult" id="consultoria">
    <div class="container">
      <h3>CONSULTORIA</h3>
&nbsp;
      <p>
        Vamos explorar seus gostos, preferências e a imagem que você deseja transmitir.
      </p>

      <p>
        A partir disso, identificaremos o estilo que mais combina com sua personalidade e objetivos.
      </p>

      <a href="#servicos" class="btn">Clique aqui</a>
    </div>
  </section>

  <!-- SOBRE -->
  <section class="section sobre" id="sobre">
    <div class="bar">Sobre</div>

    <div class="container sobre-grid">
      <img src="/ritacunha/consultora.jpg" alt="Foto da consultora" />

      <div>
        <h2>Rita Cunha</h2>
&nbsp;
        <p class="texto-grande">
          Sou Consultora de Imagem e ajudo você a transformar a forma de se vestir em uma verdadeira ferramenta de autoestima e autoconfiança.
        </p>

        <p class="texto-grande">
          Acredito que imagem não é apenas roupa — é identidade, posicionamento e segurança.
          Levo você do armário bagunçado ao look perfeito.
        </p>
      </div>
    </div>
  </section>

  <!-- ✅ PÁGINA 4: SERVIÇOS -->
  <section class="section servicos" id="servicos">
    <div class="bar center">
      <span class="pill">Conheça nossos serviços</span>
    </div>

    <div class="container servicesGrid">
      <article class="serviceCard">
        <img src="/ritacunha/servico-1.jpg" alt="Coloração pessoal" />
        <h4><br></h4>
      </article>

      <article class="serviceCard">
        <img src="/ritacunha/servico-2.jpg" alt="Personal shopping" />
        <h4><br></h4>
      </article>

      <article class="serviceCard">
        <img src="/ritacunha/servico-3.jpg" alt="Closet cleaning" />
        <h4><br></h4>
      </article>

      <article class="serviceCard">
        <img src="/ritacunha/servico-4.jpg" alt="Marketing de moda" />
        <h4><br></h4>
      </article>

      <article class="serviceCard">
        <img src="/ritacunha/servico-5.jpg" alt="Brechó" />
        <h4></h4>
      </article>

      <article class="serviceCard">
        <img src="/ritacunha/servico-6.jpg" alt="Consultoria empresarial" />
        <h4><br></h4>
      </article>
    </div>
  </section>

  <!-- ✅ PÁGINA 5: VÍDEO + CTA WHATSAPP -->
  <section class="section videoSection" id="video">
    <div class="container videoWrap">
      <div class="videoPlaceholder" aria-label="Área do vídeo">
        <div class="playIcon" aria-hidden="true"></div>
      </div>

      <a
        class="ctaInstagram"
        href="https://www.instagram.com/rita.oliveiracunha/"
        target="_blank"
        rel="noopener"
      >
        AGENDE SUA TRANSFORMAÇÃO
      </a>
    </div>
  </section>

  <!-- CONTATO / FOOTER -->
  <footer id="contato" class="footer">
    <div class="container footerInner">
      <div>
        <h3>Rita Cunha</h3>
        <p class="cargo">CONSULTORA DE IMAGEM</p>
        <p>@rita.oliveiracunha</p>
      </div>

      <div class="socials">
        <a class="social" href="#" aria-label="Instagram">IG</a>
        <a class="social" href="#" aria-label="LinkedIn">IN</a>
      </div>
    </div>
  </footer>

  <script src="./script.js"></script>
</body>
</html>
