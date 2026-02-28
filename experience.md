---
layout: default
title: Experience
permalink: /experience/
---

<style>
/* Hide injected H1 */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body{ background:var(--bg) !important; font-family: "Segoe UI", sans-serif; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 20px;
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
.nav-bar {
  text-align: center; padding: 12px 0; background: #ffffff;
  border-bottom: 3px solid var(--border); box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  position: sticky; top: 0; z-index: 10000;
}
.nav-bar a, .dropdown-toggle {
  color: #444; text-decoration: none; font-weight: 600; padding: 10px 18px;
  margin: 0 4px; border-radius: 8px; transition: all 0.2s ease;
  display: inline-block; font-size: 15px; cursor: pointer; border: none; background: none;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background-color: #e3f2fd; color: var(--primary-dark); }

/* --- FIXED DROPDOWN SYSTEM --- */
.dropdown { position: relative; display: inline-block; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
  background: transparent; 
  min-width: 250px; z-index: 9999; 
  padding-top: 10px; /* Bridge gap */
}
/* Invisible bridge pseudo-element */
.dropdown-content::before {
  content: ""; position: absolute; top: -15px; left: 0; width: 100%; height: 15px; background: transparent;
}
.dropdown:hover .dropdown-content { display: block; }

/* Visible menu container */
.dropdown-menu-box {
  background: #ffffff; border-radius: 12px; border: 1px solid var(--border);
  box-shadow: 0 10px 30px rgba(0,0,0,0.15); overflow: hidden;
}
.dropdown-menu-box a { 
  display: block; padding: 12px 20px; border-bottom: 1px solid #f0f0f0; 
  text-align: left; font-size: 14px; color: #444; text-decoration: none; 
}
.dropdown-menu-box a:last-child { border-bottom: none; }
.dropdown-menu-box a:hover { background: #f8fbff; color: var(--primary); }

/* CONTENT STYLING */
.dev-highlight-full {
  max-width: 1150px; margin: 20px auto; padding: 15px 25px;
  background: linear-gradient(135deg, #ffffff 0%, #e3f2fd 100%);
  border-radius: 16px; border: 1px solid var(--primary);
  box-shadow: 0 10px 25px rgba(30, 136, 229, 0.08);
}
.split-layout { display: flex; gap: 30px; max-width: 1150px; margin: 0 auto 30px; padding: 0 15px; }
.experience-side { flex: 1.5; }
.timeline-v { position: relative; padding-left: 30px; border-left: 3px solid var(--border); }
.timeline-v-item { position: relative; margin-bottom: 25px; }
.timeline-v-item::before {
  content: ''; position: absolute; left: -39px; top: 5px;
  width: 15px; height: 15px; background: white; border: 3px solid var(--primary);
  border-radius: 50%; z-index: 2;
}
.v-content { background: white; padding: 18px; border-radius: 12px; border: 1px solid var(--border); }
.v-content h3 { margin: 0; font-size: 17px; color: var(--primary-dark); }
.v-content b { font-size: 13.5px; color: #333; display: block; margin-top: 4px; line-height: 1.4; }
.inst-link { text-decoration: none !important; color: inherit !important; cursor: pointer; }

/* TOOLKIT STYLING */
.instrumentation-side { flex: 1; }
.sticky-right { position: sticky; top: 100px; }
.inst-category { margin-bottom: 8px; } 
.inst-category h4 { 
  font-size: 10px; text-transform: uppercase; color: #888; 
  letter-spacing: 1px; margin-bottom: 4px; border-bottom: 1px solid #eee; padding-bottom: 2px;
}
.skill-grid-compact { display: grid; grid-template-columns: repeat(2, 1fr); gap: 7px; }
.skill-badge-v {
  background: white; border: 1px solid var(--border); 
  padding: 6px 5px; border-radius: 8px; text-align: center;
  display: flex; flex-direction: column; justify-content: center; min-height: 52px; 
}
.skill-badge-v b { font-size: 11.5px; display: block; color: var(--primary-dark); line-height: 1.1; }
.skill-badge-v small { font-size: 10.5px; color: #555; margin-top: 3px; font-weight: 500; }

.diode-icon { vertical-align: middle; margin-right: 8px; width: 24px; height: 24px; }
.profile-links {
  max-width: 1150px; margin: 40px auto; text-align: center;
  padding: 20px; border-top: 1px solid var(--border);
}
.markdown-body { overflow: visible !important; }
</style>

<div class="hero-header">
  <img src="/assets/header2.jpg" alt="Experience header">
  <div class="hero-title">Experience & Expertise</div>
</div>

<div class="nav-bar">
  <a href="/">🏠 Home</a>
  <a href="/experience/">👨‍🔬 Experience</a>
  <a href="/impact/">📈 Impact</a>
  <div class="dropdown">
    <span class="dropdown-toggle">📚 Publications ▾</span>
    <div class="dropdown-content">
      <div class="dropdown-menu-box">
        <a href="/patents/">📜 1. Patents</a>
        <a href="/Book_Chapters/">📖 2. Book Chapters</a>
        <a href="/publications/">📝 3. Peer-Reviewed Articles</a>
      </div>
    </div>
  </div>
  <a href="/contact/">📬 Contact</a>
</div>

<div class="dev-highlight-full">
  <h2 style="margin-top:0; margin-bottom: 8px; color:var(--primary-dark); font-size: 22px;">🔬 Instrumental Development</h2>
  <p style="font-size: 14.5px; line-height: 1.5; color: #333; margin-bottom: 0;">
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
        <b><a href="https://www.usal.es/en" target="_blank" class="inst-link">🇪🇸 Department of Physics, University of Salamanca, Spain (2024–Present)</a></b>
      </div></div>
      <div class="timeline-v-item"><div class="v-content">
        <h3>Post-Doctoral Fellow</h3>
        <b><a href="https://www.sce.ac.il/en" target="_blank" class="inst-link">🇮🇱 Shamoon College of Engineering, Beer Sheva, Israel (2022–2024)</a></b>
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

    <div style="background: white; padding: 20px; border-radius: 12px; border: 1px solid var(--border); margin-top: 20px;">
      <h3 style="margin-top:0; color:var(--primary-dark); display: flex; align-items: center;">
        <svg class="diode-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M4 19H20M5 5V18" stroke="#1e88e5" stroke-width="2" stroke-linecap="round"/>
          <path d="M6 17C9 17 14 15 18 6" stroke="#f44336" stroke-width="2" stroke-linecap="round"/>
          <path d="M14 12L20 12M17 9V15M20 9V15" stroke="#1e88e5" stroke-width="1.5"/>
        </svg>
        Electrical & Field Emission
      </h3>
      <p style="font-size: 14px; color: #444; margin-bottom: 15px;">Characterization of field emission properties including I-V measurements in diode configuration for cold cathode applications.</p>
    </div>
  </div>

  <div class="instrumentation-side">
    <div class="sticky-right">
      <h2 style="color: var(--primary-dark); margin-bottom: 20px;">🛠️ Technical Toolkit</h2>
      <div class="inst-category">
        <h4>🔥 Thermal Analysis</h4>
        <div class="skill-grid-compact">
          <div class="skill-badge-v"><b>DSC</b><small>Phase Transitions</small></div>
          <div class="skill-badge-v"><b>TGA</b><small>Weight Change</small></div>
          <div class="skill-badge-v" style="grid-column: span 2;"><b>Furnaces</b><small>Up to 1600°C</small></div>
        </div>
      </div>
      <div class="inst-category">
        <h4>⚛️ Structural & Morphological</h4>
        <div class="skill-grid-compact">
          <div class="skill-badge-v"><b>XRD</b><small>High-Temp XRD</small></div>
          <div class="skill-badge-v"><b>SEM</b><small>JSM-IT 300</small></div>
          <div class="skill-badge-v"><b>AFM</b><small>Surface Topology</small></div>
          <div class="skill-badge-v"><b>BET</b><small>Surface Area</small></div>
        </div>
      </div>
      <div class="inst-category">
        <h4>🌈 Spectroscopy & Electro-chem</h4>
        <div class="skill-grid-compact">
          <div class="skill-badge-v"><b>Raman</b><small>Confocal/Micro</small></div>
          <div class="skill-badge-v"><b>Metrohm / PalmSens</b><small>Workstations</small></div>
          <div class="skill-badge-v" style="grid-column: span 2;"><b>UV-Vis-NIR</b><small>IR / DRS Mode</small></div>
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
