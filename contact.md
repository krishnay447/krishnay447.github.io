---
layout: default
title: Contact
permalink: /contact/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
  .markdown-body > h1:first-child { display: none !important; }
  :root {
    --primary:#1e88e5; --primary-dark:#1565c0; --nav-hover:#e3f2fd;
    --bg:#f7f9fc; --border:#dce3ef; --ink:#2a3440;
  }
  body { background: var(--bg) !important; font-family: "Segoe UI", sans-serif; color: var(--ink); margin: 0; }

  /* HERO & NAV */
  .hero-header { position:relative; width:100%; max-width:1150px; margin:0 auto 20px; border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15); }
  .hero-header img { width:100%; height:260px; object-fit:cover; display:block; }
  .hero-title { position:absolute; inset:0; display:flex; align-items:center; justify-content:center; font-size:clamp(24px,4vw,40px); font-weight:700; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.55); background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20)); }
  .nav-bar { position: sticky; top: 10px; z-index: 10000; margin: 0 auto 25px; padding: 0 15px; max-width: 1150px; }
  .nav-inner { display: flex; align-items: center; justify-content: center; gap: 15px; padding: 8px 15px; background: #ffffff; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.05); border: 1px solid var(--border); flex-wrap: wrap; }
  .nav-bar a, .dropdown-toggle { text-decoration: none; color: var(--primary-dark) !important; font-weight: 800; padding: 6px 12px; border-radius: 8px; transition: 0.2s; display: inline-flex; align-items: center; gap: 5px; font-size: 15px; cursor: pointer; border: none; background: none; }
  .nav-bar a:hover, .dropdown:hover .dropdown-toggle { background: var(--nav-hover); color: var(--primary) !important; }

  /* DROPDOWN */
  .dropdown { position: relative; }
  .dropdown-content { display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%); min-width: 160px; z-index: 9999; padding-top: 10px; }
  .dropdown:hover .dropdown-content { display: block; }
  .dropdown-menu-box { background: #fff; border-radius: 8px; border: 1px solid var(--border); box-shadow: 0 8px 16px rgba(0,0,0,0.1); padding: 5px; }
  .dropdown-menu-box a { display: block; padding: 8px 12px; font-size: 14px; color: var(--ink) !important; text-decoration: none; }

  /* LAYOUT */
  .grid-container { max-width: 1150px; margin: 20px auto; padding: 0 20px; display: grid; grid-template-columns: 350px 1fr; gap: 20px; }
  .profile-card { background: #fff; padding: 30px; border-radius: 20px; border: 1px solid var(--border); text-align: center; }
  .map-card { background: #fff; padding: 20px; border-radius: 20px; border: 1px solid var(--border); }
  #map { width: 100%; height: 300px; border-radius: 12px; margin-top: 10px; border: 1px solid var(--border); }
  
  .location-gallery { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-top: 20px; }
  .loc-box { border-radius: 8px; overflow: hidden; border: 1px solid var(--border); height: 80px; }
  .loc-box img { width: 100%; height: 100%; object-fit: cover; }

  @media (max-width: 900px) { .grid-container { grid-template-columns: 1fr; } }
</style>

<div class="hero-header">
  <img src="/assets/header7.jpg" alt="Banner" />
  <div class="hero-title">Contact & Network</div>
</div>

<nav class="nav-bar">
  <div class="nav-inner">
    <a href="/">🏠 Home</a>
    <a href="/experience/">👨‍🔬 Experience</a>
    <a href="/impact/">📈 Impact</a>
    <div class="dropdown">
      <span class="dropdown-toggle">📚 Publications ▾</span>
      <div class="dropdown-content">
        <div class="dropdown-menu-box"><a href="/patents/">📜 Patents</a><a href="/Book_Chapters/">📖 Chapters</a><a href="/publications/">📝 Articles</a></div>
      </div>
    </div>
    <a href="/contact/">📬 Contact</a>
  </div>
</nav>

<div class="grid-container">
  <aside class="profile-card">
    <img src="/assets/profile.jpg" style="width:150px; height:150px; border-radius:50%; margin-bottom:15px; border:4px solid var(--nav-hover);">
    <h2 style="font-size:22px; font-weight:800; color:var(--ink); margin:0;">Dr. Krishna Kumar Yadav</h2>
    <p style="margin:5px 0;">Postdoctoral Fellow</p>
    <div style="font-size:16px; font-style:italic; font-weight:700; color:var(--primary-dark); margin-bottom:15px;">Department of Fundamental Physics, University of Salamanca</div>
    <a href="mailto:Krish91phy@usal.es" style="display:inline-block; padding:8px 16px; background:var(--primary); color:white; border-radius:20px; text-decoration:none; font-weight:600;"><i class="fas fa-envelope"></i> Krish91phy@usal.es</a>
  </aside>

  <section class="map-card">
    <h3 style="margin-top:0; color:var(--primary-dark); font-size:18px;">📍 Research Network</h3>
    <div id="map"></div>
    <div class="location-gallery">
      <a href="https://en.wikipedia.org/wiki/Gorakhpur" class="loc-box"><img src="/assets/gorakhpur.jpg" alt="Gorakhpur"></a>
      <a href="https://en.wikipedia.org/wiki/Mohali" class="loc-box"><img src="/assets/mohali.jpg" alt="Mohali"></a>
      <a href="https://en.wikipedia.org/wiki/Beersheba" class="loc-box"><img src="/assets/beersheba.jpg" alt="Beer Sheva"></a>
      <a href="https://en.wikipedia.org/wiki/Salamanca" class="loc-box"><img src="/assets/salamanca.jpg" alt="Salamanca"></a>
    </div>
  </section>
</div>

<div style="position: fixed; bottom: 20px; right: 20px; z-index: 9999; background: white; padding: 10px; border-radius: 8px; border: 1px solid var(--border); box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
  <script type="text/javascript">
    var sc_project=13250871; 
    var sc_invisible=0; 
    var sc_security="d8d12d18"; 
    var scJsHost = "https://";
    document.write("<sc"+"ript type='text/javascript' src='" + scJsHost+
    "statcounter.com/counter/counter.js'></"+"script>");
  </script>
  <noscript><div class="statcounter"><a title="Web Analytics Made Easy - Statcounter" href="https://statcounter.com/" target="_blank"><img class="statcounter" src="https://c.statcounter.com/13250871/0/d8d12d18/0/" alt="Web Analytics Made Easy - Statcounter" referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
</div>

<script src="https://apis.mappls.com/map_v3/map?layer=map&callback=initMap&key=mnqhensxdzjubccwihxdjvaehcwnlmcbfvcq"></script>

<script>
  function initMap() {
    var map = new mappls.Map('map', {
      center: [30, 40],
      zoom: 3
    });

    map.addListener('load', function() {
      const locations = [
        {pos: "40.9650,-5.6629", name: "Salamanca"},
        {pos: "31.2529,34.7915", name: "Beer Sheva"},
        {pos: "30.7046,76.7179", name: "Mohali"},
        {pos: "26.7606,83.3732", name: "Gorakhpur"}
      ];

      locations.forEach(loc => {
        mappls.pinMarker({map: map, pin: loc.pos, popupHtml: loc.name});
      });
    });
  }
</script>
