<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
/* Reset and Base Styles */
.markdown-body > h1:first-child { display: none !important; }
:root{
  --primary:#1e88e5; --primary-dark:#0d47a1; 
  --nav-hover:#e3f2fd; --bg:#f7f9fc;
  --border:#dce3ef; --ink:#2a3440;
}
html { scroll-behavior: smooth; }
body { background: var(--bg) !important; font-family: "Segoe UI", sans-serif; color: var(--ink); margin: 0; padding: 0; }

/* HERO BANNER */
.hero-header { position: relative; width: 100%; max-width: 1150px; margin: 20px auto; border-radius: 14px; overflow: hidden; box-shadow: 0 6px 20px rgba(0,0,0,0.15); }
.hero-header img { width: 100%; height: 260px; object-fit: cover; display: block; }
.hero-title{ position:absolute; inset:0; display:flex; align-items:center; justify-content:center; font-size:clamp(24px,4vw,36px); font-weight:700; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.55); background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20)); }

/* NAVIGATION BAR */
.nav-bar { position: sticky; top: 10px; z-index: 10000; margin: 0 auto 20px; max-width: 1150px; padding: 0 10px; }
.nav-inner { display: flex; align-items: center; justify-content: center; flex-wrap: wrap; gap: 30px; padding: 8px 20px; background: #ffffff; border-radius: 12px; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06); border: 1px solid var(--border); }
.nav-bar a, .dropdown-toggle { text-decoration: none; color: var(--primary-dark) !important; font-weight: 800; padding: 8px 16px; border-radius: 8px; transition: all 0.2s; display: inline-flex; align-items: center; gap: 8px; font-size: 16px; cursor: pointer; border: none; background: none; }
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background: var(--nav-hover); color: var(--primary) !important; }

/* Active tab style */
.nav-bar a.active { color: var(--primary) !important; background: var(--nav-hover); border: none !important; }

