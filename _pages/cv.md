---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, Université Libre de Bruxelles, Belgium, 2019
* M.S. in Computer Science, Université Libre de Bruxelles, Belgium, 2020
* Ph.D in Computer Science, Reykjavik University, 2023 (expected)

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Tools
======
  <ul>{% for post in site.tools %}
    {% include archive-single-tool-cv.html %}
  {% endfor %}</ul>
