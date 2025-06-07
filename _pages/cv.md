---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  /* Restrict to your content column and give it some breathing room */
  .pdf-container {
    max-width: 1000px;        /* roughly your site's text column width */
    margin: 1.5rem auto;     /* center and vertical spacing */
    height: 75vh;            /* 75% of viewport height */
    overflow-y: auto;        /* vertical scroll only */
    overflow-x: hidden;      
    border-radius: 4px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    border: 1px solid #e0e0e0;
  }

  .pdf-container iframe {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }
</style>

<div class="pdf-container">
  <iframe
    src="{{ '/assets/cv.pdf' | relative_url }}#toolbar=0&navpanes=0&scrollbar=0&zoom=page-width"
    title="Curriculum Vitae">
  </iframe>
</div>
