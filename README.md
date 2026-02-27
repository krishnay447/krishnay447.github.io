<style>
/* Hide GitHub repo title */
.markdown-body > h1:first-child { display: none !important; }

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

/* NAVIGATION BAR */
.nav-bar {
  text-align: center;
  padding: 12px 0;
  background: #ffffff;
  border-bottom: 3px solid var(--border);
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  font-family: "Segoe UI", sans-serif;
  position: sticky;
  top: 0;
  z-index: 10000;
}
.nav-bar a, .dropdown-toggle {
  color: #444;
  text-decoration: none;
  font-weight: 600;
  padding: 8px 16px;
  margin: 0 4px;
  border-radius: 8px;
  transition: all 0.3s ease;
  display: inline-block;
  font-size: 15px;
  cursor: pointer;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle {
  background-color: #e3f2fd;
  color: var(--primary-dark);
}

/* DROPDOWN */
.dropdown { position: relative; display: inline-block; }
.dropdown-content {
  display: none;
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translateX(-50%);
  background: #ffffff;
  min-width: 250px;
  border-radius: 12px;
  border: 1px solid var(--border);
  box-shadow: 0 10px 30px rgba(0,0,0,0.15);
  z-index: 9999;
  overflow: hidden;
  margin-top: 5px;
}
.dropdown:hover .dropdown-content { display: block; animation: fadeIn 0.3s; }
.dropdown-content a {
  display: block; padding: 12px 20px; border-bottom: 1px solid #f0f0f0;
  text-align: left; font-size: 14px;
}
.dropdown-content a:hover { background-color: #f8fbff; padding-left: 25px; }

@keyframes fadeIn {
  from { opacity: 0; transform: translateX(-50%) translateY(10px); }
  to { opacity: 1; transform: translateX(-50%) translateY(0); }
}

/* ULTRA-THIN CLICKABLE STATS BAR */
.stats-bar {
  display: flex; 
  justify-content: space-around; 
  background: #fff; 
  padding: 8px 20px; 
  border-radius: 12px; 
  border: 1px solid var(--border); 
  margin: 15px 0; 
  text-align: center; 
  box-shadow: 0 2px 8px rgba(0,0,0,0.03);
  align-items: center;
}

.stat-item { 
  text-decoration: none; 
  color: inherit; 
  flex: 1; 
  cursor: pointer; 
  transition: transform 0.2s; 
  display: flex;
  flex-direction: row; 
  justify-content: center;
  align-items: center;
  gap: 6px;
}
.stat-item:hover { transform: scale(1.02); }
.stat-item h2 { color: var(--primary); margin: 0; font-size: 20px; font-weight: 800; font-family: sans-serif; }
.stat-item small { color: #666; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; font-size: 10px; }

/* LAYOUT SPLIT */
.main-grid { display: flex; flex-wrap: wrap; gap: 25px; margin-top: 20px; align-items: stretch; }
.bio-section { flex: 2; min-width: 300px; text-align: justify; text-justify: inter-word; }

/* NEWS SIDEBAR */
.news-sidebar { 
  flex: 1; min-width: 300px; background: linear-gradient(135deg, #ffffff 0%, #f0f7ff 100%); 
  padding: 20px; border-radius: 16px; border: 1px solid #c2d9ff;
  height: 480px; overflow: hidden; position: relative;
  box-shadow: 0 10px 25px rgba(30, 136, 229, 0.1);
}
.news-container { height: 100%; overflow: hidden; position: relative; margin-top: 10px; }
.news-list {
  position: absolute; width: 100%; margin: 0; padding: 0; list-style: none;
  animation: scroll-up 25s linear infinite;
}
.news-list:hover { animation-play-state: paused; }
.news-list li {
  padding: 15px 0; border-bottom: 1px dashed #d0e3ff; font-size: 13.5px;
  color: #334e68; line-height: 1.6; text-align: justify; text-justify: inter-word;
}
@keyframes scroll-up {
  0% { top: 100%; }
  100% { top: -140%; }
}

/* SKILL PILLS */
.skill-pill {
  display: inline-block; padding: 5px 12px; background: #eef6ff; 
  color: var(--primary); border-radius: 20px; font-size: 12px; 
  font-weight: 600; margin: 4px; border: 1px solid #d0e3ff;
}

/* SINGLE ROW GALLERY */
.gallery-grid { 
  display: flex; flex-direction: row; justify-content: space-between; 
  gap: 12px; margin-top: 20px; width: 100%;
}
.gallery-grid img { 
  width: calc(25% - 12px); height: 200px; object-fit: contain; 
  background: #fff; border-radius: 12px; border: 1px solid var(--border); 
  box-shadow: 0 4px 12px rgba(0,0,0,0.08); transition: transform 0.3s;
}
.gallery-grid img:hover { transform: scale(1.05); z-index: 5; }

@media (max-width: 768px) {
  .gallery-grid { flex-wrap: wrap; }
  .gallery-grid img { width: calc(50% - 12px); }
  .stats-bar { flex-direction: column; padding: 10px; }
  .stat-item { margin: 4px 0; }
}
</style>

<div class="hero-header">
  <img src="/assets/header.jpg" alt="Header banner" />
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<div class="nav-bar">
  <a href="/">🏠 Home</a>
  <a href="/experience/">👨‍🔬 Experience</a>
  <a href="/instrumentation/">🔬 Instrumentation</a>
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

<div class="stats-bar">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" class="stat-item">
    <h2 class="counter" data-target="50" data-suffix="+">0+</h2><small>Articles</small>
  </a>
  <a href="/patents/" class="stat-item">
    <h2 class="counter" data-target="3" data-suffix="">0</h2><small>Patents</small>
  </a>
  <div class="stat-item" style="cursor: default;">
    <h2 class="counter" data-target="3" data-suffix="">0</h2><small>Countries</small>
  </div>
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" class="stat-item">
    <h2 class="counter" data-target="750" data-suffix="+">0+</h2><small>Citations</small>
  </a>
</div>

<div class="main-grid">
  <div class="bio-section">
    <h1 style="color: var(--primary-dark); margin-top:0; text-align: left;">Dr. Krishna Kumar Yadav</h1>
    <h3 style="color: #555; text-align: left;">Post-Doctoral Fellow | University of Salamanca, Spain 🇪🇸</h3>
    <p>
      I am a physicist specializing in <b>Nanotechnology, Energy Device Fabrication</b>, and <b>Advanced Material Synthesis</b>. 
      My research primarily explores Metal hexaborides and 2D transition metal dichalcogenides (TMDs). 
      I am passionate about integrating <b>Artificial Intelligence</b> into materials science to accelerate discovery and automate complex data analysis.
    </p>
    
    <h4>🛠️ Technical Toolkit</h4>
    <div>
      <div class="skill-pill">KPFM/FFM</div>
      <div class="skill-pill">Exfoliation</div>
      <div class="skill-pill">Cold Field Emission</div>
      <div class="skill-pill">Device Fabrication</div>
      <div class="skill-pill">AI for Science</div>
      <div class="skill-pill">Waste To Energy</div>
    </div>
  </div>

  <div class="news-sidebar">
    <h4 style="margin-top: 0; color: var(--primary-dark); border-bottom: 2px solid #c2d9ff; padding-bottom: 10px; font-weight: 800; text-align: left;">📢 Latest News</h4>
    <div class="news-container">
      <ul class="news-list">
        <li><b>Jan 2026:</b> Successfully integrated a <b>Spectrometer</b> for 2D material thickness determination.</li>
        <li><b>Dec 2025:</b> Published article on <b>MnFe<sub>2</sub>O<sub>4</sub></b> in Inorganic Chemistry Communications.</li>
        <li><b>Nov 2025:</b> Talk at AMatS Spain on <b>2D TMDC Schottky junction solar cells</b>.</li>
        <li><b>July 2025:</b> Integrating <b>KPFM</b> for Schottky barrier quantification at USAL.</li>
        <li><b>Dec 2025:</b> Poster on <b>Solid Lubricants</b> at GEFES2025.</li>
        <li><b>Jun 2021:</b> Defended PhD thesis on Rare Earth Hexaboride.</li>
      </ul>
    </div>
  </div>
</div>

<hr style="border: 0; height: 1px; background-image: linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,0.1), rgba(0,0,0,0)); margin: 40px 0;">

<h3 style="text-align: center; color: var(--primary-dark); margin-bottom: 25px;">📸 Research & Lab Gallery</h3>

<div class="gallery-grid">
  <img src="photo1.jpg" alt="3D Surface Mapping">
  <img src="photo2.jpg" alt="Crystal Structure MnFe2O4">
  <img src="photo3.jpg" alt="KPFM Mapping">
  <img src="photo4.jpg" alt="Scientific Graph">
</div>

<hr style="margin: 40px 0; opacity: 0.5;">
<div align="center">
  <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Scholar"></a>
  <a href="https://orcid.org/0000-0002-9063-7851" target="_blank"><img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID"></a>
</div>

<script>
const counters = document.querySelectorAll('.counter');
counters.forEach(counter => {
  const updateCount = () => {
    const target = +counter.getAttribute('data-target');
    const suffix = counter.getAttribute('data-suffix');
    // Read the current text but strip the suffix to get the number
    const currentText = counter.innerText.replace(suffix, '');
    const count = +currentText;
    
    // speed 600 = very smooth and slow
    const speed = 600; 
    const inc = Math.max(1, target / speed);

    if (count < target) {
      const nextValue = Math.min(target, Math.ceil(count + inc));
      counter.innerText = nextValue + suffix;
      setTimeout(updateCount, 20); // 20ms interval is very stable
    } else {
      counter.innerText = target + suffix;
    }
  };
  updateCount();
});
</script>
