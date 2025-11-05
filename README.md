
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    /* esconder cabeçalhos automáticos do GitHub Pages, se existirem */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --bg-soft:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --blue-dark:#041f3a; /* azul bem escuro para faixas */
      --muted:#5A6571;
      --card:#FFFFFF;
      --shadow-lg:0 30px 60px rgba(15,76,129,0.08);
      --section-flag-height:40px; /* altura maior para as faixas das seções */
    }

    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      -webkit-font-smoothing:antialiased;
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(11,76,129,0.03), transparent 6%),
        linear-gradient(180deg,var(--bg-soft), #FFFFFF 86%);
      color:#122034;
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;position:relative;z-index:1}

    /* topo discreto */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:6px 0 18px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--blue-2),#89CFFD);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-family:'Playfair Display',serif}
    nav a{margin-left:14px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO: quadro branco largo */
    .hero{
      position:relative;
      border-radius:18px;
      background:linear-gradient(180deg, rgba(250,252,255,0.99), rgba(247,249,252,0.98));
      box-shadow:var(--shadow-lg);
      padding:0 48px 64px;
      margin:-90px auto 38px;
      min-height:520px;
      display:flex;
      flex-direction:column;
      align-items:center;
      text-align:center;
      transform:translateX(-2%);
      max-width:calc(100% + 160px);
      overflow:visible;
    }

    /* FAIXA WORKSHOP — trazida mais à esquerda para alinhar com quadro branco */
    .hero-topbar{
      width:120%;
      background:var(--blue-dark);
      padding:28px 0;
      text-align:center;
      position:relative;
      z-index:3;
      transform:translateX(-3%); /* movida mais para a esquerda */
      border-top-left-radius:18px;
      border-top-right-radius:18px;
      box-shadow:none;
      border-bottom:none;
    }
    .hero-topbar h2{
      color:#fff;
      font-family:'Playfair Display',serif;
      font-size:clamp(32px,5.6vw,56px);
      line-height:0.95;
      margin:0;
      font-weight:700;
      white-space:nowrap;
      letter-spacing:.02em;
    }

    /* Conteúdo abaixo da faixa */
    .hero-content{margin-top:22px;display:flex;flex-direction:column;align-items:center;z-index:5;padding:0 6px}
    h1.title{
      font-family:'Playfair Display',serif;
      font-size:clamp(32px,6vw,72px);
      line-height:1.02;
      color:var(--blue-deep);
      max-width:820px;
      margin:8px auto 6px;
      text-align:center;
      word-break:normal;
    }
    .underline{width:220px;height:10px;border-radius:999px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));margin:10px auto 0}
    .title-sub{margin-top:12px;color:var(--muted);font-size:15px;max-width:760px;text-align:center}

    /* Sections geral */
    section{padding:52px 0}
    .section-title-wrap{position:relative;margin-bottom:16px;display:flex;align-items:center;justify-content:center}
    .section-flag{
      position:absolute;left:50%;transform:translateX(-50%);
      width:100%;height:var(--section-flag-height);background:var(--blue-dark);border-radius:10px;z-index:0;opacity:1;
      max-width:calc(100% - 120px);
    }
    .section-title{position:relative;z-index:2;font-family:'Playfair Display',serif;font-size:28px;color:#fff;padding:8px 16px;margin:0 auto;background:transparent;letter-spacing:0.01em}
    /* note: section-title is white to stand on dark flag */

    /* Objetivos: cards */
    .objectives{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));max-width:1100px;margin:0 auto}
    .objective-card{background:#fff;border-radius:12px;padding:20px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 30px rgba(15,76,129,0.04);text-align:center}
    .objective-card h3{font-family:'Playfair Display',serif;color:var(--blue-deep);margin-bottom:8px}
    .objective-card p{color:var(--muted);line-height:1.6}

    /* Três noites (cards) */
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

    /* FAQ interativo: contraste maior e abertura suave */
    .faq{max-width:900px;margin:0 auto}
    .faq-item{background:linear-gradient(180deg,#fff,#fbfdff);border-radius:12px;padding:16px;box-shadow:0 8px 20px rgba(15,76,129,0.05);margin-bottom:12px;cursor:pointer;outline:none;border-left:4px solid rgba(15,76,129,0.06)}
    .faq-item:hover{box-shadow:0 12px 26px rgba(15,76,129,0.08);border-left-color:var(--blue-deep)}
    .faq-item h4{margin:0;color:var(--blue-deep);font-family:'Playfair Display',serif}
    .faq-item p{margin-top:10px;color:var(--muted);line-height:1.6;max-height:0;overflow:hidden;transition:max-height .36s ease,padding .36s ease}
    .faq-item.open p{max-height:420px;padding-top:8px}

    /* contagem vertical lado esquerdo (centrada verticalmente) */
    .countdown-float{
      position:fixed;left:18px;top:50%;transform:translateY(-50%);
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;
      padding:12px 16px;border-radius:12px;font-weight:800;
      box-shadow:0 20px 46px rgba(15,76,129,0.22);z-index:1004;text-align:center;
    }
    .countdown-float .time{font-size:18px}
    .countdown-float .label{font-size:12px;opacity:.95;margin-top:6px}

    /* WhatsApp flutuante */
    .whatsapp-float{position:fixed;right:18px;bottom:80px;background:#25D366;color:#fff;border-radius:999px;padding:12px 16px;font-weight:800;box-shadow:0 20px 46px rgba(0,0,0,0.18);z-index:1005;display:flex;gap:10px;align-items:center;font-size:15px;border:0;cursor:pointer}

    /* faixa final estreita full-width */
    .copyright-band{
      width:100%;
      background:var(--blue-dark);
      color:#fff;
      padding:12px 0;
      text-align:center;
      box-shadow:0 -6px 20px rgba(7,42,73,0.06);
      font-size:14px;
    }

    footer{padding:18px 0;text-align:center;color:var(--muted);font-size:13px}

    /* responsividade */
    @media(max-width:880px){
      .hero{transform:none;padding:0 20px 50px;margin:-60px 12px 28px;min-height:460px}
      .hero-topbar{transform:none;width:100%;padding:20px 0;border-radius:12px 12px 0 0}
      .hero-topbar h2{font-size:clamp(24px,10vw,40px)}
      .countdown-float{left:12px;top:60%}
      .whatsapp-float{right:12px;bottom:72px}
      .mentor{flex-direction:column;align-items:flex-start}
      .mentor img{width:100%;height:260px}
      .section-flag{max-width:calc(100% - 40px)}
    }
  </style>
</head>
<body>
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

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div class="hero-topbar" aria-hidden="true">
        <h2>WORKSHOP</h2>
      </div>

      <div class="hero-content">
        <h1 id="hero-title" class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline" aria-hidden="true"></div>
        <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
      </div>
    </main>

    <!-- AS TRÊS NOITES (faixa atrás do título) -->
    <section id="noites">
      <div class="section-title-wrap" aria-hidden="true">
        <div class="section-flag"></div>
        <h2 class="section-title">As três noites</h2>
      </div>

      <div class="grid-3" style="margin-top:8px">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz: mágoas, culpas e cobranças que já não cabem mais. Nomear para começar a libertar.</p></article>
        <article class="card"><h3>💚 2ª Noite — Quando soltar é cuidar</h3><p>Exercícios e práticas para soltar controle, acolher limites e aprender que cuidar também é pausar.</p></article>
        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Ritual de encerramento: transformar o vivido em sabedoria e definir intenções para 2026.</p></article>
      </div>
    </section>

    <!-- OBJETIVOS (faixa atrás do título) -->
    <section id="objetivos">
      <div class="section-title-wrap">
        <div class="section-flag"></div>
        <h2 class="section-title">Objetivos do Workshop</h2>
      </div>

      <div class="objectives">
        <div class="objective-card"><h3>Reconhecer o que pesa</h3><p>Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div class="objective-card"><h3>Aprender a soltar</h3><p>Ferramentas práticas para libertar ansiedade, culpa e cobranças.</p></div>
        <div class="objective-card"><h3>Recomeçar com intenção</h3><p>Definir ações e intenções suaves para entrar em 2026 com mais clareza e leveza.</p></div>
      </div>
    </section>

    <!-- Mentor -->
    <section id="mentor">
      <div class="section-title-wrap" style="margin-bottom:8px">
        <div class="section-flag" aria-hidden="true"></div>
        <h2 class="section-title">Conheça seu mentor</h2>
      </div>

      <div class="mentor" role="region" aria-label="Mentor">
        <img src="Mentor.jpeg" alt="Evandro Favoretto — mentor do workshop">
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq">
      <div class="section-title-wrap" style="margin-bottom:12px">
        <div class="section-flag"></div>
        <h2 class="section-title">Perguntas Frequentes</h2>
      </div>

      <div class="faq" role="list">
        <div class="faq-item" role="listitem" tabindex="0">
          <h4>Para quem é o Workshop?</h4>
          <p>Para quem busca clareza emocional e sistêmica para decidir com mais segurança, e deseja um processo guiado, humano e direto ao ponto.</p>
        </div>

        <div class="faq-item" role="listitem" tabindex="0">
          <h4>Preciso participar ao vivo?</h4>
          <p>É recomendado para aproveitar as práticas e a energia do grupo. Haverá gravação para quem não puder assistir ao vivo (acesso por tempo limitado).</p>
        </div>

        <div class="faq-item" role="listitem" tabindex="0">
          <h4>O evento é gratuito?</h4>
          <p>Sim. O workshop é gratuito — a inscrição e o link do encontro são compartilhados no grupo do WhatsApp.</p>
        </div>

        <div class="faq-item" role="listitem" tabindex="0">
          <h4>Como faço a inscrição?</h4>
          <p>Clique em “Entrar no grupo” (botão verde no canto) para acessar o grupo de organização e receber os links e materiais.</p>
        </div>

        <div class="faq-item" role="listitem" tabindex="0">
          <h4>Tenho dúvidas ou preciso de suporte</h4>
          <p>Haverá suporte via grupo do WhatsApp e mensagens antes de cada encontro com orientações práticas.</p>
        </div>
      </div>
    </section>

  </div> <!-- /.wrap -->

  <!-- faixa final e copyright -->
  <div class="copyright-band" role="contentinfo">
    Todos os direitos reservados a Workshop “Antes de virar o ano. Quero estar em paz comigo mesmo.”
  </div>

  <footer aria-hidden="true">© 2025</footer>

  <!-- contagem vertical-izquierda -->
  <div class="countdown-float" id="countdown" role="status" aria-live="polite">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">-- dias — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <!-- botão WhatsApp -->
  <button class="whatsapp-float" onclick="openGroup()" aria-label="Entrar no grupo do WhatsApp">Entrar no grupo</button>

  <script>
    // link do grupo
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

    // FAQ interativo: clicando no item abre/fecha; teclado: Enter/Space
    document.querySelectorAll('.faq-item').forEach(item=>{
      function toggle(){ item.classList.toggle('open'); }
      item.addEventListener('click', toggle);
      item.addEventListener('keydown', (e)=>{ if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(); } });
    });

    // Contagem regressiva (02 Dez 2025 20:00 local)
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
