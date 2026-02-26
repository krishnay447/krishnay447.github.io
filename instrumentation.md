---
layout: default
title: Instrumentation
permalink: /instrumentation/
---

<!-- ===================== PAGE THEME (matches Home/Experience) ===================== -->
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
  height:260px;             /* adjust height if you prefer */
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

<!-- ===================== HERO HEADER (uses header3.jpg) ===================== -->
<div class="hero-header">
  <img src="/assets/header3.jpg" alt="Header banner">
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<!-- ===================== NAVIGATION (same style site‑wide) ===================== -->
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

# 🛠️ Instrumentation & Development

My expertise extends beyond standard characterization; I actively develop and modify scientific setups to meet specific research needs.

### 🔬 Instrumental Development
* **Modified Optical Microscopy:** Successfully integrated a **spectrometer** into an optical microscope system. This custom setup allows for precise, non-destructive **2D material thickness** determination through localized spectral analysis.

---

### ⚙️ Characterization Tools

* **Thermal Analysis:**
    * **DSC:** **Differential Scanning Calorimetry** to study heat flow and phase transitions. 
    * **Publication Link:** Detailed DSC analysis of thermal phase transitions can be found in my work here: https://doi.org/10.1002/wer.1307.
    * **TGA:** **Thermogravimetric Analysis** (TGA) for measuring weight changes relative to temperature.
    * **Furnaces:** Expert use of High-Temperature Furnaces (up to 1200°C) for material synthesis and annealing.

* **Electrical & Field Emission:**
    * **Field Emission:** Characterization of field emission properties including **I-V measurements in diode configuration** for cold cathode applications.
    * **Publication Link:** https://doi.org/10.1016/j.apsusc.2020.146652.
    * **Workstations:** Professional use of **Metrohm** and **PalmSens** workstations for electrochemical sensing and cyclic voltammetry.

* **Structural & Morphological:**
    * **XRD:** Expert in **X-Ray Diffraction**, including specialized **High-Temperature XRD**.
    * **Microscopy:** SEM (JEOL JSM-IT 300) and AFM for high-resolution surface topology.
    * **Surface Area:** Measurement and analysis using **QuantaChrome** (BET analysis).

* **Spectroscopy:**
    * **Raman:** Expert in Confocal and micro Raman Spectroscopy for vibrational mode analysis.

---

<a href="/">🔙 Back to Home Page</a>
