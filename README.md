<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop gratuito</title>
  <meta name="description" content="Workshop gratuito — Dias 2, 3 e 4 de dezembro às 20h. Três noites para encerrar 2025 com leveza, soltar o que pesa e entrar em 2026 em paz." />
  <!-- Open Graph -->
  <meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
  <meta property="og:description" content="2, 3 e 4 de dezembro • 20h — três noites para encerrar 2025 com leveza e se reencontrar antes de 2026." />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
  <meta name="twitter:card" content="summary_large_image" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    /* === Oculta títulos do GitHub Pages se necessário === */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    /* === VARIÁVEIS (edite aqui para mudar a paleta) === */
    :root{
      --maxw:1200px;
      --bg1:#FFF7F3;           /* fundo suave */
      --peach-1:#FFAC8A;       /* pêssego claro */
      --peach-2:#FF7A59;       /* pêssego intenso */
      --deep:#2B1F1A;          /* texto principal (quente) */
      --muted:#7F6B63;
      --card:#FFFFFF;
      --glass: rgba(43,31,25,0.06);
      --radius:14px;
      --hero-size: clamp(40px, 8.8vw, 96px);
      --accent-shadow: 0 18px 48px rgba(255,122,89,0.12);
      --ease: cubic-bezier(.2,.9,.3,1);
    }

    /* === Reset e base === */
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, Arial;
      color:var(--deep);
      background:linear-gradient(180deg,var(--bg1),#FFF0E8 60%);
      -webkit-font-smoothing:antialiased;
      line-height:1.5;
    }
    a{color:inherit}
    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px 20px}

    /* === Topbar === */
    .topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:8px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:64px;height:64px;border-radius:12px;
      background:linear-gradient(135deg,var(--peach-1),var(--peach-2));
      display:flex;align-items:center;justify-content:center;color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:22px;box-shadow:var(--accent-shadow)
    }
    nav a{margin-left:18px;font-weight:600;color:var(--muted);text-decoration:none}

    /* === HERO chamativo === */
    .hero{
      margin:20px 0;border-radius:20px;padding:40px;display:grid;grid-template-columns:1fr 380px;gap:28px;align-items:center;
      background:radial-gradient(circle at 10% 20%, rgba(255,172,138,0.10), transparent 10%),
                 radial-gradient(circle at 90% 80%, rgba(255,122,89,0.07), transparent 12%),
                 linear-gradient(180deg, rgba(255,255,255,0.85), rgba(255,250,248,0.95));
      box-shadow:var(--accent-shadow);
      overflow:visible;
    }
    @media(max-width:980px){ .hero{grid-template-columns:1fr;padding:28px} .hero-right{order:-1} }

    .kicker{display:inline-block;padding:6px 12px;border-radius:999px;background:rgba(255,122,89,0.12);color:var(--peach-2);font-weight:800;font-size:13px;letter-spacing:.06em}
    .hero-title{font-family:'Playfair Display',serif;font-size:var(--hero-size);line-height:0.92;margin:16px 0 8px;color:var(--deep);letter-spacing:-0.01em}
    .hero-sub{color:var(--muted);font-size:17px;max-width:740px}

    .hero-cta{display:flex;gap:12px;margin-top:18px;flex-wrap:wrap}
    .btn{
      padding:14px 20px;border-radius:12px;font-weight:800;border:0;cursor:pointer;display:inline-flex;align-items:center;gap:12px;transition:transform .16s var(--ease),box-shadow .16s var(--ease)
    }
    .btn-main{background:linear-gradient(90deg,var(--peach-2),var(--peach-1));color:#fff;box-shadow:0 16px 40px rgba(255,122,89,0.18)}
    .btn-main:hover{transform:translateY(-4px);box-shadow:0 26px 60px rgba(255,122,89,0.22)}
    .btn-ghost{background:transparent;border:1px solid var(--glass);color:var(--muted)}

    /* floating badge CTA */
    .float-cta{position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));padding:12px 16px;border-radius:12px;color:#fff;font-weight:800;box-shadow:0 20px 46px rgba(255,122,89,0.22);z-index:60}

    .hero-right{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 12px 34px rgba(0,0,0,0.04)}
    .meta-small{font-size:13px;color:var(--muted);margin-bottom:6px}
    .meta-strong{font-weight:800;font-size:20px;color:var(--deep);margin-bottom:8px}

    /* decorative animated underline under title */
    .underline{
      height:8px;border-radius:999px;margin-top:10px;width:160px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));
      transform-origin:left; animation:grow 1.2s var(--ease) both;
    }
    @keyframes grow{ from{transform:scaleX(0)} to{transform:scaleX(1)} }

    /* === PROBLEM / SOLUTION section === */
    section{padding:40px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:26px;margin:0 0 12px;color:var(--deep);text-align:center}
    .ps-grid{display:grid;gap:18px}
    @media(min-width:900px){ .ps-grid{grid-template-columns:1fr 1fr} }
    .ps-card{background:var(--card);padding:20px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 28px rgba(0,0,0,0.03)}
    .ps-card h3{margin:0 0 10px;color:var(--peach-2)}
    .ps-card p{color:var(--muted);white-space:pre-line;line-height:1.6}

    /* === THREE NIGHTS cards === */
    .grid-3{display:grid;gap:14px;margin-top:12px}
    @media(min-width:860px){ .grid-3{grid-template-columns:repeat(3,1fr)} }
    .card{background:linear-gradient(180deg,#fff,#fff);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 26px rgba(0,0,0,0.03)}
    .card h4{margin:0 0 8px;color:var(--peach-2);font-size:16px}
    .card p{color:var(--muted);line-height:1.55;white-space:pre-line}

    /* === BENEFITS compact === */
    .benefits{display:flex;flex-wrap:wrap;gap:12px;margin-top:14px;justify-content:center}
    .benefit{background:var(--card);padding:12px 14px;border-radius:10px;border:1px solid var(--glass);display:flex;gap:12px;align-items:center;min-width:200px;box-shadow:0 6px 18px rgba(0,0,0,0.02)}
    .icon{width:40px;height:40px;border-radius:10px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));color:#fff;display:flex;align-items:center;justify-content:center;font-weight:800}

    /* === FAQ interactive === */
    .faq{max-width:920px;margin:20px auto 0;display:grid;gap:10px}
    .faq-item{background:var(--card);border-radius:12px;border:1px solid var(--glass);overflow:hidden;box-shadow:0 8px 22px rgba(0,0,0,0.03)}
    .faq-q{display:flex;align-items:center;justify-content:space-between;padding:14px 16px;cursor:pointer}
    .faq-q h5{margin:0;font-size:15px;color:var(--deep)}
    .faq-a{max-height:0;overflow:hidden;padding:0 16px;transition:max-height .34s var(--ease)}
    .faq-item.open .faq-a{max-height:420px;padding:14px 16px}
    .faq-a p{margin:0;color:var(--muted);line-height:1.6}

    /* === FORM === */
    .form-wrap{max-width:760px;margin:18px auto}
    .form-card{background:var(--card);padding:20px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 12px 30px rgba(0,0,0,0.04)}
    .form-row{display:grid;gap:10px}
    @media(min-width:720px){ .form-row{grid-template-columns:1fr 260px} }
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700}
    input{width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--deep);font-size:15px;outline:none}
    .form-foot{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-top:12px}
    .small{font-size:13px;color:var(--muted)}

    /* footer */
    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:14px}

    /* focus */
    a:focus, button:focus, input:focus{outline:3px solid rgba(255,122,89,0.12);outline-offset:3px;border-radius:8px}

    /* responsive tweaks */
    @media(max-width:520px){
      .hero{padding:22px;grid-template-columns:1fr}
      .logo{width:56px;height:56px}
      .hero-title{font-size:clamp(28px,11vw,56px)}
    }
  </style>
