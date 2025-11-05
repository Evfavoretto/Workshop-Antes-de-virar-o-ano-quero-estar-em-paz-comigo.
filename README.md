<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 em paz." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
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
      --final-sub: clamp(28px, 6.5vw, 72px);
    }

    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:var(--deep);
      -webkit-font-smoothing:antialiased;
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(11,76,129,0.04), transparent 6%),
        radial-gradient(900px 500px at 95% 90%, rgba(184,225,255,0.03), transparent 8%),
        linear-gradient(180deg,var(--blue-1), #FFFFFF 80%);
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}

    /* topbar */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:10px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:56px;height:56px;border-radius:12px;
      background:linear-gradient(135deg,var(--blue-2),#89CFFD);
      display:flex;align-items:center;justify-content:center;
      color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:20px;
      box-shadow:var(--shadow-lg)
    }
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO */
    .hero{
      position:relative;
      border-radius:20px;
      padding:160px 44px 84px; /* aumentei o topo */
      background:linear-gradient(180deg, rgba(255,255,255,0.99), rgba(255,255,255,0.97));
      box-shadow:var(--shadow-lg);
      margin:-80px 0 34px; /* empurra pra cima pra esconder o título azul */
      min-height:560px;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
    }

    .hero::before{
      content:"WORKSHOP";
      position:absolute;
      top:8%;left:50%;transform:translateX(-50%);
      font-family:'Playfair Display',serif;font-weight:800;
      font-size:clamp(64px,16vw,160px);
      color:rgba(15,76,129,0.03);
      pointer-events:none;user-select:none;
    }

    h1.title{
      font-family:'Playfair Display',serif;
      font-size:var(--hero-title);
      line-height:1.05;
      color:var(--blue-deep);
      max-width:900px;
      margin:0 auto;
      text-align:center;
    }
    .title-sub{
      margin-top:14px;
      color:var(--muted);
      font-size:17px;
      max-width:760px;
      text-align:center;
    }
    .underline{
      width:220px;height:12px;border-radius:999px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));
      margin:18px auto 0;
    }

    .hero-ctas{
      display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;justify-content:center;
    }
    .btn{
      border-radius:12px;padding:14px 18px;
      font-weight:800;font-size:15px;cursor:pointer;border:0;
      transition:transform .12s ease;
    }
    .btn-primary{background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.08);color:var(--muted)}

    section{padding:44px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{
      font-family:'Playfair Display',serif;font-size:28px;
      margin:0 0 20px;text-align:center;color:var(--deep)
    }

    .grid-3{display:grid;gap:18px;margin-top:12px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{
      background:var(--card);padding:18px;border-radius:12px;
      border:1px solid rgba(0,0,0,0.04);
      box-shadow:0 10px 30px rgba(0,0,0,0.03)
    }
    .card h3{font-size:18px;margin:0 0 8px;color:var(--blue-deep)}
    .card p{color:var(--muted);line-height:1.6;white-space:pre-line}

    .mentor{
      display:flex;gap:18px;align-items:center;
      padding:18px;border-radius:12px;background:var(--card);
      border:1px solid rgba(0,0,0,0.04);
      box-shadow:0 12px 36px rgba(0,0,0,0.04)
    }
    .mentor img{width:220px;height:220px;border-radius:12px;object-fit:cover}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:20px;color:var(--blue-deep)}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    /* FLOATS */
    .whatsapp-float{
      position:fixed;right:18px;bottom:80px;background:#25D366;color:#fff;
      border-radius:999px;padding:12px 16px;font-weight:800;
      box-shadow:0 20px 46px rgba(0,0,0,0.18);z-index:1001;
      display:flex;gap:10px;align-items:center;font-size:15px;border:0;cursor:pointer;
    }
    .whatsapp-float img{width:20px;height:20px;display:block}

    .countdown-float{
      position:fixed;right:18px;bottom:18px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;
      padding:12px 16px;border-radius:12px;font-weight:800;
      box-shadow:0 20px 46px rgba(15,76,129,0.22);z-index:1000;text-align:center;
    }
    .countdown-float .time{font-size:18px;letter-spacing:.02em}
    .countdown-float .label{font-size:12px;opacity:.9}

    /* FINAL */
    .final-highlight{
      margin-top:32px;border-radius:12px;overflow:hidden;
      background:linear-gradient(180deg,var(--blue-deep),#0A3C66);
      color:#fff;padding:42px 28px;
      display:flex;align-items:center;gap:28px;flex-wrap:wrap;
    }
    .final-left{flex:1;min-width:320px}
    .final-tag{font-weight:800;letter-spacing:.08em;
      color:rgba(255,255,255,0.9);
      font-family:'Playfair Display',serif;font-size:20px;margin:0 0 8px}
    .final-main{font-family:'Playfair Display',serif;
      font-size:var(--final-sub);margin:0;line-height:1;color:#fff;text-align:left}
    .final-desc{opacity:0.95;margin-top:10px;color:rgba(255,255,255,0.9)}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:13px;margin-top:22px}

    @media(max-width:760px){
      .hero{padding:120px 20px 60px}
      .mentor{flex-direction:column;align-items:flex-start}
      .mentor img{width:100%;height:320px}
      .final-main{font-size:clamp(22px,8vw,36px)}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header class="topbar">
      <div class="brand">
        <div class="logo">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif;color:var(--blue-deep)">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop • 3 noites</div>
        </div>
      </div>
      <nav>
        <a href="#noites">Noites</a>
        <a href="#mentor">Mentor</a>
        <a href="#final">Final</a>
      </nav>
    </header>

    <main class="hero">
      <h1 class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
      <div class="underline"></div>
      <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

      <div class="hero-ctas">
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

    <section id="final">
      <div class="final-highlight">
        <div class="final-left">
          <div class="final-tag">WORKSHOP — A VIDA QUE EU QUERO VIVER</div>
          <div class="final-main">Antes de virar o ano, quero estar em paz comigo.</div>
          <div class="final-desc">Três noites práticas (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz.</div>
        </div>
        <div style="min-width:220px;display:flex;flex-direction:column;gap:12px;align-items:flex-end">
          <button class="btn btn-primary" onclick="openGroup()">Entrar no grupo</button>
          <div style="color:rgba(255,255,255,0.9);font-size:13px;text-align:right">Clique para entrar no grupo e garantir seu lugar.</div>
        </div>
      </div>
    </section>

    <footer>© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</footer>
  </div>

  <!-- Botões flutuantes -->
  <button class="whatsapp-float" onclick="openGroup()">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><path fill='%23fff' d='M20.52 3.478A11.943 11.943 0 0 0 12 .5C6.201.5 1.5 5.2 1.5 11c0 1.948.49 3.827 1.422 5.505L.5 23.5l6.984-2.243A11.45 11.45 0 0 0 12 22.5c5.799 0 10.5-4.7 10.5-10.5 0-1.87-.45-3.632-1.98-5.022zM12 20.5c-1.07 0-2.104-.2-3.07-.585l-.224-.094-4.147 1.33 1.28-3.86-.12-.247A8.5 8.5 0 1 1 20.5 11 8.48 8.48 0 0 1 12 20.5z'/></svg>" alt="">
    Entrar no grupo
  </button>

  <div class="countdown-float" id="countdown">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">-- dias — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <script>
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }
    function scrollMentor(){ document.getElementById('mentor').scrollIntoView({behavior:'smooth', block:'center'}); }

    const targetDate = new Date(2025, 11, 2, 20, 0, 0);
    function updateCountdown(){
      const now = new Date();
      const diff = targetDate - now;
      const el = document.getElementById('cd-time');
      if(diff <= 0){ el.textContent = "Começou — veja no grupo"; return; }
      const d = Math.floor(diff / (1000*60*60*24));
      const h = Math.floor((diff / (1000*60*60)) % 24);
      const m = Math.floor((diff / (1000*60)) % 60);
      const s = Math.floor((diff / 1000) % 60);
      el.textContent = `${d}d — ${String(h).padStart(2,'0')}:${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}`;
    }
    updateCountdown(); setInterval(updateCountdown,1000);
  </script>
</body>
</html>
