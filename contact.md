---
layout: default
title: Contact
permalink: /contact/
---

<style>
/* Hide any injected first H1 from the theme */
.markdown-body > h1:first-child { display: none !important; }

/* --- GLOBAL COLORS --- */
:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body{ background:var(--bg) !important; }

/* ===================== HERO BANNER ===================== */
.hero-header{
  position:relative;
  width:100%;
  max-width:1150px;
  margin:0 auto 20px;
  border-radius:14px;
  overflow:hidden;
  box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{
  width:100%;
  height:260px;
  object-fit:cover;
  display:block;
}
.hero-title{
  position:absolute; inset:0;
  display:flex; align-items:center; justify-content:center;
  font-family:"Segoe UI", Roboto, Arial, sans-serif;
  font-size:clamp(28px,4vw,40px);
  font-weight:700; color:#fff;
  text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* ===================== NAVIGATION BAR ===================== */
.nav-bar{
  text-align:center;
  padding:12px 0;
  background:#fff;
  border-bottom:2px solid var(--border);
  box-shadow:0 2px 6px rgba(0,0,0,0.05);
  font-family:"Segoe UI", sans-serif;
  font-size:16px;
}
.nav-bar a{
  color:var(--primary);
  text-decoration:none;
  font-weight:600;
  padding:0 8px;
}
.nav-bar a:hover{ color:var(--primary-dark); text-decoration:underline; }

/* ===================== DROPDOWN ===================== */
.dropdown{ position:relative; display:inline-block; }
.dropdown > a.dropdown-toggle{ cursor:pointer; font-weight:700; color:var(--primary); }

.dropdown-content{
  display:none; position:absolute; top:100%; left:0;
  background:#fff; min-width:230px;
  border:1px solid var(--border); border-radius:8px;
  box-shadow:0 8px 18px rgba(0,0,0,0.12);
  z-index:9999; text-align:left;
}
.dropdown:hover .dropdown-content{ display:block; }
.dropdown-content a{
  display:block; padding:10px 16px; font-size:14px;
  color:var(--primary); text-decoration:none; border-bottom:1px solid #eee; white-space:nowrap;
}
.dropdown-content a:last-child{ border-bottom:none; }
.dropdown-content a:hover{ background:#eef6ff; color:var(--primary-dark); }

/* Prevent GitHub Pages wrapper from clipping dropdown */
.markdown-body{ overflow:visible !important; }

/* ===================== MAP & CONTACT STYLES ===================== */
.map-section-container {
  background: #1a1a1a; 
  padding: 15px;
  border-radius: 12px;
  color: white;
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.map-point {
  width: 10px;
  height: 10px;
  background: #ff4757;
  border-radius: 50%;
  position: absolute;
  cursor: pointer;
  box-shadow: 0 0 10px #ff4757;
  transition: transform 0.3s;
  z-index: 10;
}

.map-point:hover {
  transform: scale(2);
  background: #fff;
}

.loc-card {
  background: #2d2d2d;
  padding: 8px 12px;
  border-radius: 6px;
  text-decoration: none;
  color: white !important;
  font-size: 13px;
  border-left: 3px solid var(--primary);
  display: block;
  transition: 0.2s;
}

.loc-card:hover {
  background: #3d3d3d;
  transform: translateX(3px);
}

.contact-photo {
  width: 90px; 
  height: auto;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
  border: 2px solid #fff;
}
</style>

<div class="hero-header">
  <img src="/assets/header1.jpg" alt="Header banner">
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<nav class="nav-bar" role="navigation" aria-label="Primary">
  <a href="/">🏠 Home</a> |
  <a href="/experience/">👨‍🔬 Experience</a> |
  <a href="/instrumentation/">🔬 Instrumentation</a> |
  <a href="/impact/">📈 Impact</a> |
  <span class="dropdown">
    <a class="dropdown-toggle">📚 Publications ▾</a>
    <span class="dropdown-content">
      <a href="/patents/">1. Patents</a>
      <a href="/Book_Chapters/">2. Book Chapters</a>
      <a href="/publications/">3. Peer‑Reviewed Journal Articles</a>
    </span>
  </span> |
  <a href="/contact/">📬 Contact</a>
</nav>

<hr>

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start; margin-top: 10px;">

  <div style="flex: 2; min-width: 350px;">
    <div class="map-section-container">
      <h3 style="color:white; margin-top:0; font-size: 1.1em; border-bottom: 1px solid #444; padding-bottom: 5px;">🌍 Research Journey</h3>
      
      <div style="position: relative; background: #222; border-radius: 8px; overflow: hidden; margin-top: 10px;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/World_map_-_low_resolution.svg" 
             style="width:100%; filter: invert(1) opacity(0.35); display: block;" alt="World Map">
        
        <a href="/assets/gorakhpur.jpg" target="_blank" class="map-point" style="top: 48%; left: 75%;" title="Home: Gorakhpur"></a>
        <a href="https://www.inst.ac.in/" target="_blank" class="map-point" style="top: 42%; left: 73%;" title="PhD: INST Mohali"></a>
        <a href="https://en.sce.ac.il/" target="_blank" class="map-point" style="top: 48%; left: 63%;" title="PostDoc 1: SCE Beer Sheva"></a>
        <a href="https://www.usal.es/en" target="_blank" class="map-point" style="top: 42%; left: 47%;" title="Current: Univ. of Salamanca"></a>
      </div>

      <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-top: 15px;">
        <a href="/assets/gorakhpur.jpg" target="_blank" class="loc-card"><strong>🏠 Gorakhpur</strong></a>
        <a href="https://www.inst.ac.in/" target="_blank" class="loc-card"><strong>🎓 INST Mohali</strong></a>
        <a href="https://en.sce.ac.il/" target="_blank" class="loc-card"><strong>🇮🇱 SCE Israel</strong></a>
        <a href="https://www.usal.es/en" target="_blank" class="loc-card"><strong>🇪🇸 Salamanca</strong></a>
      </div>
    </div>
  </div>

  <div style="flex: 1; min-width: 300px; padding: 10px; background: white; border-radius: 12px; border: 1px solid var(--border);">
    <h3 style="margin-top: 0; color: var(--primary);">📬 Get in Touch</h3>
    
    <div style="display: flex; flex-direction: column; gap: 10px;">
      <a href="mailto:krish91phy@usal.es" style="text-decoration:none;">
        <img src="https://img.shields.io/badge/Email-krish91phy@usal.es-007ACC?style=flat-square&logo=gmail&logoColor=white" style="width:100%; height: 28px;">
      </a>
      <a href="mailto:Krishnay447@gmail.com" style="text-decoration:none;">
        <img src="https://img.shields.io/badge/Email-Krishnay447@gmail.com-007ACC?style=flat-square&logo=gmail&logoColor=white" style="width:100%; height: 28px;">
      </a>
      <a href="https://wa.me/34603917596" style="text-decoration:none;">
        <img src="https://img.shields.io/badge/WhatsApp-%2B34_603_917_596-25D366?style=flat-square&logo=whatsapp&logoColor=white" style="width:100%; height: 28px;">
      </a>
    </div>

    <hr style="margin: 15px 0; border: 0; border-top: 1px solid var(--border);">

    <div style="display: flex; gap: 12px; align-items: center;">
      <img src="/assets/profile.jpg" alt="Krishna Kumar Yadav" class="contact-photo">
      <div style="font-size: 13px; color: #444; line-height: 1.4;">
        <strong>Dept. of Physics</strong><br>
        Edificio Multiusos I+D+i<br>
        Univ. de Salamanca<br>
        Salamanca, Spain 🇪🇸
      </div>
    </div>
  </div>

</div>

---

<div align="center" style="margin-top: 20px;">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
</div>
<div align="right" style="margin-top: 30px;">
  <a href="https://github.com/krishnay447">
    <img src="https://komarev.com/ghpvc/?username=krishnay447&color=007ACC&style=for-the-badge&label=VISITORS" alt="Visitor Count">
  </a>
