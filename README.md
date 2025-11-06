<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  /* se o GitHub Pages injetar algo, escondemos (comente se for preciso) */
  header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

  :root{
    --blue-dark:#041f3a;
    --blue-deep:#0F4C81;
    --blue-light:#B8E1FF;
    --muted:#5A6571;
    --maxw:1200px;
    --float-width:150px;
    --float-height:110px;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  body{
    font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
    background:linear-gradient(180deg,#EAF4FB,#fff);
    color:#122034;
    -webkit-font-smoothing:antialiased;
  }
  .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}

  /* -------- full-bleed WORKSHOP fixed top -------- */
  .workshop-bleed{
    position:fixed;
    top:0; left:0; width:100vw;
    background:linear-gradient(180deg,var(--blue-dark),var(--blue-deep));
    color:#fff; text-align:center; z-index:999;
    padding:18px 10px; box-shadow:0 10px 30px rgba(4,31,58,0.14);
  }
  .workshop-bleed h2{font-family:'Playfair Display',serif;font-size:clamp(20px,3.8vw,36px);margin:0;font-weight:700}

  /* give page content space so the fixed banner doesn't overlap */
  .top-spacer{height:calc(72px + env(safe-area-inset-top)); /* espaço ajustável */}

  /* HERO CARD (quadro branco) */
  .hero{
    background:#fff;border-radius:14px;padding:36px 28px;margin-top:22px;box-shadow:0 30px 80px rgba(4,31,58,0.06);
    max-width:1150px;margin-left:auto;margin-right:auto;
  }
  .hero h1{font-family:'Playfair Display',serif;font-size:clamp(28px,6vw,52px);color:var(--blue-deep);line-height:1.02;text-align:center;margin-bottom:10px}
  .underline{width:220px;height:9px;border-radius:999px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-light));margin:8px auto}
  .hero p{color:var(--muted);text-align:center;max-width:860px;margin:12px auto 0}

  /* -------- sections: full-bleed flag behind title -------- */
  section{padding:44px 0}
  .flag{
    position:relative; left:50%; transform:translateX(-50%); width:100vw; height:52px; background:var(--blue-dark);
    z-index:0;
  }
  .section-title{
    position:relative; z-index:2; margin-top:-42px; text-align:center; color:#fff; font-family:'Playfair Display',serif;
    font-size:20px;padding:8px 12px; max-width:var(--maxw); margin-left:auto;margin-right:auto;
  }

  .content-wide{max-width:1150px;margin:18px auto;padding:0 18px}

  .grid-3{display:grid;gap:18px}
  @media(min-width:980px){ .grid-3{grid-template-columns:repeat(3,1fr)} }
  .card{background:#fff;border-radius:12px;padding:18px;box-shadow:0 12px 34px rgba(4,31,58,0.04);border:1px solid rgba(0,0,0,0.04)}
  .card h3{color:var(--blue-deep);font-size:18px}
  .card p{color:var(--muted);line-height:1.6}

  /* mentor wide */
  .mentor{display:flex;gap:18px;align-items:center;background:#fff;border-radius:12px;padding:18px;box-shadow:0 16px 36px rgba(4,31,58,0.04)}
  .mentor img{width:220px;height:220px;object-fit:cover;border-radius:12px}
  .mentor .bio{flex:1}
  .mentor h3{color:var(--blue-deep)}

  /* FAQ */
  .faq-item{background:#fff;border-radius:12px;padding:16px;box-shadow:0 12px 30px rgba(4,31,58,0.04);margin-bottom:12px;cursor:pointer;border-left:6px solid rgba(15,76,129,0.06)}
  .faq-item h4{font-family:'Playfair Display',serif;color:var(--blue-deep);margin:0}
  .faq-item p{max-height:0;overflow:hidden;transition:max-height .32s ease,padding .32s; padding:0;color:var(--muted)}
  .faq-item.open p{max-height:480px;padding-top:9px}

  /* who grid */
  .who-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
  @media(max-width:980px){ .who-grid{grid-template-columns:1fr} }
  .who-box{background:#fff;border-radius:12px;padding:18px;box-shadow:0 10px 28px rgba(4,31,58,0.03)}

  /* -------- floating controls: fixed size and follow scroll (no scale) -------- */
  .countdown-float{
    position:fixed; left:14px; width:var(--float-width); height:var(--float-height);
    background:linear-gradient(90deg,var(--blue-deep),var(--blue-light)); color:#fff; border-radius:14px;
    padding:12px; box-shadow:0 20px 50px rgba(4,31,58,0.22); z-index:1200;
    display:flex;flex-direction:column;align-items:center;justify-content:center;
    font-weight:800; text-align:center; font-size:14px;
  }
  .countdown-float .time{font-size:16px}

  .whatsapp-float{
    position:fixed; right:14px; width:170px; height:56px;
    background:#25D366;color:#fff;border-radius:999px;box-shadow:0 20px 46px rgba(0,0,0,0.18);
    z-index:1200;display:flex;align-items:center;justify-content:center;font-weight:800;cursor:pointer;
  }

  /* small/mobile adjustments */
  @media(max-width:980px){
    .workshop-bleed{padding:14px 8px}
    .hero{padding:22px 18px}
    .flag{height:36px}
    .section-title{margin-top:-32px;font-size:18px}
    .countdown-float{width:140px;height:96px;left:12px}
    .whatsapp-float{right:12px;width:150px;height:48px}
    .mentor{flex-direction:column;align-items:center}
    .mentor img{width:100%;max-width:320px;height:auto}
  }

  @media(max-width:420px){
    .section-title{font-size:16px}
    .countdown-float{width:128px;height:88px}
    .whatsapp-float{width:140px;height:48px}
  }

  /* footer full-bleed */
  .footer-bleed{width:100vw;left:50%;transform:translateX(-50%);position:relative;background:var(--blue-dark);color:#fff;padding:14px 16px;text-align:center;margin-top:36px}
</style>
</head>
<body>

  <!-- full-bleed workshop fixed at very top -->
  <div class="workshop-bleed" role="banner" aria-hidden="true">
    <h2>WORKSHOP</h2>
  </div>

  <!-- spacer so content begins below the fixed banner -->
  <div class="top-spacer" aria-hidden="true"></div>

  <div class="wrap">
    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <h1 id="hero-title">Antes de virar o ano, quero estar em paz comigo.</h1>
      <div class="underline" aria-hidden="true"></div>
      <p> Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
    </main>

    <!-- AS TRÊS NOITES (full-bleed flag behind title) -->
    <section id="noites">
      <div class="flag" aria-hidden="true"></div>
      <h2 class="section-title">As três noites</h2>

      <div class="content-wide grid-3" style="margin-top:18px">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz: mágoas, culpas e cobranças que já não cabem mais. Nomear para começar a libertar.</p></article>
        <article class="card"><h3>💚 2ª Noite — Quando soltar é cuidar</h3><p>Exercícios práticos para soltar o controle, acolher limites e aprender que cuidar também é pausar.</p></article>
        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Ritual de encerramento: transformar o vivido em sabedoria e definir intenções para 2026.</p></article>
      </div>
    </section>

    <!-- OBJETIVOS -->
    <section id="objetivos">
      <div class="flag" aria-hidden="true"></div>
      <h2 class="section-title">Objetivos do Workshop</h2>

      <div class="content-wide objectives" style="margin-top:18px">
        <div class="card"><h3>Reconhecer o que pesa</h3><p>Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div class="card"><h3>Aprender a soltar</h3><p>Ferramentas práticas para libertar ansiedade, culpa e cobranças.</p></div>
        <div class="card"><h3>Recomeçar com intenção</h3><p>Definir ações e intenções suaves para entrar em 2026 com mais clareza e leveza.</p></div>
      </div>
    </section>

    <!-- PARA QUEM -->
    <section id="para-quem">
      <div class="flag" aria-hidden="true"></div>
      <h2 class="section-title">Para quem é / Para quem não é</h2>

      <div class="content-wide who-grid" style="margin-top:18px">
        <div class="who-box"><h4>Para quem é</h4><ul><li>Pessoas que querem fechar o ano com clareza emocional e leveza.</li><li>Quem busca um processo guiado, humano e prático.</li><li>Quem está disposto(a) a reservar ~1h nas três noites.</li></ul></div>
        <div class="who-box"><h4>Para quem não é</h4><ul><li>Procura fórmula mágica sem envolvimento.</li><li>Não pretende reservar 1h nas três noites.</li></ul></div>
      </div>
    </section>

    <!-- MENTOR -->
    <section id="mentor">
      <div class="flag" aria-hidden="true"></div>
      <h2 class="section-title">Conheça seu mentor</h2>

      <div class="content-wide mentor" style="margin-top:18px">
        <img src="Mentor.jpeg" alt="Evandro Favoretto">
        <div class="bio"><h3>Evandro Favoretto</h3><p>Graduado em Gestão Financeira, pós-graduação em Neurociência, Psicologia e Saúde Mental; formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário e mentor de vida.</p></div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq">
      <div class="flag" aria-hidden="true"></div>
      <h2 class="section-title">Perguntas Frequentes</h2>

      <div class="content-wide" style="margin-top:18px">
        <div class="faq-item" tabindex="0"><h4>Para quem é o Workshop?</h4><p>Para quem busca clareza emocional e sistêmica e quer um processo guiado, humano e direto ao ponto.</p></div>
        <div class="faq-item" tabindex="0"><h4>Preciso participar ao vivo?</h4><p>Recomendado; haverá gravação por tempo limitado.</p></div>
        <div class="faq-item" tabindex="0"><h4>O evento é gratuito?</h4><p>Sim — inscrição pelo grupo do WhatsApp.</p></div>
      </div>
    </section>

  </div><!-- /.wrap -->

  <!-- footer full-bleed azul forte -->
  <div class="footer-bleed">© 2025 — Todos os direitos reservados a Workshop “Antes de virar o ano, quero estar em paz comigo mesmo.”</div>

  <!-- floating countdown + whatsapp (fixed size; follow scroll via JS but DON'T scale) -->
  <div class="countdown-float" id="countdown" aria-live="polite" style="top:150px">
    <div style="font-size:12px;opacity:.9">Próximo encontro</div>
    <div class="time" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" id="whatsBtn" onclick="openGroup()" style="top:220px" aria-label="Entrar no grupo">
    Entrar no grupo
  </button>

<script>
  // abrir grupo
  const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

  // FAQ toggle (click + keyboard)
  document.querySelectorAll('.faq-item').forEach(item=>{
    const body = item.querySelector('p');
    function toggle(){ item.classList.toggle('open'); }
    item.addEventListener('click', toggle);
    item.addEventListener('keydown', (e)=>{ if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(); } });
  });

  // countdown (02 Dec 2025 20:00)
  const target = new Date(2025,11,2,20,0,0);
  function updateCountdown(){
    const now = new Date();
    let diff = target - now;
    const el = document.getElementById('cd-time');
    if(diff <= 0){ el.textContent = "Começou — veja no grupo"; return; }
    const days = Math.floor(diff / (1000*60*60*24));
    diff -= days*(1000*60*60*24);
    const hours = Math.floor(diff / (1000*60*60));
    diff -= hours*(1000*60*60);
    const mins = Math.floor(diff / (1000*60));
    diff -= mins*(1000*60);
    const secs = Math.floor(diff/1000);
    el.textContent = `${days}d — ${String(hours).padStart(2,'0')}:${String(mins).padStart(2,'0')}:${String(secs).padStart(2,'0')}`;
  }
  updateCountdown(); setInterval(updateCountdown,1000);

  // floating follow: moves buttons down with scroll but keeps fixed size (no scaling)
  (function(){
    const cd = document.getElementById('countdown');
    const wbtn = document.getElementById('whatsBtn');
    const clampMinTop = 12;
    const clampMaxTopFactor = 0.78; // fraction of viewport height to not go past
    const speed = 0.16; // how much scroll moves them

    function onScroll(){
      const s = window.scrollY || window.pageYOffset;
      const vh = window.innerHeight || document.documentElement.clientHeight;
      const maxTop = Math.round(vh * clampMaxTopFactor);
      const newTopCd = Math.min(maxTop, Math.max(clampMinTop, 140 + s * speed));
      const newTopBtn = Math.min(maxTop+40, Math.max(clampMinTop+40, 200 + s * speed));
      cd.style.top = newTopCd + 'px';
      wbtn.style.top = newTopBtn + 'px';
    }
    window.addEventListener('scroll', onScroll, {passive:true});
    window.addEventListener('resize', onScroll, {passive:true});
    onScroll();
  })();
</script>
</body>
</html>