</head>
<body>
  <div class="wrap" role="document">

    <!-- TOP -->
    <header class="topbar" role="banner" aria-label="Cabeçalho">
      <div class="brand" aria-hidden="false">
        <div class="logo" aria-hidden="true">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>

      <nav aria-label="Navegação">
        <a href="#problema">Por que</a>
        <a href="#noites">Noites</a>
        <a href="#faq">FAQ</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div>
        <div class="kicker" aria-hidden="true">Workshop Gratuito</div>
        <h1 id="hero-title" class="hero-title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline" aria-hidden="true"></div>
        <p class="hero-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

        <div class="hero-cta" role="group" aria-label="Ações principais">
          <button class="btn btn-main" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Quero participar — grátis</button>
          <button class="btn btn-ghost" onclick="document.getElementById('noites').scrollIntoView({behavior:'smooth'})">Ver as noites</button>
        </div>

        <div class="benefits" aria-hidden="true" style="margin-top:18px">
          <div class="benefit"><div class="icon">✓</div><div><strong>3 noites</strong><div style="color:var(--muted)">curtas & práticas</div></div></div>
          <div class="benefit"><div class="icon">★</div><div><strong>Ritual</strong><div style="color:var(--muted)">para entrar em 2026</div></div></div>
        </div>
      </div>

      <aside class="hero-right" aria-label="Resumo do evento">
        <div class="meta-small">Próximo encontro</div>
        <div class="meta-strong">02 Dez • 20h</div>
        <div style="height:1px;background:var(--glass);border-radius:6px;margin:10px 0"></div>
        <div class="meta-small">Duração</div>
        <div style="font-weight:800;color:var(--deep)">60–75 minutos / noite</div>
        <div class="meta-small" style="margin-top:8px">Gratuito — inscrição necessária</div>
        <div style="margin-top:12px">
          <button class="btn btn-main" style="width:100%" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Reservar meu lugar</button>
        </div>
      </aside>
    </main>

    <!-- PROBLEM / SOLUTION -->
    <section id="problema" aria-labelledby="sec-prob">
      <h2 id="sec-prob" class="section-title">Por que isso importa</h2>

      <div class="ps-grid" style="margin-top:14px">
        <div class="ps-card" aria-labelledby="prob-title">
          <h3 id="prob-title">Você não precisa carregar tudo sozinha</h3>
          <p>Muitas pessoas chegam ao fim do ano carregando cansaço emocional, culpa por não ter sido “suficiente”, mágoas antigas e a sensação de que o tempo passou sem que tenham cuidado de si.
