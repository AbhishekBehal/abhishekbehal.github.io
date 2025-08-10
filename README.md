
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abhishek Behal | Data Analyst Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
    }
    header {
      padding: 2rem;
      text-align: center;
    }
    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #58a6ff;
      margin-bottom: 1rem;
    }
    header h1 {
      font-size: 2.5rem;
    }
    .tagline {
      font-size: 1.2rem;
      color: #58a6ff;
    }
    .bio {
      max-width: 600px;
      margin: 1rem auto;
      font-size: 1rem;
      line-height: 1.6;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
      padding: 2rem;
    }
    .project-card {
      background-color: #161b22;
      border-radius: 10px;
      padding: 1rem;
      width: 300px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.5);
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: scale(1.05);
    }
    .project-title {
      font-weight: 600;
      font-size: 1.2rem;
      color: #58a6ff;
    }
    .project-desc {
      font-size: 0.95rem;
      margin: 0.5rem 0;
    }
    .project-tech {
      font-size: 0.85rem;
      color: #8b949e;
    }
    footer {
      text-align: center;
      padding: 2rem;
    }
    .socials a {
      color: #58a6ff;
      text-decoration: none;
      margin: 0 1rem;
    }
    .resume-button {
      background-color: #238636;
      color: white;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: 600;
      text-decoration: none;
    }
    @media (max-width: 768px) {
      .projects {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src=  "New Pic.png" class="profile-pic">
    <h1>Abhishek Behal</h1>
    <p class="tagline">Data Analyst | Transforming Data into Decisions</p>
    <p class="bio">
      A business-savvy data analyst with a sharp analytical mindset and 4+ years of client engagement experience. Combining entrepreneurship with hands-on data skills, I specialize in converting raw datasets into compelling insights using Excel, Power BI, SQL, and Python. Passionate about driving decisions through data.
    </p>
    <a class="resume-button" href="Resume-Abhishek_Behal.pdf" download>Download Resume</a>
  </header>

  <section class="projects">
    <div class="project-card">
      <p class="project-title">Instagram User Engagement Analysis</p>
      <p class="project-desc">Identified top-performing posts, bots, and hashtags using MySQL queries.</p>
      <p class="project-tech">Tools: SQL, MySQL Workbench</p>
    </div>
    <div class="project-card">
      <p class="project-title">IMDB Movie Analysis</p>
      <p class="project-desc">Explored 7,000+ movies to analyze genres, ratings, and durations.</p>
      <p class="project-tech">Tools: Python, Pandas, Matplotlib, Seaborn</p>
    </div>
    <div class="project-card">
      <p class="project-title">Bank Loan Default Analysis</p>
      <p class="project-desc">Flagged high-risk applicants and recommended new loan policies.</p>
      <p class="project-tech">Tools: Python, Pandas, Seaborn</p>
    </div>
    <div class="project-card">
      <p class="project-title">Hiring Process Analytics</p>
      <p class="project-desc">Analyzed hiring data to uncover gender ratios and salary trends.</p>
      <p class="project-tech">Tools: Excel</p>
    </div>
    <div class="project-card">
      <p class="project-title">Car Pricing & Profitability Analysis</p>
      <p class="project-desc">Built regression model to determine key price drivers.</p>
      <p class="project-tech">Tools: Excel, Regression</p>
    </div>
    <div class="project-card">
      <p class="project-title">Call Volume Trend Analysis</p>
      <p class="project-desc">Optimized call center staffing and reduced abandonment rate.</p>
      <p class="project-tech">Tools: Excel</p>
    </div>
    <div class="project-card">
      <p class="project-title">Data-Driven Jeans Purchase Decision</p>
      <p class="project-desc">Compared brands and recommended purchases based on market research.</p>
      <p class="project-tech">Tools: Excel</p>
    </div>
      </section>

  <footer>
    <div class="socials">
      <a href="mailto:abhishekb.development@gmail.com">Email</a>
      <a href="https://www.linkedin.com/in/abhishek-behal-368176186" target="_blank">LinkedIn</a>
      <a href="https://github.com/AbhishekBehal" target="_blank">GitHub</a>
    </div>
  </footer>
</body>
</html>
