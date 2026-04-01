<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Freddy Sitorus | Resume</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #222;
    }

    .navbar {
      background: #ffffff;
      padding: 15px 30px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
      position: sticky;
      top: 0;
    }

    .navbar ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      gap: 20px;
    }

    .navbar a {
      text-decoration: none;
      color: #222;
      font-weight: bold;
    }

    .navbar a:hover {
      color: #0a66c2;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 14px rgba(0, 0, 0, 0.08);
      overflow: hidden;
    }

    .hero {
      display: flex;
      align-items: center;
      gap: 30px;
      padding: 40px;
      flex-wrap: wrap;
    }

    .hero img {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #0a66c2;
    }

    .hero-text {
      flex: 1;
      min-width: 250px;
    }

    .hero-text h1 {
      margin: 0 0 10px;
      font-size: 2.2rem;
    }

    .hero-text p {
      line-height: 1.7;
      color: #444;
      font-size: 1.05rem;
    }

    .section {
      padding: 30px 40px;
      border-top: 1px solid #eee;
    }

    .section h2 {
      margin-top: 0;
      color: #0a66c2;
    }
  </style>
</head>
<body>

  <nav class="navbar">
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <div class="container">
    <section class="hero" id="about">
      <img src="picture.jpg" alt="Your profile photo" />
      <div class="hero-text">
        <h1>Your Name</h1>
        <p>
          Hi, I’m Fred, a finance and development professional with research expertise in quantitative economic analysis, econometrics, and large-scale data management. My research focuses on the intersection of development economics, development finance, and public policy.
        </p>
      </div>
    </section>

    <section class="section" id="skills">
      <h2>Skills</h2>
      <p>HTML, CSS, JavaScript, Communication, Teamwork</p>
    </section>

    <section class="section" id="projects">
      <h2>Projects</h2>
      <p>Add your projects here.</p>
    </section>

    <section class="section" id="contact">
      <h2>Contact</h2>
      <p>Email: fs2826@columbia.edu</p>
    </section>
  </div>

</body>
</html>
