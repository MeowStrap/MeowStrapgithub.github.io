<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MeowStrap </title>
  <style>
    :root {
      --bg-color: #fdfbf7;
      --card-bg: #ffffff;
      --primary: #ff9f8f;
      --secondary: #ffe4cc;
      --text: #3a2f2a;
      --accent: #5d4037;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Segoe UI', Roboto, Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: white;
      border-bottom-left-radius: 20px;
      border-bottom-right-radius: 20px;
      box-shadow: 0 4px 12px rgba(255, 159, 143, 0.3);
    }

    h1 { font-size: 2.4rem; margin-bottom: 10px; }
    p.subtitle { font-size: 1.1rem; opacity: 0.9; }

    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 15px;
    }

    .card {
      background: var(--card-bg);
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 6px 20px rgba(58, 47, 42, 0.08);
      margin-bottom: 30px;
    }

    h2 { color: var(--accent); margin-bottom: 15px; border-left: 5px solid var(--primary); padding-left: 12px; }

    ul { list-style: none; }
    ul li {
      position: relative;
      padding-left: 28px;
      margin-bottom: 10px;
    }
    ul li::before {
      content: "       position: absolute;
      left: 0;
    }

    a.btn {
      display: inline-block;
      background-color: var(--primary);
      color: white;
      padding: 14px 24px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      transition: transform 0.2s, background-color 0.2s;
      margin-top: 10px;
    }
    a.btn:hover {
      background-color: #ff8b7b;
      transform: translateY(-2px);
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #888;
      font-size: 0.9rem;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      h1 { font-size: 1.8rem; }
      .card { padding: 20px; }
    }
  </style>
</head>
<body>

  <header>
    <h1>MeowStrap</h1>
    <p class="subtitle"></p>
  </header>

  <div class="container">
    <section class="card">
      <h2>About the project</h2>
      <p>MeowStrap (Fork a FishStrap).</p>
    </section>



    <section class="card">
      <h2>Download the latest version</h2>
      <p>Go to the releases page to download the latest files:</p>
      <a href="https://github.com/MeowStrap/MeowStrap-ROBLOX/releases" class="btn" target="_blank">Go to the releases on GitHub       </section>
  </div>

  <footer>
    &copy;  </footer>

</body>
</html>
