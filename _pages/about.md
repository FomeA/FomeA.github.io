---
permalink: /
title: " "
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>

/* GLOBAL */
body{
font-family:"Segoe UI",system-ui,Arial,sans-serif;
max-width:1100px;
margin:auto;
padding:22px;
background:linear-gradient(180deg,#f7faff,#eef3fb);
color:#2b2b2b;
line-height:1.75;
}

/* HERO */
.hero{
text-align:center;
padding:70px 25px;
background:linear-gradient(135deg,#0a2e73,#1565c0,#1e88e5);
color:white;
border-radius:18px;
margin-bottom:40px;
box-shadow:0 18px 40px rgba(0,0,0,.18);
position:relative;
overflow:hidden;
}

.hero::before{
content:"";
position:absolute;
inset:-50%;
background:radial-gradient(circle at center,rgba(255,255,255,.15),transparent 60%);
transform:rotate(20deg);
}

.hero h1{
margin:0;
font-size:2.8rem;
letter-spacing:.5px;
font-weight:700;
position:relative;
z-index:1;
}

.hero p{
position:relative;
z-index:1;
}

.subtitle{
font-size:1.25rem;
opacity:.95;
margin-top:10px;
font-weight:300;
}

/* SECTION TITLES */
h2{
color:#0d47a1;
margin-top:45px;
font-size:1.55rem;
position:relative;
padding-left:14px;
font-weight:600;
}

h2::before{
content:"";
position:absolute;
left:0;
top:6px;
width:5px;
height:22px;
background:#1e88e5;
border-radius:3px;
}

/* INTRO */
.intro{
font-size:1.08rem;
color:#444;
margin-bottom:30px;
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:20px;
}

/* CARDS */
.card{
background:white;
padding:22px;
border-radius:16px;
box-shadow:0 6px 18px rgba(0,0,0,.08);
transition:all .25s ease;
border:1px solid rgba(0,0,0,.05);
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 16px 30px rgba(0,0,0,.14);
}

.card h3{
margin-top:0;
color:#1565c0;
font-size:1.15rem;
}

/* NAVIGATION */
.nav-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:15px;
margin-top:20px;
}

.nav-card{
display:block;
text-align:center;
padding:18px;
background:linear-gradient(135deg,#f2f7ff,#eaf2ff);
border-radius:14px;
text-decoration:none;
color:#0d47a1;
font-weight:600;
border:1px solid #e3ecff;
transition:all .25s ease;
}

.nav-card:hover{
transform:translateY(-5px);
background:#dbe9ff;
box-shadow:0 10px 22px rgba(0,0,0,.1);
}

/* IMPACT */
.impact{
margin-top:45px;
padding:25px;
background:linear-gradient(135deg,#f7f9fc,#eef4ff);
border-left:6px solid #1565c0;
border-radius:14px;
box-shadow:0 8px 22px rgba(0,0,0,.06);
}

</style>

<div class="page__content">

<section class="hero">
  <h1>Dr. Anna Daniel Fome</h1>
  <p class="subtitle">Applied Mathematician | Statistician | Researcher</p>
  <!--<p>Jordan University College, Tanzania</p>-->
</section>

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

<!--<h2>Research Focus Areas</h2>

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

</div> -->

<h2>Explore</h2>

<div class="nav-grid">

<a class="nav-card" href="/teaching/">🎓 Teaching</a>
<a class="nav-card" href="/research/">📚 Research</a>
<a class="nav-card" href="/mentorship/">🤝 Mentorship</a>
<a class="nav-card" href="/publications/">📄 Publications</a>

</div>

<section class="impact">
  <h2>Impact Statement</h2>
  <p>
    Through interdisciplinary research, I aim to bridge mathematics and real-world challenges,
    contributing to evidence-based solutions that support education, health systems, and community development in Tanzania and beyond.
  </p>
</section>

</div>
