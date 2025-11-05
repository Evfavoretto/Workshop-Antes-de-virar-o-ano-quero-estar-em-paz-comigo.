<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <meta name="description" content="Workshop — Dias 2, 3 e 4 de dezembro • 20h. Três noites para encerrar 2025 com leveza e entrar em 2026 com mais paz." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    /* caso GitHub Pages adicione header automático, tentamos ocultar */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --blue-1:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --deep:#112131;
      --muted:#5A6571;
      --card:#FFFFFF;
      --glass: rgba(15,76,129,0.06);
      --radius:18px;
      --hero-title: clamp(40px, 7.5vw, 110px); /* um pouco menor que antes */
      --final-title: clamp(32px, 4.8vw, 48px);
      --final-sub: clamp(32px, 6.5vw, 72px); /* destaque grande no final */
      --easing: cubic-bezier(.2,.9,.3,1);
      --shadow-lg: 0 30px 60px rgba(15,76,129,0.08);
      --whatsapp-group: 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:var(--deep);-webkit-font-smoothing:antialiased;line-height:1.55;
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(11,76,129,0.04), transparent 6%),
        radial-gradient(900px 500px at 95% 90%, rgba(184,225,255,0.03), transparent 8%),
        linear-gradient(180deg,var(--blue-1), #FFFFFF 80%);
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}

    /* Topbar simples */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:10px 0;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--blue-2),#89CFFD);
      display:flex;align-items:center;justify-content:center;color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:20px;box-shadow:var(--shadow-lg)
    }
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO - quadro branco maior e título levemente menor */
    .hero{
      position:relative;border-radius:20px;padding:64px 36px; /* aumentei padding para expandir o quadro branco */
      background:linear-gradient(180deg, rgba(255,255,255,0.98), rgba(255,255,255,0.96));
      box-shadow:var(--shadow-lg);margin:18px 0 28px;min-height:320px;
      display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;
    }
    @media(max-width:980px){ .hero{grid-template-columns:1fr;padding:40px 20px} .hero-right{order:-1} }

    /* palavra de fundo 'WORKSHOP' reduzida e menos opaca */
    .hero::before{
      content:"WORKSHOP";
      position:absolute;left:6%;top:6%;
      font-family:'Playfair Display',serif;font-weight:800;
      font-size:clamp(64px,14vw,180px); /* reduzido */
      color:rgba(15,76,129,0.04); /* menos opaco */
      letter-spacing:0.06em;pointer-events:none;user-select:none;z-index:0;
      transform:translateY(-6%);
    }

    /* Removemos o kicker "Workshop Gratuito" (não aparece) */

    .title{
      margin:0;font-family:'Playfair Display',serif;font-size:var(--hero-title);line-height:0.95;color:var(--blue-deep);
      position:relative;z-index:2;letter-spacing:-0.01em;
    }
    .title-sub{margin-top:12px;color:var(--muted);font-size:18px;max-width:760px;position:relative;z-index:2}
    .underline{width:240px;height:12px;border-radius:999px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));margin-top:18px;position:relative;z-index:2}

    .hero-ctas{display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;position:relative;z-index:2}
    .btn{border-radius:12px;padding:14px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0;transition:transform .12s var(--easing)}
    .btn-primary{background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;box-shadow:0 12px 36px rgba(15,76,129,0.12)}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.08);color:var(--muted)}

    .hero-right{background:var(--card);padding:20px;border-radius:14px;border:1px solid var(--glass);box-shadow:0 12px 30px rgba(0,0,0,0.04);position:relative;z-index:2}
    .meta-small{font-size:13px;color:var(--muted);margin-bottom:6px}
    .meta-strong{font-weight:800;color:var(--deep);font-size:20px;margin-bottom:8px}

    /* sections */
    section{padding:44px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:24px;margin:0 0 12px;color:var(--deep)}

    .grid-3{display:grid;gap:18px;margin-top:12px}
    @media(min-width:860px){ .grid-3{grid-template-columns:repeat(3,1fr)} }
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 30px rgba(0,0,0,0.03)}
    .card h3{font-size:16px;margin:0 0 8px;color:var(--blue-deep)} .card p{color:var(--muted);line-height:1.6;white-space:pre-line}

    /* mentor */
    .mentor{display:flex;gap:18px;align-items:center;padding:18px;border-radius:12px;background:var(--card);border:1px solid var(--glass);box-shadow:0 12px 36px rgba(0,0,0,0.04)}
    .mentor img{width:220px;height:220px;border-radius:12px;object-fit:cover}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:20px;color:var(--blue-deep)}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    /* floating CTA */
    .float-cta{position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));padding:12px 16px;border-radius:12px;color:#fff;font-weight:800;box-shadow:0 20px 46px rgba(15,76,129,0.22);z-index:1000;border:0;cursor:pointer}

    /* FINAL HIGHLIGHT BAR (azul escuro com texto branco) */
    .final-highlight{
      margin-top:32px;border-radius:12px;overflow:hidden;box-shadow:0 20px 60px rgba(15,76,129,0.08);
      background:linear-gradient(180deg,var(--blue-deep),#0A3C66);
      color:#fff;padding:42px 28px;display:flex;align-items:center;gap:28px;flex-wrap:wrap;
    }
    .final-left{flex:1;min-width:320px}
    .final-tag{font-weight:800;letter-spacing:.08em;color:rgba(255,255,255,0.9);font-family:'Playfair Display',serif;font-size:var(--final-title);margin:0 0 8px}
    .final-main{font-family:'Playfair Display',serif;font-size:var(--final-sub);margin:0;line-height:1;color:#fff}
    .final-cta{margin-top:16px}
    .final-cta .btn{background:#fff;color:var(--blue-deep;padding:12px 18px;border-radius:12px;font-weight:800;border:0}
    .final-desc{opacity:0.95;margin-top:10px;color:rgba(255,255,255,0.9)}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:13px;margin-top:22px}

    /* focus */
    :focus{outline:3px solid rgba(11,76,129,0.12);outline-offset:3px;border-radius:8px}

    @media(max-width:760px){
      .hero{grid-template-columns:1fr}
      .mentor{flex-direction:column;align-items:flex-start}
      .mentor img{width:100%;height:320px}
      .final-main{font-size:clamp(26px,8vw,40px)}
      .hero::before{left:-6%;top:4%;font-size:clamp(56px,24vw,120px)}
    }
  </style>
</head>
<body>
  <div class="wrap" role="document">

    <!-- top -->
    <header class="topbar" role="banner" aria-label="Cabeçalho">
      <div class="brand">
        <div class="logo" aria-hidden="true">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif;color:var(--blue-deep)">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop • 3 noites</div>
        </div>
      </div>
      <nav aria-label="Navegação">
        <a href="#noites">Noites</a>
        <a href="#mentor">Mentor</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div>
        <!-- kicker removido conforme pedido -->
        <h1 id="hero-title" class="title">Antes de virar o ano, quero estar em paz comigo.</h1>

        <div class="underline" aria-hidden="true"></div>

        <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

        <div class="hero-ctas" role="group" aria-label="Ações principais">
          <button class="btn btn-primary" id="decidedBtn">Já tomei minha decisão</button>
          <button class="btn btn-primary" id="inscNowBtn">Quero me inscrever agora</button>
          <button class="btn btn-alt" id="doubtBtn">Ainda estou com dúvida</button>
        </div>
      </div>

      <aside class="hero-right" aria-label="Resumo do evento">
        <div class="meta-small">Próximo encontro</div>
        <div class="meta-strong">02 Dez • 20h</div>
        <div style="height:1px;background:var(--glass);border-radius:6px;margin:10px 0"></div>
        <div class="meta-small">Duração</div>
        <div style="font-weight:800;color:var(--deep)">60–75 minutos / noite</div>
        <div style="margin-top:10px" class="meta-small">Gratuito — inscrição necessária</div>
        <div style="margin-top:12px">
          <button class="btn btn-primary" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Reservar meu lugar</button>
        </div>
      </aside>
    </main>

    <!-- NOITES -->
    <section id="noites" aria-labelledby="noites-title">
      <h2 id="noites-title" class="section-title">As três noites</h2>
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

    <!-- MENTOR -->
    <section id="mentor" aria-labelledby="mentor-title">
      <h2 id="mentor-title" class="section-title">Conheça seu mentor</h2>
      <div class="mentor">
        <img src="Mentor.jpeg" alt="Foto de Evandro Favoretto — mentor do workshop" />
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
        </div>
      </div>
    </section>

    <!-- INSCRIÇÃO -->
    <section id="inscricao" aria-labelledby="insc-title">
      <h2 id="insc-title" class="section-title">Investimento & inscrição</h2>
      <div style="display:flex;gap:18px;align-items:flex-start;flex-wrap:wrap;margin-top:12px">
        <div style="min-width:260px" class="card">
          <strong style="display:block;font-size:18px;color:var(--blue-deep)">Investimento</strong>
          <p style="margin:8px 0;color:var(--muted)">Gratuito — inscrição necessária. (Vagas limitadas)</p>
          <div style="height:1px;background:var(--glass);border-radius:6px;margin:10px 0"></div>
          <strong style="display:block;color:var(--deep);margin-bottom:8px">Suporte</strong>
          <p style="color:var(--muted);margin:0">Dúvidas via WhatsApp — suporte antes e durante o workshop.</p>
        </div>

        <div style="flex:1;min-width:360px">
          <div class="card" style="padding:18px">
            <form id="signup" onsubmit="return handleSignup(event)" autocomplete="on">
              <div style="display:grid;gap:10px;grid-template-columns:1fr 260px">
                <div><label for="nome" style="display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700">Nome completo</label><input id="nome" name="nome" type="text" placeholder="Ex: Ana Silva" required style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--deep);font-size:15px"/></div>
                <div><label for="wa" style="display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700">WhatsApp (com DDI)</label><input id="wa" name="wa" type="text" placeholder="+55 11 9xxxx-xxxx" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--deep);font-size:15px"/></div>
              </div>

              <div style="margin-top:12px"><label for="email" style="display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700">E-mail (opcional)</label><input id="email" name="email" type="email" placeholder="seu@exemplo.com" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--deep);font-size:15px"/></div>

              <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;margin-top:12px">
                <div style="color:var(--muted);font-size:13px">Você receberá confirmação e lembretes por WhatsApp.</div>
                <div style="display:flex;gap:8px">
                  <button class="btn btn-primary" type="submit">Quero me inscrever agora</button>
                  <button type="button" class="btn btn-alt" id="moreInfoInline">Preciso de mais informações</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>

      <div style="margin-top:12px">
        <button class="btn btn-alt" id="contactSupport">Ainda estou com dúvida — falar com suporte</button>
      </div>
    </section>

    <!-- FINAL HIGHLIGHT -->
    <section aria-hidden="false">
      <div class="final-highlight" role="region" aria-label="Destaque final">
        <div class="final-left">
          <div class="final-tag">WORKSHOP — A VIDA QUE EU QUERO VIVER</div>
          <div class="final-main">Antes de virar o ano, quero estar em paz comigo.</div>
          <div class="final-desc">Três noites práticas (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz.</div>
        </div>

        <div style="min-width:220px;display:flex;flex-direction:column;gap:12px;align-items:flex-end">
          <button class="btn" style="background:#fff;color:var(--blue-deep;border-radius:12px;padding:12px 18px;font-weight:800;border:0" id="finalJoinBtn">Entrar no grupo</button>
          <div style="color:rgba(255,255,255,0.9);font-size:13px;text-align:right">Clique para entrar no grupo e garantir seu lugar.</div>
        </div>
      </div>
    </section>

    <footer>
      © 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”
    </footer>
  </div>

  <!-- floating CTA -->
  <button class="float-cta" id="floatBtn" aria-label="Entrar no grupo do WhatsApp">Entrar no grupo</button>

  <script>
    // URL do grupo (já configurada)
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';

    // CTAs que abrem o grupo
    document.getElementById('decidedBtn').addEventListener('click', ()=> window.open(whatsappGroupUrl,'_blank'));
    document.getElementById('inscNowBtn').addEventListener('click', ()=> window.open(whatsappGroupUrl,'_blank'));
    document.getElementById('floatBtn').addEventListener('click', ()=> window.open(whatsappGroupUrl,'_blank'));
    document.getElementById('finalJoinBtn').addEventListener('click', ()=> window.open(whatsappGroupUrl,'_blank'));

    // outros botões
    document.getElementById('doubtBtn').addEventListener('click', ()=> { document.querySelector('section#inscricao').scrollIntoView({behavior:'smooth'}); });
    document.getElementById('moreInfoInline').addEventListener('click', ()=> { document.querySelector('#noites').scrollIntoView({behavior:'smooth'}); });
    document.getElementById('contactSupport').addEventListener('click', ()=> openWhatsAppSupport());

    // formulário: abre conversa direta (opcional) - altere o número se quiser usar esse fluxo
    function handleSignup(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const wa = document.getElementById('wa').value.trim();
      // se preferir, mudar para abrir o grupo em vez de enviar mensagem individual:
      // window.open(whatsappGroupUrl,'_blank'); return false;

      const waNumber = '55419998110445'; // <--- troque caso queira enviar mensagem direta a esse número
      let msg = `Quero participar do workshop "Antes de virar o ano, quero estar em paz comigo." - Nome: ${nome}`;
      if(email) msg += `; Email: ${email}`;
      if(wa) msg += `; WhatsApp: ${wa}`;
      const encoded = encodeURIComponent(msg + ' — Inscrição via site.');
      window.open(`https://wa.me/${waNumber}?text=${encoded}`,'_blank');
      return false;
    }
    document.getElementById('signup').addEventListener('submit', handleSignup);

    function openWhatsAppSupport(){
      const waNumber = '55419998110445'; // troque se quiser outro número para suporte
      const msg = encodeURIComponent('Olá — preciso de mais informações sobre o workshop "Antes de virar o ano, quero estar em paz comigo."');
      window.open(`https://wa.me/${waNumber}?text=${msg}`,'_blank');
    }
  </script>
</body>
</html>
