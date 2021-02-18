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
* B.S. in Telematics Engineering, Litoral Polytechnic School (ESPOL), 2011
* M.S. in Cyber Security, Litoral Polytechnic School (ESPOL), 2016
* MSc. in Computational Applied Mathematics, University of Edinburgh, 2018
* Ph.D in Applied and Computational Mathematics, University of Edinburgh, 2022 (expected)

Work experience
======
* 2013 - 2017: University Teacher
  * Polytechnic School of the Litoral (ESPOL), Guayaquil, Ecuador
  * Courses: Single Variable Calculus, Multivariable Calculus, Linear Algebra, Differential Equations
  
Skills
======
* Programming languages
  * Main experience: Python, MATLAB, LaTex.
  * Other technologies: Julia, C++.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
