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
  .pdf-container {
    max-width: 1000px;
    margin: 1.5rem auto;
    height: 75vh;
    overflow-y: auto;
    overflow-x: hidden;
    border-radius: 4px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    border: 1px solid #e0e0e0;
  }
  .pdf-container img {
    display: block;
    width: 100%;
    height: auto;
  }

  
  .cv-buttons {
    text-align: center;
    margin: 1rem 0;
  }
  .cv-buttons a {
    display: inline-block;
    margin: 0 .5rem;
    padding: .4rem .8rem;
    background-color: #007acc;
    color: #fff;
    border-radius: 4px;
    text-decoration: none;
    font-size: 0.9rem;
  }
  .cv-buttons a:hover {
    background-color: #005fa3;
  }
</style>

<div class="cv-buttons">
  <a href="{{ '/assets/cv_tall.jpg' | relative_url }}" download>Download as JPG</a>
  {% if site.static_files | where: "path", "/assets/cv.pdf" | size > 0 %}
    <a href="{{ '/assets/cv.pdf' | relative_url }}" download>Download as PDF</a>
  {% endif %}
  <a href="javascript:window.print()">Print CV</a>
</div>

![My CV]({{ '/assets/cv_long.jpg' | relative_url }})

