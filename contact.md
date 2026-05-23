---
layout: default
title: Contact
permalink: /contact/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />

<style>
:root{
  --primary:#1e88e5; --primary-dark:#1565c0; --nav-hover:#e3f2fd;
  --bg:#f7f9fc; --border:#dce3ef; --ink:#2a3440;
}
body { background:var(--bg) !important; font-family: "Segoe UI", sans-serif; color: var(--ink); }

/* HERO BANNER */
.hero-header{ position:relative; width:100%; max-width:1150px; margin:0 auto 20px; border-radius:14px; overflow:hidden; box-shadow:0 6px 20px rgba(0,0,0,0.15); }
.hero-header img{ width:100%; height:260px; object-fit:cover; display:block; }
.hero-title{ position:absolute; inset:0; display:flex; align-items:center; justify-content:center; font-size:clamp(28px,4vw,40px); font-weight:700; color:#fff; text-shadow:0 3px 10px rgba(0,0,0,0.55); background:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.20)); }

/* NAVIGATION BAR */
.nav-bar { position: sticky; top: 10px; z-index: 10000; margin: 0 auto 25px; max-width: 1150px; }
.nav-inner { display: flex; align-items: center; justify-content: center; gap: 20px; padding: 6px 15px; background: #ffffff; border-radius: 12px; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06); border: 1px solid var(--border); }
.nav-bar a, .dropdown-toggle { text-decoration: none; color: var(--primary-dark) !important; font-weight: 800; padding: 8px 16px; border-radius: 8px; transition: all 0.2s ease-in-out; display: inline-flex; align-items: center; gap: 8px; font-size: 17px; cursor: pointer; border: none; background: none; white-space: nowrap; }
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background: var(--nav-hover); color: var(--primary) !important; }

/* REFINED DROPDOWN */
.dropdown { position: relative; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
  min-width: 180px; z-index: 9999; padding-top: 10px;
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-menu-box { background: #fff; border-radius: 10px; border: 1px solid var(--border); box-shadow: 0 12px 30px rgba(0,0,0,0.12); overflow: hidden; padding: 5px; }
.dropdown-menu-box a { display: block; padding: 10px 15px; font-size: 15px; color: var(--ink) !important; font-weight: 700; text-align: left; text-decoration: none; }
.dropdown-menu-box a:hover { background: var(--nav-hover); color: var(--primary) !important; }

/* LAYOUT */
.grid-container { max-width: 1150px; margin: 40px auto; padding: 0 20px; display: grid; grid-template-columns: 350px 1fr; gap: 30px; }
.profile-card { background: #fff; padding: 40px; border-radius: 20px; border: 1px solid var(--border); text-align: center; box-shadow: 0 10px 30px rgba(0,0,0,0.05); }
.map-card { background: #fff; padding: 20px; border-radius: 20px; border: 1px solid var(--border); box-shadow: 0 10px 30px rgba(0,0,0,0.05); }
.loc-box { border-radius: 12px; overflow: hidden; border: 2px solid var(--border); transition: 0.3s; height: 100px; cursor: pointer; }
.loc-box:hover { border-color: var(--primary); transform: translateY(-5px); }
.loc-box img { width: 100%; height: 100%; object-fit: cover; }
.location-gallery { display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin-top: 25px; }
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

<div class="grid-container">
  <aside class="profile-card">
    <img src="/assets/profile.jpg" style="width:180px; height:180px; border-radius:50%; margin-bottom:20px; border:5px solid var(--nav-hover);">
    <h2 style="font-size:24px; font-weight:800; color:var(--ink);">Dr. Krishna Kumar Yadav</h2>
    <p>Postdoctoral Fellow</p>
    <div style="font-size:20px; font-style:italic; font-weight:700; color:var(--primary-dark); margin-bottom:20px;">
        <i>Department of Fundamental Physics, University of Salamanca</i>
    </div>
    <a href="mailto:Krish91phy@usal.es" style="display:inline-block; padding:10px 20px; background:var(--primary); color:white; border-radius:30px; text-decoration:none; font-weight:700;">
      <i class="fas fa-envelope"></i> Send Email
    </a>
  </aside>

  <section class="map-card">
    <h3 style="margin-top:0; color:var(--primary-dark); padding-bottom: 10px; border-bottom: 1px solid var(--border);">📍 Research Network</h3>
    <div id="map" style="width:100%; height:320px; border-radius:12px; margin-top:15px; z-index:1;"></div>
    
    <div class="location-gallery">
      <a href="https://en.wikipedia.org/wiki/Gorakhpur" class="loc-box"><img src="/assets/gorakhpur.jpg" alt="Gorakhpur"></a>
      <a href="https://en.wikipedia.org/wiki/Mohali" class="loc-box"><img src="/assets/mohali.jpg" alt="Mohali"></a>
      <a href="https://en.wikipedia.org/wiki/Beersheba" class="loc-box"><img src="/assets/beersheba.jpg" alt="Beer Sheva"></a>
      <a href="https://en.wikipedia.org/wiki/Salamanca" class="loc-box"><img src="/assets/salamanca.jpg" alt="Salamanca"></a>
    </div>
  </section>
</div>

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
    var map = L.map('map').setView([30, 40], 2);
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png').addTo(map);
    var locs = [
        {coords: [40.96, -5.66], name: 'Salamanca', color: 'green'},
        {coords: [31.25, 34.79], name: 'Beer Sheva', color: 'blue'},
        {coords: [30.70, 76.73], name: 'Mohali', color: 'orange'},
        {coords: [26.76, 83.37], name: 'Gorakhpur', color: 'orange'}
    ];
    locs.forEach(function(loc) {
        var icon = new L.Icon({
            iconUrl: 'https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-'+loc.color+'.png',
            shadowUrl: 'https://cdnjs.cloudflare.com/ajax/libs/leaflet/0.7.7/images/marker-shadow.png',
            iconSize: [25, 41], iconAnchor: [12, 41], popupAnchor: [1, -34], shadowSize: [41, 41]
        });
        L.marker(loc.coords, {icon: icon}).addTo(map).bindPopup(loc.name);
    });
</script>
