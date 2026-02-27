---
layout: default
title: Impact
permalink: /impact/
---

<style>
/* Hide any injected first H1 from the theme */
.markdown-body > h1:first-child { display: none !important; }

/* --- GLOBAL COLORS --- */
:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body{ background:var(--bg) !important; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 20px;
  border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{ width:100%; height:260px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-family:"Segoe UI", sans-serif; font-size:clamp(28px,4vw,40px);
  font-weight:700; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* NAVIGATION BAR (Cleaned up to match Home/Experience) */
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
.dropdown-content a { display: block; padding: 12px 20px; border-bottom: 1px solid #f0f0f0; text-align: left; }

/* IMPACT CONTENT STYLING */
.impact-container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
.stat-card { background: #fff; padding: 20px; border-radius: 12px; border: 1px solid var(--border); margin-bottom: 20px; }
.award-item { border-left: 4px solid var(--primary); padding-left: 15px; margin: 15px 0; }

.profile-links {
  max-width: 1150px; margin: 40px auto; text-align: center;
  padding: 20px; border-top: 1px solid var(--border);
}
</style>

<div class="hero-header">
  <img src="/assets/header8.jpg" alt="Impact banner">
  <div class="hero-title">Impact</div>
</div>

<div class="nav-bar">
  <a href="/">🏠 Home</a>
  <a href="/experience/">👨‍🔬 Experience</a>
  <a href="/impact/">📈 Impact</a>
  <div class="dropdown">
    <a class="dropdown-toggle">📚 Publications ▾</a>
    <div class="dropdown-content">
      <a href="/patents/">📜 1. Patents</a>
      <a href="/Book_Chapters/">📖 2. Book Chapters</a>
      <a href="/publications/">📝 3. Peer-Reviewed Articles</a>
    </div>
  </div>
  <a href="/contact/">📬 Contact</a>
</div>

<div class="impact-container">
  <h1 style="color: var(--primary-dark); border-bottom: 2px solid var(--primary); padding-bottom: 10px;">📊 Scientific Impact & Publications</h1>

  <div class="stat-card">
    <h3 style="margin-top: 0;">📈 Statistics</h3>
    <ul style="list-style: none; padding: 0; font-size: 1.1em;">
      <li>✅ <b>Publications:</b> 51 Peer-reviewed articles</li>
      <li>✅ <b>Book Chapters:</b> 13 Chapters</li>
      <li>✅ <b>Citations:</b> 761</li>
    </ul>
  </div>

  <h3 style="color: var(--primary-dark);">🏆 Key Awards</h3>
  <div class="award-item">
    <b>CSIR-NET:</b> Qualified in Physical Science (2015)
  </div>
  <div class="award-item">
    <b>Best Poster:</b> 9th Bangalore India Nano (2017)
  </div>

  <hr style="margin: 30px 0; opacity: 0.2;">

  <h2 style="color: var(--primary-dark);">💻 Digital Innovation & Software</h2>
  
  <h3 style="display: flex; align-items: center;">⚡ Photocurrent Detector Tool</h3>
  <p>Developed custom software leveraging artificial intelligence to automate the extraction of photocurrent response from raw experimental data. This includes the automated determination of:</p>
    <ul>
    <li><b>Response Time</b></li>
    <li><b>Detectivity</b></li>
    <li><b>External Quantum Efficiency (EQE)</b></li>
  </ul>

  <h3 style="display: flex; align-items: center;">📄 PDF Management Platform</h3>
  <p>Created a web-based tool designed for the efficient management and categorization of scientific PDF documents, streamlining the literature review process for research teams.</p>
</div>

<div class="profile-links">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank">
    <img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar">
  </a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank">
    <img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID">
  </a>
</div>
