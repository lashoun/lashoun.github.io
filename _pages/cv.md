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
* Ph.D in Computer Science, Télécom Paris, 2024 (expected)
* M.S. in Computer Science and Engineering, École polytechnique, 2021
* M.S. in Computer Science and Engineering, Télécom Paris, 2021
* Preparatory School MPSI-MP*, Lycée privé Sainte-Geneviève, 2014-2016

Work experience
======

* February 2021 - Today: Ph.D Student
  * [Télécom Paris](https://www.telecom-paris.fr/en/home)
  * Currently studying Automatic Story Generation
  * Superviors: [Fabian M. Suchanek](https://www.suchanek.name/) and [Chloé Clavel](https://clavel.wp.imt.fr/)

* July-December 2020: Machine Learning Research Intern
  * [DeepLife](https://www.deeplife.co/)
  * Designed and benchmarked algorithms for predicting the evolution of biological cell states
  * Supervisor: Jean-Baptiste Morlot

* March-July 2019: Research Intern
  * Télécom Paris
  * Designed a clustering algorithm capable of one-shot learning and object description
  * Supervisor: Jean-Louis Dessalles
  
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
