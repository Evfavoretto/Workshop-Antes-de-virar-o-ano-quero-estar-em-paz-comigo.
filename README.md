<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --work-color: #0b4a74;      /* cor principal do site (faixa, footer, fundo) */
    --noites-color: #0f79b0;    /* azul mais vivo para "As três noites" */
    --panel-bg: #ffffff;        /* fundo de cards (branco) */
    --card-text: #12324a;       /* texto dos cards (alto contraste) */
    --muted: #6c7788;
    --maxw: 1150px;
    --work-h:140px;
    --work-h-small:64px;
    --radius:14px;
  }

  *{box-sizing:border-box;margin:0;padding:0}
  html,body{height:100%}
  body{
    font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
    background:var(--work-color); /* fundo unificado em azul */
    color:#eaf6ff;
    -webkit-font-smoothing:antialiased;
    -webkit-text-size-adjust:100%;
    line-height:1.5;
  }

  /* remover cabeçalho GitHub se aparecer */
  header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

  /* FAIXA WORKSHOP — topo fixa */
  .workshop-bleed{
    position:fixed; top:0; left:0; width:100vw; height:var(--work-h);
    background:var(--work-color);
    display:flex;align-items:center;justify-content:center; z-index:1400;
    box-shadow:0 14px 36px rgba(0,0,0,0.30);
    transition:transform .32s ease, height .28s ease, box-shadow .28s ease;
    will-change:transform;
  }
  .workshop-bleed.hidden{ transform: translateY(-120%); box-shadow:0 6px 14px rgba(0,0,0,0.18); }
  .workshop-bleed h1{ font-family:'Playfair Display',serif;color:#fff;font-size:clamp(18px,3.2vw,44px);letter-spacing:.02em;margin:0; }

  .top-spacer{height:calc(var(--work-h) + 18px); width:100%}

  .container{max-width:var(--maxw);margin:0 auto;padding:18px;}

  /* HERO card */
  .hero{
    background:var(--panel-bg);border-radius:var(--radius);padding:42px 28px;margin:12px auto 36px;
    box-shadow:0 30px 80px rgba(0,0,0,0.28);color:var(--work-color);
    max-width:1100px;text-align:center;
  }
  .hero h2{font-family:'Playfair Display',serif;font-size:clamp(28px,5.6vw,56px);margin:0 0 12px;color:var(--work-color);}
  .hero p{color:var(--muted);max-width:860px;margin:0 auto;line-height:1.6}

  /* AS TRÊS NOITES — faixa full-bleed */
  #noites{
    width:100vw; margin-left:calc(-50vw + 50%); padding:84px 18px 64px;
    background:linear-gradient(180deg,var(--noites-color),#128ec7);
    color:#fff; text-align:center;
  }
  #noites .inner{max-width:var(--maxw);margin:0 auto}
  #noites h3{
    font-family:'Playfair Display',serif;font-size:34px;margin:0 0 28px;color:#fff;
    text-shadow:0 2px 8px rgba(0,0,0,0.18);
  }

  .noites-grid{
    display:grid;gap:22px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));max-width:var(--maxw);margin:0 auto;
  }
  .noites-grid .card{
    background:var(--panel-bg);color:var(--card-text);padding:26px;border-radius:12px;
    box-shadow:0 12px 34px rgba(0,0,0,0.16);text-align:left;min-height:140px;
  }
  .noites-grid h4{color:var(--work-color);font-family:'Playfair Display',serif;margin-bottom:8px;font-size:18px}

  /* seção títulos em faixa menor (objetivos etc) */
  .section-title-wrap{display:flex;align-items:center;justify-content:center;margin:40px 0 18px}
  .section-title{
    color:#fff;background:transparent;font-family:'Playfair Display',serif;font-size:22px;padding:8px 12px;
  }
  .section-underline{
    height:8px;background:var(--work-color);width:60%;border-radius:6px;margin-top:12px;opacity:.95;
  }

  /* OBJETIVOS */
  #objetivos{padding:8px 18px 42px}
  .objetivos-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:22px;max-width:var(--maxw);margin:18px auto 0}
  .objetivos-grid .item{
    background:var(--panel-bg);padding:26px;border-radius:12px;box-shadow:0 16px 40px rgba(0,0,0,0.12);color:var(--card-text);min-height:140px;
  }
  .objetivos-grid h4{font-family:'Playfair Display',serif;color:var(--work-color);margin-bottom:10px;font-size:18px}

  /* PARA QUEM */
  #paraquem{padding:24px 18px 40px}
  .who-grid{display:grid;grid-template-columns:1fr 1fr;gap:22px;max-width:var(--maxw);margin:0 auto}
  .who-box{background:var(--panel-bg);border-radius:12px;padding:20px;box-shadow:0 16px 40px rgba(0,0,0,0.10);color:var(--card-text);min-height:170px}
  .who-box h4{font-family:'Playfair Display',serif;color:var(--work-color);margin-bottom:10px}

  /* MENTOR */
  #mentor{padding:36px 18px}
  .mentor-wrap{max-width:var(--maxw);margin:0 auto;display:flex;gap:24px;align-items:center;flex-wrap:wrap}
  .mentor-photo{width:260px;height:260px;border-radius:12px;overflow:hidden;flex:0 0 260px;box-shadow:0 20px 50px rgba(0,0,0,0.16)}
  .mentor-photo img{width:100%;height:100%;object-fit:cover;display:block}
  .mentor-bio{flex:1;min-width:260px;color:#dbeefb}
  .mentor-bio h3{font-family:'Playfair Display',serif;color:#fff;margin-bottom:6px}

  /* FAQ */
  #faq{padding:36px 18px 80px}
  .faq-wrap{max-width:var(--maxw);margin:0 auto}
  .faq-item{background:var(--panel-bg);border-radius:12px;padding:16px;box-shadow:0 12px 30px rgba(0,0,0,0.10);margin-bottom:12px;cursor:pointer}
  .faq-item h4{font-family:'Playfair Display',serif;color:var(--work-color);margin:0}
  .faq-item p{max-height:0;overflow:hidden;transition:max-height .28s ease,padding .28s;color:var(--muted);padding:0}
  .faq-item.open p{max-height:520px;padding-top:12px}

  /* floats */
  .countdown-float{
    position:fixed; left:12px; width:150px; height:110px;
    background:linear-gradient(90deg,#0f79b0,#66b8e6); color:#fff; border-radius:14px;
    padding:10px; box-shadow:0 24px 60px rgba(0,0,0,0.32); z-index:1500; display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;font-weight:800
  }
  .countdown-float .small{font-size:12px;opacity:.95;margin-bottom:6px}
  .countdown-float .time{font-size:14px}

  .whatsapp-float{
    position:fixed; right:16px; width:170px; height:56px; background:#25D366; color:#fff; border-radius:999px;
    box-shadow:0 20px 46px rgba(0,0,0,0.28); z-index:1500; display:flex;align-items:center;justify-content:center; font-weight:800; cursor:pointer;
  }

  /* footer full-bleed */
  .footer-bleed{width:100vw;left:50%;transform:translateX(-50%);position:relative;background:var(--work-color);color:#fff;padding:20px 16px;text-align:center;margin-top:36px}

  /* responsivo */
  @media(max-width:980px){
    .top-spacer{height:calc(var(--work-h) * 0.72 + 18px)}
    .hero{margin:14px 8px;padding:28px}
    .noites-grid{grid-template-columns:1fr}
    .who-grid{grid-template-columns:1fr}
    .mentor-photo{width:100%;max-width:420px;height:auto}
    .mentor-bio h3{color:#fff}
    .countdown-float{width:130px;height:96px}
    .whatsapp-float{right:8px;width:140px}
  }
  @media(max-width:420px){
    .top-spacer{height:calc(var(--work-h) * 0.56 + 18px)}
    #noites{padding:44px 12px}
  }
</style>
</head>
<body>

  <!-- FAIXA WORKSHOP fixa no topo -->
  <div class="workshop-bleed" id="workBleed" role="banner" aria-hidden="true">
    <h1>WORKSHOP</h1>
  </div>

  <div class="top-spacer" aria-hidden="true"></div>

  <div class="container">
    <!-- HERO -->
    <section class="hero" aria-labelledby="hero-title">
      <h2 id="hero-title">Antes de virar o ano, quero estar em paz comigo.</h2>
      <p>Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
    </section>
  </div>

  <!-- TRÊS NOITES (faixa azul viva) -->
  <section id="noites" aria-labelledby="noites-title">
    <div class="inner">
      <h3 id="noites-title">As três noites</h3>
      <div class="noites-grid" aria-hidden="false">
        <div class="card"><h4>🌙 1ª Noite — O peso que ainda carrego</h4><p>Reconheça o que está tirando sua paz: mágoas, culpas e cobranças que já não cabem mais. Nomear para começar a libertar.</p></div>
        <div class="card"><h4>💚 2ª Noite — Quando soltar é cuidar</h4><p>Exercícios práticos para soltar o controle, acolher limites e aprender que cuidar também é pausar.</p></div>
        <div class="card"><h4>✨ 3ª Noite — O recomeço que nasce da paz</h4><p>Ritual de encerramento: transformar o vivido em sabedoria e definir intenções para 2026.</p></div>
      </div>
    </div>
  </section>

  <div class="container">
    <!-- OBJETIVOS -->
    <div class="section-title-wrap">
      <div class="section-title">Objetivos do Workshop</div>
    </div>
    <div class="section-underline" style="margin:0 auto 22px;max-width:760px"></div>

    <section id="objetivos" aria-labelledby="obj-title">
      <div class="objetivos-grid" style="margin-top:8px">
        <div class="item"><h4>Reconhecer o que pesa</h4><p>Identificar emoções e padrões que atrapalham sua paz — para poder liberar com consciência.</p></div>
        <div class="item"><h4>Aprender a soltar</h4><p>Ferramentas práticas de autocuidado, respiração e presença para perder o aperto emocional.</p></div>
        <div class="item"><h4>Recomeçar com intenção</h4><p>Exercícios e um pequeno ritual de encerramento para definir intenções sutis e claras para 2026.</p></div>
      </div>
    </section>

    <!-- PARA QUEM -->
    <div class="section-title-wrap" style="margin-top:40px">
      <div class="section-title">Para quem é / Para quem não é</div>
    </div>
    <div class="section-underline" style="margin:0 auto 22px;max-width:760px"></div>

    <section id="paraquem" aria-labelledby="who-title">
      <div class="who-grid">
        <div class="who-box">
          <h4>Para quem é</h4>
          <ul style="color:var(--card-text);margin-top:8px;line-height:1.6">
            <li>Pessoas que querem fechar o ano com clareza emocional e leveza.</li>
            <li>Quem busca um processo guiado, humano e prático.</li>
            <li>Quem está disposto(a) a reservar ~1h nas três noites e participar ativamente.</li>
          </ul>
        </div>
        <div class="who-box">
          <h4>Para quem não é</h4>
          <ul style="color:var(--card-text);margin-top:8px;line-height:1.6">
            <li>Quem procura fórmula mágica sem envolvimento pessoal.</li>
            <li>Quem não pretende reservar tempo para praticar nas três noites.</li>
            <li>Quem não quer olhar emoções para entender e transformar padrões.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- MENTOR -->
    <section id="mentor" aria-labelledby="mentor-title">
      <div style="text-align:center;margin-top:40px">
        <div class="section-title">Conheça seu mentor</div>
      </div>
      <div class="section-underline" style="margin:0 auto 22px;max-width:500px"></div>

      <div class="mentor-wrap" style="margin-top:8px">
        <div class="mentor-photo" aria-hidden="false"><img src="Mentor.jpeg" alt="Foto do mentor — Evandro Favoretto"></div>
        <div class="mentor-bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <div style="margin-top:40px" class="section-title-wrap"><div class="section-title">Perguntas Frequentes</div></div>
    <div class="section-underline" style="margin:0 auto 22px;max-width:760px"></div>

    <section id="faq" aria-labelledby="faq-title">
      <div class="faq-wrap">
        <div class="faq-item" tabindex="0"><h4>Preciso participar das três noites?</h4><p>Recomendamos acompanhar o ciclo completo, mas é possível participar de noites isoladas. A sequência traz mais profundidade.</p></div>
        <div class="faq-item" tabindex="0"><h4>É online e haverá gravação?</h4><p>Sim — geralmente disponibilizamos gravações por tempo limitado; quem estiver inscrito recebe o link.</p></div>
        <div class="faq-item" tabindex="0"><h4>Como faço a inscrição?</h4><p>Entre no grupo do WhatsApp (botão “Entrar no grupo”). Lá enviamos confirmação, link de acesso e lembretes.</p></div>
        <div class="faq-item" tabindex="0"><h4>É cobrado algum valor?</h4><p>Não — o workshop é 100% gratuito.</p></div>
        <div class="faq-item" tabindex="0"><h4>Tenho dúvidas ou preciso de suporte</h4><p>Suporte via grupo do WhatsApp: envie sua dúvida e a equipe orienta.</p></div>
      </div>
    </section>

  </div> <!-- /.container -->

  <!-- footer full-bleed -->
  <div class="footer-bleed" role="contentinfo">© 2025 — Todos os direitos reservados a EA Favoretto LTDA.”</div>

  <!-- floats -->
  <div class="countdown-float" id="countdown" aria-live="polite" style="top:160px">
    <div class="small">Próximo encontro</div>
    <div class="time" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" id="whatsBtn" onclick="openGroup()" style="top:220px" aria-label="Entrar no grupo">Entrar no grupo</button>

<script>
  // Link do grupo (mantive o seu)
  const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

  // Toggle FAQ (abrir/fechar)
  document.querySelectorAll('.faq-item').forEach(item=>{
    item.addEventListener('click', ()=> item.classList.toggle('open'));
    item.addEventListener('keydown', (e)=>{ if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); item.classList.toggle('open'); } });
  });

  // Countdown (02 Dez 2025 20:00 local)
  const target = new Date(2025,11,2,20,0,0);
  function updateCountdown(){
    const now = new Date(); let diff = target - now; const el = document.getElementById('cd-time');
    if(diff <= 0){ el.textContent = "Começou — veja no grupo"; return; }
    const days = Math.floor(diff / (1000*60*60*24)); diff -= days*(1000*60*60*24);
    const hours = Math.floor(diff / (1000*60*60)); diff -= hours*(1000*60*60);
    const mins = Math.floor(diff / (1000*60)); diff -= mins*(1000*60);
    const secs = Math.floor(diff/1000);
    el.textContent = `${days}d — ${String(hours).padStart(2,'0')}:${String(mins).padStart(2,'0')}:${String(secs).padStart(2,'0')}`;
  }
  updateCountdown(); setInterval(updateCountdown,1000);

  // floats acompanham scroll (limitado)
  (function(){
    const cd = document.getElementById('countdown');
    const wbtn = document.getElementById('whatsBtn');
    const startCd = 160, startBtn = 220, speed = 0.12;
    function onScroll(){
      const s = window.scrollY || window.pageYOffset; const vh = window.innerHeight || document.documentElement.clientHeight;
      const maxTop = Math.round(vh * 0.78);
      cd.style.top = Math.min(maxTop, Math.max(12, Math.round(startCd + s * speed))) + 'px';
      wbtn.style.top = Math.min(maxTop+40, Math.max(60, Math.round(startBtn + s * speed))) + 'px';
    }
    window.addEventListener('scroll', onScroll, {passive:true});
    window.addEventListener('resize', onScroll, {passive:true});
    onScroll();
  })();

  // AUTO-HIDE da faixa WORKSHOP: esconde ao rolar para baixo, reaparece ao rolar para cima
  (function(){
    const bleed = document.getElementById('workBleed');
    let lastScroll = window.scrollY || 0;
    let ticking = false;
    function onScroll(){
      if(!ticking){
        window.requestAnimationFrame(()=>{
          const current = window.scrollY || 0;
          const delta = current - lastScroll;
          if(delta > 8 && current > 60){
            bleed.classList.add('hidden');
          } else if(delta < -8 || current <= 60){
            bleed.classList.remove('hidden');
          }
          lastScroll = current;
          ticking = false;
        });
        ticking = true;
      }
    }
    window.addEventListener('scroll', onScroll, {passive:true});
    window.addEventListener('touchstart', ()=> lastScroll = window.scrollY || 0, {passive:true});
  })();
</script>
</body>
</html>
