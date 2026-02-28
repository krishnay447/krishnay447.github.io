---
layout: default
title: Patents
permalink: /patents/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* 1. CLEANUP */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body{ background:var(--bg) !important; font-family: "Segoe UI", Roboto, sans-serif; }

/* 2. NAVIGATION BAR */
.nav-bar {
  text-align: center; background: #ffffff; border-bottom: 3px solid var(--border);
  position: sticky; top: 0; z-index: 10000; display: flex; justify-content: center; gap: 5px; padding: 12px 0;
}
.nav-item { position: relative; display: inline-block; }
.nav-bar a, .drop-btn {
  color: #444; text-decoration: none; font-weight: 600; padding: 10px 18px;
  border-radius: 8px; transition: 0.2s; font-size: 15px; cursor: pointer; border: none; background: none;
}
.nav-bar a:hover, .nav-item:hover .drop-btn { background-color: #e3f2fd; color: var(--primary-dark); }

.dropdown-content {
  display: none; position: absolute; background-color: #ffffff; min-width: 220px;
  box-shadow: 0px 8px 16px rgba(0,0,0,0.1); z-index: 1; border-radius: 8px; top: 100%; left: 0; border: 1px solid var(--border);
}
.nav-item:hover .dropdown-content { display: block; }
.dropdown-content a { color: #444; padding: 12px 16px; text-decoration: none; display: block; text-align: left; border-bottom: 1px solid #f1f1f1; }

/* 3. PATENT CARDS & IMAGE HOLDERS */
.patent-card {
  background: #fff; padding: 25px; border-radius: 12px; 
  border: 1px solid var(--border); margin-bottom: 30px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.03);
}
.patent-tag {
  display: inline-block; padding: 4px 10px; border-radius: 6px;
  font-size: 11px; font-weight: 700; text-transform: uppercase; margin-bottom: 15px;
}
.granted { background: #e8f5e9; color: #2e7d32; }

/* THE IMAGE BOX - This will always show a grey frame until image is found */
.image-submission-box {
  margin-top: 20px;
  width: 100%;
  max-width: 550px;
  border: 2px solid #edf2f7;
  border-radius: 12px;
  background-color: #f1f5f9;
  overflow: hidden;
  display: block;
}
.image-submission-box img {
  width: 100%;
  height: auto;
  display: block;
  min-height: 200px; /* Ensures the box exists even if image is loading */
}

.markdown-body{ overflow:visible !important; }
</style>

<div style="position:relative; width:100%; max-width:1150px; margin:0 auto 20px; border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);">
  <img src="/assets/header7.jpg" style="width:100%; height:260px; object-fit:cover; display:block;">
  <div style="position:absolute; inset:0; display:flex; align-items:center; justify-content:center; font-size:40px; font-weight:700; color:white; background:rgba(0,0,0,0.3); text-shadow:0 3px 10px rgba(0,0,0,0.5);">Knowledge Sharing</div>
</div>

<div class="nav-bar">
  <a href="/">🏠 Home</a>
  <a href="/experience/">👨‍🔬 Experience</a>
  <a href="/impact/">📈 Impact</a>
  <div class="nav-item">
    <button class="drop-btn">📚 Publications <i class="fas fa-caret-down"></i></button>
    <div class="dropdown-content">
      <a href="/patents/">📜 1. Patents</a>
      <a href="/Book_Chapters/">📖 2. Book Chapters</a>
      <a href="/publications/">📝 3. Peer-Reviewed Articles</a>
    </div>
  </div>
  <a href="/contact/">📬 Contact</a>
</div>

<div style="max-width: 900px; margin: 30px auto; padding: 0 20px;">
  <h1 style="color: var(--primary-dark); border-bottom: 2px solid var(--primary); padding-bottom: 10px;">📜 Patents & Intellectual Property</h1>

  <h3 style="margin-top: 30px;">🥇 Granted Patents</h3>
  
  <div class="patent-card">
    <span class="patent-tag granted">Granted • Indian Patent</span>
    <h4 style="margin: 5px 0;">A Process for Producing La<sub>2</sub>FeMnO<sub>6</sub> (LFMO) From Iron Ore Slime and Applications Thereof</h4>
    <p style="font-size: 14px; color: #555;">
      <strong>Inventors:</strong> Santanu Sarkar, Tamal Kanti Ghosh, Supriya Sarkar, Menaka Jha, Sujit Guchhait, Kritika Sood, <b>Krishna Yadav</b>, Ankush<br>
      <strong>Patent No:</strong> 482517 | <strong>Grant Date:</strong> 14/12/2023
    </p>
    
    <div class="image-submission-box">
      <img src="/assets/Patent1.jpg" alt="Patent Certificate 482517">
    </div>
  </div>

  <div class="patent-card">
    <span class="patent-tag granted">Granted • Indian Patent</span>
    <h4 style="margin: 5px 0;">Process of Preparing Silica-Iron Oxide From Iron Ore Slime</h4>
    <p style="font-size: 14px; color: #555;">
      <strong>Inventors:</strong> Santanu Sarkar, Niloy Kundu, Tamal Kanti Ghosh, Menaka Jha, Sujit Kumar Guchhait, <b>Krishna Yadav</b>, Sunaina, Arushi Arora<br>
      <strong>Patent No:</strong> 577043 | <strong>Grant Date:</strong> 31/12/2025
    </p>

    <div class="image-submission-box">
      <img src="/assets/Patent2.jpg" alt="Patent Certificate 577043">
    </div>
  </div>

  <hr style="margin: 40px 0; opacity: 0.2;">

  <h3>🚀 Patent Applications (In Progress)</h3>
  <div class="patent-card">
    <span style="background: #fff3e0; color: #ef6c00;" class="patent-tag">Application Filed</span>
    <h4 style="margin: 5px 0;">Process of conversion of wastepaper to nanostructured CaCO<sub>3</sub> and their application in de-fluorination of contaminated water.</h4>
    <p style="font-size: 14px; color: #555;">
      <strong>Inventors:</strong> Menaka Jha, Ritika Wadhwa, Sunaina, Ankush, <b>Krishna Yadav</b>, Sujit Kumar Guchhait<br>
      <strong>Application No:</strong> 202311017356
    </p>
  </div>

  <div align="center" style="margin-top: 40px;">
    <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
    <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
  </div>

  <p style="text-align: center; margin-top: 40px;">
    <a href="/" style="color: var(--primary); text-decoration: none; font-weight: 600;">[🔙 Back to Home Page]</a>
  </p>
</div>
