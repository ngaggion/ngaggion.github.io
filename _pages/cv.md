---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Computing Engineer, Facultad de Ingeniería y Ciencias Hídricas, Universidad Nacional del Litoral, May 2020
* PhD in Engineering, Facultad de Ingeniería y Ciencias Hídricas, Universidad Nacional del Litoral, 2024 (expected)

Research internships
======
- 1st July to 1st August 2022 - Research internship at CISTIB lab, Center for Computational Imaging & Simulation Tech-
nologies in Biomedicine, University of Leeds, Leeds, UK. Under the supervision of Prof. Alex Frangi.
- To begin: 1st October - Research internship at IPS2, Institute of Plant Sciences Paris-Saclay, 1 month visit, University
of Paris, Paris, France.

Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-paper-cv.html %}
  {% endfor %}</ul>
  
Awards
======
- 2021 - Best Poster Award - LatinX in CV (LXCV) Research at ICCV 2021
- 2021 - Student Travel Award - MICCAI 2021, 24th International Conference on Medical Image Computing and Computer Assisted Intervention
- 2019 - Honorific mention at Best Poster Award - Khipu: Latin American Meeting In Artificial Intelligence

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-course.html %}
  {% endfor %}</ul>
