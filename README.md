---
layout: default
title: Dr. Krishna Kumar Yadav
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

/* INTRO */
.intro{ max-width:1000px; margin:48px auto 12px; padding:0 20px; display:flex; gap:36px; align-items:center; flex-wrap:wrap; }
.intro img{ width:190px; height:190px; object-fit:cover; border-radius:50%; border:1px solid var(--border); box-shadow:0 4px 14px rgba(0,0,0,0.08); }
.intro h1{ font-size:36px; margin:0 0 6px; }
.intro .role{ font-size:17px; color:var(--muted); margin:0 0 4px; }
.intro .affil{ font-size:16px; color:var(--muted); margin:0 0 14px; }
.link-row a{ display:inline-block; margin:0 14px 6px 0; font-weight:600; font-size:15px; text-decoration:none; border-bottom:1px solid transparent; }
.link-row a:hover{ border-bottom-color:var(--accent); }

/* LAYOUT */
.main-grid{ max-width:1000px; margin:28px auto 0; padding:0 20px; display:grid; grid-template-columns:1fr 300px; gap:36px; align-items:start; }
.eyebrow{ font-size:12.5px; letter-spacing:1.8px; text-transform:uppercase; color:var(--accent); font-weight:700; margin:34px 0 8px; }
.eyebrow:first-child{ margin-top:0; }
section h2{ font-size:24px; margin:0 0 12px; }
.focus-item{ padding:14px 0; border-bottom:1px solid var(--border); }
.focus-item:last-child{ border-bottom:none; }
.focus-item b{ color:var(--heading); }
.pill{ display:inline-block; padding:4px 12px; background:var(--bg-soft); border:1px solid var(--border); color:var(--accent-dark); border-radius:20px; font-size:13.5px; font-weight:600; margin:3px 4px 3px 0; }

/* SIDEBAR */
.side-card{ background:var(--bg-soft); border:1px solid var(--border); border-radius:10px; padding:20px; margin-bottom:22px; }
.side-card h3{ font-size:17px; margin:0 0 12px; }
.news-list{ list-style:none; margin:0; padding:0; }
.news-list li{ padding:9px 0; border-bottom:1px solid var(--border); font-size:14px; line-height:1.5; }
.news-list li:last-child{ border-bottom:none; }
.news-date{ color:var(--accent); font-weight:700; font-size:12.5px; text-transform:uppercase; letter-spacing:0.5px; display:block; }
.tool-links a{ display:block; padding:7px 0; font-size:14.5px; font-weight:600; text-decoration:none; border-bottom:1px solid var(--border); }
.tool-links a:last-child{ border-bottom:none; }

/* GALLERY */
.gallery-wrap{ max-width:1000px; margin:44px auto 0; padding:0 20px; }
.gallery-grid{ display:grid; grid-template-columns:repeat(4,1fr); gap:14px; margin-top:14px; }
.gallery-grid img{ width:100%; height:150px; object-fit:cover; border-radius:8px; border:1px solid var(--border); }

/* FOOTER */
.site-footer{ border-top:1px solid var(--border); margin-top:56px; padding:32px 20px 40px; text-align:center; color:var(--muted); font-size:14px; }
.site-footer a{ margin:0 10px; font-weight:600; text-decoration:none; }

