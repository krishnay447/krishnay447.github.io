<style>
/* Hide GitHub repo title */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
  --ink:#2a3440;
}
html { scroll-behavior: smooth; }
body{ background:var(--bg) !important; font-family:"Segoe UI",sans-serif; color:var(--ink); }

/* HERO BANNER */
.hero-header{
  position:relative; width:100%; max-width:1150px; margin:0 auto 20px;
  border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15);
}
.hero-header img{ width:100%; height:260px; object-fit:cover; display:block; }
.hero-title{
  position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
  font-size:clamp(28px,4vw,40px); font-weight:700; color:#fff;
  text-shadow:0 3px 10px rgba(0,0,0,0.55);
  background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20));
}

/* ================= NAVIGATION BAR (compact like other boxes) ================= */
.nav-bar {
  position: sticky; top: 0; z-index: 10000;
  background:#fff;
  border-bottom:1px solid var(--border);          /* ✅ NEW: thinner border to match boxes */
  box-shadow:0 4px 10px rgba(0,0,0,0.05);
}
/* Inner wrapper → same width and radius style as your boxes */
.nav-inner{                                       /* ✅ NEW */
  max-width:1150px; margin:0 auto;
  display:flex; align-items:center; justify-content:center; gap:8px;
  padding:8px 10px;                               /* ✅ NEW: smaller vertical padding */
  border-radius:12px;                             /* ✅ NEW: rounded like stats box */
  background:#fff;
}
.nav-bar a, .dropdown-toggle{
  color:#333; text-decoration:none; font-weight:700;
  padding:8px 14px;                               /* ✅ NEW: reduced padding to match compact look */
  border-radius:10px; margin:0 2px;               /* ✅ NEW */
  transition:all .18s ease; display:inline-flex; align-items:center; gap:6px;
  font-size:16px; letter-spacing:.1px; cursor:pointer; border:none; background:none;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle{
  background:#e8f2ff; color:var(--primary-dark);
}

/* DROPDOWN */
.dropdown{ position:relative; display:inline-block; }
.dropdown-content{
  display:none; position:absolute; top:100%; left:50%; transform:translateX(-50%);
  background:transparent; min-width:260px; z-index:9999; padding-top:10px;
}
.dropdown-content::before{ content:""; position:absolute; top:-15px; left:0; width:100%; height:15px; }
.dropdown:hover .dropdown-content{ display:block; animation:fadeIn .2s ease-out; }
.dropdown-menu-box{
  background:#fff; border-radius:12px; border:1px solid var(--border);
  box-shadow:0 10px 30px rgba(0,0,0,0.15); overflow:hidden;
}
.dropdown-menu-box a{
  display:block; padding:12px 20px; border-bottom:1px solid #f0f0f0;
  text-align:left; font-size:15px; color:#444; text-decoration:none; transition:.2s;
}
.dropdown-menu-box a:last-child{ border-bottom:none; }
.dropdown-menu-box a:hover{ background:#f8fbff; color:var(--primary); }
@keyframes fadeIn{ from{opacity:0; transform:translateX(-50%) translateY(10px);} to{opacity:1; transform:translateX(-50%) translateY(0);} }

/* STATS BAR */
.stats-bar{
  display:flex; justify-content:space-around; background:#fff; padding:12px 20px;
  border-radius:12px; border:1px solid var(--border); margin:15px auto;
  text-align:center; box-shadow:0 2px 8px rgba(0,0,0,0.03); align-items:center; gap:8px;
  max-width:1150px;
}
.stat-item{ text-decoration:none; color:inherit; flex:1; cursor:pointer; transition:transform .2s; display:flex; align-items:center; justify-content:center; gap:8px; }
.stat-item:hover{ transform:scale(1.03); }
.stat-item h2{ color:var(--primary); margin:0; font-size:22px; font-weight:800; }
.stat-item small{ color:#666; font-weight:700; text-transform:uppercase; font-size:10px; letter-spacing:.5px; }

/* ==== CONTENT GRID: reliable 60 / 40 split ==== */
.main-grid{
  display:grid; grid-template-columns: 60% 40%; gap:25px;
  max-width:1150px; margin:20px auto 0; align-items:start;
}

/* LEFT column (text) */
.bio-section{ min-width:300px; }
.bio-inner{ max-width:850px; }
.section-title{
  color:var(--primary-dark); font-weight:800; margin:16px 0 8px;
  border-left:4px solid var(--primary); padding-left:10px;
}
.stack > * + *{ margin-top:12px; }            /* compact vertical rhythm */
ul.compact{ margin:6px 0 0 18px; }
ul.compact li{ margin:6px 0; }

/* Future Vision list */
.future-list{ margin:6px 0 0 18px; }
.future-list li{ margin:6px 0; }
@media (min-width: 1200px){
  .future-list{ columns:2; column-gap:28px; }
}

/* RIGHT column (Latest News) */
.news-sidebar{
  min-width:280px; align-self:start;
  background:linear-gradient(135deg,#ffffff 0%,#f5f9ff 100%);
  border:1px solid #cfe0ff; border-radius:16px;
  box-shadow:0 8px 26px rgba(30,136,229,.08);
  display:flex; flex-direction:column; overflow:hidden;
}
.news-header{
  position:sticky; top:0; background:linear-gradient(135deg,#ffffff 0%,#f5f9ff 100%);
  padding:10px 14px; border-bottom:1px dashed #cfe0ff; font-weight:800; color:var(--primary-dark);
  display:flex; align-items:center; gap:8px;
}
.news-scroll{ height:300px; overflow:hidden; position:relative; }
.news-list{
  position:absolute; inset:auto 0 0 0; top:100%;
  margin:0; padding:0 14px; list-style:none; color:#334e68; line-height:1.5;
  animation:scroll-up 22s linear infinite;
}
.news-list li{ padding:10px 0; border-bottom:1px dashed #e2ecff; font-size:13.2px; }
.news-list li:last-child{ border-bottom:none; }
.news-scroll:hover .news-list{ animation-play-state:paused; }
@keyframes scroll-up{ 0%{ top:100%; } 100%{ top:-190%; } }

/* SKILL PILLS */
.skill-pill{
  display:inline-block; padding:5px 12px; background:#eef6ff;
  color:var(--primary); border-radius:20px; font-size:12px;
  font-weight:600; margin:4px; border:1px solid #d0e3ff;
}

/* GALLERY */
.gallery-wrap{ max-width:1150px; margin:0 auto; }
.gallery-grid{
  display:flex; flex-wrap:wrap; justify-content:space-between; gap:12px; margin-top:20px; width:100%;
}
.gallery-grid img{
  width:calc(25% - 12px); height:200px; object-fit:contain; background:#fff;
  border-radius:12px; border:1px solid var(--border); transition:transform .3s;
}
.gallery-grid img:hover{ transform:scale(1.05); }

/* ======= FOOTER BADGE ROW (aligned buttons) ======= */
.badges-row{                                    /* ✅ NEW: aligns badges + AI button nicely */
  display:flex; flex-wrap:wrap; align-items:center; justify-content:center;
  gap:10px; margin:30px 0;
}
.badge-link img{ height:40px; display:block; }
.badge-btn{                                     /* ✅ NEW: AI button style unified with badges */
  display:inline-flex; align-items:center; justify-content:center; gap:8px;
  height:40px; padding:0 14px; border-radius:6px; font-weight:700; font-size:13px;
  text-decoration:none; color:#fff; background:#4285F4; letter-spacing:.5px;
  box-shadow:0 2px 6px rgba(66,133,244,.3);
}
.badge-btn:hover{ filter:brightness(0.95); }

@media (max-width:1024px){
  .main-grid{ grid-template-columns: 1fr; }
  .news-scroll{ height:260px; }
}
@media (max-width:768px){
  .gallery-grid img{ width:calc(50% - 12px); }
  .stats-bar{ flex-direction:column; gap:15px; }
}
.markdown-body{ overflow:visible !important; }
</style>

<!-- HERO -->
<div class="hero-header">
  <img src="/assets/header.jpg" alt="Header banner" />
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<!-- NAV (with compact inner container) -->
<div class="nav-bar">
  <div class="nav-inner"><!-- ✅ NEW -->
    <a href="/">🏠 Home</a>
    <a href="/experience/">👨‍🔬 Experience</a>
    <a href="/impact/">📈 Impact</a>

    <div class="dropdown">
      <span class="dropdown-toggle">📚 Publications ▾</span>
      <div class="dropdown-content">
        <div class="dropdown-menu-box">
          <a href="/patents/">📜 1. Patents</a>
          <a href="/Book_Chapters/">📖 2. Chapters</a>
          <a href="/publications/">📝 3. Articles</a>
        </div>
      </div>
    </div>

    <a href="/contact/">📬 Contact</a>
  </div>
</div>

<!-- STATS -->
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

<!-- MAIN 60 / 40 GRID -->
<div class="main-grid">
  <!-- LEFT (about & research) -->
  <section class="bio-section">
    <div class="bio-inner stack">
      <h3 class="section-title">🔵 Who I Am</h3>
      <p>
        I am a researcher in <b>nanotechnology and advanced materials</b>, focusing on
        <b>2D materials</b> for <b>optoelectronic</b> and <b>field‑emission</b> applications.
        My work integrates <b>materials synthesis</b> and <b>2D exfoliation</b> with
        <b>device fabrication</b> and <b>contact engineering</b>.
      </p>

      <h3 class="section-title">🟢 Current Work</h3>
      <ul class="compact">
        <li>Design of <b>engineered contact platforms</b> for 2D optoelectronic devices.</li>
        <li><b>KPFM‑assisted device physics</b> on <b>high‑responsive photodetectors</b>.</li>
      </ul>

      <h3 class="section-title">🔮 Future Vision</h3>
      <ul class="future-list">
        <li>Utilization of <b>AI</b> to optimize photodetector performance and workflows.</li>
        <li>Applying <b>contact physics</b> to next‑gen <b>optoelectronic devices</b>.</li>
        <li>Development of X‑ray devices using <b>field‑emission</b> approaches.</li>
        <li><b>Waste‑to‑nanomaterial</b> routes for sustainable materials chemistry.</li>
      </ul>

      <h4 class="section-title" style="border-left-color:#c2d9ff;">🛠 Technical Toolkit</h4>
      <div>
        <span class="skill-pill">KPFM/FFM</span>
        <span class="skill-pill">Exfoliation</span>
        <span class="skill-pill">Cold Field Emission</span>
        <span class="skill-pill">Device Fabrication</span>
        <span class="skill-pill">AI for Science</span>
      </div>
    </div>
  </section>

  <!-- RIGHT (Latest News) -->
  <aside class="news-sidebar">
    <div class="news-header">📢 Latest News</div>
    <div class="news-scroll">
      <ul class="news-list">
        <li><b>Jan 2026:</b> Installed spectrometer for 2D material thickness analysis.</li>
        <li><b>Dec 2025:</b> MnFe<sub>2</sub>O<sub>4</sub> electrocatalyst study published (Inorganic Chemistry Communications).</li>
        <li><b>Nov 2025:</b> Talk at AMatS Spain on 2D TMDC Schottky junction solar cells.</li>
        <li><b>Jul 2025:</b> KPFM integrated for Schottky barrier quantification at USAL.</li>
        <li><b>Dec 2025:</b> Poster on solid lubricants at GEFES2025.</li>
        <li><b>Jun 2021:</b> PhD on Rare‑Earth Hexaborides defended.</li>
      </ul>
    </div>
  </aside>
</div>

<hr style="border:0; height:1px; background-image:linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,0.1), rgba(0,0,0,0)); margin:30px 0;">

<!-- GALLERY -->
<div class="gallery-wrap">
  <h3 id="gallery" class="section-title" style="border-left-color:#c2d9ff; margin-top:0;">📸 Research &amp; Lab Gallery</h3>
  <div class="gallery-grid">
    <img src="/assets/photo1.jpg" alt="3D Surface Mapping">
    <img src="/assets/photo2.jpg" alt="Crystal Structure MnFe2O4">
    <img src="/assets/photo3.jpg" alt="KPFM Mapping">
    <img src="/assets/photo4.jpg" alt="Scientific Graph">
  </div>
</div>

<!-- BADGES ROW (aligned) -->
<div class="badges-row"><!-- ✅ NEW -->
  <a class="badge-link" href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" aria-label="Google Scholar">
    <img src="https://img.shields.io/badge/Google_Scholar-Profile-red?style=for-the-badge&logo=google-scholar" alt="Google Scholar">
  </a>
  <a class="badge-link" href="https://orcid.org/0000-0002-9063-7851" target="_blank" aria-label="ORCID">
    <img src="https://img.shields.io/badge/ORCID-iD-A6CE39?style=for-the-badge&logo=orcid" alt="ORCID">
  </a>
  <a class="badge-btn" href="https://notebooklm.google.com/notebook/8b8b0acb-21e5-4f16-9025-dfcc93980356" target="_blank" aria-label="AI Assistant">
    🤖 AI Assistant
  </a>
</div>

<script>
/* Animated counters (robust against plus signs) */
const counters = document.querySelectorAll('.counter');
counters.forEach(counter => {
  const animate = () => {
    const target = +counter.getAttribute('data-target');
    const suffix = counter.getAttribute('data-suffix') || "";
    const numeric = counter.innerText.replace(/[^\d]/g,'');
    const count = +numeric || 0;
    const inc = Math.max(1, Math.ceil(target / 100));
    if (count < target) {
      counter.innerText = Math.min(target, count + inc) + suffix;
      setTimeout(animate, 20);
    } else {
      counter.innerText = target + suffix;
    }
  };
  animate();
});
</script>
