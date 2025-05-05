<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AltVerse</title>
  <link href="https://fonts.googleapis.com/css2?family=Urbanist:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Urbanist', sans-serif;
      background: linear-gradient(to right, #0f0f10, #1a1a1d);
      color: #f0f0f0;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    header {
      background: rgba(255, 255, 255, 0.05);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    header h1 { font-size: 1.8rem; font-weight: 700; color: #ffffff; }
    nav a {
      color: #ccc;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    nav a:hover { color: #fff; }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: url('https://images.unsplash.com/photo-1625871061220-4c9edbd30f39') no-repeat center center;
      background-size: cover;
    }
    .hero h2 {
      font-size: 2.5rem;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.1rem;
      max-width: 600px;
      margin: 0 auto;
      color: #ccc;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background: #1a1a1d;
      padding: 60px 20px;
      gap: 30px;
    }
    .feature-card {
      background: rgba(255, 255, 255, 0.05);
      padding: 30px;
      border-radius: 15px;
      width: 300px;
      box-shadow: 0 0 10px rgba(0,0,0,0.4);
      transition: transform 0.2s ease;
    }
    .feature-card:hover {
      transform: translateY(-5px);
    }
    .feature-card h3 {
      font-size: 1.3rem;
      margin-bottom: 10px;
      color: #fff;
    }
    .feature-card p {
      font-size: 0.95rem;
      color: #bbb;
    }
    footer {
      background: rgba(255, 255, 255, 0.05);
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>AltVerse</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Universes</a>
      <a href="#">Bots</a>
      <a href="#">Login</a>
    </nav>
  </header>  <section class="hero">
    <h2>Live As Anyone. Anywhere.</h2>
    <p>Enter immersive fandom worlds, roleplay as your favorite characters, and chat with intelligent AI — all in one place.</p>
  </section>  <section class="features">
    <div class="feature-card">
      <h3>Fandom Universes</h3>
      <p>Pick a universe from anime, games, books, or create your own custom world with full lore and style.</p>
    </div>
    <div class="feature-card">
      <h3>AI Chat + RP</h3>
      <p>Talk to rich, intelligent bots powered by AI. Choose message length: Short, Medium, or Visual Novel.</p>
    </div>
    <div class="feature-card">
      <h3>In-Universe Feeds</h3>
      <p>Post photos, interact with other characters, and roleplay through an Instagram-style interface.</p>
    </div>
    <div class="feature-card">
      <h3>Bot Builder</h3>
      <p>Create your own characters with no word limit, add lore, behavior, and custom media. Make them public or private.</p>
    </div>
  </section>  <footer>
    &copy; 2025 AltVerse. All rights reserved.
  </footer>
</body>
</html>
