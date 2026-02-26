---
layout: default
title: Impact
permalink: /impact/
---

<style>
/* NAV – consistent across all pages */
.nav-bar {
  position: relative;            /* create a stacking context */
  z-index: 3000;                 /* sits above page content/headings */
  text-align: center;
  border-bottom: 2px solid #eee;
  padding: 10px 0 12px;
  font-family: sans-serif;
  background: #fff;              /* prevents transparency overlap */
}

/* Dropdown container */
.dropdown { 
  position: relative; 
  display: inline-block; 
}

/* The dropdown panel */
.dropdown-content {
  display: none;
  position: absolute;
  top: calc(100% + 6px);         /* drop below the trigger */
  left: 50%;
  transform: translateX(-50%);   /* center under the trigger */
  background-color: #ffffff;
  min-width: 230px;
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
  border: 1px solid #ddd;
  border-radius: 6px;
  z-index: 4000;                 /* higher than nav */
  text-align: left;
}

/* Show panel on hover */
.dropdown:hover .dropdown-content { display: block; }

/* Links inside dropdown */
.dropdown-content a {
  color: #0366d6 !important;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  font-size: 14px;
  border-bottom: 1px solid #f1f1f1;
}

.dropdown-content a:last-child { border-bottom: none; }
.dropdown-content a:hover { background-color: #f6f8fa; }

/* Optional: a little spacing below the nav so dropdown has room */
.nav-spacer { height: 0px; }
@media (max-width: 480px) { .nav-spacer { height: 4px; } }
</style>

<div class="nav-bar">
  <a href="https://krishnay447.github.io">🏠 Home</a> |
  <a href="https://krishnay447.github.io/experience">👨‍🔬 Experience</a> |
  <a href="https://krishnay447.github.io/instrumentation">🔬 Instrumentation</a> |
  <a href="https://krishnay447.github.io/impact">📈 Impact</a> |

  <div class="dropdown">
    <a href="javascript:void(0)" style="color:#0366d6; cursor:pointer; text-decoration:none; font-weight:bold;">
      📚 Publications ▾
    </a>
    <div class="dropdown-content">
      <a href="https://krishnay447.github.io/patents">1. Patents</a>
      <a href="https://krishnay447.github.io/book_chapters">2. Book Chapters</a>
      <a href="https://krishnay447.github.io/publications">3. Peer‑Reviewed Journal Articles</a>
    </div>
  </div> |
  <a href="https://krishnay447.github.io/contact">📬 Contact</a>
</div>
<div class="nav-spacer"></div>
---

# 📊 Scientific Impact & Publications

### 📈 Statistics
* **Publications:** 51 Peer-reviewed articles.
* **Book Chapters:** 11 Chapters.
* **Citations:** Add your citation count here.

---

### 🏆 Key Awards
* **CSIR-NET:** Qualified in Physical Science (2015).
* **Best Poster:** 9th Bangalore India Nano (2017).

---

## 💻 Digital Innovation & Software

### ⚡ Photocurrent Detector Tool
Developed AI-based software to automatically extract photocurrent parameters:
* Response Time  
* Detectivity  
* External Quantum Efficiency (EQE)

---

### 📄 PDF Management Platform
Created a research-focused tool for organizing and managing scientific PDF documents.

---

<a href="/">🔙 Back to Home</a>
