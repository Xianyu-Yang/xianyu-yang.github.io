---
layout: default
title: "CV"
permalink: /cv/
author_profile: true
---

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