Esse peso gera ansiedade, noites sem sono e dificulta um recomeço leve e consciente.</p>
        </div>

        <div class="ps-card" aria-labelledby="sol-title">
          <h3 id="sol-title">A solução: prática + acolhimento</h3>
          <p>Um espaço guiado, curto e seguro onde você vai:
• nomear o que pesa;
• aprender práticas para soltar com cuidado;
• transformar experiência em intenção para o novo ciclo.

O workshop reúne tudo isso em três noites práticas e acolhedoras — um processo pensado para fechar 2025 e abrir 2026 com mais paz.</p>
        </div>
      </div>
    </section>

    <!-- THREE NIGHTS -->
    <section id="noites" aria-labelledby="sec-noites" style="margin-top:22px">
      <h2 id="sec-noites" class="section-title">As três noites</h2>

      <div class="grid-3" style="margin-top:12px">
        <article class="card" aria-labelledby="n1">
          <h4 id="n1">🌙 1ª Noite — O peso que ainda carrego</h4>
          <p>Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.</p>
        </article>

        <article class="card" aria-labelledby="n2">
          <h4 id="n2">💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h4>
          <p>Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.</p>
        </article>

        <article class="card" aria-labelledby="n3">
          <h4 id="n3">✨ 3ª Noite — O recomeço que nasce da paz</h4>
          <p>Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.</p>
        </article>
      </div>
    </section>

    <!-- BENEFITS -->
    <section id="beneficios" aria-labelledby="sec-benef" style="margin-top:22px">
      <h2 id="sec-benef" class="section-title">O que você vai ganhar</h2>
      <div class="benefits" style="margin-top:12px">
        <div class="benefit"><div class="icon">1</div><div><strong>Clareza</strong><div style="color:var(--muted)">sobre o que vale soltar</div></div></div>
        <div class="benefit"><div class="icon">2</div><div><strong>Ferramentas</strong><div style="color:var(--muted)">práticas e simples</div></div></div>
        <div class="benefit"><div class="icon">3</div><div><strong>Ritual</strong><div style="color:var(--muted)">para começar 2026</div></div></div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" aria-labelledby="sec-faq" style="margin-top:28px">
      <h2 id="sec-faq" class="section-title">Perguntas frequentes</h2>
      <div class="faq" style="margin-top:12px" role="region" aria-live="polite">
        <div class="faq-item">
          <div class="faq-q" role="button" tabindex="0"><h5>Preciso participar das três noites?</h5><span aria-hidden="true">+</span></div>
          <div class="faq-a"><p>Idealmente sim — o ciclo se constrói noite a noite. Ainda assim, é possível participar de noites avulsas.</p></div>
        </div>

        <div class="faq-item">
          <div class="faq-q" role="button" tabindex="0"><h5>Haverá gravação?</h5><span aria-hidden="true">+</span></div>
          <div class="faq-a"><p>As gravações podem ser disponibilizadas por tempo limitado — inscreva-se para receber o comunicado por WhatsApp.</p></div>
        </div>

        <div class="faq-item">
          <div class="faq-q" role="button" tabindex="0"><h5>É gratuito?</h5><span aria-hidden="true">+</span></div>
          <div class="faq-a"><p>Sim — o workshop é totalmente gratuito.</p></div>
        </div>
      </div>
    </section>

    <!-- INSCRIPTION -->
    <section id="inscricao" aria-labelledby="sec-insc" style="margin-top:28px">
      <h2 id="sec-insc" class="section-title">Reserve seu lugar — é grátis</h2>

      <div class="form-wrap" style="margin-top:12px">
        <div class="form-card" role="form" aria-label="Formulário de inscrição">
          <form id="signup" onsubmit="return handleSignup(event)" autocomplete="on">
            <div class="form-row">
              <div>
                <label for="nome">Nome completo</label>
                <input id="nome" name="nome" type="text" placeholder="Ex: Ana Silva" required />
              </div>
              <div>
                <label for="wa">WhatsApp (com DDI)</label>
                <input id="wa" name="wa" type="text" placeholder="+55 11 9xxxx-xxxx" />
              </div>
            </div>

            <div style="margin-top:12px">
              <label for="email">E-mail (opcional)</label>
              <input id="email" name="email" type="email" placeholder="seu@exemplo.com" />
            </div>

            <div class="form-foot">
              <div class="small">Você receberá confirmação e lembretes por WhatsApp.</div>
              <button class="btn btn-main" type="submit">Confirmar inscrição</button>
            </div>
          </form>
        </div>
      </div>

    </section>

    <footer style="margin-top:36px">
      <div style="text-align:center;color:var(--muted)">© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</div>
    </footer>

    <!-- floating CTA -->
    <button class="float-cta" id="floatBtn" aria-label="Reservar meu lugar">Reservar meu lugar</button>
  </div>

  <script>
    // === Interatividade pequena: FAQ toggle, floating CTA scroll, form -> WhatsApp ===

    // FAQ: toggle
    (function(){
      const items = Array.from(document.querySelectorAll('.faq-item'));
      items.forEach(i=>{
        const q = i.querySelector('.faq-q');
        q.addEventListener('click', ()=> toggle(i));
        q.addEventListener('keydown', (e)=> { if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(i); }});
      });
      function toggle(current){
        const isOpen = current.classList.toggle('open');
        items.forEach(i => { if(i !== current) i.classList.remove('open'); });
      }
    })();

    // floating CTA: scroll to form
    document.getElementById('floatBtn').addEventListener('click', ()=> {
      document.getElementById('inscricao').scrollIntoView({behavior:'smooth'});
    });

    // Form submit: opens WhatsApp with message
    function handleSignup(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const wa = document.getElementById('wa').value.trim();

      // === IMPORTANTE: substitua pelo SEU número (formato internacional, sem sinais)
      // Ex.: const waNumber = '5511999999999';
      const waNumber = '55419998110445'; // <<-- altere para o número oficial (sem +, sem espaços)

      let msg = `Quero participar do workshop "Antes de virar o ano, quero estar em paz comigo." - Nome: ${nome}`;
      if(email) msg += `; Email: ${email}`;
      if(wa) msg += `; WhatsApp: ${wa}`;
      msg += ' — Inscrição via site.';
      const encoded = encodeURIComponent(msg);
      const url = `https://wa.me/${waNumber}?text=${encoded}`;
      window.open(url,'_blank');
      return false;
    }
  </script>
</body>
</html>
