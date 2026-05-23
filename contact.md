layout: default
title: Contact
permalink: /contact/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
:root{
  --primary:#1e88e5;
  --primary-dark:#1565c0;
  --nav-hover:#e3f2fd;
  --bg:#f7f9fc;
  --border:#dce3ef;
  --ink:#2a3440;
}
body { background:var(--bg) !important; font-family: "Segoe UI", sans-serif; color: var(--ink); }

/* Hero Banner */
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

/* NAVIGATION BAR */
.nav-bar { position: sticky; top: 10px; z-index: 10000; margin: 0 auto 25px; max-width: 1150px; }
.nav-inner { display: flex; align-items: center; justify-content: center; gap: 20px; padding: 6px 15px; background: #ffffff; border-radius: 12px; box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06); border: 1px solid var(--border); }
.nav-bar a, .dropdown-toggle { text-decoration: none; color: var(--primary-dark) !important; font-weight: 800; padding: 8px 16px; border-radius: 8px; transition: all 0.2s ease-in-out; display: inline-flex; align-items: center; gap: 8px; font-size: 17px; cursor: pointer; border: none; background: none; white-space: nowrap; }
.nav-bar a:hover, .dropdown:hover .dropdown-toggle { background: var(--nav-hover); color: var(--primary) !important; }

/* DROPDOWN - Corrected */
.dropdown { position: relative; }
.dropdown-content {
  display: none; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
  min-width: 180px; z-index: 9999; padding-top: 10px;
}
.dropdown:hover .dropdown-content { display: block; }
.dropdown-menu-box { background: #fff; border-radius: 10px; border: 1px solid var(--border); box-shadow: 0 12px 30px rgba(0,0,0,0.12); overflow: hidden; padding: 5px; }
.dropdown-menu-box a { display: block; padding: 10px 15px; font-size: 15px; color: var(--ink) !important; font-weight: 700; text-align: left; text-decoration: none; }

/* Contact Layout */
.contact-container { max-width: 1150px; margin: 40px auto; padding: 0 20px; display: flex; gap: 30px; flex-wrap: wrap; }
.contact-left { flex: 0.35; min-width: 300px; background: #fff; padding: 30px; border-radius: 16px; border: 1px solid var(--border); }
.contact-right { flex: 0.65; min-width: 400px; background: #fff; padding: 10px; border-radius: 16px; border: 1px solid var(--border); height: 400px; display: flex; align-items: center; justify-content: center; }

.contact-name { font-size: 28px; font-weight: 800; color: var(--primary-dark); margin-bottom: 5px; }
.contact-pos { font-size: 18px; color: #555; margin-bottom: 20px; }
.dept-title { font-size: 20px; font-style: italic; font-weight: 700; color: var(--primary-dark); margin-bottom: 10px; }
.profile-img-box { width: 150px; height: 150px; border-radius: 50%; background: #ddd; margin-bottom: 20px; border: 4px solid var(--primary); overflow: hidden; }
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

<div class="contact-container">
  <div class="contact-left">
    <div class="profile-img-box">
        <img src="/assets/profile.jpg" style="width:100%; height:100%; object-fit:cover;" alt="Profile">
    </div>
    <h1 class="contact-name">Dr. Krishna Kumar Yadav</h1>
    <div class="contact-pos">Postdoctoral Fellow</div>
    <div class="dept-title"><i>Department of Fundamental Physics, University of Salamanca</i></div>
    <div style="margin-top: 15px;">
      <i class="fas fa-envelope" style="color:var(--primary)"></i> 
      <a href="mailto:Krish91phy@usal.es" style="color:var(--primary); font-weight:700;">Krish91phy@usal.es</a>
    </div>
  </div>

  <div class="contact-right">
    
  </div>
</div>

<div style="text-align: center; margin-top: 40px;">
  <a href="/" style="padding: 12px 24px; background: var(--primary); color: white; border-radius: 8px; text-decoration: none; font-weight: 700;">🔙 Back to Home Page</a>
</div>
