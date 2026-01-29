---
layout: page
title: ""
permalink: /
---

<style>
:root {
  --accent: #3FA7A0; /* teal-sage */
}

/* CONTACT ICONS */
.contact-icons {
  display: flex;
  justify-content: center;
  gap: 18px;
  margin: 15px 0 25px 0;
}

.contact-icons img {
  width: 28px;
  height: 28px;
  opacity: 0.75;
  transition: opacity 0.3s ease, transform 0.3s ease;
}

.contact-icons img:hover {
  opacity: 1;
  transform: translateY(-2px);
}

/* LOGO / CARD GRID */
.logo-grid {
  display: flex;
  justify-content: center;
  gap: 40px;
  flex-wrap: wrap;
  margin-top: 30px;
}

.logo-item {
  position: relative;
  width: 150px;
  height: 150px;
  text-decoration: none;
}

.logo-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px; /* default for logos */
  transition: opacity 0.3s ease;
}

/* Make press release images circular */
.logo-item.press img {
  border-radius: 50%;
}

/* OVERLAY TEXT */
.logo-overlay {
  position: absolute;
  inset: 0;
  background: rgba(255, 255, 255, 0.95);
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 12px;
  font-size: 0.85rem;
  line-height: 1.3;
  color: #333333;  /* dark gray overlay text */
  opacity: 0;
  transition: opacity 0.3s ease;
  box-shadow: 0 8px 18px rgba(0,0,0,0.15);
}

.logo-item:hover img {
  opacity: 0;
}

.logo-item:hover .logo-overlay {
  opacity: 1;
}

/* Section heading colors */
.visual-contributions {
  color: var(--accent);
}

.subsection-title {
  color: black;
  margin-top: 40px;
}
</style>

<!-- BIO -->
<div style="text-align:center; margin-top:40px;">

  <img src="/assets/images/bio/bio.jpg"
       alt="Lorena Jiménez Sánchez"
       style="width:120px; height:120px; border-radius:50%; object-fit:cover; margin-bottom:20px;" />

  <h1 style="color:var(--accent); margin-bottom:5px;">
    Lorena Jiménez Sánchez
  </h1>

  <!-- CONTACT ICONS BELOW BIO TEXT -->
  <div class="contact-icons">
    <a href="mailto:lorena.jimenezs@ed.ac.uk">
      <img src="/assets/icons/email.svg" alt="Email">
    </a>
    <a href="https://github.com/lorenajs" target="_blank">
      <img src="/assets/icons/github.svg" alt="GitHub">
    </a>
    <a href="https://www.researchgate.net/profile/Lorena-Jimenez-Sanchez" target="_blank">
      <img src="/assets/icons/researchgate.svg" alt="ResearchGate">
    </a>
  </div>

  <p style="max-width:600px; margin:0 auto;">
    Researcher and visual storyteller with a background in neuroscience (MSc, PhD).
    Passionate about transforming complex ideas into visually engaging, accessible
    content that connects science and people.
  </p>

</div>

<!-- VISUAL CONTRIBUTIONS -->
<div style="text-align:center; margin-top:50px; margin-bottom:60px;">

  <h2 class="visual-contributions">Visual Contributions</h2>

  <!-- LOGOS -->
  <h3 class="subsection-title">Logos</h3>

  <p style="max-width:600px; margin:0 auto 30px auto;">
    Visual identities and logos created for academic labs and research projects.
  </p>

  <div class="logo-grid">

    <a class="logo-item"
       href="https://richardsonlab.ppls.ed.ac.uk/lab-values/"
       target="_blank">
      <img src="/assets/images/logos/logo1.jpg" alt="University of Edinburgh">
      <div class="logo-overlay">
        University of Edinburgh
      </div>
    </a>

    <a class="logo-item"
       href="https://inspiremsk.stir.ac.uk/glossary/"
       target="_blank">
      <img src="/assets/images/logos/logo2.jpg" alt="University of Stirling">
      <div class="logo-overlay">
        University of Stirling
      </div>
    </a>

  </div>

  <!-- PRESS RELEASES -->
  <h3 class="subsection-title">Press Releases</h3>

  <p style="max-width:600px; margin:0 auto 30px auto;">
    Illustrations and visual assets developed for institutional communication and public outreach.
  </p>

  <div class="logo-grid">

    <a class="logo-item press"
       href="https://asociacioneco.wordpress.com/2019/03/15/como-mujer-el-hecho-de-tener-otro-color-nos-perjudica-dentro-del-propio-genero/"
       target="_blank">
      <img src="/assets/images/press/press1.jpg" alt="Asociación ECO">
      <div class="logo-overlay">
        Asociación ECO
      </div>
    </a>

  </div>

</div>
