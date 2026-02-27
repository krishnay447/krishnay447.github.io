---
layout: default
title: Contact
permalink: /contact/
---

<style>
.markdown-body > h1:first-child { display: none !important; }
:root{ --primary:#1e88e5; --bg:#f7f9fc; --border:#dce3ef; }
body{ background:var(--bg) !important; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 15px;
  border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{ width:100%; height:240px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-family:"Segoe UI", sans-serif; font-size:36px; font-weight:700; color:#fff;
  text-shadow:0 3px 10px rgba(0,0,0,0.55); background:linear-gradient(0deg, rgba(0,0,0,0.4), rgba(0,0,0,0.1));
}

/* NAVIGATION */
.nav-bar{ text-align:center; padding:12px 0; background:#fff; border-bottom:2px solid var(--border); margin-bottom:20px; }
.nav-bar a{ color:var(--primary); text-decoration:none; font-weight:600; padding:0 10px; }

/* DROPDOWN */
.dropdown{ position:relative; display:inline-block; }
.dropdown-toggle{ cursor:pointer; font-weight:700; color:var(--primary); }
.dropdown-content{
  display:none; position:absolute; top:100%; left:0; background:#fff; min-width:200px;
  border:1px solid var(--border); border-radius:8px; box-shadow:0 8px 18px rgba(0,0,0,0.12); z-index:9999;
}
.dropdown:hover .dropdown-content{ display:block; }
.dropdown-content a{ display:block; padding:10px 16px; font-size:14px; color:var(--primary); text-decoration:none; border-bottom:1px solid #eee; text-align:left; }

/* SPLIT LAYOUT */
.contact-split-wrapper { display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 30px; }
.contact-left { flex: 1; min-width: 280px; background: #fff; padding: 20px; border-radius: 12px; border: 1px solid var(--border); box-shadow: 0 4px 12px rgba(0,0,0,0.05); }
.map-right { flex: 2.3; min-width: 350px; background: #1a1a1a; padding: 20px; border-radius: 12px; color: white; }

/* CONTACT BADGES - FIXED SIZING */
.badge-stack { display: flex; flex-direction: column; gap: 10px; margin-top: 15px; align-items: flex-start; }
.badge-stack a img { 
  height: 28px; 
  width: 240px; /* Forces all badges to be the same width */
  object-fit: fill; 
  border-radius: 4px;
}

/* MAP PINS */
.map-container { position: relative; background: #222; border-radius: 10px; overflow: hidden; border: 1px solid #444; }
.map-pin { width: 24px; height: 24px; position: absolute; cursor: pointer; z-index: 10; filter: drop-shadow(0 2px 4px rgba(0,0,0,0.5)); transition: transform 0.2s; }
.map-pin:hover { transform: scale(1.3) translateY(-2px); }

/* Pulse for Salamanca */
.pin-active { animation: pulse 2.5s infinite; fill: #ffd700 !important; }
@keyframes pulse {
  0% { filter: drop-shadow(0 0 0px #ffd700); }
  50% { filter: drop-shadow(0 0 12px #ffd700); }
  100% { filter: drop-shadow(0 0 0px #ffd700); }
}

.profile-card { display: flex; align-items: center; gap: 15px; margin-bottom: 15px; border-bottom: 1px solid var(--border); padding-bottom: 15px; }
.profile-img { width: 65px; height: 65px; border-radius: 50%; border: 2px solid var(--primary); }
</style>

<div class="hero-header">
  <img src="/assets/header1.jpg" alt="Header Banner">
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<nav class="nav-bar">
  <a href="/">🏠 Home</a> | 
  <a href="/experience/">👨‍🔬 Experience</a> | 
  <a href="/instrumentation/">🔬 Instrumentation</a> | 
  <a href="/impact/">📈 Impact</a> | 
  <span class="dropdown">
    <a class="dropdown-toggle">📚 Publications ▾</a>
    <div class="dropdown-content">
      <a href="/patents/">1. Patents</a>
      <a href="/Book_Chapters/">2. Book Chapters</a>
      <a href="/publications/">3. Articles</a>
    </div>
  </span> | 
  <a href="/contact/">📬 Contact</a>
</nav>

<div class="contact-split-wrapper">
  
  <div class="contact-left">
    <div class="profile-card">
      <img src="/assets/profile.jpg" alt="Krishna Profile" class="profile-img">
      <div style="font-size: 14px;">
        <strong>Krishna Kumar Yadav</strong><br>
        <span style="color: #666;">Researcher</span>
      </div>
    </div>

    <h4 style="margin-top: 0; color: var(--primary);">📬 Get in Touch</h4>
    <div class="badge-stack">
      <a href="mailto:krish91phy@usal.es"><img src="https://img.shields.io/badge/Email-krish91phy@usal.es-007ACC?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
      <a href="mailto:Krishnay447@gmail.com"><img src="https://img.shields.io/badge/Email-Krishnay447@gmail.com-007ACC?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
      <a href="https://wa.me/34603917596"><img src="https://img.shields.io/badge/WhatsApp-%2B34_603_917_596-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
    </div>

    <p style="font-size: 13px; color: #444; margin-top: 20px;">
      <strong>📍 Office:</strong><br>
      Dept. of Physics, Edificio Multiusos I+D+i,<br>
      Univ. de Salamanca, Spain 🇪🇸
    </p>
  </div>

  <div class="map-right">
    <h3 style="margin-top: 0; color: white; font-size: 1.2em;">🌍 Research Journey</h3>
    <div class="map-container">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/World_map_blank_without_borders.svg" 
           style="width: 100%; filter: invert(1) opacity(0.4); display: block;" alt="World Map">
      
      <a href="https://gorakhpur.nic.in/" target="_blank" title="Gorakhpur, India">
        <svg class="map-pin" style="top: 31.5%; left: 68.5%;" viewBox="0 0 24 24" fill="#FF9933">
          <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
        </svg>
      </a>

      <a href="https://www.inst.ac.in/" target="_blank" title="INST Mohali, India">
        <svg class="map-pin" style="top: 30.4%; left: 66.5%;" viewBox="0 0 24 24" fill="#FFFFFF">
          <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
        </svg>
      </a>

      <a href="https://en.sce.ac.il/" target="_blank" title="SCE, Israel">
        <svg class="map-pin" style="top: 24.5%; left: 55.45%;" viewBox="0 0 24 24" fill="#2E8B57">
          <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
        </svg>
      </a>

      <a href="https://lbt.usal.es/" target="_blank" title="LBT, Univ. de Salamanca">
        <svg class="map-pin pin-active" style="top: 21.3%; left: 44%;" viewBox="0 0 24 24">
          <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
        </svg>
      </a>
    </div>

    <div style="display: flex; justify-content: space-around; margin-top: 15px; font-size: 12px;">
      <span>🏠 Gorakhpur</span> ➔ <span>🎓 Mohali</span> ➔ <span>🇮🇱 Israel</span> ➔ <span>🇪🇸 Salamanca</span>
    </div>
  </div>
</div>

<div align="center">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
  <a href="https://github.com/krishnay447"><img src="https://komarev.com/ghpvc/?username=krishnay447&color=007ACC&style=for-the-badge&label=VISITORS" alt="Visitors"></a>
</div>
