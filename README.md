
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    /* caso o GitHub adicione header automático */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --bg-soft:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --blue-dark:#041f3a;
      --muted:#5A6571;
      --card:#FFFFFF;
      --maxw:1280px;
    }

    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      -webkit-font-smoothing:antialiased;
      background: linear-gradient(180deg,var(--bg-soft),#fff);
      color:#122034;
      -webkit-text-size-adjust:100%;
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;position:relative;z-index:1}

    /* top navigation (keeps compact) */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:6px 0 18px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--blue-2),#89CFFD);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-family:'Playfair Display',serif}
    nav a{margin-left:14px;color:var(--muted);text-decoration:none;font-weight:600;font-size:14px}

    /* HERO: quadro branco maior */
    .hero{
      position:relative;
      background:linear-gradient(180deg,#fff,#fbfdff);
      border-radius:18px;
      box-shadow:0 30px 80px rgba(4,31,58,0.06);
      padding:28px 40px 64px;
      margin:40px auto 48px;
      max-width:1200px;
      overflow:visible;
      z-index:2;
    }

    /* FAIXA WORKSHOP full-bleed no topo da viewport (visual full-width) */
    .full-bleed-top{
      position:relative;
      margin-top:-36px; /* empurra a faixa para cima do quadro */
    }
    .workshop-bleed{
      position:relative;
      left:50%;
      transform:translateX(-50%);
      width:100vw; /* full width across viewport */
      background:linear-gradient(180deg,var(--blue-dark),var(--blue-deep));
      color:#fff;
      padding:22px 0;
      text-align:center;
      box-shadow:0 18px 40px rgba(4,31,58,0.14);
      z-index:5;
    }
    .workshop-bleed h2{font-family:'Playfair Display',serif;font-size:clamp(20px,3.6vw,40px);margin:0;font-weight:700;letter-spacing:.02em}

    /* hero content centered inside frame */
    .hero-inner{max-width:920px;margin:18px auto 0;text-align:center}
    h1.title{font-family:'Playfair Display',serif;font-size:clamp(26px,6vw,56px);color:var(--blue-deep);line-height:1.02;margin:8px 0}
    .underline{width:220px;height:10px;border-radius:999px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));margin:12px auto}
    .lead{color:var(--muted);max-width:760px;margin:14px auto 0}

    /* SECTION flags full-bleed (mais larga) */
    section{padding:54px 0}
    .section-flag{
      position:relative;
      left:50%;
      transform:translateX(-50%);
      width:100vw; /* full-bleed */
      height:44px;
      background:var(--blue-dark);
      border-radius:6px;
      margin-bottom:12px;
      z-index:-1;
    }
    .section-title{
      max-width:var(--maxw);
      margin:-46px auto 18px;
      padding:8px 18px;
      font-family:'Playfair Display',serif;
      font-size:22px;color:#fff;text-align:center;
    }

    /* content containers wider */
    .content-wide{max-width:1200px;margin:0 auto;padding:0 20px}

    /* three cards */
    .grid-3{display:grid;gap:18px}
    @media(min-width:980px){ .grid-3{grid-template-columns:repeat(3,1fr)} }
    .card{background:var(--card);border-radius:12px;padding:20px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 14px 36px rgba(4,31,58,0.05)}
    .card h3{color:var(--blue-deep);font-size:18px;margin-bottom:8px}
    .card p{color:var(--muted);line-height:1.6}

    /* objectives grid */
    .objectives{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));margin-top:12px}

    /* mentor */
    .mentor{display:flex;gap:20px;align-items:center;background:var(--card);border-radius:12px;padding:20px;box-shadow:0 16px 40px rgba(4,31,58,0.04);border:1px solid rgba(0,0,0,0.04)}
    .mentor img{width:260px;height:260px;object-fit:cover;border-radius:12px}
    .mentor .bio{flex:1}
    .mentor h3{color:var(--blue-deep);margin-bottom:8px}
    .mentor p{color:var(--muted);line-height:1.7}

    /* FAQ */
    .faq-item{background:linear-gradient(180deg,#fff,#fbfdff);border-radius:12px;padding:18px;box-shadow:0 12px 30px rgba(4,31,58,0.04);margin-bottom:12px;cursor:pointer;border-left:6px solid rgba(15,76,129,0.06)}
    .faq-item h4{font-family:'Playfair Display',serif;color:var(--blue-deep);margin:0}
    .faq-item p{color:var(--muted);margin-top:10px;max-height:0;overflow:hidden;transition:max-height .36s ease;padding:0}
    .faq-item.open p{max-height:420px;padding-top:8px}

    /* who boxes */
    .who-grid{display:grid;gap:20px;grid-template-columns:1fr 1fr}
    @media(max-width:980px){ .who-grid{grid-template-columns:1fr} }
    .who-box{background:var(--card);border-radius:12px;padding:20px;box-shadow:0 12px 30px rgba(4,31,58,0.03)}

    /* floating controls (now smooth-follow) */
    .countdown-float, .whatsapp-float{
      position:fixed;right:18px;z-index:9999;border-radius:12px;box-shadow:0 20px 46px rgba(4,31,58,0.18);
      transition:top 280ms cubic-bezier(.22,.98,.26,1), transform 200ms ease;
      will-change:top;
    }

    .countdown-float{left:18px;right:auto;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;padding:14px 18px;font-weight:800;text-align:center}
    .countdown-float .time{font-size:18px}
    .countdown-float .label{font-size:13px;margin-top:6px;opacity:.95}

    .whatsapp-float{right:18px;left:auto;background:#25D366;color:#fff;padding:12px 18px;font-weight:800;cursor:pointer;display:flex;align-items:center;gap:10px}
    .whatsapp-float:active{transform:translateY(1px)}
    .whatsapp-float small{font-weight:600}

    /* footer band full-bleed */
    .footer-bleed{
      width:100vw;left:50%;transform:translateX(-50%);
      background:var(--blue-dark);color:#fff;padding:14px 20px;text-align:center;position:relative;margin-top:40px;
    }

    /* responsive adjustments */
    @media(max-width:980px){
      .hero{padding:22px 20px 48px;margin:18px 12px 28px}
      .hero-inner{padding:0 8px}
      h1.title{font-size:clamp(22px,6.5vw,36px)}
      .workshop-bleed h2{font-size:20px}
      .mentor{flex-direction:column;align-items:center}
      .mentor img{width:100%;max-width:340px;height:auto}
      .countdown-float{left:14px;right:auto;bottom:140px;top:auto}
      .whatsapp-float{right:14px;left:auto;bottom:18px;top:auto}
      .section-flag{height:30px}
      .section-title{margin-top:-36px}
      .who-grid{grid-template-columns:1fr;gap:14px}
      .objectives{grid-template-columns:repeat(auto-fit,minmax(200px,1fr))}
    }

    @media(max-width:420px){
      .hero{margin:14px 8px 18px}
      .workshop-bleed h2{font-size:18px}
      .section-flag{height:22px}
      .section-title{font-size:18px;margin-top:-32px}
      .countdown-float{bottom:110px}
      .whatsapp-float{bottom:12px;padding:10px 14px}
    }
  </style>
</head>
<body>
  <div class="full-bleed-top">
    <!-- full-bleed workshop strip -->
    <div class="workshop-bleed" aria-hidden="true">
      <h2>WORKSHOP</h2>
    </div>
  </div>

  <div class="wrap">
    <header class="topbar" aria-hidden="true">
      <div class="brand">
        <div class="logo" aria-hidden="true">🌿</div>
        <div style="font-weight:800;font-family:'Playfair Display',serif;color:var(--blue-deep)">Antes de virar o ano</div>
      </div>
      <nav aria-label="Navegação principal">
        <a href="#noites">Noites</a>
        <a href="#objetivos">Objetivos</a>
        <a href="#mentor">Mentor</a>
        <a href="#faq">Perguntas</a>
      </nav>
    </header>

    <main class="hero" role="main" aria-labelledby="hero-title">
      <div class="hero-inner">
        <h1 id="hero-title" class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline" aria-hidden="true"></div>
        <p class="lead">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
      </div>
    </main>

    <!-- AS TRÊS NOITES (flag full-bleed) -->
    <section id="noites" aria-labelledby="noites-title">
      <div class="section-flag" aria-hidden="true"></div>
      <h2 id="noites-title" class="section-title">As três noites</h2>

      <div class="content-wide grid-3" style="margin-top:18px">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz: mágoas, culpas e cobranças que já não cabem mais. Nomear para começar a libertar.</p></article>
        <article class="card"><h3>💚 2ª Noite — Quando soltar é cuidar</h3><p>Exercícios práticos para soltar o controle, acolher limites e aprender que cuidar também é pausar.</p></article>
        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Ritual de encerramento: transformar o vivido em sabedoria e definir intenções para 2026.</p></article>
      </div>
    </section>

    <!-- OBJETIVOS (flag full-bleed) -->
    <section id="objetivos" aria-labelledby="obj-title">
      <div class="section-flag" aria-hidden="true"></div>
      <h2 id="obj-title" class="section-title">Objetivos do Workshop</h2>

      <div class="content-wide objectives">
        <div class="card objective-card"><h3>Reconhecer o que pesa</h3><p>Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div class="card objective-card"><h3>Aprender a soltar</h3><p>Ferramentas práticas para libertar ansiedade, culpa e cobranças.</p></div>
        <div class="card objective-card"><h3>Recomeçar com intenção</h3><p>Definir ações e intenções suaves para entrar em 2026 com mais clareza e leveza.</p></div>
      </div>
    </section>

    <!-- PARA QUEM -->
    <section id="para-quem" aria-labelledby="who-title">
      <div class="section-flag" aria-hidden="true"></div>
      <h2 id="who-title" class="section-title">Para quem é / Para quem não é</h2>

      <div class="content-wide who-grid" style="margin-top:18px">
        <div class="who-box"><h4>Para quem é</h4>
          <ul>
            <li>Pessoas que querem fechar o ano com clareza emocional e leveza.</li>
            <li>Quem busca um processo guiado, humano e prático.</li>
            <li>Quem está disposto(a) a reservar ~1h nas três noites.</li>
            <li>Pessoas abertas a práticas de introspecção e rituais de encerramento.</li>
          </ul>
        </div>
        <div class="who-box"><h4>Para quem não é</h4>
          <ul>
            <li>Quem procura fórmulas mágicas ou soluções instantâneas sem participação.</li>
            <li>Quem não pode reservar tempo nas três noites.</li>
            <li>Quem não está disposto(a) a olhar para emoções.</li>
            <li>Quem deseja resultado sem investimento pessoal.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- MENTOR (flag full-bleed) -->
    <section id="mentor" aria-labelledby="mentor-title">
      <div class="section-flag" aria-hidden="true"></div>
      <h2 id="mentor-title" class="section-title">Conheça seu mentor</h2>

      <div class="content-wide mentor" style="margin-top:18px">
        <img src="Mentor.jpeg" alt="Evandro Favoretto — mentor do workshop">
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
        </div>
      </div>
    </section>

    <!-- FAQ (flag full-bleed) -->
    <section id="faq" aria-labelledby="faq-title">
      <div class="section-flag" aria-hidden="true"></div>
      <h2 id="faq-title" class="section-title">Perguntas Frequentes</h2>

      <div class="content-wide" style="margin-top:18px">
        <div class="faq-item" tabindex="0"><h4>Para quem é o Workshop?</h4><p>Para quem busca clareza emocional e sistêmica para decidir com mais segurança e quer um processo guiado, humano e direto ao ponto.</p></div>
        <div class="faq-item" tabindex="0"><h4>Preciso participar ao vivo?</h4><p>É recomendado — haverá gravação por tempo limitado para quem não puder assistir ao vivo.</p></div>
        <div class="faq-item" tabindex="0"><h4>O evento é gratuito?</h4><p>Sim — a inscrição e o link são divulgados no grupo do WhatsApp.</p></div>
        <div class="faq-item" tabindex="0"><h4>Como faço a inscrição?</h4><p>Clique no botão “Entrar no grupo” para acessar o grupo e receber os links e orientações.</p></div>
        <div class="faq-item" tabindex="0"><h4>Tenho dúvidas ou preciso de suporte</h4><p>Suporte via grupo do WhatsApp e mensagens antes de cada encontro.</p></div>
      </div>
    </section>

  </div> <!-- .wrap -->

  <!-- footer full-bleed azul forte -->
  <div class="footer-bleed" role="contentinfo">
    © 2025 — Todos os direitos reservados a Workshop “Antes de virar o ano. Quero estar em paz comigo mesmo.”
  </div>

  <!-- floating countdown & whatsapp (seguir rolagem) -->
  <div class="countdown-float" id="countdown" aria-live="polite" role="status" style="top:160px">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">--d — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" id="whatsBtn" onclick="openGroup()" aria-label="Entrar no grupo do WhatsApp" style="top:220px">
    Entrar no grupo
  </button>

  <script>
    // abrir grupo
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

    // FAQ toggle
    document.querySelectorAll('.faq-item').forEach(item=>{
      function toggle(){ item.classList.toggle('open'); }
      item.addEventListener('click', toggle);
      item.addEventListener('keydown', (e)=>{ if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(); } });
    });

    // COUNTDOWN
    const targetDate = new Date(2025,11,2,20,0,0);
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

    // floating follow: move controls as user scrolls (smooth-ish)
    (function(){
      const cd = document.getElementById('countdown');
      const wbtn = document.getElementById('whatsBtn');
      if(!cd || !wbtn) return;

      // initial offsets
      const startTopCd = 140; // px from top at start
      const startTopBtn = 200;

      // speed factor (how fast they move down with scroll). tweak as needed (0.15..0.35)
      const speed = 0.18;

      let ticking = false;
      function onScroll(){
        if(ticking) return;
        ticking = true;
        requestAnimationFrame(()=> {
          const s = window.scrollY || window.pageYOffset;
          // compute new top but clamp so it stays within viewport nicely
          const vh = window.innerHeight || document.documentElement.clientHeight;
          // vertical position increases as you scroll down, but limited so doesn't go off-screen
          const newTopCd = Math.min(vh - 180, startTopCd + s * speed);
          const newTopBtn = Math.min(vh - 90, startTopBtn + s * speed);
          cd.style.top = Math.max(12, Math.round(newTopCd)) + 'px';
          wbtn.style.top = Math.max(60, Math.round(newTopBtn)) + 'px';
          ticking = false;
        });
      }

      window.addEventListener('scroll', onScroll, {passive:true});
      window.addEventListener('resize', ()=> { /* recalc on resize if needed */ }, {passive:true});
      // run once to position
      onScroll();
    })();
  </script>
</body>
</html>
