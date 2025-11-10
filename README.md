<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vivência de Fim de Ano — Em Paz Comigo</title>
  <meta name="description" content="Antes de virar o ano, quero estar em paz comigo. Uma vivência em três noites para soltar o que pesa, cuidar do que importa e recomeçar em leveza.">
  <style>
    :root {
      --rose: #C9376E;
      --blue: #4DA6FF;
      --ink: #0F172A;
      --soft: #667085;
      --bg: #FFFFFF;
      --line: #E9EEF5;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
      background: var(--bg);
      color: var(--ink);
      line-height: 1.6;
    }

    img { max-width: 100%; display: block; }

    /* HERO */
    .hero {
      position: relative;
      height: 70vh;
      background: url('WhatsApp Image 2025-11-10 at 09.08.40.jpeg') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }
    .hero::after {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.45);
    }
    .hero-content {
      position: relative;
      z-index: 1;
      max-width: 800px;
      padding: 0 16px;
    }
    .hero h1 {
      font-size: clamp(28px, 5vw, 48px);
      font-weight: 900;
      margin-bottom: 12px;
    }
    .hero p {
      font-size: clamp(16px, 2.2vw, 20px);
      font-weight: 400;
    }

    /* SECTIONS */
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: 0 auto;
    }

    .intro {
      text-align: center;
      color: var(--soft);
      font-size: 20px;
      max-width: 760px;
      margin: 0 auto 40px;
    }

    .nights {
      display: grid;
      gap: 32px;
    }
    @media(min-width: 860px) {
      .nights {
        grid-template-columns: repeat(3, 1fr);
      }
    }

    .night-card {
      background: #fff;
      border: 1px solid var(--line);
      border-radius: 18px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.05);
      padding: 24px;
      text-align: left;
    }

    .night-card h2 {
      font-size: 22px;
      margin-bottom: 8px;
      background: linear-gradient(90deg, var(--rose), var(--blue));
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      font-weight: 900;
    }

    .night-card p {
      color: var(--soft);
      font-size: 18px;
    }

    /* CTA */
    .cta {
      text-align: center;
      margin-top: 60px;
    }
    .btn {
      display: inline-block;
      background: var(--rose);
      color: #fff;
      padding: 14px 26px;
      border-radius: 14px;
      font-weight: 700;
      font-size: 18px;
      text-decoration: none;
      transition: 0.3s ease;
    }
    .btn:hover {
      filter: brightness(1.1);
    }

    /* FOOTER */
    footer {
      background: var(--rose);
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h1>Antes de virar o ano, quero estar em paz comigo.</h1>
      <p>Uma vivência em três noites para soltar o que pesa, cuidar do que importa e recomeçar com leveza.</p>
    </div>
  </section>

  <!-- INTRO -->
  <section>
    <p class="intro">
      Três encontros para encerrar o ciclo com consciência e coração leve.
      Um espaço de reconexão, cuidado e propósito para que 2026 comece em paz — de dentro para fora.
    </p>

    <div class="nights">
      <div class="night-card">
        <h2>1ª Noite — O peso que ainda carrego</h2>
        <p>Reconhecer mágoas, culpas e cobranças que já não cabem mais. Dar nome é o primeiro passo para libertar.</p>
      </div>
      <div class="night-card">
        <h2>2ª Noite — Quando soltar é cuidar</h2>
        <p>Práticas guiadas de soltura e autocuidado. Aprender a pausar, confiar e restaurar energia.</p>
      </div>
      <div class="night-card">
        <h2>3ª Noite — O recomeço que nasce da paz</h2>
        <p>Ritual prático para transformar o vivido em sabedoria e escolher intenções para 2026.</p>
      </div>
    </div>

    <div class="cta">
      <a href="https://wa.me/5549998110445?text=Quero%20participar%20da%20Viv%C3%AAncia%20Em%20Paz%20Comigo" class="btn" target="_blank" rel="noopener">Quero participar</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2025 EA favoretto LTDA — Todos os direitos reservados.
  </footer>

</body>
</html>
