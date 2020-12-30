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

<h2>Publications</h2>
  <ul>{% for post in site.publications reversed %}
    <!-- {% include archive-single-cv.html %} -->
    <li>
      {{post.authorsshort}} "{{post.title}}."
      {% if post.macollection == "accepted" %}
        To appear in <i>{{post.venue}}</i>, {{ post.date | default: "1900-01-01" | date: "%Y" }}+
      {% endif %}
    </li>
  {% endfor %}</ul>

<h2>Talks</h2>
  <ul>{% for post in site.talks reversed %}
    <!-- {% include archive-single-talk-cv.html %} -->
    <li>
      "{{post.title}}." {{post.type}} at {{post.venue}}.<br>
      {{post.location}}. {{post.date | default: "1900-01-01" }}.
    </li>
  {% endfor %}</ul>

<h2>Teaching</h2>
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<h2>Service and leadership</h2>
  
