<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Sahra Ourari</title>
  
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@400;500&display=swap" rel="stylesheet">
  
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #fff8f0; /* crème vintage doux */
      color: #3e3e3e;
    }

    a {
      text-decoration: none;
    }

    /* Header Section */
    header {
      text-align: center;
      padding: 80px 20px;
      background: #f2e8df; /* fond doux */
      color: #5e3b8b; /* vieux violet */
      background-image: url('assets/texture-light.png'); /* optionnel pour effet vintage subtil */
      background-size: cover;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header h2 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      font-weight: 400;
      font-style: italic;
      color: #7d5ba6;
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
      border-radius: 25px;
      background: #e6d5e8; /* lilas doux */
      color: #5e3b8b;
      font-weight: 600;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: all 0.3s ease;
    }

    .btn:hover {
      background: #5e3b8b;
      color: #fff;
      box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    }

    /* Section Styles */
    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    /* About Me */
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
      border: 5px solid #d8b4f5; /* bordure lilas doux */
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .about-text h2 {
      margin-bottom: 20px;
      font-family: 'Playfair Display', serif;
      color: #5e3b8b;
    }

    .about-text p {
      line-height: 1.6;
      font-size: 1rem;
    }

    /* Contact Info */
    .contact-info {
      margin-top: 20px;
    }

    .contact-info a {
      color: #5e3b8b;
      margin-right: 15px;
      font-weight: 500;
      transition: 0.3s;
    }

    .contact-info a:hover {
      color: #341f97;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #f2e8df;
      color: #5e3b8b;
      font-style: italic;
      box-shadow: 0 -2px 6px rgba(0,0,0,0.05);
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <h1>Hi, I'm Sahra Ourari</h1>
    <h2>Data Analyst | Data Engineer | AI Enthusiast</h2>
    <p>Transforming data into elegant insights with Python, SQL, and Power BI. Passionate about learning, creativity, and sharing impactful data projects.</p>
    <a href="cv.pdf" class="btn" target="_blank">View My CV</a>
    <a href="#contact" class="btn">Contact Me</a>
  </header>

  <!-- About Me -->
  <section class="section about" id="about">
    <img src="assets/photo.jpg" alt="Photo de Sahra">
    <div class="about-text">
      <h2>About Me</h2>
      <p>I am an aspiring Data Analyst, passionate about data and AI. My goal is to contribute to innovative projects by analyzing data and creating impactful visualizations. I love blending logic, creativity, and elegance in every project.</p>
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

