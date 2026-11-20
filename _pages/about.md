---
layout: feiye
permalink: /
title: "Personal Website of Hanzhang Wang"
redirect_from:
  - /about/
  - /about.html
---

<section class="section" id="about" aria-labelledby="about-heading">
  <h2 class="section-heading" id="about-heading">About Me</h2>
  <div class="intro">
    <p>Hi, my name is Hanzhang Wang (王含章). I am a first-year Ph.D. student in the Department of Computer Science at City University of Hong Kong (CityUHK), advised by <a href="https://gavenma.github.io/">Ziye Ma</a>. Before joining CityUHK, I graduated from Harbin Institute of Technology, Shenzhen. I always welcome opportunities for collaboration, so please feel free to reach out at <a href="mailto:hanzwang6-c@my.cityu.edu.hk">hanzwang6-c@my.cityu.edu.hk</a>.</p>
  </div>
</section>

<section class="section" id="research" aria-labelledby="research-heading">
  <h2 class="section-heading" id="research-heading">Research Interests</h2>
  <p>My research interests focus on:</p>
  <ul class="research-list">
    <li><strong>LLM Pretraining:</strong> Improving pretraining itself and enhancing generalization to downstream tasks.</li>
    <li><strong>Efficient AI:</strong> Developing efficient methods for large language models, with a focus on model quantization.</li>
  </ul>
</section>

{% include feiye-publications.html %}

{% assign awards_page = site.pages | where: "permalink", "/awards/" | first %}
{{ awards_page.content }}

<section class="section" id="hobbies" aria-labelledby="hobbies-heading">
  <h2 class="section-heading" id="hobbies-heading">Hobbies : )</h2>
  <p>I like listening to music, watching movies, and working out.</p>
</section>
