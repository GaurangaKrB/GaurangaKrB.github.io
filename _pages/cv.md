---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- 1) Prevent user zooming on mobile -->
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

<style>
  /* 2) Full-screen, no page margins */
  .pdf-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    overflow-y: auto;   /* vertical scroll only */
    overflow-x: hidden; /* hide any horizontal scroll */
    margin: 0;
    padding: 0;
  }

  /* 3) Remove any iframe borders and force block layout */
  .pdf-container iframe {
    display: block;
    width: 100%;
    height: 100%;
    border: none;
  }

  /* 4) Disable pinch-zoom on touch devices (horizontal only) */
  html, body {
    touch-action: pan-y;
  }
</style>

<div class="pdf-container">
  <iframe
    src="{{ '/assets/cv.pdf' | relative_url }}#toolbar=0&navpanes=0&scrollbar=0&zoom=page-width"
    title="Curriculum Vitae">
  </iframe>
</div>
