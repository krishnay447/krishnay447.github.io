<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
/* Hide GitHub repo title */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#0d47a1; 
  --nav-hover:#e3f2fd;
  --bg:#f7f9fc;
  --border:#dce3ef;
  --ink:#2a3440;
}

html { scroll-behavior: smooth; }
body { 
  background: var(--bg) !important; 
  font-family: "Segoe UI", sans-serif; 
  color: var(--ink); 
  margin: 0; 
  padding: 0; 
}

/* HERO BANNER */
.hero-header {
  position: relative; 
  width: 100%; 
  max-width: 1150px; 
  margin: 20px auto;
  border-radius: 14px; 
  overflow: hidden; 
  box-shadow: 0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img { width: 100%; height: 260px; object-fit: cover; display: block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(24px,4vw,36px); font-weight:700; color:#fff;
  text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* NAVIGATION BAR */
.nav-bar {
  position: sticky; 
  top: 10px; 
  z-index: 10000;
  margin: 0 auto 25px;
  max-width: 1150px;
}
.nav-inner {
  display: flex; 
  align-items: center; 
  justify-content: center; 
  gap: 20px; 
  padding: 6px 15px;
  background: #ffffff; 
  border-radius: 12px; 
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
  border: 1px solid var(--border);
}
.nav-bar a, .dropdown-toggle {
  text-decoration: none; 
  color: var(--primary-dark) !important;
  font-weight: 800;
  padding: 8px 16px;
  border-radius: 8px; 
  transition: all 0.2s ease-in-out;
  display: inline-flex; 
  align-items: center; 
  gap: 8px;
  font-size: 17px; 
  cursor: pointer;
  border: none;
  background: none;
  white-space: nowrap;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle {
  background: var(--nav-hover);
  color: var(--primary) !important;
}

/* DROPDOWN */
.dropdown { position: relative; }
.dropdown-content {
  display: none; 
  position: absolute; 
  top: 100%; 
  left: 50%; 
  transform: translateX(-50%);
  min-width: 180px; 
  z-index: 9999; 
  padding-top: 10px; 
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-menu-box {
  background: #fff; border-radius: 10px; border: 1px solid var(--border);
  box-shadow: 0 12px 30px rgba(0,0,0,0.12); overflow: hidden; padding: 5px;
}
.dropdown-menu-box a {
  display: block; padding: 10px 15px; font-size: 15px; 
  color: var(--ink) !important; font-weight: 700; text-align: left;
}

/* MAIN CONTENT */
.main-grid {
  display: grid; 
  grid-template-columns: 1fr 340px; 
  gap: 30px;
  max-width: 1150px; 
  margin: 0 auto; 
  align-items: start;
}
.news-sidebar {
  width: 340px; 
  background: linear-gradient(135deg,#ffffff 0%,#f5f9ff 100%);
  border: 1px solid #cfe0ff; 
  border-radius: 16px;
  box-shadow: 0 8px 26px rgba(30,136,229,.08);
  display: flex; 
  flex-direction: column; 
  overflow: hidden;
}
.news-header {
  padding: 12px 14px; 
  border-bottom: 1px dashed #cfe0ff; 
  font-weight: 800; 
  color: var(--primary-dark);
  display: flex; align-items: center; gap: 8px;
}
.news-scroll { height: 280px; overflow: hidden; position: relative; }
.news-list {
  position: absolute; width: 100%; margin: 0; padding: 0 14px; 
  list-style: none; color: #334e68;
  animation: scroll-up 22s linear infinite;
  box-sizing: border-box;
}
.news-list li { padding: 10px 0; border-bottom: 1px dashed #e2ecff; font-size: 13px; line-height: 1.4; }

@keyframes scroll-up { 0% { top: 100%; } 100% { top: -180%; } }

/* TITLES & PILLS */
.section-title {
  color: var(--primary-dark); font-weight: 800; margin: 20px 0 10px;
  border-left: 4px solid var(--primary); padding-left: 10px;
}
.skill-pill {
  display: inline-block; padding: 5px 12px; background: #eef6ff;
  color: var(--primary); border-radius: 20px; font-size: 12px;
  font-weight: 600; margin: 4px; border: 1px solid #d0e3ff;
}

/* UPDATED GALLERY GRID SYSTEM */
.gallery-wrap { 
  max-width: 1150px; 
  margin: 40px auto; 
  padding: 0 15px;
}
.gallery-grid { 
  display: grid; 
  grid-template-columns: repeat(4, 1fr); 
  gap: 20px; 
  margin-top: 20px;
}
.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 12px;
  border: 1px solid var(--border);
  height: 180px;
  background: #fff;
  transition: all 0.3s ease;
}
.gallery-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.5s ease;
}
.gallery-item:hover {
  transform: translateY(-5px);
  border-color: var(--primary);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}
.gallery-item:hover img {
  transform: scale(1.1);
}

.symbol-row-compact {
  display: flex; justify-content: center; align-items: center; gap: 20px; margin: 40px 0;
}

@media (max-width: 1024px) {
  .main-grid { grid-template-columns: 1fr; padding: 0 20px; }
  .news-sidebar { width: 100%; }
  .gallery-grid { grid-template-columns: repeat(2, 1fr); }
}
</style>
</head>
<body>

<div class="hero-header">
  <img src="/assets/header.jpg" alt="Header banner" />
  <div class="hero-title">Krishna Kumar Yadav</div>
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

<div class="main-grid">
  <section class="bio-section">
    <div class="bio-inner">
      <h3 class="section-title">🔵 Who I Am</h3>
      <p>I am a researcher in <b>nanotechnology and advanced materials</b>, focusing on <b>2D materials</b> for <b>optoelectronic</b> and <b>field‑emission</b> applications. My work integrates <b>materials synthesis</b> and <b>2D exfoliation</b>.</p>
      
      <h3 class="section-title">🟢 Current Work</h3>
      <ul style="padding-left: 20px;">
        <li>Design of <b>engineered contact platforms</b> for 2D optoelectronic devices.</li>
        <li><b>KPFM‑assisted device physics</b> on <b>high‑responsive photodetectors</b>.</li>
      </ul>

      <h3 class="section-title">🔮 Future Vision</h3>
      <ul style="padding-left: 20px;">
        <li>Utilization of <b>AI</b> to optimize photodetector performance.</li>
        <li>Applying <b>contact physics</b> to next‑gen <b>optoelectronic devices</b>.</li>
      </ul>

      <h4 class="section-title" style="border-left-color:#c2d9ff;">🛠 Technical Toolkit</h4>
      <div>
        <span class="skill-pill">KPFM/FFM</span>
        <span class="skill-pill">Exfoliation</span>
        <span class="skill-pill">Cold Field Emission</span>
        <span class="skill-pill">AI for Science</span>
      </div>
    </div>
  </section>

  <aside class="news-sidebar">
    <div class="news-header">📢 Latest News</div>
    <div class="news-scroll">
      <ul class="news-list">
        <li><b>Jan 2026:</b> Installed spectrometer for 2D analysis.</li>
        <li><b>Dec 2025:</b> MnFe<sub>2</sub>O<sub>4</sub> study published.</li>
        <li><b>Nov 2025:</b> Talk at AMatS Spain on Schottky junctions.</li>
        <li><b>Jul 2025:</b> KPFM integrated at USAL.</li>
        <li><b>Jun 2021:</b> PhD on Rare‑Earth Hexaborides defended.</li>
      </ul>
    </div>
  </aside>
</div>

<hr style="max-width: 1150px; margin: 40px auto 0; border: 0; border-top: 1px solid var(--border);">

<div class="gallery-wrap">
  <h3 class="section-title" style="border-left: none; padding-left: 0; text-align: center; border-bottom: 3px solid var(--primary); display: table; margin: 20px auto 30px; padding-bottom: 5px;">
    📸 Research & Lab Gallery
  </h3>
  <div class="gallery-grid">
    <div class="gallery-item"><img src="/assets/photo1.jpg" alt="Lab 1"></div>
    <div class="gallery-item"><img src="/assets/photo2.jpg" alt="Lab 2"></div>
    <div class="gallery-item"><img src="/assets/photo3.jpg" alt="Lab 3"></div>
    <div class="gallery-item"><img src="/assets/photo4.jpg" alt="Lab 4"></div>
  </div>
</div>

<div class="symbol-row-compact">
  <a class="icon-link" href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank">
    <svg viewBox="0 0 24 24" width="24" height="24"><path fill="#4285F4" d="M12 2L1 9l11 7 9-5.73V17h2V9L12 2zM5.3 11.5c0 0 1.43 3.5 6.7 3.5s6.7-3.5 6.7-3.5L12 15.75 5.3 11.5z"/></svg>
  </a>
  <a class="icon-link" href="https://orcid.org/0000-0002-9063-7851" target="_blank">
    <svg viewBox="0 0 256 256" width="24" height="24"><path fill="#A6CE39" d="M256 128c0 70.7-57.3 128-128 128S0 198.7 0 128 57.3 0 128 0s128 57.3 128 128z"/><path fill="#FFF" d="M86.3 186.2H70.9V74.3h15.4v111.9zM108.9 74.3h33.8c24.9 0 38.6 17.5 38.6 37.5 0 14.5-8.1 29.5-22.3 35.1 16.3 5.4 23.3 20.2 23.3 36.3 0 25.1-18.7 39-44.5 39h-28.9V74.3zm15.4 46.1h15.9c12.5 0 19.3-8.8 19.3-19.4s-6.8-19.4-19.3-19.4h-15.9v38.8zm0 50.8h17.1c14.6 0 21.9-10.7 21.9-22.2s-7.3-22.2-21.9-22.2h-17.1v44.4z"/></svg>
  </a>
  <span style="font-size: 22px;">🤖</span>
</div>

</body>
</html>
