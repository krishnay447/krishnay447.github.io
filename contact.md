---
layout: default
title: Contact
permalink: /contact/
---

<style>
/* Reset and Global */
.markdown-body > h1:first-child { display: none !important; }
:root { --primary: #1e88e5; --bg: #f7f9fc; --border: #dce3ef; }
body { background: var(--bg) !important; }

/* Hero and Nav */
.hero-header { position: relative; max-width: 1150px; margin: 0 auto 10px; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
.hero-header img { width: 100%; height: 200px; object-fit: cover; display: block; }
.hero-title { position: absolute; inset: 0; display: flex; align-items: center; justify-content: center; font-weight: 700; color: #fff; text-shadow: 0 2px 8px rgba(0,0,0,0.5); background: rgba(0,0,0,0.3); font-size: 32px; }
.nav-bar { text-align: center; padding: 10px 0; background: #fff; border-bottom: 2px solid var(--border); margin-bottom: 15px; }
.nav-bar a { color: var(--primary); text-decoration: none; font-weight: 600; padding: 0 10px; }

/* COMPACT LAYOUT */
.compact-container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 15px;
  background: white;
  padding: 12px 20px;
  border-radius: 10px;
  border: 1px solid var(--border);
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

.profile-section { display: flex; align-items: center; gap: 12px; }
.profile-img { width: 45px; height: 45px; border-radius: 50%; border: 2px solid var(--primary); }
.address-brief { font-size: 13px; line-height: 1.2; }

.contact-badges { display: flex; gap: 8px; }
.contact-badges img { height: 22px; }

.journey-map-box { 
  flex: 1; 
  min-width: 300px; 
  background: #222; 
  border-radius: 8px; 
  padding: 8px; 
  position: relative; 
  overflow: hidden;
  height: 120px;
}
.map-point { width: 8px; height: 8px; background: #ff4757; border-radius: 50%; position: absolute; box-shadow: 0 0 8px #ff4757; cursor: pointer; }
</style>

<div class="hero-header">
  <img src="/assets/header1.jpg" alt="Banner">
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<nav class="nav-bar">
  <a href="/">🏠 Home</a> | <a href="/experience/">👨‍🔬 Experience</a> | <a href="/impact/">📈 Impact</a> | <a href="/contact/">📬 Contact</a>
</nav>

<div class="compact-container">
  <div class="profile-section">
    <img src="/assets/profile.jpg" class="profile-img" alt="Krishna">
    <div class="address-brief">
      <strong>Dept. of Physics</strong><br>
      Univ. de Salamanca, Spain 🇪🇸
    </div>
  </div>

  <div class="journey-map-box">
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/World_map_blank_without_borders.svg" 
         style="width: 100%; height: 100%; filter: invert(1) opacity(0.4); object-fit: contain;" alt="World Map">
    <a href="/assets/gorakhpur.jpg" class="map-point" style="top: 48%; left: 74%;" title="Gorakhpur"></a>
    <a href="#" class="map-point" style="top: 42%; left: 72%;" title="INST Mohali"></a>
    <a href="#" class="map-point" style="top: 46%; left: 62%;" title="Israel"></a>
    <a href="#" class="map-point" style="top: 40%; left: 47%;" title="Salamanca"></a>
  </div>

  <div class="contact-badges">
    <a href="mailto:krish91phy@usal.es"><img src="https://img.shields.io/badge/Email-Primary-007ACC?style=flat-square&logo=gmail" alt="Email"></a>
    <a href="https://wa.me/34603917596"><img src="https://img.shields.io/badge/WhatsApp-Chat-25D366?style=flat-square&logo=whatsapp" alt="WhatsApp"></a>
    <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ"><img src="https://img.shields.io/badge/Scholar-Stats-red?style=flat-square&logo=google-scholar" alt="Scholar"></a>
  </div>
</div>

<div style="text-align: center; margin-top: 15px; font-size: 13px;">
  <strong>Journey:</strong> 🏠 Gorakhpur ➔ 🎓 INST Mohali ➔ 🇮🇱 SCE Israel ➔ 🇪🇸 USAL Salamanca
</div>

<div align="right" style="margin-top: 20px;">
  <a href="https://github.com/krishnay447">
    <img src="https://komarev.com/ghpvc/?username=krishnay447&color=007ACC&style=for-the-badge&label=VISITORS" alt="Visitor Count">
  </a>
</div>
