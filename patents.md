---
layout: default
title: Patents
permalink: /patents/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* 1. GLOBAL STYLES */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --nav-hover:#e3f2fd;
  --bg:#f0f4f8;
  --border:#dce3ef;
  --ink:#2a3440;
  --card-shadow: 0 10px 25px rgba(0,0,0,0.08);
}
body{ background:var(--bg) !important; font-family: "Segoe UI", Roboto, sans-serif; color: var(--ink); }

/* 2. NAVIGATION BAR */
.nav-bar {
  position: sticky; top: 10px; z-index: 10000;
  margin: 0 auto 25px; max-width: 1150px;
}
.nav-inner {
  display: flex; align-items: center; justify-content: center;
  gap: 20px; padding: 6px 15px; background: #ffffff;
  border-radius: 12px; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
  border: 1px solid var(--border);
}
.nav-bar a, .dropdown-toggle {
  text-decoration: none; color: var(--primary-dark) !important;
  font-weight: 800; padding: 8px 16px; border-radius: 8px;
  transition: all 0.2s ease-in-out; display: inline-flex;
  align-items: center; gap: 8px; font-size: 17px; cursor: pointer;
  border: none; background: none; white-space: nowrap;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle {
  background: var(--nav-hover); color: var(--primary) !important;
}

/* Dropdown */
.dropdown { position: relative; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%;
  transform: translateX(-50%); min-width: 180px; z-index: 9999; padding-top: 10px;
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-menu-box {
  background: #fff; border-radius: 10px; border: 1px solid var(--border);
  box-shadow: 0 12px 30px rgba(0,0,0,0.12); overflow: hidden; padding: 5px;
}
.dropdown-menu-box a {
  display: block; padding: 10px 15px; font-size: 15px;
  color: var(--ink) !important; font-weight: 700; text-align: left; text-decoration: none;
}

/* 3. PATENT GRID SYSTEM */
.patent-section { max-width: 1000px; margin: 40px auto; padding: 0 20px; }
.patent-card {
  background: #ffffff; border-radius: 20px; margin-bottom: 40px;
  display: flex; flex-wrap: wrap; overflow: hidden;
  box-shadow: var(--card-shadow); border: 1px solid rgba(255,255,255,0.8);
}
.patent-info { flex: 1; padding: 30px; min-width: 300px; }
.patent-visual { 
  flex: 1; background: #f8fafc; padding: 20px; 
  display: flex; align-items: center; justify-content: center;
  min-width: 300px; border-left: 1px solid #f1f5f9;
}
.patent-tag { display: inline-block; padding: 5px 15px; border-radius: 50px; font-size: 12px; font-weight: 700; text-transform: uppercase; margin-bottom: 15px; }
.tag-granted { background: #e8f5e9; color: #2e7d32; }
.tag-pending { background: #fff3e0; color: #ef6c00; }
.patent-title { font-size: 22px; color: var(--primary-dark); font-weight: 700; margin-bottom: 15px; line-height: 1.3; }
.meta-item { font-size: 14px; margin-bottom: 8px; color: #555; display: flex; gap: 10px; line-height: 1.6; }
.meta-item i { color: var(--primary); width: 20px; flex-shrink: 0; margin-top: 4px; }
.no-wrap-name { white-space: nowrap; display: inline-block; }
.cert-frame { width: 100%; border-radius: 12px; border: 8px solid white; box-shadow: 0 5px 15px rgba(0,0,0,0.1); transition: 0.4s ease; }
@media (max-width: 768px) { .patent-card { flex-direction: column; } .patent-visual { border-left: none; border-top: 1px solid #f1f5f9; } }
</style>

<div style="position:relative; width:100%; max-width:1150px; margin:0 auto 20px; border-radius:20px; overflow:hidden; box-shadow:var(--card-shadow);">
  <img src="/assets/header7.jpg" style="width:100%; height:280px; object-fit:cover;">
  <div style="position:absolute; inset:0; display:flex; flex-direction:column; align-items:center; justify-content:center; color:white; background:rgba(0,0,0,0.4);">
    <h1 style="font-size:45px; margin:0; text-shadow:2px 2px 10px rgba(0,0,0,0.5);">Patents & IP</h1>
  </div>
</div>

<nav class="nav-bar">
  <div class="nav-inner">
    <a href="/">🏠 Home</a>
    <a href="/experience/">👨‍🔬 Experience</a>
    <a href="/impact/">📈 Impact</a>
    <div class="dropdown">
      <span class="dropdown-toggle">📚 Publications ▾</span>
      <div class="dropdown-content">
        <div class="dropdown-menu-box">
          <a href="/patents/">📜 Patents</a>
          <a href="/Book_Chapters/">📖 Chapters</a>
          <a href="/publications/">📝 Articles</a>
        </div>
      </div>
    </div>
    <a href="/contact/">📬 Contact</a>
  </div>
</nav>

<div class="patent-section">
  <h2 style="color: #2c3e50; margin-bottom: 30px; font-weight: 800; border-left: 6px solid var(--primary); padding-left: 15px;">🥇 Granted Portfolio</h2>

  <div class="patent-card">
    <div class="patent-info">
      <span class="patent-tag tag-granted"><i class="fas fa-check-circle"></i> Granted</span>
      <div class="patent-title">A Process for Producing La<sub>2</sub>FeMnO<sub>6</sub> (LFMO) From Iron Ore Slime and Applications Thereof</div>
      <div class="meta-item"><i class="fas fa-fingerprint"></i> <div><strong>Patent No:</strong> 482517</div></div>
      <div class="meta-item"><i class="fas fa-calendar-alt"></i> <div><strong>Grant Date:</strong> 14/12/2023</div></div>
      <div class="meta-item">
        <i class="fas fa-users"></i> 
        <div><strong>Team:</strong> S. Sarkar, T.K. Ghosh, S. Sarkar, M. Jha, S. Guchhait, K. Sood, <span class="no-wrap-name"><b>Krishna Yadav</b></span>, Ankush</div>
      </div>
    </div>
    <div class="patent-visual">
      <a href="/assets/Patent1.jpg" target="_blank"><img src="/assets/Patent1.jpg" class="cert-frame" alt="Patent 1"></a>
    </div>
  </div>

  <div class="patent-card">
    <div class="patent-info">
      <span class="patent-tag tag-granted"><i class="fas fa-check-circle"></i> Granted</span>
      <div class="patent-title">Process of Preparing Silica-Iron Oxide From Iron Ore Slime</div>
      <div class="meta-item"><i class="fas fa-fingerprint"></i> <div><strong>Patent No:</strong> 577043</div></div>
      <div class="meta-item"><i class="fas fa-calendar-alt"></i> <div><strong>Grant Date:</strong> 31/12/2025</div></div>
      <div class="meta-item">
        <i class="fas fa-users"></i> 
        <div><strong>Team:</strong> S. Sarkar, N. Kundu, T.K. Ghosh, M. Jha, S.K. Guchhait, <span class="no-wrap-name"><b>Krishna Yadav</b></span>, Sunaina, A. Arora</div>
      </div>
    </div>
    <div class="patent-visual">
      <a href="/assets/Patent2.jpg" target="_blank"><img src="/assets/Patent2.jpg" class="cert-frame" alt="Patent 2"></a>
    </div>
  </div>

  <h2 style="color: #2c3e50; margin-top: 60px; margin-bottom: 30px; font-weight: 800; border-left: 6px solid #ef6c00; padding-left: 15px;">🚀 Ongoing Applications</h2>
  <div class="patent-card">
    <div class="patent-info" style="flex: 2;">
      <span class="patent-tag tag-pending"><i class="fas fa-clock"></i> Pending</span>
      <div class="patent-title">Conversion of wastepaper to nanostructured CaCO<sub>3</sub> for de-fluorination of water</div>
      <div class="meta-item"><i class="fas fa-file-invoice"></i> <div><strong>App No:</strong> 202311017356</div></div>
      <div class="meta-item">
        <i class="fas fa-users"></i> 
        <div><strong>Team:</strong> M. Jha, R. Wadhwa, Sunaina, Ankush, <span class="no-wrap-name"><b>Krishna Yadav</b></span>, S.K. Guchhait</div>
      </div>
    </div>
  </div>

  <div align="center" style="margin-top: 40px; padding-top: 20px; border-top: 1px solid var(--border);">
    <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
    <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
  </div>
</div>
