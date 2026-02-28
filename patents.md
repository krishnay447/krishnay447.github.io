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
  --bg:#f0f4f8;
  --border:#dce3ef;
  --card-shadow: 0 10px 25px rgba(0,0,0,0.08);
}
body{ background:var(--bg) !important; font-family: "Segoe UI", Roboto, sans-serif; }

/* 2. NAVIGATION BAR (Fixed & Stylish) */
.nav-bar {
  text-align: center; background: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(10px);
  border-bottom: 2px solid var(--border);
  position: sticky; top: 0; z-index: 10000;
  display: flex; justify-content: center; align-items: center; gap: 10px; padding: 12px 0;
}
.nav-item { position: relative; display: inline-block; }
.nav-bar a, .drop-btn {
  color: #444; text-decoration: none; font-weight: 600; padding: 10px 20px;
  border-radius: 8px; transition: 0.3s; font-size: 15px; cursor: pointer; border: none; background: none;
}
.nav-bar a:hover, .nav-item:hover .drop-btn { background-color: var(--primary); color: white !important; }

.dropdown-content {
  display: none; position: absolute; background-color: #ffffff; min-width: 220px;
  box-shadow: 0px 8px 16px rgba(0,0,0,0.1); border-radius: 10px; top: 100%; left: 0; border: 1px solid var(--border); overflow: hidden;
}
.nav-item:hover .dropdown-content { display: block; animation: fadeIn 0.3s ease; }
.dropdown-content a { color: #444; padding: 12px 16px; display: block; text-align: left; border-bottom: 1px solid #f1f1f1; }
.dropdown-content a:hover { background: #f8fbff; color: var(--primary); }

@keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

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

.patent-tag {
  display: inline-block; padding: 5px 15px; border-radius: 50px;
  font-size: 12px; font-weight: 700; text-transform: uppercase; margin-bottom: 15px;
  letter-spacing: 0.5px;
}
.tag-granted { background: #e8f5e9; color: #2e7d32; }
.tag-pending { background: #fff3e0; color: #ef6c00; }

.patent-title { font-size: 22px; color: var(--primary-dark); font-weight: 700; margin-bottom: 15px; line-height: 1.3; }
.meta-item { font-size: 14px; margin-bottom: 8px; color: #555; display: flex; gap: 10px; }
.meta-item i { color: var(--primary); width: 20px; }

/* 4. IMAGE STYLING */
.cert-frame {
  width: 100%; border-radius: 12px; border: 8px solid white;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1); transition: 0.4s ease;
  cursor: zoom-in;
}
.cert-frame:hover { transform: scale(1.03) rotate(1deg); box-shadow: 0 15px 35px rgba(0,0,0,0.15); }

@media (max-width: 768px) {
  .patent-card { flex-direction: column; }
  .patent-visual { border-left: none; border-top: 1px solid #f1f5f9; }
}
</style>

<div style="position:relative; width:100%; max-width:1150px; margin:0 auto 20px; border-radius:20px; overflow:hidden; box-shadow:var(--card-shadow);">
  <img src="/assets/header7.jpg" style="width:100%; height:280px; object-fit:cover;">
  <div style="position:absolute; inset:0; display:flex; flex-direction:column; align-items:center; justify-content:center; color:white; background:rgba(0,0,0,0.4);">
    <h1 style="font-size:45px; margin:0; text-shadow:2px 2px 10px rgba(0,0,0,0.5);">Patents & IP</h1>
    <p style="font-size:18px; opacity:0.9;">Innovation • Research • Protection</p>
  </div>
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

<div class="patent-section">
  
  <h2 style="color: #2c3e50; margin-bottom: 30px; font-weight: 800; border-left: 6px solid var(--primary); padding-left: 15px;">🥇 Granted Portfolio</h2>

  <div class="patent-card">
    <div class="patent-info">
      <span class="patent-tag tag-granted"><i class="fas fa-check-circle"></i> Granted</span>
      <div class="patent-title">A Process for Producing La<sub>2</sub>FeMnO<sub>6</sub> (LFMO) From Iron Ore Slime</div>
      <div class="meta-item"><i class="fas fa-fingerprint"></i> <strong>Patent No:</strong> 482517</div>
      <div class="meta-item"><i class="fas fa-calendar-alt"></i> <strong>Grant Date:</strong> 14/12/2023</div>
      <div class="meta-item"><i class="fas fa-users"></i> <strong>Team:</strong> S. Sarkar, T.K. Ghosh, S. Sarkar, M. Jha, S. Guchhait, K. Sood, <b>K. Yadav</b>, Ankush</div>
      <p style="font-size: 14px; color: #777; margin-top: 15px; font-style: italic;">Application: 202131014754</p>
    </div>
    <div class="patent-visual">
      <a href="/assets/Patent1.jpg" target="_blank">
        <img src="/assets/Patent1.jpg" class="cert-frame" alt="Certificate 1" onerror="this.src='https://via.placeholder.com/400x550?text=Upload+Patent1.jpg+to+Assets'">
      </a>
    </div>
  </div>

  <div class="patent-card">
    <div class="patent-info">
      <span class="patent-tag tag-granted"><i class="fas fa-check-circle"></i> Granted</span>
      <div class="patent-title">Process of Preparing Silica-Iron Oxide From Iron Ore Slime</div>
      <div class="meta-item"><i class="fas fa-fingerprint"></i> <strong>Patent No:</strong> 577043</div>
      <div class="meta-item"><i class="fas fa-calendar-alt"></i> <strong>Grant Date:</strong> 31/12/2025</div>
      <div class="meta-item"><i class="fas fa-users"></i> <strong>Team:</strong> S. Sarkar, N. Kundu, T.K. Ghosh, M. Jha, S.K. Guchhait, <b>K. Yadav</b>, Sunaina, A. Arora</div>
      <p style="font-size: 14px; color: #777; margin-top: 15px; font-style: italic;">Application: 202231018701</p>
    </div>
    <div class="patent-visual">
      <a href="/assets/Patent2.jpg" target="_blank">
        <img src="/assets/Patent2.jpg" class="cert-frame" alt="Certificate 2" onerror="this.src='https://via.placeholder.com/400x550?text=Upload+Patent2.jpg+to+Assets'">
      </a>
    </div>
  </div>

  <h2 style="color: #2c3e50; margin-top: 60px; margin-bottom: 30px; font-weight: 800; border-left: 6px solid #ef6c00; padding-left: 15px;">🚀 Ongoing Applications</h2>

  <div class="patent-card">
    <div class="patent-info" style="border-right: none; flex: 2;">
      <span class="patent-tag tag-pending"><i class="fas fa-clock"></i> Pending</span>
      <div class="patent-title">Conversion of wastepaper to nanostructured CaCO<sub>3</sub> for de-fluorination of water</div>
      <div class="meta-item"><i class="fas fa-file-invoice"></i> <strong>App No:</strong> 202311017356</div>
      <div class="meta-item"><i class="fas fa-users"></i> <strong>Team:</strong> M. Jha, R. Wadhwa, Sunaina, Ankush, <b>K. Yadav</b>, S.K. Guchhait</div>
    </div>
  </div>

  <div align="center" style="margin-top: 50px; padding-bottom: 30px;">
    <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar"></a>
    <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid"></a>
    <br><br>
    <a href="/" style="color: var(--primary); text-decoration: none; font-weight: 700; font-size: 14px;">[🔙 BACK TO HOME]</a>
  </div>

</div>
