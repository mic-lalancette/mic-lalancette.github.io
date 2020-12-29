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

<h2>Education</h2>
  <ul>
    <li>Ph.D. in Statistics, University of Toronto, 2021 (expected)</li>
    <li>M.Sc. in Statistics, Université de Montréal, 2017</li>
    <li>B.S. in Mathematics, Université de Montréal, 2015</li>
  </ul>

<h2>Scholarships and Awards</h2>
  <ul>
    <li>First scholarship</li>
    <li>Second scholarship</li>
  </ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    <!-- {% include archive-single-cv.html %} -->
    <li>{{post.title}}
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
