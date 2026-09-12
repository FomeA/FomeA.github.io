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
   ACADEMIC HOMEPAGE — GLOBAL STYLES
========================================================= */

.page__content {
  max-width: 1040px;
  margin: 0 auto;
  font-family:
    Inter,
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    sans-serif;
  color: #475569;
  font-size: 0.95rem;
  font-weight: 400;
  line-height: 1.7;
}

/* Prevent unnecessary bold text */
.page__content p,
.page__content li,
.page__content span,
.page__content small {
  font-weight: 400;
}

/* =========================================================
   SECTION STRUCTURE
========================================================= */

.section {
  margin: 58px 0;
  scroll-margin-top: 35px;
}

.section-heading {
  margin-bottom: 12px;
}

.section-label,
.section-kicker {
  display: block;
  margin-bottom: 7px;
  color: #2e8b78;
  font-size: 0.68rem;
  font-weight: 600;
  letter-spacing: 0.13em;
  line-height: 1.4;
  text-transform: uppercase;
}

.section h2,
.section-heading h2 {
  margin: 0 0 10px;
  color: #1e293b;
  font-size: clamp(1.45rem, 2.5vw, 1.85rem);
  font-weight: 600;
  letter-spacing: -0.025em;
  line-height: 1.25;
}

.section-intro {
  max-width: 700px;
  margin: 0 0 24px;
  color: #64748b;
  font-size: 0.94rem;
  font-weight: 400;
  line-height: 1.7;
}

/* =========================================================
   INTRODUCTION
========================================================= */

.intro {
  margin-bottom: 58px;
  padding: 30px 32px;
  border: 1px solid #e2e8f0;
  border-radius: 16px;
  background: #f8fafc;
  scroll-margin-top: 35px;
}

.intro p {
  margin: 0 0 15px;
  color: #475569;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.8;
}

.intro p:last-child {
  margin-bottom: 0;
}

.intro strong {
  color: #334155;
  font-weight: 600;
}

/* =========================================================
   BUTTONS
========================================================= */

.buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 24px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 40px;
  padding: 9px 16px;
  border-radius: 8px;
  font-size: 0.84rem;
  font-weight: 500;
  line-height: 1.3;
  text-decoration: none;
  transition:
    background-color 0.2s ease,
    border-color 0.2s ease,
    color 0.2s ease,
    transform 0.2s ease;
}

.btn-primary {
  background: #2e8b78;
  color: #ffffff !important;
}

.btn-primary:hover {
  background: #246f60;
  color: #ffffff !important;
  transform: translateY(-1px);
}

.btn-light {
  border: 1px solid #cbd5e1;
  background: #ffffff !important;
  color: #475569 !important;
}

.btn-light:hover {
  border-color: #2e8b78;
  color: #2e8b78 !important;
  transform: translateY(-1px);
}

/* =========================================================
   GENERAL CARD SYSTEM
========================================================= */

.grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
}

.card {
  padding: 20px;
  border: 1px solid #e2e8f0;
  border-radius: 14px;
  background: #ffffff;
  box-shadow: 0 5px 18px rgba(15, 23, 42, 0.025);
  transition:
    border-color 0.2s ease,
    box-shadow 0.2s ease,
    transform 0.2s ease;
}

.card:hover {
  border-color: #cbded8;
  box-shadow: 0 10px 25px rgba(15, 23, 42, 0.055);
  transform: translateY(-2px);
}

.card h3 {
  margin: 0 0 8px;
  color: #334155;
  font-size: 1rem;
  font-weight: 600;
  line-height: 1.4;
}

.card p {
  margin: 0;
  color: #64748b;
  font-size: 0.9rem;
  font-weight: 400;
  line-height: 1.65;
}

/* =========================================================
   RESEARCH ACTIVITIES
========================================================= */

.research-cards {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}

