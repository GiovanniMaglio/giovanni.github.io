---
layout: splash
title: "Giovanni Maglio"
permalink: /
classes: no-masthead
header:
  overlay_image: /assets/img/header.jpg
  overlay_color: "#0f172a"   # blu notte
  overlay_filter: 0.25
excerpt: "Physics • Phenomenology • QFT"
---

<style>
/* nasconde topbar solo in home */
.no-masthead .masthead { display:none !important; }
.no-masthead .initial-content { padding-top:0 !important; }

/* tipografia più professionale */
body, .page__content {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  color: #1f2937;
}
.page__title { letter-spacing: .02em; }

/* hero più “piatto” */
.page__hero {
  min-height: 38vh;
  display: flex;
  align-items: center;
  padding: 3.4rem 2rem 2.3rem;
}
.page__hero .wrapper { width: 100%; }

/* blocco intro */
.hero-grid {
  display: flex;
  gap: 2.2rem;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}
.hero-text {
  flex: 1 1 58%;
  min-width: 280px;
}
.hero-text h1 {
  margin-bottom: .35rem;
  font-weight: 700;
  font-size: clamp(2.15rem, 2.6vw, 2.55rem);
  color: #f1f5f9;
  text-shadow: 0 3px 16px rgba(0,0,0,.35);
}
.hero-text p {
  color: #e2e8f0;
  max-width: 40rem;
  line-height: 1.25;
}
.hero-meta {
  margin-top: .9rem;
  color: #e2e8f0;
  font-size: .9rem;
}

/* foto profilo più seria (non troppo rotonda) */
.hero-photo {
  flex: 0 0 190px;
  text-align: right;
}
.hero-photo img {
  width: 180px;
  height: 180px;
  border-radius: 18px;
  object-fit: cover;
  border: 3px solid rgba(226,232,240,.2);
  box-shadow: 0 12px 26px rgba(15,23,42,.55);
}

/* pulsanti: tono blu-prof, bordi leggeri */
.btn-prof {
  display: inline-flex;
  align-items: center;
  gap: .35rem;
  background: #1d4ed8;
  color: #fff !important;
  padding: .42rem .85rem;
  border-radius: .5rem;
  font-weight: 500;
  font-size: .82rem;
  border: 1px solid rgba(255,255,255,.08);
  transition: transform .12s ease-out, box-shadow .12s ease-out;
}
.btn-prof:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(29,78,216,.35);
}

/* sezioni sotto: cards sobrie */
.section-block {
  background: #fff;
  border: 1px solid rgba(15,23,42,.04);
  border-left: 4px solid #1d4ed8;
  border-radius: .6rem;
  padding: 1.25rem 1.4rem 1rem;
  margin-bottom: 1.15rem;
  box-shadow: 0 6px 16px rgba(15,23,42,.02);
}
.section-block h2 {
  font-size: 1.02rem;
  margin-bottom: .4rem;
  color: #0f172a;
}
.section-block p {
  margin-bottom: .5rem;
  color: #374151;
}

/* lista link rapidi in colonna */
.quick-links a {
  display: inline-block;
  margin-right: .5rem;
  margin-bottom: .5rem;
}

/* responsive */
@media (max-width: 880px) {
  .hero-grid { flex-direction: column; align-items: flex-start; }
  .hero-photo { text-align: left; }
  .hero-photo img { width: 140px; height: 140px; border-radius: 16px; }
  .page__hero { padding: 2.7rem 1.2rem 1.7rem; }
}
</style>

<div class="hero-grid">
  <div class="hero-text">
    <h1>Giovanni Maglio</h1>
    <p>Physics graduate, University of Milan (B.Sc., 2025).
    Interests in theoretical and mathematical physics, electroweak sector, and proton structure parametrization.</p>
    <div class="hero-meta">
      Crema (CR), Italy · <a href="mailto:giovanni.maglio@studenti.unimi.it" style="color:#bfdbfe;">giovanni.maglio@studenti.unimi.it</a>
    </div>
    <div style="margin-top:1rem;" class="quick-links">
      <a class="btn-prof" href="{{ site.baseurl }}/about/">CV & profile</a>
      <a class="btn-prof" href="{{ site.baseurl }}/research/">Research</a>
      <a class="btn-prof" href="{{ site.baseurl }}/publications/">Publications</a>
    </div>
  </div>
  <div class="hero-photo">
    <img src="{{ site.baseurl }}/assets/img/avatar.jpeg" alt="Portrait of Giovanni Maglio">
  </div>
</div>

---

<div class="section-block" id="about">
  <h2>About</h2>
  <p>I am interested in the interplay between phenomenology and the formal structure of the Standard Model, especially in how proton parametrizations and electroweak inputs affect collider observables.</p>
  <p><a class="btn-prof" href="{{ site.baseurl }}/about/">Open CV</a></p>
</div>

<div class="section-block" id="research">
  <h2>Research</h2>
  <p>Thesis (B.Sc., 23/10/2025): <em>“Uncertainties in the parametrization of the proton and determination of the electroweak parameters in the Standard Model Lagrangian”</em>, supervisor: Prof. Alessandro Vicini.</p>
  <p><a class="btn-prof" href="{{ site.baseurl }}/research/">Explore research</a></p>
</div>

<div class="section-block" id="projects">
  <h2>Projects</h2>
  <p>Book review platform <em>RecenSito</em> · small numerical/plotting tools in C/C++/Python · LaTeX templates for academic writing.</p>
  <p><a class="btn-prof" href="{{ site.baseurl }}/projects/">View projects</a></p>
</div>

<div class="section-block" id="publications">
  <h2>Publications & Thesis</h2>
  <p>Undergraduate thesis available here:</p>
  <p><a class="btn-prof" href="https://giovannimaglio.github.io/thesis/thesis.pdf">Download thesis (PDF)</a></p>
</div>

<div class="section-block" id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:giovanni.maglio@studenti.unimi.it">giovanni.maglio@studenti.unimi.it</a><br>
     GitHub: <a href="https://github.com/giovannimaglio">github.com/giovannimaglio</a></p>
</div>
