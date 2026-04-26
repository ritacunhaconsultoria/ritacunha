<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rita Cunha — Consultoria de Imagem</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- MENU -->
  <header class="topbar" id="topo">
    <div class="container nav">
      <div class="logo">
        <!-- Substitua pelo caminho correto da imagem no GitHub Pages -->
        <!-- Exemplo: src="assets/Logo.jpg" -->
        <span class="logo-text">Rita Cunha</span>
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
    <div class="hero-content">
      <p class="hero-sub">Consultoria de Imagem</p>
      <h1>TRANSFORME<br><em>sua imagem,</em><br>TRANSFORME sua vida</h1>
      <a href="#servicos" class="btn btn-hero">Conheça os serviços</a>
    </div>
    <div class="hero-overlay"></div>
  </section>

  <!-- CONSULTORIA -->
  <section class="section consult" id="consultoria">
    <div class="container consult-inner">
      <div class="consult-deco" aria-hidden="true">✦</div>
      <h3>CONSULTORIA</h3>
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
    <div class="bar"><span>Sobre</span></div>

    <div class="container sobre-grid">
      <div class="sobre-img-wrap">
        <!-- Substitua pelo caminho correto: src="assets/consultora.jpg" -->
        <div class="img-placeholder" aria-label="Foto da consultora">
          <span>Foto</span>
        </div>
      </div>

      <div class="sobre-texto">
        <h2>Rita Cunha</h2>
        <div class="linha-decorativa"></div>
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

  <!-- SERVIÇOS -->
  <section class="section servicos" id="servicos">
    <div class="bar center">
      <span class="pill">Conheça nossos serviços</span>
    </div>

    <div class="container servicesGrid">

      <article class="serviceCard">
        <!-- src="assets/servico-1.jpg" -->
        <div class="card-img-placeholder"></div>
        <div class="card-overlay">
          <h4>Coloração Pessoal</h4>
        </div>
      </article>

      <article class="serviceCard">
        <!-- src="assets/servico-2.jpg" -->
        <div class="card-img-placeholder"></div>
        <div class="card-overlay">
          <h4>Personal Shopping</h4>
        </div>
      </article>

      <article class="serviceCard">
        <!-- src="assets/servico-3.jpg" -->
        <div class="card-img-placeholder"></div>
        <div class="card-overlay">
          <h4>Closet Cleaning</h4>
        </div>
      </article>

      <article class="serviceCard">
        <!-- src="assets/servico-4.jpg" -->
        <div class="card-img-placeholder"></div>
        <div class="card-overlay">
          <h4>Marketing de Moda</h4>
        </div>
      </article>

      <article class="serviceCard">
        <!-- src="assets/servico-5.jpg" -->
        <div class="card-img-placeholder"></div>
        <div class="card-overlay">
          <h4>Brechó</h4>
        </div>
      </article>

      <article class="serviceCard">
        <!-- src="assets/servico-6.jpg" -->
        <div class="card-img-placeholder"></div>
        <div class="card-overlay">
          <h4>Consultoria Empresarial</h4>
        </div>
      </article>

    </div>
  </section>

  <!-- VÍDEO + CTA -->
  <section class="section videoSection" id="video">
    <div class="container videoWrap">
      <h3 class="video-title">Assista e inspire-se</h3>

      <div class="videoPlaceholder" aria-label="Área do vídeo">
        <!-- Para embed de YouTube: substitua por <iframe> -->
        <div class="playIcon" aria-hidden="true"></div>
      </div>

      <a
        class="ctaInstagram"
        href="https://www.instagram.com/rita.oliveiracunha/"
        target="_blank"
        rel="noopener noreferrer"
      >
        ✦ AGENDE SUA TRANSFORMAÇÃO
      </a>
    </div>
  </section>

  <!-- FOOTER / CONTATO -->
  <footer id="contato" class="footer">
    <div class="container footerInner">
      <div class="footer-brand">
        <h3>Rita Cunha</h3>
        <p class="cargo">CONSULTORA DE IMAGEM</p>
        <p class="footer-ig">@rita.oliveiracunha</p>
      </div>

      <div class="footer-center">
        <p class="footer-quote">
          <em>"Imagem é identidade,<br>posicionamento e segurança."</em>
        </p>
      </div>

      <div class="socials">
        <a class="social" href="https://www.instagram.com/rita.oliveiracunha/" target="_blank" rel="noopener" aria-label="Instagram">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" width="18" height="18"><rect x="2" y="2" width="20" height="20" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1" fill="currentColor" stroke="none"/></svg>
        </a>
        <a class="social" href="#" aria-label="LinkedIn">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" width="18" height="18"><rect x="2" y="2" width="20" height="20" rx="3"/><path d="M7 10v7M7 7v.5M12 17v-4a2 2 0 0 1 4 0v4M12 10v7"/></svg>
        </a>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2025 Rita Cunha · Consultoria de Imagem</p>
    </div>
  </footer>

  <script>
    // Menu mobile
    const btn = document.getElementById('menuBtn');
    const menu = document.getElementById('menu');

    btn.addEventListener('click', () => {
      const isOpen = menu.classList.toggle('is-open');
      btn.setAttribute('aria-expanded', isOpen);
      btn.classList.toggle('is-active', isOpen);
    });

    // Fechar menu ao clicar em um link
    menu.querySelectorAll('a').forEach(link => {
      link.addEventListener('click', () => {
        menu.classList.remove('is-open');
        btn.setAttribute('aria-expanded', false);
        btn.classList.remove('is-active');
      });
    });

    // Smooth scroll
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          e.preventDefault();
          target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
      });
    });

    // Navbar shrink on scroll
    const topbar = document.getElementById('topo');
    window.addEventListener('scroll', () => {
      topbar.classList.toggle('scrolled', window.scrollY > 60);
    });

    // Fade-in on scroll (Intersection Observer)
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.15 });

    document.querySelectorAll('.serviceCard, .sobre-grid, .consult-inner, .videoWrap').forEach(el => {
      el.classList.add('fade-in');
      observer.observe(el);
    });
  </script>
</body>
</html>
