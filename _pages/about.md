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
Hi! I am a postdoctoral researcher at ETH Zürich studying how tree populations persist, recover, and shift under environmental change. My work combines plant demography, species distribution thinking, long-term forest data, and comparative life-history theory to understand how forests maintain biodiversity and ecosystem function in a rapidly changing world.

I am especially interested in the hidden stories inside tree data: why some species persist at their range margins, how demographic trade-offs shape coexistence, and when restoration trajectories lead to stable, diverse, and carbon-rich forests.

Outside research, I am usually outdoors: hiking mountain trails, swimming in alpine lakes, or skiing through winter landscapes.

# Research Focus

<div class="research-focus-grid">
  <section>
    <h3>Forest Demography</h3>
    <p>Quantifying how survival, growth, recruitment, and fecundity shape population persistence and recovery.</p>
  </section>
  <section>
    <h3>Range Limits</h3>
    <p>Studying how demographic performance and environmental gradients constrain where tree species occur.</p>
  </section>
  <section>
    <h3>Restoration Dynamics</h3>
    <p>Linking long-term monitoring data to biodiversity recovery, community assembly, and forest carbon storage.</p>
  </section>
</div>

<p class="research-keywords">
  Forest dynamics · Species diversity · Species range limits · Ecological restoration · Tree demography · Life-history theory
</p>

<figure style="text-align: center;">
  <img src="/images/Research topics.png" alt="Overview of Xianyu Yang's research topics in forest dynamics, species diversity, range limits, restoration, tree demography, and life-history theory." style="width: 70%;" loading="lazy">
</figure>

# News

- **2026-07** I will attend the 2026 Ecological Society of America Annual Meeting in Salt Lake City, USA.
- **2026-03** Our paper on transient dynamics during tree recovery after logging was accepted by _Journal of Plant Ecology_.
- **2025-08** I was selected to join the Junior Editorial Board of _Journal of Plant Ecology_ and _Forestry Research_.

<style>
.research-focus-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 14px;
  margin: 1.2rem 0 1rem;
}

.research-focus-grid section {
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  padding: 16px;
  background: #fbfbfb;
}

.research-focus-grid h3 {
  margin-top: 0;
  margin-bottom: 0.4rem;
  font-size: 1rem;
}

.research-focus-grid p {
  margin-bottom: 0;
  font-size: 0.92rem;
}

.research-keywords {
  font-weight: 600;
}

@media (max-width: 800px) {
  .research-focus-grid {
    grid-template-columns: 1fr;
  }
}
</style>
