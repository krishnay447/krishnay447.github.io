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
body{ background:var(--bg) !important; font-family: "Segoe UI", sans-serif; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 20px;
  border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{ width:100%; height:260px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(28px,4vw,40px);
  font-weight:700; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* NAVIGATION BAR */
.nav-bar {
  text-align: center; padding: 12px 0; background: #ffffff;
  border-bottom: 3px solid var(--border); box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  position: sticky; top: 0; z-index: 10000;
}
.nav-bar a, .dropdown-toggle {
  color: #444; text-decoration: none; font-weight: 600; padding: 10px 18px;
  margin: 0 4px; border-radius: 8px; transition: all 0.2s ease;
  display: inline-block; font-size: 15px; cursor: pointer; border: none; background: none;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background-color: #e3f2fd; color: var(--primary-dark); }

/* DROPDOWN FIX */
.dropdown { position: relative; display: inline-block; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
  background: #ffffff; min-width: 250px; border-radius: 12px; border: 1px solid var(--border);
  box-shadow: 0 10px 30px rgba(0,0,0,0.15); z-index: 9999; overflow: hidden;
  padding-top: 10px; /* Bridge gap */
}
/* Invisible bridge to prevent flickering */
.dropdown-content::before {
  content: ""; position: absolute; top: -15px; left: 0; width: 100%; height: 15px; background: transparent;
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-content a { 
  display: block; padding: 12px 20px; border-bottom: 1px solid #f0f0f0; 
  text-align: left; color: #444; text-decoration: none; font-size: 14px;
}
.dropdown-content a:hover { background: #f8fbff; color: var(--primary); }

/* IMPACT CONTENT STYLING */
.impact-container { max-width: 900px; margin: 30px auto; padding: 0 20px; }
.stat-card { background: #fff; padding: 25px; border-radius: 12px; border: 1px solid var(--border); margin-bottom: 25px; box-shadow: 0 4px 10px rgba(0,0,0,0.02); }
.award-item { border-left: 4px solid var(--primary); padding-left: 15px; margin: 15px 0; background: #fff; padding: 12px 15px; border-radius: 0 8px 8px 0; border: 1px solid var(--border); border-left-width: 4px; }

.profile-links {
  max-width: 1150px; margin: 40px auto; text-align: center;
  padding: 20px; border-top: 1px solid var(--border);
}
.markdown-body { overflow: visible !important; }
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
    <span class="dropdown-toggle">📚 Publications ▾</span>
    <div class="dropdown-content">
      <a href="/patents/">📜 1. Patents</a>
      <a href="/Book_Chapters/">📖 2. Book Chapters</a>
      <a href="/publications/">📝 3. Peer-Reviewed Articles</a>
    </div>
  </div>
  <a href="/contact/">📬 Contact</a>
</div>

<div class="impact-container">
  <h1 style="color: var(--primary-dark); border-left: 5px solid var(--primary); padding-left: 15px; margin-bottom: 25px;">📊 Research Contributions & Metrics</h1>

  <div class="stat-card">
    <h3 style="margin-top: 0; color: var(--primary);">📈 Citation Statistics</h3>
    <ul style="list-style: none; padding: 0; font-size: 1.1em; line-height: 2;">
      <li>✅ <b>Peer-reviewed articles:</b> 51</li>
      <li>✅ <b>Book Chapters:</b> 13</li>
      <li>✅ <b>Total Citations:</b> 761</li>
    </ul>
  </div>

  <h3 style="color: var(--primary-dark);">🏆 Key Awards</h3>
  <div class="award-item">
    <b>CSIR-NET:</b> Qualified in Physical Science (2015)
  </div>
  <div class="award-item">
    <b>Best Poster:</b> 9th Bangalore India Nano (2017)
  </div>

  <hr style="margin: 40px 0; opacity: 0.1;">

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
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" style="text-decoration: none; margin: 0 10px;">
    <img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar">
  </a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" style="text-decoration: none; margin: 0 10px;">
    <img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID">
  </a>
</div>
