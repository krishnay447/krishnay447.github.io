---
layout: default
title: Impact
permalink: /impact/
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

/* METRICS */
.metrics{ max-width:1000px; margin:26px auto 0; padding:0 20px; display:grid; grid-template-columns:repeat(4,1fr); gap:16px; }
.metric{ background:var(--bg-soft); border:1px solid var(--border); border-radius:10px; padding:20px; text-align:center; }
.metric .num{ font-family:Georgia,serif; font-size:34px; font-weight:700; color:var(--accent-dark); line-height:1.1; }
.metric .label{ font-size:13px; text-transform:uppercase; letter-spacing:1px; color:var(--muted); margin-top:6px; }

/* LAYOUT */
.split{ max-width:1000px; margin:34px auto 0; padding:0 20px; display:grid; grid-template-columns:1fr 1fr; gap:36px; align-items:start; }
.eyebrow{ font-size:12.5px; letter-spacing:1.8px; text-transform:uppercase; color:var(--accent); font-weight:700; margin:0 0 12px; }
.person-card{ background:#fff; border:1px solid var(--border); border-left:3px solid var(--accent); border-radius:8px; padding:12px 16px; margin-bottom:10px; }
.person-name{ font-weight:700; color:var(--heading); }
.person-role{ font-size:13px; color:var(--muted); display:block; }
.advisor-item{ background:#fff; border:1px solid var(--border); border-radius:8px; padding:12px 16px; margin-bottom:10px; display:flex; justify-content:space-between; align-items:center; gap:10px; }
.email-btn{ background:var(--bg-soft); border:1px solid var(--border); color:var(--accent) !important; padding:5px 12px; border-radius:6px; font-size:12.5px; font-weight:700; text-decoration:none; white-space:nowrap; }
.email-btn:hover{ background:var(--accent); color:#fff !important; }

/* COLLABORATION */
.collab-wrap{ max-width:1000px; margin:40px auto 0; padding:0 20px; }
.collab-grid{ display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr)); gap:16px; margin-top:6px; }
.collab-card{ background:var(--bg-soft); border:1px solid var(--border); border-radius:10px; padding:18px 20px; }
.collab-card .person-name{ font-size:15.5px; }
.collab-card p{ font-size:14px; color:#3d4754; margin:8px 0 12px; }

/* INNOVATION */
.innov{ background:#fff; border:1px solid var(--border); border-radius:10px; padding:16px 18px; margin-top:14px; }
.innov b{ color:var(--heading); }
.innov p{ margin:4px 0 0; font-size:14px; color:var(--muted); }

/* FOOTER */
.site-footer{ border-top:1px solid var(--border); margin-top:56px; padding:32px 20px 40px; text-align:center; color:var(--muted); font-size:14px; }
.site-footer a{ margin:0 10px; font-weight:600; text-decoration:none; }

@media (max-width:900px){
  .split{ grid-template-columns:1fr; }
  .metrics{ grid-template-columns:repeat(2,1fr); }
}
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
  <h1>Academic Impact</h1>
  <p>Publication metrics, mentorship, collaborations, and instrumentation expertise.</p>
</div>

<div class="metrics">
  <div class="metric"><div class="num">51</div><div class="label">Journal Articles</div></div>
  <div class="metric"><div class="num">13</div><div class="label">Book Chapters</div></div>
  <div class="metric"><div class="num">3</div><div class="label">Patents</div></div>
  <div class="metric"><div class="num">812</div><div class="label">Citations</div></div>
</div>

<div class="split">
  <div>
    <p class="eyebrow">Mentorship &amp; Supervision</p>
    <div class="person-card"><span class="person-name">Dr. Heena Sammi</span><span class="person-role">Master's Project</span></div>
    <div class="person-card"><span class="person-name">Rub&eacute;n Bastida Vadillo</span><span class="person-role">Master's Project</span></div>
    <div class="person-card"><span class="person-name">Alex Bellido Escribano</span><span class="person-role">Master's Project</span></div>
    <div class="person-card"><span class="person-name">Priyanka Goyal</span><span class="person-role">B.Sc. Supervision</span></div>

    <p class="eyebrow" style="margin-top:28px;">Innovation</p>
    <div class="innov">
      <b>Photocurrent Detector Tool</b>
      <p>Software that automates response-time and EQE extraction from photodetector measurements.</p>
    </div>
  </div>

  <div>
    <p class="eyebrow">Key Research Advisors</p>
    <div class="advisor-item">
      <div><span class="person-name">Prof. Ashok K. Ganguli</span><span class="person-role">PhD Supervisor</span></div>
      <a href="mailto:ashok@chemistry.iitd.ac.in" class="email-btn">Email</a>
    </div>
    <div class="advisor-item">
      <div><span class="person-name">Dr. Menaka Jha</span><span class="person-role">PhD Supervisor</span></div>
      <a href="mailto:menaka100jha@gmail.com" class="email-btn">Email</a>
    </div>
    <div class="advisor-item">
      <div><span class="person-name">Dr. Ariela Burg</span><span class="person-role">Postdoc Supervisor</span></div>
      <a href="mailto:arielab@sce.ac.il" class="email-btn">Email</a>
    </div>
    <div class="advisor-item">
      <div><span class="person-name">Prof. Enrique Diez</span><span class="person-role">Postdoc Supervisor</span></div>
      <a href="mailto:enrisa@usal.es" class="email-btn">Email</a>
    </div>
  </div>
</div>

<div class="collab-wrap">
  <p class="eyebrow">Collaborative Publication Network</p>
  <div class="collab-grid">
    <div class="collab-card">
      <span class="person-name">Dr. Ana P&eacute;rez Rodr&iacute;guez</span>
      <p>Postdoc collaborator specializing in terahertz physics and semiconductor dynamics.</p>
      <a href="mailto:perez.rodriguez.ana@usal.es" class="email-btn">Email</a>
    </div>
    <div class="collab-card">
      <span class="person-name">Prof. Santanu Ghosh</span>
      <p>Research on field emission and nanostructures throughout doctoral studies.</p>
      <a href="mailto:santanu1@physics.iitd.ac.in" class="email-btn">Email</a>
    </div>
  </div>
</div>

<div class="collab-wrap">
  <p class="eyebrow">Instrumentation &amp; Development</p>
  <div style="background:var(--bg-soft); border:1px solid var(--border); border-left:3px solid var(--accent); border-radius:8px; padding:16px 20px; margin-bottom:16px; font-size:14.5px;">
    <b>Modified Optical Microscopy.</b> I actively develop and modify scientific setups to meet specific research needs &mdash; including integrating a high-resolution spectrometer into an optical microscope, enabling precise, non-destructive <b>2D material thickness determination</b> through localized spectral analysis.
  </div>
  <div class="collab-grid">
    <div class="collab-card">
      <span class="person-name">Thermal Analysis</span>
      <p><b>DSC</b> for heat flow and phase transitions (<a href="https://doi.org/10.1002/wer.1307" target="_blank" rel="noopener">example study</a>), <b>TGA</b> for weight change vs. temperature, and high-temperature <b>furnaces</b> for synthesis and annealing.</p>
    </div>
    <div class="collab-card">
      <span class="person-name">Electrical &amp; Field Emission</span>
      <p>Field emission characterization including <b>I&ndash;V measurements in diode configuration</b> for cold cathodes (<a href="https://doi.org/10.1016/j.apsusc.2020.146652" target="_blank" rel="noopener">example study</a>); <b>Metrohm</b> and <b>PalmSens</b> workstations for electrochemical sensing and cyclic voltammetry.</p>
    </div>
    <div class="collab-card">
      <span class="person-name">Structural &amp; Morphological</span>
      <p><b>XRD</b> including high-temperature XRD, <b>SEM</b> (JEOL JSM-IT 300) and <b>AFM</b> for surface topology, and <b>BET</b> surface-area analysis (QuantaChrome).</p>
    </div>
    <div class="collab-card">
      <span class="person-name">Spectroscopy</span>
      <p>Confocal and micro-<b>Raman</b> spectroscopy for vibrational mode analysis; <b>UV-Vis-NIR</b> in IR/DRS mode.</p>
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
