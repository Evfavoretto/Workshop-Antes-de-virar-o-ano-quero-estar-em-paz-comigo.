<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <meta name="description" content="Três noites (2,3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    /* tenta esconder header do GitHub Pages, se existir */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --blue-1:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --blue-dark:#072a49; /* faixa mais escura */
      --muted:#5A6571;
      --shadow-lg:0 30px 60px rgba(15,76,129,0.08);
      --hero-title: clamp(36px,6.2vw,72px);
      --final-sub: clamp(28px,5.6vw,48px);
    }

    *{box-sizing:border-box}
    html,body{height:100%;margin:0}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:#122034;
      -webkit-font-smoothing:antialiased;
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(11,76,129,0.04), transparent 6%),
        linear-gradient(180deg,var(--blue-1), #FFFFFF 86%);
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;position:relative;z-index:1}

    /* topbar (simple) */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:8px 0;margin-bottom:6px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:52px;height:52px;border-radius:10px;background:linear-gradient(135deg,var(--blue-2),#89CFFD);display:flex;align-items:center;justify-content:center;color:#fff;font-family:'Playfair Display',serif;font-weight:700}
    nav a{margin-left:16px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO - quadro branco mais largo, deslocado levemente */
    .hero{
      position:relative;
      border-radius:18px;
      background:linear-gradient(180deg, rgba(250,252,255,0.99), rgba(247,249,252,0.98));
      box-shadow:var(--shadow-lg);
      padding:0 48px 64px;
      margin:-90px auto 38px; /* empurra para cima para esconder header azul */
      min-height:520px;
      display:flex;
      flex-direction:column;
      align-items:center;
      text-align:center;
      transform:translateX(-2%); /* ligeiro deslocamento esquerdo */
      max-width:calc(100% + 160px);
      overflow:visible;
    }

    /* FAIXA AZUL ESCURA — reduzida e centralizada; largura maior visualmente */
    .hero-topbar{
      width:110%;
      max-width:none;
      background:var(--blue-dark);
      padding:36px 0;            /* reduzimos a altura */
      text-align:center;
      position:relative;
      z-index:3;
      transform:translateX(-5%); /* alarga a faixa para as laterais */
      border-top-left-radius:18px;
      border-top-right-radius:18px;
    }

    /* WORKSHOP branco — menor e sem quebra */
    .hero-topbar h2{
      color:#fff;
      font-family:'Playfair Display',serif;
      font-size:clamp(36px,6.2vw,72px); /* menor e responsivo */
      line-height:0.95;
      margin:0;
      font-weight:700;
      white-space:nowrap; /* evita quebra em 'P' na linha de baixo */
      letter-spacing:.02em;
    }

    /* conteudo abaixo da faixa (gera espaçamento suficiente) */
    .hero-content{
      margin-top:22px; /* garante que H1 fique bem abaixo da faixa */
      display:flex;
      flex-direction:column;
      align-items:center;
      z-index:5;
      padding:0 6px;
    }

    h1.title{
      font-family:'Playfair Display',serif;
      font-size:var(--hero-title);
      line-height:1.02;  /* reduzido para duas linhas mais densas */
      color:var(--blue-deep);
      max-width:820px;
      margin:8px auto 6px;
      text-align:center;
      word-break:normal;
    }

    .underline{width:220px;height:10px;border-radius:999px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));margin:10px auto 0}
    .title-sub{margin-top:12px;color:var(--muted);font-size:15px;max-width:760px;text-align:center}

    .hero-ctas{display:flex;gap:12px;margin-top:20px;flex-wrap:wrap;justify-content:center}
    .btn{border-radius:12px;padding:12px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0}
    .btn-primary{background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.08);color:var(--muted)}

    /* Sections */
    section{padding:52px 0;border-top:1px solid rgba(0,0,0,0.04)}
    .section-title{font-family:'Playfair Display',serif;font-size:28px;color:var(--blue-deep);text-align:center;margin-bottom:20px}

    /* Objetivos */
    .objectives{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));max-width:1100px;margin:0 auto}
    .objective-card{background:#fff;border-radius:12px;padding:20px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 30px rgba(15,76,129,0.04);text-align:center}
    .objective-card h3{font-family:'Playfair Display',serif;color:var(--blue-deep);margin-bottom:8px}
    .objective-card p{color:var(--muted);line-height:1.6}

    /* Noites (cards) */
    .grid-3{display:grid;gap:18px;margin-top:8px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:#fff;padding:18px;border-radius:12px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 30px rgba(0,0,0,0.03)}
    .card h3{font-size:18px;margin:0 0 8px;color:var(--blue-deep)} .card p{color:var(--muted);line-height:1.6}

    /* Mentor */
    .mentor{display:flex;gap:18px;align-items:center;padding:18px;border-radius:12px;background:#fff;border:1px solid rgba(0,0,0,0.04);box-shadow:0 12px 36px rgba(0,0,0,0.04);max-width:1100px;margin:0 auto}
    .mentor img{width:200px;height:200px;border-radius:10px;object-fit:cover}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:20px;color:var(--blue-deep)}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    /* FAQ interativo */
    .faq{max-width:900px;margin:0 auto}
    .faq-item{background:#fff;border-radius:12px;padding:16px;box-shadow:0 8px 20px rgba(15,76,129,0.05);margin-bottom:12px;cursor:pointer}
    .faq-item h4{margin:0;color:var(--blue-deep);font-family:'Playfair Display',serif}
    .faq-item p{margin-top:10px;color:var(--muted);line-height:1.6;max-height:0;overflow:hidden;transition:max-height .36s ease}
    .faq-item.open p{max-height:420px}

    /* floating controls */
    .countdown-float{position:fixed;left:18px;bottom:18px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;padding:12px 16px;border-radius:12px;font-weight:800;box-shadow:0 20px 46px rgba(15,76,129,0.22);z-index:1004;text-align:center}
    .whatsapp-float{position:fixed;right:18px;bottom:80px;background:#25D366;color:#fff;border-radius:999px;padding:12px 16px;font-weight:800;box-shadow:0 20px 46px rgba(0,0,0,0.18);z-index:1005;display:flex;gap:10px;align-items:center;font-size:15px;border:0;cursor:pointer}

    /* final band */
    .final-band{width:100%;background:linear-gradient(180deg,var(--blue-deep),#0A3C66);color:#fff;padding:48px 0;margin-top:36px;text-align:center}
    .final-band h2{font-family:'Playfair Display',serif;font-size:var(--final-sub);margin:0 auto;max-width:900px}
    .final-band p{opacity:.95;margin-top:8px}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:13px;margin-top:18px}

    /* responsive tweaks */
    @media(max-width:880px){
      .hero{transform:none;padding:0 20px 56px;margin:-60px 12px 28px}
      .hero-topbar{transform:none;width:100%;padding:30px 0 22px;border-radius:12px 12px 0 0}
      .hero-topbar h2{font-size:clamp(28px,10vw,48px)}
      .hero-content{margin-top:14px;padding:0 8px}
      .mentor{flex-direction:column;align-items:flex-start}
      .mentor img{width:100%;height:280px}
      .countdown-float{left:12px;bottom:18px}
      .whatsapp-float{right:12px;bottom:78px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header class="topbar" aria-hidden="true">
      <div class="brand"><div class="logo">🌿</div><div style="font-weight:800;font-family:'Playfair Display',serif;color:var(--blue-deep)">Antes de virar o ano</div></div>
      <nav aria-label="Navegação"><a href="#noites">Noites</a><a href="#objetivos">Objetivos</a><a href="#mentor">Mentor</a><a href="#faq">Perguntas</a></nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div class="hero-topbar" aria-hidden="true">
        <h2>WORKSHOP</h2>
      </div>

      <div class="hero-content">
        <h1 id="hero-title" class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline" aria-hidden="true"></div>
        <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

        <div class="hero-ctas" role="group" aria-label="Ações principais">
          <button class="btn btn-primary" onclick="openGroup()">Já tomei minha decisão</button>
          <button class="btn btn-primary" onclick="openGroup()">Quero me inscrever agora</button>
          <button class="btn btn-alt" onclick="document.getElementById('faq').scrollIntoView({behavior:'smooth'})">Ainda estou com dúvida</button>
        </div>
      </div>
    </main>

    <!-- AS TRÊS NOITES -->
    <section id="noites" aria-labelledby="noites-title">
      <h2 id="noites-title" class="section-title">As três noites</h2>
      <div class="grid-3" style="margin-top:10px">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz: mágoas, culpas e cobranças que já não cabem mais. Nomear para começar a libertar.</p></article>
        <article class="card"><h3>💚 2ª Noite — Quando soltar é cuidar</h3><p>Exercícios e práticas para soltar controle, acolher limites e aprender que cuidar também é pausar.</p></article>
        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Ritual de encerramento: transformar o vivido em sabedoria e definir intenções para 2026.</p></article>
      </div>
    </section>

    <!-- OBJETIVOS -->
    <section id="objetivos" aria-labelledby="obj-title">
      <h2 id="obj-title" class="section-title">Objetivos do Workshop</h2>
      <div class="objectives">
        <div class="objective-card"><h3>Reconhecer o que pesa</h3><p>Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div class="objective-card"><h3>Aprender a soltar</h3><p>Ferramentas práticas para libertar ansiedade, culpa e cobranças.</p></div>
        <div class="objective-card"><h3>Recomeçar com intenção</h3><p>Definir ações e intenções suaves para entrar em 2026 com mais clareza e leveza.</p></div>
      </div>
    </section>

    <!-- MENTOR -->
    <section id="mentor" aria-labelledby="mentor-title">
      <h2 id="mentor-title" class="section-title">Conheça seu mentor</h2>
      <div class="mentor" role="region" aria-label="Mentor">
        <img src="Mentor.jpeg" alt="Evandro Favoretto — mentor do workshop">
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" aria-labelledby="faq-title">
      <h2 id="faq-title" class="section-title">Perguntas Frequentes</h2>
      <div class="faq" role="list">
        <div class="faq-item" role="listitem">
          <h4>Para quem é o Workshop?</h4>
          <p>Para quem busca clareza emocional e sistêmica para decidir com mais segurança, e deseja um processo guiado, humano e direto ao ponto.</p>
        </div>

        <div class="faq-item" role="listitem">
          <h4>Preciso participar ao vivo?</h4>
          <p>É recomendado para aproveitar as práticas e a energia do grupo. Haverá gravação para quem não puder assistir ao vivo (acesso por tempo limitado).</p>
        </div>

        <div class="faq-item" role="listitem">
          <h4>O evento é gratuito?</h4>
          <p>Sim. O workshop é gratuito — a inscrição e o link do encontro são compartilhados no grupo do WhatsApp.</p>
        </div>

        <div class="faq-item" role="listitem">
          <h4>Como faço a inscrição?</h4>
          <p>Clique em “Entrar no grupo” (ícone verde) para acessar o grupo de organização e receber os links e materiais.</p>
        </div>

        <div class="faq-item" role="listitem">
          <h4>Tenho dúvidas ou preciso de suporte</h4>
          <p>Haverá suporte via grupo do WhatsApp e mensagens antes de cada encontro com orientações práticas.</p>
        </div>
      </div>
    </section>
  </div> <!-- fim wrap -->

  <!-- faixa final full-width -->
  <div class="final-band" role="region" aria-label="Destaque final">
    <h2>Antes de virar o ano, quero estar em paz comigo.</h2>
    <p>Três noites práticas (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz.</p>
    <div style="margin-top:14px"><button class="btn btn-primary" style="padding:12px 20px" onclick="openGroup()">Entrar no grupo</button></div>
  </div>

  <footer>© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</footer>

  <!-- flutuantes -->
  <div class="countdown-float" id="countdown" role="status" aria-live="polite">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">-- dias — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" onclick="openGroup()" aria-label="Entrar no grupo do WhatsApp">Entrar no grupo</button>

  <script>
    // link do grupo (fornecido)
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

    // FAQ toggle
    document.querySelectorAll('.faq-item').forEach(item=>{
      const header = item.querySelector('h4');
      header.addEventListener('click', ()=> item.classList.toggle('open'));
      // also allow clicking the whole item
      item.addEventListener('click', ()=> item.classList.toggle('open'));
    });

    // Contagem regressiva (para 02 Dez 2025 20:00 local)
    const targetDate = new Date(2025,11,2,20,0,0);
    function updateCountdown(){
      const now = new Date();
      let diff = targetDate - now;
      const el = document.getElementById('cd-time');
      if(!el) return;
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
