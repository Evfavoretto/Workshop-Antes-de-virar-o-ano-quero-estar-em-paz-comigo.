<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop gratuito</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro, às 20h) para encerrar 2025 com leveza e começar 2026 em paz." />
  <meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
  <meta property="og:description" content="Três noites para encerrar 2025 com leveza e se reencontrar consigo mesma. 2, 3 e 4 de dezembro • 20h" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
  <meta name="twitter:card" content="summary_large_image" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    header, .page-header, .site-header, .project-name, .project-tagline { display: none !important; }

    :root{
      /* === PALETA PÊSSEGO === */
      --bg:#FFF9F6;
      --panel:#FFFFFF;
      --ink:#2B1811;
      --muted:#7A6A63;
      --peach:#FFB195;
      --rose:#F98B7B;
      --sand:#F6E3D6;
      --accent:#E2785E;
      --radius:16px;
      --maxw:1200px;
      --hero-size:clamp(44px,8vw,110px);
      --easing:cubic-bezier(.25,.9,.3,1);
      --shadow-lg:0 30px 60px rgba(43,24,17,0.07);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      background:linear-gradient(180deg,var(--bg),var(--sand));
      color:var(--ink);
      -webkit-font-smoothing:antialiased;
      line-height:1.6;
    }
    .wrap{max-width:var(--maxw);margin:0 auto;padding:36px 24px}

    /* === TOPBAR === */
    .topbar{display:flex;justify-content:space-between;align-items:center;padding:10px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--peach),var(--rose));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;font-family:'Playfair Display',serif;font-size:20px;box-shadow:0 8px 28px rgba(0,0,0,0.1)}
    nav a{color:var(--muted);margin-left:20px;text-decoration:none;font-weight:600}

    /* === HERO === */
    .hero{
      margin:20px 0 40px;border-radius:22px;padding:56px;
      background:linear-gradient(160deg,rgba(255,182,155,0.08),rgba(249,139,123,0.06));
      box-shadow:var(--shadow-lg);
      display:grid;grid-template-columns:1fr 380px;gap:28px;align-items:center;
    }
    @media(max-width:980px){.hero{grid-template-columns:1fr;padding:36px}}

    .hero-kicker{font-size:13px;color:var(--accent);font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:8px}
    .hero-title{font-family:'Playfair Display',serif;font-size:var(--hero-size);line-height:0.95;color:var(--ink);margin:0 0 16px}
    .hero-sub{color:var(--muted);font-size:18px;max-width:780px}
    .cta-row{display:flex;gap:14px;margin-top:24px;flex-wrap:wrap}
    .btn{border-radius:12px;padding:14px 22px;font-weight:700;cursor:pointer;border:0;transition:transform .18s var(--easing),box-shadow .18s var(--easing)}
    .btn:active{transform:translateY(1px)}
    .btn-primary{background:linear-gradient(90deg,var(--peach),var(--rose));color:#fff;box-shadow:0 10px 30px rgba(249,139,123,0.3)}
    .btn-primary:hover{box-shadow:0 12px 36px rgba(249,139,123,0.4);transform:translateY(-2px)}
    .btn-secondary{background:transparent;border:1px solid rgba(0,0,0,0.08);color:var(--muted)}

    .hero-right{background:var(--panel);padding:20px;border-radius:14px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 14px 36px rgba(0,0,0,0.04)}
    .meta-small{font-size:13px;color:var(--muted);margin-bottom:6px}
    .meta-strong{font-weight:800;color:var(--ink);font-size:20px;margin-bottom:8px}

    /* === SEÇÕES === */
    section{padding:40px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:28px;margin:0 0 16px;color:var(--ink);text-align:center}

    /* === PROBLEMA / SOLUÇÃO === */
    .ps{display:grid;gap:20px;margin-top:20px}
    @media(min-width:900px){.ps{grid-template-columns:1fr 1fr}}
    .ps-card{background:var(--panel);padding:28px;border-radius:14px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 28px rgba(0,0,0,0.03)}
    .ps-card h3{margin:0 0 12px;font-size:20px;color:var(--accent)}
    .ps-card p{color:var(--muted);font-size:16px;white-space:pre-line}

    /* === TRÊS NOITES === */
    .grid-3{display:grid;gap:18px;margin-top:20px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--panel);padding:20px;border-radius:12px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 8px 20px rgba(0,0,0,0.03)}
    .card h4{font-size:18px;margin:0 0 10px;color:var(--accent)}
    .card p{color:var(--muted);white-space:pre-line;line-height:1.55}

    /* === BENEFÍCIOS === */
    .benefits{display:flex;flex-wrap:wrap;gap:12px;justify-content:center;margin-top:18px}
    .benefit{background:var(--panel);border-radius:10px;padding:14px 16px;border:1px solid rgba(0,0,0,0.04);display:flex;gap:12px;align-items:center;min-width:220px;box-shadow:0 6px 18px rgba(0,0,0,0.02)}
    .badge{width:42px;height:42px;border-radius:10px;background:linear-gradient(90deg,var(--peach),var(--rose));color:#fff;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:16px}

    /* === FAQ === */
    .faq{display:grid;gap:12px;max-width:880px;margin:0 auto}
    .faq-item{background:var(--panel);border:1px solid rgba(0,0,0,0.04);border-radius:12px;overflow:hidden;box-shadow:0 8px 22px rgba(0,0,0,0.03)}
    .faq-q{padding:16px 18px;cursor:pointer;display:flex;align-items:center;justify-content:space-between}
    .faq-q h5{margin:0;font-size:16px;color:var(--ink)}
    .faq-a{max-height:0;overflow:hidden;padding:0 18px;transition:max-height .3s var(--easing)}
    .faq-item.open .faq-a{max-height:400px;padding:14px 18px}
    .faq-a p{margin:0;color:var(--muted)}

    /* === FORM === */
    .form-card{max-width:720px;margin:20px auto;padding:24px;border-radius:14px;background:var(--panel);border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 28px rgba(0,0,0,0.03)}
    .form-row{display:grid;gap:12px}
    @media(min-width:720px){.form-row{grid-template-columns:1fr 260px}}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700}
    input{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(0,0,0,0.04);background:transparent;color:var(--ink);font-size:15px;outline:none}
    .form-foot{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-top:14px}
    .note{font-size:13px;color:var(--muted)}

    footer{margin-top:36px;text-align:center;color:var(--muted);font-size:14px}
  </style>
