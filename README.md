<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tag Studio | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Outfit', sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: #111;
      color: #fff;
      padding: 1.5rem 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: #ccc;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 500;
    }
    nav a:hover {
      color: #fff;
    }
    main {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 4rem;
    }
    h2 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
    }
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }
    .project-card {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.08);
      overflow: hidden;
      transition: transform 0.2s;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    .project-card img {
      width: 100%;
      height: auto;
      display: block;
    }
    .project-card h3 {
      padding: 1rem;
      margin: 0;
      font-size: 1.2rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #111;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tag Studio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About</h2>
      <p>Hello! Welcome to Tag Studio. We’re a creative design studio specializing in visual identity, branding, and digital experiences. Check out some of our featured work below.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="project-grid">
        <div class="project-card">
          <img src="https://via.placeholder.com/400x250" alt="Project 1" />
          <h3>Project One</h3>
        </div>
        <div class="project-card">
          <img src="https://via.placeholder.com/400x250" alt="Project 2" />
          <h3>Project Two</h3>
        </div>
        <div class="project-card">
          <img src="https://via.placeholder.com/400x250" alt="Project 3" />
          <h3>Project Three</h3>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email us at <a href="mailto:hello@tagstudio.com">hello@tagstudio.com</a> or reach out on our social media.</p>
    </section>
  </main>

  <footer>
    &copy; 2025 Tag Studio. All rights reserved.
  </footer>
</body>
</html>
