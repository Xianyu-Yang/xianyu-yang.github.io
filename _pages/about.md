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
  </figure>
  <figure>
    <img src="/images/life/hiking1.jpg" alt="Mountain hike" loading="lazy">
  </figure>
  <figure>
    <img src="/images/life/hiking2.jpg" alt="Winter ski" loading="lazy">
  </figure>
    <figure>
    <img src="/images/life/skii.jpg" alt="Winter ski" loading="lazy">
  </figure>
</div>

<style>
.life-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* 两列 */
  gap: 15px; /* 图片间距 */
}

.life-grid figure {
  margin: 0;
  border-radius: 10px;
  overflow: hidden;
}

.life-grid img {
  width: 100%;
  height: auto; /* 等比例缩放 */
  display: block;
  border-radius: 10px;
}

.life-grid figcaption {
  text-align: center;
  font-size: 0.9rem;
  opacity: 0.75;
  margin-top: 6px;
}
</style>

