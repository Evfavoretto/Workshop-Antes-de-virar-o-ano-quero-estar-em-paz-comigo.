
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    /* cor única do workshop — ajuste aqui se quiser outro tom */
    --work-color: #0b4a74;      /* cor principal (faixa, footer, fundo unificado) */
    --noites-color: #0f79b0;    /* azul para a seção "As três noites" (mais vivo) */
    --panel-bg: #ffffff;        /* cards / painéis brancos para leitura */
    --muted: #6c7788;
    --maxw: 1150px;
    --work-h:140px;
    --work-h-small:64px;
  }

  *{box-sizing:border-box;margin:0;padding:0}
  html,body{height:100%}
  body{
    font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
    background:var(--work-color); /* fundo todo na cor do workshop */
    color:#eaf6ff;
    -webkit-font-smoothing:antialiased;
    -webkit-text-size-adjust:100%;
    line-height:1.5;
  }

  /* esconder cabeçalho GitHub Pages, se presente */
  header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

  /* FAIXA WORKSHOP — topo */
  .workshop-bleed{
    position:fixed; top:0; left:0; width:100vw; height:var(--work-h);
    background:var(--work-color);
    display:flex;align-items:center;justify-content:center; z-index:1400;
    box-shadow:0 14px 36px rgba(0,0,0,0.30);
    transition:transform .32s ease, height .28s ease, box-shadow .28s ease;
    will-change:transform;
  }
  /* classe aplicada no scroll down (esconder) */
  .workshop-bleed.hidden{ transform: translateY(-120%); box-shadow:0 6px 14px rgba(0,0,0,0.18); }

  .workshop-bleed h1{
    font-family:'Playfair Display',serif;color:#fff;font-size:clamp(18px,3.2vw,44px);letter-spacing:.02em;margin:0;
  }

  /* espaço para empurrar conteúdo abaixo da faixa fixa */
  .top-spacer{height:calc(var(--work-h) + 18px); width:100%}

  .container{max-width:var(--maxw);margin:0 auto;padding:18px}

  /* HERO (card branco sobre fundo azul) */
  .hero{
    background:var(--panel-bg);border-radius:12px;padding:42px 28px;margin:12px auto 36px;
    box-shadow:0 30px 80px rgba(0,0,0,0.28);color:var(--work-color);
    max-width:1100px;text-align:center;
  }
  .hero h2{font-family:'Playfair Display',serif;font-size:clamp(28px,5.6vw,56px);margin:0 0 12px;color:var(--work-color)}
  .hero p{color:var(--muted);max-width:860px;margin:0 auto;line-height:1.6}

  /* AS TRÊS NOITES — faixa azul viva full-bleed */
  #noites{
    width:100vw; margin-left:calc(-50vw + 50%); padding:84px 18px 64px;
    background:linear-gradient(180deg,var(--noites-color),#1a8fcf);
    color:#fff; text-align:center;
  }
  #noites .inner{max-width:var(--maxw);margin:0 auto}
  #noites h3{font-family:'Playfair Display',serif;font-size:34px;margin:0 0 28px;color:#fff}
  .noites-grid{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));max-width:var(--maxw);margin:0 auto}
  .noites-grid .card{background:var(--panel-bg);color:#213244;padding:20px;border-radius:12px;box-shadow:0 12px 34px rgba(0,0,0,0.18);text-align:left}
  .noites-grid h4{color:var(--work-color);font-family:'Playfair Display',serif;margin-bottom:8px}

  /* OBJETIVOS — título em faixa menor azul (inline) */
  #objetivos{padding:52px 18px;background:transparent}
  #objetivos .title{display:inline-block;background:var(--work-color);color:#fff;padding:12px 22px;border-radius:6px;font-family:'Playfair Display',serif;font-size:22px;margin-bottom:20px}
  .objetivos-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px;max-width:var(--maxw);margin:18px auto 0}
  .objetivos-grid .item{background:var(--panel-bg);padding:18px;border-radius:12px;box-shadow:0 12px 34px rgba(0,0,0,0.12)}
  .objetivos-grid h4{font-family:'Playfair Display',serif;color:var(--work-color);margin-bottom:8px}

  /* PARA QUEM */
  #paraquem{padding:48px 18px}
  .who-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;max-width:var(--maxw);margin:0 auto}
  .who-box{background:var(--panel-bg);border-radius:12px;padding:16px;box-shadow:0 12px 34px rgba(0,0,0,0.10)}
  .who-box h4{color:var(--work-color);font-family:'Playfair Display',serif;margin-bottom:8px}

  /* MENTOR */
  #mentor{padding:46px 18px}
  .mentor-wrap{max-width:var(--maxw);margin:0 auto;display:flex;gap:20px;align-items:center;flex-wrap:wrap}
  .mentor-photo{width:260px;height:260px;border-radius:12px;overflow:hidden;flex:0 0 260px;box-shadow:0 20px 50px rgba(0,0,0,0.18)}
  .mentor-photo img{width:100%;height:100%;object-fit:cover;display:block}
  .mentor-bio{flex:1;min-width:260px}
  .mentor-bio h3{font-family:'Playfair Display',serif;color:#fff;margin-bottom:8px}
  .mentor-bio p{color:#dbeefb}

  /* FAQ */
  #faq{padding:46px 18px}
  .faq-wrap{max-width:var(--maxw);margin:0 auto}
  .faq-item{background:var(--panel-bg);border-radius:12px;padding:16px;box-shadow:0 12px 30px rgba(0,0,0,0.10);margin-bottom:12px;cursor:pointer}
  .faq-item h4{font-family:'Playfair Display',serif;color:var(--work-color);margin:0}
  .faq-item p{max-height:0;overflow:hidden;transition:max-height .28s ease,padding .28s;color:var(--muted);padding:0}
  .faq-item.open p{max-height:520px;padding-top:12px}

  /* floats: contagem e whatsapp */
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
  .footer-bleed{width:100vw;left:50%;transform:translateX(-50%);position:relative;background:var(--work-color);color:#fff;padding:14px 16px;text-align:center;margin-top:36px}

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

  <!-- TRÊS NOITES (faixa azul viva full-bleed) -->
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
    <section id="objetivos" aria-labelledby="obj-title">
      <div style="text-align:center">
        <div class="title" id="obj-title">Objetivos do Workshop</div>
      </div>
      <div class="objetivos-grid" style="margin-top:18px">
        <div class="item"><h4>Reconhecer o que pesa</h4><p>Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div class="item"><h4>Aprender a soltar</h4><p>Ferramentas práticas para libertar ansiedade, culpa e cobranças.</p></div>
        <div class="item"><h4>Recomeçar com intenção</h4><p>Definir ações e intenções suaves para entrar em 2026 com mais clareza e leveza.</p></div>
      </div>
    </section>

    <!-- PARA QUEM -->
    <section id="paraquem" aria-labelledby="who-title" style="margin-top:28px">
      <h3 id="who-title" style="text-align:center;font-family:'Playfair Display',serif;color:#fff;margin-bottom:12px">Para quem é / Para quem não é</h3>
      <div class="who-grid" style="margin-top:8px">
        <div class="who-box"><h4>Para quem é</h4><ul><li>Pessoas que querem fechar o ano com clareza emocional e leveza.</li><li>Quem busca um processo guiado, humano e prático.</li><li>Quem está disposto(a) a reservar ~1h nas três noites e participar ativamente.</li></ul></div>
        <div class="who-box"><h4>Para quem não é</h4><ul><li>Procura fórmula mágica sem envolvimento.</li><li>Não pretende reservar 1h nas três noites.</li><li>Não quer olhar para emoções para compreender.</li></ul></div>
      </div>
    </section>

    <!-- MENTOR -->
    <section id="mentor" aria-labelledby="mentor-title" style="margin-top:28px">
      <h3 id="mentor-title" style="text-align:center;font-family:'Playfair Display',serif;color:#fff;margin-bottom:12px">Conheça seu mentor</h3>
      <div class="mentor-wrap" style="margin-top:8px">
        <div class="mentor-photo"><img src="Mentor.jpeg" alt="Foto de Evandro Favoretto — mentor do workshop"></div>
        <div class="mentor-bio"><h3>Evandro Favoretto</h3><p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p></div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" aria-labelledby="faq-title" style="margin-top:36px">
      <h3 id="faq-title" style="text-align:center;font-family:'Playfair Display',serif;color:#fff;margin-bottom:12px">Perguntas Frequentes</h3>
      <div class="faq-wrap">
        <div class="faq-item" tabindex="0"><h4>Preciso participar das três noites?</h4><p>Recomendamos acompanhar o ciclo completo, mas é possível participar de noites isoladas. A experiência completa vem com o ciclo inteiro.</p></div>
        <div class="faq-item" tabindex="0"><h4>O que vou vivenciar em cada noite?</h4><p>1ª noite: reconhecimento das feridas e pesos. 2ª noite: práticas de soltura e autocuidado. 3ª noite: ritual de encerramento e definição de intenções.</p></div>
        <div class="faq-item" tabindex="0"><h4>É online e haverá gravação?</h4><p>O evento é online. Gravações podem ser disponibilizadas por tempo limitado — inscreva-se no grupo para receber o link.</p></div>
        <div class="faq-item" tabindex="0"><h4>Como garanto minha vaga?</h4><p>Entrando no grupo de WhatsApp você recebe instruções, links e lembretes antes de cada encontro.</p></div>
        <div class="faq-item" tabindex="0"><h4>Preciso participar ao vivo?</h4><p>Ao vivo a experiência é mais rica; gravações ajudam quem não puder assistir.</p></div>
        <div class="faq-item" tabindex="0"><h4>É cobrado algum valor?</h4><p>Não — o workshop é 100% gratuito.</p></div>
        <div class="faq-item" tabindex="0"><h4>Tenho dúvidas ou preciso de suporte</h4><p>Suporte via grupo do WhatsApp. Envie sua dúvida no grupo e a equipe orienta.</p></div>
      </div>
    </section>

  </div> <!-- /.container -->

  <!-- footer full-bleed -->
  <div class="footer-bleed" role="contentinfo">© 2025 — Todos os direitos reservados a Workshop “Antes de virar o ano. Quero estar em paz comigo mesmo.”</div>

  <!-- floats -->
  <div class="countdown-float" id="countdown" aria-live="polite" style="top:160px">
    <div class="small">Próximo encontro</div>
    <div class="time" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" id="whatsBtn" onclick="openGroup()" style="top:220px" aria-label="Entrar no grupo">Entrar no grupo</button>

<script>
  // WhatsApp
  const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

  // FAQ toggle
  document.querySelectorAll('.faq-item').forEach(item=>{
    item.addEventListener('click', ()=> item.classList.toggle('open'));
    item.addEventListener('keydown', (e)=>{ if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); item.classList.toggle('open'); } });
  });

  // Countdown to 02 Dec 2025 20:00
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

  // floats: seguem rolagem com limite (mantém tamanho)
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
          // se rolou para baixo mais que 8px — esconder
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
    // no toque/gesto rápido também considerar
    window.addEventListener('touchstart', ()=> lastScroll = window.scrollY || 0, {passive:true});
  })();

</script>
</body>
</html>