.research-card {
  position: relative;
  padding: 22px;
  border: 1px solid #e2e8f0;
  border-top: 3px solid #2e8b78;
  border-radius: 14px;
  background: #ffffff;
  box-shadow: 0 5px 18px rgba(15, 23, 42, 0.025);
  transition:
    box-shadow 0.2s ease,
    transform 0.2s ease;
}

.research-card:hover {
  box-shadow: 0 10px 25px rgba(15, 23, 42, 0.06);
  transform: translateY(-2px);
}

.research-card-number {
  margin-bottom: 12px;
  color: #2e8b78;
  font-size: 0.67rem;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.research-card h3 {
  margin: 0 0 9px;
  color: #334155;
  font-size: 1.05rem;
  font-weight: 600;
  line-height: 1.4;
}

.research-card p {
  margin: 0;
  color: #64748b;
  font-size: 0.9rem;
  font-weight: 400;
  line-height: 1.7;
}

.dsg-link {
  display: inline-block;
  margin-top: 15px;
  color: #2e8b78;
  font-size: 0.83rem;
  font-weight: 500;
  text-decoration: none;
}

.dsg-link:hover {
  text-decoration: underline;
}

/* =========================================================
   TEACHING
========================================================= */

.teaching-section {
  margin-top: 58px;
}

.semester-group {
  margin-bottom: 28px;
}

.semester-group:last-child {
  margin-bottom: 0;
}

.semester-heading {
  display: flex;
  align-items: center;
  gap: 9px;
  margin-bottom: 13px;
}

.semester-heading h3 {
  margin: 0;
  color: #334155;
  font-size: 1.08rem;
  font-weight: 600;
  line-height: 1.3;
}

.semester-heading span {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 24px;
  height: 24px;
  border: 1px solid #cfe2dc;
  border-radius: 50%;
  color: #2e8b78;
  font-size: 0.63rem;
  font-weight: 600;
}

.course-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
}

.course-card {
  display: flex;
  min-height: 126px;
  flex-direction: column;
  align-items: flex-start;
  justify-content: space-between;
  gap: 12px;
  padding: 15px;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  background: #ffffff;
  box-shadow: 0 4px 14px rgba(15, 23, 42, 0.025);
  color: inherit;
  text-decoration: none;
  transition:
    border-color 0.2s ease,
    background-color 0.2s ease,
    box-shadow 0.2s ease,
    transform 0.2s ease;
}

.course-card:hover {
  border-color: #a9cec3;
  background: #fbfefd;
  box-shadow: 0 9px 22px rgba(15, 23, 42, 0.06);
  transform: translateY(-2px);
}

.course-card-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 26px;
  height: 26px;
  border-radius: 7px;
  background: #edf6f2;
  color: #2e8b78;
  font-size: 0.66rem;
  font-weight: 600;
}

.course-card h4 {
  width: 100%;
  margin: 0;
  color: #475569;
  font-size: 0.88rem;
  font-weight: 500;
  line-height: 1.45;
}

.course-card-link {
  display: flex;
  align-items: center;
  gap: 4px;
  color: #84909d;
  font-size: 0.7rem;
  font-weight: 400;
}

.course-card-link span {
  color: #2e8b78;
  font-size: 0.9rem;
}

/* =========================================================
   PUBLICATIONS
========================================================= */

