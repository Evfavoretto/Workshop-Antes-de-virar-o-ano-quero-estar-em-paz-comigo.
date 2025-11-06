<html lang="pt-BR">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  /* tenta esconder cabeçalho do GitHub Pages se injetado */
  header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

  :root{
    --blue-dark:#041f3a;
    --blue-deep:#0F4C81;
    --blue-light:#B8E1FF;
    --muted:#5A6571;
    --maxw:1200px;
    --bleed-height:72px; /* altura da faixa WORKSHOP fixa */
  }

  *{box-sizing:border-box;margin:0;padding:0}
  body{
    font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
    -webkit-font-smoothing:antialiased;
    background:linear-gradient(180deg,#EAF4FB,#fff);
    color:#122034;
  }

  /* WORKSHOP full-bleed FIXED no topo */
  .workshop-bleed{
    position:fixed; top:0; left:0; width:100vw; height:var(--bleed-height);
    background:linear-gradient(180deg,var(--blue-dark),var(--blue-deep));
    display:flex;align-items:center;justify-content:center; z-index:1200;
    box-shadow:0 10px 28px rgba(4,31,58,0.16);
  }
  .workshop-bleed h2{color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:clamp(18px,3.6vw,34px);letter-spacing:.02em}

  /* espaço para não ficar under the fixed banner */
  .top-spacer{height:calc(var(--bleed-height) + 10px)} /* garante folga */

  .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}

  /* HERO CARD (quadro branco maior) */
  .hero{
    background:#fff;border-radius:14px;padding:34px;margin:24px auto;box-shadow:0 30px 80px rgba(4,31,58,0.06);
    max-width:1150px; text-align:center;
  }
  .hero h1{font-family:'Playfair Display',serif;font-size:clamp(26px,5.8vw,52px);color:var(--blue-deep);line-height:1.02;margin-bottom:12px}
  .underline{width:220px;height:9px;border-radius:999px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-light));margin:12px auto}
  .hero p{color:var(--muted);max-width:860px;margin:12px auto 0;line-height:1.6}

  /* SECTION: flag full-bleed por trás e título branco na frente */
  section{padding:54px 0;position:relative}
  .flag{
    position:absolute; left:50%; transform:translateX(-50%);
    width:100vw; height:56px; background:var(--blue-dark); top:0; z-index:1;
  }
  .section-title{
    position:relative; z-index:2; margin-top:6px; text-align:center; color:#fff;
    font-family:'Playfair Display',serif; font-size:20px; padding:8px 12px; max-width:var(--maxw); margin-left:auto;margin-right:auto;
  }
  /* garante que o título esteja visível sobre a flag (centralizado) */

  .content-wide{max-width:1150px;margin:28px auto;padding:0 18px}

  .grid-3{display:grid;gap:18px}
  @media(min-width:980px){ .grid-3{grid-template-columns:repeat(3,1fr)} }
  .card{background:#fff;border-radius:12px;padding:18px;box-shadow:0 12px 34px rgba(4,31,58,0.04);border:1px solid rgba(0,0,0,0.04)}
  .card h3{color:var(--blue-deep);font-size:18px}
  .card p{color:var(--muted);line-height:1.6}

  /* OBJECTIVES */
  .objectives{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}

  /* MENTOR */
  .mentor{display:flex;gap:18px;align-items:center;background:#fff;border-radius:12px;padding:18px;box-shadow:0 16px 36px rgba(4,31,58,0.04)}
  .mentor img{width:220px;height:220px;object-fit:cover;border-radius:12px}
  .mentor h3{color:var(--blue-deep)}

  /* FAQ */
  .faq-item{background:#fff;border-radius:12px;padding:16px;box-shadow:0 12px 30px rgba(4,31,58,0.04);margin-bottom:12px;cursor:pointer;border-left:6px solid rgba(15,76,129,0.06)}
  .faq-item h4{font-family:'Playfair Display',serif;color:var(--blue-deep);margin:0}
  .faq-item p{max-height:0;overflow:hidden;transition:max-height .32s ease,padding .32s;color:var(--muted);padding:0}
  .faq-item.open p{max-height:520px;padding-top:10px}

  /* WHO */
  .who-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
  @media(max-width:980px){ .who-grid{grid-template-columns:1fr} }
  .who-box{background:#fff;border-radius:12px;padding:18px;box-shadow:0 10px 28px rgba(4,31,58,0.03)}

  /* FLOATS: tamanho fixo, não escalam, e seguem rolagem controladamente */
  .countdown-float{
    position:fixed; left:14px; width:150px; height:110px; background:linear-gradient(90deg,var(--blue-deep),var(--blue-light)); color:#fff; border-radius:14px;
    padding:12px; box-shadow:0 20px 50px rgba(4,31,58,0.22); z-index:2000; display:flex;flex-direction:column;align-items:center;justify-content:center;font-weight:800; text-align:center;
  }
  .countdown-float .time{font-size:16px}
  .whatsapp-float{
    position:fixed; right:14px; width:160px; height:56px; background:#25D366; color:#fff; border-radius:999px; box-shadow:0 20px 46px rgba(0,0,0,0.18); z-index:2000; display:flex;align-items:center;justify-content:center; font-weight:800; cursor:pointer;
  }

  /* FOOTER full-bleed azul */
  .footer-bleed{width:100vw;left:50%;transform:translateX(-50%);position:relative;background:var(--blue-dark);color:#fff;padding:14px 16px;text-align:center;margin-top:36px}

  /* MOBILE adjustments */
  @media(max-width:980px){
    .hero{padding:20px}
    .flag{height:38px}
    .section-title{margin-top:-28px;font-size:18px}
    .countdown-float{width:140px;height:96px;left:12px}
    .whatsapp-float{right:12px;width:140px;height:48px}
    .mentor{flex-direction:column;align-items:center}
    .mentor img{width:100%;max-width:320px;height:auto}
  }
  @media(max-width:420px){
    .section-title{font-size:16px}
    .countdown-float{width:128px;height:88px}
    .whatsapp-float{width:130px;height:48px}
  }
</style>
</head>
<body>

  <!-- FAIXA WORKSHOP fixada full-bleed no topo -->
  <div class="workshop-bleed" role="banner" aria-hidden="true">
    <h2>WORKSHOP</h2>
  </div>

  <!-- espaçador para empurrar conteúdo -->
  <div class="top-spacer" aria-hidden="true"></div>

  <div class="wrap">
    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <h1 id="hero-title">Antes de virar o ano, quero estar em paz comigo.</h1>
      <div class="underline" aria-hidden="true"></div>
      <p> Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
    </main>

    <!-- AS TRÊS NOITES -->
    <section id="noites" aria-labelledby="noites-title">
      <div class="flag" aria-hidden="true"></div>
      <h2 id="noites-title" class="section-title">As três noites</h2>

      <div class="content-wide grid-3" style="margin-top:18px">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz: mágoas, culpas e cobranças que já não cabem mais. Nomear para começar a libertar.</p></article>
        <article class="card"><h3>💚 2ª Noite — Quando soltar é cuidar</h3><p>Exercícios práticos para soltar o controle, acolher limites e aprender que cuidar também é pausar.</p></article>
        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Ritual de encerramento: transformar o vivido em sabedoria e definir intenções para 2026.</p></article>
      </div>
    </section>

    <!-- OBJETIVOS -->
    <section id="objetivos" aria-labelledby="obj-title">
      <div class="flag" aria-hidden="true"></div>
      <h2 id="obj-title" class="section-title">Objetivos do Workshop</h2>

      <div class="content-wide objectives" style="margin-top:18px">
        <div class="card"><h3>Reconhecer o que pesa</h3><p>Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div class="card"><h3>Aprender a soltar</h3><p>Ferramentas práticas para libertar ansiedade, culpa e cobranças.</p></div>
        <div class="card"><h3>Recomeçar com intenção</h3><p>Definir ações e intenções suaves para entrar em 2026 com mais clareza e leveza.</p></div>
      </div>
    </section>

    <!-- PARA QUEM -->
    <section id="para-quem" aria-labelledby="who-title">
      <div class="flag" aria-hidden="true"></div>
      <h2 id="who-title" class="section-title">Para quem é / Para quem não é</h2>

      <div class="content-wide who-grid" style="margin-top:18px">
        <div class="who-box"><h4>Para quem é</h4>
          <ul>
            <li>Pessoas que querem fechar o ano com clareza emocional e leveza.</li>
            <li>Quem busca um processo guiado, humano e prático.</li>
            <li>Quem está disposto(a) a reservar ~1h nas três noites e participar ativamente.</li>
            <li>Pessoas abertas a práticas de introspecção e rituais de encerramento.</li>
          </ul>
        </div>
        <div class="who-box"><h4>Para quem não é</h4>
          <ul>
            <li>Quem procura fórmulas mágicas sem envolvimento pessoal.</li>
            <li>Quem não pode ou não quer reservar ~1h nas três noites.</li>
            <li>Quem não quer olhar para emoções ou sentir para compreender.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- MENTOR -->
    <section id="mentor" aria-labelledby="mentor-title">
      <div class="flag" aria-hidden="true"></div>
      <h2 id="mentor-title" class="section-title">Conheça seu mentor</h2>

      <div class="content-wide mentor" style="margin-top:18px">
        <img src="Mentor.jpeg" alt="Evandro Favoretto — mentor do workshop">
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
        </div>
      </div>
    </section>

    <!-- FAQ — TODOS os itens (abrir/fechar) -->
    <section id="faq" aria-labelledby="faq-title">
      <div class="flag" aria-hidden="true"></div>
      <h2 id="faq-title" class="section-title">Perguntas Frequentes</h2>

      <div class="content-wide" style="margin-top:18px">
        <div class="faq-item" tabindex="0"><h4>Preciso participar das três noites?</h4><p>Recomendamos acompanhar o ciclo completo, mas é possível participar de noites isoladas. A experiência completa vem com o ciclo inteiro.</p></div>

        <div class="faq-item" tabindex="0"><h4>O que vou vivenciar em cada noite?</h4><p>1ª noite: reconhecimento das feridas e pesos. 2ª noite: práticas de soltura e autocuidado. 3ª noite: ritual de encerramento e definição de intenções.</p></div>

        <div class="faq-item" tabindex="0"><h4>É online e haverá gravação?</h4><p>O evento é online. Gravações podem ser disponibilizadas por tempo limitado — inscreva-se para receber o link.</p></div>

        <div class="faq-item" tabindex="0"><h4>Como garanto minha vaga?</h4><p>Ao entrar no grupo de WhatsApp você receberá instruções, links e lembretes antes de cada encontro.</p></div>

        <div class="faq-item" tabindex="0"><h4>Preciso participar ao vivo?</h4><p>Participar ao vivo é recomendado para vivências e trocas; gravações ajudam quem não puder assistir.</p></div>

        <div class="faq-item" tabindex="0"><h4>É cobrado algum valor?</h4><p>Não — o workshop é 100% gratuito.</p></div>

        <div class="faq-item" tabindex="0"><h4>Tenho dúvidas ou preciso de suporte</h4><p>Suporte via grupo do WhatsApp. Envie sua dúvida no grupo e a equipe irá orientar.</p></div>
      </div>
    </section>

  </div> <!-- .wrap -->

  <!-- footer full-bleed azul forte -->
  <div class="footer-bleed" role="contentinfo">© 2025 — Todos os direitos reservados a Workshop: Antes de virar o ano, quero estar em paz comigo mesmo.”</div>

  <!-- floating countdown + whatsapp (tamanho fixo; seguem rolagem sem alterar tamanho) -->
  <div class="countdown-float" id="countdown" aria-live="polite" style="top:140px">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" id="whatsBtn" onclick="openGroup()" style="top:220px" aria-label="Entrar no grupo">Entrar no grupo</button>

<script>
  // abre grupo
  const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

  // FAQ toggle (click + keyboard)
  document.querySelectorAll('.faq-item').forEach(item=>{
    item.addEventListener('click', ()=> item.classList.toggle('open'));
    item.addEventListener('keydown', (e)=>{ if(e.key==='Enter' || e.key===' ') { e.preventDefault(); item.classList.toggle('open'); } });
  });

  // contagem regressiva (02 Dez 2025 20:00)
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

  // floats: seguem rolagem mas mantêm tamanho (sem escalonamento)
  (function(){
    const cd = document.getElementById('countdown');
    const wbtn = document.getElementById('whatsBtn');
    const startCd = 140, startBtn = 220;
    const speed = 0.14;
    function onScroll(){
      const s = window.scrollY || window.pageYOffset;
      const vh = window.innerHeight || document.documentElement.clientHeight;
      const maxTop = Math.round(vh * 0.78);
      cd.style.top = Math.min(maxTop, Math.max(12, Math.round(startCd + s * speed))) + 'px';
      wbtn.style.top = Math.min(maxTop+40, Math.max(60, Math.round(startBtn + s * speed))) + 'px';
    }
    window.addEventListener('scroll', onScroll, {passive:true});
    window.addEventListener('resize', onScroll, {passive:true});
    onScroll();
  })();
</script>
</body>
</html>
