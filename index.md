---
layout: page
title: ""
permalink: /
---

<style>
:root {
  --accent: #3FA7A0; /* teal-sage */
  --text-dark: #333333;
  --font-sans: 'Helvetica Neue', Helvetica, Arial, sans-serif;
}

/* BODY FONT */
body {
  font-family: var(--font-sans);
  line-height: 1.6;
  color: var(--text-dark);
  background-color: #ffffff;
  margin: 0;
}

/* BIO IMAGE */
.bio-img {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
  transition: transform 0.3s ease;
}

.bio-img:hover {
  transform: scale(1.05);
}

/* BIO TEXT */
.bio-text {
  max-width: 600px;
  margin: 0 auto;
  font-size: 1rem;
  text-align: center;
}

/* HEADINGS */
.visual-contributions {
  color: var(--accent);
  font-size: 2.2rem;
  margin-bottom: 30px;
  text-align: center;
}

.subsection-title {
  color: var(--text-dark);
  font-size: 1.6rem;
  margin-top: 50px;
  margin-bottom: 20px;
  text-align: center;
}

/* PARAGRAPHS */
p {
  max-width: 600px;
  margin: 0 auto 30px auto;
  font-size: 1rem;
  text-align: center;
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

.logo-item {
  position: relative;
  width: 160px;
  height: 160px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  transition: transform 0.3s ease;
}

/* Circular logos: press & scientific */
.logo-item.press img,
.logo-item.scientific img {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
}

/* Rectangular logos: keep full image */
.logo-item.rect img {
  width: 140px;
  height: auto;
  border-radius: 10px;
  object-fit: contain;
}

/* Hover overlay */
.logo-overlay {
  position: absolute;
  inset: 0;
  background: rgba(255, 255, 255, 0.95);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 12px;
  font-size: 0.85rem;
  line-height: 1.3;
  color: var(--text-dark);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.logo-item:hover img {
  opacity: 0;
  transform: scale(1.05);
}

.logo-item:hover .logo-overlay {
  opacity: 1;
}

/* CONTACT LINK */
.contact-section a {
  color: #333333;
  text-decoration: underline;
  font-weight: 500;
}

@media (max-width: 500px) {
  .logo-grid {
    gap: 30px;
  }

  .logo-item {
    width: 120px;
    height: 120px;
  }

  .logo-item img {
    width: 110px;
    height: 110px;
  }
}
</style>

<!-- BIO -->
<div style="text-align:center; margin-top:40px;">
  <img class="bio-img" src="/assets/images/bio/bio.jpg" alt="Lorena Jiménez Sánchez" />
  <h1 style="color:var(--accent); margin-bottom:10px;">Lorena Jiménez Sánchez</h1>
  <p class="bio-text">
    Researcher and visual storyteller with a background in neuroscience (MSc, PhD). 
    Passionate about transforming complex ideas into visually engaging, accessible content.
  </p>

  <!-- CONTACT ICONS BELOW BIO -->
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
    <a href="https://uk.linkedin.com/in/lorena-jim%C3%A9nez" target="_blank">
      <img src="/assets/icons/linkedin.svg" alt="LinkedIn">
    </a>
  </div>
</div>

<!-- VISUAL CONTRIBUTIONS -->
<div class="section" style="text-align:center; margin-top:50px; margin-bottom:60px;">
  <h2 class="visual-contributions">Visual Contributions</h2>

  <!-- Scientific Publications -->
  <h3 class="subsection-title">Scientific Publications</h3>
  <p>Visual figures and illustrations produced for scientific articles and journals.</p>
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
      <img src="/assets/images/scientific/scientific4.png" alt="Publication 4">
      <div class="logo-overlay">University of Edinburgh, 2021</div>
    </a>
    <a class="logo-item scientific" href="https://www.sciencedirect.com/science/article/pii/S0889159121002336" target="_blank">
      <img src="/assets/images/scientific/scientific5.png" alt="Publication 5">
      <div class="logo-overlay">University of Edinburgh, 2021</div>
    </a>
    <a class="logo-item scientific" href="https://onlinelibrary.wiley.com/doi/10.1002/ca.23394" target="_blank">
      <img src="/assets/images/scientific/scientific6.png" alt="Publication 6">
      <div class="logo-overlay">Universidad Autónoma de Madrid, 2020</div>
    </a>
    <a class="logo-item scientific" href="https://www.annualreviews.org/content/journals/10.1146/annurev-bioeng-062117-121036" target="_blank">
      <img src="/assets/images/scientific/scientific7.jpg" alt="Publication 7">
      <div class="logo-overlay">Universidad Autónoma de Madrid, 2019</div>
    </a>
  </div>

  <!-- Logos -->
  <h3 class="subsection-title">Logos</h3>
  <p>Visual identities and logos created for research teams, projects, and initiatives.</p>
  <div class="logo-grid">
    <!-- Inspire MSK logo full -->
    <a class="logo-item rect" href="https://inspiremsk.stir.ac.uk/glossary/" target="_blank">
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

  <!-- Others -->
  <h3 class="subsection-title">Others</h3>
  <p>Illustrations and visual assets developed for other contexts i.e., press releases.</p>
  <div class="logo-grid">
    <a class="logo-item press" href="https://asociacioneco.wordpress.com/2019/03/15/como-mujer-el-hecho-de-tener-otro-color-nos-perjudica-dentro-del-propio-genero/" target="_blank">
      <img src="/assets/images/press/press1.jpg" alt="Asociación ECO">
      <div class="logo-overlay">Asociación ECO, 2019</div>
    </a>
  </div>
</div>

<!-- CONTACT ME -->
<div class="section" style="text-align:center; margin-top:50px; margin-bottom:60px;">
  <h2 class="visual-contributions">Contact Me</h2>
  <p>Send me an email at <a href="mailto:lorena.jimenezs@ed.ac.uk" style="color:#333333;">lorena.jimenezs@ed.ac.uk</a></p>
</div>
