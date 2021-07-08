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
* Ph.D in Applied and Interdisciplinary Mathematics and Scientific Computing, University of Michigan, 2021 (expected)
* M.S. in Mathematics, Brigham Young University, 2015
* B.S. in Physics (Magna cum Laude), Brigham Young University, 2013

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
  
Skills
======
* C++,  Python, and MATLAB
* OpenMP, OpenACC, CUDA and MPI

Courses and Certifications
==========================
* NVIDIA Deep Learning Institute, Fundamentals of Accelerated Computing with CUDA C/C++, October 2020.
* US Particle Accelerator School on Plasma-based acceleration, San Diego, January 2020.
* CERN Accelerator School on high gradient wakefield accelerators, March 11-22 2019.
