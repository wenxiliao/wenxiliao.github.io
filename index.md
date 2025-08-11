---
layout: home
title: Wenxi Liao
subtitle: Nature-based solutions
---
<style>
/* Hero banner */
.hero {
  position: relative;
  width: 100%;
  height: 360px;               /* adjust height to taste */
  border-radius: 10px;
  overflow: hidden;
  margin-bottom: 24px;
}

/* Background image with dark overlay */
.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(rgba(0,0,0,0.35), rgba(0,0,0,0.35)), /* dark overlay */
    url("/images/GRITLab2_banner.JPG") center/cover no-repeat;    /* your banner */
  filter: saturate(105%);
}

/* Text overlay */
.hero__content {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 0 6%;
  color: #fff;
  text-shadow: 0 2px 10px rgba(0,0,0,0.35);
}

.hero__title {
  font-size: clamp(26px, 4vw, 44px);
  font-weight: 700;
  margin: 0 0 8px 0;
}

.hero__subtitle {
  font-size: clamp(14px, 2.2vw, 20px);
  opacity: 0.95;
  margin-bottom: 14px;
  max-width: 1100px;
}

.hero__links a {
  display: inline-block;
  margin-right: 10px;
  margin-top: 6px;
  padding: 8px 14px;
  border-radius: 999px;
  background: rgba(255,255,255,0.15);
  color: #fff !important;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.2s ease;
}
.hero__links a:hover { background: rgba(255,255,255,0.28); }

/* Section headings spacing */
.section { margin-top: 28px; }
</style>

<div class="hero" role="img" aria-label="Wenxi Lab banner image">
  <div class="hero__content">
    <div class="hero__title">Wenxi Liao Lab</div>
    <div class="hero__subtitle">
      Climate-adaptive blue-green infrastructure • Biochar-enabled stormwater treatment •
      Micro/nanoplastics removal • Urban hydrology & remote sensing
    </div>
    <div class="hero__links">
      <a href="/projects/">Projects</a>
      <a href="/team/">Team</a>
      <a href="/publications/">Publications</a>
      <a href="/contact/">Contact</a>
    </div>
  </div>
</div>

Welcome to the Wenxi Liao Lab!  
We develop climate-adaptive blue-green infrastructure using experiments, remote sensing, and AI-based optimization.  
Our current research focuses on:
- Nature-based water treatment
- Geospatial urban environmental analysis 
- Urban ecosystem services

Check out our [Projects](/projects/), [People](/people/), and [Publications](/publications/) to learn more.

---

## Latest News
{% include posts.html %}