</head>
<body>
  <div class="wrap">
    <header class="topbar">
      <div class="brand">
        <div class="logo" aria-hidden="true">🌿</div>
        <div>
          <div style="font-family:'Playfair Display',serif;font-weight:700">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>
      <nav>
        <a href="#problema">Problema</a>
        <a href="#noites">Noites</a>
        <a href="#faq">FAQ</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <main class="hero" aria-labelledby="hero-title">
      <div>
        <div class="hero-kicker">Workshop Gratuito</div>
        <h1 id="hero-title" class="hero-title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="hero-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar antes de entrar em 2026.</div>
        <div class="cta-row">
          <button class="btn btn-primary" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Quero participar</button>
          <button class="btn btn-secondary" onclick="document.getElementById('noites').scrollIntoView({behavior:'smooth'})">Ver programação</button>
        </div>
      </div>
      <aside class="hero-right">
        <div class="meta-small">Próximo encontro</div>
        <div class="meta-strong">02 Dez • 20h</div>
        <div class="meta-small">Duração</div>
        <div style="font-weight:700;color:var(--ink)">60–75 minutos / noite</div>
        <div class="meta-small" style="margin-top:10px">Gratuito — inscrição necessária</div>
      </aside>
    </main>

    <section id="problema">
      <h2 class="section-title">O problema que a maioria enfrenta</h2>
      <div class="ps">
        <div class="ps-card">
          <h3>Você não está sozinha nisso</h3>
          <p>Muitas pessoas chegam ao fim do ano carregando cansaço emocional, culpa por não ter sido “suficiente”, mágoas antigas e a sensação de que o tempo passou sem que tenham cuidado de si.
