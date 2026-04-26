---
permalink: /
title: "Anna Daniel Fome"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anna Daniel Fome</title>

<style>

/* GLOBAL */
body{
font-family: "Segoe UI", Arial, sans-serif;
max-width:1100px;
margin:auto;
padding:20px;
background: radial-gradient(circle at top,#f5f9ff,#eef3fb);
color:#2b2b2b;
line-height:1.7;
}

/* HERO */
.hero{
text-align:center;
padding:60px 25px;
background: linear-gradient(135deg,#0b3d91,#1565c0,#1e88e5);
color:white;
border-radius:16px;
margin-bottom:35px;
box-shadow:0 12px 30px rgba(0,0,0,.15);
position:relative;
overflow:hidden;
}

.hero::after{
content:"";
position:absolute;
top:-50%;
left:-50%;
width:200%;
height:200%;
background: radial-gradient(circle, rgba(255,255,255,0.12), transparent 60%);
transform: rotate(25deg);
}

.hero h1{
margin:0;
font-size:2.6rem;
letter-spacing:.5px;
}

.subtitle{
font-size:1.2rem;
opacity:.95;
margin-top:8px;
font-weight:300;
}

/* TEXT */
.intro{
margin-bottom:25px;
color:#444;
font-size:1.05rem;
}

/* HEADINGS */
h2{
color:#0d47a1;
margin-top:40px;
font-size:1.5rem;
position:relative;
padding-left:12px;
}

h2::before{
content:"";
position:absolute;
left:0;
top:5px;
width:4px;
height:22px;
background:#1e88e5;
border-radius:2px;
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:18px;
margin-top:18px;
}

/* CARDS */
.card{
background:white;
padding:20px;
border-radius:14px;
box-shadow:0 4px 14px rgba(0,0,0,.08);
transition:all .25s ease;
border:1px solid rgba(0,0,0,.04);
}

.card:hover{
transform:translateY(-6px);
box-shadow:0 12px 25px rgba(0,0,0,.12);
}

.card h3{
margin-top:0;
color:#1565c0;
font-size:1.1rem;
}

/* NAVIGATION */
.nav-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:15px;
margin-top:18px;
}

.nav-card{
display:block;
text-align:center;
padding:18px;
background:linear-gradient(135deg,#eaf2ff,#f6f9ff);
border-radius:12px;
text-decoration:none;
color:#0d47a1;
font-weight:600;
transition:.25s;
border:1px solid #e3ecff;
}

.nav-card:hover{
transform:translateY(-4px);
background:#dbe9ff;
box-shadow:0 8px 18px rgba(0,0,0,.08);
}

/* IMPACT */
.impact{
margin-top:40px;
padding:22px;
background:linear-gradient(135deg,#f7f9fc,#eef4ff);
border-left:6px solid #1565c0;
border-radius:12px;
box-shadow:0 6px 18px rgba(0,0,0,.05);
}

</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <h1>Dr. Anna Daniel Fome</h1>
  <p class="subtitle">Applied Mathematician | Statistician | Researcher</p>
  <p>Jordan University College, Tanzania</p>
</section>

<!-- INTRO -->
<section class="intro">
  <p>
    I am an academic and researcher in Applied Mathematics and Statistics at Jordan University College, Tanzania.
    My work focuses on using statistical modelling and mathematical analysis to solve real-world problems in
    public health, education, and social development.
  </p>

  <p>
    My research interests include epidemiological modelling, biostatistics, student behaviour analysis,
    and data-driven decision-making for regional development.
  </p>
</section>

<!-- RESEARCH FOCUS -->
<h2>Research Focus Areas</h2>

<div class="grid">

<div class="card">
  <h3>📊 Biostatistics</h3>
  <p>Statistical methods for health and biological data analysis.</p>
</div>

<div class="card">
  <h3>🦠 Epidemiological Modelling</h3>
  <p>Mathematical modelling of infectious diseases.</p>
</div>

<div class="card">
  <h3>🎓 Education Analytics</h3>
  <p>Analysis of student performance and learning outcomes.</p>
</div>

<div class="card">
  <h3>📈 Data Science</h3>
  <p>Applied data analysis for decision making.</p>
</div>

</div>

<!-- NAVIGATION -->
<h2>Explore</h2>

<div class="nav-grid">

<a class="nav-card" href="/teaching/">🎓 Teaching</a>
<a class="nav-card" href="/research/">📚 Research</a>
<a class="nav-card" href="/mentorship/">🤝 Mentorship</a>
<a class="nav-card" href="/publications/">📄 Publications</a>

</div>

<!-- IMPACT -->
<section class="impact">
  <h2>Impact Statement</h2>
  <p>
    Through interdisciplinary research, I aim to bridge mathematics and real-world challenges,
    contributing to evidence-based solutions that support education, health systems, and community development in Tanzania and beyond.
  </p>
</section>

</body>
</html>
