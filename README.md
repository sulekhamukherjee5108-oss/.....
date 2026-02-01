<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday ❤️</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Poppins', sans-serif; }
    body {
      min-height: 100vh;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
      overflow: hidden;
    }
    .card {
      background: rgba(255,255,255,0.15);
      backdrop-filter: blur(12px);
      border-radius: 20px;
      padding: 30px 22px;
      width: 90%;
      max-width: 420px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.25);
      animation: pop 1s ease;
    }
    @keyframes pop {
      from { transform: scale(0.8); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
    h1 { font-size: 2.2rem; margin-bottom: 10px; }
    h2 { font-weight: 400; margin-bottom: 18px; }
    p { font-size: 1rem; line-height: 1.6; margin-bottom: 22px; }
    .heart { font-size: 2rem; animation: beat 1.2s infinite; }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.25); }
    }
    button {
      border: none;
      padding: 12px 22px;
      border-radius: 30px;
      background: #fff;
      color: #ff4f7a;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover { transform: scale(1.05); }
    .hidden { display: none; }
  </style>
</head>
<body>
  <div class="card">
    <h1>🎂 Happy Birthday Abhirup 🎂</h1>
    <h2>From Suparna 💖</h2>
    <p>
      Abhirup, you make my world brighter just by being in it.
      With you, even ordinary days feel special.
      Thank you for being you — today and always.
    </p>
    <div class="heart">❤️</div>
    <br><br>
    <button onclick="reveal()">Tap for a surprise</button>
    <p id="surprise" class="hidden">
      I may tease you, annoy you, and act dramatic sometimes 😜
      but my heart always chooses you.
      <br><br>
      Happy Birthday, my love 🌙✨
      <br>— Suparna 💌
    </p>
  </div>  <script>
    function reveal() {
      document.getElementById('surprise').classList.remove('hidden');
    }
  </script></body>
</html>
