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
  justify-content: center; /* center all items */
  gap: 50px;               /* uniform spacing */
  flex-wrap: wrap;
  margin-top: 30px;
}

.logo-item {
  position: relative;
  width: 160px;  
  height: 160px; 
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
}

.logo-item img {
  max-width: 100%;
  max-height: 100%;
  display: block;
  border-radius: 10px;
  transition: opacity 0.3s ease, transform 0.3s ease;
}

/* Circular images: press releases & scientific publications */
.logo-item.press img,
.logo-item.scientific img {
  border-radius: 50%;
  object-fit: cover;
  width: 140px;
  height: 140px;
}

/* Hover overlay */
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
  color: #333;  
  opacity: 0;
  transition: opacity 0.3s ease;
  box-shadow: 0 8px 18px rgba(0,0,0,0.15);
}

.logo-item:hover img {
  opacity: 0;
  transform: scale(1.05);
}

.logo-item:hover .logo-overlay {
  opacity: 1;
}

/* Section heading colors */
.visual-contributions {
  color: var(--accent); /* sage */
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

  <p style="max-width:600px; margin:0 auto 30px auto;">
    Researcher and visual storyteller with a background in neuroscience (MSc, PhD).
    Passionate about transforming complex ideas into visually engaging, accessible
    content that connects science and people.
  </p>

</div>

<!-- VISUAL CONTRIBUTIONS -->
<div style="text-align:center; margin-top:50px; margin-bottom:60px;">

  <h2 class="visual-contributions">Visual Contributions</h2>

  <!-- SCIENTIFIC PUBLICATIONS -->
  <h3 class="subsection-title">Scientific Publications</h3>

  <p style="max-width:600px; margin:0 auto 30px auto;">
    Visual figures and illustrations produced for scientific articles and journals.
  </p>

  <div class="logo-grid">
    <a class="logo-item scientific" href="https://kids.frontiersin.org/articles/10.3389/frym.2025.1508144" target="_blank">
      <img src="/assets/images/scientific/scientific1.jpg" alt="Publication 1">
      <div class="logo-overlay">University of Edinburgh, 2025</div>
    </a>

    <a class="logo-item scientific" href="https://www.sciencedirect.com/science/article/pii/S1878929324000483" target="_blank">
      <img src="/assets/images/scientific/scientific2.jpg" alt="Publication 2">
      <div class="logo-overlay">University of Edinburgh, 2024</div>
    </a>

    <a class="logo-item scientific" href="https://link.springer.com/article/10.1007/s00429-023-02725-9" target="_blank">
      <img src="/assets/images/scientific/scientific3.jpg" alt="Publication 3">
      <div class="logo-overlay">Universidad Autónoma de Madrid, 2024</div>
    </a>

    <a class="logo-item scientific" href="https://journals.sagepub.com/doi/full/10.1089/aut.2021.0017" target="_blank">
      <img src="/assets/images/scientific/scientific4.jpg" alt="Publication 4">
      <div class="logo-overlay">University of Edinburgh, 2021</div>
    </a>

    <a class="logo-item scientific" href="https://www.sciencedirect.com/science/article/pii/S0889159121002336" target="_blank">
      <img src="/assets/images/scientific/scientific5.jpg" alt="Publication 5">
      <div class="logo-overlay">University of Edinburgh, 2021</div>
    </a>

    <a class="logo-item scientific" href="https://onlinelibrary.wiley.com/doi/10.1002/ca.23394" target="_blank">
      <img src="/assets/images/scientific/scientific6.jpg" alt="Publication 6">
      <div class="logo-overlay">Universidad Autónoma de Madrid, 2020</div>
    </a>

    <a class="logo-item scientific" href="https://www.annualreviews.org/content/journals/10.1146/annurev-bioeng-062117-121036" target="_blank">
      <img src="/assets/images/scientific/scientific7.jpg" alt="Publication 7">
      <div class="logo-overlay">Universidad Autónoma de Madrid, 2019</div>
    </a>
  </div>

  <!-- LOGOS -->
  <h3 class="subsection-title">Logos</h3>

  <p style="max-width:600px; margin:0 auto 30px auto;">
    Visual identities and logos created for academic labs and research projects.
  </p>

  <div class="logo-grid">
    <a class="logo-item" href="https://inspiremsk.stir.ac.uk/glossary/" target="_blank">
      <img src="/assets/images/logos/logo2.jpg" alt="University of Stirling">
      <div class="logo-overlay">University of Stirling, 2026</div>
    </a>
    
    <a class="logo-item" href="https://richardsonlab.ppls.ed.ac.uk/lab-values/" target="_blank">
      <img src="/assets/images/logos/logo1.jpg" alt="University of Edinburgh">
      <div class="logo-overlay">University of Edinburgh, 2024</div>
    </a>

    <a class="logo-item" href="https://www.facebook.com/GlasgowNeuroSociety/posts/the-great-glasgow-brain-fest-this-july-we-have-a-message-for-you-from-the-bna-if/1548628088628053/" target="_blank">
    <img src="/assets/images/logos/logo3.png" alt="British Neuroscience Association">
    <div class="logo-overlay">British Neuroscience Association, 2020</div>
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
      <div class="logo-overlay">Asociación ECO, 2019</div>
    </a>
  </div>

</div>

<!-- CONTACT ME SECTION -->
<div style="text-align:center; margin-top:50px; margin-bottom:60px;">
  <h2 class="visual-contributions">Contact Me</h2>

  <p style="max-width:600px; margin:20px auto 0 auto; color:#333333; font-size:1rem;">
    Send me an email at 
    <a href="mailto:lorena.jimenezs@ed.ac.uk" style="color:#333333; text-decoration:underline;">
      lorena.jimenezs@ed.ac.uk
    </a>
  </p>
</div>
