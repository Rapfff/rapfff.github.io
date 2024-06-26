---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[pdf](/files/Raphael Reynouard - CV.pdf)

Education
---------
* B.S. in Computer Science, Université Libre de Bruxelles, Belgium, 2019
* M.S. in Computer Science, Université Libre de Bruxelles, Belgium, 2020
* Ph.D in Computer Science, Reykjavik University, Iceland, 2023

Publications
---------
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Tools
---------
  <ul>{% for post in site.tools %}
    {% include archive-single-tool-cv.html %}
  {% endfor %}</ul>

Research activities
-------------------
  <ul>{% for post in site.ra %}
    {% include archive-single-ra-cv.html %}
  {% endfor %}</ul>

Languages
---------
* French (native)
* English (professional profeciency)

Skills
------
- Python
- Theory of Machine Learning
- PyTorch
- Markov models
