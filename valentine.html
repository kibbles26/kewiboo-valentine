<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Valentine ❤️</title>

  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ffb6c1, #ffc0cb);
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Pacifico', cursive;
    }

    .page {
      display: none;
      text-align: center;
      background: rgba(255,255,255,0.9);
      padding: 40px 60px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      animation: fadeIn 1s ease;
    }

    .page.active {
      display: block;
    }

    h1 {
      font-size: 48px;
      color: #ff4d6d;
    }

    p {
      font-size: 22px;
      color: #444;
      margin-top: 15px;
    }

    button {
      font-size: 18px;
      padding: 10px 26px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      transition: 0.3s;
      margin: 10px;
    }

    #Yes {
      background: #2ecc71;
      color: white;
      box-shadow: 0 0 15px rgba(46,204,113,0.8);
      animation: pulse 1.2s infinite;
    }

    #Yes:hover {
      transform: scale(1.15);
    }

    #No {
      background: #e74c3c;
      color: white;
      position: fixed;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.08); }
      100% { transform: scale(1); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }

    /* Floating hearts */
    .heart {
      position: absolute;
      font-size: 20px;
      animation: floatUp 6s linear infinite;
      opacity: 0.8;
    }

    @keyframes floatUp {
      0% { transform: translateY(100vh); opacity: 0; }
      50% { opacity: 1; }
      100% { transform: translateY(-10vh); opacity: 0; }
    }
  </style>
</head>

<body>

  <!-- PAGE 1 -->
  <div class="page active" id="page1">
    <h1>Will you be my Valentine? ❤️</h1>
    <button id="Yes">Yes!</button>
    <button id="No">No🥹</button>
  </div>

  <!-- PAGE 2 (FINAL MESSAGE) -->
  <div class="page" id="page2">
    <h1>Yaayyy, Thank you, My Bebi boo! 💖</h1>
    <p>
      I love you see you soon.<br><br>
      I can't wait to see you soon hihihi,<br>
      and make this Valentine’s Day special! 🌹 <br>



    </p>
    <p>See you soon my labbbbb ❤️</p>
  </div>

  <script>
    /* ===== SOUND EFFECTS ===== */
    const audioCtx = new (window.AudioContext || window.webkitAudioContext)();

    function playSound(freq, duration) {
      const osc = audioCtx.createOscillator();
      const gain = audioCtx.createGain();
      osc.connect(gain);
      gain.connect(audioCtx.destination);
      osc.frequency.value = freq;
      osc.type = "sine";
      gain.gain.value = 0.15;
      osc.start();
      osc.stop(audioCtx.currentTime + duration);
    }

    /* YES BUTTON */
    document.getElementById("Yes").addEventListener("click", () => {
      playSound(880, 0.3); // happy sound
      setTimeout(() => playSound(1320, 0.2), 200);

      document.getElementById("page1").classList.remove("active");
      document.getElementById("page2").classList.add("active");
    });

    /* NO BUTTON */
    const noBtn = document.getElementById("No");
    noBtn.addEventListener("mouseenter", () => {
      playSound(400, 0.15); // boop sound

      const maxX = window.innerWidth - noBtn.offsetWidth;
      const maxY = window.innerHeight - noBtn.offsetHeight;

      noBtn.style.left = Math.random() * maxX + "px";
      noBtn.style.top = Math.random() * maxY + "px";
    });

    /* FLOATING HEARTS */
    setInterval(() => {
      const heart = document.createElement("div");
      heart.className = "heart";
      heart.innerHTML = "❤️";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (4 + Math.random() * 3) + "s";
      document.body.appendChild(heart);
      setTimeout(() => heart.remove(), 7000);
    }, 500);
  </script>

</body>
</html>
