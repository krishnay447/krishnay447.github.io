---
layout: default
title: Publications
permalink: /publications/
---

<style>
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body{ background:var(--bg) !important; font-family: "Segoe UI", sans-serif; }

/* Hero Banner */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 20px;
  border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{ width:100%; height:260px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(28px,4vw,40px); font-weight:700; color:#fff;
  text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* Navigation Bar */
.nav-bar{
  text-align:center; padding:12px 0; background:#fff;
  border-bottom:2px solid var(--border); margin-bottom: 20px;
}
.nav-bar a{ color:var(--primary); text-decoration:none; font-weight:600; padding:0 8px; }
.nav-bar a:hover{ color:var(--primary-dark); text-decoration:underline; }

/* Dropdown */
.dropdown{ position:relative; display:inline-block; }
.dropdown-content{
  display:none; position:absolute; top:100%; left:0;
  background:#fff; min-width:230px; border:1px solid var(--border);
  border-radius:8px; box-shadow:0 8px 18px rgba(0,0,0,0.12); z-index:9999; text-align:left;
}
.dropdown:hover .dropdown-content{ display:block; }
.dropdown-content a{ display:block; padding:10px 16px; font-size:14px; color:var(--primary); text-decoration:none; border-bottom:1px solid #eee; }
.dropdown-content a:hover{ background:#eef6ff; }

/* Search Bar */
.search-container { max-width: 900px; margin: 25px auto; padding: 0 20px; }
#pubSearch {
  width: 100%; padding: 14px 25px; font-size: 16px; border-radius: 30px;
  border: 2px solid var(--border); outline: none; transition: 0.3s;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}
#pubSearch:focus { border-color: var(--primary); box-shadow: 0 4px 15px rgba(30, 136, 229, 0.15); }

/* Unified Publication Card Style */
.pub-list-container { max-width: 900px; margin: 0 auto; padding: 0 20px; }
.pub-card {
  background: #fff; padding: 20px; border-radius: 12px;
  border: 1px solid var(--border); margin-bottom: 15px; position: relative;
  transition: 0.3s; display: block;
}
.pub-card:hover { border-color: var(--primary); transform: translateY(-2px); box-shadow: 0 6px 15px rgba(0,0,0,0.08); }

.article-title { color: var(--primary-dark); font-weight: 700; font-size: 17px; display: block; margin-bottom: 8px; line-height: 1.4; }
.article-authors { font-size: 14px; color: #555; margin-bottom: 5px; }
.article-journal { font-style: italic; color: #444; font-size: 14px; }
.article-doi { font-size: 13px; margin-top: 8px; display: inline-block; color: var(--primary); text-decoration: none; font-weight: 600; }
.article-doi:hover { text-decoration: underline; }

.article-year-label { float: right; background: #e3f2fd; color: var(--primary); padding: 3px 10px; border-radius: 20px; font-size: 12px; font-weight: 700; border: 1px solid #bbdefb; }
.if-badge { background: #fff3e0; color: #e65100; padding: 2px 8px; border-radius: 4px; font-size: 11px; font-weight: 800; margin-left: 10px; border: 1px solid #ffe0b2; }

sub, sup { font-size: 0.75em; line-height: 0; position: relative; vertical-align: baseline; }
sub { bottom: -0.2em; }
sup { top: -0.4em; }
</style>

<div class="hero-header">
  <img src="/assets/header7.jpg" alt="Banner">
  <div class="hero-title">Knowledge Sharing</div>
</div>

<nav class="nav-bar">
  <a href="/">🏠 Home</a> |
  <a href="/experience/">🧪 Experience</a> |
  <a href="/impact/">🧭 Impact</a> |
  <span class="dropdown">
    <a class="dropdown-toggle" style="font-weight:700;">📚 Publications ▾</a>
    <span class="dropdown-content">
      <a href="/patents/">1. Patents</a>
      <a href="/Book_Chapters/">2. Chapters</a>
      <a href="/publications/">3. Articles</a>
    </span>
  </span> |
  <a href="/contact/">📬 Contact</a>
</nav>

<div class="search-container">
  <input type="text" id="pubSearch" onkeyup="searchFunction()" placeholder="🔍 Search Title, Year, Journal, or Authors...">
</div>

<div class="pub-list-container" id="pubList">
  <h2 style="border-left: 5px solid var(--primary); padding-left: 15px; margin-bottom: 25px; color: var(--primary-dark);">🔬 Peer‑Reviewed Journal Articles</h2>

  <div class="pub-card">
    <span class="article-year-label">2026</span>
    <span class="article-title">Shape-induced manganese iron-based nanostructures loaded onto iron sheet as efficient electrocatalyst for O<sub>2</sub> evolution.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K. Yadav</b>, Menaka Jha</div>
    <div class="article-journal">Inorganic Chemistry Communications, 183, 115745 <span class="if-badge">IF 5.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.inoche.2025.115745">DOI: 10.1016/j.inoche.2025.115745</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2025</span>
    <span class="article-title">Excellent Electrochemical Oxygen Production from Ultrafine Nanoparticles of Manganese Ferrite Spinel Derived from Spent Primary Battery.</span>
    <div class="article-authors">Sujit Kumar Guchhait, Supriya Rana, <b>Krishna K Yadav</b>, Sushma Kumari, Surinder K Mehta, Menaka Jha</div>
    <div class="article-journal">Energy Technology, 13, 2500985 <span class="if-badge">IF 3.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/ente.202500985">DOI: 10.1002/ente.202500985</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2026</span>
    <span class="article-title">Enhanced photogenerated carrier assisted ethanol oxidation via surface modification with perovskite to develop pn type NiTiO<sub>3</sub>-NiO heterostructure.</span>
    <div class="article-authors">Ritika Wadhwa, Arushi Arora, Sushma Kumari, <b>Krishna K Yadav</b>, Menaka Jha</div>
    <div class="article-journal">Materials Research Bulletin, 196, 113865 <span class="if-badge">IF 5.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.materresbull.2025.113865">DOI: 10.1016/j.materresbull.2025.113865</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2025</span>
    <span class="article-title">Electrochemical Sensor Based on Black Phosphorus for Antimony Detection Using Dip-Pen Nanolithography: The Role of Dwell Time.</span>
    <div class="article-authors"><b>Krishna K. Yadav</b>, Dror Shamir, Haya Kornweitz, Lonia Friedlander, Moshe Zohar, Ariela Burg</div>
    <div class="article-journal">Small Methods, 2402157 <span class="if-badge">IF 9.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/smtd.202402157">DOI: 10.1002/smtd.202402157</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Black Phosphorus/Dysprosium Hexaboride-Based Heterostructured Films for Field Emission Technologies.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Sunaina, S Saini, R Wadhwa, S Devi, S Ghosh, M Jha</div>
    <div class="article-journal">ACS Applied Nano Materials, 7, 9942-9949 <span class="if-badge">IF 5.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acsanm.3c06152">DOI: 10.1021/acsanm.3c06152</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Er<sub>2</sub>FeCrO<sub>6</sub>: Emerging efficient nanomaterials for multiferroics.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, R Wadhwa, VM Gaikwad</div>
    <div class="article-journal">Materials Chemistry and Physics, 317, 129198 <span class="if-badge">IF 4.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.matchemphys.2024.129198">DOI: 10.1016/j.matchemphys.2024.129198</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Development of Meta-Chemical Surface by Dip-Pen Nanolithography for Precise Electrochemical Lead Sensing.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Dror Shamir, Haya Kornweitz, Yael Peled, Moshe Zohar, Ariela Burg</div>
    <div class="article-journal">Small Methods, 8, 1-9 <span class="if-badge">IF 9.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/smtd.202301118">DOI: 10.1002/smtd.202301118</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">Understanding the role of sheet thickness on field emission from engineered hexagonal tin disulphide.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, G Kumar, S Rana, S Ghosh, M Jha</div>
    <div class="article-journal">Applied Surface Science, 606, 154816 <span class="if-badge">IF 6.9</span></div>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">Design of a new process for stabilization of La<sub>x</sub>Gd<sub>1-x</sub>B<sub>6</sub> nanorods and their Field Emission properties.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Gulshan Kumar, Ankush, S. Ghosh, and Menaka Jha</div>
    <div class="article-journal">Materials Science and Engineering: B, 282, 115759 <span class="if-badge">IF 4.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2022.154816">DOI: 10.1016/j.apsusc.2022.154816</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">An Insight of enhanced field emission from anisotropic La<sub>x</sub>Nd<sub>1-x</sub>B<sub>6</sub> nanostructures.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Ankush, Gulshan Kumar, Arushi Arora, S. Ghosh, Menaka Jha</div>
    <div class="article-journal">Materials Chemistry and Physics, 279, 125694 <span class="if-badge">IF 4.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.matchemphys.2021.125694">DOI: 10.1016/j.matchemphys.2021.125694</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2021</span>
    <span class="article-title">Efficient metal-free supercapacitor based on graphene oxide derived from waste rice.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Ritika Wadhwa, Nausad Khan, Menaka Jha</div>
    <div class="article-journal">Current Research in Green and Sustainable Chemistry, 4, 100075</div>
    <a class="article-doi" href="https://doi.org/10.1016/j.crgsc.2021.100075">DOI: 10.1016/j.crgsc.2021.100075</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Utilization of waste coir fibre architecture to synthesize porous graphene oxide and their derivatives: An efficient energy storage material.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Harish Singh, Supriya Rana, Sunaina, Heena Sammi, S.T. Nishanthi and Menaka Jha</div>
    <div class="article-journal">Journal of Cleaner Production, 276, 124240 <span class="if-badge">IF 10</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jclepro.2020.124240">DOI: 10.1016/j.jclepro.2020.124240</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Excellent Field Emission from Ultrafine Vertically Aligned Nanorods of NdB<sub>6</sub> on Silicon Substrate.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, M Sreekanth, S Ghosh, Ashok K Ganguli, Menaka Jha</div>
    <div class="article-journal">Applied Surface Science, 526, 146652 <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2020.146652">DOI: 10.1016/j.apsusc.2020.146652</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Extraction of nanostructured sodium nitrate from industrial effluent and their thermal properties.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, M Sharma, Menaka Jha</div>
    <div class="article-journal">Water Environment Research, 92, 1123–1130 <span class="if-badge">IF 1.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/wer.1307">DOI: 10.1002/wer.1307</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">A new Process for Stabilization of Vertically Aligned GdB<sub>6</sub> nanorods and their Field Emission Properties.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, M. Sreekanth, Ankush, S. Ghosh, Menaka Jha</div>
    <div class="article-journal">CrystEngComm, 22, 5473-5480 <span class="if-badge">IF 2.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1039/D0CE00591F">DOI: 10.1039/D0CE00591F</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">Synthesis of zirconium diboride and its application in the protection of stainless-steel surfaces in harsh environment.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, Sujit Kumar Guchhait, CM Hussain, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Solid-State Electrochemistry, 23, 3243-3253 <span class="if-badge">IF 2.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1007/s10008-019-04408-0">DOI: 10.1007/s10008-019-04408-0</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2017</span>
    <span class="article-title">Low-temperature synthesis process of stabilization of cubic yttria stabilized zirconia spindles: an important high temperature ceramic material.</span>
    <div class="article-authors"><b>Krishna K Yadav</b>, A Gupta, M Sharma, N Dabas, AK Ganguli, M Jha</div>
    <div class="article-journal">Materials Research Express, 4, 105044 <span class="if-badge">IF 2.2</span></div>
    <a class="article-doi" href="https://doi.org/10.1088/2053-1591/aa9231">DOI: 10.1088/2053-1591/aa9231</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2025</span>
    <span class="article-title">Dip‐Pen Nanolithography‐Based Fabrication of Meta‐Chemical Surface for Heavy Metal Detection: Role of Poly‐Methyl Methacrylate in Sensor Sensitivity.</span>
    <div class="article-authors">Rahma Okbi, Mohammed Alkrenawi, <b>Krishna K. Yadav</b>, Dror Shamir, Haya Kornweitz, Yael Peled, Moshe Zohar, Ariela Burg</div>
    <div class="article-journal">Small Sciences, 5, 2400459 <span class="if-badge">IF 8.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/smsc.202400459">DOI: 10.1002/smsc.202400459</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2025</span>
    <span class="article-title">Harnessing the Potential of Dip-Pen Nanolithography to Pattern Meta-Chemical Surfaces with Glutathione Inks: An Electrochemical Sensor for Pb(II) and Hg(II).</span>
    <div class="article-authors">Zorik Shamish, <b>Krishna K. Yadav</b>, Haya Kornweitz, Moshe Zohar, Dror Shamir, Raz Jelinek, Ariela Burg</div>
    <div class="article-journal">Advanced Materials Interfaces, 2500295 <span class="if-badge">IF 4.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/admi.202500295">DOI: 10.1002/admi.202500295</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Hierarchical nanostructure engineering of 3D nickel cobaltite ultrafine nanoparticles assemblies for synergistic electrocatalytic water and urea oxidation.</span>
    <div class="article-authors">S Rana, SK Guchhait, <b>Krishna K Yadav</b>, S Devi, SK Mehta, M Jha</div>
    <div class="article-journal">Journal of Electroanalytical Chemistry, 966, 118378 <span class="if-badge">IF 4.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jelechem.2024.118378">DOI: 10.1016/j.jelechem.2024.118378</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Effect of Sol–Gel Silica Matrices on the Chemical Properties of Adsorbed/Entrapped Compounds.</span>
    <div class="article-authors">A Burg, <b>Krishna K Yadav</b>, D Meyerstein, H Kornweitz, D Shamir, Y Albo</div>
    <div class="article-journal">Gels, 10, 441 <span class="if-badge">IF 5.3</span></div>
    <a class="article-doi" href="https://doi.org/10.3390/gels10070441">DOI: 10.3390/gels10070441</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Tailoring crystalline Mn<sub>5</sub>O<sub>8</sub> nanostructures: Kinetic control and stabilization for enhanced electrocatalytic O<sub>2</sub> evolution.</span>
    <div class="article-authors">Supriya Rana, Ahmed Belal Salik Usmani, Sapna Devi, Ritika Wadhwa, <b>Krishna K. Yadav</b>, Surinder.K. Mehta, Menaka Jha</div>
    <div class="article-journal">Fuel, 367, 131485 <span class="if-badge">IF 7.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.fuel.2024.131485">DOI: 10.1016/j.fuel.2024.131485</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Oxalate-mediated synthesis of hybrid nickel cobalt-based nanostructures for boosting water and urea electrooxidation efficiency.</span>
    <div class="article-authors">S Rana, <b>Krishna K Yadav</b>, S Devi, SK Mehta, M Jha</div>
    <div class="article-journal">Journal of Alloys and Compounds, 990, 174241 <span class="if-badge">IF 6.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jallcom.2024.174241">DOI: 10.1016/j.jallcom.2024.174241</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Photoelectrochemical water oxidation reaction for coated and meta-chemical surface electrodes with Na<sub>3</sub>[Ru<sub>2</sub>(μ-CO<sub>3</sub>)<sub>4</sub>].</span>
    <div class="article-authors">S Aharon, SG Patra, <b>Krishna K Yadav</b>, Moshe Zohar, Dan Meyerstein, Eyal Tzur, Dror Shamir, Yael Albo, Ariela Burg</div>
    <div class="article-journal">International Journal of Hydrogen Energy, 72, 1058-1068 <span class="if-badge">IF 8.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.ijhydene.2024.05.475">DOI: 10.1016/j.ijhydene.2024.05.475</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Enhanced electrochemical oxygen generation from sillenite phase of bismuth iron oxide (Bi<sub>24</sub>Fe<sub>2</sub>O<sub>39</sub>) ultrafine particles stabilised at room temperature.</span>
    <div class="article-authors">A Arora, R Wadhwa, <b>Krishna K Yadav</b>, Ankush, M Jha</div>
    <div class="article-journal">Journal of Electroanalytical Chemistry, 958, 118154 <span class="if-badge">IF 4.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jelechem.2024.118154">DOI: 10.1016/j.jelechem.2024.118154</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Electrochemical Oxygen Generation from VO<sub>2</sub> Nanoflakes Decorated onto Graphite Sheet.</span>
    <div class="article-authors">ABS Usmani, S Rana, A Arora, <b>Krishna K Yadav</b>, H Sammi, N Sardana, M Jha</div>
    <div class="article-journal">Journal of Alloys and Compounds, 976, 173058 <span class="if-badge">IF 6.3</span></div>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Realizing ultralow overpotential during electrochemical hydrogen generation through photoexcitation of chromium disulphide.</span>
    <div class="article-authors">N Khan, <b>Krishna K Yadav</b>, R Wadhwa, M Jha</div>
    <div class="article-journal">International Journal of Hydrogen Energy, 56, 1294-1300 <span class="if-badge">IF 8.3</span></div>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2024</span>
    <span class="article-title">Polyoxometalate-Derived Cu-MoO<sub>2</sub> nanosheets as electrocatalyst for enhanced acidic water oxidation.</span>
    <div class="article-authors">Parul Sood, Krishankant, Harshita Bagdwal, Arti Joshi, <b>Krishna K. Yadav</b>, Chandan Bera, Monika Singh</div>
    <div class="article-journal">ACS Applied Nano Materials, 7, 69–76 <span class="if-badge">IF 5.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acsanm.3c05226">DOI: 10.1021/acsanm.3c05226</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2023</span>
    <span class="article-title">Cobalt Decorated Graphitic Carbon Nitride Photoanode for Electrochemical Ethanol Oxidation: A Sustainable Way Towards Clean Energy.</span>
    <div class="article-authors">Ritika Wadhwa, <b>Krishna K Yadav</b>, Ankush, Supriya Rana, Sunaina, Menaka Jha</div>
    <div class="article-journal">International Journal of Hydrogen Energy, 48, 29982-29995 <span class="if-badge">IF 8.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.ijhydene.2023.04.162">DOI: 10.1016/j.ijhydene.2023.04.162</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2023</span>
    <span class="article-title">Design of New Process to Utilize Stubble Char for Construction of M25 Concrete.</span>
    <div class="article-authors">SK Guchhait, <b>Krishna K Yadav</b>, A Yadav, R Zutshi, N Singh, M Jha</div>
    <div class="article-journal">Advanced Materials Science and Technology, 5, 1-13</div>
    <a class="article-doi" href="https://doi.org/10.37155/2717-526X-0502-4">DOI: 10.37155/2717-526X-0502-4</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2023</span>
    <span class="article-title">Efficient field emission from ultrafine nanostructured lanthanum sulphide synthesized by chemical route.</span>
    <div class="article-authors">Anima Mahajan, Nausad Khan, <b>Krishna K Yadav</b>, Menaka Jha and S. Ghosh</div>
    <div class="article-journal">Applied Surface Science, 623, 156996 <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2023.156996">DOI: 10.1016/j.apsusc.2023.156996</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2023</span>
    <span class="article-title">Unravelling the behaviour of dual active sites of La<sub>2</sub>FeMnO<sub>6</sub> for electrochemical oxygen generation in alkaline conditions.</span>
    <div class="article-authors">Kritika Sood, <b>Krishna K Yadav</b>, Kuldeep K Bhasin, Tamal K Ghosh, Santanu Sarkar, Menaka Jha</div>
    <div class="article-journal">Journal of Electroanalytical Chemistry, 938, 117449 <span class="if-badge">IF 4.1</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jelechem.2023.117449">DOI: 10.1016/j.jelechem.2023.117449</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">Conversion of Gaseous Effluents of Power Plant to Sodium Carbonate: A value-added material for powder detergent.</span>
    <div class="article-authors">Sujit K. Guchhait, <b>Krishna K Yadav</b>, Shyam Khatana, Rajendra K Saini, Upain K Arora, Rajiv Satyakam, Ramesh Bajaj, Menaka Jha</div>
    <div class="article-journal">Cleaner Waste Systems, 3, 100042 <span class="if-badge">IF 3.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.clwas.2022.100042">DOI: 10.1016/j.clwas.2022.100042</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">Understanding the origin of ethanol oxidation from ultrafine nickel manganese oxide nanosheets derived from spent alkaline batteries.</span>
    <div class="article-authors">S Devi, Sunaina, R Wadhwa, <b>Krishna K Yadav</b>, Menaka Jha</div>
    <div class="article-journal">Journal of Cleaner Production, 376, 134147 <span class="if-badge">IF 10</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jclepro.2022.134147">DOI: 10.1016/j.jclepro.2022.134147</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">Structurally engineered anisotropic Cobalt-based nanostructures for efficient chlorine and oxygen evolution.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K Yadav</b>, Sunaina, Surinder. K. Mehta and Menaka Jha</div>
    <div class="article-journal">Advanced Materials Interfaces, 9, 2200740 <span class="if-badge">IF 4.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/admi.202200740">DOI: 10.1002/admi.202200740</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2022</span>
    <span class="article-title">One pot green method for fabrication of MoS<sub>2</sub> decorated graphite rods and their application in H<sub>2</sub> evolution.</span>
    <div class="article-authors">Nausad Khan, <b>Krishna K Yadav</b>, Ritika Wadhwa, Ankush, and Menaka Jha</div>
    <div class="article-journal">Materials Letters, 313, 131784 <span class="if-badge">IF 2.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.matlet.2022.131784">DOI: 10.1016/j.matlet.2022.131784</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2021</span>
    <span class="article-title">Surface phosphorization of nickel oxalate nanosheets to stabilize ultrathin nickel cyclo tetraphosphate nanosheets for efficient hydrogen generation.</span>
    <div class="article-authors">Ankush, <b>Krishna K Yadav</b>, Sujit Kumar Guchhait, Menaka Jha</div>
    <div class="article-journal">Materials Chemistry and Physics, 139, 111275 <span class="if-badge">IF 4.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.materresbull.2021.111275">DOI: 10.1016/j.materresbull.2021.111275</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2021</span>
    <span class="article-title">Insights of enhanced oxygen evolution reaction of nanostructured cobalt ferrite surface.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K Yadav</b>, Sujit Kumar Guchhait, S. T. Nishanthi, S. K. Mehta, Menaka Jha</div>
    <div class="article-journal">Journal of Materials Science, 56, 8383–8395 <span class="if-badge">IF 3.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1007/s10853-020-05629-9">DOI: 10.1007/s10853-020-05629-9</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2021</span>
    <span class="article-title">Excellent hydrogen generation from ultrathin nanosheets of cobalt cyclo tetraphosphate.</span>
    <div class="article-authors">Ankush, <b>Krishna K Yadav</b>, Sujit Kumar Guchhait, Supriya Rana, Menaka Jha</div>
    <div class="article-journal">Materials Science and Engineering: B, 265, 114983 <span class="if-badge">IF 4.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.mseb.2020.114983">DOI: 10.1016/j.mseb.2020.114983</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2021</span>
    <span class="article-title">Mechanistic Insights for Photoelectrochemical Ethanol Oxidation on Black Gold Decorated Monoclinic Zirconia.</span>
    <div class="article-authors">Ritika Wadhwa, <b>Krishna K Yadav</b>, Tanmay Goswami, Ankush, Sujit Kumar Guchhait, Sunaina, S.T. Nishanthi, Hirendra N. Ghosh, Menaka Jha</div>
    <div class="article-journal">ACS Applied Materials & Interfaces, 13, 9942–9954 <span class="if-badge">IF 8.2</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acsami.0c21010">DOI: 10.1021/acsami.0c21010</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2021</span>
    <span class="article-title">New hydrometallurgical approach to obtain uniform antiferromagnetic ferrous chloride cubes from waste tin cans.</span>
    <div class="article-authors">SK Guchhait, H Sammi, <b>Krishna K Yadav</b>, S Rana, M Jha</div>
    <div class="article-journal">Journal of Materials Science: Materials in Electronics, 32, 2965-2972 <span class="if-badge">IF 2.8</span></div>
    <a class="article-doi" href="https://doi.org/10.1007/s10854-020-05048-1">DOI: 10.1007/s10854-020-05048-1</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Low Temperature Hydrothermal Method for Synthesis of Fe<sub>2</sub>O<sub>3</sub> and their Oxygen Evolution Performance.</span>
    <div class="article-authors">Supriya Rana, <b>Krishna K Yadav</b>, Kritika Sood, Ankush, S. K. Mehta, Menaka Jha</div>
    <div class="article-journal">Electroanalysis, 32, 2528–2534 <span class="if-badge">IF 2.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1002/elan.202060146">DOI: 10.1002/elan.202060146</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Towards Novel Biocomposites from Unavoidable Food Supply Chain Wastes and Zirconia.</span>
    <div class="article-authors">Yang Gao, Fangru Xing, Menaka Jha, <b>Krishna K Yadav</b>, Ranjana Yadav, and Avtar S. Matharu</div>
    <div class="article-journal">ACS Sustainable Chemistry & Engineering, 8, 14039–14046 <span class="if-badge">IF 7.3</span></div>
    <a class="article-doi" href="https://doi.org/10.1021/acssuschemeng.0c04211">DOI: 10.1021/acssuschemeng.0c04211</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Mechanistic insights of enhanced photocatalytic efficiency of SnO<sub>2</sub>-SnS<sub>2</sub> heterostructures derived from partial sulphurization of SnO<sub>2</sub>.</span>
    <div class="article-authors">Sunaina, <b>Krishna K Yadav</b>, SK Guchhait, K Sood, SK Mehta, AK Ganguli, Menaka Jha</div>
    <div class="article-journal">Separation and Purification Technology, 242, 116835 <span class="if-badge">IF 9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.seppur.2020.116835">DOI: 10.1016/j.seppur.2020.116835</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2020</span>
    <span class="article-title">Tuning the bandgap of m-ZrO<sub>2</sub> by incorporation of copper nanoparticles into the visible region for the treatment of organic pollutants.</span>
    <div class="article-authors">H Singh, Sunaina, <b>Krishna K Yadav</b>, VK Bajpai, Menaka Jha</div>
    <div class="article-journal">Materials Research Bulletin, 123, 110698 <span class="if-badge">IF 5.7</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.materresbull.2019.110698">DOI: 10.1016/j.materresbull.2019.110698</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">Design of process for stabilization of La<sub>2</sub>NiMnO<sub>6</sub> nanorods and their magnetic properties.</span>
    <div class="article-authors">VM Gaikwad, <b>Krishna K Yadav</b>, Sunaina, S Chakraverty, SE Lofland, KV Ramanujachary, ST Nishanthi, Ashok K Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Magnetism and Magnetic Materials, 492, 165652 <span class="if-badge">IF 3</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jmmm.2019.165652">DOI: 10.1016/j.jmmm.2019.165652</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">New process for conversion of hazardous industrial effluent of ceramic industry into nanostructured sodium carbonate and their application in the textile industry.</span>
    <div class="article-authors">N Dabas, <b>Krishna K Yadav</b>, Ashok K Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Environmental Management, 240, 352–358 <span class="if-badge">IF 8.4</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jenvman.2019.03.066">DOI: 10.1016/j.jenvman.2019.03.066</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">New sustainable and environmentally friendly process of synthesis of highly porous Mo<sub>2</sub>S<sub>3</sub> nanoflowers in cooking oil and their electrochemical properties.</span>
    <div class="article-authors">ST Nishanthi, <b>Krishna K Yadav</b>, A Baruah, AK Ganguli, M Jha</div>
    <div class="article-journal">Electrochimica Acta, 300, 177-185 <span class="if-badge">IF 5.6</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.electacta.2019.01.091">DOI: 10.1016/j.electacta.2019.01.091</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">New low temperature environmentally friendly process for the synthesis of tetragonal MoO<sub>2</sub> and its field emission properties.</span>
    <div class="article-authors">ST Nishanthi, A Baruah, <b>Krishna K Yadav</b>, D Sarker, S Ghosh, AK Ganguli, Menaka Jha</div>
    <div class="article-journal">Applied Surface Science, 467, 1148-1156 <span class="if-badge">IF 6.9</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.apsusc.2018.10.173">DOI: 10.1016/j.apsusc.2018.10.173</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">New low-temperature process for stabilization of nanostructured La<sub>2</sub>NiMnO<sub>6</sub> and their magnetic properties.</span>
    <div class="article-authors">Vishwajit M. Gaikwad, <b>Krishna K Yadav</b>, S. E. Lofland, Kandalam V. Ramanujachary, S. Chakraverty, Ashok K. Ganguli, Menaka Jha</div>
    <div class="article-journal">Journal of Magnetism and Magnetic Materials, 471, 8-13 <span class="if-badge">IF 3.0</span></div>
    <a class="article-doi" href="https://doi.org/10.1016/j.jmmm.2018.08.081">DOI: 10.1016/j.jmmm.2018.08.081</a>
  </div>

  <div class="pub-card">
    <span class="article-year-label">2019</span>
    <span class="article-title">Nanostructured silver decorated hollow silica and their application in the treatment of microbial contaminated water at room temperature.</span>
    <div class="article-authors">ST Nishanthi, <b>Krishna K Yadav</b>, A Baruah, K Vaghasiya, RK Verma, AK Ganguli, Menaka Jha</div>
    <div class="article-journal">New Journal of Chemistry, 43 (23), 8993-9001 <span class="if-badge">IF 2.5</span></div>
    <a class="article-doi" href="https://doi.org/10.1039/C9NJ01049A">DOI: 10.1039/C9NJ01049A</a>
  </div>

</div>
<hr style="margin: 30px 0; opacity: 0.5;">
<div align="center">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
</div>

<script>
function searchFunction() {
  var input = document.getElementById("pubSearch").value.toUpperCase();
  var cards = document.getElementsByClassName("pub-card");

  for (var i = 0; i < cards.length; i++) {
    var content = cards[i].textContent || cards[i].innerText;
    if (content.toUpperCase().indexOf(input) > -1) {
      cards[i].style.display = "";
    } else {
      cards[i].style.display = "none";
    }
  }
}
</script>
