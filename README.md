<!-- ===================== GLOBAL UI THEME ===================== -->
<style>
/* Hide GitHub repo title */
.markdown-body > h1:first-child {
  display: none !important;
}

/* --- GLOBAL COLORS --- */
:root {
  --primary: #1e88e5;
  --primary-dark: #1565c0;
  --background: #f7f9fc;
  --border: #dce3ef;
}

/* Page background */
body {
  background: var(--background) !important;
}

/* ===================== HERO BANNER ===================== */
.hero-header {
  position: relative;
  width: 100%;
  max-width: 1150px;
  margin: 0 auto 18px;
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 6px 20px rgba(0,0,0,0.15);
}

.hero-header img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  display: block;
}

.hero-title {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Segoe UI", Roboto, sans-serif;
  font-size: clamp(26px, 4vw, 40px);
  font-weight: 700;
  color: white;
  text-shadow: 0 3px 10px rgba(0,0,0,0.55);
  background: linear-gradient(0deg, rgba(0,0,0,0.42), rgba(0,0,0,0.15));
}

/* ===================== NAVIGATION BAR ===================== */
.nav-bar {
  text-align: center;
  padding: 12px 0;
  background: #ffffff;
  border-bottom: 2px solid var(--border);
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  font-family: "Segoe UI", sans-serif;
  font-size: 16px;
}

.nav-bar a {
  color: var(--primary);
  text-decoration: none;
  font-weight: 600;
  padding: 6px 10px;
  transition: 0.3s ease;
}

.nav-bar a:hover {
  color: var(--primary-dark);
  text-decoration: underline;
}

/* ===================== DROPDOWN MENU ===================== */
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-toggle {
  cursor: pointer;
  color: var(--primary);
  font-weight: 700;
}

.dropdown-content {
  display: none;
  position: absolute;
  top: 100%;
  left: 0%;
  min-width: 230px;
  background: white;
  border: 1px solid var(--border);
  border-radius: 8px;
  box-shadow: 0px 8px 18px rgba(0,0,0,0.12);
  z-index: 9999;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown-content a {
  display: block;
  padding: 10px 16px;
  color: var(--primary);
  font-size: 14px;
  text-decoration: none;
  border-bottom: 1px solid #eee;
}

.dropdown-content a:hover {
  background: #eef6ff;
  color: var(--primary-dark);
}

.dropdown-content a:last-child {
  border-bottom: none;
}

/* Fix clipping on GitHub pages */
.markdown-body { overflow: visible !important; }
</style>


<!-- ===================== HERO HEADER ===================== -->
<div class="hero-header">
  /assets/header.jpg
  <div class="hero-title">
    Dr. Krishna Kumar Yadav
  </div>
</div>


<!-- ===================== NAVIGATION BAR ===================== -->
<div class="nav-bar">
  /🏠 Home</a> | 
  /experience/👨‍🔬 Experience</a> | 
  /instrumentation/🔬 Instrumentation</a> | 
  /impact/📈 Impact</a> | 

  <span class="dropdown">
    <a class="dropdown-toggle">📚 Publications ▾</a>
    <span class="dropdown-content">
      /patents/1. Patents</a>
      /Book_Chapters/2. Book Chapters</a>
      /publications/3. Peer‑Reviewed Journal Articles</a>
    </span>
  </span> |

  /contact/📬 Contact</a>
</div>


<!-- ===================== MAIN CONTENT (unchanged) ===================== -->

# Dr. Krishna Kumar Yadav 
### Post-Doctoral Fellow | University of Salamanca, Spain 🇪🇸

---

## Welcome
Welcome to my professional academic website. I am a physicist specializing in Nanotechnology, Energy, Device Fabrication, and Advanced Material Synthesis, with a particular focus on Metal hexaboride. I am a proactive learner, constantly integrating modern tools like **Artificial Intelligence** to accelerate scientific discovery and automate data analysis.

---

### 📸 Research & Lab Gallery

<div align="center">
<table style="border: none; border-collapse: collapse;">
<tr>
<td style="padding: 10px; border: none;"><img src="photo1.jpg" height="320" style="border-radius: 10px;"></td>
<td style="padding: 10px; border: none;"><img src="photo2.jpg" height="320" style="border-radius: 10px;"></td>
</tr>
<tr>
<td style="padding: 10px; border: none;"><img src="photo3.jpg" height="320" style="border-radius: 10px;"></td>
<td style="padding: 10px; border: none;"><img src="photo4.jpg" height="320" style="border-radius: 10px;"></td>
</tr>
</table>
</div>

---

### 📍 Current Focus
Currently advancing the characterization of two‑dimensional (2D) transition metal dichalcogenides (TMDs), establishing a scalable platform for Schottky barrier quantification using KPFM, and fabricating Schottky‑junction solar cells at the **University of Salamanca**, Spain.

---

📧 **Contact:** krish91phy@usal.es
