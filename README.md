<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VizionEcho – Data That Speaks</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Inter:wght@300;400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #f4f4f4;
      color: #1f2937;
      line-height: 1.6;
    }

    header {
      background-color: #111827;
      padding: 1.2rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: #fff;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 1.8rem;
      letter-spacing: 1px;
    }

    nav a {
      color: #d1d5db;
      text-decoration: none;
      margin-left: 1.5rem;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #facc15;
    }

    .hero {
      text-align: center;
      padding: 6rem 2rem 3rem;
      background: linear-gradient(to right, #fff, #f9fafb);
    }

    .hero h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.8rem;
      color: #111827;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      color: #4b5563;
    }

    .video-section {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: 0 auto;
    }

    .video-section h3 {
      text-align: center;
      font-size: 1.6rem;
      margin-bottom: 1rem;
    }

    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      border-radius: 1rem;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    }

    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: none;
    }

    footer {
      background-color: #111827;
      color: #d1d5db;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>VizionEcho</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Series</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Data That Speaks. Stories That Matter.</h2>
    <p>Uncovering Africa’s realities through data-driven narratives that inspire change.</p>
  </section>

  <section class="video-section">
    <h3>🎥 Featured Episode</h3>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
    </div>
  </section>

  <footer>
    &copy; 2025 VizionEcho. All rights reserved.
  </footer>

</body>
</html>
