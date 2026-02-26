<!-- ===================== GLOBAL UI THEME ===================== -->
<style>
/* Hide GitHub repo title ("krishnay447") that Pages may inject */
.markdown-body > h1:first-child { display: none !important; }

/* --- GLOBAL COLORS --- */
:root{
  --primary:#1e88e5;         /* blue */
  --primary-dark:#1565c0;    /* darker blue */
  --bg:#f7f9fc;              /* soft background */
  --border:#dce3ef;          /* light divider */
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
  height:260px;              /* adjust if you want taller/shorter */
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

/* show menu directly under trigger (no hover gap) */
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
</style>

<!-- ===================== HERO HEADER ===================== -->
<div class="hero-header">
  <img src="/assets/header.jpg" alt="Header banner" />
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<!-- ===================== NAVIGATION (ALL LINKS CLICKABLE) ===================== -->
<div class="nav-bar" role="navigation" aria-label="Primary">
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
</div>

---

# Dr. Krishna Kumar Yadav 
### Post-Doctoral Fellow | University of Salamanca, Spain 🇪🇸 

---

## Welcome
Welcome to my professional academic website. I am a physicist specializing in Nanotechnology, Energy, Device Fabrication, and Advanced Material Synthesis, with a particular focus on Metal hexaboride. I am a proactive learner, constantly integrating modern tools like **Artificial Intelligence** to accelerate scientific discovery and automate data analysis.

---

### 📸 Research & Lab Gallery

<div align="center">
<table style="border: none; border-collapse: collapse;">
<tr>
<td style="padding: 10px; border: none;"><img src="photo1.jpg" height="320" style="border-radius: 10px;" alt="Research Image 1"></td>
<td style="padding: 10px; border: none;"><img src="photo2.jpg" height="320" style="border-radius: 10px;" alt="Research Image 2"></td>
</tr>
<tr>
<td style="padding: 10px; border: none;"><img src="photo3.jpg" height="320" style="border-radius: 10px;" alt="Research Image 3"></td>
<td style="padding: 10px; border: none;"><img src="photo4.jpg" height="320" style="border-radius: 10px;" alt="Research Image 4"></td>
</tr>
</table>
</div>

---

### 📍 Current Focus
Currently advancing the characterization of two‑dimensional (2D) transition metal dichalcogenides (TMDs), establishing a scalable platform for Schottky barrier quantification using KPFM, and fabricating Schottky‑junction solar cells at the **University of Salamanca**, Spain.

---
📧 **Contact:** krish91phy@usal.es | <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ&hl=en" target="_blank" rel="noopener">🎓 Google Scholar</a>