.publication-list {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.publication {
  display: block;
  padding: 16px 19px;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  background: #ffffff;
  color: inherit;
  text-decoration: none;
  transition:
    border-color 0.2s ease,
    background-color 0.2s ease,
    transform 0.2s ease;
}

.publication:hover {
  border-color: #bfd8d0;
  background: #fbfefd;
  transform: translateX(2px);
}

.publication-meta {
  display: block;
  margin-bottom: 4px;
  color: #2e8b78;
  font-size: 0.68rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

.publication-title {
  display: block;
  color: #334155;
  font-size: 0.9rem;
  font-weight: 500;
  line-height: 1.45;
}

.publication-journal {
  display: block;
  margin-top: 4px;
  color: #84909d;
  font-size: 0.78rem;
  font-weight: 400;
  line-height: 1.4;
}

.section-link {
  display: inline-block;
  margin-top: 17px;
  color: #2e8b78;
  font-size: 0.83rem;
  font-weight: 500;
  text-decoration: none;
}

.section-link:hover {
  text-decoration: underline;
}

/* =========================================================
   TALKS AND CONFERENCES
========================================================= */

.conference-list {
  border-top: 1px solid #e2e8f0;
}

.conference {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  padding: 14px 0;
  border-bottom: 1px solid #e2e8f0;
}

.conference-content {
  min-width: 0;
}

.conference-content strong {
  display: block;
  margin-bottom: 3px;
  color: #475569;
  font-size: 0.9rem;
  font-weight: 500;
  line-height: 1.45;
}

.conference-content span {
  display: block;
  color: #84909d;
  font-size: 0.78rem;
  font-weight: 400;
  line-height: 1.4;
}

.conference-link {
  flex: 0 0 auto;
  color: #2e8b78;
  font-size: 0.78rem;
  font-weight: 500;
  text-decoration: none;
  white-space: nowrap;
}

.conference-link:hover {
  text-decoration: underline;
}

/* =========================================================
   GRANTS AND SCHOLARSHIPS
========================================================= */

.grant-card h3 {
  margin-bottom: 9px;
}

.grant-card p {
  color: #64748b;
}

/* =========================================================
   MENTORSHIP AND SUPERVISION
========================================================= */

.mentorship-box {
  display: grid;
  grid-template-columns: minmax(0, 1.35fr) minmax(220px, 0.65fr);
  gap: 28px;
  align-items: center;
  padding: 25px;
  border: 1px solid #dce7e3;
  border-radius: 16px;
  background:
    linear-gradient(135deg, #f5faf8 0%, #ffffff 70%);
}

.mentorship-content h3 {
  margin: 0 0 10px;
  color: #334155;
  font-size: 1.15rem;
  font-weight: 600;
  line-height: 1.4;
}

.mentorship-content p {
  margin: 0 0 15px;
  color: #64748b;
  font-size: 0.92rem;
  font-weight: 400;
  line-height: 1.7;
}

.mentorship-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 7px 20px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.mentorship-list li {
  position: relative;
  padding-left: 16px;
  color: #64748b;
  font-size: 0.84rem;
  font-weight: 400;
  line-height: 1.5;
}

.mentorship-list li::before {
  position: absolute;
  top: 0.58em;
  left: 0;
  width: 5px;
  height: 5px;
  border-radius: 50%;
  background: #2e8b78;
  content: "";
}

.mentorship-action {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding-left: 24px;
  border-left: 1px solid #dce7e3;
}

.mentorship-action-label {
  margin-bottom: 11px;
  color: #84909d;
  font-size: 0.78rem;
  font-weight: 400;
  line-height: 1.5;
}

.mentorship-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  padding: 11px 16px;
  border-radius: 9px;
  background: #2e8b78;
  color: #ffffff !important;
  font-size: 0.82rem;
  font-weight: 500;
  line-height: 1.3;
  text-align: center;
  text-decoration: none;
  transition:
    background-color 0.2s ease,
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.mentorship-button:hover {
  background: #246f60;
  color: #ffffff !important;
  box-shadow: 0 6px 15px rgba(46, 139, 120, 0.2);
  transform: translateY(-1px);
}

/* =========================================================
   PAGE NAVIGATOR
========================================================= */

.page-navigator {
  position: fixed;
  top: 50%;
  right: 20px;
  z-index: 1000;
  width: 170px;
  padding: 13px;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  background: rgba(255, 255, 255, 0.96);
  box-shadow: 0 8px 25px rgba(15, 23, 42, 0.07);
  backdrop-filter: blur(10px);
  transform: translateY(-50%);
}

.page-navigator-title {
  margin: 0 0 8px;
  padding-bottom: 8px;
  border-bottom: 1px solid #e2e8f0;
  color: #64748b;
  font-size: 0.66rem;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.page-navigator-links a {
  display: block;
  margin: 2px 0;
  padding: 5px 8px;
  border-radius: 6px;
  color: #64748b;
  font-size: 0.78rem;
  font-weight: 400;
  line-height: 1.35;
  text-decoration: none;
  transition:
    background-color 0.2s ease,
    color 0.2s ease;
}

.page-navigator-links a:hover,
.page-navigator-links a.active {
  background: #eef7f3;
  color: #2e8b78;
}

.page-navigator-links a.active {
  font-weight: 500;
}

/* =========================================================
   REVEAL ANIMATION
========================================================= */

.reveal {
  opacity: 0;
  transform: translateY(12px);
  transition:
    opacity 0.55s ease,
    transform 0.55s ease;
}

.reveal.active {
  opacity: 1;
  transform: none;
}

/* =========================================================
   ACCESSIBILITY
========================================================= */

a:focus-visible,
button:focus-visible {
  outline: 3px solid rgba(46, 139, 120, 0.35);
  outline-offset: 3px;
}

/* =========================================================
   RESPONSIVE DESIGN
========================================================= */

@media (max-width: 1150px) {
  .page-navigator {
    position: static;
    width: auto;
    margin: 0 0 30px;
    padding: 10px 12px;
    transform: none;
  }

  .page-navigator-title {
    margin-bottom: 6px;
    padding-bottom: 6px;
  }

  .page-navigator-links {
    display: flex;
    flex-wrap: wrap;
    gap: 4px;
  }

  .page-navigator-links a {
    display: inline-block;
    margin: 0;
  }
}

@media (max-width: 850px) {
  .grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .research-cards {
    grid-template-columns: 1fr;
  }

  .mentorship-box {
    grid-template-columns: 1fr;
  }

  .mentorship-action {
    align-items: flex-start;
    padding-top: 20px;
    padding-left: 0;
    border-top: 1px solid #dce7e3;
    border-left: 0;
  }
}

@media (max-width: 700px) {
  .course-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 9px;
  }

  .course-card {
    min-height: 120px;
    padding: 12px;
  }

  .course-card h4 {
    font-size: 0.8rem;
  }

  .course-card-link {
    font-size: 0.66rem;
  }

  .conference {
    align-items: flex-start;
    flex-direction: column;
    gap: 6px;
  }

  .conference-link {
    white-space: normal;
  }
}

@media (max-width: 560px) {
  .section {
    margin: 45px 0;
  }

  .intro {
    padding: 23px;
    margin-bottom: 45px;
  }

  .intro p {
    font-size: 0.94rem;
  }

  .grid {
    grid-template-columns: 1fr;
  }

  .course-grid {
    grid-template-columns: 1fr;
  }

  .course-card {
    min-height: 105px;
  }

  .mentorship-box {
    padding: 20px;
  }

  .mentorship-list {
    grid-template-columns: 1fr;
  }
}

@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }

  .reveal {
    opacity: 1;
    transform: none;
    transition: none;
  }

  .card,
  .course-card,
  .research-card,
  .publication,
  .btn,
  .mentorship-button {
    transition: none;
  }
}

/* =========================================================
   SMOOTH SCROLLING
========================================================= */

html {
  scroll-behavior: smooth;
}
</style>


<!-- =========================================================
     PAGE NAVIGATOR
========================================================= -->

<nav class="page-navigator" aria-label="Page navigation">
  <div class="page-navigator-title">On this page</div>

  <div class="page-navigator-links">
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#teaching">Teaching</a>
    <a href="#publications">Publications</a>
    <a href="#conferences">Talks & Conferences</a>
    <a href="#grants">Grants & Scholarships</a>
    <a href="#mentorship">Mentorship</a>
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
</section>


<!-- =========================================================
     RESEARCH ACTIVITIES
========================================================= -->

<section id="research" class="section reveal">
  <div class="section-heading">
    <span class="section-label">Research Activities</span>
    <h2>Research with purpose and application</h2>
  </div>

  <p class="section-intro">
    My research brings together mathematical modelling, statistical analysis,
    and data science to address challenges in health, education, and society.
  </p>

  <div class="research-cards">

    <article class="research-card">
      <div class="research-card-number">01 · Disease Modelling</div>
      <h3>Disease Modeling</h3>
      <p>
        Creating mathematical models to analyze how quarantine,
        cross-immunity, and media awareness campaigns affect the spread
        of co-circulating respiratory viruses.
      </p>
    </article>

    <article class="research-card">
      <div class="research-card-number">02 · Clinical Health</div>
      <h3>Clinical Health Metrics</h3>
      <p>
        Establishing baseline reference data for steady-state Sickle Cell
        Disease patients in Tanzania to improve local hospital care.
      </p>
    </article>

    <article class="research-card">
      <div class="research-card-number">03 · Socio-Educational</div>
      <h3>Socio-Educational Analytics</h3>
      <p>
        Investigating how lifestyle choices, internet habits, and social
        environments impact the academic performance of university students.
      </p>
    </article>

    <article class="research-card">
      <div class="research-card-number">04 · Research Leadership</div>
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

<section id="teaching" class="section teaching-section reveal">
  <div class="section-heading">
    <span class="section-label">Teaching Portfolio</span>
    <h2>Teaching</h2>
  </div>

  <p class="section-intro">
    Courses taught across undergraduate and postgraduate programmes,
    organized by semester.
  </p>

  <!-- Semester I -->
  <div class="semester-group">
    <div class="semester-heading">
      <h3>Semester I</h3>
      <!--<span>01</span>-->
    </div>

    <div class="course-grid">

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/qms101/"
      >
        <span class="course-card-number"> 01 </span>
        <h4>QMS 101: Introductory Statistics</h4>
        <span class="course-card-link">
          View course <span>↗</span>
        </span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/mat102/"
      >
        <span class="course-card-number">02</span>
        <h4>MAT 102: Ordinary DE</h4>
        <span class="course-card-link">
          View course <span>↗</span>
        </span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/mat103/"
      >
        <span class="course-card-number">03</span>
        <h4>MAT 103: Numerical Analysis I </h4>
        <span class="course-card-link">
          View course <span>↗</span>
        </span>
      </a>

    </div>
  </div>

  <!-- Semester II -->
  <div class="semester-group">
    <div class="semester-heading">
      <h3>Semester II</h3>
      <!--<span>02</span>-->
    </div>

    <div class="course-grid">

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/qms050/"
      >
        <span class="course-card-number">01</span>
        <h4> QMS 050: Business Maths & Stats </h4>
        <span class="course-card-link">
          View course <span>↗</span>
        </span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/mat050/"
      >
        <span class="course-card-number">02</span>
        <h4>MAT 050: Maths content I </h4>
        <span class="course-card-link">
          View course <span>↗</span>
        </span>
      </a>

      <a
        class="course-card"
        href="{{ site.baseurl }}/teaching/mat101/"
      >
        <span class="course-card-number">03</span>
        <h4>MAT 101: Linear Algebra I</h4>
        <span class="course-card-link">
          View course <span>↗</span>
        </span>
      </a>

    </div>
  </div>
</section>


<!-- =========================================================
     SELECTED PUBLICATIONS
========================================================= -->

<section id="publications" class="section reveal">
  <div class="section-heading">
    <span class="section-label">Selected Publications</span>
    <h2>Recent scholarly contributions</h2>
  </div>

  <p class="section-intro">
    Selected publications in mathematical modelling, epidemiology,
    and applied mathematics.
  </p>

  <div class="publication-list">

    <a
      class="publication"
      href="https://doi.org/10.1007/978-3-032-20404-2_16"
      target="_blank"
      rel="noopener"
    >
      <span class="publication-meta">Book Chapter · 2026</span>
      <span class="publication-title">
        Dynamics Around Equilibria in a Competitive Respiratory Disease
        System with Quarantine.
      </span>
      <span class="publication-journal">
        Progress in Industrial Mathematics at ECMI 2023 · Springer
      </span>
    </a>

    <a
      class="publication"
      href="https://doi.org/10.1186/s12889-025-24362-z"
      target="_blank"
      rel="noopener"
    >
      <span class="publication-meta">Journal Article · 2025</span>
      <span class="publication-title">
        Influenza–COVID-19 co-circulation in Germany 2020–2022:
        competitive dynamics with quarantine and cross-immunity.
      </span>
      <span class="publication-journal">
        BMC Public Health
      </span>
    </a>

    <a
      class="publication"
      href="https://doi.org/10.1016/j.amc.2024.128968"
      target="_blank"
      rel="noopener"
    >
      <span class="publication-meta">Journal Article · 2025</span>
      <span class="publication-title">
        Competitive respiratory disease system with quarantine:
        epidemic thresholds and cross-immunity.
      </span>
      <span class="publication-journal">
        Applied Mathematics and Computation
      </span>
    </a>

    <a
      class="publication"
      href="https://doi.org/10.1016/j.health.2023.100189"
      target="_blank"
      rel="noopener"
    >
      <span class="publication-meta">Journal Article · 2023</span>
      <span class="publication-title">
        A deterministic SIR model for studying the impact of media
        on epidemic dynamics.
      </span>
      <span class="publication-journal">
        Healthcare Analytics
      </span>
    </a>

    <a
      class="publication"
      href="https://doi.org/10.3390/hemato3010007"
      target="_blank"
      rel="noopener"
    >
      <span class="publication-meta">Journal Article · 2022</span>
      <span class="publication-title">
        Hematological and biochemical reference ranges for SCD patients
        in Tanzania.
      </span>
      <span class="publication-journal">
        Hemato
      </span>
    </a>

  </div>

  <a
    class="section-link"
    href="{{ site.baseurl }}/publications/"
  >
    View full publication list →
  </a>
</section>


<!-- =========================================================
     TALKS AND CONFERENCES
========================================================= -->

<section id="conferences" class="section reveal">
  <div class="section-heading">
    <span class="section-label">Academic Engagement</span>
    <h2>Talks &amp; Conferences</h2>
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

      <a
        class="conference-link"
        href="https://www.icipe.org/"
        target="_blank"
        rel="noopener"
      >
        Website ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>6th Young Researchers Symposium, RPTU</strong>
        <span>Germany · Pitch + Poster</span>
      </div>

      <a
        class="conference-link"
        href="https://rptu.de/"
        target="_blank"
        rel="noopener"
      >
        RPTU ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>2nd MONID Infectious Disease Modelling Conference</strong>
        <span>Halle, Germany · Pitch + Poster</span>
      </div>

      <a
        class="conference-link"
        href="https://monid.org/"
        target="_blank"
        rel="noopener"
      >
        MONID ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>Research Visit, Linnaeus University</strong>
        <span>Växjö, Sweden · Research visit and talk</span>
      </div>

      <a
        class="conference-link"
        href="https://lnu.se/en/"
        target="_blank"
        rel="noopener"
      >
        Linnaeus ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>Joint African-Nordic Conference in Mathematics</strong>
        <span>Uganda · Hybrid talk</span>
      </div>

      <a
        class="conference-link"
        href="https://www.mathunion.org/"
        target="_blank"
        rel="noopener"
      >
        IMU ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>22nd ECMI Conference on Industrial &amp; Applied Mathematics</strong>
        <span>Poland · Talk</span>
      </div>

      <a
        class="conference-link"
        href="https://ecmiindmath.org/"
        target="_blank"
        rel="noopener"
      >
        ECMI ↗
      </a>
    </div>

    <div class="conference">
      <div class="conference-content">
        <strong>14th DSABNS Conference on Dynamical Systems</strong>
        <span>Bilbao, Spain · Poster</span>
      </div>

      <a
        class="conference-link"
        href="https://www.dsabns.org/"
        target="_blank"
        rel="noopener"
      >
        DSABNS ↗
      </a>
    </div>

  </div>
</section>


<!-- =========================================================
     GRANTS AND SCHOLARSHIPS
========================================================= -->

<section id="grants" class="section reveal">
  <div class="section-heading">
    <span class="section-label">Academic Support</span>
    <h2>Grants &amp; Scholarships</h2>
  </div>

  <p class="section-intro">
    Selected scholarships and research funding supporting academic
    training, research, and professional development.
  </p>

  <div class="grid">

    <article class="card grant-card">
      <h3>DAAD Scholarship</h3>
      <p>
        PhD in Mathematics<br>
        RPTU Kaiserslautern-Landau, Germany
      </p>
    </article>

    <article class="card grant-card">
      <h3>AIMS–GSK Funds</h3>
      <p>
        Funding support for an internship at the
        Muhimbili Sickle-Cell Program.
      </p>
    </article>

    <article class="card grant-card">
      <h3>Mastercard Foundation Scholarship</h3>
      <p>
        MSc Mathematical Sciences<br>
        African Institute for Mathematical Sciences (AIMS)
      </p>
    </article>

  </div>
</section>


<!-- =========================================================
     MENTORSHIP AND SUPERVISION
========================================================= -->

<section id="mentorship" class="section reveal">
  <div class="section-heading">
    <span class="section-label">Mentorship &amp; Supervision</span>
    <h2>Supporting emerging researchers</h2>
  </div>

  <div class="mentorship-box">

    <div class="mentorship-content">
      <h3>Guidance for students and early-career researchers</h3>

      <p>
        I am interested in mentoring and supervising students and
        early-career researchers working in mathematics, statistics,
        data science, mathematical modelling, and public health.
      </p>

      <ul class="mentorship-list">
        <li>Research project development</li>
        <li>Mathematical and statistical modelling</li>
        <li>Data analysis and scientific computing</li>
        <li>Academic writing and research communication</li>
        <li>Undergraduate research mentorship</li>
        <li>Postgraduate research supervision</li>
      </ul>
    </div>

    <div class="mentorship-action">
      <span class="mentorship-action-label">
        Interested in discussing a research or mentorship opportunity?
      </span>

      <a
        class="mentorship-button"
        href="https://calendar.app.google/RF8rbheuphgiRurh6"
        target="_blank"
        rel="noopener"
      >
        Schedule a mentorship session
        <span aria-hidden="true">↗</span>
      </a>
    </div>

  </div>
</section>


<!-- =========================================================
     REVEAL ANIMATION AND NAVIGATION SCRIPT
========================================================= -->

<script>
document.addEventListener("DOMContentLoaded", function () {
  /* Reveal sections as they enter the viewport */
  const revealElements = document.querySelectorAll(".reveal");

  if ("IntersectionObserver" in window) {
    const revealObserver = new IntersectionObserver(
      function (entries, observer) {
        entries.forEach(function (entry) {
          if (entry.isIntersecting) {
            entry.target.classList.add("active");
            observer.unobserve(entry.target);
          }
        });
      },
      {
        threshold: 0.08
      }
    );

    revealElements.forEach(function (element) {
      revealObserver.observe(element);
    });
  } else {
    revealElements.forEach(function (element) {
      element.classList.add("active");
    });
  }

  /* Highlight the current section in the page navigator */
  const sections = document.querySelectorAll(
    "#about, #research, #teaching, #publications, " +
    "#conferences, #grants, #mentorship"
  );

  const navLinks = document.querySelectorAll(".page-navigator a");

  if ("IntersectionObserver" in window) {
    const navigationObserver = new IntersectionObserver(
      function (entries) {
        entries.forEach(function (entry) {
          if (entry.isIntersecting) {
            navLinks.forEach(function (link) {
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

    sections.forEach(function (section) {
      navigationObserver.observe(section);
    });
  }
});
</script>
