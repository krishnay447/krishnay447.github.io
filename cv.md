---
layout: default
title: Curriculum Vitae
permalink: /cv/
---

<style>
  :root {
    --cv-accent: #1f3864;
    --cv-accent-light: #3f5b8c;
    --cv-text: #2b2b2b;
    --cv-muted: #5a5a5a;
    --cv-border: #dfe3ea;
    --cv-bg-soft: #f6f8fb;
  }

  .cv-wrap {
    max-width: 880px;
    margin: 0 auto;
    padding: 2rem 1.25rem 4rem;
    color: var(--cv-text);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.55;
  }

  .cv-header {
    text-align: center;
    padding-bottom: 1.5rem;
    margin-bottom: 2rem;
    border-bottom: 3px solid var(--cv-accent);
  }

  .cv-header h1 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 2.2rem;
    color: var(--cv-accent);
    margin: 0 0 0.35rem;
  }

  .cv-header .cv-title {
    font-size: 1.05rem;
    font-style: italic;
    color: var(--cv-muted);
    margin-bottom: 0.5rem;
  }

  .cv-header .cv-affil {
    font-size: 0.95rem;
    color: var(--cv-muted);
    margin-bottom: 0.75rem;
  }

  .cv-header .cv-links a {
    color: var(--cv-accent);
    text-decoration: none;
    font-weight: 600;
    margin: 0 0.4rem;
  }
  .cv-header .cv-links a:hover { text-decoration: underline; }

  .cv-download {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.55rem 1.3rem;
    background: var(--cv-accent);
    color: #fff !important;
    border-radius: 6px;
    font-weight: 600;
    text-decoration: none !important;
    font-size: 0.95rem;
  }
  .cv-download:hover { background: var(--cv-accent-light); }

  .cv-section {
    margin-bottom: 2.25rem;
  }

  .cv-section h2 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 1.3rem;
    color: var(--cv-accent);
    border-bottom: 2px solid var(--cv-border);
    padding-bottom: 0.4rem;
    margin-bottom: 1rem;
    letter-spacing: 0.02em;
  }

  .cv-metrics {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 1rem;
    text-align: center;
  }
  .cv-metric {
    background: var(--cv-bg-soft);
    border: 1px solid var(--cv-border);
    border-radius: 8px;
    padding: 1rem 0.5rem;
  }
  .cv-metric .num {
    display: block;
    font-size: 1.6rem;
    font-weight: 700;
    color: var(--cv-accent);
  }
  .cv-metric .label {
    font-size: 0.82rem;
    color: var(--cv-muted);
  }

  .cv-entry {
    margin-bottom: 1.1rem;
  }
  .cv-entry .role {
    font-weight: 700;
    color: var(--cv-text);
  }
  .cv-entry .dates {
    float: right;
    font-style: italic;
    color: var(--cv-muted);
    font-size: 0.9rem;
  }
  .cv-entry .org {
    color: var(--cv-muted);
  }
  .cv-entry .desc {
    font-size: 0.92rem;
    color: var(--cv-muted);
    margin-top: 0.2rem;
  }

  .cv-pub-list {
    list-style: none;
    counter-reset: pub-counter;
    padding: 0;
  }
  .cv-pub-list li {
    counter-increment: pub-counter;
    padding-left: 2rem;
    position: relative;
    margin-bottom: 0.85rem;
    font-size: 0.94rem;
  }
  .cv-pub-list li::before {
    content: counter(pub-counter) ".";
    position: absolute;
    left: 0;
    color: var(--cv-accent);
    font-weight: 700;
  }
  .cv-pub-list li a {
    color: var(--cv-accent);
    text-decoration: none;
    font-weight: 600;
  }
  .cv-pub-list li a:hover { text-decoration: underline; }

  .cv-grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
  }

  .cv-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  .cv-tags .tag-group {
    width: 100%;
    margin-bottom: 0.75rem;
  }
  .cv-tags .tag-group h3 {
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.04em;
    color: var(--cv-muted);
    margin: 0 0 0.4rem;
  }
  .cv-tags .tag {
    display: inline-block;
    background: var(--cv-bg-soft);
    border: 1px solid var(--cv-border);
    color: var(--cv-accent);
    font-size: 0.82rem;
    padding: 0.3rem 0.65rem;
    border-radius: 999px;
    margin: 0 0.35rem 0.35rem 0;
  }

  .cv-ref-card {
    border: 1px solid var(--cv-border);
    border-radius: 8px;
    padding: 0.85rem 1rem;
    margin-bottom: 0.85rem;
    background: var(--cv-bg-soft);
  }
  .cv-ref-card .name { font-weight: 700; }
  .cv-ref-card .affil { font-size: 0.88rem; color: var(--cv-muted); }
  .cv-ref-card .email { font-size: 0.88rem; }
  .cv-ref-card .email a { color: var(--cv-accent); text-decoration: none; }

  .cv-footer {
    text-align: center;
    margin-top: 3rem;
    padding-top: 1.25rem;
    border-top: 1px solid var(--cv-border);
    font-size: 0.85rem;
    color: var(--cv-muted);
  }
  .cv-footer a { color: var(--cv-accent); text-decoration: none; }

  @media (max-width: 700px) {
    .cv-metrics { grid-template-columns: repeat(2, 1fr); }
    .cv-grid-2 { grid-template-columns: 1fr; }
    .cv-entry .dates { float: none; display: block; }
  }

  @media print {
    .cv-download, .cv-nav { display: none !important; }
    .cv-wrap { max-width: 100%; padding: 0; }
    .cv-section { break-inside: avoid; }
    .cv-header { border-bottom: 2px solid #000; }
    .cv-metric, .cv-ref-card, .tag { border-color: #999 !important; background: #fff !important; }
  }
</style>

<div class="cv-wrap">

  <div class="cv-header">
    <h1>Dr. Krishna Kumar Yadav</h1>
    <div class="cv-title">Postdoctoral Researcher — Nanotechnology &amp; 2D Material Devices</div>
    <div class="cv-affil">Department of Fundamental Physics, University of Salamanca, Spain</div>
    <div class="cv-links">
      <a href="mailto:krishphy25@gmail.com">Email</a>|
      <a href="http://surl.li/fhzfyb" target="_blank" rel="noopener">Google Scholar</a>|
      <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" rel="noopener">ORCID</a>
    </div>
    <a class="cv-download" href="{{ '/assets/Krishna_Kumar_Yadav_CV.pdf' | relative_url }}" download>Download PDF ↓</a>
  </div>

  <div class="cv-section">
    <h2>Research Profile</h2>
    <p>
      I specialize in the synthesis, transfer, and device integration of 2D materials — including graphene and
      Transition Metal Dichalcogenides (TMDCs, e.g. MoTe₂, SnS₂) and black phosphorus — combined with advanced
      cleanroom nanofabrication and micro/nanolithography. My work focuses on optimizing device physics for
      high-performance optoelectronic devices, field-effect transistors (FETs), and planar terahertz detectors
      (log-periodic and bowtie antenna architectures). I also work on electrochemical sensing and
      electrocatalysis/energy-storage systems built on engineered nanomaterials.
    </p>
  </div>

  <div class="cv-section">
    <h2>Research Metrics</h2>
    <div class="cv-metrics">
      <div class="cv-metric"><span class="num">51</span><span class="label">Journal Articles</span></div>
      <div class="cv-metric"><span class="num">13</span><span class="label">Book Chapters</span></div>
      <div class="cv-metric"><span class="num">3</span><span class="label">Patents (2 Granted)</span></div>
      <div class="cv-metric"><span class="num">4</span><span class="label">Institutions / 3 Countries</span></div>
    </div>
  </div>

  <div class="cv-section">
    <h2>Research Positions</h2>

    <div class="cv-entry">
      <span class="dates">Sep 2024 – Present</span>
      <div class="role">Postdoctoral Researcher</div>
      <div class="org">Department of Fundamental Physics, University of Salamanca, Spain</div>
    </div>

    <div class="cv-entry">
      <span class="dates">Nov 2022 – Aug 2024</span>
      <div class="role">Postdoctoral Researcher</div>
      <div class="org">Shamoon College of Engineering, Beer-Sheva, Israel</div>
      <div class="desc">Dip-Pen Nanolithography printing over screen-printed electrodes for real-time electrochemical sensing of heavy metals.</div>
    </div>

    <div class="cv-entry">
      <span class="dates">Jun 2021 – Oct 2022</span>
      <div class="role">Institute Postdoctoral Fellow</div>
      <div class="org">Institute of Nano Science &amp; Technology (INST), Mohali, India</div>
      <div class="desc">Understanding the role of 2D materials for field emission.</div>
    </div>

    <div class="cv-entry">
      <span class="dates">Jan 2018 – Jun 2021</span>
      <div class="role">Senior Research Fellow (SRF), CSIR-India — Ph.D. Research</div>
      <div class="org">Institute of Nano Science &amp; Technology (INST), Mohali, India</div>
      <div class="desc">Ph.D. (2021): Nanostructured Metal Borides — Synthesis and Their Applications. Supervisors: Dr. Menaka Jha &amp; Prof. Ashok K. Ganguli.</div>
    </div>
  </div>

  <div class="cv-section">
    <h2>Selected First-Author Publications</h2>
    <ol class="cv-pub-list">
      <li>Krishna K. Yadav, et al. <strong>Room-Temperature Photodetector Performance of Monolayer 2H-MoTe₂: Effects of Trap Density and Contact Barrier.</strong> Submitted to <em>Small</em>. <span style="color:var(--cv-muted);">(under review)</span></li>
      <li>Krishna K. Yadav, et al. <strong>Robust Sliding-Induced Electrostatic Domain Patterns in Exfoliated ReS₂ Flakes.</strong> Submitted to <em>2D Materials</em>. <span style="color:var(--cv-muted);">(under review)</span></li>
      <li>Krishna K. Yadav, Dror Shamir, Haya Kornweitz, Lonia Friedlander, Moshe Zohar, Ariela Burg. <strong>Electrochemical Sensor Based on Black Phosphorus for Antimony Detection Using Dip-Pen Nanolithography: The Role of Dwell Time.</strong> <em>Small Methods</em>, 2025, 2402157. (IF ~9.1)</li>
      <li>Krishna K. Yadav, Sunaina, S. Saini, R. Wadhwa, S. Devi, S. Ghosh, M. Jha. <strong>Black Phosphorus/Dysprosium Hexaboride-Based Heterostructured Films for Field Emission Technologies.</strong> <em>ACS Applied Nano Materials</em>, 2024, 7, 9942–9949. (IF ~5.5)</li>
      <li>Krishna K. Yadav, R. Wadhwa, V.M. Gaikwad. <strong>Er₂FeCrO₆: Emerging Efficient Nanomaterials for Multiferroics.</strong> <em>Materials Chemistry and Physics</em>, 2024, 317, 129198. (IF ~4.7)</li>
      <li>Krishna K. Yadav, Dror Shamir, Haya Kornweitz, Yael Peled, Moshe Zohar, Ariela Burg. <strong>Development of Meta-Chemical Surface by Dip-Pen Nanolithography for Precise Electrochemical Lead Sensing.</strong> <em>Small Methods</em>, 2024, 8, 1–9. (IF ~9.1)</li>
      <li>Krishna K. Yadav, G. Kumar, S. Rana, S. Ghosh, M. Jha. <strong>Understanding the Role of Sheet Thickness on Field Emission from Engineered Hexagonal Tin Disulphide.</strong> <em>Applied Surface Science</em>, 2022, 606, 154816. (IF ~6.9)</li>
      <li>Krishna K. Yadav, Gulshan Kumar, Ankush, S. Ghosh, Menaka Jha. <strong>Design of a New Process for Stabilization of La<sub>x</sub>Gd<sub>1-x</sub>B₆ Nanorods and Their Field Emission Properties.</strong> <em>Materials Science and Engineering: B</em>, 2022, 282, 115759. (IF ~4.6)</li>
      <li>Krishna K. Yadav, Harish Singh, Supriya Rana, Sunaina, Heena Sammi, S.T. Nishanthi, Menaka Jha. <strong>Utilization of Waste Coir Fibre Architecture to Synthesize Porous Graphene Oxide and Their Derivatives.</strong> <em>Journal of Cleaner Production</em>, 2020, 276, 124240. (IF ~10)</li>
    </ol>
    <p style="font-size:0.9rem;"><a href="{{ '/publications/' | relative_url }}">→ View the complete list of 51 publications</a></p>
  </div>

  <div class="cv-section">
    <h2>Patents</h2>
    <ol class="cv-pub-list">
      <li>Santanu Sarkar, Tamal Kanti Ghosh, Supriya Sarkar, Menaka Jha, Sujeet Kumar, Kritika Sood, <strong>Krishna Yadav</strong>, Ankush. <em>A Process for Producing La₂FeMnO₆ from Iron Ore Slime and Applications Thereof.</em> Patent No. 482517 (Granted).</li>
      <li>Santanu Sarkar, Niloy Kundu, Tamal Kanti Ghosh, Menaka Jha, Sujit Ghuchait, <strong>Krishna Yadav</strong>, Sunaina, Arushi Arora. <em>Process of Preparing Silica-Iron Oxide from Iron Ore Slime.</em> Patent No. 577043 (Granted).</li>
      <li>Menaka Jha, Ritika Wadhwa, Sunaina, Ankush, <strong>Krishna Yadav</strong>, Sujit Kumar Guchhait. <em>Process of Conversion of Wastepaper to Nanostructured CaCO₃ and Their Application in De-fluorination of Contaminated Water.</em> Application No. 202311017356 (Filed).</li>
    </ol>
  </div>

  <div class="cv-section">
    <h2>Technical Skills</h2>
    <div class="cv-tags">
      <div class="tag-group">
        <h3>2D Material Synthesis &amp; Transfer</h3>
        <span class="tag">Graphene</span><span class="tag">TMDCs (MoTe₂, SnS₂)</span><span class="tag">Black Phosphorus</span><span class="tag">h-BN Heterostructures</span>
      </div>
      <div class="tag-group">
        <h3>Cleanroom Nanofabrication &amp; Lithography</h3>
        <span class="tag">Dip-Pen Nanolithography (DPN)</span><span class="tag">Optical Lithography</span><span class="tag">Wire Bonding</span>
      </div>
      <div class="tag-group">
        <h3>Device Physics &amp; Integration</h3>
        <span class="tag">FETs</span><span class="tag">Optoelectronic Devices</span><span class="tag">Engineered Metal Contacts</span><span class="tag">Planar THz Detectors (Log-Periodic / Bowtie)</span>
      </div>
      <div class="tag-group">
        <h3>Characterization</h3>
        <span class="tag">AFM (multi-mode)</span><span class="tag">Raman Spectroscopy</span><span class="tag">SEM</span><span class="tag">XRD / HT-XRD</span><span class="tag">Frictional Force &amp; Transverse Shear Microscopy</span>
      </div>
      <div class="tag-group">
        <h3>Sensing</h3>
        <span class="tag">Electrochemical Heavy-Metal Sensors</span><span class="tag">Field-Emission Sensing</span>
      </div>
      <div class="tag-group">
        <h3>Electrocatalysis &amp; Energy</h3>
        <span class="tag">Water Splitting</span><span class="tag">Supercapacitors</span><span class="tag">Photoelectrochemical Systems</span>
      </div>
    </div>
  </div>

  <div class="cv-section">
    <h2>Mentorship</h2>
    <div class="cv-entry">
      <div class="role">Rubén Bastida Vadillo</div>
      <div class="desc">2025–2026, TFG, Spain — Co-supervised with Ana Pérez Rodríguez. “Fabrication and Characterization of MoTe₂/NbSe₂ Heterostructures for High-Performance Photodetectors,” NanoLab, University of Salamanca.</div>
    </div>
    <div class="cv-entry">
      <div class="role">Alex Bellido Escribano</div>
      <div class="desc">2025–2026, TFG, Spain — Co-supervised with Mario Amado Montero. “New Techniques for Obtaining Ultrapure Graphene,” NanoLab, University of Salamanca.</div>
    </div>
    <div class="cv-entry">
      <div class="role">Ahmed Belal Salik Usmani</div>
      <div class="desc">Aug 2021 – May 2022, M.Tech Internship, with Dr. Menaka Jha. “Supercapacitive Performance of Graphene Derived from Waste Pine Tree Leaves,” INST, Mohali, India.</div>
    </div>
    <div class="cv-entry">
      <div class="role">Supriya Rana, Nausad Khan, Kritika Sood, Ritika Wadhwa (Ph.D. students, 2017–2021)</div>
      <div class="desc">Co-mentored with Dr. Menaka Jha, INST Mohali — topics spanning electrocatalytic Fe₂O₃, MoS₂ energy applications, valuable-materials recovery, and monoclinic zirconia photoelectrochemistry.</div>
    </div>
  </div>

  <div class="cv-section">
    <h2>References</h2>
    <div class="cv-grid-2">
      <div class="cv-ref-card">
        <div class="name">Prof. Ashok K. Ganguli</div>
        <div class="affil">Director, IISER Berhampur; Indian Institute of Technology, New Delhi, India</div>
        <div class="email"><a href="mailto:ashok@chemistry.iitd.ac.in">ashok@chemistry.iitd.ac.in</a></div>
      </div>
      <div class="cv-ref-card">
        <div class="name">Dr. Menaka Jha</div>
        <div class="affil">Scientist, Institute of Nano Science &amp; Technology, Mohali, India</div>
        <div class="email"><a href="mailto:menaka100jha@gmail.com">menaka100jha@gmail.com</a></div>
      </div>
      <div class="cv-ref-card">
        <div class="name">Prof. Ariela Burg</div>
        <div class="affil">Dept. of Chemical Engineering, Sami Shamoon College of Engineering, Beer-Sheva, Israel</div>
        <div class="email"><a href="mailto:arielab@sce.ac.il">arielab@sce.ac.il</a></div>
      </div>
      <div class="cv-ref-card">
        <div class="name">Prof. Dr. Enrique Díez Fernández</div>
        <div class="affil">Dept. of Fundamental Physics, University of Salamanca, Spain</div>
        <div class="email"><a href="mailto:enrisa@usal.es">enrisa@usal.es</a></div>
      </div>
    </div>
  </div>

  <div class="cv-footer">
    <p>Dr. Krishna Kumar Yadav — Department of Fundamental Physics, University of Salamanca, Spain</p>
    <p><a href="mailto:krishphy25@gmail.com">krishphy25@gmail.com</a> · <a href="http://surl.li/fhzfyb">Google Scholar</a> · <a href="https://orcid.org/0000-0002-9063-7851">ORCID</a></p>
  </div>

</div>
