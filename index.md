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

/* LOGO GRID */
.logo-grid {
  display: flex;
  justify-content: center;
  gap: 40px;
  flex-wrap: wrap;
  margin-top: 30px;
}

/* LOGO + TOOLTIP */
.logo-item {
  position: relative;
}

.logo-item img {
  width: 150px;
  border-radius: 10px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.logo-item img:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 20px rgba(0,0,0,0.15);
}

/* TOOLTIP */
.logo-item .tooltip {
  visibility: hidden;
  opacity: 0;
  width: 220px;
  background-color: #ffffff;
  color: #333;
  text-align: center;
  padding: 10px 12px;
  border-radius: 8px;
  position: absolute;
  bottom: -75px;
  left: 50%;
  transform: translateX(-50%);
  box-shadow: 0 8px 18px rgba(0,0,0,0.15);
  font-size: 0.85rem;
  line-height: 1.3;
  transition: opacity 0.3s ease;
  z-index: 10;
}

.logo-item:hover .tooltip {
  visibility: visible;
  opacity: 1;
}
</style>

<!-- BIO -->
<div style="text-align:center; margin-top:40px; margin-bottom:40px;">

  <img src="/assets/images/bio/bio.jpg"
       alt="Lorena Jiménez Sánchez"
       style="width:120px; height:120px; border-radius:50%; object-fit:cover; margin-bottom:20px;" />

  <h1 style="color:var(--accent); margin-bottom:5px;">
    Lorena Jiménez Sánchez
  </h1>

  <!-- CONTACT ICONS -->
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

  <!-- LOGOS DIRECTLY UNDER BIO -->
  <div class="logo-grid">

    <div class="logo-item">
      <a href="https://richardsonlab.ppls.ed.ac.uk/lab-values/" target="_blank">
        <img src="/assets/images/logos/logo1.jpg" alt="Richardson Lab logo">
      </a>
      <div class="tooltip">
        <strong>Richardson Lab logo</strong><br>
        University of Edinburgh
      </div>
    </div>

    <div class="logo-item">
      <a href="https://inspiremsk.stir.ac.uk/glossary/" target="_blank">
        <img src="/assets/images/logos/logo2.jpg" alt="INSPIRE MSK logo">
      </a>
      <div class="tooltip">
        <strong>INSPIRE MSK project</strong><br>
        University of Stirling
      </div>
    </div>

  </div>

</div>
