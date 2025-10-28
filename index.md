---
layout: splash
title: "Giovanni Maglio"
permalink: /
classes: no-masthead   
header:
  overlay_image: /assets/img/header.jpg
  overlay_color: "#1a2a52"
  overlay_filter: 0.15
excerpt: "Personal site • Physics and more"
---

<style>
/* Nasconde la top bar solo in questa pagina (che ha body.no-masthead) */
.no-masthead .masthead { display: none !important; }
.no-masthead .initial-content { padding-top: 0 !important; }

/* Title & subtitle readability sull'hero */
.page__hero .page__title,
.page__hero .page__lead {
  color: #f9fafc;
  text-shadow: 0 2px 8px rgba(0,0,0,.45);
  letter-spacing: 0.3px;
}

/* Titoli sezione con underline azzurro opaco */
.page__content h2 {
  margin-top: 2.2rem;
  padding-bottom: .3rem;
  border-bottom: 2px solid #7da3c8;
  color: #0d1a33;
}

/* Pulsanti tutti azzurro accademico opaco */
.btn--primary,
.btn--info,
.btn--success {
  background-color: #7da3c8 !important;
  border: none !important;
  color: #fff !important;
  transition: all 0.2s ease-in-out;
}
.btn--primary:hover,
.btn--info:hover,
.btn--success:hover { filter: brightness(1.12); }

/* ===== Intro layout (foto a destra su desktop) ===== */
.intro-wrapper {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 1.2rem;
  margin-bottom: 2rem;
}
.intro-text   { flex: 1 1 60%; min-width: 260px; }
.intro-photo  { flex: 1 1 30%; min-width: 180px; text-align: right; }

.intro-photo img {
  width: 220px;             /* desktop */
  height: 220px;            /* desktop */
  max-width: 100%;
  border-radius: 50%;
  border: 3px solid #1a2a52;
  box-shadow: 0 4px 14px rgba(0,0,0,.2);
  object-fit: cover;
}

/* ===== Tablet (riduciamo leggermente) ===== */
@media (max-width: 992px) {
  .intro-photo img {
    width: 190px;
    height: 190px;
  }
}

/* ===== Smartphone (stack a colonna, niente sovrapposizioni) ===== */
@media (max-width: 640px) {
  .intro-wrapper {
    flex-direction: column;        /* mettiamo in colonna */
    align-items: flex-start;       /* testo allineato a sinistra */
  }
  .intro-text { order: 1; width: 100%; }
  .intro-photo { 
    order: 2;                      /* foto sotto il nome/bio */
    width: 100%; 
    text-align: center;            /* centriamo la foto */
    margin-top: .5rem;
  }
  .intro-photo img {
    width: 150px;                  /* più piccola su mobile */
    height: 150px;
  }
  /* Margini titolo/bio per evitare incastri */
  .intro-text h1 { margin-bottom: .35rem; }
  .intro-text p  { margin-top: .25rem; }
}
</style>

---

<div class="intro-wrapper">
  <div class="intro-text">
    <h1 style="margin-bottom:0.5rem;">Giovanni Maglio</h1>
    <p style="margin-top:0; font-size:1.05rem; color:#1e293b;">
      Physics graduate from the University of Milan, with research interests in 
      <strong>theoretical physics</strong> and 
      <strong>mathematical structures of fundamental interactions</strong>.
    </p>
  </div>
  <div class="intro-photo">
    <img src="{{ site.baseurl }}/assets/img/avatar.jpeg" alt="Giovanni Maglio portrait">
  </div>
</div>

---

## 👤 About & CV {#about}
[Open CV]({{ site.baseurl }}/about/){: .btn .btn--primary }

---

## 🔬 Research {#research}
[Explore Research]({{ site.baseurl }}/research/){: .btn .btn--primary }

---

## 🧰 Projects {#projects}
[View Projects]({{ site.baseurl }}/projects/){: .btn .btn--primary }

---

## 📚 Publications {#publications}

---

## ✉️ Contact {#contact}
- **Email:** <giovanni.maglio@studenti.unimi.it>
