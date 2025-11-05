<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 em paz." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    /* tenta ocultar header do GitHub Pages, caso apareça */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --blue-1:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --deep:#122034;
      --muted:#5A6571;
      --card:#FFFFFF;
      --shadow-lg: 0 30px 60px rgba(15,76,129,0.08);
      --hero-title: clamp(36px, 6vw, 80px);
      --final-sub: clamp(28px, 6.5vw, 52px);
    }

    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:var(--deep);
      -webkit-font-smoothing:antialiased;
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(11,76,129,0.04), transparent 6%),
        radial-gradient(900px 500px at 95% 90%, rgba(184,225,255,0.03), transparent 8%),
        linear-gradient(180deg,var(--blue-1), #FFFFFF 80%);
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;position:relative;z-index:1}

    /* Topbar */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:10px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--blue-2),#89CFFD);
      display:flex;align-items:center;justify-content:center;color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:20px;box-shadow:var(--shadow-lg)
    }
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO - quadro branco maior e deslocado para a esquerda */
    .hero{
      position:relative;
      border-radius:22px;
      /* Aumentei bastante o padding-top e deixei mais espaço à esquerda via transform */
      padding:200px 56px 96px;
      background:linear-gradient(180deg, rgba(255,255,255,0.99), rgba(255,255,255,0.97));
      box-shadow:var(--shadow-lg);
      margin:-120px 0 34px; /* sobe o quadro para cobrir o header azul se necessário */
      min-height:640px;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      /* desloca o bloco para a esquerda, cobrindo o texto de fundo à direita */
      transform:translateX(-6%);
      max-width:calc(100% + 160px); /* permite o deslocamento sem cortar */
      z-index:2;
    }
    @media(max-width:1100px){
      .hero{transform:translateX(-2%);padding:160px 28px 64px;min-height:540px}
    }
    @media(max-width:760px){
      .hero{transform:none;padding:120px 18px 60px;min-height:460px}
    }

    /* palavra de fundo WORKSHOP — movida mais para cima */
    .hero::before{
      content:"WORKSHOP";
      position:absolute;
      top:-6%; /* mais acima */
      left:75%; /* bem à direita, a hero desliza para a esquerda e cobre parte */
      transform:translateX(-50%);
      font-family:'Playfair Display',serif;font-weight:800;
      font-size:clamp(64px,18vw,200px);
      color:rgba(15,76,129,0.03);
      pointer-events:none;user-select:none;
      z-index:0;
    }

    h1.title{
      font-family:'Playfair Display',serif;
      font-size:var(--hero-title);
      line-height:1.02;  /* reduzido para manter duas linhas */
      color:var(--blue-deep);
      max-width:760px;   /* força quebra em duas linhas */
      margin:0 auto;
      text-align:center;
      z-index:3;
      word-break:normal;
    }

    .title-sub{
      margin-top:14px;
      color:var(--muted);
      font-size:17px;
      max-width:760px;
      text-align:center;
      z-index:3;
    }

    .underline{
      width:220px;height:12px;border-radius:999px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));
      margin:18px auto 0;
      z-index:3;
    }

    .hero-ctas{
      display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;justify-content:center;z-index:3;
    }
    .btn{border-radius:12px;padding:14px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0;transition:transform .12s ease}
    .btn-primary{background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.08);color:var(--muted)}

    /* sections */
    section{padding:44px 0;border-top:1px solid rgba(0,0,0,0.03);position:relative;z-index:1}
    .section-title{font-family:'Playfair Display',serif;font-size:28px;margin:0 0 20px;text-align:center;color:var(--deep)}

    .grid-3{display:grid;gap:18px;margin-top:12px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 30px rgba(0,0,0,0.03)}
    .card h3{font-size:18px;margin:0 0 8px;color:var(--blue-deep)}
    .card p{color:var(--muted);line-height:1.6;white-space:pre-line}

    .mentor{display:flex;gap:18px;align-items:center;padding:18px;border-radius:12px;background:var(--card);border:1px solid rgba(0,0,0,0.04);box-shadow:0 12px 36px rgba(0,0,0,0.04)}
    .mentor img{width:220px;height:220px;border-radius:12px;object-fit:cover}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:20px;color:var(--blue-deep)}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    /* Floating WhatsApp (right) kept */
    .whatsapp-float{
      position:fixed;right:18px;bottom:80px;background:#25D366;color:#fff;border-radius:999px;padding:12px 16px;font-weight:800;box-shadow:0 20px 46px rgba(0,0,0,0.18);z-index:1005;display:flex;gap:10px;align-items:center;font-size:15px;border:0;cursor:pointer;
    }
    .whatsapp-float img{width:20px;height:20px;display:block}

    /* Countdown moved to left side */
    .countdown-float{
      position:fixed;left:18px;bottom:18px; /* moved to left */
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;padding:12px 16px;border-radius:12px;font-weight:800;box-shadow:0 20px 46px rgba(15,76,129,0.22);z-index:1004;text-align:center;
    }
    .countdown-float .time{font-size:18px;letter-spacing:.02em}
    .countdown-float .label{font-size:12px;opacity:.9}

    /* final band full width */
    .final-band{width:100%;background:linear-gradient(180deg,var(--blue-deep),#0A3C66);color:#fff;padding:48px 0;margin-top:40px;box-shadow:0 -6px 30px rgba(10,60,102,0.08)}
    .final-band .inner{max-width:var(--maxw);margin:0 auto;padding:0 28px;text-align:center}
    .final-band .small-tag{font-family:'Playfair Display',serif;font-weight:700;letter-spacing:.06em;opacity:0.95;margin-bottom:12px;font-size:18px}
    .final-band .big-title{font-family:'Playfair Display',serif;font-size:var(--final-sub);line-height:1.02;font-weight:700;margin:0 auto;max-width:1100px}
    .final-band .final-note{margin-top:12px;opacity:0.95;font-size:15px}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:13px;margin-top:18px}

    @media(max-width:760px){
      .whatsapp-float{right:12px;bottom:80px}
      .countdown-float{left:12px;bottom:96px}
      .hero{padding:120px 18px 60px;transform:none;min-height:480px}
      .hero::before{left:90%;top:-12%}
      .final-band .big-title{font-size:clamp(22px,7vw,36px)}
      .mentor img{width:100%;height:320px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header class="topbar" role="banner">
      <div class="brand">
        <div class="logo" aria-hidden="true">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif;color:var(--blue-deep)">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop • 3 noites</div>
        </div>
      </div>

      <nav aria-label="Navegação principal">
        <a href="#noites">Noites</a>
        <a href="#mentor">Mentor</a>
        <a href="#final">Final</a>
      </nav>
    </header>

    <main class="hero" role="main" aria-labelledby="hero-title">
      <h1 id="hero-title" class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
      <div class="underline" aria-hidden="true"></div>
      <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

      <div class="hero-ctas" role="group" aria-label="Ações principais">
        <button class="btn btn-primary" onclick="openGroup()">Já tomei minha decisão</button>
        <button class="btn btn-primary" onclick="openGroup()">Quero me inscrever agora</button>
        <button class="btn btn-alt" onclick="scrollMentor()">Ainda estou com dúvida</button>
      </div>
    </main>

    <section id="noites">
      <h2 class="section-title">As três noites</h2>
      <div class="grid-3">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.</p></article>

        <article class="card"><h3>💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h3><p>Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.</p></article>

        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.</p></article>
      </div>
    </section>

    <section id="mentor">
      <h2 class="section-title">Conheça seu mentor</h2>
      <div class="mentor">
        <img src="Mentor.jpeg" alt="Evandro Favoretto — mentor do workshop">
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
        </div>
      </div>
    </section>

  </div> <!-- fim .wrap -->

  <!-- final full-width band -->
  <div class="final-band" role="region" aria-label="Destaque final">
    <div class="inner">
      <div class="small-tag">Workshop</div>
      <h2 class="big-title">Antes de virar o ano, quero estar em paz comigo.</h2>
      <div class="final-note">Três noites práticas (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz.</div>
      <div style="margin-top:18px">
        <button class="btn btn-primary" onclick="openGroup()">Entrar no grupo</button>
      </div>
    </div>
  </div>

  <footer style="max-width:var(--maxw);margin:18px auto;padding:0 28px">© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</footer>

  <!-- floating whatsapp (right) -->
  <button class="whatsapp-float" onclick="openGroup()" aria-label="Entrar no grupo do WhatsApp">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><path fill='%23fff' d='M20.52 3.478A11.943 11.943 0 0 0 12 .5C6.201.5 1.5 5.2 1.5 11c0 1.948.49 3.827 1.422 5.505L.5 23.5l6.984-2.243A11.45 11.45 0 0 0 12 22.5c5.799 0 10.5-4.7 10.5-10.5 0-1.87-.45-3.632-1.98-5.022zM12 20.5c-1.07 0-2.104-.2-3.07-.585l-.224-.094-4.147 1.33 1.28-3.86-.12-.247A8.5 8.5 0 1 1 20.5 11 8.48 8.48 0 0 1 12 20.5z'/></svg>" alt="">
    Entrar no grupo
  </button>

  <!-- countdown (moved to left) -->
  <div class="countdown-float" id="countdown" role="status" aria-live="polite">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">-- dias — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <script>
    // link do grupo
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }
    function scrollMentor(){ document.getElementById('mentor').scrollIntoView({behavior:'smooth', block:'center'}); }

    // countdown target: 02 Dez 2025 20:00 local
    const targetDate = new Date(2025, 11, 2, 20, 0, 0);
    function updateCountdown(){
      const now = new Date();
      let diff = targetDate - now;
      const el = document.getElementById('cd-time');
      if(diff <= 0){ el.textContent = "Começou — veja no grupo"; return; }
      const days = Math.floor(diff / (1000*60*60*24));
      diff -= days * (1000*60*60*24);
      const hours = Math.floor(diff / (1000*60*60));
      diff -= hours * (1000*60*60);
      const minutes = Math.floor(diff / (1000*60));
      diff -= minutes * (1000*60);
      const seconds = Math.floor(diff / 1000);
      el.textContent = `${days}d — ${String(hours).padStart(2,'0')}:${String(minutes).padStart(2,'0')}:${String(seconds).padStart(2,'0')}`;
    }
    updateCountdown(); setInterval(updateCountdown,1000);
  </script>
</body>
</html>
