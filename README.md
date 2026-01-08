<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Babylen Pedres | Sunset Portfolio</title>
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
      background: linear-gradient(to bottom, #ff7e5f, #feb47b, #ff6a88, #8e2de2);
      color: #fff;
      overflow-x: hidden;
      min-height: 100vh;
    }

    /* Floating light particles */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background: radial-gradient(circle, rgba(255,255,255,0.15) 2px, transparent 2px);
      background-size: 60px 60px;
      animation: float 120s linear infinite;
      z-index: -1;
    }

    @keyframes float {
      from { background-position: 0 0; }
      to { background-position: 4000px 2000px; }
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: rgba(0,0,0,0.3);
      backdrop-filter: blur(6px);
    }

    header h1 {
      font-size: 3rem;
      color: #ffe29f;
      text-shadow: 0 0 15px #ff9a76;
    }

    header p {
      font-size: 1.2rem;
      color: #fbeaff;
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
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ffe29f;
      text-shadow: 0 0 10px #ffe29f;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      margin-bottom: 25px;
      color: #ffe29f;
      text-shadow: 0 0 10px #ff9a76;
    }

    .card {
      background: rgba(255,255,255,0.12);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 25px rgba(0,0,0,0.2);
      backdrop-filter: blur(6px);
      margin-bottom: 40px;
    }

    .skills ul {
      list-style: none;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      text-align: center;
    }

    .skills li {
      background: rgba(0,0,0,0.25);
      padding: 12px;
      border-radius: 8px;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background: #ff7e5f;
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #feb47b;
      box-shadow: 0 0 15px #ffe29f;
      color: #000;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #fbeaff;
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <h1>Babylen Pedres</h1>
    <p>Student | Aspiring Web Developer | Creative Learner</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#goal">Goal</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about">
    <div class="card">
      <h2>About Me</h2>
      <p>
        Hi! I’m <strong>Babylen Pedres</strong>, 20 years old and currently studying at
        <strong>Southern Luzon Technological College Foundation Pio Duran Inc.</strong>
        I am passionate about learning new technologies and improving my skills in web development.
        I enjoy exploring creative designs, building user-friendly websites, and continuously
        challenging myself to grow both personally and professionally.
        I believe that dedication, curiosity, and consistency are the keys to success.
      </p>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <div class="card skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML & CSS</li>
        <li>Basic JavaScript</li>
        <li>Responsive Web Design</li>
        <li>Creative UI Design</li>
        <li>Basic Computer Skills</li>
        <li>Teamwork & Communication</li>
      </ul>
    </div>
  </section>

  <!-- Goal Section -->
  <section id="goal">
    <div class="card">
      <h2>My Goal</h2>
      <p>
        My goal is to become a skilled and confident web developer who can create meaningful
        and impactful digital experiences. I want to continuously improve my technical knowledge,
        learn advanced programming skills, and gain real-world experience in the tech industry.
        In the future, I hope to work on projects that help people, inspire creativity, and
        contribute positively to society while achieving personal growth and career success.
      </p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="card contact">
      <h2>Contact Me</h2>
      <p>Feel free to reach out:</p>
      <a href="mailto:babylenpedres@gmail.com">Email</a>
    </div>
  </section>

  <footer>
    &copy; 2026 Babylen Pedres. All rights reserved.
  </footer>

</body>
</html>
