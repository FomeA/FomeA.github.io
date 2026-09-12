---
layout: single
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>

/* =========================================================
   ACADEMIC HOMEPAGE
   ========================================================= */

.page__content {
  max-width: 980px;
  margin: auto;
  font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  color: #334155;
  line-height: 1.75;
}

/* =========================================================
   SECTIONS
   ========================================================= */

.section {
  margin: 65px 0;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 12px;
  color: #0f172a;
  border-bottom: 2px solid #e2e8f0;
  padding-bottom: 10px;
  letter-spacing: -0.02em;
}

.section-intro {
  color: #64748b;
  margin: 0 0 28px;
  font-size: 1.02rem;
}

/* =========================================================
   INTRO
   ========================================================= */

.intro {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 18px;
  padding: 38px;
  margin-bottom: 65px;
}

.intro p {
  font-size: 1.08rem;
  margin: 0 0 18px;
}

.intro p:last-of-type {
  margin-bottom: 0;
}

.intro strong {
  color: #0f172a;
}

/* Research keywords */

.research-keywords {
  margin-top: 25px;
  display: flex;
  flex-wrap: wrap;
  gap: 9px;
}

.research-keywords span {
  background: white;
  border: 1px solid #dbe3ec;
  border-radius: 999px;
  padding: 6px 13px;
  font-size: .88rem;
  font-weight: 600;
  color: #475569;
}

/* =========================================================
   BUTTONS
   ========================================================= */

.buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 28px;
}

.btn {
  display: inline-block;
  text-decoration: none;
  padding: 11px 18px;
  border-radius: 10px;
  font-weight: 600;
  transition: .25s ease;
}

.btn-primary {
  background: #2563eb;
  color: white !important;
}

.btn-primary:hover {
  background: #1d4ed8;
  transform: translateY(-1px);
}

.btn-light {
  background: white !important;
  border: 1px solid #2563eb !important;
  color: #2563eb !important;
}

.btn-light:hover {
  background: #f8fafc !important;
  border-color: #1d4ed8 !important;
  color: #1d4ed8 !important;
  transform: translateY(-1px);
}

/* =========================================================
   CARDS
   ========================================================= */

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
}

.card {
  background: white;
  border: 1px solid #e2e8f0;
  border-radius: 16px;
  padding: 24px;
  transition: .25s ease;
}

.card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, .06);
}

.card h3 {
  margin-top: 0;
  margin-bottom: 9px;
  color: #0f172a;
  font-size: 1.15rem;
}

.card p {
  margin-bottom: 12px;
  font-size: .96rem;
}

.card-link {
  color: #2563eb;
  font-weight: 600;
  text-decoration: none;
  font-size: .92rem;
}

.card-link:hover {
  text-decoration: underline;
}

/* =========================================================
   RESEARCH
   ========================================================= */

.research-card {
  border-top: 4px solid #2563eb;
}

  /* =========================================
   Teaching Section
========================================= */

.teaching-section {
  margin-top: 4rem;
}

.section-heading {
  max-width: 680px;
  margin-bottom: 2rem;
}

.section-kicker {
  display: block;
  margin-bottom: 0.5rem;
  color: #2e8b78;
  font-size: 0.7rem;
  font-weight: 750;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.section-heading h2 {
  margin: 0 0 0.65rem;
  color: #102542;
  font-size: clamp(2rem, 4vw, 2.8rem);
  font-weight: 750;
  letter-spacing: -0.045em;
}

.section-heading p {
  max-width: 620px;
  margin: 0;
  color: #687789;
  font-size: 0.98rem;
  line-height: 1.75;
}

/* Semester Group */

.semester-group {
  margin-bottom: 2.25rem;
}

.semester-heading {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  margin-bottom: 1rem;
}

.semester-heading h3 {
  margin: 0;
  color: #102542;
  font-size: 1.25rem;
  font-weight: 750;
  letter-spacing: -0.025em;
}

.semester-heading span {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 27px;
  height: 27px;
  border: 1px solid #cfe2dc;
  border-radius: 50%;
  color: #2e8b78;
  font-size: 0.65rem;
  font-weight: 750;
}

/* Course Card Grid */

.course-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

/* Individual Course Cards */

.course-card {
  position: relative;
  display: flex;
  min-height: 145px;
  flex-direction: column;
  align-items: flex-start;
  justify-content: space-between;
  gap: 1rem;
  padding: 1.15rem;
  overflow: hidden;
  border: 1px solid #dce5eb;
  border-radius: 16px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(16, 37, 66, 0.035);
  color: inherit;
  text-decoration: none;
  transition:
    border-color 0.25s ease,
    background-color 0.25s ease,
    box-shadow 0.25s ease,
    transform 0.25s ease;
}

.course-card::before {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  height: 3px;
  background: #2e8b78;
  content: "";
  opacity: 0;
  transition: opacity 0.25s ease;
}

.course-card:hover {
  border-color: #a9cec3;
  background: #fbfefd;
  box-shadow: 0 14px 32px rgba(16, 37, 66, 0.08);
  transform: translateY(-3px);
}

.course-card:hover::before {
  opacity: 1;
}

.course-card-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 30px;
  height: 30px;
  border-radius: 8px;
  background: #edf6f2;
  color: #2e8b78;
  font-size: 0.7rem;
  font-weight: 750;
}

