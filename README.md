<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trisha Nabata | Galaxy Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background: radial-gradient(ellipse at bottom, #0b0c27 0%, #000 100%);
      color: #fff;
      overflow-x: hidden;
    }

    /* Stars animation background */
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: transparent url('https://i.ibb.co/2y0vVtQ/stars.png') repeat;
      z-index: -1;
      animation: moveStars 200s linear infinite;
    }

    @keyframes moveStars {
      0% {background-position: 0 0;}
      100% {background-position: -10000px 5000px;}
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: rgba(0,0,0,0.5);
      backdrop-filter: blur(5px);
    }

    header h1 {
      font-size: 3rem;
      color: #ff6ec7; /* Galaxy pink/purple */
      text-shadow: 0 0 10px #ff6ec7, 0 0 20px #8a2be2;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
      text-shadow: 0 0 5px #fff;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff6ec7;
      text-shadow: 0 0 10px #ff6ec7;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      color: #8a2be2;
      margin-bottom: 30px;
      text-shadow: 0 0 10px #8a2be2;
    }

    .about, .projects, .contact {
      margin-bottom: 50px;
      background: rgba(255,255,255,0.05);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(255,255,255,0.1);
      backdrop-filter: blur(5px);
    }

    .projects .project {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(138,43,226,0.5);
    }

    .projects .project h3 {
      color: #ff6ec7;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background: #8a2be2;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #ff6ec7;
      box-shadow: 0 0 15px #ff6ec7, 0 0 30px #8a2be2;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #ccc;
      text-shadow: 0 0 5px #fff;
    }

  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Trisha Nabata</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I'm Trisha Nabata, a passionate web developer inspired by the universe. I enjoy creating modern, interactive websites and bringing ideas to life with code. Constant learning and exploring new technologies are my favorite things!</p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>My Projects</h2>

    <div class="project">
      <h3>Project One</h3>
      <p>A brief description of your project goes here. Mention technologies used and what it does.</p>
    </div>

    <div class="project">
      <h3>Project Two</h3>
      <p>A brief description of your project goes here. Mention technologies used and what it does.</p>
    </div>

  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Reach out through any platform below:</p>
    <a href="mailto:nabatatrisha@gmail.com">Email</a>
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/yourprofile/" target="_blank">LinkedIn</a>
    <a href="YOUR_FACEBOOK_LINK_HERE" target="_blank">Facebook</a>
  </section>

  <footer>
    &copy; 2026 Trisha Nabata. All rights reserved.
  </footer>

</body>
</html>
