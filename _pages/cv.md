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
* Computing Engineer (Ingeniería en Informática), Facultad de Ingeniería y Ciencias Hídricas, Universidad Nacional del Litoral, May 2020
* Ph.D in Engineering (mention on Signals, Systems and Artificial Intelligence), Facultad de Ingeniería y Ciencias Hídricas, Universidad Nacional del Litoral, 2024 (expected)

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
