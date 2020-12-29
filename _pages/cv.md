---
layout: archive
title: "Short CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A more complete PDF version can be found here.

Education
======
* Ph.D. in Statistics, University of Toronto, 2021 (expected)
* M.Sc. in Statistics, Université de Montréal, 2017
* B.S. in Mathematics, Université de Montréal, 2015

Scholarships and Awards
======
  <ul>
  <li>First scholarship</li>
  <li>Second scholarship</li>
  </ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
