<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --blue-1:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --blue-dark:#0B355F;
      --muted:#5A6571;
      --shadow-lg:0 30px 60px rgba(15,76,129,0.08);
    }

    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      background:linear-gradient(180deg,var(--blue-1),#fff);
      color:#122034;
      -webkit-font-smoothing:antialiased;
    }

    .wrap{max-width:1200px;margin:0 auto;padding:28px;position:relative;z-index:1}

    /* HERO */
    .hero{
      position:relative;
      border-radius:22px;
      background:linear-gradient(180deg, rgba(240,245,252,0.98), rgba(235,242,250,0.96));
      box-shadow:var(--shadow-lg);
      padding:0 56px 96px;
      margin:-120px auto 34px;
      min-height:640px;
      display:flex;
      flex-direction:column;
      justify-content:flex-start;
      align-items:center;
      text-align:center;
      transform:translateX(-3%);
      max-width:calc(100% + 200px);
      overflow:hidden;
    }

    /* BARRA AZUL ESCURA */
    .hero-topbar{
      width:100%;
      background:var(--blue-dark);
      padding:60px 0 40px;
      text-align:center;
      position:relative;
      z-index:3;
    }
    .hero-topbar h2{
      color:#fff;
      font-family:'Playfair Display',serif;
      font-size:clamp(64px,9vw,140px);
      letter-spacing:.03em;
      margin:0;
      font-weight:800;
    }

    /* CONTEÚDO CENTRAL */
    .hero-content{
      margin-top:-30px;
      display:flex;
      flex-direction:column;
      align-items:center;
      z-index:5;
    }

    h1.title{
      font-family:'Playfair Display',serif;
      font-size:clamp(36px,6vw,80px);
      line-height:1.05;
      color:var(--blue-deep);
      max-width:760px;
      margin:0 auto;
      text-align:center;
    }

    .underline{
      width:220px;height:12px;border-radius:999px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));
      margin:18px auto 0;
    }

    .title-sub{
      margin-top:14px;
      color:var(--muted);
      font-size:17px;
      max-width:760px;
      text-align:center;
    }

    .hero-ctas{
      display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;justify-content:center;
    }
    .btn{border-radius:12px;padding:14px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0}
    .btn-primary{background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.08);color:var(--muted)}

    /* --- OBJETIVOS --- */
    section{padding:60px 0;border-top:1px solid rgba(0,0,0,0.04)}
    .section-title{
      font-family:'Playfair Display',serif;
      font-size:32px;
      color:var(--blue-deep);
      text-align:center;
      margin-bottom:30px;
    }

    .objectives{
      display:grid;
      gap:18px;
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    }

    .objective-card{
      background:#fff;
      border:1px solid rgba(0,0,0,0.05);
      border-radius:12px;
      padding:20px;
      box-shadow:0 10px 30px rgba(15,76,129,0.05);
      text-align:center;
    }

    .objective-card h3{
      color:var(--blue-deep);
      font-size:20px;
      margin-bottom:8px;
      font-family:'Playfair Display',serif;
    }

    .objective-card p{
      color:var(--muted);
      line-height:1.6;
      font-size:15px;
    }

    /* --- FAQ --- */
    .faq{
      max-width:850px;
      margin:0 auto;
    }
    .faq-item{
      background:#fff;
      border-radius:12px;
      padding:18px;
      box-shadow:0 8px 20px rgba(15,76,129,0.06);
      margin-bottom:14px;
      cursor:pointer;
      transition:all .2s ease;
    }
    .faq-item:hover{transform:translateY(-2px)}
    .faq-item h4{
      margin:0;
      color:var(--blue-deep);
      font-size:18px;
      font-family:'Playfair Display',serif;
    }
    .faq-item p{
      color:var(--muted);
      font-size:15px;
      margin-top:8px;
      line-height:1.6;
    }

    /* flutuantes */
    .countdown-float{
      position:fixed;left:18px;bottom:18px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;
      padding:12px 16px;border-radius:12px;font-weight:800;
      box-shadow:0 20px 46px rgba(15,76,129,0.22);
      z-index:1004;text-align:center;
    }
    .whatsapp-float{
      position:fixed;right:18px;bottom:80px;background:#25D366;color:#fff;border-radius:999px;
      padding:12px 16px;font-weight:800;box-shadow:0 20px 46px rgba(0,0,0,0.18);
      z-index:1005;display:flex;gap:10px;align-items:center;font-size:15px;border:0;cursor:pointer;
    }

    /* faixa final */
    .final-band{width:100%;background:linear-gradient(180deg,var(--blue-deep),#0A3C66);color:#fff;padding:48px 0;margin-top:40px;text-align:center}
    .final-band h2{font-family:'Playfair Display',serif;font-size:clamp(28px,6vw,52px);line-height:1.1;margin:0 auto;max-width:900px}
    footer{text-align:center;padding:28px 0;color:var(--muted);font-size:13px}
  </style>
</head>
<body>
  <div class="wrap">
    <main class="hero">
      <div class="hero-topbar">
        <h2>WORKSHOP</h2>
      </div>
      <div class="hero-content">
        <h1 class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline"></div>
        <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
        <div class="hero-ctas">
          <button class="btn btn-primary" onclick="openGroup()">Já tomei minha decisão</button>
          <button class="btn btn-primary" onclick="openGroup()">Quero me inscrever agora</button>
          <button class="btn btn-alt">Ainda estou com dúvida</button>
        </div>
      </div>
    </main>

    <!-- OBJETIVOS -->
    <section id="objetivos">
      <h2 class="section-title">Objetivos do Workshop</h2>
      <div class="objectives">
        <div class="objective-card">
          <h3>Reconhecer o que pesa</h3>
          <p>Identificar emoções, mágoas e culpas que ainda prendem você ao passado.</p>
        </div>
        <div class="objective-card">
          <h3>Aprender a soltar</h3>
          <p>Compreender que o cuidado verdadeiro começa quando se permite descansar e confiar.</p>
        </div>
        <div class="objective-card">
          <h3>Recomeçar em paz</h3>
          <p>Encerrar o ciclo de 2025 com leveza e criar intenções conscientes para 2026.</p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq">
      <h2 class="section-title">Perguntas Frequentes</h2>
      <div class="faq">
        <div class="faq-item">
          <h4>Para quem é o Workshop?</h4>
          <p>Para pessoas que desejam fechar o ano com mais clareza emocional, leveza e reconexão consigo mesmas.</p>
        </div>

        <div class="faq-item">
          <h4>Preciso participar ao vivo?</h4>
          <p>Recomendamos sim — a energia do grupo e as práticas guiadas são mais poderosas ao vivo. Mas haverá acesso posterior para quem não puder.</p>
        </div>

        <div class="faq-item">
          <h4>O evento é gratuito?</h4>
          <p>Sim, 100% gratuito. Basta entrar no grupo oficial de WhatsApp para garantir sua vaga.</p>
        </div>

        <div class="faq-item">
          <h4>Vai ter gravação?</h4>
          <p>As gravações ficam disponíveis por tempo limitado apenas para os inscritos no grupo.</p>
        </div>

        <div class="faq-item">
          <h4>Como faço para participar?</h4>
          <p>Clique em “Entrar no grupo” e garanta seu lugar para receber os links e materiais de cada noite.</p>
        </div>
      </div>
    </section>
  </div>

  <div class="final-band">
    <h2>Antes de virar o ano, quero estar em paz comigo.</h2>
    <p>Três noites práticas (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz.</p>
  </div>

  <div class="countdown-float" id="countdown">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">-- dias — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" onclick="openGroup()">
    Entrar no grupo
  </button>

  <footer>© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</footer>

  <script>
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

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
