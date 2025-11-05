<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop gratuito</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro, às 20h) para encerrar 2025 com leveza e entrar em 2026 em paz." />
  <meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
  <meta property="og:description" content="Três noites para encerrar 2025 com leveza e se reencontrar consigo mesma. 2, 3 e 4 de dezembro • 20h" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
  <meta name="twitter:card" content="summary_large_image" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Playfair+Display:wght@600;800&display=swap" rel="stylesheet">

  <style>
    /* Remove cabeçalho do GitHub Pages */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    /* ===== VARIÁVEIS (altere aqui para personalizar cores/título) ===== */
    :root{
      --bg:#FFF8F4;                 /* fundo suave */
      --hero-grad-1:#7C3AED;        /* violeta profundo */
      --hero-grad-2:#FF6B6B;        /* coral quente */
      --accent:#FF6B6B;
      --muted:#6B7280;
      --card:#FFFFFF;
      --ink:#0B1220;
      --radius:18px;
      --maxw:1200px;
      --hero-title: clamp(44px, 8.6vw, 120px); /* título grande e responsivo */
      --glass: rgba(11,18,32,0.04);
      --easing: cubic-bezier(.2,.9,.3,1);
    }
    /* ===== reset simples ===== */
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      background:var(--bg);color:var(--ink);-webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;line-height:1.5;
    }
    .wrap{max-width:var(--maxw);margin:0 auto;padding:36px 20px}

    /* ===== topbar ===== */
    .topbar{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:6px 0}
    .brand{display:flex;gap:14px;align-items:center}
    .logo{
      width:64px;height:64px;border-radius:14px;
      background:linear-gradient(135deg,var(--hero-grad-1),var(--hero-grad-2));
      display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;font-family:'Playfair Display',serif;
      box-shadow:0 10px 30px rgba(11,18,32,0.12);
    }
    nav a{color:var(--muted);text-decoration:none;font-weight:600;margin-left:18px}

    /* ===== HERO dramático ===== */
    .hero{
      margin:18px 0 28px;border-radius:20px;overflow:hidden;position:relative;
      background:linear-gradient(135deg, rgba(124,58,237,0.09), rgba(255,107,107,0.06));
      padding:44px;
      display:grid;grid-template-columns:1fr;gap:18px;align-items:center;
      box-shadow:0 30px 60px rgba(11,18,32,0.06);
    }
    @media(min-width:980px){ .hero{grid-template-columns:1fr 420px;padding:56px} }

    .hero-kicker{display:inline-block;padding:6px 12px;border-radius:999px;background:rgba(255,255,255,0.6);font-weight:800;color:var(--accent);font-size:13px}
    .hero-title{
      font-family:'Playfair Display',serif;
      font-size:var(--hero-title);
      line-height:0.95;
      margin:18px 0 10px;
      color:linear-gradient(90deg,var(--hero-grad-1),var(--hero-grad-2));
      background:linear-gradient(90deg,var(--hero-grad-1),var(--hero-grad-2));
      -webkit-background-clip:text;background-clip:text;color:transparent;
      text-wrap:balance;
      text-shadow:0 6px 20px rgba(124,58,237,0.08);
    }
    .hero-sub{font-size:18px;color:var(--muted);max-width:740px;margin-bottom:18px}

    .cta-row{display:flex;gap:12px;flex-wrap:wrap}
    .btn{
      display:inline-flex;align-items:center;gap:10px;padding:14px 20px;border-radius:12px;border:0;font-weight:800;cursor:pointer;
      transition:transform .16s var(--easing),box-shadow .16s var(--easing);
    }
    .btn-primary{background:linear-gradient(90deg,var(--hero-grad-1),var(--hero-grad-2));color:#fff;box-shadow:0 14px 34px rgba(124,58,237,0.12)}
    .btn-primary:hover{transform:translateY(-3px)}
    .btn-ghost{background:transparent;border:1px solid rgba(11,18,32,0.06);color:var(--muted)}

    .hero-panel{
      background:linear-gradient(180deg,rgba(255,255,255,0.8),#fff);
      border-radius:14px;padding:18px;border:1px solid var(--glass);
      box-shadow:0 12px 30px rgba(11,18,32,0.06);
    }
    .hero-meta{font-weight:700;color:var(--ink);margin-bottom:6px}
    .hero-small{color:var(--muted);font-size:13px}

    /* SVG accent */
    .hero .accent-blob{position:absolute;right:-120px;top:-40px;opacity:.14;filter:blur(24px);transform:rotate(12deg);pointer-events:none}

    /* ===== PROBLEMA / SOLUÇÃO ===== */
    .ps{display:grid;gap:20px;margin-top:24px}
    @media(min-width:900px){ .ps{grid-template-columns:1fr 1fr} }
    .ps-card{background:var(--card);padding:24px;border-radius:14px;border:1px solid var(--glass);box-shadow:0 14px 36px rgba(11,18,32,0.04)}
    .ps-card h3{margin:0 0 10px;color:var(--hero-grad-1);font-size:20px}
    .ps-card p{color:var(--muted);font-size:16px;white-space:pre-line}

    /* ===== TRÊS NOITES ===== */
    .grid-3{display:grid;gap:18px;margin-top:6px}
    @media(min-width:860px){ .grid-3{grid-template-columns:repeat(3,1fr)} }
    .card{background:var(--card);padding:20px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 30px rgba(11,18,32,0.03)}
    .card h4{margin:0 0 10px;font-size:18px;color:var(--hero-grad-1)}
    .card p{color:var(--muted);white-space:pre-line}

    /* ===== BENEFÍCIOS ===== */
    .benefits{display:flex;flex-wrap:wrap;gap:12px;margin-top:16px}
    .benefit{background:linear-gradient(90deg,#fff,#fff);border-radius:10px;padding:12px 14px;border:1px solid var(--glass);display:flex;gap:10px;align-items:center;min-width:220px}
    .badge{width:40px;height:40px;border-radius:10px;background:linear-gradient(90deg,var(--hero-grad-1),var(--hero-grad-2));color:#fff;display:flex;align-items:center;justify-content:center;font-weight:800}

    /* ===== FAQ elegante ===== */
    .faq{margin-top:26px;display:grid;gap:12px}
    .faq-item{border-radius:12px;border:1px solid var(--glass);overflow:hidden;background:var(--card);box-shadow:0 8px 20px rgba(11,18,32,0.03)}
    .faq-q{display:flex;align-items:center;gap:12px;padding:14px 16px;cursor:pointer}
    .faq-q h5{margin:0;font-size:16px}
    .faq-a{max-height:0;overflow:hidden;padding:0 16px;transition:max-height .32s var(--easing)}
    .faq-item.open .faq-a{max-height:400px;padding:14px 16px}
    .faq-a p{margin:0;color:var(--muted)}

    /* ===== FORM ===== */
    .form-card{max-width:760px;margin:18px auto;padding:22px;border-radius:12px;background:var(--card);border:1px solid var(--glass)}
    .form-row{display:grid;gap:12px}
    @media(min-width:720px){.form-row{grid-template-columns:1fr 260px}}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700}
    input{width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--ink);font-size:15px;outline:none}
    .form-foot{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-top:12px}
    .note{font-size:13px;color:var(--muted)}

    /* ===== FOOTER ===== */
    footer{margin-top:28px;padding:36px 0;text-align:center;color:var(--muted);font-size:14px}

    /* small responsive tweaks */
    @media(max-width:520px){ .logo{width:52px;height:52px} .hero-panel{display:none} .hero{padding:28px} }
    /* focus */
    :focus{outline:3px solid rgba(124,58,237,0.12);outline-offset:3px;border-radius:8px}
  </style>
</head>
<body>
  <div class="wrap">
    <!-- TOP -->
    <header class="topbar" aria-label="Cabeçalho">
      <div class="brand">
        <div class="logo" aria-hidden="true">⚖️</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>
      <nav aria-label="Navegação">
        <a href="#problema">Problema</a>
        <a href="#noites">Noites</a>
        <a href="#faq">Perguntas</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div>
        <div class="hero-kicker">Workshop Gratuito</div>

        <!-- TITULO BEM GRANDE -->
        <h1 id="hero-title" class="hero-title">Antes de virar o ano, quero estar em paz comigo.</h1>

        <!-- datas e descrição -->
        <div class="hero-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar antes de entrar em 2026.</div>

        <!-- CTA -->
        <div class="cta-row" style="margin-top:18px">
          <button class="btn btn-primary" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Inscrever-se grátis</button>
          <a class="btn btn-ghost" href="#noites">Ver as noites</a>
        </div>

        <!-- mini benefícios -->
        <div style="margin-top:18px" class="benefits" aria-hidden="false">
          <div class="benefit"><div class="badge">✓</div><div><strong>3 noites</strong><div style="color:var(--muted)">práticas e acolhedoras</div></div></div>
          <div class="benefit"><div class="badge">★</div><div><strong>Ritual</strong><div style="color:var(--muted)">para entrar em 2026</div></div></div>
        </div>
      </div>

      <!-- painel lateral -->
      <aside class="hero-panel" aria-label="Resumo do evento">
        <div style="display:flex;flex-direction:column;gap:10px">
          <div style="font-size:13px;color:var(--muted)">Próximo encontro</div>
          <div style="font-weight:800;font-size:20px;color:var(--ink)">02 Dez • 20h</div>
          <div style="height:1px;background:var(--glass);margin:8px 0;border-radius:4px"></div>
          <div style="font-size:13px;color:var(--muted)">Duração</div>
          <div style="font-weight:700;color:var(--ink)">60–75 minutos / noite</div>
          <div style="font-size:13px;color:var(--muted);margin-top:8px">Gratuito — inscrição necessária</div>
          <div style="margin-top:12px">
            <button class="btn btn-primary" style="width:100%" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Quero participar</button>
          </div>
        </div>
      </aside>

      <!-- decorative SVG blob -->
      <svg class="accent-blob" width="520" height="520" viewBox="0 0 520 520" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <defs>
          <linearGradient id="g" x1="0" x2="1"><stop offset="0" stop-color="#7C3AED"/><stop offset="1" stop-color="#FF6B6B"/></linearGradient>
        </defs>
        <path d="M420 60C470 120 500 220 440 300C380 380 260 420 180 380C100 340 60 220 120 140C180 60 320 0 420 60Z" fill="url(#g)" />
      </svg>
    </main>

    <!-- PROBLEMA / SOLUÇÃO -->
    <section id="problema" style="margin-top:6px">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:16px;flex-wrap:wrap">
        <h2 class="section-title" style="margin:0">O problema que a maioria enfrenta</h2>
        <div style="color:var(--muted);font-size:14px">Se isso ressoa, você está no lugar certo.</div>
      </div>

      <div class="ps" style="margin-top:18px">
        <div class="ps-card">
          <h3>Você não está sozinha nisso</h3>
          <p>
Muitas pessoas chegam ao fim do ano carregando cansaço emocional, culpa por não ter sido “suficiente”, mágoas antigas e a sensação de que o tempo passou sem que tenham cuidado de si.
Isso gera ansiedade, noites sem sono e um peso constante que bloqueia um recomeço leve e consciente.
          </p>
        </div>

        <div class="ps-card">
          <h3>A solução: um lugar para fechar com paz</h3>
          <p>
Entrar em um espaço guiado, curto e seguro onde você possa:
• dar nome ao que pesa;
• aprender práticas para soltar com cuidado;
• transformar experiência em intenção para o próximo ciclo.

O Workshop é exatamente isso: três noites práticas e acolhedoras para fechar 2025 e chegar em 2026 mais leve.
          </p>
        </div>
      </div>
    </section>

    <!-- TRÊS NOITES -->
    <section id="noites" style="margin-top:6px">
      <h2 class="section-title">As três noites</h2>
      <div class="grid-3" style="margin-top:18px">
        <article class="card" aria-labelledby="n1">
          <h4 id="n1">🌙 1ª Noite — O peso que ainda carrego</h4>
          <p>
Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.
          </p>
        </article>

        <article class="card" aria-labelledby="n2">
          <h4 id="n2">💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h4>
          <p>
Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.
          </p>
        </article>

        <article class="card" aria-labelledby="n3">
          <h4 id="n3">✨ 3ª Noite — O recomeço que nasce da paz</h4>
          <p>
Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.
          </p>
        </article>
      </div>
    </section>

    <!-- BENEFÍCIOS -->
    <section id="beneficios" style="margin-top:18px">
      <h2 class="section-title">O que você vai levar</h2>
      <div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:12px">
        <div class="benefit"><div class="badge">1</div><div><strong>Clareza</strong><div style="color:var(--muted)">sobre o que soltar</div></div></div>
        <div class="benefit"><div class="badge">2</div><div><strong>Práticas</strong><div style="color:var(--muted)">simples de autocuidado</div></div></div>
        <div class="benefit"><div class="badge">3</div><div><strong>Ritual</strong><div style="color:var(--muted)">para intenção de 2026</div></div></div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" style="margin-top:18px">
      <h2 class="section-title">Perguntas frequentes</h2>
      <div class="faq" aria-live="polite" style="margin-top:12px">
        <!-- item -->
        <div class="faq-item" data-key="participar">
          <div class="faq-q" role="button" tabindex="0"><h5>Preciso participar das três noites?</h5></div>
          <div class="faq-a"><p>Acompanhar as três noites traz mais sentido ao processo, mas é possível participar de noites avulsas se necessário.</p></div>
        </div>
        <div class="faq-item" data-key="gravação">
          <div class="faq-q" role="button" tabindex="0"><h5>Haverá gravação?</h5></div>
          <div class="faq-a"><p>As gravações podem ficar disponíveis por tempo limitado — inscreva-se para receber avisos por WhatsApp.</p></div>
        </div>
        <div class="faq-item" data-key="gratuito">
          <div class="faq-q" role="button" tabindex="0"><h5>É gratuito?</h5></div>
          <div class="faq-a"><p>Sim — o workshop é 100% gratuito.</p></div>
        </div>
      </div>
    </section>

    <!-- INSCRIÇÃO -->
    <section id="inscricao" style="margin-top:26px">
      <h2 class="section-title">Reserve seu lugar — é grátis</h2>
      <div class="form-card" role="form" aria-label="Formulário de inscrição" style="margin-top:12px">
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
            <div class="note">Você receberá confirmação e lembretes por WhatsApp.</div>
            <button type="submit" class="btn btn-primary">Confirmar inscrição</button>
          </div>
        </form>
      </div>
      <p style="text-align:center;color:var(--muted);font-size:13px;margin-top:10px">Ao enviar você aceita receber mensagens relacionadas ao evento.</p>
    </section>

    <footer>
      © 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”
    </footer>
  </div>

  <script>
    // FAQ: accessible toggle (um aberto por vez)
    (function(){
      const items = Array.from(document.querySelectorAll('.faq-item'));
      items.forEach(item=>{
        const q = item.querySelector('.faq-q');
        const a = item.querySelector('.faq-a');
        q.addEventListener('click', ()=> toggle(item));
        q.addEventListener('keydown', (e)=> { if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(item); }});
        function toggle(current){
          const isOpen = current.classList.toggle('open');
          items.forEach(i => { if(i!==current) i.classList.remove('open'); });
        }
      });
    })();

    // Form opens WhatsApp with message - altere waNumber para o número oficial (formato +5511...)
    function handleSignup(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const wa = document.getElementById('wa').value.trim();
      const waNumber = '+55419998110445'; // <<----- substitua pelo número oficial (internacional)
      let msg = `Quero participar do workshop "Antes de virar o ano, quero estar em paz comigo." - Nome: ${nome}`;
      if(email) msg += `; Email: ${email}`;
      if(wa) msg += `; WhatsApp: ${wa}`;
      msg += ' — Inscrição via site.';
      const encoded = encodeURIComponent(msg);
      const url = `https://wa.me/${waNumber.replace(/\D/g,'')}?text=${encoded}`;
      window.open(url, '_blank');
      return false;
    }
  </script>
</body>
</html>
