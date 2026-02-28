---
layout: default
title: Patents
permalink: /patents/
---

<style>
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body{ background:var(--bg) !important; }

/* HERO */
.hero-header{
  position:relative;
  width:100%;
  max-width:1150px;
  margin:0 auto 20px;
  border-radius:14px;
  overflow:hidden;
  box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{
  width:100%;
  height:260px;
  object-fit:cover;
  display:block;
}
.hero-title{
  position:absolute; inset:0;
  display:flex; align-items:center; justify-content:center;
  font-family:"Segoe UI", Roboto, sans-serif;
  font-size:clamp(28px,4vw,40px);
  font-weight:700; color:white;
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.2));
  text-shadow:0 3px 10px rgba(0,0,0,0.55);
}

/* NAVIGATION (Instrumentation removed) */
.nav-bar {
  text-align: center; padding: 12px 0; background: #ffffff;
  border-bottom: 3px solid var(--border); box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  font-family: "Segoe UI", sans-serif; position: sticky; top: 0; z-index: 10000;
}
.nav-bar a, .dropdown-toggle {
  color: #444; text-decoration: none; font-weight: 600; padding: 8px 16px;
  margin: 0 4px; border-radius: 8px; transition: all 0.3s ease;
  display: inline-block; font-size: 15px; cursor: pointer;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background-color: #e3f2fd; color: var(--primary-dark); }

/* DROPDOWN */
.dropdown { position: relative; display: inline-block; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
  background: #ffffff; min-width: 250px; border-radius: 12px; border: 1px solid var(--border);
  box-shadow: 0 10px 30px rgba(0,0,0,0.15); z-index: 9999; overflow: hidden; margin-top: 5px;
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-content a { 
  display: block; padding: 12px 20px; border-bottom: 1px solid #f0f0f0; 
  text-align: left; font-size: 14px; color: #444; text-decoration: none;
}
.dropdown-content a:hover { background: #eef6ff; color: var(--primary-dark); }

.markdown-body{ overflow:visible !important; }

/* PATENT STYLING */
.patent-card {
  background: #fff; padding: 20px; border-radius: 12px; 
  border: 1px solid var(--border); margin-bottom: 20px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.03);
}
.patent-tag {
  display: inline-block; padding: 4px 10px; border-radius: 6px;
  font-size: 11px; font-weight: 700; text-transform: uppercase;
  margin-bottom: 10px;
}
.granted { background: #e8f5e9; color: #2e7d32; }
.pending { background: #fff3e0; color: #ef6c00; }
</style>

<div class="hero-header">
  <img src="/assets/header7.jpg" alt="Patents Image">
  <div class="hero-title">Knowledge Sharing</div>
</div>

<div class="nav-bar">
  <a href="/">🏠 Home</a>
  <a href="/experience/">👨‍🔬 Experience</a>
  <a href="/impact/">📈 Impact</a>
  <div class="dropdown">
    <a class="dropdown-toggle">📚 Publications ▾</a>
    <div class="dropdown-content">
      <a href="/patents/">📜 1. Patents</a>
      <a href="/Book_Chapters/">📖 2. Chapters</a>
      <a href="/publications/">📝 3. Articles</a>
    </div>
  </div>
  <a href="/contact/">📬 Contact</a>
</div>

<div style="max-width: 900px; margin: 30px auto; padding: 0 20px;">
  <h1 style="color: var(--primary-dark); border-bottom: 2px solid var(--primary); padding-bottom: 10px;">📜 Patents & Intellectual Property</h1>

  <h3 style="margin-top: 30px;">🥇 Granted Patents</h3>
  
  <div class="patent-card">
    <span class="patent-tag granted">Granted • Indian Patent</span>
    <h4 style="margin: 5px 0;">A Process for Producing La<sub>2</sub>FeMnO<sub>6</sub> From Iron Ore Slime and Applications Thereof.</h4>
    <p style="font-size: 14px; color: #555;">
      <strong>Inventors:</strong> Santanu Sarkar, Tamal Kanti Ghosh, Menaka Jha, Sujeet Kumar, Kritika Sood, <b>Krishna Yadav</b>, Ankush<br>
      <strong>Patent No:</strong> 482517
    </p>
  </div>

  <hr style="margin: 40px 0; opacity: 0.2;">

  <h3>🚀 Patent Applications (In Progress)</h3>

  <div class="patent-card">
    <span class="patent-tag pending">Application Filed</span>
    <h4 style="margin: 5px 0;">Conversion process of Iron Ore Slime into SiO<sub>2</sub>/Fe<sub>2</sub>O<sub>3</sub> heterostructures.</h4>
    <p style="font-size: 14px; color: #555;">
      <strong>Inventors:</strong> Santanu Sarkar, Niloy Kundu, Tamal Kanti Ghosh, Menaka Jha, Sujit Ghuchait, <b>Krishna Yadav</b>, Sunaina, Arushi Arora<br>
      <strong>Application No:</strong> 202231018701
    </p>
  </div>

  <div class="patent-card">
    <span class="patent-tag pending">Application Filed</span>
    <h4 style="margin: 5px 0;">Process of conversion of wastepaper to nanostructured CaCO<sub>3</sub> and their application in de-fluorination of contaminated water.</h4>
    <p style="font-size: 14px; color: #555;">
      <strong>Inventors:</strong> Menaka Jha, Ritika Wadhwa, Sunaina, Ankush, <b>Krishna Yadav</b>, Sujit Kumar Guchhait<br>
      <strong>Application No:</strong> 202311017356
    </p>
  </div>
  <hr style="margin: 30px 0; opacity: 0.5;">
<div align="center">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
</div>

  <p style="text-align: center; margin-top: 40px;">
    <a href="/" style="color: var(--primary); text-decoration: none; font-weight: 600;">[🔙 Back to Home Page]</a>
  </p>
</div>
