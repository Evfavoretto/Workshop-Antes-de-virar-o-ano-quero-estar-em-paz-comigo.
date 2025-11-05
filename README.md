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
    /* remove cabeçalho do GitHub Pages, se presente */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --bg-1:#FFF7F3;
      --peach-1:#FFD6C2;
      --peach-2:#FF9B73;
      --deep:#2B1811;
      --muted:#7A6A63;
      --card:#FFFFFF;
      --glass: rgba(43,31,25,0.06);
      --radius:16px;
      --hero-title: clamp(48px, 9.6vw, 140px);   /* título grande */
      --underline-h: 12px;
      --easing: cubic-bezier(.2,.9,.3,1);
      --shadow-lg: 0 30px 60px rgba(43,31,25,0.08);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:var(--deep);-webkit-font-smoothing:antialiased;line-height:1.55;
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(255,155,110,0.06), transparent 6%),
        radial-gradient(900px 500px at 95% 90%, rgba(255,200,170,0.05), transparent 8%),
        linear-gradient(180deg,var(--bg-1), #FFF0E8 60%);
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}

    /* topbar */
    .topbar{display:flex;align-items:center;justify-content:space-between;padding:10px 0;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--peach-1),var(--peach-2));
      display:flex;align-items:center;justify-content:center;color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:20px;box-shadow:var(--shadow-lg)
    }
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO - layout com grande "WORKSHOP" no fundo */
    .hero{
      position:relative;overflow:visible;border-radius:18px;padding:48px 28px 56px;background:linear-gradient(180deg, rgba(255,255,255,0.95), rgba(255,250,247,0.98));
      box-shadow:var(--shadow-lg);margin:18px 0 28px;
      display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;
    }
    @media(max-width:980px){ .hero{grid-template-columns:1fr;padding:36px} .hero-right{order:-1} }

    /* GIGANTE BACKWORD */
    .hero::before{
      content:"WORKSHOP";
      position:absolute;left:6%;top:6%;
      font-family:'Playfair Display',serif;
      font-weight:800;
      font-size:clamp(80px,18vw,260px);
      color:rgba(255,150,110,0.06);
      letter-spacing:0.06em;
      pointer-events:none;
      user-select:none;
      transform:translateY(-6%);
    }

    .kicker{display:inline-block;padding:6px 12px;border-radius:999px;background:rgba(255,127,94,0.08);color:var(--peach-2);font-weight:800;font-size:13px;letter-spacing:.05em}
    h1.title{
      margin:0;font-family:'Playfair Display',serif;font-size:var(--hero-title);line-height:0.9;color:var(--peach-2);
      position:relative;z-index:2; /* acima do 'WORKSHOP' */
      letter-spacing:-0.01em;
    }
    .title-sub{margin-top:10px;color:var(--muted);font-size:18px;max-width:760px;position:relative;z-index:2}

    .underline{
      width:220px;height:var(--underline-h);border-radius:999px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));
      margin-top:18px;position:relative;z-index:2;transform-origin:left;animation:grow .9s var(--easing) both;
    }
    @keyframes grow{from{transform:scaleX(0)}to{transform:scaleX(1)}}

    .hero-ctas{display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;position:relative;z-index:2}
    .btn{border-radius:12px;padding:14px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0;transition:transform .16s var(--easing),box-shadow .16s var(--easing)}
    .btn-primary{background:linear-gradient(90deg,var(--peach-2),var(--peach-1));color:#fff;box-shadow:0 12px 36px rgba(255,127,94,0.18)}
    .btn-alt{background:transparent;border:1px solid rgba(43,31,25,0.06);color:var(--muted)}

    .hero-right{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 12px 30px rgba(0,0,0,0.04);position:relative;z-index:2}
    .meta-small{font-size:13px;color:var(--muted);margin-bottom:6px}
    .meta-strong{font-weight:800;color:var(--deep);font-size:20px;margin-bottom:8px}

    /* floating CTA visível em mobile */
    .float-cta{position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));padding:12px 16px;border-radius:12px;color:#fff;font-weight:800;box-shadow:0 20px 46px rgba(255,127,94,0.22);z-index:1000}

    /* SECTIONS */
    section{padding:44px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:24px;margin:0 0 12px;color:var(--deep)}

    /* HOW IT WORKS */
    .steps{display:grid;gap:14px}
    @media(min-width:900px){ .steps{grid-template-columns:repeat(3,1fr)} }
    .step{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 28px rgba(0,0,0,0.03)}
    .step h4{margin:0 0 8px;color:var(--peach-2)} .step p{color:var(--muted);margin:0}

    /* 3 NOITES */
    .grid-3{display:grid;gap:18px;margin-top:12px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 30px rgba(0,0,0,0.03)}
    .card h3{font-size:16px;margin:0 0 8px;color:var(--peach-2)} .card p{color:var(--muted);line-height:1.6;white-space:pre-line}

    /* WHY / WHO */
    .cols{display:grid;gap:14px}
    @media(min-width:900px){ .cols{grid-template-columns:1fr 1fr} }
    .list{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass)}

    /* BENEFÍCIOS */
    .benefits{display:flex;flex-wrap:wrap;gap:12px;margin-top:12px}
    .benefit{background:var(--card);padding:12px 14px;border-radius:10px;border:1px solid var(--glass);display:flex;gap:12px;align-items:center;min-width:220px}
    .badge{width:44px;height:44px;border-radius:10px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800}

    /* MENTOR */
    .mentor{display:flex;gap:18px;align-items:center;padding:18px;border-radius:12px;background:linear-gradient(180deg,#fff,#fff);border:1px solid var(--glass);box-shadow:0 12px 36px rgba(0,0,0,0.04)}
    .mentor img{width:220px;height:220px;border-radius:12px;object-fit:cover;border:2px solid rgba(0,0,0,0.04)}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:20px}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    /* TESTIMONIALS */
    .testimonials{display:grid;gap:12px}
    .test{background:var(--card);padding:16px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 8px 22px rgba(0,0,0,0.03)}
    .test p{margin:0;color:var(--muted)} .test .who{margin-top:10px;font-weight:700;color:var(--deep)}

    /* FORM */
    .form-card{max-width:760px;margin:12px auto;padding:18px;border-radius:12px;background:var(--card);border:1px solid var(--glass);box-shadow:0 12px 34px rgba(0,0,0,0.04)}
    .form-row{display:grid;gap:10px}
    @media(min-width:720px){ .form-row{grid-template-columns:1fr 260px} }
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700}
    input{width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--deep);font-size:15px;outline:none}
    .form-foot{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-top:12px}
    .small{font-size:13px;color:var(--muted)}

    /* FAQ */
    .faq{max-width:920px;margin:12px auto;display:grid;gap:12px}
    .faq-item{background:var(--card);border-radius:12px;border:1px solid var(--glass);overflow:hidden}
    .faq-q{padding:14px;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .faq-a{max-height:0;overflow:hidden;padding:0 14px;transition:max-height .34s var(--easing)}
    .faq-item.open .faq-a{max-height:420px;padding:12px 14px}
    .faq-a p{margin:0;color:var(--muted);line-height:1.6}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:13px}

    /* focus */
    a:focus,button:focus,input:focus{outline:3px solid rgba(255,127,94,0.12);outline-offset:3px;border-radius:8px}

    @media(max-width:760px){
      .hero{grid-template-columns:1fr}
      .mentor{flex-direction:column;align-items:flex-start}
      .mentor img{width:100%;height:320px}
      .hero::before{left:-6%;top:4%;font-size:clamp(60px,28vw,160px)}
    }
  </style>