.course-card h4 {
  width: 100%;
  margin: 0;
  color: #1b3049;
  font-size: 0.95rem;
  font-weight: 700;
  line-height: 1.45;
  letter-spacing: -0.01em;
}

.course-card-link {
  display: flex;
  align-items: center;
  gap: 0.3rem;
  color: #7b8996;
  font-size: 0.72rem;
  font-weight: 650;
  transition: color 0.2s ease;
}

.course-card-link span {
  font-size: 0.95rem;
  transition: transform 0.2s ease;
}

.course-card:hover .course-card-link {
  color: #2e8b78;
}

.course-card:hover .course-card-link span {
  transform: translate(2px, -2px);
}

/* Responsive */

@media (max-width: 750px) {
  .course-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 460px) {
  .course-grid {
    grid-template-columns: 1fr;
  }

  .course-card {
    min-height: 125px;
  }
}
/* =========================================================
   PUBLICATIONS
   ========================================================= */

.publication-list {
  display: flex;
  flex-direction: column;
  gap: 17px;
}

.publication {
  background: white;
  border: 1px solid #e2e8f0;
  border-radius: 14px;
  padding: 22px 25px;
}

.publication p {
  margin: 7px 0;
}

.publication-status {
  display: inline-block;
  font-size: .72rem;
  font-weight: 700;
  letter-spacing: .07em;
  color: #2563eb;
  margin-bottom: 4px;
}

.publication-title {
  color: #0f172a;
}

.publication-meta {
  font-size: .88rem;
  color: #64748b;
}

.publication-meta a {
  color: #2563eb;
  text-decoration: none;
}

.publication-meta a:hover {
  text-decoration: underline;
}

.more-link {
  margin-top: 22px;
  text-align: right;
}

.more-link a {
  color: #2563eb;
  font-weight: 600;
  text-decoration: none;
}

.more-link a:hover {
  text-decoration: underline;
}

/* =========================================================
   CONFERENCES
   ========================================================= */

.conference-list {
  display: flex;
  flex-direction: column;
}

.conference {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 25px;
  padding: 17px 0;
  border-bottom: 1px solid #e2e8f0;
}

.conference:first-child {
  border-top: 1px solid #e2e8f0;
}

.conference-name {
  color: #0f172a;
  font-weight: 600;
}

.conference-type {
  white-space: nowrap;
  font-size: .86rem;
  font-weight: 600;
  color: #64748b;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  padding: 5px 10px;
}

/* =========================================================
   GRANTS
   ========================================================= */

.grant-card h3 {
  margin-bottom: 7px;
}

.grant-card p {
  margin: 0;
}

/* =========================================================
   VISION
   ========================================================= */

.vision {
  background: #f8fafc;
  border-left: 5px solid #2563eb;
  padding: 30px;
  border-radius: 14px;
}

.vision p {
  margin: 0;
  font-size: 1.05rem;
}

/* =========================================================
   FOCUS BOX
   ========================================================= */

.focus-box {
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 16px;
  padding: 25px;
  margin-top: 20px;
}

.focus-box h3 {
  margin-top: 0;
  color: #0f172a;
}

.focus-box ul {
  margin-bottom: 0;
}

/* =========================================================
   ANIMATION
   ========================================================= */

.reveal {
  opacity: 0;
  transform: translateY(18px);
  transition: opacity .7s ease, transform .7s ease;
}

.reveal.active {
  opacity: 1;
  transform: none;
}

