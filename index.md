<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>StarPolaris OS — Hoshimiya Script</title>
</head>

<style>
  /* ------------------------------
      GLOBAL
  ------------------------------*/
  body {
    margin: 0;
    padding: 0;
    font-family: "Segoe UI", Helvetica, Arial, sans-serif;
    color: #f8f3e8;
    background:
      radial-gradient(circle at top, rgba(255, 215, 128, 0.12) 0, transparent 60%),
      radial-gradient(circle at bottom, rgba(255, 160, 64, 0.18) 0, transparent 55%),
      #050712;
    background-attachment: scroll;
    line-height: 1.7;
  }

  .container {
    max-width: 900px;
    margin: 20px auto;
    padding: 20px 16px 24px;
    background: rgba(3, 6, 18, 0.92);
    border-radius: 24px;
    box-shadow: 0 30px 80px rgba(0, 0, 0, 0.9);
    border: 1px solid rgba(255, 204, 128, 0.16);
    backdrop-filter: blur(10px);
    box-sizing: border-box;
  }

  /* ------------------------------
      HEADINGS
  ------------------------------*/
  h1 {
    font-size: 2.6em;
    text-align: center;
    color: #ffe7b3;
    margin-top: 0;
    text-shadow:
      0 0 18px rgba(255, 180, 90, 0.55),
      0 0 40px rgba(0, 0, 0, 0.9);
  }

  h2 {
    font-size: 1.7em;
    margin-top: 42px;
    padding-bottom: 6px;
    border-bottom: 1px solid rgba(255, 210, 140, 0.35);
  }

  a {
    color: #ffdf99;
    font-weight: 600;
    text-decoration: none;
  }
  a:hover { text-decoration: underline; }

  .small-note {
    opacity: 0.8;
    font-size: 0.9em;
  }

  /* ------------------------------
      LOGO
  ------------------------------*/
  .logo-wrap { text-align: center; margin: 32px 0 18px; }

  .logo-glow {
    max-width: 280px;
    width: 70%;
    height: auto;
    filter:
      drop-shadow(0 0 10px rgba(255, 190, 120, 0.55))
      drop-shadow(0 0 28px rgba(255, 160, 64, 0.4));
    animation: logoPulse 7s ease-in-out infinite;
  }

  @keyframes logoPulse {
    0% { transform: scale(1); }
    50% {
      transform: scale(1.03);
      filter:
        drop-shadow(0 0 26px rgba(255, 210, 150, 0.9))
        drop-shadow(0 0 50px rgba(255, 180, 90, 0.7));
    }
    100% { transform: scale(1); }
  }

  /* ------------------------------
      PHOENIX BUTTON 🔥
  ------------------------------*/
  .phoenix-button {
    display: inline-block;
    margin: 25px auto 10px;
    padding: 14px 24px;
    border-radius: 14px;
    font-size: 1.1em;
    font-weight: 700;
    color: #fff;
    background: linear-gradient(135deg, #b86a00, #ffb84d, #cc7a00);
    text-decoration: none;
    box-shadow:
      0 0 14px rgba(255, 180, 80, 0.4),
      0 0 30px rgba(255, 160, 64, 0.25);
    transition: 0.28s ease;
    border: 1px solid rgba(255, 200, 120, 0.4);
  }

  .phoenix-button:hover {
    transform: translateY(-3px) scale(1.04);
    background: linear-gradient(135deg, #ffcc66, #ffb347, #ffa533);
    box-shadow:
      0 0 22px rgba(255, 200, 110, 0.85),
      0 0 60px rgba(255, 160, 64, 0.55);
    text-shadow: 0 0 12px rgba(255, 255, 220, 0.85);
  }

  /* ------------------------------
      SECTION BOX
  ------------------------------*/
  .section-box {
    margin-top: 18px;
    padding: 14px 16px;
    border-radius: 14px;
    background: rgba(9, 13, 32, 0.96);
    border: 1px solid rgba(255, 215, 128, 0.12);
  }

  pre {
    white-space: pre-wrap;
    background: rgba(0, 0, 0, 0.35) !important;
    border: 1px solid rgba(255, 210, 120, 0.35) !important;
    color: #ffe7bb !important;
    padding: 18px !important;
    border-radius: 12px !important;
    box-shadow: 0 0 18px rgba(255, 180, 80, 0.15);
    overflow-x: auto;
  }

  /* ------------------------------
      RESPONSIVE
  ------------------------------*/
  @media (max-width: 768px) {
    .container { padding: 15px 10px 20px; max-width: 95%; margin: 10px auto; }
    h1 { font-size: 2em; }
    h2 { font-size: 1.4em; }
    .logo-glow { width: 80%; max-width: 260px; }
    .phoenix-button { font-size: 1em; padding: 12px 18px; }
  }

  @media (max-width: 480px) {
    .container { padding: 10px 8px 15px; }
    h1 { font-size: 1.8em; }
    .section-box { padding: 10px 12px; }
  }
</style>

<!-- ------------------------------
     PAGE BODY
------------------------------- -->

<div class="container">

  <p class="logo-wrap">
    <img src="logo.png" class="logo-glow" alt="StarPolaris OS – Phoenix Emblem" />
  </p>

  <h1>🌌 StarPolaris OS — Hoshimiya Script</h1>

  <!-- ⭐ PHOENIX BUTTON HERE -->
  <p style="text-align:center;">
    <a class="phoenix-button"
       href="https://github.com/StarPolaris9/Hoshimiya-script">
      🔥 Official GitHub Repository — StarPolaris OS
    </a>
  </p>

  <p><b>
    Multi-layer internal AI architecture (Type-G Trinity / ResonanceOS).<br>
    Designed by Hoshimiya. Reproducible inside modern LLMs.
  </b></p>


  <!-- あとは現在の本文がそのまま続く（省略せず貼ってOK） -->