</head>
<body>
  <div class="wrap" role="document">

    <!-- top -->
    <header class="topbar" role="banner" aria-label="Cabeçalho">
      <div class="brand" aria-hidden="false">
        <div class="logo" aria-hidden="true">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>
      <nav aria-label="Navegação principal">
        <a href="#como">Como funciona</a>
        <a href="#noites">Noites</a>
        <a href="#mentor">Mentor</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-title">
      <div>
        <div class="kicker" aria-hidden="true">Workshop Gratuito</div>

        <!-- TÍTULO BEM GRANDE -->
        <h1 id="hero-title" class="title">Antes de virar o ano, quero estar em paz comigo.</h1>

        <div class="underline" aria-hidden="true"></div>

        <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>

        <div class="hero-ctas" role="group" aria-label="Ações principais">
          <button class="btn btn-primary" id="decidedBtn">Já tomei minha decisão</button>
          <button class="btn btn-primary" id="inscNowBtn">Quero me inscrever agora</button>
          <button class="btn btn-alt" id="doubtBtn">Ainda estou com dúvida</button>
          <button class="btn btn-alt" id="moreInfoBtn">Preciso de mais informações</button>
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

    <!-- COMO FUNCIONA -->
    <section id="como" aria-labelledby="como-title">
      <h2 id="como-title" class="section-title">Como vai funcionar</h2>
      <div class="steps" style="margin-top:12px">
        <div class="step"><h4>Inscrição</h4><p>Preencha o formulário ou use o WhatsApp. Receba confirmação e lembretes.</p></div>
        <div class="step"><h4>Encontros ao vivo</h4><p>3 noites consecutivas às 20h — práticas guiadas, reflexões e integração entre encontros.</p></div>
        <div class="step"><h4>Integração</h4><p>Exercícios práticos para aplicar entre os encontros e ritual de encerramento na 3ª noite.</p></div>
      </div>
    </section>

    <!-- 3 NOITES -->
    <section id="noites" aria-labelledby="noites-title">
      <h2 id="noites-title" class="section-title">As três noites</h2>
      <div class="grid-3" style="margin-top:12px">
        <article class="card"><h3>🌙 1ª Noite — O peso que ainda carrego</h3><p>Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.</p></article>

        <article class="card"><h3>💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h3><p>Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.</p></article>

        <article class="card"><h3>✨ 3ª Noite — O recomeço que nasce da paz</h3><p>Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.</p></article>
      </div>
    </section>

    <!-- POR QUE / PARA QUEM -->
    <section id="porque" aria-labelledby="pq-title">
      <h2 id="pq-title" class="section-title">Por que participar</h2>
      <div class="cols" style="margin-top:12px">
        <div class="list">
          <h4 style="margin-top:0;color:var(--peach-2)">É para você se...</h4>
          <ul style="color:var(--muted);line-height:1.8">
            <li>Quer clareza emocional e sistêmica para decidir com segurança.</li>
            <li>Está pronto(a) para praticar integração entre encontros.</li>
            <li>Busca um processo guiado, humano e direto ao ponto.</li>
          </ul>
        </div>
        <div class="list">
          <h4 style="margin-top:0;color:#B85E4A">Não é para você se...</h4>
          <ul style="color:var(--muted);line-height:1.8">
            <li>Procura fórmula mágica sem envolvimento pessoal.</li>
            <li>Quer resultado sem abrir espaço para sentir e compreender.</li>
            <li>Não pretende reservar ~1h durante os 3 dias.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- O QUE GANHO -->
    <section id="ganhos" aria-labelledby="ganhos-title">
      <h2 id="ganhos-title" class="section-title">O que você ganha</h2>
      <div class="benefits" style="margin-top:12px">
        <div class="benefit"><div class="badge">1</div><div style="margin-left:8px"><strong>Clareza</strong><div style="color:var(--muted)">Identificar o que pesa</div></div></div>
        <div class="benefit"><div class="badge">2</div><div style="margin-left:8px"><strong>Ferramentas</strong><div style="color:var(--muted)">Práticas para soltar</div></div></div>
        <div class="benefit"><div class="badge">3</div><div style="margin-left:8px"><strong>Ritual</strong><div style="color:var(--muted)">Fechar 2025 e abrir 2026</div></div></div>
      </div>
    </section>

    <!-- MENTOR (usar imagem enviada: Mentor.jpeg) -->
    <section id="mentor" aria-labelledby="mentor-title" style="margin-top:22px">
      <h2 id="mentor-title" class="section-title">Conheça seu mentor</h2>
      <div class="mentor" style="margin-top:12px">
        <img src="Mentor.jpeg" alt="Foto de Evandro Favoretto — mentor do workshop" />
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
          <p style="margin-top:10px;color:var(--muted)">Evandro combina ferramentas práticas e abordagens terapêuticas para facilitar processos de transformação leve e sustentada — com foco em clareza, ação consciente e presença.</p>
        </div>
      </div>
    </section>

    <!-- DEPOIMENTOS -->
    <section id="depoimentos" aria-labelledby="dep-title" style="margin-top:22px">
      <h2 id="dep-title" class="section-title">Transformações Reais</h2>
      <div class="testimonials" style="margin-top:12px">
        <div class="test"><p>"Participar foi um divisor de águas. Entendi o que me segurava e saí com ferramentas práticas — hoje fico menos ansiosa e mais presente."</p><div class="who">— Marina, 34</div></div>
        <div class="test"><p>"O ritual de encerramento me ajudou a ver 2025 com gratidão e 2026 com esperança. Recomendo muito."</p><div class="who">— Lucas, 41</div></div>
      </div>
    </section>

    <!-- INSCRIÇÃO -->
    <section id="inscricao" aria-labelledby="insc-title" style="margin-top:22px">
      <h2 id="insc-title" class="section-title">Investimento & inscrição</h2>

      <div style="display:flex;gap:18px;align-items:flex-start;flex-wrap:wrap;margin-top:12px">
        <div style="min-width:260px" class="card">
          <strong style="display:block;font-size:18px;color:var(--peach-2)">Investimento</strong>
          <p style="margin:8px 0;color:var(--muted)">Gratuito — inscrição necessária. (Vagas limitadas)</p>
          <div style="height:1px;background:var(--glass);border-radius:6px;margin:10px 0"></div>
          <strong style="display:block;color:var(--deep);margin-bottom:8px">Suporte</strong>
          <p style="color:var(--muted);margin:0">Dúvidas via WhatsApp — suporte antes e durante o workshop.</p>
        </div>

        <div style="flex:1;min-width:360px">
          <div class="form-card">
            <form id="signup" onsubmit="return handleSignup(event)" autocomplete="on">
              <div class="form-row">
                <div><label for="nome">Nome completo</label><input id="nome" name="nome" type="text" placeholder="Ex: Ana Silva" required /></div>
                <div><label for="wa">WhatsApp (com DDI)</label><input id="wa" name="wa" type="text" placeholder="+55 11 9xxxx-xxxx" /></div>
              </div>

              <div style="margin-top:12px"><label for="email">E-mail (opcional)</label><input id="email" name="email" type="email" placeholder="seu@exemplo.com" /></div>

              <div class="form-foot">
                <div class="small">Você receberá confirmação e lembretes por WhatsApp.</div>
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

    <!-- FAQ -->
    <section style="margin-top:22px">
      <h2 class="section-title">Perguntas frequentes</h2>
      <div class="faq" style="margin-top:12px">
        <div class="faq-item"><div class="faq-q" role="button" tabindex="0"><strong>Preciso participar das três noites?</strong><span aria-hidden="true">+</span></div><div class="faq-a"><p>Recomendamos acompanhar o ciclo completo para aproveitar a progressão; ainda assim, é possível participar de noites avulsas.</p></div></div>

        <div class="faq-item"><div class="faq-q" role="button" tabindex="0"><strong>Haverá gravação?</strong><span aria-hidden="true">+</span></div><div class="faq-a"><p>As gravações podem ser disponibilizadas por tempo limitado. Inscreva-se para receber atualizações por WhatsApp.</p></div></div>

        <div class="faq-item"><div class="faq-q" role="button" tabindex="0"><strong>Como faço a inscrição?</strong><span aria-hidden="true">+</span></div><div class="faq-a"><p>Preencha o formulário ou utilize o WhatsApp de suporte — enviaremos o link de acesso e lembretes.</p></div></div>
      </div>
    </section>

    <footer style="margin-top:36px">
      <div style="text-align:center;color:var(--muted)">© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</div>
    </footer>
  </div>

  <!-- floating CTA -->
  <button class="float-cta" id="floatBtn" aria-label="Reservar meu lugar">Reservar meu lugar</button>

  <script>
    // FAQ toggle
    (function(){
      const items = Array.from(document.querySelectorAll('.faq-item'));
      items.forEach(item=>{
        const q = item.querySelector('.faq-q');
        q.addEventListener('click', ()=> toggle(item));
        q.addEventListener('keydown', (e)=> { if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(item); }});
      });
      function toggle(current){
        const isOpen = current.classList.toggle('open');
        items.forEach(i => { if(i !== current) i.classList.remove('open'); });
      }
    })();

    // Buttons
    document.getElementById('decidedBtn').addEventListener('click', ()=> document.getElementById('inscricao').scrollIntoView({behavior:'smooth'}));
    document.getElementById('inscNowBtn').addEventListener('click', ()=> { document.getElementById('inscricao').scrollIntoView({behavior:'smooth'}); document.getElementById('nome').focus(); });
    document.getElementById('doubtBtn').addEventListener('click', ()=> document.getElementById('faq').scrollIntoView({behavior:'smooth'}));
    document.getElementById('moreInfoBtn').addEventListener('click', ()=> document.getElementById('como').scrollIntoView({behavior:'smooth'}));
    document.getElementById('moreInfoInline').addEventListener('click', ()=> document.getElementById('faq').scrollIntoView({behavior:'smooth'}));
    document.getElementById('contactSupport').addEventListener('click', ()=> openWhatsAppSupport());
    document.getElementById('floatBtn').addEventListener('click', ()=> document.getElementById('inscricao').scrollIntoView({behavior:'smooth'}));

    // Form submit -> opens WhatsApp (alterar número abaixo)
    function handleSignup(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const wa = document.getElementById('wa').value.trim();

      // ======= ATENÇÃO: substitua pelo SEU NÚMERO no formato internacional (sem +, sem espaços)
      // exemplo: const waNumber = '5511999999999';
      const waNumber = '55419998110445'; // <<-- TROQUE para o número oficial

      let msg = `Quero participar do workshop "Antes de virar o ano, quero estar em paz comigo." - Nome: ${nome}`;
      if(email) msg += `; Email: ${email}`;
      if(wa) msg += `; WhatsApp: ${wa}`;
      msg += ' — Inscrição via site.';
      const encoded = encodeURIComponent(msg);
      const url = `https://wa.me/${waNumber}?text=${encoded}`;
      window.open(url,'_blank');
      return false;
    }

    // Support WA
    function openWhatsAppSupport(){
      const waNumber = '55419998110445'; // <<-- TROQUE para o número oficial
      const msg = encodeURIComponent('Olá — preciso de mais informações sobre o workshop "Antes de virar o ano, quero estar em paz comigo."');
      window.open(`https://wa.me/${waNumber}?text=${msg}`, '_blank');
    }

    // attach handler
    document.getElementById('signup').addEventListener('submit', handleSignup);
  </script>
</body>
</html>
