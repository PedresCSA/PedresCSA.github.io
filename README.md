  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Babylen Pedres | Sunset Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(to bottom, #ff9966, #ff5e62, #2c1053);
      color: #fff;
      overflow-x: hidden;
    }

    /* Sunset glow overlay */
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at top, rgba(255,255,255,0.15), transparent 60%);
      z-index: -1;
    }

    header {
      text-align: center;
      padding: 90px 20px;
      background: rgba(0,0,0,0.3);
      backdrop-filter: blur(6px);
    }

    header h1 {
      font-size: 3rem;
      color: #ffe259;
      text-shadow: 0 0 10px #ffb347, 0 0 25px #ff5e62;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #fcefee;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 20px 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ffe259;
      text-shadow: 0 0 10px #ffb347;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      color: #ffe259;
      margin-bottom: 25px;
      text-shadow: 0 0 10px #ffb347;
    }

    .card {
      background: rgba(255,255,255,0.1);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0,0,0,0.3);
      backdrop-filter: blur(6px);
      margin-bottom: 40px;
    }

    .info p {
      margin-bottom: 10px;
      font-size: 1rem;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background: #ff5e62;
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 600;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #ffe259;
      color: #2c1053;
      box-shadow: 0 0 15px #ffe259;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #fcefee;
      font-size: 0.9rem;
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <h1>Babylen Pedres</h1>
    <p>Student | Aspiring Professional | Lifelong Learner</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About Me</a>
    <a href="#goal">My Goal</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <div class="card">
      <h2>All About Me</h2>
      <p>
        Hello! I am <strong>Babylen Pedres</strong>, 20 years old, currently living in
        <strong>Balanac, Ligao City</strong>. I am a motivated student who believes in
        continuous growth, self-improvement, and learning through experience.
        I strive to stay positive, focused, and dedicated in everything I do.
      </p>
    </div>
  </section>

  <!-- Goal Section -->
  <section id="goal">
    <div class="card">
      <h2>My Goal</h2>
      <p>
        My goal is to become a determined and successful student who consistently
        works hard to achieve academic excellence. I aim to develop my skills,
        overcome challenges with perseverance, and use my education to build a
        better future for myself and my community.
      </p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="card contact">
      <h2>Contact Information</h2>
      <div class="info">
        <p><strong>Address:</strong> Balanac, Ligao City</p>
        <p><strong>Age:</strong> 20</p>
        <p><strong>Email:</strong> babylenpedres@gmail.com</p>
      </div>

      <a href="mailto:babylenpedres@gmail.com">Send Email</a>
    </div>
  </section>

  <footer>
    &copy; 2026 Babylen Pedres. All rights reserved.
  </footer>

</body>
</html>
