---
layout: default
title: Publications
permalink: /publications/
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
.page-head{ max-width:900px; margin:44px auto 10px; padding:0 20px; }
.page-head h1{ font-size:34px; margin:0 0 6px; }
.page-head p{ color:var(--muted); margin:0; font-size:16.5px; }
.sub-nav{ max-width:900px; margin:10px auto 0; padding:0 20px; font-size:14.5px; }
.sub-nav a{ font-weight:600; text-decoration:none; margin-right:14px; }

/* SEARCH */
.search-container{ max-width:900px; margin:22px auto 6px; padding:0 20px; display:flex; gap:12px; flex-wrap:wrap; align-items:center; }
#pubSearch{ flex:1 1 300px; padding:12px 18px; font-size:15px; border-radius:8px; border:1px solid var(--border); outline:none; box-sizing:border-box; background:var(--bg-soft); }
#pubSearch:focus{ border-color:var(--accent); background:#fff; }
.ai-link{ font-size:14px; font-weight:600; text-decoration:none; white-space:nowrap; }

/* PUB LIST */
.pub-list-container{ max-width:900px; margin:0 auto; padding:0 20px; }
.year-head{ font-size:22px; margin:34px 0 12px; padding-bottom:6px; border-bottom:1px solid var(--border); }
.pub-card{ background:#fff; border:1px solid var(--border); border-radius:10px; padding:18px 20px; margin-bottom:12px; transition:border-color 0.15s; }
.pub-card:hover{ border-color:var(--accent); }
.article-title{ color:var(--heading); font-weight:700; font-size:16px; display:block; margin-bottom:6px; line-height:1.45; }
.article-authors{ font-size:13.5px; color:var(--muted); margin-bottom:4px; }
.article-journal{ font-style:italic; color:#3d4754; font-size:13.5px; }
.article-doi{ font-size:13px; margin-top:8px; display:inline-block; color:var(--accent); text-decoration:none; font-weight:600; }
.if-badge{ background:var(--bg-soft); color:var(--accent-dark); padding:2px 8px; border-radius:4px; font-size:11px; font-weight:700; border:1px solid var(--border); font-style:normal; }

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
  <h1>Peer-Reviewed Journal Articles</h1>
  <p>51 publications in international journals, sorted by year.</p>
</div>
<div class="sub-nav">Also see: <a href="/Book_Chapters/">Book Chapters</a> <a href="/patents/">Patents</a></div>

<div class="search-container">
  <input type="text" id="pubSearch" onkeyup="searchFunction()" placeholder="Search title, year, journal, or authors...">
  <a class="ai-link" href="https://notebooklm.google.com/notebook/8b8b0acb-21e5-4f16-9025-dfcc93980356" target="_blank" rel="noopener">Ask the AI assistant &rarr;</a>
</div>

<div class="pub-list-container" id="pubList">

  <h2 class="year-head" data-year-head>2026</h2>

  <div class="pub-card">
    <span class="article-title">Shape-induced manganese iron-based nanostructures loaded onto iron sheet as efficient electrocatalyst for O<sub>2</sub> evolution.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K. Yadav</b>, Menaka Jha</div>
    <div class="article-journal">Inorganic Chemistry Communications, 183, 115745 (2026) <span class="if-badge">IF 5.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.inoche.2025.115745" target="_blank" rel="noopener">DOI: 10.1016/j.inoche.2025.115745</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Enhanced photogenerated carrier assisted ethanol oxidation via surface modification with perovskite to develop pn type NiTiO<sub>3</sub>-NiO heterostructure.</span>
    <div class="article-authors">Ritika Wadhwa, Arushi Arora, Sushma Kumari, <b>Krishna K. Yadav</b>, Menaka Jha</div>
    <div class="article-journal">Materials Research Bulletin, 196, 113865 (2026) <span class="if-badge">IF 5.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.materresbull.2025.113865" target="_blank" rel="noopener">DOI: 10.1016/j.materresbull.2025.113865</a>
  </div>

  <h2 class="year-head" data-year-head>2025</h2>

  <div class="pub-card">
    <span class="article-title">Excellent Electrochemical Oxygen Production from Ultrafine Nanoparticles of Manganese Ferrite Spinel Derived from Spent Primary Battery.</span>
    <div class="article-authors">Sujit Kumar Guchhait, Supriya Rana, <b>Krishna K. Yadav</b>, Sushma Kumari, Surinder K. Mehta, Menaka Jha</div>
    <div class="article-journal">Energy Technology, 13, 2500985 (2025) <span class="if-badge">IF 3.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/ente.202500985" target="_blank" rel="noopener">DOI: 10.1002/ente.202500985</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Electrochemical Sensor Based on Black Phosphorus for Antimony Detection Using Dip-Pen Nanolithography: The Role of Dwell Time.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Dror Shamir, Haya Kornweitz, Lonia Friedlander, Moshe Zohar, Ariela Burg</div>
    <div class="article-journal">Small Methods, 2402157 (2025) <span class="if-badge">IF 9.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/smtd.202402157" target="_blank" rel="noopener">DOI: 10.1002/smtd.202402157</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Dip-Pen Nanolithography-Based Fabrication of Meta-Chemical Surface for Heavy Metal Detection: Role of Poly-Methyl Methacrylate in Sensor Sensitivity.</span>
    <div class="article-authors">Rahma Okbi, Mohammed Alkrenawi, <b>Krishna K. Yadav</b>, Dror Shamir, Haya Kornweitz, Yael Peled, Moshe Zohar, Ariela Burg</div>
    <div class="article-journal">Small Science, 5, 2400459 (2025) <span class="if-badge">IF 8.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/smsc.202400459" target="_blank" rel="noopener">DOI: 10.1002/smsc.202400459</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Harnessing the Potential of Dip-Pen Nanolithography to Pattern Meta-Chemical Surfaces with Glutathione Inks: An Electrochemical Sensor for Pb(II) and Hg(II).</span>
    <div class="article-authors">Zorik Shamish, <b>Krishna K. Yadav</b>, Haya Kornweitz, Moshe Zohar, Dror Shamir, Raz Jelinek, Ariela Burg</div>
    <div class="article-journal">Advanced Materials Interfaces, 2500295 (2025) <span class="if-badge">IF 4.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/admi.202500295" target="_blank" rel="noopener">DOI: 10.1002/admi.202500295</a>
  </div>

  <h2 class="year-head" data-year-head>2024</h2>

  <div class="pub-card">
    <span class="article-title">Black Phosphorus/Dysprosium Hexaboride-Based Heterostructured Films for Field Emission Technologies.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Sunaina, S. Saini, R. Wadhwa, S. Devi, S. Ghosh, M. Jha</div>
    <div class="article-journal">ACS Applied Nano Materials, 7, 9942&ndash;9949 (2024) <span class="if-badge">IF 5.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acsanm.3c06152" target="_blank" rel="noopener">DOI: 10.1021/acsanm.3c06152</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Er<sub>2</sub>FeCrO<sub>6</sub>: Emerging efficient nanomaterials for multiferroics.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, R. Wadhwa, V.M. Gaikwad</div>
    <div class="article-journal">Materials Chemistry and Physics, 317, 129198 (2024) <span class="if-badge">IF 4.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.matchemphys.2024.129198" target="_blank" rel="noopener">DOI: 10.1016/j.matchemphys.2024.129198</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Development of Meta-Chemical Surface by Dip-Pen Nanolithography for Precise Electrochemical Lead Sensing.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Dror Shamir, Haya Kornweitz, Yael Peled, Moshe Zohar, Ariela Burg</div>
    <div class="article-journal">Small Methods, 8, 1&ndash;9 (2024) <span class="if-badge">IF 9.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/smtd.202301118" target="_blank" rel="noopener">DOI: 10.1002/smtd.202301118</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Hierarchical nanostructure engineering of 3D nickel cobaltite ultrafine nanoparticles assemblies for synergistic electrocatalytic water and urea oxidation.</span>
    <div class="article-authors">S. Rana, S.K. Guchhait, <b>Krishna K. Yadav</b>, S. Devi, S.K. Mehta, M. Jha</div>
    <div class="article-journal">Journal of Electroanalytical Chemistry, 966, 118378 (2024) <span class="if-badge">IF 4.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jelechem.2024.118378" target="_blank" rel="noopener">DOI: 10.1016/j.jelechem.2024.118378</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Effect of Sol&ndash;Gel Silica Matrices on the Chemical Properties of Adsorbed/Entrapped Compounds.</span>
    <div class="article-authors">A. Burg, <b>Krishna K. Yadav</b>, D. Meyerstein, H. Kornweitz, D. Shamir, Y. Albo</div>
    <div class="article-journal">Gels, 10, 441 (2024) <span class="if-badge">IF 5.3</span></div>
    <a class="article-doi" href="https://doi.org/10.3390/gels10070441" target="_blank" rel="noopener">DOI: 10.3390/gels10070441</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Tailoring crystalline Mn<sub>5</sub>O<sub>8</sub> nanostructures: Kinetic control and stabilization for enhanced electrocatalytic O<sub>2</sub> evolution.</span>
    <div class="article-authors">Supriya Rana, Ahmed Belal Salik Usmani, Sapna Devi, Ritika Wadhwa, <b>Krishna K. Yadav</b>, Surinder K. Mehta, Menaka Jha</div>
    <div class="article-journal">Fuel, 367, 131485 (2024) <span class="if-badge">IF 7.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.fuel.2024.131485" target="_blank" rel="noopener">DOI: 10.1016/j.fuel.2024.131485</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Oxalate-mediated synthesis of hybrid nickel cobalt-based nanostructures for boosting water and urea electrooxidation efficiency.</span>
    <div class="article-authors">S. Rana, <b>Krishna K. Yadav</b>, S. Devi, S.K. Mehta, M. Jha</div>
    <div class="article-journal">Journal of Alloys and Compounds, 990, 174241 (2024) <span class="if-badge">IF 6.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jallcom.2024.174241" target="_blank" rel="noopener">DOI: 10.1016/j.jallcom.2024.174241</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Photoelectrochemical water oxidation reaction for coated and meta-chemical surface electrodes with Na<sub>3</sub>[Ru<sub>2</sub>(&mu;-CO<sub>3</sub>)<sub>4</sub>].</span>
    <div class="article-authors">S. Aharon, S.G. Patra, <b>Krishna K. Yadav</b>, Moshe Zohar, Dan Meyerstein, Eyal Tzur, Dror Shamir, Yael Albo, Ariela Burg</div>
    <div class="article-journal">International Journal of Hydrogen Energy, 72, 1058&ndash;1068 (2024) <span class="if-badge">IF 8.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.ijhydene.2024.05.475" target="_blank" rel="noopener">DOI: 10.1016/j.ijhydene.2024.05.475</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Enhanced electrochemical oxygen generation from sillenite phase of bismuth iron oxide (Bi<sub>24</sub>Fe<sub>2</sub>O<sub>39</sub>) ultrafine particles stabilised at room temperature.</span>
    <div class="article-authors">A. Arora, R. Wadhwa, <b>Krishna K. Yadav</b>, Ankush, M. Jha</div>
    <div class="article-journal">Journal of Electroanalytical Chemistry, 958, 118154 (2024) <span class="if-badge">IF 4.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jelechem.2024.118154" target="_blank" rel="noopener">DOI: 10.1016/j.jelechem.2024.118154</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Electrochemical Oxygen Generation from VO<sub>2</sub> Nanoflakes Decorated onto Graphite Sheet.</span>
    <div class="article-authors">A.B.S. Usmani, S. Rana, A. Arora, <b>Krishna K. Yadav</b>, H. Sammi, N. Sardana, M. Jha</div>
    <div class="article-journal">Journal of Alloys and Compounds, 976, 173058 (2024) <span class="if-badge">IF 6.3</span></div>
  </div>

  <div class="pub-card">
    <span class="article-title">Realizing ultralow overpotential during electrochemical hydrogen generation through photoexcitation of chromium disulphide.</span>
    <div class="article-authors">N. Khan, <b>Krishna K. Yadav</b>, R. Wadhwa, M. Jha</div>
    <div class="article-journal">International Journal of Hydrogen Energy, 56, 1294&ndash;1300 (2024) <span class="if-badge">IF 8.3</span></div>
  </div>

  <div class="pub-card">
    <span class="article-title">Polyoxometalate-Derived Cu-MoO<sub>2</sub> nanosheets as electrocatalyst for enhanced acidic water oxidation.</span>
    <div class="article-authors">Parul Sood, Krishankant, Harshita Bagdwal, Arti Joshi, <b>Krishna K. Yadav</b>, Chandan Bera, Monika Singh</div>
    <div class="article-journal">ACS Applied Nano Materials, 7, 69&ndash;76 (2024) <span class="if-badge">IF 5.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acsanm.3c05226" target="_blank" rel="noopener">DOI: 10.1021/acsanm.3c05226</a>
  </div>

  <h2 class="year-head" data-year-head>2023</h2>

  <div class="pub-card">
    <span class="article-title">Cobalt Decorated Graphitic Carbon Nitride Photoanode for Electrochemical Ethanol Oxidation: A Sustainable Way Towards Clean Energy.</span>
    <div class="article-authors">Ritika Wadhwa, <b>Krishna K. Yadav</b>, Ankush, Supriya Rana, Sunaina, Menaka Jha</div>
    <div class="article-journal">International Journal of Hydrogen Energy, 48, 29982&ndash;29995 (2023) <span class="if-badge">IF 8.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.ijhydene.2023.04.162" target="_blank" rel="noopener">DOI: 10.1016/j.ijhydene.2023.04.162</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Design of New Process to Utilize Stubble Char for Construction of M25 Concrete.</span>
    <div class="article-authors">S.K. Guchhait, <b>Krishna K. Yadav</b>, A. Yadav, R. Zutshi, N. Singh, M. Jha</div>
    <div class="article-journal">Advanced Materials Science and Technology, 5, 1&ndash;13 (2023)</div>
    <a class="article-doi" href="https://doi.org/10.37155/2717-526X-0502-4" target="_blank" rel="noopener">DOI: 10.37155/2717-526X-0502-4</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Efficient field emission from ultrafine nanostructured lanthanum sulphide synthesized by chemical route.</span>
    <div class="article-authors">Anima Mahajan, Nausad Khan, <b>Krishna K. Yadav</b>, Menaka Jha, S. Ghosh</div>
    <div class="article-journal">Applied Surface Science, 623, 156996 (2023) <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2023.156996" target="_blank" rel="noopener">DOI: 10.1016/j.apsusc.2023.156996</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Unravelling the behaviour of dual active sites of La<sub>2</sub>FeMnO<sub>6</sub> for electrochemical oxygen generation in alkaline conditions.</span>
    <div class="article-authors">Kritika Sood, <b>Krishna K. Yadav</b>, Kuldeep K. Bhasin, Tamal K. Ghosh, Santanu Sarkar, Menaka Jha</div>
    <div class="article-journal">Journal of Electroanalytical Chemistry, 938, 117449 (2023) <span class="if-badge">IF 4.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jelechem.2023.117449" target="_blank" rel="noopener">DOI: 10.1016/j.jelechem.2023.117449</a>
  </div>

  <h2 class="year-head" data-year-head>2022</h2>

  <div class="pub-card">
    <span class="article-title">Understanding the role of sheet thickness on field emission from engineered hexagonal tin disulphide.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, G. Kumar, S. Rana, S. Ghosh, M. Jha</div>
    <div class="article-journal">Applied Surface Science, 606, 154816 (2022) <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2022.154816" target="_blank" rel="noopener">DOI: 10.1016/j.apsusc.2022.154816</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Design of a new process for stabilization of La<sub>x</sub>Gd<sub>1-x</sub>B<sub>6</sub> nanorods and their Field Emission properties.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Gulshan Kumar, Ankush, S. Ghosh, Menaka Jha</div>
    <div class="article-journal">Materials Science and Engineering: B, 282, 115759 (2022) <span class="if-badge">IF 4.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.mseb.2022.115759" target="_blank" rel="noopener">DOI: 10.1016/j.mseb.2022.115759</a>
  </div>

  <div class="pub-card">
    <span class="article-title">An Insight of enhanced field emission from anisotropic La<sub>x</sub>Nd<sub>1-x</sub>B<sub>6</sub> nanostructures.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Ankush, Gulshan Kumar, Arushi Arora, S. Ghosh, Menaka Jha</div>
    <div class="article-journal">Materials Chemistry and Physics, 279, 125694 (2022) <span class="if-badge">IF 4.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.matchemphys.2021.125694" target="_blank" rel="noopener">DOI: 10.1016/j.matchemphys.2021.125694</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Conversion of Gaseous Effluents of Power Plant to Sodium Carbonate: A value-added material for powder detergent.</span>
    <div class="article-authors">Sujit K. Guchhait, <b>Krishna K. Yadav</b>, Shyam Khatana, Rajendra K. Saini, Upain K. Arora, Rajiv Satyakam, Ramesh Bajaj, Menaka Jha</div>
    <div class="article-journal">Cleaner Waste Systems, 3, 100042 (2022) <span class="if-badge">IF 3.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.clwas.2022.100042" target="_blank" rel="noopener">DOI: 10.1016/j.clwas.2022.100042</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Understanding the origin of ethanol oxidation from ultrafine nickel manganese oxide nanosheets derived from spent alkaline batteries.</span>
    <div class="article-authors">S. Devi, Sunaina, R. Wadhwa, <b>Krishna K. Yadav</b>, Menaka Jha</div>
    <div class="article-journal">Journal of Cleaner Production, 376, 134147 (2022) <span class="if-badge">IF 10</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jclepro.2022.134147" target="_blank" rel="noopener">DOI: 10.1016/j.jclepro.2022.134147</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Structurally engineered anisotropic Cobalt-based nanostructures for efficient chlorine and oxygen evolution.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K. Yadav</b>, Sunaina, Surinder K. Mehta, Menaka Jha</div>
    <div class="article-journal">Advanced Materials Interfaces, 9, 2200740 (2022) <span class="if-badge">IF 4.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/admi.202200740" target="_blank" rel="noopener">DOI: 10.1002/admi.202200740</a>
  </div>

  <div class="pub-card">
    <span class="article-title">One pot green method for fabrication of MoS<sub>2</sub> decorated graphite rods and their application in H<sub>2</sub> evolution.</span>
    <div class="article-authors">Nausad Khan, <b>Krishna K. Yadav</b>, Ritika Wadhwa, Ankush, Menaka Jha</div>
    <div class="article-journal">Materials Letters, 313, 131784 (2022) <span class="if-badge">IF 2.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.matlet.2022.131784" target="_blank" rel="noopener">DOI: 10.1016/j.matlet.2022.131784</a>
  </div>

  <h2 class="year-head" data-year-head>2021</h2>

  <div class="pub-card">
    <span class="article-title">Efficient metal-free supercapacitor based on graphene oxide derived from waste rice.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Ritika Wadhwa, Nausad Khan, Menaka Jha</div>
    <div class="article-journal">Current Research in Green and Sustainable Chemistry, 4, 100075 (2021)</div>
    <a class="article-doi" href="https://doi.org/10.1016/j.crgsc.2021.100075" target="_blank" rel="noopener">DOI: 10.1016/j.crgsc.2021.100075</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Surface phosphorization of nickel oxalate nanosheets to stabilize ultrathin nickel cyclo tetraphosphate nanosheets for efficient hydrogen generation.</span>
    <div class="article-authors">Ankush, <b>Krishna K. Yadav</b>, Sujit Kumar Guchhait, Menaka Jha</div>
    <div class="article-journal">Materials Research Bulletin, 139, 111275 (2021) <span class="if-badge">IF 5.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.materresbull.2021.111275" target="_blank" rel="noopener">DOI: 10.1016/j.materresbull.2021.111275</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Insights of enhanced oxygen evolution reaction of nanostructured cobalt ferrite surface.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K. Yadav</b>, Sujit Kumar Guchhait, S.T. Nishanthi, S.K. Mehta, Menaka Jha</div>
    <div class="article-journal">Journal of Materials Science, 56, 8383&ndash;8395 (2021) <span class="if-badge">IF 3.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1007/s10853-020-05629-9" target="_blank" rel="noopener">DOI: 10.1007/s10853-020-05629-9</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Excellent hydrogen generation from ultrathin nanosheets of cobalt cyclo tetraphosphate.</span>
    <div class="article-authors">Ankush, <b>Krishna K. Yadav</b>, Sujit Kumar Guchhait, Supriya Rana, Menaka Jha</div>
    <div class="article-journal">Materials Science and Engineering: B, 265, 114983 (2021) <span class="if-badge">IF 4.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.mseb.2020.114983" target="_blank" rel="noopener">DOI: 10.1016/j.mseb.2020.114983</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Mechanistic Insights for Photoelectrochemical Ethanol Oxidation on Black Gold Decorated Monoclinic Zirconia.</span>
    <div class="article-authors">Ritika Wadhwa, <b>Krishna K. Yadav</b>, Tanmay Goswami, Ankush, Sujit Kumar Guchhait, Sunaina, S.T. Nishanthi, Hirendra N. Ghosh, Menaka Jha</div>
    <div class="article-journal">ACS Applied Materials &amp; Interfaces, 13, 9942&ndash;9954 (2021) <span class="if-badge">IF 8.2</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acsami.0c21010" target="_blank" rel="noopener">DOI: 10.1021/acsami.0c21010</a>
  </div>

  <div class="pub-card">
    <span class="article-title">New hydrometallurgical approach to obtain uniform antiferromagnetic ferrous chloride cubes from waste tin cans.</span>
    <div class="article-authors">S.K. Guchhait, H. Sammi, <b>Krishna K. Yadav</b>, S. Rana, M. Jha</div>
    <div class="article-journal">Journal of Materials Science: Materials in Electronics, 32, 2965&ndash;2972 (2021) <span class="if-badge">IF 2.8</span></div>
    <a class="article-doi" href="https://doi.org/10.1007/s10854-020-05048-1" target="_blank" rel="noopener">DOI: 10.1007/s10854-020-05048-1</a>
  </div>

  <h2 class="year-head" data-year-head>2020</h2>

  <div class="pub-card">
    <span class="article-title">Utilization of waste coir fibre architecture to synthesize porous graphene oxide and their derivatives: An efficient energy storage material.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Harish Singh, Supriya Rana, Sunaina, Heena Sammi, S.T. Nishanthi, Menaka Jha</div>
    <div class="article-journal">Journal of Cleaner Production, 276, 124240 (2020) <span class="if-badge">IF 10</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jclepro.2020.124240" target="_blank" rel="noopener">DOI: 10.1016/j.jclepro.2020.124240</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Excellent Field Emission from Ultrafine Vertically Aligned Nanorods of NdB<sub>6</sub> on Silicon Substrate.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, M. Sreekanth, S. Ghosh, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Applied Surface Science, 526, 146652 (2020) <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2020.146652" target="_blank" rel="noopener">DOI: 10.1016/j.apsusc.2020.146652</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Extraction of nanostructured sodium nitrate from industrial effluent and their thermal properties.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, M. Sharma, Menaka Jha</div>
    <div class="article-journal">Water Environment Research, 92, 1123&ndash;1130 (2020) <span class="if-badge">IF 1.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/wer.1307" target="_blank" rel="noopener">DOI: 10.1002/wer.1307</a>
  </div>

  <div class="pub-card">
    <span class="article-title">A new Process for Stabilization of Vertically Aligned GdB<sub>6</sub> nanorods and their Field Emission Properties.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, M. Sreekanth, Ankush, S. Ghosh, Menaka Jha</div>
    <div class="article-journal">CrystEngComm, 22, 5473&ndash;5480 (2020) <span class="if-badge">IF 2.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1039/D0CE00591F" target="_blank" rel="noopener">DOI: 10.1039/D0CE00591F</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Low Temperature Hydrothermal Method for Synthesis of Fe<sub>2</sub>O<sub>3</sub> and their Oxygen Evolution Performance.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K. Yadav</b>, Kritika Sood, Ankush, S.K. Mehta, Menaka Jha</div>
    <div class="article-journal">Electroanalysis, 32, 2528&ndash;2534 (2020) <span class="if-badge">IF 2.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/elan.202060146" target="_blank" rel="noopener">DOI: 10.1002/elan.202060146</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Towards Novel Biocomposites from Unavoidable Food Supply Chain Wastes and Zirconia.</span>
    <div class="article-authors">Yang Gao, Fangru Xing, Menaka Jha, <b>Krishna K. Yadav</b>, Ranjana Yadav, Avtar S. Matharu</div>
    <div class="article-journal">ACS Sustainable Chemistry &amp; Engineering, 8, 14039&ndash;14046 (2020) <span class="if-badge">IF 7.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acssuschemeng.0c04211" target="_blank" rel="noopener">DOI: 10.1021/acssuschemeng.0c04211</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Mechanistic insights of enhanced photocatalytic efficiency of SnO<sub>2</sub>-SnS<sub>2</sub> heterostructures derived from partial sulphurization of SnO<sub>2</sub>.</span>
    <div class="article-authors">Sunaina, <b>Krishna K. Yadav</b>, S.K. Guchhait, K. Sood, S.K. Mehta, A.K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Separation and Purification Technology, 242, 116835 (2020) <span class="if-badge">IF 9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.seppur.2020.116835" target="_blank" rel="noopener">DOI: 10.1016/j.seppur.2020.116835</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Tuning the bandgap of m-ZrO<sub>2</sub> by incorporation of copper nanoparticles into the visible region for the treatment of organic pollutants.</span>
    <div class="article-authors">H. Singh, Sunaina, <b>Krishna K. Yadav</b>, V.K. Bajpai, Menaka Jha</div>
    <div class="article-journal">Materials Research Bulletin, 123, 110698 (2020) <span class="if-badge">IF 5.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.materresbull.2019.110698" target="_blank" rel="noopener">DOI: 10.1016/j.materresbull.2019.110698</a>
  </div>

  <h2 class="year-head" data-year-head>2019</h2>

  <div class="pub-card">
    <span class="article-title">Synthesis of zirconium diboride and its application in the protection of stainless-steel surfaces in harsh environment.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Sujit Kumar Guchhait, C.M. Hussain, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Solid-State Electrochemistry, 23, 3243&ndash;3253 (2019) <span class="if-badge">IF 2.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1007/s10008-019-04408-0" target="_blank" rel="noopener">DOI: 10.1007/s10008-019-04408-0</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Design of process for stabilization of La<sub>2</sub>NiMnO<sub>6</sub> nanorods and their magnetic properties.</span>
    <div class="article-authors">V.M. Gaikwad, <b>Krishna K. Yadav</b>, Sunaina, S. Chakraverty, S.E. Lofland, K.V. Ramanujachary, S.T. Nishanthi, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Magnetism and Magnetic Materials, 492, 165652 (2019) <span class="if-badge">IF 3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jmmm.2019.165652" target="_blank" rel="noopener">DOI: 10.1016/j.jmmm.2019.165652</a>
  </div>

  <div class="pub-card">
    <span class="article-title">New process for conversion of hazardous industrial effluent of ceramic industry into nanostructured sodium carbonate and their application in the textile industry.</span>
    <div class="article-authors">N. Dabas, <b>Krishna K. Yadav</b>, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Environmental Management, 240, 352&ndash;358 (2019) <span class="if-badge">IF 8.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jenvman.2019.03.066" target="_blank" rel="noopener">DOI: 10.1016/j.jenvman.2019.03.066</a>
  </div>

  <div class="pub-card">
    <span class="article-title">New sustainable and environmentally friendly process of synthesis of highly porous Mo<sub>2</sub>S<sub>3</sub> nanoflowers in cooking oil and their electrochemical properties.</span>
    <div class="article-authors">S.T. Nishanthi, <b>Krishna K. Yadav</b>, A. Baruah, A.K. Ganguli, M. Jha</div>
    <div class="article-journal">Electrochimica Acta, 300, 177&ndash;185 (2019) <span class="if-badge">IF 5.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.electacta.2019.01.091" target="_blank" rel="noopener">DOI: 10.1016/j.electacta.2019.01.091</a>
  </div>

  <div class="pub-card">
    <span class="article-title">New low temperature environmentally friendly process for the synthesis of tetragonal MoO<sub>2</sub> and its field emission properties.</span>
    <div class="article-authors">S.T. Nishanthi, A. Baruah, <b>Krishna K. Yadav</b>, D. Sarker, S. Ghosh, A.K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Applied Surface Science, 467, 1148&ndash;1156 (2019) <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2018.10.173" target="_blank" rel="noopener">DOI: 10.1016/j.apsusc.2018.10.173</a>
  </div>

  <div class="pub-card">
    <span class="article-title">New low-temperature process for stabilization of nanostructured La<sub>2</sub>NiMnO<sub>6</sub> and their magnetic properties.</span>
    <div class="article-authors">Vishwajit M. Gaikwad, <b>Krishna K. Yadav</b>, S.E. Lofland, Kandalam V. Ramanujachary, S. Chakraverty, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Magnetism and Magnetic Materials, 471, 8&ndash;13 (2019) <span class="if-badge">IF 3.0</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jmmm.2018.08.081" target="_blank" rel="noopener">DOI: 10.1016/j.jmmm.2018.08.081</a>
  </div>

  <div class="pub-card">
    <span class="article-title">Nanostructured silver decorated hollow silica and their application in the treatment of microbial contaminated water at room temperature.</span>
    <div class="article-authors">S.T. Nishanthi, <b>Krishna K. Yadav</b>, A. Baruah, K. Vaghasiya, R.K. Verma, A.K. Ganguli, Menaka Jha</div>
    <div class="article-journal">New Journal of Chemistry, 43, 8993&ndash;9001 (2019) <span class="if-badge">IF 2.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1039/C9NJ01049A" target="_blank" rel="noopener">DOI: 10.1039/C9NJ01049A</a>
  </div>

  <h2 class="year-head" data-year-head>2017</h2>

  <div class="pub-card">
    <span class="article-title">Low-temperature synthesis process of stabilization of cubic yttria stabilized zirconia spindles: an important high temperature ceramic material.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, A. Gupta, M. Sharma, N. Dabas, A.K. Ganguli, M. Jha</div>
    <div class="article-journal">Materials Research Express, 4, 105044 (2017) <span class="if-badge">IF 2.2</span></div>
    <a class="article-doi" href="https://doi.org/10.1088/2053-1591/aa9231" target="_blank" rel="noopener">DOI: 10.1088/2053-1591/aa9231</a>
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

<script>
function searchFunction() {
  var filter = document.getElementById('pubSearch').value.toUpperCase();
  var container = document.getElementById("pubList");
  var cards = container.getElementsByClassName('pub-card');
  for (var i = 0; i < cards.length; i++) {
    var text = cards[i].textContent || cards[i].innerText;
    cards[i].style.display = text.toUpperCase().indexOf(filter) > -1 ? "" : "none";
  }
  // Hide year headings when all their cards are hidden
  var heads = container.querySelectorAll('[data-year-head]');
  heads.forEach(function(head){
    var el = head.nextElementSibling, anyVisible = false;
    while (el && !el.hasAttribute('data-year-head')) {
      if (el.classList.contains('pub-card') && el.style.display !== 'none') { anyVisible = true; break; }
      el = el.nextElementSibling;
    }
    head.style.display = anyVisible ? "" : "none";
  });
}
</script>
