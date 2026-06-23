---
layout: default
title: "Gallery"
permalink: /gallery/
author_profile: true
---

# Gallery

<p>A few moments from life around Switzerland and the mountains.</p>

<div class="life-grid">
  <figure>
    <img src="/images/life/Zurich-lake.jpg" alt="Lake Zürich on a clear day" loading="lazy">
    <figcaption>Lake Zürich</figcaption>
  </figure>
  <figure>
    <img src="/images/life/hiking1.jpg" alt="Mountain hiking trail in Switzerland" loading="lazy">
    <figcaption>Mountain hiking</figcaption>
  </figure>
  <figure>
    <img src="/images/life/hiking2.jpg" alt="Alpine hiking landscape" loading="lazy">
    <figcaption>Alpine trails</figcaption>
  </figure>
  <figure>
    <img src="/images/life/skii.jpg" alt="Skiing in a snowy mountain landscape" loading="lazy">
    <figcaption>Skiing</figcaption>
  </figure>
  <figure>
    <img src="/images/life/St.Mortiz.jpg" alt="St. Moritz mountain landscape" loading="lazy">
    <figcaption>St. Moritz</figcaption>
  </figure>
  <figure>
    <img src="/images/life/Aletsch Glacier.jpg" alt="Aletsch Glacier in Switzerland" loading="lazy">
    <figcaption>Aletsch Glacier</figcaption>
  </figure>
</div>

<style>
.life-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}

.life-grid figure {
  margin: 0;
}

.life-grid img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
  border-radius: 8px;
}

.life-grid figcaption {
  text-align: center;
  font-size: 0.9rem;
  opacity: 0.75;
  margin-top: 6px;
}

@media (max-width: 700px) {
  .life-grid {
    grid-template-columns: 1fr;
  }
}
</style>
