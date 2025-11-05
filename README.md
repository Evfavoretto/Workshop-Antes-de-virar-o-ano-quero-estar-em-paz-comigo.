<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Antes de virar o ano — quero estar em paz comigo | Workshop</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    header, .page-header, .site-header, .project-name, .project-tagline { display:none !important; }

    :root{
      --maxw:1200px;
      --blue-1:#EAF4FB;
      --blue-2:#B8E1FF;
      --blue-deep:#0F4C81;
      --deep:#122034;
      --muted:#5A6571;
      --card:#FFFFFF;
      --shadow-lg: 0 30px 60px rgba(15,76,129,0.08);
    }

    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      color:var(--deep);
      background:
        radial-gradient(1200px 600px at 10% 10%, rgba(11,76,129,0.04), transparent 6%),
        radial-gradient(900px 500px at 95% 90%, rgba(184,225,255,0.03), transparent 8%),
        linear-gradient(180deg,var(--blue-1), #FFFFFF 80%);
    }

    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;position:relative;z-index:1}

    /* HERO */
    .hero{
      position:relative;
      border-radius:22px;
      /* leve tonalidade azul escuro + sombra mais suave */
      background:linear-gradient(180deg, rgba(240,245,252,0.98), rgba(235,242,250,0.96));
      box-shadow:0 30px 60px rgba(15,76,129,0.06);
      padding:200px 56px 96px;
      margin:-120px auto 34px;
      min-height:640px;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      /* deslocamento mais equilibrado (menos à esquerda, mais largura) */
      transform:translateX(-3%);
      max-width:calc(100% + 200px);
      z-index:2;
    }

    /* palavra de fundo menor e contida no quadro */
    .hero::before{
      content:"WORKSHOP";
      position:absolute;
      top:-4%;
      left:50%;
      transform:translateX(-50%);
      font-family:'Playfair Display',serif;
      font-weight:800;
      font-size:clamp(80px,10vw,130px);
      color:rgba(15,76,129,0.05);
      pointer-events:none;
      user-select:none;
      z-index:0;
    }

    h1.title{
      font-family:'Playfair Display',serif;
      font-size:clamp(36px,6vw,80px);
      line-height:1.02;
      color:var(--blue-deep);
      max-width:760px;
      margin:0 auto;
      text-align:center;
      z-index:3;
    }

    .title-sub{
      margin-top:14px;
      color:var(--muted);
      font-size:17px;
      max-width:760px;
      text-align:center;
    }

    .underline{
      width:220px;height:12px;border-radius:999px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));
      margin:18px auto 0;
    }

    .hero-ctas{
      display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;justify-content:center;
    }
    .btn{border-radius:12px;padding:14px 18px;font-weight:800;font-size:15px;cursor:pointer;border:0}
    .btn-primary{background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff}
    .btn-alt{background:transparent;border:1px solid rgba(15,76,129,0.08);color:var(--muted)}

    /* contagem regressiva */
    .countdown-float{
      position:fixed;left:18px;bottom:18px;
      background:linear-gradient(90deg,var(--blue-deep),var(--blue-2));color:#fff;
      padding:12px 16px;border-radius:12px;font-weight:800;
      box-shadow:0 20px 46px rgba(15,76,129,0.22);z-index:1004;text-align:center;
    }
    .countdown-float .time{font-size:18px;}
    .countdown-float .label{font-size:12px;opacity:.9}

    /* botão WhatsApp */
    .whatsapp-float{
      position:fixed;right:18px;bottom:80px;background:#25D366;color:#fff;border-radius:999px;
      padding:12px 16px;font-weight:800;box-shadow:0 20px 46px rgba(0,0,0,0.18);
      z-index:1005;display:flex;gap:10px;align-items:center;font-size:15px;border:0;cursor:pointer;
    }

    /* faixa final */
    .final-band{width:100%;background:linear-gradient(180deg,var(--blue-deep),#0A3C66);color:#fff;padding:48px 0;margin-top:40px;text-align:center}
    .final-band h2{font-family:'Playfair Display',serif;font-size:clamp(28px,6vw,52px);line-height:1.1;margin:0 auto;max-width:900px}

    footer{text-align:center;padding:28px 0;color:var(--muted);font-size:13px}
  </style>
</head>
<body>
  <div class="wrap">
    <main class="hero">
      <h1 class="title">Antes de virar o ano, quero estar em paz comigo.</h1>
      <div class="underline"></div>
      <p class="title-sub">Dias 2, 3 e 4 de dezembro • às 20h — três noites para encerrar 2025 com leveza, soltar o que pesa e se reencontrar consigo mesma antes de entrar em 2026.</p>
      <div class="hero-ctas">
        <button class="btn btn-primary" onclick="openGroup()">Já tomei minha decisão</button>
        <button class="btn btn-primary" onclick="openGroup()">Quero me inscrever agora</button>
        <button class="btn btn-alt" onclick="scrollMentor()">Ainda estou com dúvida</button>
      </div>
    </main>
  </div>

  <div class="final-band">
    <h2>Antes de virar o ano, quero estar em paz comigo.</h2>
    <p>Três noites práticas (2, 3 e 4 de dezembro • 20h) para encerrar 2025 com leveza e entrar em 2026 com mais paz.</p>
  </div>

  <div class="countdown-float" id="countdown">
    <div style="font-size:12px;opacity:.95">Próximo encontro</div>
    <div class="time" id="cd-time">-- dias — --:--:--</div>
    <div class="label">02 Dez • 20h</div>
  </div>

  <button class="whatsapp-float" onclick="openGroup()">
    <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><path fill='%23fff' d='M20.52 3.478A11.943 11.943 0 0 0 12 .5C6.201.5 1.5 5.2 1.5 11c0 1.948.49 3.827 1.422 5.505L.5 23.5l6.984-2.243A11.45 11.45 0 0 0 12 22.5c5.799 0 10.5-4.7 10.5-10.5 0-1.87-.45-3.632-1.98-5.022zM12 20.5c-1.07 0-2.104-.2-3.07-.585l-.224-.094-4.147 1.33 1.28-3.86-.12-.247A8.5 8.5 0 1 1 20.5 11 8.48 8.48 0 0 1 12 20.5z'/></svg>" alt="" style="width:20px;height:20px">
    Entrar no grupo
  </button>

  <footer>© 2025 — Workshop “Antes de virar o ano, quero estar em paz comigo.”</footer>

  <script>
    const whatsappGroupUrl = 'https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp';
    function openGroup(){ window.open(whatsappGroupUrl,'_blank'); }

    const targetDate = new Date(2025, 11, 2, 20, 0, 0);
    function updateCountdown(){
      const now = new Date();
      const diff = targetDate - now;
      const el = document.getElementById('cd-time');
      if(diff <= 0){ el.textContent = "Começou — veja no grupo"; return; }
      const d = Math.floor(diff / (1000*60*60*24));
      const h = Math.floor((diff / (1000*60*60)) % 24);
      const m = Math.floor((diff / (1000*60)) % 60);
      const s = Math.floor((diff / 1000) % 60);
      el.textContent = `${d}d — ${String(h).padStart(2,'0')}:${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}`;
    }
    updateCountdown(); setInterval(updateCountdown,1000);
  </script>
</body>
</html>
