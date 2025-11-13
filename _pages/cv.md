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
* PhD in Astrophysics, CEA / Université Paris Cité, 2021-2024
* M.S. in Astrophysics, Université Côte d'Azur, 2019-2021
* B.S. in Physics, Université Côte d'Azur, 2016-2019
* Baccalauréat Scientifique, spécialité mathématiques, Lycée Gustave Eiffel (Maputo - Mozambique), 2016

[You can download my complete academic CV here.](https://drive.google.com/file/d/1H2DzSkTDo_r7WaP7VMX7xCNe_s09S8TV/view?usp=sharing)

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
