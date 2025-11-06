
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de 2026." />
<meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
<meta property="og:description" content="Três noites para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
<meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
<meta name="twitter:card" content="summary_large_image" />
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --accent:#0b4a74;        /* cor principal - ajuste para clarear/escurecer */
    --accent-2:#0f79b0;     /* cor secundária */
    --bg:#eaf6ff;           /* textura clara usada atrás (sutileza) */
    --card:#ffffff;
    --muted:#6b7280;
    --ink:#083047;
    --radius:14px;
    --maxw:1150px;
    --work-h:132px;
    --shadow-lg: 0 30px 80px rgba(2,8,23,0.14);
    --glass: rgba(255,255,255,0.7);
  }

  /* reset */
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
    background:linear-gradient(180deg,#f6fbff, #e8f6ff);
    color:var(--ink);-webkit-font-smoothing:antialiased;
    -webkit-text-size-adjust:100%;
    line-height:1.5;
  }

  /* escondendo título GitHub (quando aparece no topo) */
  header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

  /* ====== TOP FAIXA WORKSHOP (fixa e elegante) ====== */
  .top-bar{
    position:fixed; left:0; right:0; top:0; height:var(--work-h); display:flex;align-items:center;justify-content:center;
    background:linear-gradient(180deg,var(--accent), #062e45); color:#fff; z-index:2000;
    box-shadow:0 10px 40px rgba(2,8,23,0.22); transition:transform .34s ease,opacity .24s;
  }
  .top-bar.hidden{ transform: translateY(-120%); opacity:0; }
  .top-bar h1{ font-family:'Playfair Display',serif; letter-spacing:.08em; font-size:clamp(20px,2.8vw,34px); margin:0; font-weight:700;}

  /* spacer para empurrar conteúdo sob o topo fixo */
  .top-spacer{height:calc(var(--work-h) + 18px);}

  /* container central */
  .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;}

  /* ===== HERO ===== */
  .hero{
    background:var(--card); border-radius:18px; padding:48px 36px; margin:18px auto; box-shadow:var(--shadow-lg);
    display:flex; gap:36px; align-items:center; position:relative; overflow:visible;
  }
  @media(max-width:960px){ .hero{flex-direction:column;padding:32px 20px} }

  .hero-left{flex:1}
  .kicker{display:inline-block;background:linear-gradient(90deg,var(--accent-2),#66b8e6);color:#fff;padding:8px 14px;border-radius:999px;font-weight:700;font-size:13px;margin-bottom:18px}

  .hero-title{
    font-family:'Playfair Display',serif;font-size:clamp(34px,6.6vw,68px);line-height:1.02;margin:6px 0 20px;color:var(--accent);
    letter-spacing:-0.01em;
  }
  .hero-sub{color:var(--muted); font-size:16px; max-width:820px}

  .hero-ctas{margin-top:20px;display:flex;gap:12px;flex-wrap:wrap}
  .btn{border:0;padding:14px 20px;border-radius:12px;font-weight:700;cursor:pointer}
  .btn-primary{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#fff;box-shadow:0 12px 36px rgba(11,74,116,0.18)}
  .btn-ghost{background:transparent;border:1px solid rgba(8,48,71,0.08);color:var(--muted)}

  .hero-right{width:360px;flex:0 0 360px;background:linear-gradient(180deg, rgba(255,255,255,0.98), var(--card)); border-radius:12px;padding:22px;border:1px solid rgba(6,46,69,0.04)}
  @media(max-width:960px){ .hero-right{width:100%;flex:unset} }

  .hero-right .next{font-weight:800;color:var(--accent-2);font-size:28px}
  .meta{color:var(--muted);font-weight:700;margin-top:8px}

  /* ===== SEÇÃO problema → solução pequena ===== */
  .problem{
    max-width:980px;margin:34px auto 8px;text-align:center;color:var(--muted);
    font-size:16px;line-height:1.7;
  }

  /* ===== TRÊS NOITES — FAIXA COMPACTA ===== */
  .noites-bleed{width:100%; margin-left:calc(-50vw + 50%); background:linear-gradient(180deg,var(--accent-2), #0b86c3); padding:44px 24px; color:#fff}
  .noites-inner{max-width:var(--maxw);margin:0 auto}
  .noites-title{font-family:'Playfair Display',serif;font-size:26px;margin:0 0 18px;text-align:center}
  .noites-grid{display:grid;gap:18px;grid-template-columns:repeat(3,1fr); max-width:1100px;margin:0 auto}
  @media(max-width:980px){ .noites-grid{grid-template-columns:1fr} }

  .noite-card{background:var(--card);color:var(--ink);border-radius:12px;padding:22px;box-shadow:0 20px 50px rgba(2,8,23,0.08);min-height:140px}
  .noite-card h4{font-family:'Playfair Display',serif;color:var(--accent);margin-bottom:8px}

  /* ===== BENEFÍCIOS (cards) ===== */
  .benefs{max-width:1100px;margin:44px auto 10px;display:grid;gap:18px;grid-template-columns:repeat(4,1fr)}
  @media(max-width:1100px){ .benefs{grid-template-columns:repeat(2,1fr)} }
  @media(max-width:640px){ .benefs{grid-template-columns:1fr} }
  .benef{background:var(--card);padding:18px;border-radius:12px;color:var(--ink);box-shadow:0 18px 42px rgba(2,8,23,0.06)}

  /* ===== OBJETIVOS — faixa discreta atrás do título ===== */
  .objetivos-wrap{max-width:var(--maxw);margin:52px auto;padding:28px;border-radius:12px; background:linear-gradient(180deg, rgba(255,255,255,0.96), rgba(255,255,255,0.98)); box-shadow:0 30px 80px rgba(2,8,23,0.06)}
  .objetivos-flag{display:inline-block;background:var(--accent);color:#fff;padding:10px 16px;border-radius:999px;font-family:'Playfair Display',serif;font-size:18px;margin-bottom:18px}
  .objetivos-grid{display:grid;gap:18px;grid-template-columns:repeat(3,1fr);margin-top:18px}
  @media(max-width:980px){ .objetivos-grid{grid-template-columns:1fr} }

  /* ===== PARA QUEM — 2 colunas ===== */
  .who{max-width:var(--maxw);margin:38px auto;display:grid;grid-template-columns:1fr 1fr;gap:18px}
  @media(max-width:900px){ .who{grid-template-columns:1fr} }
  .who .box{background:var(--card);padding:20px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06);color:var(--ink)}

  /* ===== MENTOR ===== */
  .mentor{max-width:var(--maxw);margin:48px auto;display:flex;gap:24px;align-items:center;flex-wrap:wrap}
  .mentor-photo{width:320px;height:320px;border-radius:12px;overflow:hidden;flex:0 0 320px;box-shadow:0 30px 80px rgba(2,8,23,0.08)}
  .mentor-photo img{width:100%;height:100%;object-fit:cover;display:block}
  .mentor-bio{flex:1;color:var(--muted)}
  .mentor-bio h3{font-family:'Playfair Display',serif;color:var(--accent);margin-bottom:10px}

  /* ===== FAQ estilo acordeão ===== */
  .faq{max-width:var(--maxw);margin:48px auto 80px}
  .faq-item{background:var(--card);padding:18px;border-radius:12px;margin-bottom:12px;box-shadow:0 18px 40px rgba(2,8,23,0.06);cursor:pointer}
  .faq-item h4{font-family:'Playfair Display',serif;color:var(--accent);margin:0}
  .faq-item p{color:var(--muted);max-height:0;overflow:hidden;transition:max-height .28s ease,padding .28s;padding:0}
  .faq-item.open p{max-height:520px;padding-top:10px}

  /* ===== floats: contagem e WhatsApp ===== */
  .float-count{position:fixed; left:18px; bottom:18vh; width:170px;background:linear-gradient(180deg,var(--accent-2), #66b8e6); color:#fff;padding:14px;border-radius:14px;box-shadow:0 24px 60px rgba(2,8,23,0.18);z-index:2100}
  .float-whats{position:fixed; right:18px; bottom:14vh; background:#25D366;color:#fff;padding:14px 20px;border-radius:999px;box-shadow:0 24px 60px rgba(2,8,23,0.18);z-index:2100;border:0;font-weight:800;cursor:pointer}

  /* ===== footer full-bleed ===== */
  .footer{width:100vw;left:50%;transform:translateX(-50%);position:relative;background:var(--accent);color:#fff;padding:18px 12px;text-align:center}

  /* acessibilidade: foco */
  a:focus,button:focus,input:focus{outline:3px solid rgba(11,74,116,0.14);outline-offset:3px;border-radius:8px}

  /* responsividade fina */
  @media(max-width:980px){
    .hero-right{width:100%}
    .hero{padding:28px}
    .mentor-photo{width:100%;height:360px;flex-basis:100%}
  }
  @media(max-width:480px){
    .hero-title{font-size:34px}
    .float-count{left:10px;bottom:18vh;width:140px}
    .float-whats{right:10px;bottom:8vh;padding:12px 16px}
  }
</style>
</head>
<body>

  <!-- FAIXA FIXA -->
  <div class="top-bar" id="topBar" aria-hidden="true"><h1>WORKSHOP</h1></div>
  <div class="top-spacer" aria-hidden="true"></div>

  <main>

    <div class="wrap">
      <!-- HERO -->
      <section class="hero" aria-labelledby="hero-title">
        <div class="hero-left">
          <div class="kicker">Três noites • Encontro online</div>
          <h2 id="hero-title" class="hero-title">Antes de virar o ano, <strong>quero estar em paz comigo.</strong></h2>
          <p class="hero-sub">Dias 2, 3 e 4 de dezembro • 20h — três noites práticas e afetivas para reconhecer o que pesa, aprender a soltar com cuidado e entrar em 2026 com mais leveza. Um processo curto, humano e direto ao ponto.</p>

          <div class="hero-ctas">
            <button class="btn btn-primary" onclick="openGroup()">Entrar no grupo — reservar vaga</button>
            <a class="btn btn-ghost" href="#noites">Ver as noites</a>
          </div>
        </div>

        <aside class="hero-right" aria-label="Resumo do evento">
          <div style="font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em">Próximo encontro</div>
          <div class="next" id="nextTime">02 Dez • 20h</div>
          <div style="height:10px"></div>
          <div class="meta">Duração por noite: 60–75 minutos</div>
          <div style="height:12px"></div>
          <div class="meta">Gratuito — inscrição necessária</div>
        </aside>
      </section>

    </div>

    <!-- PROBLEMA → SOLUÇÃO (curto) -->
    <div class="problem" role="region" aria-live="polite">
      Muitas pessoas chegam ao fim do ano cansadas, com mágoas e cobranças que ocupam a cabeça e o corpo. Este workshop é um espaço compassivo para **dar nome ao que pesa**, aprender práticas simples de soltura e terminar o ano com um ritual que abre caminho para um recomeço mais leve.
    </div>

    <!-- TRÊS NOITES — faixa colorida -->
    <section class="noites-bleed" id="noites" aria-labelledby="noites-title">
      <div class="noites-inner">
        <h3 id="noites-title" class="noites-title">As três noites</h3>
        <div class="noites-grid" role="list">
          <article class="noite-card" role="listitem">
            <h4>🌙 1ª Noite — O peso que ainda carrego</h4>
            <p>Reconhecer mágoas, culpas e cobranças; nomear o que dói como primeiro passo para libertar.</p>
          </article>

          <article class="noite-card" role="listitem">
            <h4>💚 2ª Noite — Quando soltar é cuidar</h4>
            <p>Práticas de soltura, respiração e acolhimento: soltar controle e cuidar-se com verdade.</p>
          </article>

          <article class="noite-card" role="listitem">
            <h4>✨ 3ª Noite — O recomeço que nasce da paz</h4>
            <p>Ritual de encerramento para transformar experiência em sabedoria e plantar intenções para 2026.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- BENEFÍCIOS -->
    <div class="benefs" aria-hidden="false">
      <div class="benef">Clareza emocional — Nomeie e entenda o que pesa.</div>
      <div class="benef">Ferramentas práticas — Técnicas simples para aplicar no dia a dia.</div>
      <div class="benef">Ritual de fechamento — Um gesto simbólico para recomeçar.</div>
      <div class="benef">Comunidade — Apoio e continuidade via grupo.</div>
    </div>

    <!-- OBJETIVOS -->
    <div class="objetivos-wrap" id="objetivos" aria-labelledby="obj-title">
      <div style="text-align:center"><span class="objetivos-flag" id="obj-title">Objetivos do Workshop</span></div>
      <div class="objetivos-grid">
        <div><strong>Reconhecer o que pesa</strong><p style="color:var(--muted);margin-top:8px">Identificar emoções e padrões que reduzem sua paz.</p></div>
        <div><strong>Aprender a soltar</strong><p style="color:var(--muted);margin-top:8px">Ferramentas de respiração e presença para aliviar ansiedade e culpa.</p></div>
        <div><strong>Recomeçar com intenção</strong><p style="color:var(--muted);margin-top:8px">Pequenas ações e um ritual para entrar em 2026 com clareza.</p></div>
      </div>
    </div>

    <!-- PARA QUEM -->
    <section class="who" aria-labelledby="who-title">
      <div style="text-align:center;width:100%;grid-column:1/-1;margin-bottom:6px">
        <h3 id="who-title" style="color:var(--accent);font-family:'Playfair Display',serif">Para quem é / Para quem não é</h3>
      </div>

      <div class="box">
        <div class="box" style="background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06)">
          <h4 style="color:var(--accent);font-family:'Playfair Display',serif">Para quem é</h4>
          <ul style="color:var(--muted);margin-top:8px;line-height:1.6">
            <li>Pessoas que querem encerrar 2025 com mais leveza.</li>
            <li>Quem aceita olhar e transformar emoções com orientação.</li>
            <li>Quem reserva ~1h nas três noites e participa ativamente.</li>
          </ul>
        </div>
      </div>

      <div class="box">
        <div class="box" style="background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06)">
          <h4 style="color:var(--accent);font-family:'Playfair Display',serif">Para quem não é</h4>
          <ul style="color:var(--muted);margin-top:8px;line-height:1.6">
            <li>Quem espera fórmulas instantâneas sem participação pessoal.</li>
            <li>Quem não quer reservar tempo para praticar.</li>
            <li>Quem não deseja se abrir para sentir e compreender.</li>
          </ul>
        </div>
      </div>

    </section>

    <!-- MENTOR -->
    <section class="mentor" aria-labelledby="mentor-title">
      <div class="mentor-photo" aria-hidden="false"><img src="Mentor.jpeg" alt="Evandro Favoretto — mentor do workshop"></div>
      <div class="mentor-bio">
        <h3 id="mentor-title">Evandro Favoretto</h3>
        <p>Graduado em Gestão Financeira; pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, Numerologia, Respiração Terapêutica e Meditação. Empresário, consultor e mentor de vida. <strong>Transformações reais e práticas.</strong></p>
      </div>
    </section>

    <!-- PROVAS (espaço para depoimentos) -->
    <section style="max-width:var(--maxw);margin:34px auto">
      <h3 style="font-family:'Playfair Display',serif;color:var(--accent);text-align:center">Transformações reais</h3>
      <p style="text-align:center;color:var(--muted);max-width:820px;margin:10px auto">Depoimentos de participantes anteriores — você poderá colar os prints ou textos aqui. (Removido conforme solicitação anterior; espaço reservado.)</p>
      <!-- Place testimonials here later -->
    </section>

    <!-- FAQ -->
    <section class="faq" aria-labelledby="faq-title">
      <h3 id="faq-title" style="font-family:'Playfair Display',serif;color:var(--accent);text-align:center;margin-bottom:12px">Perguntas Frequentes</h3>
      <div class="faq-item" tabindex="0"><h4>Preciso participar das três noites?</h4><p>Recomendamos o ciclo completo para a experiência inteira, mas é possível participar de noites isoladas.</p></div>
      <div class="faq-item" tabindex="0"><h4>É online? Haverá gravação?</h4><p>Sim, é online. Gravações podem ser disponibilizadas por tempo limitado para inscritos.</p></div>
      <div class="faq-item" tabindex="0"><h4>Como faço a inscrição?</h4><p>Entre no grupo de WhatsApp (botão verde) — lá enviamos confirmação, links e lembretes.</p></div>
      <div class="faq-item" tabindex="0"><h4>Tem custo?</h4><p>Não — o workshop é 100% gratuito.</p></div>
      <div class="faq-item" tabindex="0"><h4>Preciso de suporte?</h4><p>Suporte via grupo do WhatsApp. Pergunte por lá e a equipe ajuda.</p></div>
    </section>

  </main>

  <!-- floats -->
  <div class="float-count" id="countdown" aria-live="polite">
    <div style="font-size:13px;opacity:.95">Próximo encontro</div>
    <div style="font-weight:800;font-size:18px" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="float-whats" id="whatsBtn" aria-label="Entrar no grupo" onclick="openGroup()">Entrar no grupo</button>

  <!-- footer full-bleed -->
  <footer class="footer" role="contentinfo">
    © 2025 — Todos os direitos reservados a Workshop “Antes de virar o ano. Quero estar em paz comigo mesmo.”
  </footer>

<script>
  // link do grupo
  const whatsappGroup = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroup,'_blank'); }

  // FAQ toggle
  document.querySelectorAll('.faq-item').forEach(i=>{
    i.addEventListener('click', ()=> i.classList.toggle('open'));
    i.addEventListener('keydown', e=>{ if(e.key==='Enter' || e.key===' ') { e.preventDefault(); i.classList.toggle('open'); } });
  });

  // countdown para 02 Dez 2025 20:00
  const target = new Date(2025,11,2,20,0,0);
  function update(){
    const now = new Date(); let diff = target - now;
    const el = document.getElementById('cd-time');
    if(diff <= 0){ el.textContent = 'Começou — veja no grupo'; return; }
    const d = Math.floor(diff / (1000*60*60*24)); diff -= d*(1000*60*60*24);
    const h = Math.floor(diff / (1000*60*60)); diff -= h*(1000*60*60);
    const m = Math.floor(diff / (1000*60)); diff -= m*(1000*60);
    const s = Math.floor(diff/1000);
    el.textContent = `${d}d — ${String(h).padStart(2,'0')}:${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}`;
  }
  update(); setInterval(update,1000);

  // top-bar auto-hide on scroll (down hides, up shows)
  (function(){
    const bar = document.getElementById('topBar');
    let last = window.scrollY||0, ticking=false;
    window.addEventListener('scroll', ()=>{
      if(!ticking){
        window.requestAnimationFrame(()=>{
          const cur = window.scrollY||0, delta = cur - last;
          if(delta > 8 && cur > 80) bar.classList.add('hidden');
          else if(delta < -8 || cur <= 80) bar.classList.remove('hidden');
          last = cur; ticking=false;
        });
        ticking=true;
      }
    },{passive:true});
  })();

  // small improvement: open group on primary CTA too
  document.querySelectorAll('.btn-primary').forEach(b=>b.addEventListener('click', openGroup));
</script>
</body>
</html>
