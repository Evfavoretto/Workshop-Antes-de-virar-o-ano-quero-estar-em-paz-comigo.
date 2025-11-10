
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover" />
  <title>Antes de virar o ano, quero estar em paz comigo</title>
  <meta name="description" content="Três noites para reconhecer, soltar e recomeçar — preparando 2026 com leveza e clareza emocional." />
  <style>
    :root{
      --green-900:#0c4d1f;
      --green-800:#0a3c16;
      --green-soft:#e6f3ea;
      --gold-500:#c6a75d;
      --yellow-canary:#ffeb3b;
      --stone-200:#e7e7e7;
      --red-700:#c62828;
      --shadow:0 10px 28px rgba(0,0,0,.14);
      --bg:#eaf5ec;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:#0b0b0b;background:var(--bg);-webkit-font-smoothing:antialiased;line-height:1.5}
    img{max-width:100%;display:block}
    a{text-decoration:none;color:inherit}

    /* ===== Cabeçalho fixo ===== */
    .top-bar{
      position:fixed;
      top:0;left:0;right:0;
      background:var(--green-900);
      color:#fff;
      text-align:center;
      padding:14px 10px;
      font-weight:900;
      font-size:clamp(16px,4vw,22px);
      letter-spacing:.03em;
      z-index:9999;
      box-shadow:0 4px 10px rgba(0,0,0,.25);
    }

    /* ===== HERO ===== */
    .hero{
      position:relative;
      min-height:68vh;
      background:url('WhatsApp Image 2025-11-10 at 09.08.40.jpeg') center/cover no-repeat;
      display:flex;align-items:center;justify-content:center;
      color:#fff;text-align:center;
      padding:120px 20px 60px;
      margin-top:54px; /* compensar faixa fixa */
    }
    .hero::before{
      content:"";
      position:absolute;inset:0;
      background:linear-gradient(180deg,rgba(6,41,15,.6),rgba(10,60,22,.7));
    }
    .hero .inner{position:relative;z-index:1;max-width:900px}
    .hero h1{font-size:clamp(26px,5.5vw,48px);font-weight:900;margin-bottom:10px}
    .hero p{font-size:clamp(16px,2.6vw,20px);font-weight:500;color:rgba(255,255,255,.95);margin-bottom:20px}
    .btn{display:inline-block;border-radius:999px;padding:14px 28px;font-weight:800;font-size:16px;cursor:pointer;transition:.2s}
    .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
    .btn-yellow:hover{transform:translateY(-3px)}

    /* ===== Trustbar ===== */
    .trustbar{background:#fff;padding:16px 0;border-top:1px solid var(--stone-200);border-bottom:1px solid var(--stone-200)}
    .trust{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:10px;align-items:center;text-align:center}
    .trust-item{background:#f8fbf9;border:1px solid var(--stone-200);border-radius:999px;padding:10px 14px;font-weight:700;color:var(--green-900);font-size:15px}

    /* ===== Seções ===== */
    section{padding:60px 20px;max-width:1120px;margin:0 auto}
    .title{font-size:clamp(26px,4vw,36px);text-align:center;margin:0 0 28px;font-weight:900;color:#0b0b0b}

    /* ===== As 3 Noites ===== */
    .nights{display:grid;gap:20px}
    @media(min-width:860px){.nights{grid-template-columns:repeat(3,1fr)}}
    .night{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:24px}
    .night h3{color:var(--green-900);margin-bottom:8px;font-size:18px}
    .night p{color:#333;font-size:16px;line-height:1.6}

    /* ===== Investimento ===== */
    #investimento{background:var(--green-soft);text-align:center}
    #investimento h2{color:var(--green-900)}
    .price{font-size:38px;font-weight:900;color:var(--red-700)}
    .price.free{color:var(--green-900)}
    .price-note{font-size:18px;color:#444}

    /* ===== Mentor ===== */
    .bio{max-width:800px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:30px;text-align:center}
    .bio h3{font-size:24px;margin-bottom:8px}
    .mentor-photo{max-width:110px;border-radius:50%;margin:14px auto;box-shadow:0 6px 18px rgba(0,0,0,.25)}

    /* ===== Rodapé ===== */
    .footer{background:var(--green-800);color:#e6f3ea;text-align:center;padding:28px 20px;font-size:14px}
    .footer a{color:var(--yellow-canary)}

    /* ===== WhatsApp ===== */
    .whats-float{position:fixed;right:18px;bottom:18px;z-index:9999;width:60px;height:60px;border-radius:50%;background:#25D366;display:flex;align-items:center;justify-content:center;box-shadow:0 12px 28px rgba(0,0,0,.18)}
    .whats-float svg{width:30px;height:30px;fill:#fff}

    @media(max-width:480px){
      section{padding:40px 14px}
      .mentor-photo{max-width:90px}
    }
  </style>
</head>
<body>

  <!-- CABEÇALHO FIXO -->
  <div class="top-bar">Antes de virar o ano, quero estar em paz comigo</div>

  <!-- HERO -->
  <section class="hero">
    <div class="inner">
      <h1>Encerre o ciclo com leveza</h1>
      <p>Três noites de vivência para reconhecer, soltar e recomeçar — preparando 2026 com paz interior.</p>
      <a href="https://wa.me/5549998110445?text=Quero%20participar%20do%20workshop%20Antes%20de%20virar%20o%20ano" target="_blank" class="btn btn-yellow" rel="noopener">Quero participar</a>
    </div>
  </section>

  <!-- TRUSTBAR -->
  <div class="trustbar">
    <div class="trust">
      <div class="trust-item">3 encontros ao vivo</div>
      <div class="trust-item">Práticas de soltura e autocuidado</div>
      <div class="trust-item">Ritual de recomeço para 2026</div>
      <div class="trust-item">Experiência gratuita</div>
    </div>
  </div>

  <!-- AS 3 NOITES -->
  <section>
    <h2 class="title">As 3 Noites</h2>
    <div class="nights">
      <div class="night">
        <h3>1ª Noite — O peso que ainda carrego</h3>
        <p>Reconhecer mágoas, culpas e cobranças que já não cabem mais. Dar nome é o primeiro passo para libertar.</p>
      </div>
      <div class="night">
        <h3>2ª Noite — Quando soltar é cuidar</h3>
        <p>Práticas guiadas de soltura e autocuidado. Aprender a pausar, confiar e restaurar energia.</p>
      </div>
      <div class="night">
        <h3>3ª Noite — O recomeço que nasce da paz</h3>
        <p>Ritual prático para transformar o vivido em sabedoria e escolher intenções para 2026.</p>
      </div>
    </div>
  </section>

  <!-- INVESTIMENTO -->
  <section id="investimento">
    <h2 class="title">Investimento</h2>
    <div class="price free">Gratuito</div>
    <p class="price-note">Vivência aberta — vagas limitadas</p>
    <a href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20gratuita%20no%20workshop" target="_blank" class="btn btn-yellow" rel="noopener">Garantir minha vaga</a>
  </section>

  <!-- BIO / MENTOR -->
  <section>
    <h2 class="title">Facilitador</h2>
    <div class="bio">
      <img src="Mentor.jpeg" alt="Evandro — facilitador" class="mentor-photo" onerror="this.style.display='none'">
      <h3>Evandro</h3>
      <p>Mentor em desenvolvimento pessoal e emocional, pós-graduado em neurociência, saúde mental e psicologia. Une práticas sistêmicas e constelação familiar para conduzir processos de transformação com leveza e presença.</p>
      <a href="https://wa.me/5549998110445?text=Quero%20falar%20com%20o%20Evandro" class="btn btn-yellow" target="_blank" rel="noopener" style="margin-top:16px;">Falar no WhatsApp</a>
    </div>
  </section>

  <!-- RODAPÉ -->
  <footer class="footer">
    © <span id="ano"></span> Antes de virar o ano, quero estar em paz comigo — Todos os direitos reservados.
  </footer>

  <!-- WHATSAPP FLUTUANTE -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais%20sobre%20o%20workshop%20Antes%20de%20virar%20o%20ano" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
    <svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <script>
    document.getElementById("ano").textContent = new Date().getFullYear();
  </script>
</body>
</html>
