---
layout: page
title: ""
permalink: /
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@1,500;1,600&display=swap');

:root {
  --accent: #3FA7A0;
  --text-dark: #333333;
  --font-sans: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  --font-script: 'Playfair Script', cursive;
}

/* BODY */
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
}

/* NAME TITLE */
.name-title {
  font-family: var(--font-script);
  font-size: 2.8rem;
  font-weight: 500;
  letter-spacing: 0.5px;
  color: var(--accent);
  margin-bottom: 10px;
}

/* BIO TEXT */
.bio-text {
  max-width: 600px;
  margin: 0 auto;
  font-size: 1rem;
  text-align: center;
}

/* SECTION HEADINGS */
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
}

/* Circular logos */
.logo-item.press img,
.logo-item.scientific img {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
}

/* Rectangular logos */
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

/* MOBILE */
@media (max-width: 500px) {
  .name-title {
    font-size: 2.3rem;
  }

  .logo-grid {
    gap: 30px;
  }

  .logo-item {
    width: 120px;
    height: 120px;
  }
}
</style>

<!-- BIO -->
<div style="text-align:center; margin-top:40px;">
  <img class="bio-img" src="/assets/images/bio/bio.jpg" alt="Lorena Jiménez Sánchez" />
  <h1 class="name-title">Lorena Jiménez Sánchez</h1>

  <p class="bio-text">
    Researcher and visual storyteller with a background in neuroscience (MSc, PhD).
    Passionate about transforming complex ideas into visually engaging, accessible content.
  </p>

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

<!-- CONTACT ME -->
<div class="section" style="text-align:center; margin-top:50px; margin-bottom:60px;">
  <h2 class="visual-contributions">Contact Me</h2>
  <p>
    Send me an email at
    <a href="mailto:lorena.jimenezs@ed.ac.uk" style="color:#333333;">
      lorena.jimenezs@ed.ac.uk
    </a>
  </p>
</div>