/* DROPDOWN */
.dropdown { position: relative; }
.dropdown-content { display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%); min-width: 180px; z-index: 9999; padding-top: 10px; }
.dropdown:hover .dropdown-content { display: block; }
.dropdown-menu-box { background: #fff; border-radius: 10px; border: 1px solid var(--border); box-shadow: 0 12px 30px rgba(0,0,0,0.12); overflow: hidden; padding: 5px; }
.dropdown-menu-box a { display: block; padding: 10px 15px; font-size: 15px; color: var(--ink) !important; font-weight: 700; text-align: left; text-decoration: none; }

/* MAIN CONTENT */
.main-grid { display: grid; grid-template-columns: 1fr 340px; gap: 20px; max-width: 1150px; margin: 0 auto; padding: 0 15px; align-items: start; }
.bio-section { font-size: 20px !important; line-height: 1.5; }
.section-title { color: var(--primary-dark); font-weight: 800; margin: 15px 0 5px; border-left: 4px solid var(--primary); padding-left: 10px; font-size: 24px !important; }
.skill-pill { display: inline-block; padding: 4px 10px; background: #eef6ff; color: var(--primary); border-radius: 20px; font-size: 15px; font-weight: 600; margin: 2px; border: 1px solid #d0e3ff; }

/* Sidebar Sections - Each is now a separate card */
.sidebar-card {
    background: #ffffff;
    border: 1px solid #dce3ef;
    border-radius: 16px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    padding: 15px;
    margin-bottom: 20px;
}
.sidebar-header { font-weight: 800; color: var(--primary-dark); margin-bottom: 15px; padding-bottom: 10px; border-bottom: 1px solid #e2ecff; display: block; }

.news-list { margin: 0; padding: 0; list-style: none; color: #334e68; }
.news-list li { padding: 10px 0; border-bottom: 1px dashed #e2ecff; font-size: 15px; line-height: 1.4; }

.tool-links a { display: block; padding: 8px 0; color: var(--primary-dark); font-weight: 700; text-decoration: none; font-size: 15px; }

.sidebar-img { width: 100%; height: 140px; object-fit: cover; border-radius: 8px; border: 1px solid var(--border); margin-bottom: 10px; }

/* GALLERY */
.gallery-wrap { max-width: 1150px; margin: 30px auto 0; padding: 0 15px; }
.gallery-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin-top: 15px; }
.gallery-item { position: relative; overflow: hidden; border-radius: 12px; border: 1px solid var(--border); height: 160px; background: #fff; }
.gallery-item img { width: 100%; height: 100%; object-fit: cover; }

/* FOOTER */
.footer-wrap { text-align: center; padding: 40px 20px; border-top: 1px solid var(--border); margin-top: 40px; color: #666; font-size: 14px; }

@media (max-width: 1024px) { .main-grid { grid-template-columns: 1fr; } .gallery-grid { grid-template-columns: repeat(2, 1fr); } }
</style>
</head>
<body>

<div class="hero-header">
  <img src="/assets/header.jpg" loading="lazy" alt="Header banner" />
  <div class="hero-title">Krishna Kumar Yadav</div>
</div>

<nav class="nav-bar">
  <div class="nav-inner">
    <a href="/" class="active">🏠 Home</a>
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
  <section class="bio-section" style="text-align: justify;">
    <h3 class="section-title">🔵 Who I Am</h3>
    <p>I am a dedicated researcher in <b>nanotechnology and advanced materials</b>, specializing in the synthesis of nanostructured materials and their application in next-generation electronics. My expertise spans the <b>mechanical and chemical exfoliation of 2D materials</b>, the precise <b>fabrication of optoelectronic and field-effect transistor (FET) devices</b>, and the utilization of advanced characterization techniques like <b>KPFM and Raman spectroscopy</b>.</p>
    
    <h3 class="section-title">🟢 Current Work</h3>
    <ul>
      <li><b>Device Fabrication & FETs:</b> Developing high-performance field-effect transistors (FET) utilizing 2D material architectures to study charge transport and contact resistance.</li>
      <li><b>Photodetector Optimization:</b> Engineering 2D-material-based photodetectors to achieve high responsivity and external quantum efficiency through precise interface and contact engineering.</li>
      <li><b>Nanoscale Characterization:</b> Employing <b>Dip-Pen Nanolithography (DPN)</b> and <b>Atomic Force Microscopy (AFM/KPFM)</b> to pattern surfaces and study the electronic behavior of 2D heterostructures.</li>
    </ul>

    <h3 class="section-title">🔮 Future Vision</h3>
    <ul>
      <li>Leveraging the unique properties of 2D heterostructures to develop ultra-sensitive, flexible, and high-speed optoelectronic devices.</li>
      <li>Implementing machine learning and AI-driven data analysis to accelerate the optimization of device architectures, particularly in photodetectors and sensors.</li>
      <li>Industries scale fabrication of a short channel device based on TMDS for very high on off ratio.</li>
    </ul>
    
    <h4 class="section-title" style="border-left-color:#c2d9ff; font-size:20px !important;">🛠 Technical Toolkit</h4>
    <div>
        <span class="skill-pill">KPFM/FFM</span>
        <span class="skill-pill">Exfoliation</span>
        <span class="skill-pill">Cold Field Emission</span>
        <span class="skill-pill">AI for Science</span>
    </div>
  </section>

  <aside>
    <div class="sidebar-card">
        <div class="sidebar-header">📢 Latest News</div>
        <ul class="news-list">
            <li><b>Jan 2026:</b> Installed spectrometer for 2D analysis.</li>
            <li><b>Dec 2025:</b> MnFe<sub>2</sub>O<sub>4</sub> study published.</li>
            <li><b>Nov 2025:</b> Talk at AMatS Spain on Schottky junctions.</li>
        </ul>
    </div>

    <div class="sidebar-card">
        <div class="sidebar-header">⚡ Computational Research Suite</div>
        <div class="tool-links">
            <a href="https://photosensor-459111164189.us-west1.run.app/" target="_blank">🚀 PhotoSensor Pro</a>
            <a href="https://band-aligner-459111164189.us-west1.run.app/" target="_blank">⚛️ BandGap Aligner</a>
            <a href="https://sbh-laboratory-pro-459111164189.us-west1.run.app/" target="_blank">🌡 SBH & Activation Lab</a>
            <a href="https://acadefig-459111164189.us-west1.run.app/" target="_blank">🎨 AcadeFig Pro</a>
        </div>
    </div>

    <div class="sidebar-card">
        <div class="sidebar-header">🖼 Featured Research</div>
        <img src="/assets/photo1.jpg" class="sidebar-img" loading="lazy" alt="Research 1">
        <img src="/assets/photo2.jpg" class="sidebar-img" loading="lazy" alt="Research 2">
    </div>
  </aside>
</div>

<div class="gallery-wrap">
  <h3 class="section-title" style="border-left: none; padding-left: 0; text-align: center; border-bottom: 3px solid var(--primary); display: table; margin: 15px auto 20px; padding-bottom: 5px;">📸 Research & Lab Gallery</h3>
  <div class="gallery-grid">
    <div class="gallery-item"><img src="/assets/photo1.jpg" loading="lazy" alt="Lab 1"></div>
    <div class="gallery-item"><img src="/assets/photo2.jpg" loading="lazy" alt="Lab 2"></div>
    <div class="gallery-item"><img src="/assets/photo3.jpg" loading="lazy" alt="Lab 3"></div>
    <div class="gallery-item"><img src="/assets/photo4.jpg" loading="lazy" alt="Lab 4"></div>
  </div>
</div>

<footer class="footer-wrap">
    <p><b>Dr. Krishna Kumar Yadav</b></p>
    <div style="margin: 10px 0;">
        <a href="mailto:Krish91phy@usal.es" target="_blank" rel="noopener noreferrer" style="color:var(--primary); margin: 0 10px; text-decoration:none;">Email</a>
        <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" rel="noopener noreferrer" style="color:var(--primary); margin: 0 10px; text-decoration:none;">Google Scholar</a>
        <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" rel="noopener noreferrer" style="color:var(--primary); margin: 0 10px; text-decoration:none;">ORCID</a>
    </div>
    <p>&copy; 2026 Krishna Kumar Yadav. All rights reserved.</p>
</footer>

</body>
</html>
