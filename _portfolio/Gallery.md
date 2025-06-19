---
layout: single
title: "Gallery"
collection: portfolio
permalink: /portfolio/gallery/
---

{% include base_path %}

<style>
  /* outer spacing */
  .gallery-timeline {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
  }

  /* date headings */
  .gallery-timeline h2 {
    margin-top: 3rem;
    font-size: 1.5rem;
    border-bottom: 2px solid #e0e0e0;
    padding-bottom: 0.5rem;
    color: currentColor;
  }

  /* grid wrapper */
  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px,1fr));
    grid-gap: 1rem;
    margin-top: 1rem;
  }

  /* each image + caption */
  .gallery-grid figure {
    margin: 0;
    background: var(--color-canvas-subtle);
    border-radius: 4px;
    overflow: hidden;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }
  .gallery-grid img {
    display: block;
    width: 100%;
    height: auto;
  }
  .gallery-grid figcaption {
    padding: 0.5rem;
    font-size: 0.9rem;
    color: #222;
    text-align: center;
    background: rgba(255,255,255,0.85);
  }
  
  /* Dark‐mode override: dark background + light text */
  @media (prefers-color-scheme: dark) {
    .gallery-grid figcaption {
      background: rgba(0,0,0,0.7);
      color: #eee;
    }
  }
</style>

<div class="gallery-timeline">

  <h2>May - July 2024</h2>
  <div class="gallery-grid">
    <figure>
      <img src="{{ '/images/gallery/profile.png' | relative_url }}" alt="Event 4">
      <figcaption>@ MIT</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/new york.jpg' | relative_url }}" alt="Event 4">
      <figcaption>@ New York (93rd floor)</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/harvard.jpg' | relative_url }}" alt="Event 4">
      <figcaption>@ Harvard Medical School</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/mit_.jpg' | relative_url }}" alt="Event 4">
      <figcaption>@ MIT</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/gallery/advik.jpg' | relative_url }}" alt="Event 1">
      <figcaption>Me teaching Advik at Boston, US</figcaption>
    </figure>
    <!-- … -->
  </div>

  <!-- May 2025 -->
  <h2>Oct 2023</h2>
  <div class="gallery-grid">
    <figure>
      <img src="{{ '/images/gallery/inno.jpg' | relative_url }}" alt="Event 3">
      <figcaption>Ganit Mela</figcaption>
    </figure>
    <!-- … -->
  </div>

</div>
