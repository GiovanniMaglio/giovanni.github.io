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

/* Title & subtitle readability */
.page__hero .page__title,
.page__hero .page__lead {
  color: #f9fafc;
  text-shadow: 0 2px 8px rgba(0,0,0,.45);
  letter-spacing: 0.3px;
}

/* Section titles with subtle blue underline */
.page__content h2 {
  margin-top: 2.2rem;
  padding-bottom: .3rem;
  border-bottom: 2px solid #1a2a52;
  color: #0d1a33;
}

/* Button tones adjusted to match the academic blue palette */
.btn--primary   { background-color:#1e3a8a; border:none; }
.btn--info      { background-color:#2563eb; border:none; }
.btn--success   { background-color:#1e40af; border:none; }
.btn--primary:hover,
.btn--info:hover,
.btn--success:hover { filter: brightness(1.15); }

/* Layout for intro section (photo right, text left) */
.intro-wrapper {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 1.2rem;
  margin-bottom: 2rem;
}

.intro-text {
  flex: 1 1 60%;
  min-width: 250px;
}

.intro-photo {
  flex: 1 1 30%;
  min-width: 180px;
  text-align: right;
}

.intro-photo img {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  border: 3px solid #1a2a52;
  box-shadow: 0 4px 14px rgba(0,0,0,.2);
  object-fit: cover;
}
</style>

---

<div class="intro-wrapper">
  <div class="intro-text">
    <h1 style="margin-bottom:0.5rem;">Giovanni Maglio</h1>
    <p style="margin-top:0; font-size:1.05rem; color:#1e293b;">
      Physics graduate from the University of Milan, with research interests in 
      <strong>theoretical and electroweak physics</strong>, 
      <strong>quantum field theory</strong>, and 
      <strong>mathematical structures of fundamental interactions</strong>.
      Passionate about connecting rigorous theory with computational tools and scientific communication.
    </p>
  </div>
  <div class="intro-photo">
    <img src="{{ site.baseurl }}/assets/img/avatar.jpg" alt="Giovanni Maglio portrait">
  </div>
</div>

---

## 👤 About & CV {#about}
[Open CV]({{ site.baseurl }}/about/){: .btn .btn--primary }

---

## 🔬 Research {#research}
[Explore Research]({{ site.baseurl }}/research/){: .btn .btn--info }

---

## 🧰 Projects {#projects}
[View Projects]({{ site.baseurl }}/projects/){: .btn .btn--success }

---

## 📚 Publications {#publications}

---

## ✉️ Contact {#contact}
- **Email:** <giovanni.maglio@studenti.unimi.it>
