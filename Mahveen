<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BiBi Mahveen ❤️</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ffe6f0, #fff8fc);
      color: #5b3044;
      text-align: center;
      overflow-x: hidden;
    }

    .container {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 25px;
    }

    .card {
      width: 100%;
      max-width: 650px;
      background: rgba(255,255,255,0.92);
      border-radius: 30px;
      padding: 40px 25px;
      box-shadow: 0 15px 50px rgba(120,60,90,0.18);
    }

    .heart {
      font-size: 65px;
      animation: heartbeat 1.3s infinite;
    }

    h1 {
      color: #d65b91;
      font-size: 38px;
      margin: 15px 0 5px;
    }

    h2 {
      color: #8d526d;
      font-size: 28px;
      margin: 5px 0 20px;
    }

    .date {
      display: inline-block;
      background: #ffe0ec;
      padding: 12px 20px;
      border-radius: 30px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      line-height: 1.7;
    }

    .love {
      font-size: 21px;
      color: #d65b91;
      font-weight: bold;
      margin-top: 25px;
    }

    button {
      border: none;
      padding: 13px 22px;
      margin: 8px 4px;
      border-radius: 30px;
      background: #d65b91;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    button:active {
      transform: scale(0.96);
    }

    #surprise {
      margin-top: 20px;
      font-size: 20px;
      font-weight: bold;
      color: #d65b91;
      min-height: 30px;
    }

    .footer {
      margin-top: 30px;
      font-size: 14px;
      opacity: 0.7;
    }

    .floating-heart {
      position: fixed;
      bottom: -30px;
      font-size: 22px;
      animation: floatUp 7s linear infinite;
      pointer-events: none;
    }

    @keyframes heartbeat {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.15);
      }
    }

    @keyframes floatUp {
      from {
        transform: translateY(0);
        opacity: 1;
      }

      to {
        transform: translateY(-110vh);
        opacity: 0;
      }
    }
  </style>
</head>

<body>

  <div class="container">
    <div class="card">

      <div class="heart">❤️</div>

      <h1>Welcome, My Little Princess</h1>

      <h2>BiBi Mahveen 🌸</h2>

      <div class="date">
        Born on 26 May 2026 👶💕
      </div>

      <p>
        MashaAllah! Welcome to this beautiful world,
        our little princess. 🌷
      </p>

      <p>
        You are a precious blessing and a beautiful
        reason for endless smiles and happiness.
      </p>

      <div class="love">
        Lots of Love from<br>
        Baba Zain Ghani ❤️
      </div>

      <br>

      <button onclick="showSurprise()">
        Tap for a Surprise 💕
      </button>

      <button onclick="musicMessage()">
        🎵 Music ON / OFF
      </button>

      <div id="surprise"></div>

      <div class="footer">
        Made with ❤️ especially for BiBi Mahveen
      </div>

    </div>
  </div>

  <script>

    function showSurprise() {
      document.getElementById("surprise").innerHTML =
        "You are loved more than words can ever say! 🥰❤️";
    }

    function musicMessage() {
      document.getElementById("surprise").innerHTML =
        "🎵 Music button is ready! Add your music file as <b>music.mp3</b> to enable it.";
    }

    function createHeart() {
      const heart = document.createElement("div");

      heart.className = "floating-heart";
      heart.innerHTML = Math.random() > 0.5 ? "❤️" : "🌸";

      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration =
        (5 + Math.random() * 5) + "s";

      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 10000);
    }

    setInterval(createHeart, 1200);

  </script>

</body>
</html>
