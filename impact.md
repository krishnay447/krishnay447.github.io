---
layout: default
title: Impact
permalink: /impact/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* Hide any injected first H1 from the theme */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --nav-hover:#e3f2fd;
  --accent: #ff9800;
  --bg:#f0f4f8;
  --card-bg: rgba(255, 255, 255, 0.9);
  --border:#dce3ef;
  --text-main: #2c3e50;
  --ink:#2a3440;
}
body{ background:var(--bg) !important; font-family: "Segoe UI", Roboto, sans-serif; margin: 0; padding: 0; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:20px auto;
  border-radius:14px; overflow:hidden; box-shadow:0 8px 25px rgba(0,0,0,0.1);
}
.hero-header img{ width:100%; height:220px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(28px,4vw,36px);
  font-weight:800; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.6);
  background:linear-gradient(to top, rgba(0,0,0,0.4), transparent);
}

/* NAVIGATION BAR */
.nav-bar { position: sticky; top: 10px; z-index: 10000; margin: 0 auto 25px; max-width: 1150px; padding: 0 10px; }
.nav-inner {
  display: flex; align-items: center; justify-content: center;
  flex-wrap: wrap; gap: 15px; padding: 8px 15px; background: #ffffff;
  border-radius: 12px; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
  border: 1px solid var(--border);
}
.nav-bar a, .dropdown-toggle {
  text-decoration: none; color: var(--primary-dark) !important;
  font-weight: 800; padding: 8px 16px; border-radius: 8px;
  transition: all 0.2s ease-in-out; display: inline-flex;
  align-items: center; gap: 8px; font-size: 16px; cursor: pointer;
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

/* IMPACT LAYOUT */
.impact-container { max-width: 1150px; margin: 20px auto; padding: 0 15px; }
.impact-row { display: grid; grid-template-columns: 1fr 320px; gap: 20px; }
.stat-card { background: var(--card-bg); padding: 20px; border-radius: 15px; border: 1px solid #fff; box-shadow: 0 4px 20px rgba(0,0,0,0.05); margin-bottom: 20px; }
.section-header { color: var(--primary-dark); font-size: 1.2em; margin-bottom: 15px; display: flex; align-items: center; gap: 8px; border-bottom: 2px solid #eef2f7; padding-bottom: 8px; }

/* MENTORSHIP & ADVISORS */
.mentor-card { font-size: 0.9em; background: #ffffff; padding: 12px; border-radius: 10px; border-left: 4px solid var(--primary); box-shadow: 0 2px 8px rgba(0,0,0,0.04); margin-bottom: 10px; }
.mentor-name { color: #1a237e; font-weight: 700; display: block; }
.mentor-role { color: var(--primary); font-weight: 600; font-size: 0.85em; }
.advisor-item { background: #fff; padding: 10px; border-radius: 10px; margin-bottom: 8px; border: 1px solid #eee; display: flex; justify-content: space-between; align-items: center; }
.advisor-name { font-weight: 700; color: var(--primary-dark); font-size: 0.95em; }
.email-btn { background: var(--primary); color: white !important; padding: 4px 8px; border-radius: 5px; font-size: 11px; text-decoration: none; }

/* SOFTWARE ITEMS & METRICS */
.software-item { background: #fff; padding: 12px; border-radius: 10px; border-left: 4px solid #2c3e50; margin-bottom: 12px; }
.metric-box { display: flex; justify-content: space-between; padding: 10px; background: #1e88e5; color: white; border-radius: 8px; margin-bottom: 6px; font-size: 0.9em; }

/* COLLABORATIVE GRID - RESPONSIVE */
.inst-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 15px; margin-top: 15px; }
.inst-card { background: #fff; padding: 15px; border-radius: 10px; border: 1px solid var(--border); display: flex; flex-direction: column; }
.prof-highlight { color: var(--primary-dark); font-weight: 700; }
.work-desc { font-size: 0.85em; color: #555; margin: 8px 0; }

/* BUTTONS */
.research-btn { display: flex; align-items: stretch; border-radius: 4px; text-decoration: none; height: 40px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
.btn-left { background: #555; color: #fff; padding: 0 15px; display: flex; align-items: center; font-size: 14px; font-weight: 700; }
.btn-right-scholar { background: #4285F4; color: #fff; padding: 0 15px; display: flex; align-items: center; font-size: 14px; font-weight: 700; }
.btn-right-orcid { background: #A6CE39; color: #fff; padding: 0 15px; display: flex; align-items: center; font-size: 14px; font-weight: 700; }
.symbol-row-compact { display: flex; justify-content: center; flex-wrap: wrap; gap: 15px; margin: 30px 0; }

@media (max-width: 900px) { 
  .impact-row { grid-template-columns: 1fr; } 
  .inst-grid { grid-template-columns: 1fr; }
}
</style>

<div class="hero-header">
  <img src="/assets/header8.jpg" alt="Impact banner">
  <div class="hero-title">Academic Impact</div>
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

<div class="impact-container">
  <div class="impact-row">
    <div class="impact-left">
      <div class="stat-card">
        <h3 class="section-header"><i class="fas fa-users"></i> Mentorship & Supervision</h3>
        <div class="mentor-card"><span class="mentor-name">Dr. Heena Sammi</span><span class="mentor-role">Master's Project</span></div>
        <div class="mentor-card"><span class="mentor-name">Rubén Bastida Vadillo</span><span class="mentor-role">Master's Project</span></div>
        <div class="mentor-card"><span class="mentor-name">Alex Bellido Escribano</span><span class="mentor-role">Master's Project</span></div>
        <div class="mentor-card"><span class="mentor-name">Priyanka Goyal</span><span class="mentor-role">B.Sc. Supervision</span></div>

        <h3 class="section-header" style="margin-top:20px;"><i class="fas fa-user-tie"></i> Key Research Advisors</h3>
        <div class="advisor-item">
          <div><span class="advisor-name">Prof. Ashok K. Ganguli</span><br><small style="color:var(--primary)">PHD SUPERVISOR</small></div>
          <a href="mailto:ashok@chemistry.iitd.ac.in" class="email-btn">Email</a>
        </div>
        <div class="advisor-item">
          <div><span class="advisor-name">Dr. Menaka Jha</span><br><small style="color:var(--primary)">PHD SUPERVISOR</small></div>
          <a href="mailto:menaka100jha@gmail.com" class="email-btn">Email</a>
        </div>
        <div class="advisor-item">
          <div><span class="advisor-name">Dr. Ariela Burg</span><br><small style="color:var(--primary)">POSTDOC SUPERVISOR</small></div>
          <a href="mailto:arielab@sce.ac.il" class="email-btn">Email</a>
        </div>
        <div class="advisor-item">
          <div><span class="advisor-name">Prof. Enrique Diez</span><br><small style="color:#666">POSTDOC SUPERVISOR</small></div>
          <a href="mailto:enrisa@usal.es" class="email-btn">Email</a>
        </div>
      </div>
    </div>

    <div class="impact-right">
      <div class="stat-card">
        <h3 class="section-header"><i class="fas fa-chart-bar"></i> Metrics</h3>
        <div class="metric-box">Articles <span>51</span></div>
        <div class="metric-box">Chapters <span>13</span></div>
        <div class="metric-box" style="background: #e67e22;">Patents <span>3</span></div>
        <div class="metric-box" style="background: #2c3e50;">Citations <span>793</span></div>
      </div>

      <div class="stat-card">
        <h3 class="section-header"><i class="fas fa-laptop-code"></i> Innovation</h3>
        <div class="software-item">
          <span class="software-title">⚡ Photocurrent Detector Tool</span>
          <p class="software-desc">Automates Response Time and EQE extraction.</p>
        </div>
      </div>
    </div>
  </div>

  <div class="stat-card">
    <h3 class="section-header"><i class="fas fa-globe-americas"></i> Collaborative Publication Network</h3>
    <div class="inst-grid">
      <div class="inst-card">
        <span class="prof-highlight">Dr. Ana Pérez Rodríguez</span>
        <p class="work-desc">Postdoc collaborator specializing in Terahertz Physics and Semiconductor dynamics.</p>
        <a href="mailto:perez.rodriguez.ana@usal.es" class="email-btn" style="width:fit-content;">Email</a>
      </div>
      <div class="inst-card">
        <span class="prof-highlight">Prof. Santanu Ghosh</span>
        <p class="work-desc">Research on Field Emission and Nanostructures throughout doctoral studies.</p>
        <a href="mailto:santanu1@physics.iitd.ac.in" class="email-btn" style="width:fit-content;">Email</a>
      </div>
    </div>
  </div>
</div>

<div class="symbol-row-compact">
  <a class="research-btn" href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank">
    <div class="btn-left">GOOGLE SCHOLAR</div>
    <div class="btn-right-scholar">PROFILE</div>
  </a>
  <a class="research-btn" href="https://orcid.org/0000-0002-9063-7851" target="_blank">
    <div class="btn-left">ORCID</div>
    <div class="btn-right-orcid">ID</div>
  </a>
</div>
