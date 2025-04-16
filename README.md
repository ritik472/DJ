<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DJ Archana & DJ Equine</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(120deg, #000000, #1a1a1a);
      color: #fff;
      overflow-x: hidden;
      animation: fadeIn 2s ease-in;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    header {
      background: #111;
      padding: 20px;
      text-align: center;
      font-size: 2em;
      color: #0ff;
      text-shadow: 0 0 10px #0ff, 0 0 20px #f0f;
      animation: glow 3s infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px #0ff; }
      to { text-shadow: 0 0 20px #f0f, 0 0 40px #0ff; }
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1518972559570-0bf2ed7fe217?auto=format&fit=crop&w=1950&q=80') center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      animation: zoomIn 2s ease-in-out;
    }
    @keyframes zoomIn {
      from { transform: scale(0.95); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
    .hero h1 {
      background: rgba(0, 0, 0, 0.6);
      padding: 20px;
      border-radius: 10px;
      font-size: 3em;
      color: #f0f;
      text-shadow: 0 0 10px #f0f;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
      animation: fadeInUp 1.5s ease-in-out;
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .playlist .song {
      background: #222;
      padding: 15px;
      margin: 15px auto;
      width: 90%;
      border-radius: 10px;
      box-shadow: 0 0 10px #333;
    }
    .playlist audio {
      width: 100%;
      outline: none;
    }
    .contact {
      background: #111;
      padding: 30px;
      border-top: 1px solid #333;
    }
    .contact a {
      display: inline-block;
      background: #25D366;
      padding: 10px 20px;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
      transition: background 0.3s ease;
    }
    .contact a:hover {
      background: #128C7E;
    }
    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>
  <header>DJ Archana & DJ Equine</header>
  <section class="hero">
    <h1>Feel the Vibe with Archana & Equine</h1>
  </section>

  <section class="section">
    <h2>Epic Party Moments</h2>
    <img src="https://images.unsplash.com/photo-1533106418989-88406c7cc8e1?auto=format&fit=crop&w=800&q=80" width="90%" alt="DJ Party">
  </section>

  <section class="section playlist">
    <h2>Bollywood Hits Playlist</h2>
    <div class="song">
      <p>1. Kesariya - Brahmastra</p>
      <audio controls src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3"></audio>
    </div>
    <div class="song">
      <p>2. Tum Mile - Tum Mile</p>
      <audio controls src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3"></audio>
    </div>
    <div class="song">
      <p>3. Apna Bana Le - Bhediya</p>
      <audio controls src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-3.mp3"></audio>
    </div>
    <div class="song">
      <p>4. Tujhe Kitna Chahne Lage</p>
      <audio controls src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-4.mp3"></audio>
    </div>
    <div class="song">
      <p>5. Shayad - Love Aaj Kal</p>
      <audio controls src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-5.mp3"></audio>
    </div>
  </section>

  <section class="section contact">
    <h2>Book Us Now</h2>
    <p>For double the fun with DJ Archana & DJ Equine, contact us today!</p>
    <a href="https://wa.me/919999999999" target="_blank">WhatsApp Us</a>
  </section>
</body>
</html>
