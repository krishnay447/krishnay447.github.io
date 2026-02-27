---
layout: default
title: Book Chapters
permalink: /Book_Chapters/
---

<style>
/* 1. HIDE GITHUB REPO TITLE */
.markdown-body > h1:first-child { display: none !important; }

:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --bg:#f7f9fc;
  --border:#dce3ef;
}
body { background:var(--bg) !important; font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif; }

/* 2. HERO BANNER */
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

/* 3. NAVIGATION BAR & STICKY DROPDOWN FIX */
.nav-bar {
  text-align: center; padding: 12px 0; background: #ffffff;
  border-bottom: 3px solid var(--border); box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  position: sticky; top: 0; z-index: 10000;
}
.nav-bar a, .dropdown-toggle {
  color: #444; text-decoration: none; font-weight: 600; padding: 10px 18px;
  margin: 0 2px; border-radius: 8px; transition: all 0.2s ease;
  display: inline-block; font-size: 15px; cursor: pointer; border: none; background: none;
}
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background-color: #e3f2fd; color: var(--primary-dark); }

.dropdown { position: relative; display: inline-block; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
  background: #ffffff; min-width: 250px; border-radius: 12px; border: 1px solid var(--border);
  box-shadow: 0 10px 30px rgba(0,0,0,0.15); z-index: 9999; overflow: hidden;
  padding-top: 10px; /* Bridge gap */
}
/* Invisible hover bridge */
.dropdown-content::before {
  content: ""; position: absolute; top: -15px; left: 0; width: 100%; height: 15px; background: transparent;
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-content a {
  display: block; padding: 12px 20px; border-bottom: 1px solid #f0f0f0;
  text-align: left; font-size: 14px; color: #444; text-decoration: none; border-radius: 0; margin: 0;
}
.dropdown-content a:hover { background: #f8fbff; color: var(--primary); }

/* 4. SCHOLAR & ORCID CARDS */
.profile-container {
  max-width: 950px; margin: 20px auto; display: flex; gap: 15px; padding: 0 20px;
}
.profile-link {
  flex: 1; display: flex; align-items: center; padding: 12px 20px;
  background: #fff; border: 1px solid var(--border); border-radius: 12px;
  text-decoration: none; transition: 0.3s; box-shadow: 0 2px 5px rgba(0,0,0,0.03);
}
.profile-link:hover { transform: translateY(-3px); border-color: var(--primary); box-shadow: 0 6px 15px rgba(0,0,0,0.1); }
.profile-link img { width: 30px; height: 30px; margin-right: 15px; }
.profile-label { display: block; font-size: 11px; color: #888; text-transform: uppercase; }
.profile-name { display: block; font-size: 15px; font-weight: 700; color: var(--primary-dark); }

/* 5. SEARCH & FILTER */
.search-container {
  max-width: 950px; margin: 15px auto; padding: 0 20px;
  display: flex; flex-wrap: wrap; gap: 10px; align-items: center;
}
#yearInput {
  padding: 8px 15px; border-radius: 8px; border: 1px solid var(--border);
  width: 200px; font-size: 14px; outline: none; transition: 0.3s;
}
#yearInput:focus { border-color: var(--primary); box-shadow: 0 0 0 3px rgba(30, 136, 229, 0.1); }
.filter-btn {
  padding: 7px 16px; border: 1px solid var(--border); background: #fff; color: #666;
  border-radius: 8px; cursor: pointer; font-weight: 600; font-size: 13px; transition: 0.2s;
}
.filter-btn:hover, .filter-btn.active { background: var(--primary); color: #fff; border-color: var(--primary); }

/* 6. CHAPTER CARDS */
.chapter-container { max-width: 950px; margin: 0 auto; padding: 0 20px; }
.chapter-card {
  background: #fff; padding: 22px; border-radius: 12px; border: 1px solid var(--border);
  margin-bottom: 15px; position: relative; transition: 0.3s; display: block;
}
.chapter-card:hover { border-color: var(--primary); box-shadow: 0 5px 15px rgba(0,0,0,0.05); }
.chapter-year-label {
  float: right; background: #e3f2fd; color: var(--primary);
  padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 800; border: 1px solid #bbdefb;
}
.chapter-title { color: var(--primary-dark); font-size: 17px; font-weight: 700; margin-bottom: 8px; display: block; line-height: 1.4; }
.chapter-authors { font-size: 14px; color: #555; margin-bottom: 6px; }
.chapter-meta { font-size: 13px; color: #888; font-style: italic; border-top: 1px solid #f0f0f0; padding-top: 8px; margin-top: 8px; }

.markdown-body { overflow: visible !important; }
@media (max-width: 600px) { .profile-container { flex-direction: column; } }
</style>

<div class="hero-header">
  <img src="/assets/header5.jpg" alt="Banner">
  <div class="hero-title">Krishna Kumar Yadav</div>
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

  </a>
</div>

<div class="search-container">
  <input type="text" id="yearInput" onkeyup="filterBySearch()" placeholder="🔍 Search Title or Year...">
  <button class="filter-btn active" onclick="filterByYear('all', this)">All</button>
  <button class="filter-btn" onclick="filterByYear('2025', this)">2025</button>
  <button class="filter-btn" onclick="filterByYear('2024', this)">2024</button>
  <button class="filter-btn" onclick="filterByYear('2023', this)">2023</button>
  <button class="filter-btn" onclick="filterByYear('2022', this)">2022</button>
</div>

<div class="chapter-container" id="chapterList">
  <h2 style="color: var(--primary-dark); border-left: 5px solid var(--primary); padding-left: 15px; margin-bottom: 25px;">📖 Authored Book Chapters</h2>

  <div class="chapter-card" data-year="2025">
    <span class="chapter-year-label">2025</span>
    <span class="chapter-title">Chemical Waste-Derived Carbon Nanomaterials</span>
    <div class="chapter-authors">Deepak Kumar Chauhan, Kritika Sood, Venugopala Rao Battula, <b>Krishna K Yadav</b></div>
    <div class="chapter-meta">ACS Symposium Series, Vol. 1494, pp. 203–224 | ISBN: 9780841296619</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Potentiometric Devices for Biomarkers</span>
    <div class="chapter-authors">Arushi Arora, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Detection Science Series, RSC, pp. 146–165 | ISBN: 978-1-83767-323-0</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Scalable and Cost-Effective Synthesis of 2D Materials</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, Sunaina, S Rana, SK Guchhait</div>
    <div class="chapter-meta">2D Materials: Sensing Applications, pp. 1–19 | ISBN: 978-981-97-6258-3</div>
  </div>

  <div class="chapter-card" data-year="2024">
    <span class="chapter-year-label">2024</span>
    <span class="chapter-title">Quantum Dots/One-Dimensional (1D) Composites</span>
    <div class="chapter-authors">S Rana, VM Gaikwad, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Springer Nature Switzerland, pp. 177–191 | ISBN: 978-3-031-54779-9</div>
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
    <div class="chapter-meta">Elsevier, pp. 319–340 | ISBN: 9780443223365</div>
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
    <div class="chapter-authors">R Wadhwa, A Arora, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Walter de Gruyter GmbH & Co KG, p. 191 | ISBN: 9783110992892</div>
  </div>

  <div class="chapter-card" data-year="2023">
    <span class="chapter-year-label">2023</span>
    <span class="chapter-title">Overview of advanced fiber materials</span>
    <div class="chapter-authors">R Wadhwa, A Arora, S Rana, <b>Krishna K. Yadav</b></div>
    <div class="chapter-meta">Walter de Gruyter GmbH & Co KG, p. 1 | ISBN: 9783110992892</div>
  </div>

  <div class="chapter-card" data-year="2023">
    <span class="chapter-year-label">2023</span>
    <span class="chapter-title">Chemically Modified Carbon Nanotubes in 3D and 4D Printing</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, A Arora, S Jangra, M Jha</div>
    <div class="chapter-meta">Wiley‑VCH GmbH, pp. 419–439 | ISBN: 9783527838790</div>
  </div>

  <div class="chapter-card" data-year="2022">
    <span class="chapter-year-label">2022</span>
    <span class="chapter-title">Application of Surface Modified Carbon Nanotubes in Energy</span>
    <div class="chapter-authors"><b>Krishna K. Yadav</b>, N Khan, M Jha</div>
    <div class="chapter-meta">American Chemical Society, pp. 101–119 | ISBN: 9780841297463</div>
  </div>
</div>

<script>
function filterByYear(year, btn) {
  const cards = document.querySelectorAll('.chapter-card');
  const buttons = document.querySelectorAll('.filter-btn');
  buttons.forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('yearInput').value = '';

  cards.forEach(card => {
    if (year === 'all' || card.getAttribute('data-year') === year) {
      card.style.display = 'block';
    } else {
      card.style.display = 'none';
    }
  });
}

function filterBySearch() {
  const input = document.getElementById('yearInput').value.toUpperCase();
  const cards = document.querySelectorAll('.chapter-card');
  const buttons = document.querySelectorAll('.filter-btn');
  buttons.forEach(b => b.classList.remove('active'));

  cards.forEach(card => {
    const text = card.textContent || card.innerText;
    card.style.display = text.toUpperCase().includes(input) ? 'block' : 'none';
  });
}
</script>

<p style="text-align: center; margin: 30px 0;">
  <a href="/" style="color: var(--primary); text-decoration: none; font-weight: 600;">[🔙 Back to Home Page]</a>
</p>