/* =========================================================
   ACCESSIBILITY
   ========================================================= */

.btn:focus-visible,
a:focus-visible {
  outline: 3px solid #93c5fd;
  outline-offset: 3px;
}

/* =========================================================
   MOBILE
   ========================================================= */

@media (max-width: 768px) {

  .section {
    margin: 48px 0;
  }

  .intro {
    padding: 25px;
    margin-bottom: 48px;
  }

  .intro p {
    font-size: 1rem;
  }

  .section h2 {
    font-size: 1.65rem;
  }

  .card {
    padding: 20px;
  }

  .conference {
    flex-direction: column;
    align-items: flex-start;
    gap: 8px;
  }

  .conference-type {
    white-space: normal;
  }

}

/* =========================================================
   PAGE NAVIGATOR
   ========================================================= */

.page-navigator {
  position: fixed;
  top: 50%;
  right: 24px;
  transform: translateY(-50%);
  z-index: 1000;
  width: 190px;
  background: rgba(255, 255, 255, 0.96);
  border: 1px solid #e2e8f0;
  border-radius: 14px;
  padding: 15px;
  box-shadow: 0 10px 30px rgba(15, 23, 42, 0.08);
  backdrop-filter: blur(10px);
}

.page-navigator-title {
  margin: 0 0 10px;
  padding-bottom: 9px;
  border-bottom: 1px solid #e2e8f0;
  font-size: .78rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: .08em;
  color: #64748b;
}

.page-navigator a {
  display: block;
  padding: 6px 9px;
  margin: 2px 0;
  border-radius: 7px;
  color: #64748b;
  text-decoration: none;
  font-size: .86rem;
  line-height: 1.35;
  transition: .2s ease;
}

.page-navigator a:hover {
  color: #2563eb;
  background: #eff6ff;
}

.page-navigator a.active {
  color: #2563eb;
  background: #eff6ff;
  font-weight: 700;
  border-left: 3px solid #2563eb;
  padding-left: 6px;
}

/* Smooth navigation */

html {
  scroll-behavior: smooth;
}

.section,
.intro {
  scroll-margin-top: 35px;
}

/* =========================================================
   MOBILE NAVIGATOR
   ========================================================= */

@media (max-width: 1100px) {

  .page-navigator {
    position: sticky;
    top: 10px;
    right: auto;
    transform: none;
    width: auto;
    margin: 0 0 30px;
    padding: 10px 12px;
  }

  .page-navigator-title {
    margin-bottom: 7px;
    padding-bottom: 6px;
  }

  .page-navigator-links {
    display: flex;
    flex-wrap: wrap;
    gap: 5px;
  }

  .page-navigator a {
    display: inline-block;
    margin: 0;
    padding: 6px 9px;
  }

  .page-navigator a.active {
    border-left: none;
    padding-left: 9px;
  }

}
  
/* =========================================================
   REDUCED MOTION
   ========================================================= */

@media (prefers-reduced-motion: reduce) {

  .reveal {
    opacity: 1;
    transform: none;
    transition: none;
  }

  .card,
  .btn {
    transition: none;
  }

  .card:hover,
  .btn:hover {
    transform: none;
  }

}

</style>

<!-- =========================================================
     PAGE NAVIGATOR
     ========================================================= -->

<nav class="page-navigator" aria-label="Page navigation">

  <div class="page-navigator-title">
    On this page
  </div>

  <div class="page-navigator-links">

    <a href="#about">About</a>

    <a href="#research">Research</a>

    <a href="#teaching">Teaching</a>

    <a href="#publications">Publications</a>

    <a href="#conferences">Talks & Conferences</a>

    <a href="#grants">Grants & Scholarships</a>

    <a href="#mentorship">Mentorship</a>

    <!--<a href="#vision">Research Vision</a>-->

  </div>

</nav>

<!-- =========================================================
     INTRODUCTION
     ========================================================= -->

<section id="about" class="intro reveal">

<p>
I am an <strong>applied mathematician and educator</strong> interested in
mathematical modelling, statistics, epidemiology, and data science.
My research focuses on developing quantitative approaches for
understanding and addressing practical challenges in public health,
education, and community development.
</p>

<p>
My work brings together <strong>mathematical modelling</strong>,
<strong>biostatistics</strong>, <strong>numerical methods</strong>,
and <strong>statistical computing</strong> to translate complex
data and systems into useful evidence for decision-making, with
particular interest in applications in Tanzania and beyond.
</p>

