---
permalink: /
title: "Welcome to My Website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Put this wherever you want the quote to appear -->
<blockquote class="hero-quote">
  “The greater danger for most of us lies not in setting our aim too high and falling short;  
  but in setting our aim too low, and achieving our mark.”
  <footer>― Michelangelo Buonarroti</footer>
</blockquote>

<style>
  .hero-quote {
    max-width: 800px;           /* prevent it from getting too wide */
    margin: 4rem auto;          /* centered with vertical breathing room */
    font-size: 2.5rem;          /* big text */
    line-height: 1.3;           /* comfortable reading */
    font-style: italic;         /* classic quote style */
    text-align: center;         /* center the text block */
    color: #222;                /* dark gray on light bg */
  }
  .hero-quote footer {
    margin-top: 1rem;
    font-size: 1.2rem;          /* smaller author credit */
    font-style: normal;
    font-weight: 500;
    text-align: right;          /* align the credit to the right */
    color: #555;
  }

  /* Responsive down-scale on small screens */
  @media (max-width: 600px) {
    .hero-quote {
      font-size: 1.8rem;
      margin: 2rem auto;
    }
    .hero-quote footer {
      font-size: 1rem;
    }
  }
</style>


I am a researcher in AI and ML. My primary research areas include Causal AI, RL, and Gen AI. Additionally, I apply ML methodologies to interdisciplinary problems across Computational Biology, Public Health, Computational Linguistics (e.g., Psychology).

I transitioned from the graduate program in Mathematics at IIT Kharagpur to complete my Master’s degree in Data Science at the Chennai Mathematical Institute (CMI), graduating in 2025. In 2024, I was honored to receive the [Khorana Scholarship](https://iusstf.org/khorana-program-for-scholars) to spend my summer at Harvard Medical School under the mentorship of [Prof. Yu-Hua Tseng](https://yhtsenglab.org/).

Outside my professional pursuits, I cherish diverse intellectual and recreational activities: cinematic arts (especially dramatic narratives), Chess, puzzle-solving, competitive programming, travel, photography, sketching, and writing philosophical and biographical articles. You can explore more of my thoughts and experiences in the [blogs](https://gaurangakrb.github.io/year-archive/) section.

I am always eager to connect, exchange ideas, and collaborate. Please feel free to reach out through any of my social media platforms.

<style>
  /* news-feed container */
  .news-list {
    list-style: none;
    padding: 0;
    margin: 2rem 0;
  }

  /* each news item */
  .news-item {
    display: flex;
    align-items: flex-start;
    border-bottom: 1px solid #e0e0e0;
    padding: 1rem 0;
  }
  .news-item:last-child {
    border-bottom: none;
  }

  /* date on the left: inherits theme text color, then mutes via opacity */
  .news-item time {
    flex: 0 0 120px;
    color: currentColor;
    opacity: 0.6;
    font-weight: bold;
  }

  /* content on the right */
  .news-content {
    flex: 1;
  }
  .news-content a {
    font-size: 1.05rem;
    font-weight: 600;
    color: #007acc;
    text-decoration: none;
  }
  .news-content a:hover {
    text-decoration: underline;
  }
  .news-content p {
    margin: 0.25rem 0 0;
    color: #333;
    font-size: 0.95rem;
  }
</style>

## Latest News

<ul class="news-list">
  <li class="news-item">
    <time datetime="2025-06-08">June 08, 2025</time>
    <div class="news-content">
      Will be joining TCS Research.
    </div>
  </li>
  <li class="news-item">
    <time datetime="2025-05-07">May 07, 2025</time>
    <div class="news-content">
      Started working in two independent projects. One with 
      <a href="https://scholar.google.co.in/citations?user=Ip1c2OcAAAAJ&amp;hl=en" target="_blank" rel="noopener">
        Dr. Raghav Kulkarni
      </a> in computational psychology &amp; one with 
      <a href="https://surajitray.org/" target="_blank" rel="noopener">
        Prof. Surajit Sen
      </a> in Causal inference in medical imaging.
    </div>
  </li>
  <li class="news-item">
    <time datetime="2025-05-03">April 05, 2025</time>
    <div class="news-content">
      Appereared for the last exam of my Masters Degree.
    </div>
  </li>
</ul>
