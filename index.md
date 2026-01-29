---
layout: page
title: ""
permalink: /
---

<style>
:root {
  --accent: #4FB6B0; /* teal-sage */
}

.contact-icons {
  display: flex;
  justify-content: center;
  gap: 18px;
  margin: 15px 0 30px 0;
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

.logo-grid {
  display: flex;
  justify-content: center;
  gap: 40px;
  flex-wrap: wrap;
}

.logo-grid img {
  width: 160px;
  border-radius: 10px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.logo-grid img:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 20px rgba(0,0,0,0.15);
}
</style>

<!-- BIO -->
<div style="text-align:center; margin-top:40px; margin-bottom:50px;">

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
    <a href="https://www.researchgate.net/profile/lorena-jimenez-sanchez" target="_blank">
      <img src="/assets/icons/researchgate.svg" alt="ResearchGate">
    </a>
  </div>

  <p style="max-width:600px; margin:0 auto;">
    Researcher and visual storyteller with a background in neuroscience (MSc, PhD).
    Passionate about transforming complex ideas into visually engaging, accessible
    content that connects science and people.
  </p>

</div>

<hr style="margin:60px auto; max-width:200px;">

<!-- VISUAL CONTRIBUTIONS -->
<div style="text-align:center; margin-bottom:60px;">

  <h2 style="margin-bottom:40px;">
    Visual Contributions
  </h2>

  <!-- LAB LOGOS -->
  <div>

    <h3 style="color:var(--accent); margin-bottom:10px;">
      Lab Logo Creations
    </h3>

    <p style="max-width:600px; margin:0 auto 30px auto;">
      Custom logos and visual identities designed for research labs and initiatives.
    </p>

    <div class="logo-grid">

      <a href="https://richardsonlab.ppls.ed.ac.uk/lab-values/" target="_blank">
        <img src="/assets/images/logos/logo1.jpg" alt="Richardson Lab logo">
      </a>

      <a href="https://inspiremsk.stir.ac.uk/glossary/" target="_blank">
        <img src="/assets/images/logos/logo2.jpg" alt="INSPIRE MSK logo">
      </a>

    </div>

  </div>

</div>
