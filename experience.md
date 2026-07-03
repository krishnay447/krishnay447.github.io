---
layout: default
title: Experience
permalink: /experience/
---

<style>
/* ===== Clean Academic Theme ===== */
.markdown-body > h1:first-child { display: none !important; }
.markdown-body { overflow: visible !important; }
:root{
  --accent:#1a5490; --accent-dark:#123c66; --ink:#1f2937; --muted:#5b6572;
  --border:#e3e8ef; --bg-soft:#f7f9fb; --heading:#1c2e40;
}
body{ background:#fff !important; color:var(--ink); font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif; margin:0; padding:0; line-height:1.65; }
h1,h2,h3{ font-family:Georgia,"Times New Roman",serif; color:var(--heading); font-weight:600; }
a{ color:var(--accent); }

/* NAV */
.site-nav{ position:sticky; top:0; z-index:1000; background:rgba(255,255,255,0.97); border-bottom:1px solid var(--border); }
.nav-inner{ max-width:1000px; margin:0 auto; padding:12px 20px; display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:10px; }
.brand{ font-family:Georgia,serif; font-size:20px; font-weight:700; color:var(--heading) !important; text-decoration:none; }
.nav-links{ display:flex; align-items:center; gap:2px; flex-wrap:wrap; }
.nav-links a, .dropdown-toggle{ color:var(--ink) !important; text-decoration:none; font-size:15px; font-weight:600; padding:6px 12px; border-radius:6px; }
.nav-links a:hover, .dropdown:hover .dropdown-toggle{ background:var(--bg-soft); color:var(--accent) !important; }
.dropdown{ position:relative; display:inline-block; }
.dropdown-content{ display:none; position:absolute; top:100%; right:0; min-width:190px; z-index:999; padding-top:8px; }
.dropdown:hover .dropdown-content{ display:block; }
.dropdown-menu-box{ background:#fff; border:1px solid var(--border); border-radius:8px; box-shadow:0 10px 25px rgba(0,0,0,0.08); padding:6px; }
.dropdown-menu-box a{ display:block; padding:9px 14px; font-size:14px; color:var(--ink) !important; text-decoration:none; border-radius:6px; }
.dropdown-menu-box a:hover{ background:var(--bg-soft); color:var(--accent) !important; }

/* PAGE HEAD */
.page-head{ max-width:1000px; margin:44px auto 10px; padding:0 20px; }
.page-head h1{ font-size:34px; margin:0 0 6px; }
.page-head p{ color:var(--muted); margin:0; font-size:16.5px; }

/* LAYOUT */
.split{ max-width:1000px; margin:26px auto 0; padding:0 20px; display:grid; grid-template-columns:1fr 320px; gap:36px; align-items:start; }
.eyebrow{ font-size:12.5px; letter-spacing:1.8px; text-transform:uppercase; color:var(--accent); font-weight:700; margin:30px 0 12px; }
.eyebrow:first-child{ margin-top:0; }

/* TIMELINE */
.timeline{ position:relative; padding-left:26px; border-left:2px solid var(--border); }
.t-item{ position:relative; margin-bottom:22px; }
.t-item::before{ content:''; position:absolute; left:-33px; top:7px; width:12px; height:12px; background:#fff; border:3px solid var(--accent); border-radius:50%; }
.t-item h3{ margin:0; font-size:18px; }
.t-item .inst{ font-size:14.5px; color:var(--muted); margin-top:3px; }
.t-item .inst a{ color:var(--muted); text-decoration:none; }
.t-item .inst a:hover{ color:var(--accent); }

/* HIGHLIGHT + CARDS */
.highlight{ background:var(--bg-soft); border:1px solid var(--border); border-left:4px solid var(--accent); border-radius:8px; padding:18px 20px; margin:14px 0 26px; font-size:15.5px; }
.exp-card{ background:#fff; border:1px solid var(--border); border-radius:10px; padding:18px 20px; margin-bottom:16px; }
.exp-card h3{ margin:0 0 8px; font-size:17.5px; }
.exp-card p{ margin:0; font-size:14.5px; color:#3d4754; }

/* TOOLKIT */
.inst-category{ margin-bottom:20px; }
.inst-category h4{ font-size:12px; text-transform:uppercase; color:var(--muted); letter-spacing:1.5px; margin:0 0 10px; border-bottom:1px solid var(--border); padding-bottom:6px; }
.skill-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:10px; }
.skill-badge{ background:var(--bg-soft); border:1px solid var(--border); padding:12px 10px; border-radius:8px; text-align:center; min-height:58px; display:flex; flex-direction:column; justify-content:center; }
.skill-badge b{ font-size:14.5px; color:var(--accent-dark); }
.skill-badge small{ font-size:12px; color:var(--muted); }

/* FOOTER */
.site-footer{ border-top:1px solid var(--border); margin-top:56px; padding:32px 20px 40px; text-align:center; color:var(--muted); font-size:14px; }
.site-footer a{ margin:0 10px; font-weight:600; text-decoration:none; }

@media (max-width:900px){ .split{ grid-template-columns:1fr; } }
</style>

<nav class="site-nav">
  <div class="nav-inner">
    <a class="brand" href="/">Krishna K. Yadav</a>
    <div class="nav-links">
      <a href="/">Home</a>
      <a href="/experience/">Experience</a>
      <a href="/impact/">Impact</a>
      <div class="dropdown">
        <a href="/publications/" class="dropdown-toggle">Publications &#9662;</a>
        <div class="dropdown-content"><div class="dropdown-menu-box">
          <a href="/publications/">Journal Articles</a>
          <a href="/Book_Chapters/">Book Chapters</a>
          <a href="/patents/">Patents</a>
        </div></div>
      </div>
      <a href="/cv/">CV</a>
      <a href="/contact/">Contact</a>
    </div>
  </div>
</nav>

<div class="page-head">
  <h1>Experience &amp; Expertise</h1>
  <p>Research positions, instrumentation development, and technical skills.</p>
</div>

<div class="split">
  <div>
    <p class="eyebrow">Instrumental Development</p>
    <div class="highlight">
      <b>Modified Optical Microscopy.</b> I actively develop and modify scientific setups to meet specific research needs. I integrated a <b>high-resolution spectrometer</b> into an optical microscope system, enabling precise, non-destructive <b>2D material thickness determination</b> through localized spectral analysis.
    </div>

    <p class="eyebrow">Research Positions</p>
    <div class="timeline">
      <div class="t-item">
        <h3>Postdoctoral Fellow</h3>
        <div class="inst"><a href="https://nanotech.usal.es/" target="_blank" rel="noopener">University of Salamanca, Spain</a> &middot; 2024&ndash;Present</div>
      </div>
      <div class="t-item">
        <h3>Postdoctoral Fellow</h3>
        <div class="inst"><a href="https://en.sce.ac.il/" target="_blank" rel="noopener">Shamoon College of Engineering, Israel</a> &middot; 2022&ndash;2024</div>
      </div>
      <div class="t-item">
        <h3>Research Associate</h3>
        <div class="inst"><a href="https://inst.ac.in/" target="_blank" rel="noopener">Institute of Nano Science and Technology (INST), Mohali, India</a> &middot; 2021&ndash;2022</div>
      </div>
      <div class="t-item">
        <h3>PhD Scholar, Nanotechnology</h3>
        <div class="inst"><a href="https://inst.ac.in/" target="_blank" rel="noopener">Institute of Nano Science and Technology (INST), Mohali, India</a> &middot; 2016&ndash;2021</div>
      </div>
    </div>

    <p class="eyebrow">Core Expertise</p>
    <div class="exp-card">
      <h3>Electrical &amp; Field Emission</h3>
      <p>Characterization of field emission properties including I&ndash;V measurements in diode configuration for cold cathode applications.</p>
    </div>
    <div class="exp-card">
      <h3>Cleanroom Fabrication (2D Materials)</h3>
      <p>Extensive experience in cleanroom fabrication processes, including photolithography, e-beam lithography, and thin-film deposition, optimized for 2D heterostructure assembly.</p>
    </div>
    <p style="font-size:14px; color:var(--muted);">Full instrumentation details are on the <a href="/instrumentation/">Instrumentation page</a>.</p>
  </div>

  <div>
    <p class="eyebrow">Technical Toolkit</p>
    <div class="inst-category">
      <h4>Thermal Analysis</h4>
      <div class="skill-grid">
        <div class="skill-badge"><b>DSC</b><small>Phase Transitions</small></div>
        <div class="skill-badge"><b>TGA</b><small>Weight Change</small></div>
        <div class="skill-badge" style="grid-column:span 2;"><b>Furnaces</b><small>Up to 1600&deg;C</small></div>
      </div>
    </div>
    <div class="inst-category">
      <h4>Structural &amp; Morphological</h4>
      <div class="skill-grid">
        <div class="skill-badge"><b>XRD</b><small>High-Temp XRD</small></div>
        <div class="skill-badge"><b>SEM</b><small>JEOL JSM-IT 300</small></div>
        <div class="skill-badge"><b>AFM</b><small>Surface Topology</small></div>
        <div class="skill-badge"><b>BET</b><small>Surface Area</small></div>
      </div>
    </div>
    <div class="inst-category">
      <h4>Spectroscopy &amp; Electrochemistry</h4>
      <div class="skill-grid">
        <div class="skill-badge"><b>Raman</b><small>Confocal / Micro</small></div>
        <div class="skill-badge"><b>Metrohm</b><small>Workstations</small></div>
        <div class="skill-badge" style="grid-column:span 2;"><b>UV-Vis-NIR</b><small>IR / DRS Mode</small></div>
      </div>
    </div>
  </div>
</div>

<footer class="site-footer">
  <b style="color:var(--heading);">Dr. Krishna Kumar Yadav</b><br>
  <div style="margin:10px 0;">
    <a href="mailto:Krish91phy@usal.es">Email</a>
    <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" rel="noopener">Google Scholar</a>
    <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" rel="noopener">ORCID</a>
  </div>
  &copy; 2026 Krishna Kumar Yadav. All rights reserved.
</footer>
