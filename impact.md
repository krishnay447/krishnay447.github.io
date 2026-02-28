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
  --accent: #ff9800;
  --bg:#f0f4f8;
  --card-bg: rgba(255, 255, 255, 0.9);
  --border:#dce3ef;
  --text-main: #2c3e50;
}
body{ background:var(--bg) !important; font-family: "Segoe UI", Roboto, sans-serif; }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 15px;
  border-radius:14px; overflow:hidden; box-shadow:0 8px 25px rgba(0,0,0,0.1);
}
.hero-header img{ width:100%; height:220px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(28px,4vw,36px);
  font-weight:800; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.6);
  background:linear-gradient(to top, rgba(0,0,0,0.4), transparent);
}

/* NAVIGATION */
.nav-bar {
  text-align: center; padding: 10px 0; background: #ffffff;
  border-bottom: 2px solid var(--border); position: sticky; top: 0; z-index: 10000;
}
.nav-bar a {
  color: #444; text-decoration: none; font-weight: 600; padding: 8px 15px;
  margin: 0 2px; border-radius: 6px; transition: 0.2s; font-size: 14px;
}
.nav-bar a:hover { background-color: #e3f2fd; color: var(--primary-dark); }

.impact-container { max-width: 1150px; margin: 20px auto; padding: 0 20px; }
.impact-row { display: grid; grid-template-columns: 1.3fr 0.7fr; gap: 20px; }

.stat-card { 
  background: var(--card-bg); padding: 20px; border-radius: 15px; 
  border: 1px solid #fff; box-shadow: 0 4px 20px rgba(0,0,0,0.05);
  backdrop-filter: blur(4px);
}

.section-header {
  color: var(--primary-dark); font-size: 1.2em; margin-bottom: 15px;
  display: flex; align-items: center; gap: 8px; border-bottom: 2px solid #eef2f7; padding-bottom: 8px;
}

/* MODERN MENTORSHIP BOXES */
.mentor-card {
  font-size: 0.88em; 
  background: #ffffff;
  padding: 12px; 
  border-radius: 10px; 
  border-left: 4px solid var(--primary);
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
  transition: transform 0.2s ease;
}
.mentor-card:hover { transform: translateY(-2px); }
.mentor-name {
  color: #1a237e; 
  font-weight: 700;
  display: block;
  font-size: 1.05em;
  margin-bottom: 2px;
}
.mentor-role { color: var(--primary); font-weight: 600; font-size: 0.85em; }

/* ADVISOR ITEMS WITH TOOLTIP */
.advisor-item {
  position: relative; background: #fff; padding: 10px 15px; border-radius: 10px; margin-bottom: 8px;
  border: 1px solid #eee; display: flex; justify-content: space-between; align-items: center;
}
.advisor-name { font-weight: 700; color: var(--primary-dark); font-size: 1em; cursor: help; border-bottom: 1px dashed #ccc; }

.tooltip-content {
  visibility: hidden; width: 260px; background-color: #333; color: #fff;
  text-align: left; border-radius: 6px; padding: 10px; position: absolute;
  z-index: 100; bottom: 125%; left: 0; opacity: 0; transition: opacity 0.3s;
  box-shadow: 0 5px 15px rgba(0,0,0,0.3); font-size: 0.8em; font-weight: normal; line-height: 1.4;
}
.advisor-name:hover + .tooltip-content { visibility: visible; opacity: 1; }

.email-btn {
  background: var(--primary); color: white !important; padding: 4px 10px;
  border-radius: 5px; font-size: 11px; text-decoration: none; transition: 0.2s;
  display: inline-flex; align-items: center; gap: 4px;
}

/* REFINED COLLABORATIVE GRID */
.inst-grid { 
  display: grid; 
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); 
  gap: 15px; 
  margin-top: 15px; 
}
.inst-card {
  background: #fff; padding: 15px; border-radius: 10px; border: 1px solid var(--border);
  display: flex; flex-direction: column; transition: 0.2s;
}
.inst-card:hover { border-color: var(--primary); box-shadow: 0 5px 15px rgba(0,0,0,0.05); }
.prof-highlight { color: var(--primary-dark); font-weight: 700; font-size: 1em; display: block; }
.work-desc { font-size: 0.82em; color: #555; line-height: 1.4; margin: 8px 0; }

.tag { display: inline-block; padding: 2px 8px; border-radius: 4px; font-size: 9px; font-weight: 800; text-transform: uppercase; }
.tag-phd { background: #e3f2fd; color: #1565c0; }
.tag-postdoc { background: #fff3e0; color: #e65100; }
.tag-ongoing { background: #e8f5e9; color: #2e7d32; }

/* METRICS */
.metric-box {
  display: flex; justify-content: space-between; padding: 12px;
  background: linear-gradient(135deg, #1e88e5, #1565c0);
  color: white; border-radius: 10px; margin-bottom: 8px; font-size: 0.9em;
}

@media (max-width: 900px) { .impact-row { grid-template-columns: 1fr; } }
</style>

<div class="hero-header">
  <img src="/assets/header8.jpg" alt="Impact banner">
  <div class="hero-title">Academic Impact</div>
</div>

<div class="nav-bar">
  <a href="/">🏠 Home</a>
  <a href="/experience/">👨‍🔬 Experience</a>
  <a href="/impact/">📈 Impact</a>
  <a href="/publications/">📝 Publications</a>
  <a href="/contact/">📬 Contact</a>
</div>

<div class="impact-container">
  
  <div class="impact-row">
    <div class="impact-left">
      <div class="stat-card">
        <h3 class="section-header"><i class="fas fa-users"></i> Mentorship & Supervision</h3>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 25px;">
          <div class="mentor-card">
            <span class="mentor-name">Dr. Heena Sammi</span>
            <span class="mentor-role">Master's Project</span>
            <div style="font-size: 0.8em; color: #666; margin-top: 4px;">Asst. Prof, Rupnagar, Punjab</div>
          </div>
          <div class="mentor-card">
            <span class="mentor-name">Rubén Bastida Vadillo</span>
            <span class="mentor-role">Master's Project</span>
            <div style="font-size: 0.8em; color: #666; margin-top: 4px;">University of Salamanca, Spain</div>
          </div>
          <div class="mentor-card">
            <span class="mentor-name">Alex Bellido Escribano</span>
            <span class="mentor-role">Master's Project</span>
            <div style="font-size: 0.8em; color: #666; margin-top: 4px;">University of Salamanca, Spain</div>
          </div>
          <div class="mentor-card">
            <span class="mentor-name">Priyanka Goyal</span>
            <span class="mentor-role">B.Sc. Supervision</span>
            <div style="font-size: 0.8em; color: #666; margin-top: 4px;">Project Mentorship</div>
          </div>
        </div>

        <h3 class="section-header"><i class="fas fa-user-tie"></i> Key Research Advisors</h3>
        
        <div class="advisor-item">
          <div>
            <span class="advisor-name">Prof. Ashok K. Ganguli</span>
            <div class="tooltip-content">Director, IISER Berhampur & Professor, IIT Delhi</div>
            <br><small style="font-size: 0.75em; color:var(--primary)">PHD SUPERVISOR</small>
          </div>
          <a href="mailto:ashok@chemistry.iitd.ac.in" class="email-btn"><i class="fas fa-envelope"></i> Email</a>
        </div>

        <div class="advisor-item">
          <div>
            <span class="advisor-name">Dr. Menaka Jha</span>
            <div class="tooltip-content">Scientist, Institute of Nano Science and Technology (INST), Mohali</div>
            <br><small style="font-size: 0.75em; color:var(--primary)">PHD SUPERVISOR</small>
          </div>
          <a href="mailto:menaka100jha@gmail.com" class="email-btn"><i class="fas fa-envelope"></i> Email</a>
        </div>

        <div class="advisor-item">
          <div>
            <span class="advisor-name">Prof. Ariela Burg</span>
            <div class="tooltip-content">Professor, Dept. of Chemical Engineering, Sami Shamoon College, Israel</div>
            <br><small style="font-size: 0.75em; color:var(--primary)">POSTDOC SUPERVISOR</small>
          </div>
          <a href="mailto:arielab@sce.ac.il" class="email-btn"><i class="fas fa-envelope"></i> Email</a>
        </div>

        <div class="advisor-item">
          <div>
            <span class="advisor-name">Prof. Enrique Diez</span>
            <div class="tooltip-content">Dept. of Fundamental Physics, University of Salamanca, Spain</div>
            <br><small style="font-size: 0.75em; color:#666">POSTDOC SUPERVISOR</small>
          </div>
          <a href="mailto:enrisa@usal.es" class="email-btn"><i class="fas fa-envelope"></i> Email</a>
        </div>
      </div>
    </div>

    <div class="impact-right">
      <div class="stat-card">
        <h3 class="section-header"><i class="fas fa-chart-bar"></i> Metrics</h3>
        <div class="metric-box">Articles <span>51</span></div>
        <div class="metric-box">Chapters <span>13</span></div>
        <div class="metric-box" style="background: #e67e22;">Patents <span>3</span></div>
        <div class="metric-box" style="background: #2c3e50;">Citations <span>761</span></div>
        <div style="margin-top:20px; font-size:0.85em; border-left:3px solid var(--accent); padding-left:10px;">
          <i class="fas fa-medal" style="color:var(--accent)"></i> <b>CSIR-NET</b> (2015)<br>
          <i class="fas fa-medal" style="color:var(--accent)"></i> <b>Best Poster</b> (Bangalore Nano)
        </div>
      </div>
    </div>
  </div>

  <div class="stat-card" style="margin-top: 20px;">
    <h3 class="section-header"><i class="fas fa-globe-americas"></i> Collaborative Publication Network</h3>
    <div class="inst-grid">
      
      <div class="inst-card">
        <span class="prof-highlight">Dr. Ana Pérez Rodríguez</span>
        <small style="color:#888; font-weight:600;">U. Salamanca, Spain</small>
        <p class="work-desc">Postdoc collaborator specializing in <b>Terahertz Physics</b> and Semiconductor dynamics.</p>
        <div style="display:flex; justify-content:space-between; align-items:center; margin-top:auto;">
          <span class="tag tag-postdoc">Postdoc Collab</span>
          <a href="mailto:perez.rodriguez.ana@usal.es" class="email-btn">Email</a>
        </div>
      </div>

      <div class="inst-card">
        <span class="prof-highlight">Dr. Carmen Munuera López</span>
        <small style="color:#888; font-weight:600;">ICMM-CSIC, Madrid</small>
        <p class="work-desc">Advanced material characterization and <b>Surface Science</b> expertise during Postdoc phase.</p>
        <div style="display:flex; justify-content:space-between; align-items:center; margin-top:auto;">
          <span class="tag tag-postdoc">Postdoc Collab</span>
          <a href="mailto:cmunuera@icmm.csic.es" class="email-btn">Email</a>
        </div>
      </div>

      <div class="inst-card">
        <span class="prof-highlight">Prof. Santanu Ghosh</span>
        <small style="color:#888; font-weight:600;">IIT Delhi</small>
        <p class="work-desc">Extensive research on <b>Field Emission</b> and Nanostructures throughout doctoral studies.</p>
        <div style="display:flex; justify-content:space-between; align-items:center; margin-top:auto;">
          <span class="tag tag-phd">Field Emission</span>
          <a href="mailto:santanu1@physics.iitd.ac.in" class="email-btn">Email</a>
        </div>
      </div>

      <div class="inst-card">
        <span class="prof-highlight">Dr. Sunaina Choudhary</span>
        <small style="color:#888; font-weight:600;">GNDU, Amritsar</small>
        <p class="work-desc">Assistant Professor. Core collaborator on <b>Physical Chemistry</b> and Nanomaterials since PhD.</p>
        <div style="display:flex; justify-content:space-between; align-items:center; margin-top:auto;">
          <span class="tag tag-ongoing">PhD to Present</span>
          <a href="mailto:sunaina1010@yahoo.com" class="email-btn">Email</a>
        </div>
      </div>

      <div class="inst-card">
        <span class="prof-highlight">Dr. Vishwajit Gaikwad</span>
        <small style="color:#888; font-weight:600;">SGB Amravati Univ.</small>
        <p class="work-desc">Experimental physics partner focused on <b>Instrumentation</b> and precision measurements.</p>
        <div style="display:flex; justify-content:space-between; align-items:center; margin-top:auto;">
          <span class="tag tag-ongoing">PhD to Present</span>
          <a href="mailto:vish9823@gmail.com" class="email-btn">Email</a>
        </div>
      </div>

      <div class="inst-card">
        <span class="prof-highlight">Prof. S.K. Mehta</span>
        <small style="color:#888; font-weight:600;">Panjab University</small>
        <p class="work-desc">Joint research on <b>Chemical Synthesis</b> pathways and material characterization techniques.</p>
        <div style="display:flex; justify-content:space-between; align-items:center; margin-top:auto;">
          <span class="tag tag-phd">PhD Period</span>
          <a href="mailto:skmehta@pu.ac.in" class="email-btn">Email</a>
        </div>
      </div>

    </div>
  </div>
</div>
<hr style="margin: 30px 0; opacity: 0.5;">
<div align="center">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
</div>
