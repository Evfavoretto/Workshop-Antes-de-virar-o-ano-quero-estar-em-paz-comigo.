
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
      --gold-500:#c6a75d;
      --yellow-canary:#ffeb3b;
      --stone-200:#e7e7e7;
      --red-700:#c62828;
      --shadow:0 10px 28px rgba(0,0,0,.14);
      --bg:#eaf5ec;
      --max-w:1200px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:#0b0b0b;background:var(--bg);-webkit-font-smoothing:antialiased;line-height:1.5}
    img{max-width:100%;display:block}
    a{text-decoration:none;color:inherit}

    /* cabeçalho fixo */
    .top-bar{
      position:fixed;
      top:0;left:0;right:0;
      background:var(--green-900);
      color:#fff;
      text-align:center;
      padding:14px 12px;
      font-weight:900;
      font-size:clamp(15px,2.6vw,20px);
      letter-spacing:.02em;
      z-index:9999;
      box-shadow:0 6px 20px rgba(0,0,0,.18);
    }

    .container{max-width:var(--max-w);margin:0 auto;padding:0 20px}
    section{padding:56px 20px}

    /* HERO WRAP: verde contínuo */
    .hero-wrap{
      background: linear-gradient(180deg, var(--green-900) 0%, var(--green-800) 100%);
      color:#fff;
      padding-top: calc(54px + 18px);
      padding-bottom: 28px;
    }

    /* HERO central */
    .hero{
      position:relative;
      max-width:var(--max-w);
      margin: 0 auto;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      padding:28px 18px 46px;
      overflow:hidden;
    }

    .hero .bg{
      position:absolute; inset:0;
      background-image: url('WhatsApp Image 2025-11-10 at 09.08.40.jpeg');
      background-size:cover;
      background-position:center;
      opacity:0.18;
      z-index:0;
      filter:contrast(.92) saturate(.82);
      transform:scale(1.02);
    }
    .hero::after{
      content:"";
      position:absolute; inset:0;
      background: linear-gradient(180deg, rgba(6,41,15,0.55), rgba(10,60,22,0.65));
      z-index:1;
    }

    .hero-inner{position:relative;z-index:2;max-width:980px}
    .hero h1{font-size:clamp(24px,4.5vw,48px);font-weight:900;margin-bottom:12px;line-height:1.02}
    .hero .subtitle{font-size:clamp(14px,1.9vw,18px);font-weight:600;color:rgba(255,255,255,0.96);margin-bottom:18px}

    .btn{display:inline-block;border-radius:999px;padding:12px 24px;font-weight:800;font-size:15px;cursor:pointer;transition:transform .18s}
    .btn-primary{background:var(--yellow-canary);color:#111;box-shadow:0 10px 28px rgba(0,0,0,.18)}
    .btn-primary:hover{transform:translateY(-3px)}

    /* hero-banner contínuo (titulo grande) */
    .hero-banner{
      background: transparent;
      margin:0 auto;
      max-width:1100px;
      padding:34px 18px 46px;
      text-align:center;
      color:#fff;
      position:relative;
      z-index:2;
      border-bottom-left-radius:14px;
      border-bottom-right-radius:14px;
      margin-top:18px;
    }
    .hero-banner h2{font-size:clamp(26px,4.8vw,48px);font-weight:900;margin-bottom:14px;line-height:1.02}
    .hero-banner p{color:rgba(255,255,255,0.95);font-size:18px;max-width:860px;margin:0 auto}

    /* trustbar */
    .trustbar{background:#fff;padding:14px 0;border-top:1px solid var(--stone-200);border-bottom:1px solid var(--stone-200)}
    .trust{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:10px;align-items:center;text-align:center;padding:6px 18px}
    .trust-item{background:#f8fbf9;border:1px solid var(--stone-200);border-radius:999px;padding:10px 14px;font-weight:700;color:var(--green-900);font-size:15px}

    /* As 3 noites */
    .title{font-size:clamp(22px,2.6vw,30px);text-align:center;margin:0 0 20px;font-weight:900;color:#0b0b0b}
    .nights{display:grid;gap:18px}
    @media(min-width:880px){.nights{grid-template-columns:repeat(3,1fr)}}
    .night{background:#fff;border:1px solid var(--stone-200);border-radius:14px;box-shadow:var(--shadow);padding:20px}
    .night h3{color:var(--green-900);margin-bottom:8px;font-size:16px}
    .night p{color:#333;font-size:15px;line-height:1.6}

    /* Investimento */
    #investimento{background:var(--green-soft);text-align:center}
    .price{font-size:32px;font-weight:900;color:var(--green-900);margin-bottom:8px}
    .price-note{font-size:15px;color:#444;margin-bottom:14px}

    /* FAQ */
    #faq{background:transparent;padding-top:42px;padding-bottom:42px}
    .faq-wrap{max-width:980px;margin:0 auto;display:flex;flex-direction:column;gap:12px}
    .faq-item{background:#fff;border:1px solid var(--stone-200);border-radius:12px;overflow:hidden;box-shadow:var(--shadow)}
    .faq-q{display:flex;justify-content:space-between;align-items:center;padding:14px 16px;cursor:pointer;font-weight:800;color:var(--green-900);font-size:15px;background:#fff;border:0}
    .faq-q:hover{background:#f7fff6}
    .faq-a{display:none;padding:12px 16px;color:#333;font-size:15px;line-height:1.6;background:#fff}
    .faq-item.open .faq-a{display:block}
    .faq-q::after{content:'▸';transition:transform .18s;color:#111;font-size:16px;margin-left:12px}
    .faq-item.open .faq-q::after{transform:rotate(90deg)}

    /* Bio / Mentor */
    .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:12px;box-shadow:var(--shadow);padding:22px;text-align:center}
    .mentor-photo{max-width:84px;border-radius:50%;margin:12px auto;box-shadow:0 6px 18px rgba(0,0,0,.25);object-fit:cover}
    .bio h3{font-size:18px;margin-bottom:8px}

    /* Footer / WhatsApp */
    .footer{background:var(--green-800);color:#e6f3ea;text-align:center;padding:18px 16px;font-size:14px;margin-top:18px}
    .whats-float{position:fixed;right:16px;bottom:16px;z-index:9999;width:56px;height:56px;border-radius:50%;background:#25D366;display:flex;align-items:center;justify-content:center;box-shadow:0 12px 28px rgba(0,0,0,.18)}
    .whats-float svg{width:28px;height:28px;fill:#fff}

    /* Desktop tweaks: mais presença */
    @media(min-width:1100px){
      .hero{padding:48px 18px 64px; min-height:48vh}
      .hero h1{font-size:48px}
      .hero-banner h2{font-size:48px}
      .hero .bg{opacity:0.16; transform:scale(1.04)}
    }

    /* Mobile */
    @media(max-width:560px){
      section{padding:36px 14px}
      .hero{padding:22px 14px 34px}
      .hero-wrap{padding-top:calc(54px + 10px)}
      .hero h1{font-size:20px}
      .hero-banner h2{font-size:20px}
      .mentor-photo{max-width:72px}
    }
  </style>
</head>
<body>

  <!-- cabeçalho fixo -->
  <div class="top-bar">Antes de virar o ano, quero estar em paz comigo</div>

  <!-- hero verde contínuo + banner sutil -->
  <div class="hero-wrap" role="region" aria-label="Topo — Antes de virar o ano">
    <div class="hero container" role="banner">
      <div class="bg" aria-hidden="true"></div>
      <div class="hero-inner">
        <h1>Encerre o ciclo com leveza</h1>
        <p class="subtitle">Três noites de vivência para reconhecer, soltar e recomeçar — preparando 2026 com paz interior.</p>
        <div style="margin-top:12px">
          <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20participar%20do%20workshop%20Antes%20de%20virar%20o%20ano" target="_blank" rel="noopener">Quero participar</a>
        </div>
      </div>
    </div>

    <div class="hero-banner container" aria-hidden="true">
      <h2>Encerre o ciclo com leveza</h2>
      <p>Três noites de vivência para reconhecer, soltar e recomeçar — preparar 2026 a partir de um lugar interno de paz.</p>
    </div>
  </div>

  <!-- trustbar -->
  <div class="trustbar" role="region" aria-label="Benefícios">
    <div class="container trust">
      <div class="trust-item">3 encontros ao vivo</div>
      <div class="trust-item">Práticas de soltura e autocuidado</div>
      <div class="trust-item">Ritual de recomeço para 2026</div>
      <div class="trust-item">Experiência gratuita</div>
    </div>
  </div>

  <!-- As 3 Noites -->
  <section id="noites" class="container" aria-labelledby="noites-title">
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
  <section id="investimento" class="container" aria-labelledby="invest-title">
    <h2 id="invest-title" class="title">Investimento</h2>
    <div class="price">Gratuito</div>
    <p class="price-note">Vivência aberta — vagas limitadas. Garanta sua vaga pelo WhatsApp.</p>
    <div style="margin-top:12px"><a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20gratuita" target="_blank" rel="noopener">Garantir minha vaga</a></div>
  </section>

  <!-- FAQ (abre um por vez) -->
  <section id="faq" class="container" aria-labelledby="faq-title">
    <h2 id="faq-title" class="title">Perguntas & Respostas</h2>
    <div class="faq-wrap" role="list">
      <div class="faq-item" role="listitem">
        <button class="faq-q" type="button">Para quem é este workshop?</button>
        <div class="faq-a">
          <p>Para qualquer pessoa que deseje concluir o ano com mais presença e leveza — sem necessidade de experiência prévia.</p>
        </div>
      </div>

      <div class="faq-item" role="listitem">
        <button class="faq-q" type="button">Qual a duração de cada encontro?</button>
        <div class="faq-a">
          <p>Cada encontro tem entre 90 e 120 minutos: espaço para práticas, integrações e perguntas.</p>
        </div>
      </div>

      <div class="faq-item" role="listitem">
        <button class="faq-q" type="button">Vou precisar falar sobre minha vida em grupo?</button>
        <div class="faq-a">
          <p>Não é obrigatório. Há momentos de partilha voluntária e exercícios que podem ser feitos de forma individual ou em dupla.</p>
        </div>
      </div>

      <div class="faq-item" role="listitem">
        <button class="faq-q" type="button">Será online ou presencial?</button>
        <div class="faq-a">
          <p>O formato principal é online. Caso haja turmas presenciais, as datas e locais serão informados via WhatsApp após inscrição.</p>
        </div>
      </div>

      <div class="faq-item" role="listitem">
        <button class="faq-q" type="button">Preciso pagar algo?</button>
        <div class="faq-a">
          <p>Esta edição está marcada como <strong>gratuita</strong>. Confirmamos detalhes pelo WhatsApp.</p>
        </div>
      </div>

      <div class="faq-item" role="listitem">
        <button class="faq-q" type="button">Receberei material de apoio?</button>
        <div class="faq-a">
          <p>Sim — enviaremos material de apoio e sugestões práticas após cada encontro para quem participar.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Mentor / Bio -->
  <section class="container" aria-labelledby="bio-title">
    <h2 id="bio-title" class="title">Facilitador</h2>
    <div class="bio">
      <img src="Mentor.jpeg" alt="Evandro — facilitador" class="mentor-photo" onerror="this.style.display='none'">
      <h3>Evandro</h3>
      <p>Mentor em desenvolvimento pessoal e emocional — pós-graduado em neurociência, saúde mental e psicologia. Uso práticas sistêmicas e constelação para guiar processos com cuidado e leveza.</p>
      <div style="margin-top:12px">
        <a class="btn btn-primary" href="https://wa.me/5549998110445?text=Quero%20falar%20com%20o%20Evandro" target="_blank" rel="noopener">Falar no WhatsApp</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer" role="contentinfo">
    © <span id="ano"></span> Antes de virar o ano, quero estar em paz comigo — Todos os direitos reservados.
  </footer>

  <!-- WhatsApp flutuante -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
    <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <script>
    // preencher ano
    document.getElementById('ano').textContent = new Date().getFullYear();

    // FAQ: abrir apenas 1 por vez (com acessibilidade)
    (function(){
      const items = Array.from(document.querySelectorAll('.faq-item'));
      items.forEach(item => {
        const btn = item.querySelector('.faq-q');
        btn.setAttribute('role','button');
        btn.setAttribute('tabindex','0');
        btn.addEventListener('click', () => {
          // fecha todos menos este
          items.forEach(i => {
            if(i !== item) i.classList.remove('open');
          });
          // alterna este
          item.classList.toggle('open');
          // rolar suavemente para garantir visibilidade em telas menores
          if(item.classList.contains('open')){
            setTimeout(() => {
              item.scrollIntoView({behavior:'smooth',block:'center'});
            }, 160);
          }
        });
        btn.addEventListener('keydown', e => {
          if(e.key === 'Enter' || e.key === ' '){
            e.preventDefault();
            btn.click();
          }
        });
      });
    })();
  </script>
</body>
</html>
