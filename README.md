<!doctype html>
<html lang="pt-br">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width,initial-scale=1"/>
  <title>Antes de virar o ano, quero estar em paz comigo</title>
  <meta name="description" content="Três noites para reconhecer, soltar e recomeçar — preparando 2026 com paz interior. Workshop prático e acolhedor."/>
  <!-- Open Graph -->
  <meta property="og:title" content="Antes de virar o ano, quero estar em paz comigo"/>
  <meta property="og:description" content="Três noites para reconhecer, soltar e recomeçar — preparando 2026 com paz interior."/>
  <meta property="og:type" content="website"/>
  <meta property="og:image" content="WhatsApp Image 2025-11-10 at 09.08.40.jpeg"/>

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
      --ink:#0b0b0b;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:var(--ink);background:var(--bg);-webkit-font-smoothing:antialiased}
    .container{max-width:1120px;margin:0 auto;padding:0 20px}
    section{padding:60px 20px}

    /* HERO no topo — usando a imagem enviada como banner */
    .hero{
      position:relative;
      background:linear-gradient(180deg,var(--green-900),var(--green-800));
      color:#fff;
      text-align:center;
      padding:120px 20px 80px;
      margin-top:0;
      overflow:hidden;
    }
    .hero .banner{
      position:absolute;
      inset:0;
      background-image: url('WhatsApp Image 2025-11-10 at 09.08.40.jpeg');
      background-size:cover;
      background-position:center;
      opacity:.22;
      filter:grayscale(.02) saturate(.86);
      z-index:0;
    }
    .hero .overlay{
      position:absolute; inset:0; background:linear-gradient(180deg, rgba(6,41,15,.52), rgba(10,60,22,.64)); z-index:1;
    }
    .hero .inner{position:relative; z-index:2; max-width:980px; margin:0 auto; color:#fff}
    .hero h1 {
      font-size: clamp(28px, 6vw, 68px);
      letter-spacing: .5px;
      text-transform: none;
      margin-bottom: 18px;
      font-weight: 900;
      line-height:1.02;
    }
    .hero p.lead{max-width:820px;margin:12px auto 20px;color:rgba(255,255,255,.95);font-weight:600;font-size:18px}
    .hero .hero-kicker{max-width:880px;margin:20px auto 10px;color:#e8f7ef;font-weight:600;text-align:center}

    /* Botões */
    .btn{display:inline-block;border-radius:999px;padding:14px 28px;font-weight:800;text-decoration:none;cursor:pointer;transition:.18s;font-size:16px}
    .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
    .btn-yellow:hover{transform:translateY(-3px);filter:brightness(1.03)}
    .btn-ghost{background:transparent;color:#fff;border:2px solid rgba(255,255,255,.18);padding:12px 22px}

    /* Trustbar */
    .trustbar{background:#fff;padding:14px 0;border-top:1px solid var(--stone-200);border-bottom:1px solid var(--stone-200)}
    .trust{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:10px;align-items:center;text-align:center}
    .trust-item{background:#f8fbf9;border:1px solid var(--stone-200);border-radius:999px;padding:10px 14px;font-weight:700;color:var(--green-900)}

    /* As 3 noites */
    .title{font-size:42px;text-align:center;margin:0 0 28px;font-weight:900;color:var(--ink)}
    .nights{display:grid;gap:18px;grid-template-columns:1fr}
    @media(min-width:860px){.nights{grid-template-columns:repeat(3,1fr)}}
    .night{border-radius:16px;box-shadow:var(--shadow);padding:22px;background:#fff;border:1px solid var(--stone-200)}
    .night h3{color:var(--green-900);margin-bottom:10px;font-size:20px}
    .night p{color:#333;font-size:16px;line-height:1.6}

    /* Como funciona (passo a passo) */
    #como-funciona .steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    #como-funciona .step{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
    #como-funciona .step .num{width:48px;height:48px;border-radius:50%;background:var(--green-900);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:900;margin:0 auto 10px;font-size:18px}
    #como-funciona h4{margin:10px 0 6px;font-size:18px;color:var(--green-900)}

    /* Depoimentos */
    .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
    .depo{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:22px;position:relative;font-size:16px}
    .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:44px;color:var(--gold-500);opacity:.35}
    .depo p{margin:8px 0 12px;font-style:italic;color:#333}
    .depo small{display:block;color:#444;font-weight:700;text-align:right}

    /* Investimento */
    #investimento{background:var(--green-soft);text-align:center;padding:56px 20px}
    #investimento h2{font-size:36px;color:var(--red-700);margin-bottom:18px;font-weight:900}
    .price-wrap{display:grid;gap:12px;max-width:720px;margin:0 auto}
    .price{font-size:36px;color:var(--red-700);font-weight:900}
    .price .old{display:block;text-decoration:line-through;color:var(--green-900);font-size:18px;font-weight:900}

    /* Garantia / Transparência */
    #garantia .guarantee-card{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:24px;max-width:880px;margin:0 auto;text-align:center}
    #garantia h3{color:var(--green-900);margin-bottom:10px}
    #garantia small{display:block;margin-top:10px;color:#444}

    /* FAQ */
    #faq{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;padding-top:60px;padding-bottom:60px}
    #faq .title{color:#fff}
    .faq{max-width:900px;margin:0 auto;display:flex;flex-direction:column;gap:12px}
    .faq-item{border:1px solid rgba(255,255,255,.15);border-radius:14px;background:#fff;box-shadow:var(--shadow);overflow:hidden}
    .faq-q{width:100%;text-align:left;background:#fff;padding:16px 18px;font-weight:900;font-size:18px;cursor:pointer;display:flex;align-items:center;justify-content:space-between;color:var(--green-900)}
    .faq-a{display:none;padding:0 18px 18px 18px;color:#2c2c2c;font-size:16px;line-height:1.6;background:#fff}
    .faq-item.active .faq-a{display:block}
    .faq-item.active .faq-q::after{transform:rotate(90deg)}

    /* Bio / Mentor */
    .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:28px;text-align:center}
    .bio h3{font-size:26px;margin-bottom:8px}
    .mentor-photo{max-width:160px;border-radius:50%;margin:18px auto;display:block;box-shadow:0 6px 20px rgba(0,0,0,.25);object-fit:cover}

    /* CTA final */
    .final-buttons{margin-top:24px;text-align:center;display:flex;flex-direction:column;gap:12px;align-items:center}
    @media(min-width:680px){.final-buttons{flex-direction:row;justify-content:center}}

    /* Rodapé */
    .footer{background:var(--green-800);color: #e6f3ea;text-align:center;padding:28px 20px;font-size:14px}
    .footer a{color:var(--yellow-canary);text-decoration:none}

    /* WhatsApp Floating */
    .whats-float{
      position:fixed; right:18px; bottom:18px; z-index:9999;
      width:60px; height:60px; border-radius:50%; background:#25D366; display:flex; align-items:center; justify-content:center; box-shadow:0 12px 28px rgba(0,0,0,.18);
    }
    .whats-float svg{width:30px;height:30px;fill:#fff}
  </style>
</head>
<body>

  <!-- HERO -->
  <header class="hero" role="banner" aria-label="Hero — Antes de virar o ano, quero estar em paz comigo">
    <div class="banner" aria-hidden="true"></div>
    <div class="overlay" aria-hidden="true"></div>
    <div class="inner container">
      <h1>Antes de virar o ano, quero estar em paz comigo</h1>
      <p class="lead">Três noites de vivência para reconhecer, soltar e recomeçar — preparar 2026 com leveza e clareza emocional.</p>
      <div class="hero-kicker">Encontros ao vivo com práticas guiadas, reflexões e um ritual de recomeço.</div>
      <div style="margin-top:20px">
        <a class="btn btn-yellow" href="https://wa.me/5549998110445?text=Quero%20participar%20da%20Viv%C3%AAncia%20Em%20Paz%20Comigo" target="_blank" rel="noopener">Quero participar</a>
        <a class="btn btn-ghost" href="#como-funciona" style="margin-left:10px">Como funciona</a>
      </div>
    </div>
  </header>

  <!-- TRUSTBAR -->
  <div class="trustbar" role="region" aria-label="Benefícios">
    <div class="container trust">
      <div class="trust-item">3 encontros ao vivo (90-120min)</div>
      <div class="trust-item">Práticas guiadas e materiais de apoio</div>
      <div class="trust-item">Ritual de encerramento para 2026</div>
      <div class="trust-item">Vagas limitadas — acompanhamento próximo</div>
    </div>
  </div>

  <!-- AS 3 NOITES -->
  <section aria-labelledby="noites" class="container">
    <h2 id="noites" class="title">As 3 Noites</h2>
    <div class="nights" role="list">
      <article class="night" role="listitem" aria-label="1ª Noite">
        <h3>1ª Noite — O peso que ainda carrego</h3>
        <p>Reconhecer mágoas, culpas e cobranças que já não cabem mais. Dar nome é o primeiro passo para libertar. Espaço seguro para acolher o que pesa e começar a entender padrões.</p>
      </article>

      <article class="night" role="listitem" aria-label="2ª Noite">
        <h3>2ª Noite — Quando soltar é cuidar</h3>
        <p>Práticas guiadas de soltura e autocuidado: exercícios de respiração, escrita terapêutica e rituais de liberação para restaurar energia e confiança em si.</p>
      </article>

      <article class="night" role="listitem" aria-label="3ª Noite">
        <h3>3ª Noite — O recomeço que nasce da paz</h3>
        <p>Ritual prático para transformar o vivido em sabedoria e escolher intenções para 2026 — um fechamento simbólico e um plano simples para seguir em paz.</p>
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
        <p>Três noites em formato online (ou híbrido) com registro e materiais pós-encontro.</p>
      </div>
      <div class="step">
        <div class="num">2</div>
        <h4>Práticas guiadas</h4>
        <p>Exercícios somáticos, escrita e rituais simples para levar pra casa.</p>
      </div>
      <div class="step">
        <div class="num">3</div>
        <h4>Apoio e continuidade</h4>
        <p>Grupo fechado para quem participar, com orientações para aplicar as intenções durante 2026.</p>
      </div>
    </div>
  </section>

  <!-- DEPOIMENTOS -->
  <section class="container" aria-labelledby="depoimentos-title">
    <h2 id="depoimentos-title" class="title">Depoimentos</h2>
    <div class="depos">
      <div class="depo">
        <p>Saí com uma sensação de leveza que não sentia há anos. As práticas me ajudaram a entender onde eu me prendia.</p>
        <small>— Grasiela N.</small>
      </div>
      <div class="depo">
        <p>Aprendi a pausar e a cuidar de mim. Foi transformador para minha rotina emocional.</p>
        <small>— Mateus B.</small>
      </div>
      <div class="depo">
        <p>O ritual final me deu clareza para escolher o que quero cultivar em 2026.</p>
        <small>— Alini D.</small>
      </div>
    </div>
  </section>

  <!-- INVESTIMENTO -->
  <section id="investimento" aria-labelledby="invest-title">
    <div class="container">
      <h2 id="invest-title">Investimento</h2>
      <div class="price-wrap" role="list">
        <div>
          <div class="price"><span class="old">R$ 399</span></div>
          <div class="price">R$ 249 <small style="display:block;font-size:14px;color:var(--green-900);">Valor por pessoa — vagas limitadas</small></div>
        </div>
      </div>
      <div style="margin-top:18px">
        <a class="btn btn-yellow" href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20no%20Antes%20de%20virar%20o%20ano%20quero%20estar%20em%20paz%20comigo" target="_blank" rel="noopener">Garantir minha vaga</a>
      </div>
    </div>
  </section>

  <!-- GARANTIA -->
  <section id="garantia" class="container" aria-labelledby="garant-title">
    <h2 id="garant-title" class="title">Garantia & Transparência</h2>
    <div class="guarantee-card">
      <h3>Compromisso de acolhimento</h3>
      <p>Se, após a primeira noite, sentir que o formato não atende às suas necessidades, entre em contato para reembolso parcial conforme política informada no WhatsApp.</p>
      <small>Horários, datas e local (quando presencial) serão confirmados após inscrição.</small>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" aria-labelledby="faq-title">
    <div class="container">
      <h2 id="faq-title" class="title">Perguntas Frequentes</h2>
      <div class="faq" role="list">
        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button"><span>Para quem é este workshop?</span></button>
          <div class="faq-a"><p>Para qualquer pessoa que deseja encerrar o ano com mais paz interior: não é necessário experiência prévia.</p></div>
        </div>

        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button"><span>Preciso expor histórias pessoais?</span></button>
          <div class="faq-a"><p>Não. Há espaços de partilha voluntária e práticas individuais; você escolhe o quanto compartilhar.</p></div>
        </div>

        <div class="faq-item" role="listitem">
          <button class="faq-q" type="button"><span>Qual a duração de cada encontro?</span></button>
          <div class="faq-a"><p>Entre 90 e 120 minutos, com espaço para prática e perguntas.</p></div>
        </div>
      </div>
    </div>
  </section>

  <!-- BIO / MENTOR -->
  <section class="container" aria-labelledby="bio-title">
    <h2 id="bio-title" class="title">Facilitador</h2>
    <div class="bio">
      <img src="evandro-alinne.jpg" alt="Evandro — facilitador" class="mentor-photo" onerror="this.style.display='none'">
      <h3>Evandro</h3>
      <p>Mentor em desenvolvimento pessoal e emocional — formação em gestão financeira, pós-graduação em neurociência, saúde mental e psicologia. Uso práticas sistêmicas e experiência em constelações para guiar processos de transformação com leveza.</p>
      <div class="final-buttons" style="margin-top:16px">
        <a class="btn btn-yellow" href="https://wa.me/5549998110445?text=Quero%20falar%20com%20o%20Evandro%20sobre%20o%20workshop" target="_blank" rel="noopener">Falar no WhatsApp</a>
        <a class="btn btn-ghost" href="#investimento">Ver investimento</a>
      </div>
    </div>
  </section>

  <!-- RODAPÉ -->
  <footer class="footer" role="contentinfo">
    <div class="container">
      © <span id="ano"></span> Antes de virar o ano, quero estar em paz comigo — Todos os direitos reservados. • <a href="mailto:contato@seudominio.com">contato@seudominio.com</a>
    </div>
  </footer>

  <!-- WHATSAPP FLUTUANTE -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais%20sobre%20o%20workshop%20Antes%20de%20virar%20o%20ano" aria-label="Falar no WhatsApp" target="_blank" rel="noopener">
    <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <script>
    // ano no rodapé
    document.getElementById('ano').textContent = new Date().getFullYear();

    // FAQ toggle: abre/fecha item
    document.querySelectorAll('.faq-item').forEach(item => {
      const q = item.querySelector('.faq-q');
      q.addEventListener('click', () => {
        item.classList.toggle('active');
      });
    });

    // acessibilidade: foco em teclas para botões
    document.querySelectorAll('button, a').forEach(el => {
      el.addEventListener('keydown', (e) => {
        if(e.key === 'Enter') el.click();
      });
    });
  </script>
</body>
</html>
