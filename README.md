<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Alexandra Ash | Staff Profile</title>
  <meta name="viewport" content="width=1024">
  <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --maroon: #500000;
      --black: #222;
      --white: #fff;
      --gray: #e9e9e9;
    }
    html, body {
      margin: 0; padding: 0;
      background: var(--white);
      font-family: 'Libre Baskerville', Baskerville, serif;
      color: var(--black);
      min-width: 340px;
    }
    .header {
      background: var(--maroon);
      color: var(--white);
      padding: 3rem 0 2rem 0;
      text-align: center;
    }
    .header .name {
      font-size: 2.8rem;
      letter-spacing: 2px;
      font-weight: bold;
      margin-bottom: 0.5rem;
    }
    .header .contact {
      font-size: 1.1rem;
      letter-spacing: 1px;
      margin-bottom: 0.4rem;
      opacity: 0.85;
    }
    .main {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2.5rem;
      padding: 2.5rem 1rem;
      background: var(--gray);
    }
    .card {
      background: var(--white);
      border-radius: 18px;
      box-shadow: 0 6px 24px rgba(80,0,0,0.09);
      margin: 0 auto;
      min-width: 330px;
      max-width: 480px;
      width: 100%;
      padding: 2rem 2rem 2.7rem 2rem;
      position: relative;
      border-top: 5px solid var(--maroon);
    }
    .card h2 {
      margin-top: 0;
      font-size: 1.2rem;
      font-weight: bold;
      letter-spacing: 1px;
      color: var(--maroon);
      margin-bottom: 1rem;
    }
    .card .subtitle {
      font-size: 1.01rem;
      font-style: italic;
      color: var(--black);
      margin-bottom: 1rem;
      font-weight: 400;
    }
    .card ul, .card li {
      margin-left: 0;
      padding-left: 0;
      list-style: none;
    }
    .card ul {
      margin-bottom: 1.1rem;
      margin-left: 0;
      padding-left: 0;
    }
    .card li {
      margin-bottom: 0.6em;
      line-height: 1.5;
    }
    .bold {
      font-weight: bold;
    }
    .muted {
      color: #744;
      font-size: 0.95rem;
    }
    .section-divider {
      width: 90%;
      height: 1px;
      background: #cacaca;
      margin: 2rem auto;
      border-radius: 4px;
      opacity: 0.15;
    }
    .card .institution {
      font-weight: bold;
      font-size: 1.1rem;
      color: var(--maroon);
      margin-bottom: 0;
    }
    .card .role {
      font-weight: bold;
      color: var(--black);
      font-size: 1rem;
      margin-bottom: .3rem;
      margin-top: .9rem;
      letter-spacing: 0.5px;
    }
    .card .years {
      color: #555;
      font-size: 0.93em;
      opacity: 0.72;
    }
    @media (max-width: 900px) {
      .main {flex-direction: column;align-items: center;}
      .card {max-width: 99vw;}
    }
    /* For modern feel on buttons/links */
    .button {
      display: inline-block;
      margin-top: 1rem;
      background: var(--maroon);
      color: var(--white);
      padding: 0.6em 2em;
      border-radius: 24px;
      font-size: 1rem;
      letter-spacing: 1px;
      text-decoration: none;
      font-family: 'Libre Baskerville', Baskerville, serif;
    }
    .button:hover {
      background: #2c0101;
    }
    /* Subtle backdrop for accent */
    body::before {
      content:'';
      position:fixed;z-index:-1;
      top:0;left:0;right:0;bottom:0;
      background: linear-gradient(120deg, var(--maroon) 0%, #fff 45%, #fff 100%);
      opacity:0.03;
    }
  </style>
</head>
<body>
  <div class="header">
    <div class="name">Alexandra Ash</div>
    <div class="contact">
      Laredo, TX &nbsp;|&nbsp; (956) 285-0270 &nbsp;|&nbsp; <a style="color:#fff;text-decoration:underline;" href="mailto:ashalexandra03@gmail.com">ashalexandra03@gmail.com</a>
    </div>
    <div style="font-size:1.1rem;letter-spacing:0.5px;opacity:0.85;margin-top:0.5em;">
      Staff Profile — Texas A&M International University
    </div>
  </div>
  <div class="main">

    <div class="card">
      <h2>Education</h2>
      <div class="institution">Texas A&amp;M International University (TAMIU), Laredo, TX</div>
      <div class="subtitle">Bachelor of Science in Biology <span class="years">(Expected May 2025)</span></div>
      <div><span class="bold">Relevant Coursework:</span> Principles of Biology I–III, Ecology, Evolution, Genetics, GIS, Cell Biology, Infectious Diseases, Polymers in Nature, Environmental Monitoring, General Chemistry I &amp; II, Organic Chemistry I &amp; II, General Physics I &amp; II, Precalculus, Statistics</div>
      <div class="muted">Dean’s List (Spring 2023) &nbsp;|&nbsp; GPA: 3.69</div>
      <br>
      <div class="institution">Laredo College, Laredo, TX</div>
      <div class="subtitle">Dual Enrollment <span class="years">(January 2022)</span></div>
      <div class="muted">Dean’s List &nbsp;|&nbsp; GPA: 3.818</div>
    </div>

    <div class="card">
      <h2>Professional Experience</h2>
      <div class="role">Graduate Teaching Assistant</div>
      <div class="subtitle">Texas A&amp;M University, College Station, TX <span class="years">(August 2025–Present)</span></div>
      <ul>
        <li>Instruction of three introductory Biology laboratory sections (BIOL 111), including laboratory protocol and theoretical lectures</li>
        <li>Facilitation of weekly office hours for individualized student support</li>
      </ul>
      <div class="role">Undergraduate Research Assistant, Remote Sensing of White-tailed Deer Urban Habitats</div>
      <div class="subtitle">Texas A&amp;M International University, Laredo, TX <span class="years">(Nov 2024–May 2025)</span></div>
      <ul>
        <li>Ecological research employing ArcGIS Pro and satellite imagery to assess land cover and vegetation impacts on urban deer populations</li>
        <li>Analysis of human-wildlife interactions within park ecosystems; recommendation of conservation practices for biodiversity protection</li>
      </ul>
      <div class="role">Science Influencer Program, Science Communicator</div>
      <div class="subtitle">Texas A&amp;M University, College Station, TX <span class="years">(Jan 2024–Dec 2024)</span></div>
      <ul>
        <li>Developed scientific communication materials (infographics, podcasts, social media content) focused on fungal pathogen research and agriculture</li>
        <li>Recruited STEM students via oral presentations; presented original bioremediation research</li>
      </ul>
      <div class="role">Research Intern, IPMB REEU</div>
      <div class="subtitle">Texas A&amp;M University, College Station, TX <span class="years">(May 2024–Aug 2024)</span></div>
      <ul>
        <li>Full-time participant in plant pathology laboratory; performed experimental design, molecular biology techniques (16s rRNA PCR, gel electrophoresis), microbial culture preparation, instrument operation</li>
        <li>Led research project on Sargassum bioremediation for promotion of anti-Fov4 bacterial growth; disseminated results at symposia</li>
      </ul>
      <div class="role">Sales Associate</div>
      <div class="subtitle">Shop 195, Laredo
