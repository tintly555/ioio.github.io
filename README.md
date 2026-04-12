# ioio.github.io
一个游戏网站
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Games</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
      text-align: center;
    }

    header {
      padding: 40px 20px 20px;
    }

    h1 {
      margin: 0;
      font-size: 42px;
    }

    p {
      color: #ccc;
    }

    .game-list {
      max-width: 900px;
      margin: 30px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .game-card {
      display: block;
      background: #222;
      color: white;
      text-decoration: none;
      border-radius: 16px;
      padding: 28px 20px;
      transition: transform 0.2s, background 0.2s;
      box-shadow: 0 6px 18px rgba(0,0,0,0.35);
    }

    .game-card:hover {
      background: #333;
      transform: translateY(-4px);
    }

    .game-title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .game-desc {
      font-size: 15px;
      color: #bbb;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Games</h1>
    <p>点击按钮开始游戏</p>
  </header>

  <main class="game-list">
    <a class="game-card" href="games/territorial/index.html">
      <div class="game-title">Territorial</div>
      <div class="game-desc">点击进入游戏</div>
    </a>
  </main>
</body>
</html>
