
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover" />
  <title>Antes de virar o ano, quero estar em paz comigo</title>
  <meta name="description" content="Três noites para reconhecer, soltar e recomeçar — preparando 2026 com leveza e clareza emocional." />
  <!-- Open Graph -->
  <meta property="og:title" content="Antes de virar o ano, quero estar em paz comigo"/>
  <meta property="og:description" content="Três noites para reconhecer, soltar e recomeçar — preparando 2026 com leveza e clareza emocional."/>
  <meta property="og:image" content="WhatsApp Image 2025-11-10 at 09.08.40.jpeg"/>

  <style>
    /* ===== Variáveis e reset ===== */
    :root{
      --green-900:#0c4d1f;
      --green-800:#0a3c16;
      --green-soft:#e6f3ea;
      --gold-500:#c6a75d;
      --yellow-canary:#ffeb3b;
      --stone-200:#e7e7e7;
      --red-700:#c62828;
      --shadow:0 10px 28px rgba(0,0,0,.14);
      --bg:#eaf5ec;
      --ink:#0b0b0b;
      --glass: rgba(255,255,255,0.06);
      --max-w:1120px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;
      color:var(--ink);
      background:var(--bg);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      -webkit-text-size-adjust:100%;
      line-height:1.5;
    }
    img{max-width:100%;display:block}
    a{color:inherit;text-decoration:none}

    /* Esconder possíveis cabeçalhos do GitHub Pages (forçar o topo verde) */
    header, .page-header, .site-header, .project-name, .project-tagline, .topbar {
      display: none !important;
    }

    .container{max-width:var(--max-w);margin:0 auto;padding:0 20px}
    section{padding:56px 20px}

    /* ===== HERO (banner com overlay verde) ===== */
    .hero {
      position:relative;
      min-height:62vh;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:#fff;
      overflow:hidden;
      padding-top: calc(32px + env(safe-area-inset-top)); /* evita corte em iOS */
    }

    /* imagem de fundo — manter no topo visual sem faixa branca */
    .hero .bg {
      position:absolute;
      inset:0;
      background-image: url('WhatsApp Image 2025-11-10 at 09.08.40.jpeg');
      background-size:cover;
      background-position:center;
      z-index:0;
      transform:scale(1.03);
    }
    /* sobreposição verde para garantir leitura */
    .hero::before{
      content:"";
      position:absolute;inset:0;
      background: linear-gradient(180deg, rgba(6,41,15,0.62), rgba(10,60,22,0.72));
      z-index:1;
    }

    .hero-inner{
      position:relative;
      z-index:2;
      max-width:980px;
      padding:40px 18px;
    }
    .hero h1{
      font-size:clamp(26px,6vw,56px);
      font-weight:900;
      margin-bottom:12px;
      line-height:1.02;
      letter-spacing:0.2px;
    }
    .hero p.lead{
      font-size:clamp(15px,2.4vw,18px);
      color:rgba(255,255,255,0.95);
      margin-bottom:18px;
      font-weight:600;
    }
    .hero .kicker{color:rgba(232,247,239,0.92);margin-bottom:18px}

    .hero .actions{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
    .btn{display:inline-block;border-radius:999px;padding:12px 24px;font-weight:800;cursor:pointer;transition:transform .18s,filter .18s;font-size:15px}
    .btn-primary{background:var(--yellow-canary);color:#111;box-shadow:0 10px 28px rgba(0,0,0,.18)}
    .btn-ghost{background:transparent;border:2px solid rgba(255,255,255,.18);color:#fff;padding:10px 20px}
    .btn-primary:hover{transform:translateY(-3px)}
    .btn-ghost:hover{background:rgba(255,255,255,.06)}

    /* ===== Trustbar ===== */
    .trustbar{background:#fff;padding:14px 0;border-top:1px solid var(--stone-200);border-bottom:1px solid var(--stone-200)}
    .trust{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:10px;align-items:center;text-align:center;padding:6px 18px}
    .trust-item{background:#f8fbf9;border:1px solid var(--stone-200);border-radius:999px;padding:10px 14px;font-weight:700;color:var(--green-900);font-size:15px}

    /* ===== As 3 noites ===== */
    .title{font-size:34px;text-align:center;margin:12px 0 20px;font-weight:900;color:var(--ink)}
    .nights{display:grid;gap:18px;grid-template-columns:1fr}
    @media(min-width:880px){ .nights{grid-template-columns:repeat(3,1fr)} }
    .night{border-radius:14px;box-shadow:var(--shadow);padding:20px;background:#fff;border:1px solid var(--stone-200)}
    .night h3{color:var(--green-900);margin-bottom:8px;font-size:18px}
    .night p{color:#333;font-size:15px;line-height:1.6}

    /* ===== Como funciona ===== */
    #como-funciona .steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
    #como-funciona .step{background:#fff;border:1px solid var(--stone-200);border-radius:14px;box-shadow:var(--shadow);padding:16px;text-align:center}
    #como-funciona .num{width:40px;height:40px;border-radius:50%;background:var(--green-900);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:900;margin:0 auto 8px}

    /* ===== Depoimentos ===== */
    .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .depo{background:#fff;border:1px solid var(--stone-200);border-radius:14px;box-shadow:var(--shadow);padding:18px;position:relative;font-size:15px}
    .depo:before{content:'\201C';position:absolute;top:-10px;left:12px;font-size:36px;color:var(--gold-500);opacity:.28}
    .depo p{margin:8px 0 12px;font-style:italic;color:#333}
    .depo small{display:block;color:#444;font-weight:700;text-align:right}

    /* ===== Investimento ===== */
    #investimento{background:var(--green-soft);text-align:center;padding:48px 20px}
    #investimento h2{font-size:28px;color:var(--red-700);margin-bottom:12px;font-weight:900}
    .price-wrap{display:grid;gap:8px;max-width:720px;margin:0 auto}
    .price{font-size:32px;color:var(--red-700);font-weight:900}
    .price .old{display:block;text-decoration:line-through;color:var(--green-900);font-size:16px;font-weight:900}

    /* ===== Garantia ===== */
    #garantia .guarantee-card{background:#fff;border:1px solid var(--stone-200);border-radius:14px;box-shadow:var(--shadow);padding:20px;max-width:880px;margin:0 auto;text-align:center}
    #garantia h3{color:var(--green-900);margin-bottom:8px}
    #garantia small{display:block;margin-top:8px;color:#444;font-size:14px}

    /* ===== FAQ ===== */
    #faq{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;padding-top:48px;padding-bottom:48px}
    #faq .title{color:#fff}
    .faq{max-width:900px;margin:0 auto;display:flex;flex-direction:column;gap:12px}
    .faq-item{border-radius:12px;overflow:hidden}
    .faq-q{width:100%;text-align:left;background:#fff;padding:14px 16px;font-weight:900;font-size:16px;cursor:pointer;display:flex;align-items:center;justify-content:space-between;color:var(--green-900);border:1px solid rgba(255,255,255,.12)}
    .faq-q:hover{background:#fffde7}
    .faq-a{display:none;padding:12px 16px;color:#222;background:#fff;font-size:15px;line-height:1.6}
    .faq-item.active .faq-a{display:block}
    .faq-item.active .faq-q::after{transform:rotate(90deg)}

    /* ===== Bio / Mentor ===== */
    .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:14px;box-shadow:var(--shadow);padding:22px;text-align:center}
    .bio h3{font-size:22px;margin-bottom:6px}
    .mentor-photo{max-width:140px;border-radius:50%;margin:12px auto;display:block;box-shadow:0 6px 20px rgba(0,0,0,.25);object-fit:cover}

    /* ===== CTA final e Rodapé ===== */
    .final-buttons{margin-top:18px;text-align:center;display:flex;flex-direction:column;gap:10px;align-items:center}
    @media(min-width:680px){.final-buttons{flex-direction:row;justify-content:center}}
    .footer{background:var(--green-800);color: #e6f3ea;text-align:center;padding:22px 20px;font-size:14px}
    .footer a{color:var(--yellow-canary);text-decoration:none}

    /* ===== WhatsApp flutuante ===== */
    .whats-float{
      position:fixed; right:18px; bottom:18px; z-index:9999;
      width:60px; height:60px; border-radius:50%; background:#25D366; display:flex; align-items:center; justify-content:center; box-shadow:0 12px 28px rgba(0,0,0,.18);
    }
    .whats-float svg{width:30px;height:30px;fill:#fff}

    /* Ajustes finos de responsividade: menos padding no mobile */
    @media(max-width:480px){
      section{padding:36px 14px}
      .hero{padding-top: calc(20px + env(safe-area-inset-top)); min-height:58vh}
      .hero-inner{padding:22px}
      .hero h1{font-size:22px}
      .trust-item{font-size:13px;padding:8px}
      .mentor-photo{max-width:120px}
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <header class="hero" role="banner" aria-label="Hero — Antes de virar o ano, quero estar em paz comigo">
    <div class="bg" aria-hidden="true"></div>
    <div class="hero-inner container">
      <h1>Antes de virar o ano, quero estar em paz comigo</h1>
      <p class="lead">Três noites de vivência para reconhecer, soltar e recomeçar — preparando 2026 com leveza e clareza emocional.</p>
      <div class="kicker">Encontros ao vivo com práticas guiadas, escrita reflexiva e um ritual de recomeço.</div>

      <div class="actions" style="margin-top:18px;">
        <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20participar%20do%20workshop%20Antes%20de%20virar%20o%20ano%20quero%20estar%20em%20paz%20comigo" target="_blank" rel="noopener">Quero participar</a>
        <a class="btn btn-ghost" href="#como-funciona">Como funciona</a>
      </div>
    </div>
  </header>

  <!-- TRUSTBAR -->
  <div class="trustbar" role="region" aria-label="Benefícios">
    <div class="container trust" aria-hidden="false">
      <div class="trust-item">3 encontros ao vivo (90–120min)</div>
      <div class="trust-item">Materiais e exercícios práticos</div>
      <div class="trust-item">Ritual de encerramento para 2026</div>
      <div class="trust-item">Vagas limitadas — atenção próxima</div>
    </div>
  </div>

  <!-- AS 3 NOITES -->
  <section id="noites" class="container" aria-labelledby="noites-title">
    <h2 id="noites-title" class="title">As 3 Noites</h2>
    <div class="nights" role="list">
      <article class="night" role="listitem" aria-label="1ª Noite">
        <h3>1ª Noite — O peso que ainda carrego</h3>
        <p>Reconhecer mágoas, culpas e cobranças que já não cabem mais. Dar nome é o primeiro passo para libertar. Espaço seguro para acolher e mapear padrões emocionais.</p>
      </article>

      <article class="night" role="listitem" aria-label="2ª Noite">
        <h3>2ª Noite — Quando soltar é cuidar</h3>
        <p>Práticas guiadas de soltura e autocuidado: respiração, escrita terapêutica e pequenos rituais para restaurar energia e criar suporte interno.</p>
      </article>

      <article class="night" role="listitem" aria-label="3ª Noite">
        <h3>3ª Noite — O recomeço que nasce da paz</h3>
        <p>Ritual prático para transformar o vivido em sabedoria e escolher intenções claras para 2026 — fechamento simbólico e plano simples de continuidade.</p>
      </article>
    </div>
  </section>

  <!-- COMO FUNCIONA -->
  <section id="como-funciona" class="container" aria-labelledby="como-title">
    <h2 id="como-title" class="title">Como funciona</h2>
    <div class="steps">
      <div class="step" aria-hidden="false">
        <div class="num">1</div>
        <h4>Encontros ao vivo</h4>
        <p>Três noites em formato online (gravação disponível por tempo limitado).</p>
      </div>
      <div class="step">
        <div class="num">2</div>
        <h4>Práticas guiadas</h4>
        <p>Exercícios somáticos, escrita, tempo para integração e partilhas seguras.</p>
      </div>
      <div class="step">
        <div class="num">3</div>
        <h4>Continuidade</h4>
        <p>Grupo fechado para apoiar a manutenção das intenções ao longo de 2026.</p>
      </div>
    </div>
  </section>

  <!-- DEPOIMENTOS -->
  <section class="container" aria-labelledby="depoimentos-title">
    <h2 id="depoimentos-title" class="title">Depoimentos</h2>
    <div class="depos" role="list">
      <div class="depo" role="listitem">
        <p>Saí com uma sensação de leveza que não sentia há anos. As práticas me ajudaram a entender onde eu me prendia.</p>
        <small>— Grasiela N.</small>
      </div>
      <div class="depo" role="listitem">
        <p>Aprendi a pausar e a cuidar de mim. Foi transformador para minha rotina emocional.</p>
        <small>— Mateus B.</small>
      </div>
      <div class="depo" role="listitem">
        <p>O ritual final me deu clareza para escolher o que quero cultivar em 2026.</p>
        <small>— Alini D.</small>
      </div>
    </div>
  </section>

  <!-- INVESTIMENTO -->
  <section id="investimento" aria-labelledby="invest-title">
    <div class="container">
      <h2 id="invest-title" class="title">Investimento</h2>
      <div class="price-wrap" role="list">
        <div style="text-align:center">
          <div class="price"><span class="old">R$ 399</span></div>
          <div class="price">R$ 249 <small style="display:block;font-size:14px;color:var(--green-900);font-weight:800">Valor por pessoa — vagas limitadas</small></div>
        </div>
      </div>
      <div style="margin-top:18px;text-align:center">
        <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20no%20Antes%20de%20virar%20o%20ano%20quero%20estar%20em%20paz%20comigo" target="_blank" rel="noopener">Garantir minha vaga</a>
      </div>
    </div>
  </section>

  <!-- GARANTIA -->
  <section id="garantia" class="container" aria-labelledby="garant-title">
    <h2 id="garant-title" class="title">Garantia & Transparência</h2>
    <div class="guarantee-card">
      <h3>Compromisso de acolhimento</h3>
      <p>Se, após a primeira noite, você sentir que o formato não atende às suas necessidades, entre em contato para avaliar reembolso conforme política combinada via WhatsApp.</p>
      <small>Datas, horários e formato serão confirmados após inscrição.</small>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" aria-labelledby="faq-title">
    <div class="container">
      <h2 id="faq-title" class="title">Perguntas Frequentes</h2>
      <div class="faq" role="list">
        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button"><span>Para quem é este workshop?</span></button>
          <div class="faq-a"><p>Para qualquer pessoa que deseja encerrar o ano com mais paz interior. Não é necessária experiência prévia.</p></div>
        </div>

        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button"><span>Preciso expor histórias pessoais?</span></button>
          <div class="faq-a"><p>Não. Há espaços de partilha, mas tudo é voluntário. As práticas individuais funcionam bem mesmo sem partilha pública.</p></div>
        </div>

        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button"><span>Qual a duração de cada encontro?</span></button>
          <div class="faq-a"><p>Entre 90 e 120 minutos, com espaço para integração e perguntas.</p></div>
        </div>
      </div>
    </div>
  </section>

  <!-- BIO / MENTOR -->
  <section class="container" aria-labelledby="bio-title">
    <h2 id="bio-title" class="title">Facilitador</h2>
    <div class="bio">
      <img src="Mentor.jpeg" alt="Evandro — facilitador" class="mentor-photo" onerror="this.style.display='none'">
      <h3>Evandro</h3>
      <p>Mentor em desenvolvimento pessoal e emocional — formação em gestão financeira e pós-graduação em neurociência, saúde mental e psicologia. Uso práticas sistêmicas e constelação para guiar processos com leveza e clareza.</p>

      <div class="final-buttons" style="margin-top:14px">
        <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20falar%20com%20o%20Evandro%20sobre%20o%20workshop" target="_blank" rel="noopener">Falar no WhatsApp</a>
        <a class="btn btn-ghost" href="#investimento">Ver investimento</a>
      </div>
    </div>
  </section>

  <!-- RODAPÉ -->
  <footer class="footer" role="contentinfo">
    <div class="container">
      © <span id="ano"></span> Antes de virar o ano, quero estar em paz comigo — Todos os direitos reservados. • 
    </div>
  </footer>

  <!-- WHATSAPP FLUTUANTE -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais%20sobre%20o%20workshop%20Antes%20de%20virar%20o%20ano" aria-label="Falar no WhatsApp" target="_blank" rel="noopener">
    <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <script>
    // ano no rodapé
    document.getElementById('ano').textContent = new Date().getFullYear();

    // FAQ toggle
    document.querySelectorAll('.faq-item').forEach(item => {
      const q = item.querySelector('.faq-q');
      q.addEventListener('click', () => item.classList.toggle('active'));
    });

    // keyboard accessibility for buttons/links
    document.querySelectorAll('button, a').forEach(el => {
      el.addEventListener('keydown', (e) => { if (e.key === 'Enter') el.click(); });
    });
  </script>
</body>
</html>
