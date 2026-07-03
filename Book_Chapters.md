---
layout: default
title: Book Chapters
permalink: /Book_Chapters/
---

<style>
/* ===== Clean Academic Theme ===== */
.markdown-body > h1:first-child { display: none !important; }
.markdown-body { overflow: visible !important; }
:root{
  --accent:#1a5490; --accent-dark:#123c66; --ink:#1f2937; --muted:#5b6572;
  --border:#e3e8ef; --bg-soft:#f7f9fb; --heading:#1c2e40;
}
body{ background:#fff !important; color:var(--ink); font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif; margin:0; padding:0; line-height:1.65; }
h1,h2,h3{ font-family:Georgia,"Times New Roman",serif; color:var(--heading); font-weight:600; }
a{ color:var(--accent); }

/* NAV */
.site-nav{ position:sticky; top:0; z-index:1000; background:rgba(255,255,255,0.97); border-bottom:1px solid var(--border); }
.nav-inner{ max-width:1000px; margin:0 auto; padding:12px 20px; display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:10px; }
.brand{ font-family:Georgia,serif; font-size:20px; font-weight:700; color:var(--heading) !important; text-decoration:none; }
.nav-links{ display:flex; align-items:center; gap:2px; flex-wrap:wrap; }
.nav-links a, .dropdown-toggle{ color:var(--ink) !important; text-decoration:none; font-size:15px; font-weight:600; padding:6px 12px; border-radius:6px; }
.nav-links a:hover, .dropdown:hover .dropdown-toggle{ background:var(--bg-soft); color:var(--accent) !important; }
.dropdown{ position:relative; display:inline-block; }
.dropdown-content{ display:none; position:absolute; top:100%; right:0; min-width:190px; z-index:999; padding-top:8px; }
.dropdown:hover .dropdown-content{ display:block; }
.dropdown-menu-box{ background:#fff; border:1px solid var(--border); border-radius:8px; box-shadow:0 10px 25px rgba(0,0,0,0.08); padding:6px; }
.dropdown-menu-box a{ display:block; padding:9px 14px; font-size:14px; color:var(--ink) !important; text-decoration:none; border-radius:6px; }
.dropdown-menu-box a:hover{ background:var(--bg-soft); color:var(--accent) !important; }

/* PAGE HEAD */
.page-head{ max-width:900px; margin:44px auto 10px; padding:0 20px; }
.page-head h1{ font-size:34px; margin:0 0 6px; }
.page-head p{ color:var(--muted); margin:0; font-size:16.5px; }
.sub-nav{ max-width:900px; margin:10px auto 0; padding:0 20px; font-size:14.5px; }
.sub-nav a{ font-weight:600; text-decoration:none; margin-right:14px; }

/* SEARCH & FILTER */
.search-container{ max-width:900px; margin:22px auto 6px; padding:0 20px; display:flex; flex-wrap:wrap; gap:10px; align-items:center; }
#yearInput{ flex:1 1 220px; max-width:320px; padding:10px 16px; border-radius:8px; border:1px solid var(--border); font-size:14.5px; outline:none; background:var(--bg-soft); box-sizing:border-box; }
#yearInput:focus{ border-color:var(--accent); background:#fff; }
.filter-btn{ padding:8px 16px; border:1px solid var(--border); background:#fff; color:var(--muted); border-radius:8px; cursor:pointer; font-weight:600; font-size:13px; }
.filter-btn:hover, .filter-btn.active{ background:var(--accent); color:#fff; border-color:var(--accent); }

/* CHAPTER CARDS */
.chapter-container{ max-width:900px; margin:14px auto 0; padding:0 20px; }
.chapter-card{ background:#fff; border:1px solid var(--border); border-radius:10px; padding:18px 20px; margin-bottom:12px; transition:border-color 0.15s; }
.chapter-card:hover{ border-color:var(--accent); }
.chapter-year-label{ float:right; background:var(--bg-soft); color:var(--accent); padding:2px 10px; border-radius:20px; font-size:11.5px; font-weight:800; border:1px solid var(--border); margin-left:10px; }
.chapter-title{ color:var(--heading); font-size:16px; font-weight:700; margin-bottom:6px; line-height:1.45; display:block; }
.chapter-authors{ font-size:13.5px; color:var(--muted); margin-bottom:6px; }
.chapter-meta{ font-size:13px; color:#6b7280; font-style:italic; border-top:1px solid var(--bg-soft); padding-top:6px; margin-top:6px; }

/* FOOTER */
.site-footer{ border-top:1px solid var(--border); margin-top:56px; padding:32px 20px 40px; text-align:center; color:var(--muted); font-size:14px; }
.site-footer a{ margin:0 10px; font-weight:600; text-decoration:none; }
</style>

<nav class="site-nav">
  <div class="nav-inner">
    <a class="brand" href="/">Krishna K. Yadav</a>
    <div class="nav-links">
      <a href="/">Home</a>
      <a href="/experience/">Experience</a>
      <a href="/impact/">Impact</a>
      <div class="dropdown">
        <a href="/publications/" class="dropdown-toggle">Publications &#9662;</a>
        <div class="dropdown-content"><div class="dropdown-menu-box">
          <a href="/publications/">Journal Articles</a>
          <a href="/Book_Chapters/">Book Chapters</a>
          <a href="/patents/">Patents</a>
        </div></div>
      </div>
      <a href="/cv/">CV</a>
      <a href="/contact/">Contact</a>
    </div>
  </div>
</nav>

<div class="page-head">
  <h1>Book Chapters</h1>
  <p>Authored chapters in edited volumes from ACS, RSC, Springer, Elsevier, Wiley, De Gruyter, and CRC Press.</p>
</div>
<div class="sub-nav">Also see: <a href="/publications/">Journal Articles</a> <a href="/patents/">Patents</a></div>

<div class="search-container">
  <input type="text" id="yearInput" onkeyup="filterBySearch()" placeholder="Search title or year...">
  <button class="filter-btn active" onclick="filterByYear('all', this)">All</button>
  <button class="filter-btn" onclick="filterByYear('2025', this)">2025</button>
  <button class="filter-btn" onclick="filterByYear('2024', this)">2024</button>
  <button class="filter-btn" onclick="filterByYear('2023', this)">2023</button>
  <button class="filter-btn" onclick="filterByYear('2022', this)">2022</button>
</div>

<div class="chapter-container" id="chapterList">

  <div class="chapter-card" data-year="2025">
    <span class="chapter-year-label">2025</span>
    <span class="chapter-title">Chemical Waste-Derived Carbon Nanomaterials</span>
    <div class="chapter-authors">Deepak Kumar Chauhan, Kritika Sood, Venugopala Rao Battula, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">ACS Symposium Series, Vol. 1494, pp. 203&ndash;224 | ISBN: 9780841296619</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Potentiometric Devices for Biomarkers</span>
    <div class="chapter-authors">Arushi Arora, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Detection Science Series, RSC, pp. 146&ndash;165 | ISBN: 978-1-83767-323-0</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Scalable and Cost-Effective Synthesis of 2D Materials</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, Sunaina, S. Rana, S.K. Guchhait</div>
    <div class="chapter-meta">2D Materials: Sensing Applications, pp. 1&ndash;19 | ISBN: 978-981-97-6258-3</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Quantum Dots/One-Dimensional (1D) Composites</span>
    <div class="chapter-authors">S. Rana, V.M. Gaikwad, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Springer Nature Switzerland, pp. 177&ndash;191 | ISBN: 978-3-031-54779-9</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Green Synthesis of Nanomaterials and Their Applications for Sustainable Environment</span>
    <div class="chapter-authors">Khushbu Jain, <b>Krishna K. Yadav</b>, Neeru Dabas</div>
    <div class="chapter-meta">CRC Press, p. 19 | ISBN: 9781003473749</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Application of waste-synthesized nanoparticles in energy</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, Supriya Rana, Sunaina</div>
    <div class="chapter-meta">Elsevier, pp. 319&ndash;340 | ISBN: 9780443223365</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Standard reference materials</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, Sunaina, Menaka Jha</div>
    <div class="chapter-meta">Elsevier, p. 199 | ISBN: 978-0-323-90047-8</div>
  </div>

  <div class="chapter-card" data-year="2023">
    <span class="chapter-year-label">2023</span>
    <span class="chapter-title">Advanced fiber materials in optical and photonic applications</span>
    <div class="chapter-authors">R. Wadhwa, A. Arora, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Walter de Gruyter GmbH &amp; Co KG, p. 191 | ISBN: 9783110992892</div>
  </div>

  <div class="chapter-card" data-year="2023">
    <span class="chapter-year-label">2023</span>
    <span class="chapter-title">Overview of advanced fiber materials</span>
    <div class="chapter-authors">R. Wadhwa, A. Arora, S. Rana, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Walter de Gruyter GmbH &amp; Co KG, p. 1 | ISBN: 9783110992892</div>
  </div>

  <div class="chapter-card" data-year="2023">
    <span class="chapter-year-label">2023</span>
    <span class="chapter-title">Chemically Modified Carbon Nanotubes in 3D and 4D Printing</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, A. Arora, S. Jangra, M. Jha</div>
    <div class="chapter-meta">Wiley-VCH GmbH, pp. 419&ndash;439 | ISBN: 9783527838790</div>
  </div>

  <div class="chapter-card" data-year="2022">
    <span class="chapter-year-label">2022</span>
    <span class="chapter-title">Application of Surface Modified Carbon Nanotubes in Energy</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, N. Khan, M. Jha</div>
    <div class="chapter-meta">American Chemical Society, pp. 101&ndash;119 | ISBN: 9780841297463</div>
  </div>
</div>

<footer class="site-footer">
  <b style="color:var(--heading);">Dr. Krishna Kumar Yadav</b><br>
  <div style="margin:10px 0;">
    <a href="mailto:Krish91phy@usal.es">Email</a>
    <a href="https://scholar.google.com/citations?user=DsDWPX4AAAAJ" target="_blank" rel="noopener">Google Scholar</a>
    <a href="https://orcid.org/0000-0002-9063-7851" target="_blank" rel="noopener">ORCID</a>
  </div>
  &copy; 2026 Krishna Kumar Yadav. All rights reserved.
</footer>

<script>
function filterByYear(year, btn) {
  const cards = document.querySelectorAll('.chapter-card');
  document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('yearInput').value = '';
  cards.forEach(card => {
    card.style.display = (year === 'all' || card.getAttribute('data-year') === year) ? 'block' : 'none';
  });
}
function filterBySearch() {
  const input = document.getElementById('yearInput').value.toUpperCase();
  document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
  document.querySelectorAll('.chapter-card').forEach(card => {
    card.style.display = (card.textContent || card.innerText).toUpperCase().includes(input) ? 'block' : 'none';
  });
}
</script>