@media (max-width:900px){
  .main-grid{ grid-template-columns:1fr; }
  .gallery-grid{ grid-template-columns:repeat(2,1fr); }
  .intro{ justify-content:center; text-align:center; }
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

<div class="intro">
  <img src="/assets/profile.jpg" alt="Dr. Krishna Kumar Yadav">
  <div>
    <h1>Dr. Krishna Kumar Yadav</h1>
    <p class="role">Postdoctoral Researcher &middot; Nanotechnology &amp; 2D Material Devices</p>
    <p class="affil">Department of Fundamental Physics, University of Salamanca, Spain</p>
    <div class="link-row">
      <a href="mailto:Krish91phy@usal.es">Email</a>
      <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" rel="noopener">Google Scholar</a>
      <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" rel="noopener">ORCID</a>
      <a href="/cv/"><b>Download CV &rarr;</b></a>
    </div>
  </div>
</div>

<div class="main-grid">
  <section>
    <p class="eyebrow">About</p>
    <p>I am a researcher in <b>nanotechnology and advanced materials</b>, specializing in the synthesis of nanostructured materials and their application in next-generation electronics. My expertise spans the <b>mechanical and chemical exfoliation of 2D materials</b>, the precise <b>fabrication of optoelectronic and field-effect transistor (FET) devices</b>, and advanced characterization techniques such as <b>KPFM and Raman spectroscopy</b>.</p>

    <p class="eyebrow">Current Research</p>
    <div class="focus-item"><b>Device Fabrication &amp; FETs.</b> Developing high-performance field-effect transistors based on 2D material architectures to study charge transport and contact resistance.</div>
    <div class="focus-item"><b>Photodetector Optimization.</b> Engineering 2D-material photodetectors for high responsivity and external quantum efficiency through precise interface and contact engineering.</div>
    <div class="focus-item"><b>Nanoscale Characterization.</b> Employing Dip-Pen Nanolithography (DPN) and Atomic Force Microscopy (AFM/KPFM) to pattern surfaces and study the electronic behavior of 2D heterostructures.</div>

    <p class="eyebrow">Future Directions</p>
    <p>My long-term goals include developing ultra-sensitive, flexible, and high-speed optoelectronic devices from 2D heterostructures; applying machine learning to accelerate device-architecture optimization for photodetectors and sensors; and industry-scale fabrication of short-channel TMDC devices with very high on/off ratios.</p>

    <p class="eyebrow">Technical Toolkit</p>
    <div>
      <span class="pill">KPFM / FFM</span>
      <span class="pill">2D Material Exfoliation</span>
      <span class="pill">Cold Field Emission</span>
      <span class="pill">Cleanroom Nanofabrication</span>
      <span class="pill">Raman Spectroscopy</span>
      <span class="pill">AI for Science</span>
    </div>
  </section>

  <aside>
    <div class="side-card">
      <h3>Latest News</h3>
      <ul class="news-list">
        <li><span class="news-date">Jan 2026</span> Installed a spectrometer for 2D material thickness analysis.</li>
        <li><span class="news-date">Dec 2025</span> MnFe<sub>2</sub>O<sub>4</sub> electrocatalysis study published.</li>
        <li><span class="news-date">Nov 2025</span> Invited talk at AMatS Spain on Schottky junctions.</li>
      </ul>
    </div>

    <div class="side-card">
      <h3>Digital Tools Suite</h3>
      <div class="tool-links">
        <a href="https://photosensor-459111164189.us-west1.run.app/" target="_blank" rel="noopener">PhotoSensor</a>
        <a href="https://fermi-studio-459111164189.us-west1.run.app/" target="_blank" rel="noopener">BandGap Aligner</a>
        <a href="https://charge-transport-explorer-459111164189.us-west1.run.app/" target="_blank" rel="noopener">Device Physics Analyzer</a>
        <a href="https://acadefig-459111164189.us-west1.run.app/" target="_blank" rel="noopener">AcadeFig Pro</a>
        <a href="https://pdf-utility-hub-459111164189.us-west1.run.app" target="_blank" rel="noopener">PDF Utility Hub</a>
      </div>
    </div>

    <div class="side-card">
      <h3>Featured Research</h3>
      <p style="font-size:13px; color:var(--muted); margin:0 0 6px;">Microscope imaging</p>
      <img src="/assets/photo5.jpg" alt="Microscope imaging" style="width:100%; height:140px; object-fit:cover; border-radius:8px; border:1px solid var(--border); margin-bottom:12px;">
      <p style="font-size:13px; color:var(--muted); margin:0 0 6px;">Device fabrication</p>
      <img src="/assets/photo6.jpg" alt="Device fabrication" style="width:100%; height:140px; object-fit:cover; border-radius:8px; border:1px solid var(--border);">
    </div>
  </aside>
</div>

<div class="gallery-wrap">
  <p class="eyebrow">Research &amp; Lab Gallery</p>
  <div class="gallery-grid">
    <img src="/assets/photo1.jpg" alt="Lab 1">
    <img src="/assets/photo2.jpg" alt="Lab 2">
    <img src="/assets/photo3.jpg" alt="Lab 3">
    <img src="/assets/photo4.jpg" alt="Lab 4">
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
