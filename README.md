
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover" />
  <title>Antes de virar o ano, quero estar em paz comigo</title>
  <meta name="description" content="Três noites para reconhecer, soltar e recomeçar — preparando 2026 com leveza e clareza emocional." />
  <style>
    :root{
      --green-900:#0c4d1f;
      --green-800:#0a3c16;
      --green-soft:#e6f3ea;
      --yellow-canary:#ffeb3b;
      --stone-200:#e7e7e7;
      --shadow:0 10px 28px rgba(0,0,0,.12);
      --bg:#eaf5ec;
      --topbar-h:52px;
      --left-w:360px; /* largura da coluna verde no desktop */
      --gutter:22px;
      --max-w:1200px;
    }

    /* reset */
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
      color:#0b0b0b;
      background:var(--bg);
      -webkit-font-smoothing:antialiased;
      line-height:1.45;
      padding-top:var(--topbar-h);
      padding-bottom:90px; /* espaço para CTA flutuante/rodapé no mobile */
    }
    img{max-width:100%;display:block}
    a{text-decoration:none;color:inherit}

    /* esconder cabeçalhos GitHub Pages/Jekyll injetados */
    .markdown-body > h1:first-child,
    .markdown-body h1,
    body > header,
    body > .project-name,
    body > .project-tagline,
    .project-title,
    .repo-title,
    .site-header,
    .page-header,
    .jekyll-header,
    .gh-header,
    .gh-title {
      display:none !important;
    }
    .markdown-body { padding-top:0 !important; }

    /* topo fixo */
    .top-bar{
      position:fixed;top:0;left:0;right:0;height:var(--topbar-h);
      background:var(--green-900); color:#fff; display:flex;align-items:center;justify-content:center;
      padding:0 12px;font-weight:800;font-size:14px;z-index:9999;box-shadow:0 6px 18px rgba(0,0,0,.08);
    }

    .site-wrap{max-width:var(--max-w);margin:0 auto;padding:0 16px}

    /* ===== SPLIT: coluna esquerda contínua + conteúdo à direita =====
       No desktop: duas colunas
       No mobile: empilha (coluna verde aparece acima do conteúdo)
    */
    .split {
      margin: 0 auto;
      display:grid;
      grid-template-columns: 1fr; /* mobile first: 1 coluna */
      gap: var(--gutter);
      align-items:stretch;
      max-width:var(--max-w);
      padding-top:12px;
    }

    /* left visual column (verde contínuo) */
    .split .left {
      background: linear-gradient(180deg, var(--green-900), var(--green-800));
      color: #fff;
      border-radius: 12px;
      position: relative;
      overflow: hidden;
      min-height: 240px;
      display:flex;
      align-items:center;
      justify-content:center;
      padding: 22px 14px;
    }
    .left .left-inner {
      width:100%;
      max-width: 280px;
      text-align:center;
    }
    .left .left-inner h3{font-size:20px;font-weight:900;margin-bottom:8px}
    .left .left-inner p{font-size:14px;color:rgba(255,255,255,0.95);line-height:1.4}

    /* textura/imagem discreta na esquerda */
    .left::before{
      content:"";
      position:absolute; inset:0;
      background-image:url('WhatsApp Image 2025-11-10 at 09.08.40.jpeg');
      background-size:cover;background-position:center;
      opacity:0.06; z-index:0; transform:scale(1.02);
      filter:contrast(.95) saturate(.8);
    }

    /* right column com o conteúdo (hero + trustbar estarão aqui) */
    .split .right {
      background: transparent;
      padding: 0;
    }

    /* HERO (dentro da coluna direita) */
    .hero {
      background: transparent;
      padding: 28px 16px 18px;
      position: relative;
      z-index:2;
      text-align:left;
      display:flex;
      flex-direction:column;
      justify-content:center;
    }
    .hero h1{font-size:clamp(20px,4.4vw,30px);font-weight:900;color:var(--green-900);margin-bottom:12px}
    .hero p.lead{font-size:15px;color:#244b2e;margin-bottom:18px;max-width:780px}

    /* CTA: no desktop atravessa (invade) a divisão, no mobile fica full width */
    .cta {
      display:flex;align-items:center;
      position:relative;
    }
    .btn{
      display:inline-block;border-radius:999px;padding:12px 22px;font-weight:800;font-size:15px;cursor:pointer;transition:transform .12s, box-shadow .12s;
    }
    .btn-primary{background:var(--yellow-canary);color:#111;box-shadow:0 12px 30px rgba(0,0,0,.12)}
    .btn-primary:hover{transform:translateY(-2px)}

    /* TRUSTBAR: deixamos transparente na esquerda, mas o lado direito fica branco — removi o "quadro branco" visualmente indesejado
       Aqui o trustbar é colocado dentro da coluna direita, enquanto a coluna esquerda continua verde (visual contínuo).
    */
    .trustbar{
      margin-top:18px;
      padding:10px 0;
    }
    .trust {
      display:grid;
      gap:10px;
      grid-template-columns:1fr;
    }
    @media(min-width:880px){
      .trust{grid-template-columns:repeat(2,1fr)}
    }
    .trust-item{background:#fff;border-radius:999px;padding:10px 12px;text-align:center;border:1px solid var(--stone-200);font-weight:700;color:var(--green-900)}

    /* Section geral: "As 3 Noites" e cards */
    section{padding:42px 16px}
    .title{font-size:clamp(20px,3.6vw,28px);text-align:center;margin:0 0 18px;font-weight:900;color:#0b0b0b}
    .nights{display:grid;gap:14px}
    @media(min-width:880px){ .nights{grid-template-columns:repeat(3,1fr)} }
    .night{background:#fff;border:1px solid var(--stone-200);border-radius:12px;box-shadow:var(--shadow);padding:14px}
    .night h3{color:var(--green-900);margin-bottom:8px;font-size:15px}
    .night p{color:#333;font-size:14px;line-height:1.5}

    /* Investimento e FAQ */
    #investimento{background:var(--green-soft);text-align:center;padding:36px 16px;border-radius:10px}
    .price{font-size:22px;font-weight:900;color:var(--green-900);margin-bottom:8px}

    .faq-wrap{max-width:920px;margin:0 auto;display:flex;flex-direction:column;gap:10px}
    .faq-item{background:#fff;border:1px solid var(--stone-200);border-radius:10px;overflow:hidden;box-shadow:var(--shadow)}
    .faq-q{display:flex;justify-content:space-between;align-items:center;padding:14px 12px;cursor:pointer;font-weight:800;color:var(--green-900);font-size:15px;background:#fff}
    .faq-a{display:none;padding:12px 14px;color:#333;font-size:14px;line-height:1.6;background:#fff}
    .faq-item.open .faq-a{display:block}
    .faq-q::after{content:'▸';transition:transform .18s;color:#111;margin-left:12px}
    .faq-item.open .faq-q::after{transform:rotate(90deg)}

    /* Bio */
    .bio{max-width:820px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:12px;box-shadow:var(--shadow);padding:14px;text-align:center}
    .mentor-photo{max-width:76px;border-radius:50%;margin:8px auto;box-shadow:0 6px 18px rgba(0,0,0,.14);object-fit:cover}

    /* sticky CTA (mobile) */
    .sticky-cta{
      position:fixed;left:12px;right:12px;bottom:12px;z-index:9998;display:none;justify-content:center;
    }
    .sticky-cta .btn-primary{width:100%;padding:14px 18px;border-radius:12px;font-size:16px;box-shadow:0 12px 26px rgba(0,0,0,.14)}

    /* float whatsapp */
    .whats-float{position:fixed;right:16px;bottom:86px;z-index:9999;width:56px;height:56px;border-radius:50%;background:#25D366;display:flex;align-items:center;justify-content:center;box-shadow:0 12px 28px rgba(0,0,0,.12)}
    .whats-float svg{width:28px;height:28px;fill:#fff}

    .footer{background:var(--green-800);color:#e6f3ea;text-align:center;padding:16px 12px;font-size:13px;margin-top:18px;border-radius:8px}

    /* DESKTOP: layout em duas colunas, left fixa, right flex */
    @media(min-width:880px){
      .split{ grid-template-columns: var(--left-w) 1fr; gap:var(--gutter); align-items:stretch; }
      /* CTA invade a divisão: posicionamento negativo para atravessar o limite */
      .hero .cta { margin-top:8px; display:flex; }
      .hero .btn-primary { position: relative; left: 60px; box-shadow:0 18px 36px rgba(0,0,0,.12); }
      /* se o botão ficar muito fora no desktop grande, limitamos */
      @media(min-width:1200px){
        .hero .btn-primary{ left: 86px; }
      }
      /* left column: garantir estender até o final do right's header area (já feito pelo grid) */
      .left{ border-radius:12px 0 12px 12px; }
    }

    /* MOBILE tweaks */
    @media(max-width:879px){
      .left{ border-radius:10px; min-height:180px; padding:18px; }
      .left .left-inner h3{font-size:18px}
      .left .left-inner p{font-size:13px}
      .hero h1{font-size:20px}
      .hero p.lead{font-size:14px}
      .btn-primary{width:100%}
      .sticky-cta{display:flex}
      .whats-float{bottom:72px}
    }
  </style>
</head>
<body>
  <div class="top-bar">Antes de virar o ano, quero estar em paz comigo</div>

  <div class="site-wrap">

    <!-- SPLIT: coluna esquerda contínua + direita com hero+trustbar -->
    <div class="split" role="region" aria-label="Topo dividido">
      <div class="left" aria-hidden="true">
        <div class="left-inner">
          <h3>Antes de virar o ano, quero estar em paz comigo</h3>
          <p>Um espaço pra soltar, respirar e recomeçar de coração leve.</p>
        </div>
      </div>

      <div class="right">
        <!-- HERO (conteúdo principal à direita) -->
        <div class="hero" role="region" aria-label="Hero">
          <div class="hero-inner">
            <h1>Encerre o ciclo com leveza</h1>
            <p class="lead">Três noites de vivência para reconhecer, soltar e recomeçar — preparando 2026 com paz interior.</p>

            <div class="cta">
              <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20participar%20do%20workshop" target="_blank" rel="noopener">Quero participar</a>
            </div>
          </div>
        </div>

        <!-- TRUSTBAR (continua à direita; left permanece verde) -->
        <div class="trustbar" role="region" aria-label="Benefícios">
          <div class="trust">
            <div class="trust-item">3 encontros ao vivo</div>
            <div class="trust-item">Práticas de soltura e autocuidado</div>
            <div class="trust-item">Ritual de recomeço para 2026</div>
            <div class="trust-item">Experiência gratuita</div>
          </div>
        </div>
      </div> <!-- fim right -->
    </div> <!-- fim split -->

    <!-- As 3 Noites -->
    <section aria-labelledby="noites-title">
      <h2 id="noites-title" class="title">As 3 Noites</h2>
      <div class="nights">
        <div class="night">
          <h3>1ª Noite — O peso que ainda carrego</h3>
          <p>Reconhecer mágoas, culpas e cobranças que já não cabem mais. Dar nome é o primeiro passo para libertar.</p>
        </div>
        <div class="night">
          <h3>2ª Noite — Quando soltar é cuidar</h3>
          <p>Práticas guiadas de soltura e autocuidado: respiração, escrita terapêutica e rituais de liberação.</p>
        </div>
        <div class="night">
          <h3>3ª Noite — O recomeço que nasce da paz</h3>
          <p>Ritual prático para transformar o vivido em sabedoria e escolher intenções para 2026.</p>
        </div>
      </div>
    </section>

    <!-- Investimento -->
    <section id="investimento" aria-labelledby="invest-title">
      <h2 id="invest-title" class="title">Investimento</h2>
      <div class="price">Gratuito</div>
      <p class="price-note">Vivência aberta — vagas limitadas. Garanta sua vaga pelo WhatsApp.</p>
      <div style="margin-top:10px"><a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20gratuita" target="_blank" rel="noopener">Garantir minha vaga</a></div>
    </section>

    <!-- FAQ -->
    <section id="faq" aria-labelledby="faq-title">
      <h2 id="faq-title" class="title">Perguntas & Respostas</h2>
      <div class="faq-wrap" role="list">
        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button">Para quem é este workshop?</button>
          <div class="faq-a"><p>Para qualquer pessoa que deseje concluir o ano com mais presença e leveza — sem necessidade de experiência prévia.</p></div>
        </div>
        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button">Qual a duração de cada encontro?</button>
          <div class="faq-a"><p>Cada encontro tem entre 90 e 120 minutos: espaço para práticas, integrações e perguntas.</p></div>
        </div>
        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button">Vou precisar falar em grupo?</button>
          <div class="faq-a"><p>Não é obrigatório. Partilha é voluntária; há práticas individuais.</p></div>
        </div>
      </div>
    </section>

    <!-- Mentor -->
    <section aria-labelledby="bio-title">
      <h2 id="bio-title" class="title">Facilitador</h2>
      <div class="bio">
        <img src="Mentor.jpeg" alt="Evandro — facilitador" class="mentor-photo" onerror="this.style.display='none'">
        <h3>Evandro</h3>
        <p>Mentor em desenvolvimento pessoal e emocional — pós-graduado em neurociência, saúde mental e psicologia. Uso práticas sistêmicas e constelação para guiar processos com cuidado e leveza.</p>
      </div>
    </section>

    <footer class="footer">© <span id="ano"></span> Antes de virar o ano, quero estar em paz comigo — Todos os direitos reservados.</footer>

  </div><!-- .site-wrap -->

  <!-- CTA fixo mobile -->
  <div class="sticky-cta" aria-hidden="false">
    <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20participar%20do%20workshop" target="_blank" rel="noopener">Quero participar</a>
  </div>

  <!-- WhatsApp flutuante -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
    <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <script>
    // ano no rodapé
    document.getElementById('ano').textContent = new Date().getFullYear();

    // FAQ: abre apenas 1 por vez (acessível)
    (function(){
      const items = Array.from(document.querySelectorAll('.faq-item'));
      items.forEach(item => {
        const btn = item.querySelector('.faq-q');
        btn.setAttribute('role','button');
        btn.setAttribute('tabindex','0');
        btn.addEventListener('click', () => {
          items.forEach(i => { if(i !== item) i.classList.remove('open'); });
          item.classList.toggle('open');
          if(item.classList.contains('open')) setTimeout(()=> item.scrollIntoView({behavior:'smooth',block:'center'}),120);
        });
        btn.addEventListener('keydown', e => { if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); btn.click(); } });
      });
    })();
  </script>
</body>
</html>
