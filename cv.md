---
layout: default
title: Curriculum Vitae
permalink: /cv/
---

<style>
/* ===== Clean Academic Theme ===== */
.markdown-body > h1:first-child { display: none !important; }
.markdown-body { overflow: visible !important; }
:root{
  --accent:#1a5490; --accent-dark:#123c66; --ink:#1f2937; --muted:#5b6572;
  --border:#e3e8ef; --bg-soft:#f7f9fb; --heading:#1c2e40;
}
body{ background:#fff !important; color:var(--ink); font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif; margin:0; padding:0; line-height:1.6; }
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

/* CV LAYOUT */
.cv-wrap{ max-width:840px; margin:40px auto 0; padding:0 24px; }
.cv-header{ text-align:center; border-bottom:2px solid var(--heading); padding-bottom:18px; margin-bottom:8px; }
.cv-header h1{ font-size:32px; margin:0 0 4px; }
.cv-header .cv-role{ font-size:16px; color:var(--muted); margin:0 0 8px; }
.cv-header .cv-contact{ font-size:13.5px; color:var(--muted); }
.cv-header .cv-contact a{ text-decoration:none; font-weight:600; }
.print-row{ text-align:center; margin:16px 0 4px; }
.print-btn{ display:inline-block; background:var(--accent); color:#fff !important; border:none; padding:10px 24px; border-radius:8px; font-size:14.5px; font-weight:700; cursor:pointer; text-decoration:none; }
.print-btn:hover{ background:var(--accent-dark); }
.print-hint{ font-size:12.5px; color:var(--muted); margin-top:6px; }

.cv-section{ margin-top:30px; }
.cv-section h2{ font-size:19px; text-transform:uppercase; letter-spacing:1.5px; border-bottom:1px solid var(--border); padding-bottom:6px; margin:0 0 14px; }
.cv-item{ margin-bottom:14px; }
.cv-item .cv-line{ display:flex; justify-content:space-between; gap:14px; flex-wrap:wrap; }
.cv-item b{ color:var(--heading); font-size:15.5px; }
.cv-date{ color:var(--muted); font-size:14px; white-space:nowrap; font-weight:600; }
.cv-sub{ font-size:14px; color:var(--muted); }
.cv-desc{ font-size:14px; color:#3d4754; margin-top:3px; }

.cv-metrics{ display:grid; grid-template-columns:repeat(4,1fr); gap:12px; margin-top:4px; }
.cv-metric{ background:var(--bg-soft); border:1px solid var(--border); border-radius:8px; padding:12px; text-align:center; }
.cv-metric .n{ font-family:Georgia,serif; font-size:24px; font-weight:700; color:var(--accent-dark); }
.cv-metric .l{ font-size:11.5px; text-transform:uppercase; letter-spacing:0.8px; color:var(--muted); }

.cv-pub{ font-size:14px; margin-bottom:10px; padding-left:22px; text-indent:-22px; }
.cv-pub a{ font-weight:600; text-decoration:none; font-size:13px; }
.skill-row{ font-size:14px; margin-bottom:8px; }
.skill-row b{ color:var(--heading); }
.two-col{ display:grid; grid-template-columns:1fr 1fr; gap:6px 24px; font-size:14px; }

/* FOOTER */
.site-footer{ border-top:1px solid var(--border); margin-top:56px; padding:32px 20px 40px; text-align:center; color:var(--muted); font-size:14px; }
.site-footer a{ margin:0 10px; font-weight:600; text-decoration:none; }

@media (max-width:700px){ .cv-metrics{ grid-template-columns:repeat(2,1fr); } .two-col{ grid-template-columns:1fr; } }

/* PRINT: turns this page into a clean PDF */
@media print{
  .site-nav, .site-footer, .print-row{ display:none !important; }
  body{ font-size:12px; }
  .cv-wrap{ max-width:100%; margin:0; padding:0; }
  a{ color:#000 !important; text-decoration:none !important; }
  .cv-metric{ border:1px solid #999; }
  .cv-section{ page-break-inside:avoid; }
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

<div class="cv-wrap">

  <div class="cv-header">
    <h1>Dr. Krishna Kumar Yadav</h1>
    <p class="cv-role">Postdoctoral Researcher &mdash; Nanotechnology &amp; 2D Material Devices</p>
    <div class="cv-contact">
      Department of Fundamental Physics, University of Salamanca, Spain<br>
      <a href="mailto:Krish91phy@usal.es">Krish91phy@usal.es</a> &middot;
      <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" rel="noopener">Google Scholar</a> &middot;
      <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" rel="noopener">ORCID: 0000-0002-9063-7851</a>
    </div>
  </div>

  <div class="print-row">
    <a class="print-btn" href="javascript:window.print()">Download as PDF</a>
    <div class="print-hint">Opens your print dialog &mdash; choose "Save as PDF" as the destination.</div>
  </div>

  <div class="cv-section">
    <h2>Research Profile</h2>
    <p style="font-size:14.5px; margin:0;">Researcher in nanotechnology and advanced materials specializing in the synthesis, transfer, and device integration of 2D materials (graphene, TMDCs, black phosphorus). Expertise spans mechanical and chemical exfoliation, cleanroom nanofabrication (photolithography, e-beam lithography, thin-film deposition), fabrication of optoelectronic devices and field-effect transistors, and advanced characterization (KPFM, Raman spectroscopy, Dip-Pen Nanolithography, field emission).</p>
  </div>

  <div class="cv-section">
    <h2>Research Metrics</h2>
    <div class="cv-metrics">
      <div class="cv-metric"><div class="n">51</div><div class="l">Journal Articles</div></div>
      <div class="cv-metric"><div class="n">13</div><div class="l">Book Chapters</div></div>
      <div class="cv-metric"><div class="n">3</div><div class="l">Patents</div></div>
      <div class="cv-metric"><div class="n">800+</div><div class="l">Citations</div></div>
    </div>
  </div>

  <div class="cv-section">
    <h2>Research Positions</h2>
    <div class="cv-item">
      <div class="cv-line"><b>Postdoctoral Fellow</b><span class="cv-date">2024 &ndash; Present</span></div>
      <div class="cv-sub">Department of Fundamental Physics, University of Salamanca, Spain</div>
      <div class="cv-desc">Fabrication of 2D-material FETs and photodetectors; charge transport and contact resistance studies; integration of a high-resolution spectrometer into optical microscopy for non-destructive 2D thickness determination.</div>
    </div>
    <div class="cv-item">
      <div class="cv-line"><b>Postdoctoral Fellow</b><span class="cv-date">2022 &ndash; 2024</span></div>
      <div class="cv-sub">Shamoon College of Engineering, Beer Sheva, Israel</div>
      <div class="cv-desc">Dip-Pen Nanolithography patterning of meta-chemical surfaces; electrochemical sensors for heavy-metal detection based on black phosphorus and functional inks.</div>
    </div>
    <div class="cv-item">
      <div class="cv-line"><b>Research Associate</b><span class="cv-date">2021 &ndash; 2022</span></div>
      <div class="cv-sub">Institute of Nano Science and Technology (INST), Mohali, India</div>
      <div class="cv-desc">Engineered 2D materials and nanostructures for field emission and energy applications.</div>
    </div>
    <div class="cv-item">
      <div class="cv-line"><b>PhD Scholar, Nanotechnology</b><span class="cv-date">2016 &ndash; 2021</span></div>
      <div class="cv-sub">Institute of Nano Science and Technology (INST), Mohali, India &mdash; Supervisors: Prof. Ashok K. Ganguli &amp; Dr. Menaka Jha</div>
      <div class="cv-desc">Synthesis and stabilization of rare-earth hexaboride nanostructures and 2D materials for cold-cathode field emission; waste-derived functional nanomaterials for energy and environment.</div>
    </div>
  </div>

  <div class="cv-section">
    <h2>Selected First-Author Publications</h2>
    <p style="font-size:13px; color:var(--muted); margin:0 0 12px;">Full list of 51 articles: <a href="/publications/">krishnay447.github.io/publications</a></p>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Electrochemical Sensor Based on Black Phosphorus for Antimony Detection Using Dip-Pen Nanolithography: The Role of Dwell Time. <i>Small Methods</i>, 2402157 (2025). <a href="https://doi.org/10.1002/smtd.202402157" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Development of Meta-Chemical Surface by Dip-Pen Nanolithography for Precise Electrochemical Lead Sensing. <i>Small Methods</i>, 8, 1&ndash;9 (2024). <a href="https://doi.org/10.1002/smtd.202301118" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Black Phosphorus/Dysprosium Hexaboride-Based Heterostructured Films for Field Emission Technologies. <i>ACS Applied Nano Materials</i>, 7, 9942&ndash;9949 (2024). <a href="https://doi.org/10.1021/acsanm.3c06152" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Er<sub>2</sub>FeCrO<sub>6</sub>: Emerging efficient nanomaterials for multiferroics. <i>Materials Chemistry and Physics</i>, 317, 129198 (2024). <a href="https://doi.org/10.1016/j.matchemphys.2024.129198" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Understanding the role of sheet thickness on field emission from engineered hexagonal tin disulphide. <i>Applied Surface Science</i>, 606, 154816 (2022). <a href="https://doi.org/10.1016/j.apsusc.2022.154816" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Design of a new process for stabilization of La<sub>x</sub>Gd<sub>1-x</sub>B<sub>6</sub> nanorods and their Field Emission properties. <i>Materials Science and Engineering: B</i>, 282, 115759 (2022). <a href="https://doi.org/10.1016/j.mseb.2022.115759" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Efficient metal-free supercapacitor based on graphene oxide derived from waste rice. <i>Current Research in Green and Sustainable Chemistry</i>, 4, 100075 (2021). <a href="https://doi.org/10.1016/j.crgsc.2021.100075" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Utilization of waste coir fibre architecture to synthesize porous graphene oxide: An efficient energy storage material. <i>Journal of Cleaner Production</i>, 276, 124240 (2020). <a href="https://doi.org/10.1016/j.jclepro.2020.124240" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., Excellent Field Emission from Ultrafine Vertically Aligned Nanorods of NdB<sub>6</sub> on Silicon Substrate. <i>Applied Surface Science</i>, 526, 146652 (2020). <a href="https://doi.org/10.1016/j.apsusc.2020.146652" target="_blank" rel="noopener">DOI</a></div>
    <div class="cv-pub"><b>K.K. Yadav</b> et al., A new Process for Stabilization of Vertically Aligned GdB<sub>6</sub> nanorods and their Field Emission Properties. <i>CrystEngComm</i>, 22, 5473&ndash;5480 (2020). <a href="https://doi.org/10.1039/D0CE00591F" target="_blank" rel="noopener">DOI</a></div>
  </div>

  <div class="cv-section">
    <h2>Patents</h2>
    <div class="cv-pub">A Process for Producing La<sub>2</sub>FeMnO<sub>6</sub> (LFMO) From Iron Ore Slime and Applications Thereof. Patent No. 482517, granted 14/12/2023 (India).</div>
    <div class="cv-pub">Process of Preparing Silica-Iron Oxide From Iron Ore Slime. Patent No. 577043, granted 31/12/2025 (India).</div>
    <div class="cv-pub">Conversion of wastepaper to nanostructured CaCO<sub>3</sub> for de-fluorination of water. Application No. 202311017356 (pending).</div>
  </div>

  <div class="cv-section">
    <h2>Technical Skills</h2>
    <div class="skill-row"><b>2D Materials:</b> Mechanical &amp; chemical exfoliation, heterostructure assembly and transfer, thickness determination via localized spectral analysis.</div>
    <div class="skill-row"><b>Nanofabrication:</b> Cleanroom processing, photolithography, e-beam lithography, thin-film deposition, Dip-Pen Nanolithography.</div>
    <div class="skill-row"><b>Device Physics:</b> FET fabrication and characterization, photodetector optimization (responsivity, EQE), contact engineering, field emission (I&ndash;V, diode configuration).</div>
    <div class="skill-row"><b>Characterization:</b> AFM/KPFM/FFM, confocal &amp; micro-Raman, SEM (JEOL JSM-IT 300), XRD (incl. high-temperature), BET, DSC, TGA, UV-Vis-NIR (DRS).</div>
    <div class="skill-row"><b>Electrochemistry:</b> Metrohm and PalmSens workstations, cyclic voltammetry, electrochemical sensing.</div>
    <div class="skill-row"><b>Software &amp; Tools:</b> AI-assisted data analysis; developer of the Photocurrent Detector Tool (automated response-time and EQE extraction) and a suite of web-based device-physics tools.</div>
  </div>

  <div class="cv-section">
    <h2>Mentorship</h2>
    <div class="two-col">
      <span>Dr. Heena Sammi &mdash; Master's Project</span>
      <span>Rub&eacute;n Bastida Vadillo &mdash; Master's Project</span>
      <span>Alex Bellido Escribano &mdash; Master's Project</span>
      <span>Priyanka Goyal &mdash; B.Sc. Supervision</span>
    </div>
  </div>

  <div class="cv-section">
    <h2>References</h2>
    <div class="two-col">
      <span><b>Prof. Enrique Diez</b><br>University of Salamanca<br><a href="mailto:enrisa@usal.es">enrisa@usal.es</a></span>
      <span><b>Dr. Ariela Burg</b><br>Shamoon College of Engineering<br><a href="mailto:arielab@sce.ac.il">arielab@sce.ac.il</a></span>
      <span><b>Prof. Ashok K. Ganguli</b><br>IIT Delhi<br><a href="mailto:ashok@chemistry.iitd.ac.in">ashok@chemistry.iitd.ac.in</a></span>
      <span><b>Dr. Menaka Jha</b><br>INST Mohali<br><a href="mailto:menaka100jha@gmail.com">menaka100jha@gmail.com</a></span>
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
