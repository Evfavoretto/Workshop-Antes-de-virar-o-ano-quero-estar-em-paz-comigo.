
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --accent:#0b4a74;       /* azul principal */
    --accent-2:#147fb2;     /* azul secundário */
    --bg: linear-gradient(180deg,#f6fbff,#eaf6ff);
    --card:#fff;
    --muted:#6b7280;
    --ink:#083047;
    --maxw:1150px;
    --radius:14px;
    --work-h:132px;
    --faq-open:#f0f8ff;     /* fundo da resposta quando aberta */
  }

  *{box-sizing:border-box}
  html,body{height:100%}
  body{margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;background:var(--bg);color:var(--ink);-webkit-font-smoothing:antialiased}

  /* remove header do github (quando tiver) */
  header,.page-header,.site-header,.project-name,.project-tagline{display:none!important;}

  /* Top bar (faixa WORKSHOP) */
  .top-bar{position:fixed;left:0;right:0;top:0;height:var(--work-h);display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,var(--accent),#062e45);color:#fff;z-index:2000;box-shadow:0 12px 40px rgba(0,0,0,0.18);transition:transform .32s ease}
  .top-bar.hidden{transform:translateY(-120%)}
  .top-bar h1{font-family:'Playfair Display',serif;margin:0;font-size:clamp(18px,2.6vw,32px);letter-spacing:.06em}

  .top-spacer{height:calc(var(--work-h) + 18px);}

  .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}

  /* HERO */
  .hero{background:var(--card);border-radius:18px;padding:44px 36px;margin:18px auto 30px;box-shadow:0 30px 80px rgba(2,8,23,0.08);display:flex;gap:28px;align-items:center}
  @media(max-width:960px){.hero{flex-direction:column;padding:28px}}
  .hero-left{flex:1}
  .kicker{display:inline-block;background:linear-gradient(90deg,var(--accent-2),#66b8e6);color:#fff;padding:8px 14px;border-radius:999px;font-weight:700;font-size:13px;margin-bottom:18px}
  .hero-title{font-family:'Playfair Display',serif;font-size:clamp(34px,6.6vw,64px);line-height:1.02;color:var(--accent);margin:8px 0}
  .hero-sub{color:var(--muted);font-size:16px;max-width:780px}
  .hero-ctas{margin-top:20px;display:flex;gap:12px;flex-wrap:wrap}
  .btn{border:0;padding:14px 20px;border-radius:12px;font-weight:700;cursor:pointer}
  .btn-primary{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#fff;box-shadow:0 12px 36px rgba(11,74,116,0.12)}
  .btn-ghost{background:transparent;border:1px solid rgba(8,48,71,0.08);color:var(--muted)}
  .hero-right{width:340px;flex:0 0 340px;background:linear-gradient(180deg,#fff,#fbfdff);border-radius:12px;padding:20px;border:1px solid rgba(8,48,71,0.04)}
  @media(max-width:960px){.hero-right{width:100%}}

  .hero-right .next{font-weight:800;color:var(--accent-2);font-size:24px}
  .meta{color:var(--muted);margin-top:10px;font-weight:700}

  /* problema / solução */
  .problem{max-width:980px;margin:24px auto 12px;text-align:center;color:var(--muted);font-size:16px;line-height:1.6}

  /* FAIXA AZUL - AS TRÊS NOITES (CENTRALIZADA) */
  .noites-section{
    /* full-bleed visual mas conteúdo centralizado */
    width:100%;
    background:linear-gradient(180deg,#0f79b0,#0f6ea8);
    padding:60px 20px;
    display:flex;
    justify-content:center;
  }
  .noites-inner{
    width:100%;
    max-width:1100px;
    text-align:center;
    color:#fff;
  }
  .noites-title{font-family:'Playfair Display',serif;font-size:30px;margin:0 0 26px;color:#fff}
  /* flex centralizado para os cards: 3 em linha, centralizados; no mobile viram em coluna */
  .noites-grid{display:flex;gap:26px;justify-content:center;align-items:flex-start;flex-wrap:wrap}
  .noite-card{background:var(--card);color:var(--ink);border-radius:12px;padding:22px;box-shadow:0 20px 50px rgba(2,8,23,0.08);min-height:150px;width:320px;text-align:left;display:flex;flex-direction:column;justify-content:flex-start}
  .noite-card h4{font-family:'Playfair Display',serif;color:var(--accent-2);margin-bottom:10px}
  @media(max-width:980px){.noite-card{width:100%;max-width:640px}}

  /* BENEFÍCIOS (novo visual: linha clara e direta, sem "balõezinhos" vagos) */
  .benefs-row{max-width:var(--maxw);margin:38px auto;display:flex;gap:18px;justify-content:space-between;align-items:stretch;flex-wrap:wrap}
  .benef-block{flex:1 1 220px;background:var(--card);padding:20px;border-radius:12px;box-shadow:0 18px 48px rgba(2,8,23,0.06);min-width:200px}
  .benef-block h4{margin:0 0 8px;color:var(--accent);font-family:'Playfair Display',serif}
  .benef-block p{margin:0;color:var(--muted);line-height:1.6}

  /* OBJETIVOS */
  .objetivos-wrap{max-width:var(--maxw);margin:52px auto;padding:28px;border-radius:12px;background:linear-gradient(180deg,#fff,#fbfdff);box-shadow:0 30px 80px rgba(2,8,23,0.06)}
  .objetivos-flag{display:inline-block;background:var(--accent);color:#fff;padding:8px 14px;border-radius:999px;font-family:'Playfair Display',serif;font-size:18px;margin-bottom:18px}
  .objetivos-grid{display:grid;gap:18px;grid-template-columns:repeat(3,1fr);margin-top:18px}
  @media(max-width:980px){.objetivos-grid{grid-template-columns:1fr}}

  /* PARA QUEM */
  .who{max-width:var(--maxw);margin:38px auto;display:grid;grid-template-columns:1fr 1fr;gap:18px}
  @media(max-width:900px){.who{grid-template-columns:1fr}}
  .who .box{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06);color:var(--ink)}

  /* MENTOR */
  .mentor{max-width:var(--maxw);margin:48px auto;display:flex;gap:24px;align-items:center;flex-wrap:wrap}
  .mentor-photo{width:320px;height:320px;border-radius:12px;overflow:hidden;flex:0 0 320px;box-shadow:0 30px 80px rgba(2,8,23,0.08)}
  .mentor-photo img{width:100%;height:100%;object-fit:cover;display:block}
  .mentor-bio{flex:1;color:var(--muted)}
  .mentor-bio h3{font-family:'Playfair Display',serif;color:var(--accent);margin-bottom:10px}

  /* DEPOIMENTOS */
  .testimonials{max-width:var(--maxw);margin:48px auto;padding:6px 12px}
  .test-grid{display:grid;gap:18px;grid-template-columns:repeat(3,1fr)}
  @media(max-width:980px){.test-grid{grid-template-columns:1fr}}
  .test-card{background:linear-gradient(180deg,#fff,#fbfdff);padding:22px;border-radius:12px;box-shadow:0 20px 60px rgba(2,8,23,0.06);color:var(--ink)}
  .test-card p{color:var(--muted);line-height:1.5}
  .test-author{margin-top:12px;font-weight:700;color:var(--accent)}

  /* FAQ: destaque visual quando abrir */
  .faq{max-width:var(--maxw);margin:48px auto 80px}
  .faq-item{background:var(--card);padding:18px;border-radius:12px;margin-bottom:12px;box-shadow:0 18px 40px rgba(2,8,23,0.06);cursor:pointer;transition:background .22s,transform .12s}
  .faq-item:hover{transform:translateY(-4px)}
  .faq-item h4{font-family:'Playfair Display',serif;color:var(--accent);margin:0}
  .faq-item p{color:var(--muted);max-height:0;overflow:hidden;transition:max-height .28s ease,padding .28s;padding:0}
  .faq-item.open{background:var(--faq-open)}
  .faq-item.open p{max-height:520px;padding-top:12px}

  /* floats */
  .float-count{position:fixed;left:18px;bottom:18vh;width:170px;background:linear-gradient(180deg,var(--accent-2),#66b8e6);color:#fff;padding:14px;border-radius:14px;box-shadow:0 24px 60px rgba(2,8,23,0.18);z-index:2100}
  .float-whats{position:fixed;right:18px;bottom:14vh;background:#25D366;color:#fff;padding:14px 20px;border-radius:999px;box-shadow:0 24px 60px rgba(2,8,23,0.18);z-index:2100;border:0;font-weight:800;cursor:pointer}

  .footer{width:100vw;left:50%;transform:translateX(-50%);position:relative;background:var(--accent);color:#fff;padding:18px 12px;text-align:center}

  @media(max-width:480px){
    .hero-title{font-size:28px}
    .noite-card{max-width:none;width:100%}
    .benefs-row{flex-direction:column}
    .benef-block{width:100%}
    .float-count{left:10px;width:140px;bottom:22vh}
    .float-whats{right:10px;bottom:10vh}
    .top-spacer{height:calc(var(--work-h) + 10px)}
  }
</style>
</head>
<body>

  <!-- TOPO -->
  <div class="top-bar" id="topBar"><h1>WORKSHOP</h1></div>
  <div class="top-spacer" aria-hidden="true"></div>

  <main>
    <div class="wrap">
      <!-- HERO -->
      <section class="hero" aria-labelledby="hero-title">
        <div class="hero-left">
          <div class="kicker">Três noites • Encontro online</div>
          <h2 id="hero-title" class="hero-title">Antes de virar o ano, <strong>quero estar em paz comigo.</strong></h2>
          <p class="hero-sub">Dias 2, 3 e 4 de dezembro • 20h — três encontros curtos e profundos para reconhecer, soltar e renascer leve para 2026. Práticas guiadas, partilha e um pequeno ritual de encerramento.</p>
          <div class="hero-ctas">
            <button class="btn btn-primary" onclick="openGroup()">Entrar no grupo — reservar vaga</button>
            <a class="btn btn-ghost" href="#noites">Ver as noites</a>
          </div>
        </div>

        <aside class="hero-right" aria-label="Resumo">
          <div style="font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em">Próximo encontro</div>
          <div class="next" id="nextTime">02 Dez • 20h</div>
          <div class="meta">Duração por noite: 60–75 minutos</div>
          <div style="height:8px"></div>
          <div class="meta">Gratuito — inscrição necessária</div>
        </aside>
      </section>
    </div>

    <!-- PROBLEM -->
    <div class="problem">Se você sente que carrega mágoas, culpa ou ansiedade ao olhar para o ano que passou — este workshop é para fechar 2025 com mais leveza. Venha transformar o peso em presença e recomeçar com intenções claras.</div>

    <!-- FAIXA AZUL CENTRALIZADA - AS TRÊS NOITES -->
    <section class="noites-section" id="noites">
      <div class="noites-inner" role="region" aria-labelledby="noites-title">
        <h3 class="noites-title" id="noites-title">As três noites</h3>

        <div class="noites-grid" aria-label="cards das três noites">
          <article class="noite-card" role="article">
            <h4>🌙 1ª Noite — O peso que ainda carrego</h4>
            <p>Reconhecer as mágoas, culpas e cobranças que já não cabem mais. Nomear o que dói é o primeiro passo da libertação.</p>
          </article>

          <article class="noite-card" role="article">
            <h4>💚 2ª Noite — Quando soltar é cuidar</h4>
            <p>Práticas de soltura, respiração e acolhimento — aprender que força também é pausar e confiar no processo.</p>
          </article>

          <article class="noite-card" role="article">
            <h4>✨ 3ª Noite — O recomeço que nasce da paz</h4>
            <p>Ritual de encerramento: transformar o vivido em sabedoria e escolher intenções para 2026.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- BENEFÍCIOS (claro, sem balõezinhos) -->
    <div class="benefs-row" aria-hidden="false">
      <div class="benef-block">
        <h4>Clareza</h4>
        <p>Entenda o que é hora de deixar para trás — práticas para identificar e nomear o que pesa.</p>
      </div>
      <div class="benef-block">
        <h4>Ferramentas</h4>
        <p>Práticas simples e aplicáveis (respiração, presença) para usar no dia a dia e manter a calma.</p>
      </div>
      <div class="benef-block">
        <h4>Ritual</h4>
        <p>Um fechamento simbólico que ajuda a transformar experiências em intenção e ação para 2026.</p>
      </div>
      <div class="benef-block">
        <h4>Comunidade</h4>
        <p>Espaço de suporte no grupo — lembretes, gravações e trocas entre participantes.</p>
      </div>
    </div>

    <!-- OBJETIVOS -->
    <div class="objetivos-wrap" id="objetivos">
      <div style="text-align:center"><span class="objetivos-flag">Objetivos do Workshop</span></div>
      <div class="objetivos-grid">
        <div><strong>Reconhecer o que pesa</strong><p style="color:var(--muted);margin-top:8px">Identificar emoções e padrões que reduzem sua paz.</p></div>
        <div><strong>Aprender a soltar</strong><p style="color:var(--muted);margin-top:8px">Ferramentas práticas para aliviar tensão e culpa.</p></div>
        <div><strong>Recomeçar com intenção</strong><p style="color:var(--muted);margin-top:8px">Definir pequenas ações e intenções para 2026.</p></div>
      </div>
    </div>

    <!-- PARA QUEM -->
    <section class="who" aria-labelledby="who-title">
      <div style="text-align:center;width:100%;grid-column:1/-1;margin-bottom:6px">
        <h3 id="who-title" style="font-family:'Playfair Display',serif;color:var(--accent)">Para quem é / Para quem não é</h3>
      </div>

      <div class="box">
        <div class="box" style="background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06)">
          <h4 style="color:var(--accent);font-family:'Playfair Display',serif">Para quem é</h4>
          <ul style="color:var(--muted);margin-top:8px;line-height:1.6">
            <li>Pessoas que querem fechar 2025 com clareza emocional.</li>
            <li>Quem busca um processo guiado, humano e prático.</li>
            <li>Quem reserva ~1h nas três noites para participar.</li>
          </ul>
        </div>
      </div>

      <div class="box">
        <div class="box" style="background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06)">
          <h4 style="color:var(--accent);font-family:'Playfair Display',serif">Para quem não é</h4>
          <ul style="color:var(--muted);margin-top:8px;line-height:1.6">
            <li>Quem procura soluções instantâneas sem participação.</li>
            <li>Quem não quer reservar tempo para se dedicar.</li>
            <li>Quem não deseja se abrir para sentir e compreender.</li>
          </ul>
        </div>
      </div>

    </section>

    <!-- MENTOR -->
    <section class="mentor" aria-labelledby="mentor-title">
      <div class="mentor-photo"><img src="Mentor.jpeg" alt="Foto do mentor Evandro Favoretto"></div>
      <div class="mentor-bio">
        <h3 id="mentor-title">Evandro Favoretto</h3>
        <p style="color:var(--muted)">Graduado em Gestão Financeira; pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
      </div>
    </section>

    <!-- DEPOIMENTOS -->
    <section class="testimonials" aria-labelledby="test-title">
      <h3 id="test-title" style="font-family:'Playfair Display',serif;color:var(--accent);text-align:center;margin-bottom:8px">Transformações reais</h3>
      <p style="text-align:center;color:var(--muted);max-width:880px;margin:0 auto 18px">Depoimentos de participantes anteriores — substitua por reais quando preferir.</p>

      <div class="test-grid">
        <div class="test-card">
          <p>"Saí das três noites com uma clareza que não esperava. As práticas me ajudaram a entender o que eu carregava e a respirar diferente. Hoje acordo mais leve."</p>
          <div class="test-author">Mariana R., São Paulo</div>
        </div>

        <div class="test-card">
          <p>"O ritual final foi emocionante e prático — eu consegui transformar sentimentos antigos em intenção. Recomendo para quem quer fechar o ano com presença."</p>
          <div class="test-author">Joana M., Curitiba</div>
        </div>

        <div class="test-card">
          <p>"Participar foi um presente: curto, objetivo e muito humano. Saí com ferramentas simples que usei no dia a dia para lidar com ansiedade."</p>
          <div class="test-author">Fernanda L., Belo Horizonte</div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section class="faq" aria-labelledby="faq-title">
      <h3 id="faq-title" style="font-family:'Playfair Display',serif;color:var(--accent);text-align:center">Perguntas Frequentes</h3>
      <div style="height:12px"></div>

      <div class="faq-item" tabindex="0">
        <h4>Preciso participar das três noites?</h4>
        <p>Recomendamos completar o ciclo para a experiência integral, pois cada noite apoia a seguinte. Ainda assim, é possível participar de noites isoladas.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>O que vou vivenciar em cada noite?</h4>
        <p>1ª noite: reconhecimento do que pesa. 2ª noite: práticas de soltura e autocuidado. 3ª noite: ritual de encerramento e definição de intenções.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>É online e haverá gravação?</h4>
        <p>O evento é online. As gravações podem ser disponibilizadas por tempo limitado para inscritos; recomendamos participar ao vivo para melhor experiência.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Como garanto minha vaga?</h4>
        <p>Entre no grupo de WhatsApp através do botão verde; lá enviaremos confirmação, link das sessões e lembretes antes de cada encontro.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Preciso participar ao vivo?</h4>
        <p>Participar ao vivo é recomendado pela interação e práticas em tempo real, mas caso não consiga, buscaremos disponibilizar a gravação.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>É cobrado algum valor?</h4>
        <p>Não — o workshop é 100% gratuito. Pedimos apenas sua presença e abertura para a experiência.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Tenho dúvidas ou preciso de suporte</h4>
        <p>Suporte e dúvidas são atendidos no grupo de WhatsApp. Ao entrar, você terá instruções e um canal para perguntar antes e durante o evento.</p>
      </div>

    </section>

  </main>

  <!-- floats -->
  <div class="float-count" id="countdown" aria-live="polite">
    <div style="font-size:13px;opacity:.95">Próximo encontro</div>
    <div style="font-weight:800;font-size:18px" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="float-whats" id="whatsBtn" aria-label="Entrar no grupo" onclick="openGroup()">Entrar no grupo</button>

  <!-- footer -->
  <footer class="footer">© 2025 — Todos os direitos reservados a Workshop “Antes de virar o ano. Quero estar em paz comigo mesmo.”</footer>

<script>
  // abrir grupo
  const whatsappGroup = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroup,'_blank'); }

  // FAQ acordeão + foco teclado
  document.querySelectorAll('.faq-item').forEach(item=>{
    item.addEventListener('click', ()=> item.classList.toggle('open'));
    item.addEventListener('keydown', e=>{ if(e.key==='Enter'||e.key===' '){ e.preventDefault(); item.classList.toggle('open'); }});
  });

  // countdown para 02 Dez 2025 20:00
  const target = new Date(2025,11,2,20,0,0);
  function updateCountdown(){
    const now = new Date(); let diff = target - now; const el = document.getElementById('cd-time');
    if(diff <= 0){ el.textContent = 'Começou — veja no grupo'; return; }
    const days = Math.floor(diff / (1000*60*60*24)); diff -= days*(1000*60*60*24);
    const hours = Math.floor(diff / (1000*60*60)); diff -= hours*(1000*60*60);
    const mins = Math.floor(diff / (1000*60)); diff -= mins*(1000*60);
    const secs = Math.floor(diff/1000);
    el.textContent = `${days}d — ${String(hours).padStart(2,'0')}:${String(mins).padStart(2,'0')}:${String(secs).padStart(2,'0')}`;
  }
  updateCountdown(); setInterval(updateCountdown,1000);

  // top-bar hide on scroll (down hides, up shows)
  (function(){
    const bar = document.getElementById('topBar'); let last = window.scrollY||0, ticking=false;
    window.addEventListener('scroll', ()=>{
      if(!ticking){
        window.requestAnimationFrame(()=>{
          const cur = window.scrollY||0;
          const delta = cur - last;
          if(delta > 8 && cur > 80) bar.classList.add('hidden');
          else if(delta < -8 || cur <= 80) bar.classList.remove('hidden');
          last = cur; ticking=false;
        }); ticking=true;
      }
    }, {passive:true});
  })();
</script>
</body>
</html>
