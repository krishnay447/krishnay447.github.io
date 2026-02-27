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

/* ===================== CONTACT PAGE SPECIFIC LAYOUT ===================== */
.contact-container {
  display: flex;
  align-items: flex-start;
  gap: 25px; 
  margin: 20px 0;
  flex-wrap: wrap; /* Allows stacking on mobile */
}

.contact-photo {
  width: 160px; 
  height: auto;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  border: 3px solid #fff;
}

.address-details {
  flex: 1;
  min-width: 250px;
}

.contact-table td, .contact-table th { padding: 8px 10px; }
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

Click the buttons below to reach me or view my professional profiles.

| Channel | Interactive Link (Click to Action) |
| :--- | :--- |
| 📧 **Primary Email** | <a href="mailto:krish91phy@usal.es"><img src="https://img.shields.io/badge/Email-krish91phy@usal.es-007ACC?style=for-the-badge&logo=gmail&logoColor=white" alt="Email: krish91phy@usal.es"></a> |
| 📧 **Personal Email** | <a href="mailto:Krishnay447@gmail.com"><img src="https://img.shields.io/badge/Email-Krishnay447@gmail.com-007ACC?style=for-the-badge&logo=gmail&logoColor=white" alt="Email: Krishnay447@gmail.com"></a> |
| 📱 **Mobile / WhatsApp** | <a href="https://wa.me/34603917596"><img src="https://img.shields.io/badge/WhatsApp-%2B34%20603%20917%20596-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="+34 603 917 596 on WhatsApp"></a> |
| 🎓 **Google Scholar** | <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-View_Profile-red?style=for-the-badge&logo=google-scholar&logoColor=white" alt="Google Scholar Profile"></a> |
| 🆔 **ORCID iD** | <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-0000--0002--9063--7851-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID: 0000-0002-9063-7851"></a> |

---

### 📍 Location

<div class="contact-container">
  <img src="/assets/profile.jpg" alt="Krishna Kumar Yadav" class="contact-photo">

  <div class="address-details">
    <p><strong>Department of Physics</strong><br>
    Edificio Multiusos I+D+i<br>
    Universidad de Salamanca<br>
    C. Espejo, 2, 37007 Salamanca, Spain 🇪🇸</p>
    
   
</div>

---

<div align="right">
  <a href="https://github.com/krishnay447">
    <img src="https://komarev.com/ghpvc/?username=krishnay447&color=007ACC&style=for-the-badge&label=VISITORS" alt="Visitor Count">
  </a>
</div>

---
