
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
<meta name="description" content="Três noites (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  /* ==========================
     Variáveis de tema
     ========================== */
  :root{
    --bg-page: linear-gradient(180deg,#e9f6ff,#fbfdff);
    --deep: #08283f;      /* azul profundo - topbar / rodapé */
    --brand: #0b5ea3;     /* azul marca */
    --brand-2:#0ea3c5;    /* gradiente */
    --accent:#f07b6a;     /* cor de apoio (suave) */
    --card:#ffffff;
    --muted:#6b7280;
    --ink:#062633;
    --glass: rgba(6,38,51,0.04);
    --radius:14px;
    --maxw:1180px;
    --top-h:140px;
    --faq-open:#f4fbff;
  }

  /* reset */
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;background:var(--bg-page);
    color:var(--ink);-webkit-font-smoothing:antialiased;line-height:1.5;
  }

  /* Esconder cabeçalho do GitHub Pages quando presente */
  header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

  /* Topbar fixa (faixa WORKSHOP) */
  .topbar{
    position:fixed;left:0;right:0;top:0;height:var(--top-h);display:flex;align-items:center;justify-content:center;
    background:linear-gradient(180deg,var(--deep),#063043);color:#fff;z-index:2200;box-shadow:0 18px 50px rgba(2,8,23,0.18);
    transition:transform .36s ease,opacity .36s ease;
  }
  .topbar.hidden{transform:translateY(-120%);opacity:0}
  .topbar h1{font-family:'Playfair Display',serif;margin:0;font-size:clamp(20px,2.6vw,36px);letter-spacing:.06em}

  .top-spacer{height:calc(var(--top-h) + 22px)} /* empurra conteúdo para fora da faixa fixa */

  /* Container central */
  .wrap{max-width:var(--maxw);margin:0 auto;padding:28px 20px}

  /* HERO */
  .hero{
    background:linear-gradient(180deg, #fff, #fbfdff);
    border-radius:18px;padding:46px 36px;margin:18px auto 30px;box-shadow:0 30px 80px rgba(2,8,23,0.06);
    display:grid;grid-template-columns:1fr 360px;gap:36px;align-items:center;
  }
  @media(max-width:980px){ .hero{grid-template-columns:1fr;padding:28px} .hero-right{order:3;width:100%} }
  .kicker{display:inline-block;background:linear-gradient(90deg,var(--brand),var(--brand-2));color:#fff;padding:8px 14px;border-radius:999px;font-weight:700;font-size:13px}
  .hero-title{font-family:'Playfair Display',serif;font-size:clamp(34px,6.6vw,64px);line-height:1.02;color:var(--deep);margin:14px 0}
  .hero-sub{color:var(--muted);font-size:16px;max-width:760px}
  .cta-row{margin-top:20px;display:flex;gap:12px;flex-wrap:wrap}
  .btn{border:0;padding:13px 18px;border-radius:12px;font-weight:800;cursor:pointer}
  .btn-primary{background:linear-gradient(90deg,var(--brand),var(--brand-2));color:#fff;box-shadow:0 14px 36px rgba(11,74,116,0.12)}
  .btn-ghost{background:transparent;border:1px solid rgba(6,38,51,0.06);color:var(--muted)}
  .hero-right{background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(6,38,51,0.04);box-shadow:0 18px 40px rgba(2,8,23,0.04)}
  .next-label{font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em}
  .next-time{font-size:22px;font-weight:800;color:var(--brand);margin-top:6px}

  /* problema breve */
  .lead{max-width:920px;margin:8px auto 26px;text-align:center;color:var(--muted);font-size:16px}

  /* =========================
     FAIXA CENTRAL - AS TRÊS NOITES
     - centralizada: conteúdo fechado ao centro
     - fundo azul extenso (mais largo que container)
     ========================= */
  .noites-outer{width:100%;display:flex;justify-content:center;margin:0}
  .noites-bleed{
    background:linear-gradient(180deg,#0b67a5,#0a4b78);
    color:#fff;padding:62px 18px;border-radius:6px;/* borda leve em container */
    width:calc(100% - 40px);max-width:1180px;box-shadow:0 30px 80px rgba(2,8,23,0.12);
    margin:0 20px;
  }
  .noites-title{font-family:'Playfair Display',serif;text-align:center;margin:0 0 26px;font-size:28px;letter-spacing:.02em}
  .noites-grid{display:flex;gap:22px;justify-content:center;align-items:flex-start;flex-wrap:wrap}
  .noite-card{background:var(--card);color:var(--ink);border-radius:12px;padding:20px;min-width:300px;max-width:340px;box-shadow:0 25px 60px rgba(2,8,23,0.08)}
  .noite-card h4{font-size:16px;margin:0 0 8px;color:var(--deep);font-family:'Playfair Display',serif}
  .noite-card p{color:var(--muted);margin:0;line-height:1.6}

  /* BENEFÍCIOS claros (substitui "balõezinhos") */
  .benefs{display:flex;gap:18px;justify-content:space-between;margin:36px 0;flex-wrap:wrap}
  .benef{flex:1 1 240px;background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 50px rgba(2,8,23,0.06)}
  .benef h4{margin:0 0 8px;color:var(--brand)}

  /* OBJETIVOS (faixa leve) */
  .objetivos{max-width:var(--maxw);margin:36px auto;padding:26px;border-radius:12px;background:linear-gradient(180deg,#fff,#fbfdff);box-shadow:0 18px 40px rgba(2,8,23,0.06)}
  .flag{display:inline-block;background:var(--brand);color:#fff;padding:10px 16px;border-radius:999px;font-weight:700;margin-bottom:14px}

  /* PARA QUEM / NÃO É */
  .who{display:grid;grid-template-columns:1fr 1fr;gap:18px;max-width:var(--maxw);margin:26px auto}
  @media(max-width:920px){.who{grid-template-columns:1fr}}

  .bio-mentor{display:flex;gap:22px;align-items:center;max-width:var(--maxw);margin:36px auto;padding:18px;border-radius:12px;background:linear-gradient(180deg,#fff,#fbfdff);box-shadow:0 18px 50px rgba(2,8,23,0.06)}
  .mentor-photo{flex:0 0 220px;border-radius:10px;overflow:hidden;height:220px}
  .mentor-photo img{width:100%;height:100%;object-fit:cover;display:block}
  .mentor-text h3{margin:0;color:var(--brand);font-family:'Playfair Display',serif}

  /* DEPOIMENTOS */
  .tests{max-width:var(--maxw);margin:36px auto;display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
  @media(max-width:980px){.tests{grid-template-columns:1fr}}
  .test{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 40px rgba(2,8,23,0.06)}
  .test cite{display:block;margin-top:12px;color:var(--brand);font-weight:700}

  /* FAQ com destaque quando abre */
  .faq{max-width:var(--maxw);margin:32px auto 80px}
  .faq-item{background:var(--card);padding:18px;border-radius:12px;margin-bottom:12px;box-shadow:0 18px 40px rgba(2,8,23,0.06);cursor:pointer;transition:transform .12s,background .18s}
  .faq-item:hover{transform:translateY(-4px)}
  .faq-item h4{font-family:'Playfair Display',serif;margin:0;color:var(--brand)}
  .faq-item p{color:var(--muted);margin-top:10px;max-height:0;overflow:hidden;transition:max-height .28s ease,padding .28s;padding:0}
  .faq-item.open{background:var(--faq-open)}
  .faq-item.open p{padding-top:10px;max-height:420px}

  /* floats */
  .float-count{position:fixed;left:18px;bottom:18vh;width:180px;background:linear-gradient(180deg,var(--brand-2),#66b8e6);color:#fff;padding:14px;border-radius:12px;box-shadow:0 26px 60px rgba(2,8,23,0.18);z-index:2100}
  .float-whats{position:fixed;right:18px;bottom:14vh;background:#25D366;color:#fff;padding:14px 18px;border-radius:999px;box-shadow:0 26px 60px rgba(2,8,23,0.18);z-index:2100;border:0;font-weight:800;cursor:pointer}

  /* Rodapé faixa larga azul */
  .footer{background:var(--deep);color:#fff;padding:16px 8px;text-align:center;margin-top:40px;position:relative}

  /* Responsividade */
  @media(max-width:980px){
    .hero-title{font-size:38px}
    .noite-card{min-width:100%;max-width:unset}
    .float-count{left:12px;width:150px;bottom:26vh}
    .float-whats{right:12px;bottom:12vh}
  }
  @media(max-width:480px){
    .hero-title{font-size:28px}
    .top-spacer{height:calc(var(--top-h) + 12px)}
  }

  /* acessibilidade: foco visível */
  a:focus, button:focus, .faq-item:focus { outline:4px solid rgba(11,94,163,0.12); outline-offset:3px; border-radius:8px; }
</style>
</head>
<body>

  <!-- TOPO FIXO -->
  <div class="topbar" id="topbar"><h1>WORKSHOP</h1></div>
  <div class="top-spacer" aria-hidden="true"></div>

  <div class="wrap">

    <!-- HERO -->
    <section class="hero" aria-labelledby="hero-title">
      <div>
        <div class="kicker">Três noites • Encontros online</div>
        <h2 id="hero-title" class="hero-title">Antes de virar o ano,<br><strong>quero estar em paz comigo.</strong></h2>
        <p class="hero-sub">Dias 2, 3 e 4 de dezembro • às 20h — três encontros curtos e profundos para reconhecer, soltar e renascer leve para 2026.</p>

        <div class="cta-row" role="group" aria-label="Ações principais">
          <button class="btn btn-primary" onclick="openGroup()">Entrar no grupo — reservar vaga</button>
          <button class="btn btn-ghost" onclick="document.getElementById('noites').scrollIntoView({behavior:'smooth'})">Ver as noites</button>
        </div>
      </div>

      <aside class="hero-right" aria-label="Resumo do evento">
        <div class="next-label">Próximo encontro</div>
        <div class="next-time" id="nextTime">02 Dez • 20h</div>
        <div class="meta" style="margin-top:8px">Duração: 60 — 75 minutos / noite</div>
        <div style="height:10px"></div>
        <div style="font-size:13px;color:var(--muted)">Gratuito — inscrição necessária</div>
      </aside>
    </section>

    <p class="lead">Três noites para encerrar 2025 com leveza: dar nome ao que pesa, aprender a soltar com cuidado e definir intenções suaves para entrar em 2026 com mais paz.</p>
  </div>

  <!-- FAIXA CENTRAL - AS TRÊS NOITES (centralizada no layout) -->
  <div class="noites-outer">
    <section class="noites-bleed" id="noites" aria-labelledby="noites-title">
      <h3 class="noites-title" id="noites-title">As três noites</h3>

      <div class="noites-grid" role="list">
        <article class="noite-card" role="listitem" aria-labelledby="n1">
          <h4 id="n1">🌙 1ª Noite — O peso que ainda carrego</h4>
          <p>Reconhecer mágoas, culpas e cobranças que já não cabem mais. Dar nome é o primeiro passo para libertar.</p>
        </article>

        <article class="noite-card" role="listitem" aria-labelledby="n2">
          <h4 id="n2">💚 2ª Noite — Quando soltar é cuidar</h4>
          <p>Práticas guiadas de soltura e autocuidado — aprender a pausar, confiar e restaurar energia.</p>
        </article>

        <article class="noite-card" role="listitem" aria-labelledby="n3">
          <h4 id="n3">✨ 3ª Noite — O recomeço que nasce da paz</h4>
          <p>Ritual prático para transformar o vivido em sabedoria e escolher intenções para 2026.</p>
        </article>
      </div>
    </section>
  </div>

  <div class="wrap">

    <!-- BENEFÍCIOS -->
    <div class="benefs" aria-hidden="true" style="max-width:var(--maxw);margin:36px auto 0">
      <div class="benefs">
        <div class="benef"><h4>Clareza</h4><p>Entenda o que é hora de deixar para trás e recupere espaço mental.</p></div>
        <div class="benef"><h4>Ferramentas</h4><p>Práticas simples (respiração, presença) para usar no cotidiano.</p></div>
        <div class="benef"><h4>Ritual</h4><p>Fechamentos simbólicos que sustentam o recomeço.</p></div>
        <div class="benef"><h4>Comunidade</h4><p>Grupo de suporte e lembretes antes dos encontros.</p></div>
      </div>
    </div>

    <!-- OBJETIVOS -->
    <section class="objetivos" aria-labelledby="obj-title">
      <span class="flag">Objetivos do Workshop</span>
      <div style="display:flex;gap:18px;flex-wrap:wrap;margin-top:18px">
        <div style="flex:1;min-width:200px"><strong>Reconhecer</strong><p style="color:var(--muted)">Identificar emoções e padrões que atrapalham sua paz.</p></div>
        <div style="flex:1;min-width:200px"><strong>Soltar</strong><p style="color:var(--muted)">Ferramentas práticas para libertar ansiedade e culpa.</p></div>
        <div style="flex:1;min-width:200px"><strong>Recomeçar</strong><p style="color:var(--muted)">Definir ações suaves e intenções para 2026.</p></div>
      </div>
    </section>

    <!-- PARA QUEM -->
    <section class="who" aria-labelledby="who-title" style="margin-top:30px">
      <div style="background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 40px rgba(2,8,23,0.06)">
        <h4 style="color:var(--brand);font-family:'Playfair Display',serif">Para quem é</h4>
        <ul style="color:var(--muted);line-height:1.6">
          <li>Pessoas que querem fechar 2025 com clareza emocional.</li>
          <li>Quem busca um processo guiado, humano e prático.</li>
          <li>Quem reserva ~1h nas três noites e participa ativamente.</li>
        </ul>
      </div>

      <div style="background:var(--card);padding:18px;border-radius:12px;box-shadow:0 18px 40px rgba(2,8,23,0.06)">
        <h4 style="color:var(--brand);font-family:'Playfair Display',serif">Para quem não é</h4>
        <ul style="color:var(--muted);line-height:1.6">
          <li>Quem procura fórmulas mágicas sem envolvimento pessoal.</li>
          <li>Quem quer resultados sem abrir espaço para sentir.</li>
          <li>Quem não pretende reservar 1h nas três noites.</li>
        </ul>
      </div>
    </section>

    <!-- MENTOR -->
    <section class="bio-mentor" aria-labelledby="mentor-title" style="margin-top:36px">
      <div class="mentor-photo" aria-hidden="true">
        <img src="Mentor.jpeg" alt="Foto do mentor Evandro Favoretto">
      </div>
      <div class="mentor-text">
        <h3 id="mentor-title">Evandro Favoretto</h3>
        <p style="color:var(--muted)">Graduado em Gestão Financeira; pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, numerologia, respiração terapêutica e meditação. Empresário, consultor e mentor de vida.</p>
      </div>
    </section>

    <!-- DEPOIMENTOS -->
    <section style="margin-top:36px">
      <h3 style="font-family:'Playfair Display',serif;color:var(--brand);text-align:center">Transformações reais</h3>
      <p style="text-align:center;color:var(--muted);max-width:820px;margin:6px auto 18px">Depoimentos de participantes do Workshop anterior.</p>

      <div class="tests" aria-live="polite">
        <blockquote class="test">
          <p>"Participar me trouxe uma paz prática. Em poucos dias consegui usar as práticas no dia a dia e senti diferença."</p>
          <cite>— Mariana, São Paulo</cite>
        </blockquote>

        <blockquote class="test">
          <p>"O fechamento e o ritual final me ajudaram a transformar um ciclo difícil em aprendizado. Recomendo."</p>
          <cite>— Joana, Curitiba</cite>
        </blockquote>

        <blockquote class="test">
          <p>"Curto, direto e com muita sensibilidade. Senti suporte real do grupo e do mentor."</p>
          <cite>— Fernanda, BH</cite>
        </blockquote>
      </div>
    </section>

    <!-- FAQ -->
    <section class="faq" aria-labelledby="faq-title" style="margin-top:36px">
      <h3 id="faq-title" style="font-family:'Playfair Display',serif;color:var(--brand);text-align:center">Perguntas frequentes</h3>
      <div style="height:12px"></div>

      <div class="faq-item" tabindex="0">
        <h4>Preciso participar das três noites?</h4>
        <p>A recomendação é participar do ciclo completo. Cada encontro prepara o próximo. Se não puder, participe das noites que conseguir.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Como funciona na prática?</h4>
        <p>Encontros ao vivo de 60–75 minutos com orientação, exercícios e um pequeno ritual na última noite. Haverá espaço para partilha.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Haverá gravação?</h4>
        <p>As gravações podem ser disponibilizadas por tempo limitado para inscritos; recomendamos participar ao vivo para maior profundidade.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Qual é o investimento?</h4>
        <p>O workshop é gratuito. A inscrição garante acesso ao grupo e ao link das sessões.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Como faço a inscrição?</h4>
        <p>Clique em “Entrar no grupo” (WhatsApp) — lá você receberá confirmação, lembretes e o link das sessões.</p>
      </div>

      <div class="faq-item" tabindex="0">
        <h4>Tenho dúvidas ou preciso de suporte</h4>
        <p>O canal oficial de suporte é o grupo de WhatsApp. Inscreva-se para receber ajuda antes e durante o evento.</p>
      </div>

    </section>

  </div> <!-- /wrap -->

  <!-- FLOATS -->
  <div class="float-count" id="countdown" aria-live="polite">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div style="font-weight:800;font-size:16px" id="cd-time">--d — --:--:--</div>
    <div style="font-size:12px;margin-top:6px">02 Dez • 20h</div>
  </div>

  <button class="float-whats" id="whats" aria-label="Entrar no grupo" onclick="openGroup()">Entrar no grupo</button>

  <!-- FOOTER -->
  <footer class="footer">© 2025 — Todos os direitos reservados a empresa EA Favoretto LTDA.”</footer>

<script>
  /* Link do grupo (fornecido) */
  const whatsappGroup = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
  function openGroup(){ window.open(whatsappGroup,'_blank'); }

  /* FAQ: toggle + keyboard */
  document.querySelectorAll('.faq-item').forEach(item=>{
    item.addEventListener('click', ()=> item.classList.toggle('open'));
    item.addEventListener('keydown', e=>{
      if(e.key === 'Enter' || e.key === ' '){
        e.preventDefault();
        item.classList.toggle('open');
      }
    });
  });

  /* Countdown para 02 Dez 2025 20:00 */
  const target = new Date(2025,11,2,20,0,0); // mês 11 = Dezembro
  function updateCountdown(){
    const now = new Date();
    let diff = target - now;
    const el = document.getElementById('cd-time');
    if(diff <= 0){ el.textContent = 'Começou — ver grupo'; return; }
    const days = Math.floor(diff / (1000*60*60*24)); diff -= days*(1000*60*60*24);
    const hours = Math.floor(diff / (1000*60*60)); diff -= hours*(1000*60*60);
    const mins = Math.floor(diff / (1000*60)); diff -= mins*(1000*60);
    const secs = Math.floor(diff/1000);
    el.textContent = `${days}d — ${String(hours).padStart(2,'0')}:${String(mins).padStart(2,'0')}:${String(secs).padStart(2,'0')}`;
  }
  updateCountdown(); setInterval(updateCountdown,1000);

  /* Topbar: esconder ao rolar para baixo, mostrar ao subir */
  (function(){
    const bar = document.getElementById('topbar'); let last = window.scrollY||0, ticking=false;
    window.addEventListener('scroll', ()=>{
      if(!ticking){
        window.requestAnimationFrame(()=>{
          const cur = window.scrollY||0;
          const delta = cur - last;
          if(delta > 12 && cur > 120) bar.classList.add('hidden');
          else if(delta < -12 || cur <= 120) bar.classList.remove('hidden');
          last = cur; ticking=false;
        }); ticking=true;
      }
    }, {passive:true});
  })();

  /* Ajuste simples para floats: desloca um pouco para cima quando teclado mobile abre (evitar sobreposição) */
  window.addEventListener('resize', ()=> {
    const fh = window.innerHeight;
    const wc = document.querySelector('.float-whats');
    const fc = document.querySelector('.float-count');
    if(window.innerWidth < 700){
      fc.style.bottom = Math.max(12, Math.round((fh/40))) + 'px';
      wc.style.bottom = Math.max(8, Math.round((fh/34))) + 'px';
    } else {
      fc.style.bottom = '18vh';
      wc.style.bottom = '14vh';
    }
  });

  // Trigger resize to set initial floats
  window.dispatchEvent(new Event('resize'));
</script>
</body>
</html>
