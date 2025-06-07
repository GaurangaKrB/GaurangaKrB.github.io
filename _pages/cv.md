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
  /* Container to give the PDF a card-like appearance */
  .pdf-container {
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    overflow: hidden;              /* hide any overflow */
    margin: 1.5rem 0;              /* space above/below */
  }
  .pdf-container iframe {
    border: none;                  /* remove the ugly default border */
    display: block;                /* remove inline whitespace */
    width: 100%;
    height: 80vh;                  /* adjust as needed */
  }
</style>

<div class="pdf-container">
  <iframe
    src="{{ '/assets/cv.pdf' | relative_url }}#toolbar=0&navpanes=0&scrollbar=0"
    title="Curriculum Vitae">
  </iframe>
</div>
