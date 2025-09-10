<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfolio • Sahra Ourari</title>
  <style>
    :root{
      --pink1:#ffeef6;
      --pink2:#ffd0ea;
      --accent:#d6336c;
      --card:#ffffff;
      --text:#222;
      --muted:#6b6b6b;
      --shadow: 0 8px 24px rgba(0,0,0,0.08);
      --radius:14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter, "Segoe UI", Roboto, Arial, sans-serif;background:linear-gradient(180deg,var(--pink1),#fff);color:var(--text);}

    .wrap{
      max-width:1100px;margin:30px auto;padding:20px;display:grid;grid-template-columns:320px 1fr;gap:28px;
    }

    /* SIDEBAR (colonne gauche) */
    .sidebar{
      background:var(--card);border-radius:var(--radius);padding:22px;box-shadow:var(--shadow);
      display:flex;flex-direction:column;align-items:center;height:calc(100vh - 90px);
    }
    .profile-img{width:160px;height:160px;border-radius:50%;overflow:hidden;border:6px solid rgba(255,255,255,0.9);box-shadow:0 8px 20px rgba(198,67,111,0.12)}
    .profile-img img{width:100%;height:100%;object-fit:cover;display:block}
    .name{font-size:1.35rem;font-weight:700;margin-top:14px;color:var(--accent)}
    .role{font-size:0.94rem;color:var(--muted);margin-top:6px;text-align:center}
    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
    .badge{background:linear-gradient(180deg,#fff,#fff);padding:6px 10px;border-radius:999px;font-size:0.8rem;border:1px solid #f1e7ef;color:var(--accent)}

    /* push contact bottom */
    .sidebar .bottom{margin-top:auto;width:100%}
    .info-card{background:linear-gradient(180deg,#fff,#fff);padding:14px;border-radius:10px;border:1px solid #f2e6ee}
    .info-line{display:flex;align-items:center;gap:10px;font-size:0.95rem;color:var(--muted);margin:6px 0}
    .info-line strong{color:var(--text);font-weight:600}
    .contact-btn{display:block;text-align:center;margin-top:10px;padding:10px;border-radius:8px;text-decoration:none;background:var(--accent);color:white;font-weight:600}

    /* MAIN CONTENT */
    .main{display:flex;flex-direction:column;gap:18px}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:var(--shadow)}
    h1{margin:0;font-size:1.6rem;color:var(--accent)}
    h2{margin:0 0 10px 0;color:var(--accent);font-size:1.1rem}
    p{color:#333;line-height:1.5}
    .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px;margin-top:10px}
    .project{padding:12px;border-radius:10px;border:1px solid #f4e7ef;background:#fff}
    .project a{color:var(--accent);text-decoration:none;font-weight:600}

    /* stats row */
    .stats-row{display:flex;gap:14px;flex-wrap:wrap}
    .stat-card{flex:1;min-width:180px;padding:12px;border-radius:10px;background:linear-gradient(180deg,var(--pink2),#fff);border:1px solid #ffdce6;text-align:center}

    footer{margin-top:8px;text-align:center;color:var(--muted);font-size:0.9rem}

    /* responsive */
    @media(max-width:900px){
      .wrap{grid-template-columns:1fr; padding:12px}
      .sidebar{height:auto;flex-direction:row;gap:14px;padding:14px}
      .profile-img{width:88px;height:88px}
      .bottom{margin-top:0;flex:1}
    }
  </style>
</head>
<body>
  <div class="wrap">

    <!-- LEFT SIDEBAR -->
    <aside class="sidebar">
      <div style="text-align:center">
        <div class="profile-img">
          <!-- Upload your avatar.jpg into the repo root (same folder as index.html) -->
          <img src="avatar.jpg" alt="Sahra Ourari">
        </div>
        <div class="name">Sahra Ourari</div>
        <div class="role">🚀 Ingénieur Data & Data Analyst</div>

        <div class="badges" aria-hidden="true">
          <span class="badge">Python</span>
          <span class="badge">SQL</span>
          <span class="badge">Power BI</span>
        </div>
      </div>

      <div class="bottom">
        <div class="info-card">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div style="font-weight:700">Mon CV</div>
            <a class="contact-btn" href="cv.pdf" target="_blank" rel="noopener">Voir le CV</a>
          </div>

          <div style="margin-top:10px" class="info-line"><strong>📍</strong><span>Béjaïa, Algérie</span></div>
          <div class="info-line"><strong>🏫</strong><span>ESTIN</span></div>
          <div class="info-line"><strong>✉️</strong><span>ourari@estin.dz</span></div>
          <div class="info-line"><strong>🔗</strong><span><a href="https://www.linkedin.com/in/sahra-ourari-3b628a303/" target="_blank">LinkedIn</a></span></div>
          <div style="margin-top:10px;font-size:0.85rem;color:var(--muted)">Disponible pour collaborations • Open to work</div>
        </div>
      </div>
    </aside>

    <!-- RIGHT MAIN -->
    <main class="main">
      <section class="card">
        <h1>Bienvenue — je suis Sahra</h1>
        <p>Data Analyst & Ingénieur Data en formation. J'aime transformer des données brutes en visualisations et insights utiles.</p>
      </section>

      <section class="card">
        <h2>🚀 Projets récents</h2>
        <div class="projects">
          <div class="project">
            <div style="font-weight:700">Analyse Ventes - Power BI</div>
            <div style="margin-top:8px">Dashboard KPI, filtres, drill-down. <a href="https://github.com/saku-bloom/mon-projet" target="_blank">Voir le repo</a></div>
          </div>
          <div class="project">
            <div style="font-weight:700">Nettoyage & EDA - Python</div>
            <div style="margin-top:8px">Pandas, visualisations, rapport. <a href="https://github.com/saku-bloom" target="_blank">Voir mes projets</a></div>
          </div>
        </div>
      </section>

      <section class="card">
        <h2>📊 Statistiques GitHub</h2>
        <div class="stats-row">
          <div class="stat-card">
            <!-- Replace username in the URL if needed -->
            <img src="https://github-readme-stats.vercel.app/api?username=saku-bloom&show_icons=true&theme=radical" alt="stats" style="max-width:100%">
          </div>
          <div class="stat-card">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=saku-bloom&theme=radical" alt="streak" style="max-width:100%">
          </div>
        </div>
      </section>

      <footer>© <span id="year"></span> • Fait avec ❤️ par Sahra</footer>
    </main>

  </div>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
