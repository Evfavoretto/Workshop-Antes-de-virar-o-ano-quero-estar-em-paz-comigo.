<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop gratuito</title>
  <meta name="description" content="Workshop gratuito — Dias 2, 3 e 4 de dezembro às 20h. Três noites para encerrar 2025 com leveza e entrar em 2026 em paz." />
  <meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
  <meta property="og:description" content="2, 3 e 4 de dezembro • 20h — três noites para encerrar 2025 com leveza e se reencontrar antes de 2026." />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
  <meta name="twitter:card" content="summary_large_image" />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --blue-1:#EAF4FB;
      --blue-2:#B8E1FF;
      --accent:#0F4C81;
      --deep:#112131;
      --muted:#5A6571;
      --card:#FFFFFF;
      --glass: rgba(15,76,129,0.06);
      --radius:16px;
      --hero-title: clamp(48px, 9.6vw, 140px);
      --underline-h: 12px;
      --easing: cubic-bezier(.2,.9,.3,1);
      --shadow-lg: 0 30px 60px rgba(15,76,129,0.08);
    }

    *{box-sizing:border-box}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:var(--deep);background:linear-gradient(180deg,var(--blue-1),#FFFFFF 80%);
      line-height:1.55;-webkit-font-smoothing:antialiased;
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}

    .logo{
      width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--blue-2),#89CFFD);
      display:flex;align-items:center;justify-content:center;color:#fff;
      font-family:'Playfair Display',serif;font-weight:700;font-size:20px;box-shadow:var(--shadow-lg)
    }

    /* HERO */
    .hero{
      position:relative;border-radius:18px;padding:48px 28px 56px;background:rgba(255,255,255,0.9);
      box-shadow:var(--shadow-lg);margin:18px 0 28px;
      display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;
    }
    @media(max-width:980px){ .hero{grid-template-columns:1fr;padding:36px} .hero-right{order:-1} }

    .hero::before{
      content:"WORKSHOP";
      position:absolute;left:6%;top:6%;
      font-family:'Playfair Display',serif;
      font-weight:800;font-size:clamp(80px,18vw,260px);
      color:rgba(15,76,129,0.06);letter-spacing:0.06em;pointer-events:none;user-select:none;
    }

    .kicker{display:inline-block;padding:6px 12px;border-radius:999px;background:rgba(15,76,129,0.08);color:var(--accent);font-weight:800;font-size:13px;letter-spacing:.05em}
    h1.title{margin:0;font-family:'Playfair Display',serif;font-size:var(--hero-title);line-height:0.9;color:var(--accent);position:relative;z-index:2;letter-spacing:-0.01em;}
    .title-sub{margin-top:10px;color:var(--muted);font-size:18px;max-width:760px;position:relative;z-index:2}
    .underline{width:220px;height:var(--underline-h);border-radius:999px;background:linear-gradient(90deg,var(--accent),var(--blue-2));margin-top:18px;position:relative;z-index:2;}

    .btn{border-radius:12px;padding:14px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0;}
    .btn-primary{background:linear-gradient(90deg,var(--accent),var(--blue-2));color:#fff;box-shadow:0 12px 36px rgba(15,76,129,0.18);}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.1);color:var(--muted)}

    .hero-ctas{display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;}
    .hero-right{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 12px 30px rgba(0,0,0,0.04)}
    .meta-small{font-size:13px;color:var(--muted);}
    .meta-strong{font-weight:800;color:var(--deep);font-size:20px;margin-bottom:8px}

    .float-cta{position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--accent),var(--blue-2));padding:12px 16px;border-radius:12px;color:#fff;font-weight:800;box-shadow:0 20px 46px rgba(15,76,129,0.25);z-index:1000;border:0;cursor:pointer}

    section{padding:44px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:24px;margin:0 0 12px;color:var(--deep)}
    .grid-3{display:grid;gap:18px;margin-top:12px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 30px rgba(0,0,0,0.03)}
    .card h3{font-size:16px;margin:0 0 8px;color:var(--accent)} .card p{color:var(--muted);line-height:1.6;white-space:pre-line}

    .mentor{display:flex;gap:18px;align-items:center;padding:18px;border-radius:12px;background:var(--card);border:1px solid var(--glass);box-shadow:0 12px 36px rgba(0,0,0,0.04)}
    .mentor img{width:220px;height:220px;border-radius:12px;object-fit:cover}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:20px;color:var(--accent)}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:13px}
  </style>
</head>
<body>
  <div class="wrap">

    <header class="topbar">
      <div class="brand">
        <div class="logo">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif;color:var(--accent)">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>
    </header>

    <main class="hero">
      <div>
        <div class="kicker">Workshop Gratuito</div>
        <h1 class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline"></div>
        <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

        <div class="hero-ctas">
          <button class="btn btn-primary" onclick="window.open('https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp','_blank')">Já tomei minha decisão</button>
          <button class="btn btn-primary" onclick="window.open('https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp','_blank')">Quero me inscrever agora</button>
        </div>
      </div>

      <aside class="hero-right">
        <div class="meta-small">Próximo encontro</div>
        <div class="meta-strong">02 Dez • 20h</div>
        <div class="meta-small">Duração: 60–75 minutos / noite</div>
        <div class="meta-small" style="margin-top:10px">Gratuito — inscrição necessária</div>
      </aside>
    </main>

    <section id="noites">
      <h2 class="section-title">As três noites</h2>
      <div class="grid-3">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.</p></article>

        <article class="card"><h3>💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h3><p>Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.</p></article>

        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.</p></article>
      </div>
    </section>

    <section id="mentor">
      <h2 class="section-title">Conheça seu mentor</h2>
      <div class="mentor">
        <img src="Mentor.jpeg" alt="Foto de Evandro Favoretto — mentor do workshop" />
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
        </div>
      </div>
    </section>

    <footer>
      © 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”
    </footer>
  </div>

  <button class="float-cta" onclick="window.open('https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp','_blank')">Entrar no grupo</button>
</body>
</html>
