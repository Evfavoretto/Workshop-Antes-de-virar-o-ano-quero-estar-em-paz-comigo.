<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop gratuito</title>
  <meta name="description" content="Três noites (2, 3 e 4 de dezembro, às 20h) para encerrar 2025 com leveza: soltar o que pesa e se reencontrar consigo mesma." />
  <!-- Open Graph -->
  <meta property="og:title" content="Antes de virar o ano — quero estar em paz comigo" />
  <meta property="og:description" content="Três noites para encerrar 2025 com leveza e se reencontrar consigo mesma. 2, 3 e 4 de dezembro • 20h" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Antes+de+virar+o+ano" />
  <meta name="twitter:card" content="summary_large_image" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    /* 🔧 Oculta o cabeçalho padrão do GitHub Pages (remove o título azul no topo) */
    header, .page-header, .site-header, .project-name, .project-tagline {
      display: none !important;
    }

    :root{
      /* ====== personalização de cores — altere aqui ======
         --bg-soft: fundo geral
         --accent-1: cor principal (título / CTA)
         --accent-2: cor secundária (gradiente)
         --card: cor dos cards
      =================================================== */
      --bg-soft: #FFF7F2;        /* fundo suave (creme claro) */
      --accent-1: #8B5CF6;       /* violeta suave, chama atenção sem agredir */
      --accent-2: #FF8A65;       /* pêssego para contraste quente */
      --card: #FFFFFF;
      --muted: #6B7280;
      --ink: #0F1724;
      --radius: 14px;
      --maxw: 1200px;
      --hero-title-size: clamp(38px, 8.8vw, 110px); /* TITULO BEM GRANDE e responsivo */
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      background:linear-gradient(180deg,var(--bg-soft),#FFF2E8 60%);
      color:var(--ink);-webkit-font-smoothing:antialiased;line-height:1.55;
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px}
    .topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:8px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(90deg,var(--accent-1),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:800;color:#fff;font-family:'Playfair Display',serif;font-size:20px}
    .brand .title{font-family:'Playfair Display',serif;font-size:15px;margin:0}
    nav{font-weight:600;color:var(--muted);font-size:15px}
    nav a{color:var(--muted);margin-left:18px}

    /* HERO */
    .hero{
      margin:12px 0 10px;
      background:linear-gradient(180deg, rgba(255,255,255,0.95), rgba(255,255,255,0.98));
      border-radius:20px;padding:40px;border:1px solid rgba(0,0,0,0.04);
      box-shadow:0 18px 50px rgba(15,23,36,0.05);
      display:grid;grid-template-columns:1fr;gap:18px;align-items:center;
    }
    @media(min-width:980px){.hero{grid-template-columns:1fr 420px;padding:48px}}

    .kicker{font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:.12em;margin-bottom:6px}
    .headline-small{font-weight:800;color:var(--accent-1);font-size:14px;margin-bottom:8px}
    h1{font-family:'Playfair Display',serif;font-size:var(--hero-title-size);line-height:1;margin:0 0 10px;color:var(--accent-1); /* título destacado em accent-1 */ }
    .lead{color:var(--muted);font-size:18px;max-width:820px;margin-bottom:12px}

    .dates{display:inline-block;background:linear-gradient(90deg, rgba(139,92,246,0.06), rgba(255,138,101,0.06));padding:8px 12px;border-radius:999px;color:var(--accent-1);font-weight:700;margin-bottom:12px}

    .hero-cta{display:flex;gap:12px;flex-wrap:wrap}
    .btn{border-radius:12px;padding:12px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0;box-shadow:0 10px 30px rgba(2,8,23,0.06);transition:transform .16s}
    .btn:active{transform:translateY(1px)}
    .btn-primary{background:linear-gradient(90deg,var(--accent-1),var(--accent-2));color:#fff}
    .btn-ghost{background:transparent;border:1px solid rgba(15,23,36,0.06);color:var(--muted)}

    .hero-right{background:var(--card);border-radius:12px;padding:18px;border:1px solid rgba(0,0,0,0.03)}
    .mini{font-size:13px;color:var(--muted);margin-bottom:8px}
    .count{font-size:28px;font-weight:800;color:var(--ink);margin-bottom:6px}
    .meta{font-weight:700;color:var(--muted);margin-bottom:6px}

    /* Sections */
    section{padding:46px 0;border-top:1px solid rgba(0,0,0,0.03)}
    .section-title{font-family:'Playfair Display',serif;font-size:26px;margin:0 0 12px;text-align:center;color:var(--ink)}

    /* problem + solution cards */
    .ps-grid{display:grid;gap:18px;align-items:stretch}
    @media(min-width:900px){.ps-grid{grid-template-columns:1fr 1fr}}
    .ps-card{background:var(--card);border-radius:12px;padding:22px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 30px rgba(2,8,23,0.03)}
    .ps-card h3{margin:0 0 10px;color:var(--accent-1);font-size:20px}
    .ps-card p{color:var(--muted);margin:0;font-size:16px;white-space:pre-line}

    /* Three nights cards */
    .grid-3{display:grid;gap:18px;margin-top:6px}
    @media(min-width:860px){.grid-3{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--card);border-radius:12px;padding:20px;border:1px solid rgba(0,0,0,0.04);box-shadow:0 10px 30px rgba(2,8,23,0.03)}
    .card h3{font-size:18px;margin:0 0 10px;color:var(--accent-1)}
    .card p{color:var(--muted);margin:6px 0 0;white-space:pre-line}

    /* benefits */
    .benefits{display:grid;gap:10px;max-width:920px;margin:10px auto 0}
    .benefits ul{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;list-style:none;padding:0;margin:0}
    @media(max-width:720px){.benefits ul{grid-template-columns:1fr}}
    .benefits li{background:var(--card);padding:12px;border-radius:10px;border:1px solid rgba(0,0,0,0.03);display:flex;gap:12px;align-items:center}
    .icon-square{width:44px;height:44px;border-radius:10px;background:linear-gradient(90deg,var(--accent-1),var(--accent-2));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800}

    /* FAQ */
    .faq-wrap{max-width:1000px;margin:6px auto 0}
    .faq-controls{display:flex;gap:12px;align-items:center;justify-content:space-between;margin-bottom:14px}
    .faq-search input{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(0,0,0,0.04);background:transparent;color:var(--ink)}
    .chip{padding:8px 12px;border-radius:999px;background:transparent;border:1px solid rgba(0,0,0,0.04);cursor:pointer;color:var(--muted)}
    .chip.active{background:linear-gradient(90deg,var(--accent-1),var(--accent-2));color:#fff;border-color:transparent}

    .faq-grid{display:grid;grid-template-columns:1fr 360px;gap:18px}
    @media(max-width:980px){.faq-grid{grid-template-columns:1fr}}
    .faq-card{background:var(--card);padding:14px;border-radius:12px;border:1px solid rgba(0,0,0,0.04)}
    .faq-q{display:flex;align-items:flex-start;gap:12px;cursor:pointer}
    .faq-q h4{margin:0;font-size:16px;color:var(--ink)}
    .faq-q p{margin:6px 0 0;color:var(--muted);font-size:14px}
    .faq-icon{width:44px;height:44px;border-radius:10px;background:linear-gradient(90deg,var(--accent-1),var(--accent-2));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700}

    .answer{max-height:0;overflow:hidden;transition:max-height .28s ease;padding:0 2px}
    .faq-card.open .answer{max-height:320px;padding-top:12px}

    .faq-idx{background:var(--card);padding:16px;border-radius:12px;border:1px solid rgba(0,0,0,0.04)}
    .faq-idx h5{margin:0 0 8px;font-size:15px;color:var(--ink)}
    .faq-idx ul{list-style:none;padding:0;margin:0;display:grid;gap:8px}
    .faq-idx li{cursor:pointer;padding:8px;border-radius:8px;color:var(--muted);border:1px solid transparent}
    .faq-idx li:hover{background:rgba(0,0,0,0.02);color:var(--ink);border-color:rgba(0,0,0,0.03)}

    /* form */
    .form-card{max-width:760px;margin:10px auto;padding:20px;border-radius:12px;background:var(--card);border:1px solid rgba(0,0,0,0.04)}
    .form-row{display:grid;gap:8px}
    @media(min-width:720px){.form-row{grid-template-columns:1fr 260px}}
    label{font-size:13px;color:var(--muted);display:block;margin-bottom:6px;font-weight:700}
    input[type="text"], input[type="email"]{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(0,0,0,0.04);background:transparent;color:var(--ink);outline:none;font-size:15px}
    .form-foot{display:flex;gap:12px;align-items:center;justify-content:flex-end;margin-top:12px}
    .small{font-size:13px;color:var(--muted);}

    footer{padding:28px 0;text-align:center;color:var(--muted);font-size:14px}
    a:focus, button:focus, input:focus{outline:3px solid rgba(139,92,246,0.14);outline-offset:3px;border-radius:6px}
    .muted-small{color:var(--muted);font-size:14px}
  </style>
</head>
<body>
  <div class="wrap" role="document">
    <!-- top -->
    <header class="topbar" aria-label="Cabeçalho do site">
      <div class="brand">
        <div class="logo" aria-hidden="true">⚖️</div>
        <div>
          <div class="title">Antes de virar o ano</div>
          <div style="font-size:13px;color:var(--muted)">Workshop gratuito • 3 noites</div>
        </div>
      </div>
      <nav aria-label="Navegação principal">
        <a href="#noites">Noites</a>
        <a href="#problema">Problema</a>
        <a href="#solucao">Solução</a>
        <a href="#inscricao">Inscrição</a>
      </nav>
    </header>

    <!-- hero -->
    <main class="hero" role="main" aria-labelledby="main-title">
      <div>
        <div class="headline-small">Workshop Gratuito:</div>
        <!-- TÍTULO BEM GRANDE E DESTACADO -->
        <h1 id="main-title">Antes de virar o ano, quero estar em paz comigo.</h1>

        <!-- subtítulo com datas + descrição -->
        <div class="dates">Dias 2, 3 e 4 de dezembro • às 20h</div>
        <p class="lead">Três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes do novo ciclo começar.</p>

        <div class="hero-cta" role="group" aria-label="Ações principais">
          <button class="btn btn-primary" onclick="document.getElementById('inscricao').scrollIntoView({behavior:'smooth'})">Inscrever-se grátis</button>
          <a class="btn btn-ghost" href="#noites">Ver as noites</a>
        </div>
      </div>

      <aside class="hero-right" aria-label="Resumo do evento">
        <div class="mini">Próximo encontro</div>
        <div class="count">02 Dez • 20h</div>
        <div class="mini">Duração por noite</div>
        <div class="meta">60 — 75 minutos</div>
        <div class="mini">Vagas</div>
        <div class="muted-small">Gratuito — inscrição necessária</div>
      </aside>
    </main>

    <!-- PROBLEMA / SOLUÇÃO -->
    <section id="problema" aria-labelledby="prob-title">
      <h2 id="prob-title" class="section-title">O problema que a maioria enfrenta</h2>
      <div class="ps-grid" style="margin-top:12px">
        <div class="ps-card">
          <h3>Você não está sozinha nisso</h3>
          <p>
Muitas pessoas chegam ao fim do ano carregando cansaço emocional, culpa por não ter sido “suficiente”, mágoas antigas e a sensação de que o tempo passou sem que elas tivessem cuidado de si.
Isso cria ansiedade, noites sem sono e um peso constante que impede um recomeço com leveza.
          </p>
        </div>

        <div class="ps-card" id="solucao" aria-labelledby="sol-title">
          <h3 id="sol-title">A solução — por onde começar</h3>
          <p>
Entrar em um espaço guiado, curto e seguro onde você possa:
• nomear o que pesa,
• aprender práticas para soltar com cuidado,
• e transformar experiência em intenção para o próximo ciclo.
O Workshop é exatamente isso: três noites práticas e acolhedoras que ajudam você a fechar 2025 com paz e entrar em 2026 mais leve.
          </p>
        </div>
      </div>
    </section>

    <!-- tres noites (com o texto exato pedido) -->
    <section id="noites" aria-labelledby="noites-title">
      <h2 id="noites-title" class="section-title">As três noites</h2>
      <div class="grid-3" style="margin-top:18px">
        <article class="card" aria-labelledby="n1">
          <h3 id="n1">🌙 1ª Noite — O peso que ainda carrego</h3>
          <p>
Reconheça o que está tirando sua paz.
Mágoas, culpas e cobranças que já não cabem mais.
O primeiro passo pra se libertar é dar nome ao que dói.
          </p>
        </article>

        <article class="card" aria-labelledby="n2">
          <h3 id="n2">💚 2ª Noite — Quando soltar é a forma mais sincera de cuidar</h3>
          <p>
Aprenda a soltar o controle e a cuidar de si com verdade.
Descubra que força também é confiar, pausar e permitir-se descansar.
          </p>
        </article>

        <article class="card" aria-labelledby="n3">
          <h3 id="n3">✨ 3ª Noite — O recomeço que nasce da paz</h3>
          <p>
Transforme o que viveu em sabedoria e escolha recomeçar leve.
Defina suas intenções para 2026 em um ritual de paz e renascimento.
          </p>
        </article>
      </div>
    </section>

    <!-- beneficios -->
    <section id="beneficios" aria-labelledby="benef-title">
      <h2 id="benef-title" class="section-title">O que você vai levar</h2>
      <div class="benefits" style="margin-top:14px">
        <ul>
          <li><div class="icon-square">1</div><div><strong>Clareza</strong><div style="color:var(--muted)">Sobre o que deixar para trás</div></div></li>
          <li><div class="icon-square">2</div><div><strong>Ferramentas</strong><div style="color:var(--muted)">Práticas simples de autocuidado</div></div></li>
          <li><div class="icon-square">3</div><div><strong>Ritual</strong><div style="color:var(--muted)">Ritual prático para definir intenções</div></div></li>
          <li><div class="icon-square">4</div><div><strong>Leveza</strong><div style="color:var(--muted)">Mais paz emocional para 2026</div></div></li>
        </ul>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" aria-labelledby="faq-title">
      <h2 id="faq-title" class="section-title">Perguntas frequentes</h2>

      <div class="faq-wrap" role="region" aria-live="polite">
        <div class="faq-controls" style="margin-bottom:12px">
          <div class="faq-search">
            <input id="faqSearch" type="search" placeholder="Buscar perguntas (ex.: gravação, gratuito, vagas)" aria-label="Buscar perguntas"/>
          </div>
          <div class="faq-filter" aria-hidden="true">
            <button class="chip active" data-filter="all">Todas</button>
            <button class="chip" data-filter="logistica">Logística</button>
            <button class="chip" data-filter="conteudo">Conteúdo</button>
            <button class="chip" data-filter="tecnico">Técnico</button>
          </div>
        </div>

        <div class="faq-grid">
          <div class="faq-list" id="faqList">
            <!-- items -->
            <div class="faq-card" data-tags="logistica">
              <div class="faq-q" tabindex="0" role="button" aria-expanded="false">
                <div class="faq-icon">Q</div>
                <div>
                  <h4>Preciso participar das três noites?</h4>
                  <p>Recomendamos acompanhar o ciclo completo, mas você pode participar de noites isoladas se necessário.</p>
                </div>
              </div>
              <div class="answer" aria-hidden="true"><div class="muted-small">Acompanhar as três noites dá mais sentido ao processo — cada encontro constrói o seguinte. Se faltar uma, não se preocupe: você ainda será bem-vinda nas demais.</div></div>
            </div>

            <div class="faq-card" data-tags="conteudo">
              <div class="faq-q" tabindex="0" role="button" aria-expanded="false">
                <div class="faq-icon">C</div>
                <div>
                  <h4>O que vou vivenciar em cada noite?</h4>
                  <p>Resumo prático dos focos das três noites.</p>
                </div>
              </div>
              <div class="answer" aria-hidden="true"><div class="muted-small">1ª noite: reconhecimento das feridas e pesos. 2ª noite: práticas de soltura e autocuidado. 3ª noite: ritual de encerramento e definição de intenções.</div></div>
            </div>

            <div class="faq-card" data-tags="tecnico">
              <div class="faq-q" tabindex="0" role="button" aria-expanded="false">
                <div class="faq-icon">T</div>
                <div>
                  <h4>É online e haverá gravação?</h4>
                  <p>O evento é online; gravações podem ser disponibilizadas.</p>
                </div>
              </div>
              <div class="answer" aria-hidden="true"><div class="muted-small">As gravações geralmente ficam disponíveis por tempo limitado. Inscreva-se para receber o link quando for liberado.</div></div>
            </div>

            <div class="faq-card" data-tags="logistica">
              <div class="faq-q" tabindex="0" role="button" aria-expanded="false">
                <div class="faq-icon">V</div>
                <div>
                  <h4>Como garanto minha vaga?</h4>
                  <p>Preencha o formulário de inscrição — enviaremos avisos por WhatsApp.</p>
                </div>
              </div>
              <div class="answer" aria-hidden="true"><div class="muted-small">A inscrição confirma seu interesse e garante que receba instruções e lembretes antes de cada encontro.</div></div>
            </div>

            <div class="faq-card" data-tags="conteudo">
              <div class="faq-q" tabindex="0" role="button" aria-expanded="false">
                <div class="faq-icon">P</div>
                <div>
                  <h4>Preciso participar ao vivo?</h4>
                  <p>Participar ao vivo é recomendado para a experiência completa.</p>
                </div>
              </div>
              <div class="answer" aria-hidden="true"><div class="muted-small">Ao vivo você vive as práticas e troca em tempo real; ainda assim, quem não puder terá a opção de ver a gravação quando disponível.</div></div>
            </div>

            <div class="faq-card" data-tags="tecnico">
              <div class="faq-q" tabindex="0" role="button" aria-expanded="false">
                <div class="faq-icon">A</div>
                <div>
                  <h4>É cobrado algum valor?</h4>
                  <p>Não — o workshop é 100% gratuito.</p>
                </div>
              </div>
              <div class="answer" aria-hidden="true"><div class="muted-small">Sem custos. Apenas pedimos presença e abertura para a experiência.</div></div>
            </div>
          </div>

          <aside class="faq-idx" aria-label="Índice de perguntas">
            <h5>Atalhos rápidos</h5>
            <ul>
              <li data-jump="Como garanto minha vaga?">Como garanto minha vaga?</li>
              <li data-jump="É online e haverá gravação?">Gravações</li>
              <li data-jump="É cobrado algum valor?">Gratuito</li>
              <li data-jump="Preciso participar das três noites?">Participação</li>
            </ul>
          </aside>
        </div>
      </div>
    </section>

    <!-- INSCRIÇÃO -->
    <section id="inscricao" aria-labelledby="insc-title">
      <h2 id="insc-title" class="section-title">Reserve seu lugar — é grátis</h2>
      <div class="form-card" role="form" aria-label="Formulário de inscrição">
        <form id="signup" onsubmit="return handleSignup(event)">
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
            <div class="small">Você receberá confirmação por WhatsApp.</div>
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
    // FAQ interatividade (toggle, busca, filtros, índice)
    (function(){
      const faqList = document.getElementById('faqList');
      const cards = Array.from(faqList.querySelectorAll('.faq-card'));
      const search = document.getElementById('faqSearch');
      const chips = Array.from(document.querySelectorAll('.chip'));
      const idx = document.querySelectorAll('.faq-idx li');

      function toggleCard(card){
        const isOpen = card.classList.toggle('open');
        const q = card.querySelector('.faq-q');
        const ans = card.querySelector('.answer');
        q.setAttribute('aria-expanded', isOpen ? 'true' : 'false');
        ans.setAttribute('aria-hidden', isOpen ? 'false' : 'true');
        if(isOpen){
          cards.forEach(c => { if(c !== card){ c.classList.remove('open'); c.querySelector('.faq-q').setAttribute('aria-expanded','false'); c.querySelector('.answer').setAttribute('aria-hidden','true'); }});
        }
      }

      cards.forEach(card=>{
        const q = card.querySelector('.faq-q');
        q.addEventListener('click', ()=> toggleCard(card));
        q.addEventListener('keydown', (e)=>{
          if(e.key === 'Enter' || e.key === ' '){ e.preventDefault(); toggleCard(card); }
        });
      });

      function filterFAQs(term, tag){
        const t = term.trim().toLowerCase();
        cards.forEach(card=>{
          const text = (card.innerText || '').toLowerCase();
          const tags = (card.dataset.tags || '').toLowerCase();
          const matchesText = !t || text.includes(t);
          const matchesTag = !tag || tag === 'all' || tags.includes(tag);
          card.style.display = (matchesText && matchesTag) ? '' : 'none';
        });
      }

      if(search){
        search.addEventListener('input', ()=> {
          const term = search.value;
          const active = chips.find(c => c.classList && c.classList.contains('active')) || {dataset:{filter:'all'}};
          filterFAQs(term, active.dataset.filter);
        });
      }

      chips.forEach(ch=>{
        ch.addEventListener('click', ()=>{
          chips.forEach(c=>c.classList.remove('active'));
          ch.classList.add('active');
          const tag = ch.dataset.filter;
          filterFAQs(search.value || '', tag);
        });
      });

      idx.forEach(li=>{
        li.addEventListener('click', ()=>{
          const q = li.dataset.jump || li.innerText;
          const match = cards.find(c => c.innerText.toLowerCase().includes(q.toLowerCase()));
          if(match){
            match.scrollIntoView({behavior:'smooth', block:'center'});
            if(!match.classList.contains('open')) toggleCard(match);
          }
        });
      });
    })();

    // Form: abre WhatsApp com mensagem pré-preenchida
    function handleSignup(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      const email = document.getElementById('email').value.trim();
      const wa = document.getElementById('wa').value.trim();

      // === ATENÇÃO: Substitua abaixo pelo número de destino (formato internacional, sem sinais)
      // Ex.: const waNumber = '+5511999999999';
      const waNumber = '+55419998110445'; // placeholder — troque para o número/WhatsApp oficial

      let msg = `Quero participar do workshop "Antes de virar o ano, quero estar em paz comigo." - Nome: ${nome}`;
      if(email) msg += `; E-mail: ${email}`;
      if(wa) msg += `; WhatsApp: ${wa}`;
      msg += ' — Inscrição via site.';
      const encoded = encodeURIComponent(msg);
      const url = `https://wa.me/${waNumber.replace(/\D/g,'')}?text=${encoded}`;
      window.open(url,'_blank');
      return false;
    }
  </script>
</body>
</html>
