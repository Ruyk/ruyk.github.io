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
* B.S. in Universidad de La Laguna, 2006
* M.S. in Universidad de La Laguna, 2009
* Ph.D in Universidad de La Laguna, 2012

Work experience
======
...
  
Skills
======
* C++
* SYCL/OpenCL/CUDA
* OpenACC

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
  