<!--
<div class="research-keywords">
  <span>Mathematical Modelling</span>
  <span>Biostatistics</span>
  <span>Epidemiology</span>
  <span>Data Science</span>
  <span>Numerical Analysis</span>
  <span>Public Health</span>
</div> -->

<!--<div class="buttons">
<a href="{{ site.baseurl }}/files/CV.pdf" class="btn btn-primary">
Curriculum Vitae
</a>
<a href="{{ site.baseurl }}/publications/" class="btn btn-light">
Publications
</a>
<a href="{{ site.baseurl }}/juco-dsg/" class="btn btn-light">
Research Group
</a>
</div>-->

</section>


<!-- =========================================================
     RESEARCH ACTIVITIES
     ========================================================= -->

<section id="research" class="section reveal">

  <div class="section-heading">
    <div>
      <div class="section-label">Research Activities</div>
      <h2>Research with purpose and application.</h2>
    </div>
  </div>

  <p class="section-intro">
    My research brings together mathematical modelling, statistical analysis,
    and data science to address challenges in health, education, and society.
  </p>

  <div class="research-cards">

    <article class="research-card">
      <div class="research-card-number">01 · DISEASE MODELLING</div>
      <h3>Disease Modeling</h3>
      <p>
        Creating mathematical models to analyze how quarantine,
        cross-immunity, and media awareness campaigns affect the spread
        of co-circulating respiratory viruses.
      </p>
    </article>

    <article class="research-card">
      <div class="research-card-number">02 · CLINICAL HEALTH</div>
      <h3>Clinical Health Metrics</h3>
      <p>
        Establishing baseline reference data for steady-state Sickle Cell
        Disease patients in Tanzania to improve local hospital care.
      </p>
    </article>

    <article class="research-card">
      <div class="research-card-number">03 · SOCIO-EDUCATIONAL</div>
      <h3>Socio-Educational Analytics</h3>
      <p>
        Investigating how lifestyle choices, internet habits, and social
        environments impact the academic performance of university students.
      </p>
    </article>

    <article class="research-card">
      <div class="research-card-number">04 · RESEARCH LEADERSHIP</div>
      <h3>Data Science Leadership</h3>
      <p>
        Leading an institutional research group that trains African scholars
        in R, Python, and statistical modeling techniques.
      </p>

      <a href="{{ site.baseurl }}/juco-dsg/" class="dsg-link">
        Explore JUCo DSRG →
      </a>
    </article>

  </div>

</section>


<!-- =========================================================
     TEACHING
     ========================================================= -->
<section class="academic-section teaching-section" id="teaching">
  <div class="section-heading">
    <span class="section-kicker">Teaching Portfolio</span>
    <h2>Teaching</h2>
    <p>
      Courses taught across undergraduate and postgraduate programmes,
      organized by semester.
    </p>
  </div>

  <!-- Semester I -->
  <div class="semester-group">
    <div class="semester-heading">
      <h3>Semester I</h3>
      <span>01</span>
    </div>

    <div class="course-grid">

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/course-1/"
      >
        <span class="course-card-number">01</span>
        <h4>Course Title One</h4>
        <span class="course-card-link">View course <span>↗</span></span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/course-2/"
      >
        <span class="course-card-number">02</span>
        <h4>Course Title Two</h4>
        <span class="course-card-link">View course <span>↗</span></span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/course-3/"
      >
        <span class="course-card-number">03</span>
        <h4>Course Title Three</h4>
        <span class="course-card-link">View course <span>↗</span></span>
      </a>

    </div>
  </div>

  <!-- Semester II -->
  <div class="semester-group">
    <div class="semester-heading">
      <h3>Semester II</h3>
      <span>02</span>
    </div>

    <div class="course-grid">

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/course-4/"
      >
        <span class="course-card-number">01</span>
        <h4>Course Title Four</h4>
        <span class="course-card-link">View course <span>↗</span></span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/course-5/"
      >
        <span class="course-card-number">02</span>
        <h4>Course Title Five</h4>
        <span class="course-card-link">View course <span>↗</span></span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/course-6/"
      >
        <span class="course-card-number">03</span>
        <h4>Course Title Six</h4>
        <span class="course-card-link">View course <span>↗</span></span>
      </a>

    </div>
  </div>