Isso gera ansiedade, noites sem sono e um peso constante que bloqueia um recomeço leve e consciente.</p>
        </div>
        <div class="ps-card">
          <h3>A solução — por onde começar</h3>
          <p>Entrar em um espaço guiado, curto e seguro onde você possa:
• dar nome ao que pesa;
• aprender práticas para soltar com cuidado;
• transformar experiência em intenção para o próximo ciclo.

O Workshop oferece três noites práticas e acolhedoras para fechar 2025 e chegar em 2026 mais leve.</p>
        </div>
      </div>
    </section>

    <section id="noites">
      <h2 class="section-title">As três noites</h2>
      <div class="grid-3">
        <article class="card"><h4>🌙 1ª Noite — O peso que ainda carrego</h4><p>Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.</p></article>
        <article class="card"><h4>💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h4><p>Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.</p></article>
        <article class="card"><h4>✨ 3ª Noite — O recomeço que nasce da paz</h4><p>Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.</p></article>
      </div>
    </section>

    <section id="beneficios">
      <h2 class="section-title">O que você vai levar</h2>
      <div class="benefits">
        <div class="benefit"><div class="badge">1</div><div><strong>Clareza</strong><div style="color:var(--muted)">sobre o que soltar</div></div></div>
        <div class="benefit"><div class="badge">2</div><div><strong>Práticas</strong><div style="color:var(--muted)">para autocuidado real</div></div></div>
        <div class="benefit"><div class="badge">3</div><div><strong>Ritual</strong><div style="color:var(--muted)">para o novo ciclo</div></div></div>
      </div>
    </section>

    <section id="faq">
      <h2 class="section-title">Perguntas frequentes</h2>
      <div class="faq">
        <div class="faq-item"><div class="faq-q"><h5>Preciso participar das três noites?</h5></div><div class="faq-a"><p>Acompanhar as três noites traz continuidade ao processo; ainda assim, é possível participar de noites avulsas se necessário.</p></div></div>
        <div class="faq-item"><div class="faq-q"><h5>Haverá gravação?</h5></div><div class="faq-a"><p>As gravações podem ser disponibilizadas por tempo limitado. Inscreva-se para receber o link por WhatsApp.</p></div></div>
        <div class="faq-item"><div class="faq-q"><h5>É gratuito?</h5></div><div class="faq-a"><p>Sim — totalmente gratuito. Pedimos apenas presença e abertura para a experiência.</p></div></div>
      </div>
    </section>

    <section id="inscricao">
      <h2 class="section-title">Reserve seu lugar — é grátis</h2>
      <div class="form-card">
        <form id="signup" onsubmit="return handleSignup(event)">
          <div class="form-row">
            <div><label for="nome">Nome completo</label><input id="nome" name="nome" type="text" required placeholder="Ex: Ana Silva"/></div>
            <div><label for="wa">WhatsApp (com DDI)</label><input id="wa" name="wa" type="text" placeholder="+55 11 9xxxx-xxxx"/></div>
          </div>
          <div style="margin-top:12px"><label for="email">E-mail (opcional)</label><input id="email" name="email" type="email" placeholder="seu@exemplo.com"/></div>
          <div class="form-foot"><div class="note">Confirmação e lembretes por WhatsApp.</div><button class="btn btn-primary" type="submit">Confirmar inscrição</button></div>
        </form>
      </div>
      <p style="text-align:center;color:var(--muted);font-size:13px;margin-top:10px">Ao enviar você aceita receber mensagens relacionadas ao evento.</
