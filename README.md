<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop gratuito</title>
  <meta name="description" content="Workshop gratuito — Dias 2, 3 e 4 de dezembro às 20h. Três noites para encerrar 2025 com leveza e entrar em 2026 em paz." />
  <!-- Open Graph -->
  <meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
  <meta property="og:description" content="2, 3 e 4 de dezembro • 20h — três noites para encerrar 2025 com leveza e se reencontrar antes de 2026." />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
  <meta name="twitter:card" content="summary_large_image" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    /* remove cabeçalho do GitHub Pages (se estiver usando) */
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --bg:#FFF7F3;
      --peach-1:#FFB89C;
      --peach-2:#FF7F5E;
      --ink:#2B1F1A;
      --muted:#79615A;
      --card:#FFFFFF;
      --glass: rgba(43,31,25,0.06);
      --radius:16px;
      --hero-size: clamp(48px, 9.5vw, 120px);
      --easing: cubic-bezier(.2,.9,.3,1);
      --shadow-lg: 0 30px 60px rgba(43,31,25,0.08);
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      background:linear-gradient(180deg,var(--bg),#FFF0E6 60%);
      color:var(--ink);-webkit-font-smoothing:antialiased;line-height:1.5;
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:36px 20px}

    /* Topbar */
    .topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:6px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--peach-1),var(--peach-2));display:flex;align-items:center;justify-content:center;color:#fff;font-family:'Playfair Display',serif;font-weight:700;font-size:20px;box-shadow:var(--shadow-lg)}
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}

    /* HERO */
    .hero{
      margin:18px 0;border-radius:20px;padding:48px;display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;
      background:linear-gradient(180deg, rgba(255,255,255,0.96), rgba(255,250,248,0.96));
      box-shadow:var(--shadow-lg);
    }
    @media(max-width:980px){ .hero{grid-template-columns:1fr; padding:28px } .hero-right{order:-1} }

    .kicker{display:inline-block;padding:6px 12px;border-radius:999px;background:rgba(255,127,94,0.08);color:var(--peach-2);font-weight:800;font-size:13px;letter-spacing:.05em}
    .title-main{font-family:'Playfair Display',serif;font-size:var(--hero-size);line-height:0.95;margin:12px 0;color:var(--peach-2)}
    .subtitle{color:var(--muted);font-size:17px;max-width:760px}

    .hero-ctas{display:flex;gap:10px;flex-wrap:wrap;margin-top:18px}
    .btn{
      border-radius:12px;padding:14px 20px;font-weight:800;font-size:15px;cursor:pointer;border:0;transition:transform .16s var(--easing),box-shadow .16s var(--easing);
    }
    .btn-primary{background:linear-gradient(90deg,var(--peach-2),var(--peach-1));color:#fff;box-shadow:0 16px 40px rgba(255,127,94,0.18)}
    .btn-secondary{background:transparent;border:1px solid rgba(43,31,25,0.06);color:var(--muted)}
    .btn-ghost{background:transparent;border:1px solid rgba(43,31,25,0.03);color:var(--muted)}

    .hero-right{background:var(--card);padding:20px;border-radius:14px;border:1px solid var(--glass);box-shadow:0 12px 30px rgba(0,0,0,0.04)}
    .meta-small{font-size:13px;color:var(--muted);margin-bottom:6px}
    .meta-strong{font-weight:800;color:var(--ink);font-size:20px;margin-bottom:8px}

    .underline{height:8px;border-radius:999px;width:180px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));animation:grow .9s var(--easing) both;margin-top:8px}
    @keyframes grow{from{transform:scaleX(0)}to{transform:scaleX(1)}}

    /* SECTIONS */
    section{padding:42px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:24px;margin:0 0 12px;color:var(--ink);text-align:left}

    /* HOW IT WORKS */
    .steps{display:grid;gap:14px}
    @media(min-width:900px){ .steps{grid-template-columns:repeat(3,1fr)} }
    .step{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 28px rgba(0,0,0,0.03)}
    .step h4{margin:0 0 8px;color:var(--peach-2)} .step p{color:var(--muted);margin:0}

    /* THREE NIGHTS */
    .grid-3{display:grid;gap:18px;margin-top:12px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 10px 30px rgba(0,0,0,0.03)}
    .card h3{font-size:16px;margin:0 0 8px;color:var(--peach-2)}
    .card p{color:var(--muted);line-height:1.55;white-space:pre-line}

    /* WHY / WHO */
    .cols{display:grid;gap:16px}
    @media(min-width:900px){ .cols{grid-template-columns:1fr 1fr} }
    .list{background:var(--card);padding:18px;border-radius:12px;border:1px solid var(--glass)}

    /* WHAT YOU GAIN */
    .benefits{display:flex;flex-wrap:wrap;gap:12px;margin-top:12px}
    .benefit{background:var(--card);padding:12px 14px;border-radius:10px;border:1px solid var(--glass);display:flex;gap:12px;align-items:center;min-width:220px}
    .badge{width:44px;height:44px;border-radius:10px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800}

    /* MENTOR */
    .mentor{display:flex;gap:18px;align-items:center;padding:18px;border-radius:12px;background:linear-gradient(180deg,#fff,#fff);border:1px solid var(--glass);box-shadow:0 12px 36px rgba(0,0,0,0.04)}
    .mentor img{width:180px;height:180px;border-radius:12px;object-fit:cover;border:2px solid rgba(0,0,0,0.04)}
    .mentor .bio{flex:1}
    .mentor h3{margin:0 0 8px;font-size:18px}
    .mentor p{margin:0;color:var(--muted);line-height:1.6}

    /* TESTIMONIALS */
    .testimonials{display:grid;gap:12px}
    .test{background:var(--card);padding:16px;border-radius:12px;border:1px solid var(--glass);box-shadow:0 8px 22px rgba(0,0,0,0.03)}
    .test p{margin:0;color:var(--muted)} .test .who{margin-top:10px;font-weight:700;color:var(--ink)}

    /* FORM / INVESTMENT */
    .form-card{max-width:760px;margin:12px auto;padding:18px;border-radius:12px;background:var(--card);border:1px solid var(--glass);box-shadow:0 12px 34px rgba(0,0,0,0.04)}
    .form-row{display:grid;gap:10px}
    @media(min-width:720px){ .form-row{grid-template-columns:1fr 260px} }
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px;font-weight:700}
    input{width:100%;padding:12px;border-radius:10px;border:1px solid var(--glass);background:transparent;color:var(--ink);font-size:15px;outline:none}
    .form-foot{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-top:12px}
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

    @media(max-width:720px){
      .hero{grid-template-columns:1fr}
      .mentor{flex-direction:column;align-items:flex-start}
      .mentor img{width:100%;height:280px}
    }
  </style>
</head>
<body>
  <div class="wrap">

    <!-- TOP -->
    <header class="topbar" role="banner" aria-label="Cabeçalho">
      <div class="brand">
        <div class="logo" aria-hidden="true">🌿</div>
        <div>
          <div style="font-weight:800;font-family:'Playfair Display',serif">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>
      <nav aria-label="Navegação">
        <a href="#como">Como funciona</a>
        <a href="#noites">Noites</a>
        <a href="#mentor">Mentor</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="main-title">
      <div>
        <div class="kicker">Workshop Gratuito</div>
        <h1 id="main-title" class="title-main">Antes de virar o ano, quero estar em paz comigo.</h1>
        <div class="underline" aria-hidden="true"></div>
        <p class="subtitle">Dias 2, 3 e 4 de dezembro • às 20h — três noites práticas para encerrar 2025 com leveza, soltar o que pesa e entrar em 2026 com mais paz.</p>

        <div class="hero-ctas" aria-label="Ações principais">
          <button class="btn btn-primary" id="decidedBtn">Já tomei minha decisão</button>
          <button class="btn btn-primary" id="inscNowBtn">Quero me inscrever agora</button>
          <button class="btn btn-secondary" id="doubtBtn">Ainda estou com dúvida</button>
          <button class="btn btn-ghost" id="moreInfoBtn">Preciso de mais informações</button>
        </div>

        <div style="margin-top:18px" class="small" aria-hidden="true">Vagas limitadas — inscrição necessária.</div>
      </div>

      <aside class="hero-right" aria-label="Resumo do evento">
        <div class="meta-small">Próximo encontro</div>
        <div class="meta-strong">02 Dez • 20h</div>
        <div style="height:1px;background:var(--glass);border-radius:6px;margin:10px 0"></div>
        <div class="meta-small">Duração</div>
        <div style="font-weight:800;color:var(--ink)">60–75 minutos / noite</div>
        <div style="margin-top:10px" class="meta-small">Gratuito — inscrição necessária</div>
        <div style="margin-top:12px">
          <button class="btn btn-primary" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Reservar meu lugar</button>
        </div>
      </aside>
    </main>

    <!-- HOW IT WORKS -->
    <section id="como" aria-labelledby="como-title">
      <h2 id="como-title" class="section-title">Como vai funcionar</h2>
      <div class="steps" style="margin-top:12px">
        <div class="step">
          <h4>1 — Inscrição</h4>
          <p>Você se inscreve pelo formulário (ou WhatsApp) e recebe o link e lembretes antes dos encontros.</p>
        </div>
        <div class="step">
          <h4>2 — Encontros ao vivo</h4>
          <p>Três noites consecutivas, ao vivo às 20h — práticas guiadas, reflexões e espaço de partilha.</p>
        </div>
        <div class="step">
          <h4>3 — Integração</h4>
          <p>Exercícios práticos para integrar entre os encontros e um pequeno ritual na última noite.</p>
        </div>
      </div>
    </section>

    <!-- THREE NIGHTS -->
    <section id="noites" aria-labelledby="noites-title">
      <h2 id="noites-title" class="section-title">As 3 noites</h2>
      <div class="grid-3" style="margin-top:12px">
        <article class="card">
          <h3>🌙 1ª Noite — O peso que ainda carrego</h3>
          <p>Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.</p>
        </article>

        <article class="card">
          <h3>💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h3>
          <p>Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.</p>
        </article>

        <article class="card">
          <h3>✨ 3ª Noite — O recomeço que nasce da paz</h3>
          <p>Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.</p>
        </article>
      </div>
    </section>

    <!-- WHY / WHO -->
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

    <!-- WHAT YOU GAIN -->
    <section id="ganhos" aria-labelledby="ganhos-title">
      <h2 id="ganhos-title" class="section-title">O que você ganha ao participar</h2>
      <div class="benefits" style="margin-top:12px">
        <div class="benefit"><div class="badge">1</div><div style="margin-left:8px"><strong>Clareza</strong><div style="color:var(--muted)">Identificar o que pesa e por que</div></div></div>
        <div class="benefit"><div class="badge">2</div><div style="margin-left:8px"><strong>Ferramentas</strong><div style="color:var(--muted)">Práticas para soltar e cuidar</div></div></div>
        <div class="benefit"><div class="badge">3</div><div style="margin-left:8px"><strong>Ritual</strong><div style="color:var(--muted)">Fechar 2025 e entrar em 2026</div></div></div>
      </div>
    </section>

    <!-- MENTOR -->
    <section id="mentor" aria-labelledby="mentor-title" style="margin-top:22px">
      <h2 id="mentor-title" class="section-title">Conheça seu mentor</h2>
      <div class="mentor" style="margin-top:12px">
        <!-- substitua src pela foto oficial -->
        <img src="https://via.placeholder.com/480x480.png?text=Foto+do+Mentor" alt="Foto de Evandro Favoretto — mentor do workshop" />
        <div class="bio">
          <h3>Evandro Favoretto</h3>
          <p>Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
          <p style="margin-top:10px;color:var(--muted)">Evandro combina ferramentas práticas e abordagens terapêuticas para facilitar processos de transformação leve e sustentada — com foco em clareza, ação consciente e presença.</p>
        </div>
      </div>
    </section>

    <!-- TRANSFORMAÇÕES REAIS (depoimentos) -->
    <section id="depoimentos" aria-labelledby="dep-title" style="margin-top:22px">
      <h2 id="dep-title" class="section-title">Transformações Reais</h2>
      <div class="testimonials" style="margin-top:12px">
        <div class="test">
          <p>"Participar foi um divisor de águas. Entendi o que me segurava e saí com ferramentas práticas — hoje fico menos ansiosa e mais presente."</p>
          <div class="who">— Marina, 34</div>
        </div>

        <div class="test">
          <p>"O ritual de encerramento me ajudou a ver 2025 com gratidão e 2026 com esperança. Recomendo muito."</p>
          <div class="who">— Lucas, 41</div>
        </div>

        <div class="test">
          <p>"Simples, direto e profundo. As noites foram objetivas e acolhedoras — senti diferença já no segundo encontro."</p>
          <div class="who">— Joana, 29</div>
        </div>
      </div>
    </section>

    <!-- INVESTIMENTO / INSCRIÇÃO / SUPORTE -->
    <section id="inscricao" aria-labelledby="insc-title" style="margin-top:22px">
      <h2 id="insc-title" class="section-title">Investimento & inscrição</h2>

      <div style="display:flex;gap:18px;align-items:flex-start;flex-wrap:wrap;margin-top:12px">
        <div style="min-width:260px" class="card">
          <strong style="display:block;font-size:18px;color:var(--peach-2)">Investimento</strong>
          <p style="margin:8px 0;color:var(--muted)">Gratuito — inscrição necessária. (Vagas limitadas)</p>
          <div style="height:1px;background:var(--glass);border-radius:6px;margin:10px 0"></div>
          <strong style="display:block;color:var(--ink);margin-bottom:8px">Suporte</strong>
          <p style="color:var(--muted);margin:0">Se tiver dúvidas, oferecemos suporte via WhatsApp antes e durante o workshop.</p>
        </div>

        <div style="flex:1;min-width:360px">
          <div class="form-card">
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
                <div style="display:flex;gap:8px">
                  <button class="btn btn-primary" type="submit">Quero me inscrever agora</button>
                  <button type="button" class="btn btn-secondary" id="moreInfoInline">Preciso de mais informações</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>

      <!-- quick support CTA -->
      <div style="margin-top:12px">
        <button class="btn btn-ghost" id="contactSupport">Ainda estou com dúvida — falar com suporte</button>
      </div>
    </section>

    <!-- FAQ -->
    <section style="margin-top:22px">
      <h2 class="section-title">Perguntas frequentes</h2>
      <div class="faq" style="margin-top:12px">
        <div class="faq-item">
          <div class="faq-q" role="button" tabindex="0"><strong>Preciso participar das três noites?</strong><span aria-hidden="true">+</span></div>
          <div class="faq-a"><p>Recomendamos acompanhar o ciclo completo para aproveitar a progressão; ainda assim, é possível participar de noites avulsas.</p></div>
        </div>

        <div class="faq-item">
          <div class="faq-q" role="button" tabindex="0"><strong>Haverá gravação?</strong><span aria-hidden="true">+</span></div>
          <div class="faq-a"><p>As gravações podem ser disponibilizadas por tempo limitado. Inscreva-se para receber atualizações por WhatsApp.</p></div>
        </div>

        <div class="faq-item">
          <div class="faq-q" role="button" tabindex="0"><strong>Como faço a inscrição?</strong><span aria-hidden="true">+</span></div>
          <div class="faq-a"><p>Preencha o formulário acima ou use o botão de WhatsApp — enviaremos o link de acesso e lembretes.</p></div>
        </div>
      </div>
    </section>

    <footer style="margin-top:36px">
      <div style="text-align:center;color:var(--muted)">© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</div>
    </footer>
  </div>

  <!-- Floating CTA -->
  <button id="floatReserve" aria-label="Reservar meu lugar" style="position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--peach-2),var(--peach-1));color:#fff;border:0;padding:12px 16px;border-radius:12px;font-weight:800;box-shadow:0 20px 46px rgba(255,127,94,0.22);cursor:pointer;z-index:60">Reservar meu lugar</button>

  <script>
    // ===== Interatividade: FAQ toggle, CTAs, formulário -> WhatsApp / suporte =====

    // FAQ toggle (accessible)
    (function(){
      const items = Array.from(document.querySelectorAll('.faq-item'));
      items.forEach(item=>{
        const q = item.querySelector('.faq-q');
        q.addEventListener('click', ()=> toggle(item));
        q.addEventListener('keydown', (e)=>{ if(e.key==='Enter' || e.key===' ') { e.preventDefault(); toggle(item); }});
      });
      function toggle(current){
        const open = current.classList.toggle('open');
        items.forEach(i=>{ if(i!==current) i.classList.remove('open'); });
      }
    })();

    // Buttons behavior
    document.getElementById('decidedBtn').addEventListener('click', ()=> {
      // quick scroll to inscription & open form region
      document.getElementById('inscricao').scrollIntoView({behavior:'smooth', block:'center'});
    });

    document.getElementById('inscNowBtn').addEventListener('click', ()=> {
      document.getElementById('inscricao').scrollIntoView({behavior:'smooth', block:'center'});
      const name = document.getElementById('nome'); if(name) name.focus();
    });

    document.getElementById('doubtBtn').addEventListener('click', ()=> {
      // open FAQ
      document.querySelector('#inscricao').scrollIntoView({behavior:'smooth'});
    });

    document.getElementById('moreInfoBtn').addEventListener('click', ()=> {
      document.querySelector('#como').scrollIntoView({behavior:'smooth'});
    });

    document.getElementById('moreInfoInline').addEventListener('click', ()=> {
      document.querySelector('#faq').scrollIntoView({behavior:'smooth'});
    });

    document.getElementById('contactSupport').addEventListener('click', ()=> {
      openWhatsAppSupport();
    });

    document.getElementById('floatReserve').addEventListener('click', ()=> {
      document.getElementById('inscricao').scrollIntoView({behavior:'smooth'});
    });

    // Form submit: opens WhatsApp (change waNumber below)
    function handleSignup(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const wa = document.getElementById('wa').value.trim();

      // ======= ATENÇÃO: substitua pelo SEU NÚMERO oficial (formato internacional, sem sinais) =======
      // exemplo: const waNumber = '5511999999999';
      const waNumber = '55419998110445'; // <<-- TROQUE para seu número (sem +, sem espaços)

      let msg = `Quero participar do workshop "Antes de virar o ano, quero estar em paz comigo." - Nome: ${nome}`;
      if(email) msg += `; Email: ${email}`;
      if(wa) msg += `; WhatsApp: ${wa}`;
      msg += ' — Inscrição via site.';
      const encoded = encodeURIComponent(msg);
      const url = `https://wa.me/${waNumber}?text=${encoded}`;
      window.open(url, '_blank');
      return false;
    }

    // Support: open WhatsApp chat (same number)
    function openWhatsAppSupport(){
      const waNumber = '55419998110445'; // <<-- TROQUE para seu número oficial
      const msg = encodeURIComponent('Olá — preciso de mais informações sobre o workshop "Antes de virar o ano, quero estar em paz comigo."');
      window.open(`https://wa.me/${waNumber}?text=${msg}`, '_blank');
    }

    // attach form handler
    document.getElementById('signup').addEventListener('submit', handleSignup);
  </script>
</body>
</html>