</section>


<!-- =========================================================
     SELECTED PUBLICATIONS
     ========================================================= -->

<section id="publications" class="section reveal">

  <div class="section-heading">
    <div>
      <div class="section-label">Selected Publications</div>
      <h2>Recent scholarly contributions.</h2>
    </div>
  </div>

  <p class="section-intro">
    Selected publications in mathematical modelling, epidemiology,
    and applied mathematics.
  </p>

  <div class="publication-list">

    <a class="publication"
       href="https://doi.org/10.1007/978-3-032-20404-2_16"
       target="_blank"
       rel="noopener">
      <span class="publication-meta">Book Chapter · 2026</span>
      <span class="publication-title">
        Dynamics Around Equilibria in a Competitive Respiratory Disease System with Quarantine.
      </span>
      <span class="publication-journal">
        Progress in Industrial Mathematics at ECMI 2023 · Springer
      </span>
    </a>

    <a class="publication"
       href="https://doi.org/10.1186/s12889-025-24362-z"
       target="_blank"
       rel="noopener">
      <span class="publication-meta">Journal Article · 2025</span>
      <span class="publication-title">
        Influenza–COVID-19 co-circulation in Germany 2020–2022: competitive dynamics with quarantine and cross-immunity.
      </span>
      <span class="publication-journal">
        BMC Public Health
      </span>
    </a>

    <a class="publication"
       href="https://doi.org/10.1016/j.amc.2024.128968"
       target="_blank"
       rel="noopener">
      <span class="publication-meta">Journal Article · 2025</span>
      <span class="publication-title">
        Competitive respiratory disease system with quarantine: epidemic thresholds and cross-immunity.
      </span>
      <span class="publication-journal">
        Applied Mathematics and Computation
      </span>
    </a>

    <a class="publication"
       href="https://doi.org/10.1016/j.health.2023.100189"
       target="_blank"
       rel="noopener">
      <span class="publication-meta">Journal Article · 2023</span>
      <span class="publication-title">
        A deterministic SIR model for studying the impact of media on epidemic dynamics.
      </span>
      <span class="publication-journal">
        Healthcare Analytics
      </span>
    </a>

    <a class="publication"
       href="https://doi.org/10.3390/hemato3010007"
       target="_blank"
       rel="noopener">
      <span class="publication-meta">Journal Article · 2022</span>
      <span class="publication-title">
        Hematological and biochemical reference ranges for SCD patients in Tanzania.
      </span>
      <span class="publication-journal">
        Hemato
      </span>
    </a>

  </div>

  <a class="section-link" href="{{ site.baseurl }}/publications/">
    View full publication list →
  </a>

</section>


<!-- =========================================================
     TALKS & CONFERENCES
     ========================================================= -->

<section id="conferences" class="section reveal">

  <div class="section-heading">
    <div>
      <div class="section-label">Academic Engagement</div>
      <h2>Talks &amp; Conferences.</h2>
    </div>
  </div>

  <p class="section-intro">
    Selected presentations, posters, research visits, and scientific meetings.
  </p>

  <div class="conference-list">

    <div class="conference">
      <div class="conference-content">
        <strong>4th Ifakara Annual Scientific Conference</strong>
        <span>Tanzania · Talk</span>
      </div>
      <a class="conference-link"
         href="https://www.icipe.org/"
         target="_blank"
         rel="noopener">
        Website ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>6th Young Researchers Symposium, RPTU</strong>
        <span>Germany · Pitch + Poster</span>
      </div>
      <a class="conference-link"
         href="https://rptu.de/"
         target="_blank"
         rel="noopener">
        RPTU ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>2nd MONID Infectious Disease Modelling Conference</strong>
        <span>Halle, Germany · Pitch + Poster</span>
      </div>
      <a class="conference-link"
         href="https://monid.org/"
         target="_blank"
         rel="noopener">
        MONID ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>Research Visit, Linnaeus University</strong>
        <span>Växjö, Sweden · Research visit and talk</span>
      </div>
      <a class="conference-link"
         href="https://lnu.se/en/"
         target="_blank"
         rel="noopener">
        Linnaeus ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>Joint African-Nordic Conference in Mathematics</strong>
        <span>Uganda · Hybrid talk</span>
      </div>
      <a class="conference-link"
         href="https://www.mathunion.org/"
         target="_blank"
         rel="noopener">
        IMU ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>22nd ECMI Conference on Industrial &amp; Applied Mathematics</strong>
        <span>Poland · Talk</span>
      </div>
      <a class="conference-link"
         href="https://ecmiindmath.org/"
         target="_blank"
         rel="noopener">
        ECMI ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>14th DSABNS Conference on Dynamical Systems</strong>
        <span>Bilbao, Spain · Poster</span>
      </div>
      <a class="conference-link"
         href="https://www.dsabns.org/"
         target="_blank"
         rel="noopener">
        DSABNS ↗
      </a>
    </div>

  </div>

