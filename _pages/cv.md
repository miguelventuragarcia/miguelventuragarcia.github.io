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
* Ph.D in Mathematics and Applications, NOVA FCT, 2030 (expected)
* M.S. in Mathematics and Applications, NOVA FCT, 2026
* B.S. in Mathematics, NOVA FCT, 2024

Work experience
======
* Fall 2024: Research Assistant
  * NOVA FCT
  * Supervisor: João Cabral and Ana Casimiro

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
