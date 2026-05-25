---
layout: default
title: Experience
permalink: /experience/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* Hide injected H1 */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
  --ink:#2a3440;
}
body{ background:var(--bg) !important; font-family: "Segoe UI", sans-serif; color: var(--ink); margin: 0; padding: 0; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:20px auto;
  border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{ width:100%; height:260px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(28px,4vw,40px);
  font-weight:700; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* NAVIGATION BAR */
.nav-bar { position: sticky; top: 10px; z-index: 10000; margin: 0 auto 25px; max-width: 1150px; padding: 0 10px; }
.nav-inner { display: flex; align-items: center; justify-content: center; flex-wrap: wrap; gap: 15px; padding: 8px 20px; background: #ffffff; border-radius: 12px; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06); border: 1px solid var(--border); }
.nav-bar a, .dropdown-toggle { text-decoration: none; color: var(--primary-dark) !important; font-weight: 800; padding: 8px 16px; border-radius: 8px; transition: all 0.2s; display: inline-flex; align-items: center; gap: 8px; font-size: 16px; cursor: pointer; border: none; background: none; white-space: nowrap; }
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background: #e3f2fd; color: var(--primary) !important; }

/* DROPDOWN */
.dropdown { position: relative; }
.dropdown-content { display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%); min-width: 180px; z-index: 9999; padding-top: 10px; }
.dropdown:hover .dropdown-content { display: block; }
.dropdown-menu-box { background: #fff; border-radius: 10px; border: 1px solid var(--border); box-shadow: 0 12px 30px rgba(0,0,0,0.12); overflow: hidden; padding: 5px; }
.dropdown-menu-box a { display: block; padding: 10px 15px; font-size: 15px; color: var(--ink) !important; font-weight: 700; text-align: left; text-decoration: none; }

/* CONTENT STYLING */
.dev-highlight-full {
  max-width: 1150px; margin: 20px auto; padding: 25px;
  background: linear-gradient(135deg, #ffffff 0%, #e3f2fd 100%);
  border-radius: 16px; border: 1px solid var(--primary);
  box-shadow: 0 10px 25px rgba(30, 136, 229, 0.08);
}
.split-layout { display: grid; grid-template-columns: 1fr 380px; gap: 30px; max-width: 1150px; margin: 0 auto 30px; padding: 0 15px; }
.experience-side { width: 100%; }
.timeline-v { position: relative; padding-left: 30px; border-left: 3px solid var(--border); }
.timeline-v-item { position: relative; margin-bottom: 25px; }
.timeline-v-item::before { content: ''; position: absolute; left: -39px; top: 5px; width: 15px; height: 15px; background: white; border: 3px solid var(--primary); border-radius: 50%; z-index: 2; }
.v-content { background: white; padding: 20px; border-radius: 12px; border: 1px solid var(--border); }
.v-content h3 { margin: 0; font-size: 19px; color: var(--primary-dark); }
.v-content b { font-size: 15px; color: #333; display: block; margin-top: 6px; line-height: 1.5; }
.inst-link { text-decoration: none !important; color: inherit !important; }

/* TOOLKIT STYLING */
.instrumentation-side { width: 100%; }
.sticky-right { position: sticky; top: 20px; }
.inst-category { margin-bottom: 20px; } 
.inst-category h4 { font-size: 12px; text-transform: uppercase; color: #666; letter-spacing: 1.5px; margin-bottom: 10px; border-bottom: 2px solid var(--border); padding-bottom: 5px; }
.skill-grid-compact { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; }
.skill-badge-v { 
  background: white; border: 1px solid var(--border); padding: 12px 10px; border-radius: 10px; text-align: center; 
  display: flex; flex-direction: column; justify-content: center; min-height: 70px; box-shadow: 0 2px 5px rgba(0,0,0,0.03); 
  text-decoration: none; color: inherit; transition: 0.2s;
}
.skill-badge-v:hover { border-color: var(--primary); background: #fdfdfd; }
.skill-badge-v b { font-size: 15px; display: block; color: var(--primary-dark); line-height: 1.2; margin-bottom: 4px; }
.skill-badge-v small { font-size: 12px; color: #555; font-weight: 500; }

.diode-icon { vertical-align: middle; margin-right: 8px; width: 24px; height: 24px; }
.profile-links { max-width: 1150px; margin: 40px auto; text-align: center; padding: 20px; border-top: 1px solid var(--border); }

@media (max-width: 900px) {
  .split-layout { grid-template-columns: 1fr; }
  .sticky-right { position: static; }
}
</style>

<div class="hero-header">
  <img src="/assets/header2.jpg" alt="Experience header">
  <div class="hero-title">Experience & Expertise</div>
</div>

<nav class="nav-bar">
  <div class="nav-inner">
    <a href="/">🏠 Home</a>
    <a href="/experience/">👨‍🔬 Experience</a>
    <a href="/impact/">📈 Impact</a>
    <div class="dropdown">
      <span class="dropdown-toggle">📚 Publications ▾</span>
      <div class="dropdown-content">
        <div class="dropdown-menu-box">
          <a href="/patents/">📜 Patents</a>
          <a href="/Book_Chapters/">📖 Chapters</a>
          <a href="/publications/">📝 Articles</a>
        </div>
      </div>
    </div>
    <a href="/contact/">📬 Contact</a>
  </div>
</nav>

<div class="dev-highlight-full">
  <h2 style="margin-top:0; margin-bottom: 8px; color:var(--primary-dark); font-size: 24px;">🔬 Instrumental Development</h2>
  <p style="font-size: 16px; line-height: 1.6; color: #333; margin-bottom: 0;">
    <b>Modified Optical Microscopy:</b> I actively develop and modify scientific setups to meet specific research needs. 
    I successfully integrated a <b>high-resolution spectrometer</b> into an optical microscope system, allowing for 
    precise, non-destructive <b>2D material thickness determination</b> through localized spectral analysis.
  </p>
</div>

<div class="split-layout">
  <div class="experience-side">
    <h2 style="color: var(--primary-dark); margin-bottom: 20px;">👨‍🔬 Experience Tree</h2>
    <div class="timeline-v">
      <div class="timeline-v-item"><div class="v-content">
        <h3>Post-Doctoral Fellow</h3>
        <b><a href="https://nanotech.usal.es/" target="_blank" class="inst-link">🇪🇸 Department of Physics, University of Salamanca, Spain (2024–Present)</a></b>
      </div></div>
      <div class="timeline-v-item"><div class="v-content">
        <h3>Post-Doctoral Fellow</h3>
        <b><a href="https://en.sce.ac.il/" target="_blank" class="inst-link">🇮🇱 Shamoon College of Engineering, Beer Sheva, Israel (2022–2024)</a></b>
      </div></div>
      <div class="timeline-v-item"><div class="v-content">
        <h3>Research Associate</h3>
        <b><a href="https://inst.ac.in/" target="_blank" class="inst-link">🇮🇳 Institute of Nano Science and Technology, Mohali, India (2021–2022)</a></b>
      </div></div>
      <div class="timeline-v-item"><div class="v-content">
        <h3>PhD Scholar (Nanotechnology)</h3>
        <b><a href="https://inst.ac.in/" target="_blank" class="inst-link">🇮🇳 Institute of Nano Science and Technology, Mohali, India (2016–2021)</a></b>
      </div></div>
    </div>

    <div style="background: white; padding: 20px; border-radius: 12px; border: 1px solid var(--border); margin-bottom: 20px;">
      <h3 style="margin-top:0; color:var(--primary-dark); display: flex; align-items: center; font-size: 19px;">
        <svg class="diode-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M4 19H20M5 5V18" stroke="#1e88e5" stroke-width="2" stroke-linecap="round"/>
          <path d="M6 17C9 17 14 15 18 6" stroke="#f44336" stroke-width="2" stroke-linecap="round"/>
          <path d="M14 12L20 12M17 9V15M20 9V15" stroke="#1e88e5" stroke-width="1.5"/>
        </svg>
        Electrical & Field Emission
      </h3>
      <p style="font-size: 15px; color: #444; margin-bottom: 0;">Characterization of field emission properties including I-V measurements in diode configuration for cold cathode applications.</p>
    </div>

    <div style="background: #fffdf5; padding: 20px; border-radius: 12px; border: 1px solid #ffe082;">
      <h3 style="margin-top:0; color:#d97706; display: flex; align-items: center; font-size: 19px;">
        <i class="fas fa-microchip" style="margin-right:10px;"></i> Cleanroom Expertise (2D Materials)
      </h3>
      <p style="font-size: 15px; color: #444; margin-bottom: 0;">Extensive experience in <b>cleanroom fabrication processes</b>, including photolithography, E-beam lithography, and thin-film deposition, specifically optimized for high-quality 2D material heterostructure device assembly.</p>
    </div>
  </div>

  <div class="instrumentation-side">
    <div class="sticky-right">
      <h2 style="color: var(--primary-dark); margin-bottom: 20px;">🛠️ Technical Toolkit</h2>
      
      <div class="inst-category">
        <h4>🔥 Thermal Analysis</h4>
        <div class="skill-grid-compact">
          <a href="https://en.wikipedia.org/wiki/Differential_scanning_calorimetry" class="skill-badge-v"><b>DSC</b><small>Phase Transitions</small></a>
          <a href="https://en.wikipedia.org/wiki/Thermogravimetric_analysis" class="skill-badge-v"><b>TGA</b><small>Weight Change</small></a>
          <a href="https://en.wikipedia.org/wiki/Furnace" class="skill-badge-v" style="grid-column: span 2;"><b>Furnaces</b><small>Up to 1600°C</small></a>
        </div>
      </div>
      
      <div class="inst-category">
        <h4>⚛️ Structural & Morphological</h4>
        <div class="skill-grid-compact">
          <a href="https://en.wikipedia.org/wiki/X-ray_crystallography" class="skill-badge-v"><b>XRD</b><small>High-Temp XRD</small></a>
          <a href="https://en.wikipedia.org/wiki/Scanning_electron_microscope" class="skill-badge-v"><b>SEM</b><small>JSM-IT 300</small></a>
          <a href="https://en.wikipedia.org/wiki/Atomic_force_microscopy" class="skill-badge-v"><b>AFM</b><small>Surface Topology</small></a>
          <a href="https://en.wikipedia.org/wiki/Brunauer–Emmett–Teller_theory" class="skill-badge-v"><b>BET</b><small>Surface Area</small></a>
        </div>
      </div>
      
      <div class="inst-category">
        <h4>🌈 Spectroscopy & Electro-chem</h4>
        <div class="skill-grid-compact">
          <a href="https://en.wikipedia.org/wiki/Raman_spectroscopy" class="skill-badge-v"><b>Raman</b><small>Confocal/Micro</small></a>
          <a href="https://en.wikipedia.org/wiki/Potentiostat" class="skill-badge-v"><b>Metrohm / PalmSens</b><small>Workstations</small></a>
          <a href="https://en.wikipedia.org/wiki/UV%E2%80%93vis_spectroscopy" class="skill-badge-v" style="grid-column: span 2;"><b>UV-Vis-NIR</b><small>IR / DRS Mode</small></a>
        </div>
      </div>
      
    </div>
  </div>
</div>

<div class="profile-links">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar">
  </a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID">
  </a>
</div>