</section>


<!-- =========================================================
     GRANTS & SCHOLARSHIPS
     ========================================================= -->

<section id="grants" class="section reveal">
<h2>Grants & Scholarships</h2>

<p class="section-intro">
Selected scholarships and research funding supporting academic
training, research, and professional development.
</p>

<div class="grid">


<div class="card grant-card">

<h3>DAAD Scholarship</h3>

<p>
PhD in Mathematics<br>
RPTU Kaiserslautern-Landau, Germany
</p>

</div>


<div class="card grant-card">

<h3>AIMS–GSK Funds</h3>

<p>
Funding support for an internship at the
Muhimbili Sickle-Cell Program.
</p>

</div>


<div class="card grant-card">

<h3>Mastercard Foundation Scholarship</h3>

<p>
MSc Mathematical Sciences<br>
African Institute for Mathematical Sciences (AIMS)
</p>

</div>


</div>

</section>


<!-- =========================================================
     MENTORSHIP & SUPERVISION
     ========================================================= -->

<section id="mentorship" class="section reveal">
<h2>Mentorship & Supervision</h2>

<div class="focus-box">

<h3>Supporting the next generation of researchers</h3>

<p>
I am interested in mentoring and supervising students and early-career
researchers working in areas related to mathematics, statistics,
data science, mathematical modelling, and public health.
</p>

<ul>
<li>Research project development</li>
<li>Mathematical and statistical modelling</li>
<li>Data analysis and scientific computing</li>
<li>Academic writing and research communication</li>
<li>Undergraduate and postgraduate research mentorship</li>
</ul>

<!-- BOOKING -->
<h3 class="section-title"><a class="book-btn" href="https://calendar.app.google/RF8rbheuphgiRurh6" target="_blank">
📅 Schedule a mentorship session here
</a></h3>

</div>

</section>


<!-- =========================================================
     RESEARCH VISION
     ========================================================= -->

<!--<section id="vision" class="section reveal">
<h2>Research Vision</h2>

<div class="vision">

<p>
My goal is to develop and promote mathematical, statistical, and
data-driven approaches that connect theory with practical applications.
Through research, teaching, mentorship, and collaboration, I aim to
contribute to evidence-based solutions for challenges in public health,
education, and sustainable development in Tanzania and beyond.
</p>

</div>

</section> -->


<!-- =========================================================
     ANIMATION
     ========================================================= -->

<script>

document.addEventListener("DOMContentLoaded", function() {

  /* =========================================================
     REVEAL ANIMATION
     ========================================================= */

  const revealObserver = new IntersectionObserver(
    (entries) => {

      entries.forEach((entry) => {

        if (entry.isIntersecting) {
          entry.target.classList.add("active");
          revealObserver.unobserve(entry.target);
        }

      });

    },
    {
      threshold: 0.1
    }
  );

  document
    .querySelectorAll(".reveal")
    .forEach((el) => revealObserver.observe(el));


  /* =========================================================
     PAGE NAVIGATOR
     ========================================================= */

  const sections = document.querySelectorAll(
    "#about, #research, #teaching, #publications, #conferences, #grants, #mentorship, #vision"
  );

  const navLinks = document.querySelectorAll(
    ".page-navigator a"
  );

  const navObserver = new IntersectionObserver(
    (entries) => {

      entries.forEach((entry) => {

        if (entry.isIntersecting) {

          navLinks.forEach((link) => {
            link.classList.remove("active");
          });

          const activeLink = document.querySelector(
            '.page-navigator a[href="#' + entry.target.id + '"]'
          );

          if (activeLink) {
            activeLink.classList.add("active");
          }

        }

      });

    },
    {
      rootMargin: "-25% 0px -60% 0px",
      threshold: 0
    }
  );

  sections.forEach((section) => {
    navObserver.observe(section);
  });

});

</script>
