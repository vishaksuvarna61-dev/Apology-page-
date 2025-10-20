<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Heartfelt Apology with Hearts</title>
  <style>
    body {
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #4a2c2a;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      padding: 20px;
      text-align: center;
      overflow: hidden;
    }
    .container {
      background: rgba(255, 255, 255, 0.9);
      border-radius: 20px;
      padding: 40px 30px;
      max-width: 600px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
      animation: fadeInScale 1.5s ease forwards;
      line-height: 1.7;
      font-size: 1.2rem;
      white-space: pre-wrap;
      position: relative;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 15px;
      color: #b03060;
      letter-spacing: 1.2px;
      animation: colorPulse 3s infinite alternate;
      position: relative;
    }
    /* Heart styles */
    .hearts {
      margin: 20px 0;
      font-size: 3rem;
      display: flex;
      justify-content: center;
      gap: 25px;
    }
    .heart {
      animation: heartPulse 4s infinite, colorChange 6s infinite;
      cursor: default;
      user-select: none;
      filter: drop-shadow(0 0 2px rgba(0,0,0,0.1));
    }
    .heart:nth-child(2) {
      animation-delay: 1s, 2s;
    }
    .heart:nth-child(3) {
      animation-delay: 2s, 4s;
    }
    @keyframes fadeInScale {
      0% {
        opacity: 0;
        transform: scale(0.8);
      }
      100% {
        opacity: 1;
        transform: scale(1);
      }
    }
    @keyframes colorPulse {
      0% { color: #b03060; }
      100% { color: #ff6f91; }
    }
    @keyframes heartPulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    @keyframes colorChange {
      0% { color: #ff4d6d; }
      25% { color: #ff7b72; }
      50% { color: #ff5f9e; }
      75% { color: #e75480; }
      100% { color: #ff4d6d; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>My Heartfelt Apology</h1>
    <div class="hearts" aria-hidden="true">
      <span class="heart">❤</span>
      <span class="heart">❤</span>
      <span class="heart">❤</span>
    </div>
    <p>
      I am really sorry 😭😭aaruuu<br />
      Extremely sorrryyy<br />
      Bhadwa hu ek no kaaaa<br />
      Aur pagal, chutiyaaaa sabhhh<br />
      Meri he galti heee 😭👆🏻yaarr<br />
      Idhar in gharwaalo ki mk--- sahi mehh<br />
      I wanted to stayyy but bc<br />
      Kaha phas gaya meh in logo ke beech<br />
      Freedom naam ka toh unhe kuch pata bhi nehii!!<br />
      Sahi mehh kshamaaa kardooo madammm 😭😭😭🙏🏻<br />
      Sorrryyy, teko bhukaar bhi heee!!!<br />
      Jaldi theek ho jaana!!!<br />
      I am feeling too much guilty for not being there with you yesterday!!<br />
      But haan tonight, I will stay sachiiii!!<br />
      So I am sorry!! Please forgive me 😭!!
    </p>
  </div>
</body>
</html>
