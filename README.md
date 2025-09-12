<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Sahra Ourari</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #f5f7fa, #e4e9f0);
      color: #333;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: #6c5ce7; /* violet doux */
      color: #fff;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header h2 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      font-weight: 400;
    }

    header p {
      font-size: 1rem;
      margin-bottom: 30px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    .btn {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      border-radius: 20px;
      background: #fff;
      color: #6c5ce7;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .btn:hover {
      background: #6c5ce7;
      color: #fff;
      box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    }

    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .about {
      display: flex;
      align-items: center;
      gap: 40px;
      flex-wrap: wrap;
    }

    .about img {
      border-radius: 50%;
      width: 200px;
      height: 200px;
      object-fit: cover;
      border: 5px solid #6c5ce7;
    }

    .about-text h2 {
      margin-bottom: 20px;
      color: #6c5ce7;
    }

    .about-text p {
      line-height: 1.6;
    }

    .contact-info {
      margin-top: 20px;
    }

    .contact-info a {
      text-decoration: none;
      color: #6c5ce7;
      margin-right: 15px;
      font-weight: 500;
      transition: 0.3s;
    }

    .contact-info a:hover {
      color: #341f97;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #6c5ce7;
      color: #fff;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <h1>Hi, I'm Sahra Ourari</h1>
    <h2>Data Analyst | Data Engineer | AI Enthusiast</h2>
    <p>Transforming data into actionable insights with Python, SQL, and Power BI. Passionate about learning and sharing innovative data projects.</p>
    <a href="cv.pdf" class="btn" target="_blank">View My CV</a>
    <a href="#contact" class="btn">Contact Me</a>
  </header>

  <!-- About Me -->
  <section class="section about" id="about">
    <img src="assets/photo.jpg" alt="Photo de Sahra">
    <div class="about-text">
      <h2>About Me</h2>
      <p>I am an aspiring Data Analyst, passionate about data and AI. My goal is to contribute to innovative projects by analyzing data and creating impactful visualizations.</p>
      <div class="contact-info" id="contact">
        <a href="mailto:ourari@estin.dz">📧 Email</a>
        <a href="https://www.linkedin.com/in/sahra-ourari-3b628a303/" target="_blank">LinkedIn</a>
        <a href="https://github.com/saku-bloom" target="_blank">GitHub</a>
        <a href="https://wa.me/213779406611" target="_blank">WhatsApp</a>
      </div>
    </div>
  </section>

  <footer>
    © 2025 - Made with ❤️ by Sahra
  </footer>

</body>
</html>
