---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
Hi! I’m a postdoc at **ETH Zürich** curious about everything that makes forests tick, from how individual trees grow and survive to how whole ecosystems maintain their biodiversity, shift their ranges, and store carbon. I love digging into the stories hidden in tree data to understand how forests adapt and transform in our rapidly changing world.

When I’m off work, I’m usually outdoors, hiking along mountain trails on weekends, swimming in crystal-clear alpine lakes during the summer, or skiing through snowy landscapes in the winter.  

# 🔥 Areas of Emphasis
Forest Dynamics, Species Diversity, Species Range Limits, Ecological Restoration, Tree Demography, Life history Theory

# 📷 Gallery
<div class="life-grid">
  <figure>
    <img src="/images/life/Zurich-lake.jpg" alt="Zurich lake" loading="lazy">
    <figcaption>Zurich lake</figcaption>
  </figure>
  <figure>
    <img src="/images/life/hiking1.jpg" alt="Mountain hike" loading="lazy">
    <figcaption>Oeschinen Lake</figcaption>
  </figure>
  <figure>
    <img src="/images/life/hiking2.jpg" alt="Winter ski" loading="lazy">
    <figcaption>Grindelwald</figcaption>
  </figure>
    <figure>
    <img src="/images/life/hiking2.jpg" alt="Winter ski" loading="lazy">
    <figcaption>Spize</figcaption>
  </figure>
</div>

<style>
.life-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.life-grid figure {
  margin: 0;
  overflow: hidden;
  border-radius: 12px;
}

.life-grid img {
  width: 100%;
  height: 300px;          /* 调整等高卡片的高度 */
  object-fit: cover;      /* 保证整齐布局，轻微裁切 */
  transition: transform 0.3s ease;
}

.life-grid img:hover {
  transform: scale(1.05); /* 鼠标悬停时放大一点 */
}

.life-grid figcaption {
  text-align: center;
  font-size: 0.9rem;
  opacity: 0.75;
  margin-top: 6px;
}
</style>


