---
layout: home
title: Wenxi Liao
subtitle: Nature-based solutions
---
<img src="/images/GRITLab2_banner.JPG" alt="Lab Banner" style="width:100%; border-radius: 8px; margin-bottom: 20px;">

Welcome to the Wenxi Liao Lab!  
We develop climate-adaptive blue-green infrastructure using experiments, remote sensing, and AI-based optimization.  
Our current research focuses on:
- Nature-based water treatment
- Geospatial urban environmental analysis 
- Urban ecosystem services

Check out our [Projects](/projects/), [People](/people/), and [Publications](/publications/) to learn more.

---

## Latest News
<ul class="post-list">
  {% assign posts = site.posts | sort: "date" | reverse %}
  {% for post in posts limit: 5 %}
    <li style="margin-bottom:0.8rem;">
      <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a>
      <span> — {{ post.date | date: "%b %d, %Y" }}</span>
      {% if post.excerpt %}
        <div style="margin-top:0.2rem;">{{ post.excerpt | strip_html | truncate: 160 }}</div>
      {% endif %}
    </li>
  {% endfor %}
</ul>
