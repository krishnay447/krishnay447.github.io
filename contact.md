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
  --primary:#1e88e5;        /* blue */
  --primary-dark:#1565c0;   /* darker blue */
  --bg:#f7f9fc;             /* soft background */
  --border:#dce3ef;         /* light divider */
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

/* ===================== CONTACT & MAP LAYOUT ===================== */
.contact-container {
  display: flex;
  align-items: flex-start;
  gap: 25px; 
  margin: 20px 0;
  flex-wrap: wrap;
}

.contact-photo {
  width: 160px; 
  height: auto;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  border: 3px solid #fff;
}

.map-section-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 30px;
  background: #1a1a1a; 
  padding: 25px;
  border-radius: 15px;
  color: white;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

.map-box {
  flex: 2;
  min-width: 300px;
  position: relative;
}

.locations-list {
  flex: 1;
  min-width: 250px;
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.map-point {
  width: 12px;
  height: 12px;
  background: #ff4757;
  border-radius: 50%;
  position: absolute;
  cursor: pointer;
  box-shadow: 0 0 12px #ff4757;
  transition: transform 0.3s;
  z-index: 10;
}

.map-point:hover {
  transform: scale(1.8);
  background: #fff;
}

.loc-card {
  background: #2d2d2d;
  padding: 12px;
  border-radius: 8px;
  text-decoration: none;
  color: white !important;
  font-size: 14px;
  border-left: 4px solid var(--primary);
  transition: 0.3s;
}

.loc-card:hover {
  background: #3d3d3d;
  transform: translateX(5px);
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
    <span class="dropdown-content" role="menu" aria-label="Publications submenu">
      <a href="/patents/">1. Patents</a>
      <a href="/Book_Chapters/">2. Book Chapters</a>
      <a href="/publications/">3. Peer‑Reviewed Journal Articles</a>
    </span>
  </span> |
  <a href="/contact/">📬 Contact</a>
</nav>

---

# 📬 Get in Touch

| Channel | Interactive Link (Click to Action) |
| :--- | :--- |
| 📧 **Primary Email** | <a href="mailto:krish91phy@usal.es"><img src="https://img.shields.io/badge/Email-krish91phy@usal.es-007ACC?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a> |
| 📧 **Personal Email** | <a href="mailto:Krishnay447@gmail.com"><img src="https://img.shields.io/badge/Email-Krishnay447@gmail.com-007ACC?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a> |
| 📱 **WhatsApp** | <a href="https://wa.me/34603917596"><img src="https://img.shields.io/badge/WhatsApp-%2B34%20603%20917%20596-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a> |

---

### 📍 Current Location & Research Journey

<div class="contact-container">
  <img src="/assets/profile.jpg" alt="Krishna Kumar Yadav" class="contact-photo">
  <div class="address-details">
    <p><strong>Department of Physics</strong><br>
    Edificio Multiusos I+D+i<br>
    Universidad de Salamanca<br>
    C. Espejo, 2, 37007 Salamanca, Spain 🇪🇸</p>
  </div>
</div>

<div class="map-section-container">
  
  <div class="map-box">
    <h3 style="color:white; margin-top:0;">🌍 Global Research Footprint</h3>
    <div style="position: relative; background: #222; border-radius: 10px; overflow: hidden;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/World_map_-_low_resolution.svg" 
           style="width:100%; filter: invert(1) opacity(0.3); display: block;" alt="World Map">
      
      <a href="/assets/gorakhpur.jpg" target="_blank" class="map-point" style="top: 48%; left: 75%;" title="Home: Gorakhpur"></a>
      
      <a href="https://www.inst.ac.in/" target="_blank" class="map-point" style="top: 42%; left: 73%;" title="PhD: INST Mohali"></a>
      
      <a href="https://en.sce.ac.il/" target="_blank" class="map-point" style="top: 48%; left: 63%;" title="PostDoc 1: SCE Beer Sheva"></a>
      
      <a href="https://www.usal.es/en" target="_blank" class="map-point" style="top: 42%; left: 47%;" title="Current: Univ. of Salamanca"></a>
    </div>
    <p style="font-size: 12px; color: #888; margin-top: 10px;">* Click dots to view photos or institutional links.</p>
  </div>

  <div class="locations-list">
    <h4 style="margin-top:0; color: var(--primary);">📍 Timeline</h4>
    
    <a href="/assets/gorakhpur.jpg" target="_blank" class="loc-card">
      <strong>🏠 Gorakhpur</strong><br>Home City & Roots
    </a>

    <a href="https://www.inst.ac.in/" target="_blank" class="loc-card">
      <strong>🎓 INST Mohali</strong><br>PhD Institute (India)
    </a>

    <a href="https://en.sce.ac.il/" target="_blank" class="loc-card">
      <strong>🇮🇱 SCE Beer Sheva</strong><br>1st PostDoc (Israel)
    </a>

    <a href="https://www.usal.es/en" target="_blank" class="loc-card">
      <strong>🇪🇸 Univ. of Salamanca</strong><br>Current PostDoc (Spain)
    </a>
  </div>
</div>

---

<div align="right">
  <a href="https://github.com/krishnay447">
    <img src="https://komarev.com/ghpvc/?username=krishnay447&color=007ACC&style=for-the-badge&label=VISITORS" alt="Visitor Count">
  </a>
</div>
