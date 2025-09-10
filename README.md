<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Sahra Ourari</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #ffdee9, #ffb6d9);
      color: #fff;
    }
    header {
      text-align: center;
      padding: 100px 20px;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      color: #fff;
    }
    header h2 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #ffe6f2;
    }
    header p {
      font-size: 1rem;
      margin-bottom: 20px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    .btn {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      border-radius: 30px;
      background: #fff;
      color: #c2185b;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn:hover {
      background: #c2185b;
      color: #fff;
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
    }
    .about img {
      border-radius: 50%;
      width: 200px;
      height: 200px;
      object-fit: cover;
      border: 5px solid #fff;
    }
    .about-text h2 {
      margin-bottom: 20px;
      color: #fff;
    }
    .about-text p {
      line-height: 1.6;
    }
    .contact-info {
      margin-top: 20px;
    }
    .contact-info p {
      margin: 5px 0;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #ff8ac0;
      color: #fff;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <h1>Hi, I'm Sahra Ourari 🌸</h1>
    <h2>Data Analyst | Ingénieure Data | Passionnée par l’IA</h2>
    <p>Je transforme les données en insights utiles grâce à Python, SQL et Power BI. 
       J’aime apprendre et partager mes projets data avec la communauté.</p>
    <a href="cv.pdf" class="btn" target="_blank">View My CV</a>
    <a href="#contact" class="btn">Contact Me</a>
  </header>

  <!-- About Me -->
  <section class="section about" id="about">
    <img src="assets/photo.jpg" alt="Photo de Sahra">
    <div class="about-text">
      <h2>About Me</h2>
      <p>Je suis une Data Analyst en devenir, passionnée par la data et l’intelligence artificielle. 
      Mon objectif est de contribuer à des projets innovants en analysant les données et en créant des visualisations impactantes.</p>
      <div class="contact-info" id="contact">
        <p>📍 Algérie</p>
        <p>📧 <a href="mailto:ourari@estin.dz" style="color:#fff;">ourari@estin.dz</a></p>
        <p>🔗 <a href="https://www.linkedin.com/in/sahra-ourari-3b628a303/" target="_blank" style="color:#fff;">LinkedIn</a></p>
        <p>💻 <a href="https://github.com/saku-bloom" target="_blank" style="color:#fff;">GitHub</a></p>
      </div>
    </div>
  </section>

  <footer>
    © 2025 - Fait avec 💖 par Sahra
  </footer>

</body>
</html>
