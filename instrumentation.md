---
layout: default
title: Instrumentation
permalink: /instrumentation/
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

/* CONTENT */
.content{ max-width:1000px; margin:26px auto 0; padding:0 20px; }
.eyebrow{ font-size:12.5px; letter-spacing:1.8px; text-transform:uppercase; color:var(--accent); font-weight:700; margin:30px 0 12px; }
.highlight{ background:var(--bg-soft); border:1px solid var(--border); border-left:4px solid var(--accent); border-radius:8px; padding:18px 20px; margin:14px 0 10px; font-size:15.5px; }
.tool-card{ background:#fff; border:1px solid var(--border); border-radius:10px; padding:18px 20px; margin-bottom:16px; }
.tool-card h3{ margin:0 0 8px; font-size:17.5px; }
.tool-card p{ margin:0 0 6px; font-size:14.5px; color:#3d4754; }
.tool-card p:last-child{ margin-bottom:0; }

/* FOOTER */
.site-footer{ border-top:1px solid var(--border); margin-top:56px; padding:32px 20px 40px; text-align:center; color:var(--muted); font-size:14px; }
.site-footer a{ margin:0 10px; font-weight:600; text-decoration:none; }
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
  <h1>Instrumentation &amp; Development</h1>
  <p>My expertise extends beyond standard characterization; I actively develop and modify scientific setups to meet specific research needs.</p>
</div>

<div class="content">
  <p class="eyebrow">Instrumental Development</p>
  <div class="highlight">
    <b>Modified Optical Microscopy.</b> Successfully integrated a spectrometer into an optical microscope system. This custom setup allows precise, non-destructive <b>2D material thickness determination</b> through localized spectral analysis.
  </div>

  <p class="eyebrow">Characterization Tools</p>

  <div class="tool-card">
    <h3>Thermal Analysis</h3>
    <p><b>DSC:</b> Differential Scanning Calorimetry to study heat flow and phase transitions. Detailed DSC analysis of thermal phase transitions in my work: <a href="https://doi.org/10.1002/wer.1307" target="_blank" rel="noopener">doi.org/10.1002/wer.1307</a>.</p>
    <p><b>TGA:</b> Thermogravimetric Analysis for measuring weight changes relative to temperature.</p>
    <p><b>Furnaces:</b> Expert use of high-temperature furnaces for material synthesis and annealing.</p>
  </div>

  <div class="tool-card">
    <h3>Electrical &amp; Field Emission</h3>
    <p><b>Field Emission:</b> Characterization of field emission properties, including I&ndash;V measurements in diode configuration for cold cathode applications. Example publication: <a href="https://doi.org/10.1016/j.apsusc.2020.146652" target="_blank" rel="noopener">doi.org/10.1016/j.apsusc.2020.146652</a>.</p>
    <p><b>Workstations:</b> Professional use of Metrohm and PalmSens workstations for electrochemical sensing and cyclic voltammetry.</p>
  </div>

  <div class="tool-card">
    <h3>Structural &amp; Morphological</h3>
    <p><b>XRD:</b> X-ray diffraction, including specialized high-temperature XRD.</p>
    <p><b>Microscopy:</b> SEM (JEOL JSM-IT 300) and AFM for high-resolution surface topology.</p>
    <p><b>Surface Area:</b> BET measurement and analysis using QuantaChrome.</p>
  </div>

  <div class="tool-card">
    <h3>Spectroscopy</h3>
    <p><b>Raman:</b> Confocal and micro-Raman spectroscopy for vibrational mode analysis.</p>
  </div>

  <p><a href="/experience/">&larr; Back to Experience</a></p>
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
