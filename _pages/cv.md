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
      "{{post.title}}."<br>
      {{post.type}} at <i>{{post.venue}}.</i><br>
      <small style="font-size:75%;">{{post.location}}. {{post.date | default: "1900-01-01" | date: "%B %d, %Y" }}</small> <!-- This format used to describe the date is the "strftime format" -->
    </li>
  {% endfor %}</ul>

<!--
<h2>Teaching Experience</h2>
  <h3>As course instructor</h3>
    <ul>{% for post in site.teaching reversed %}
      <li>
        {{post.title}} ({{post.type}}).<br>
        <small style="font-size:75%;">{{post.venue}}, {{post.semester}}</small>
      </li>
    {% endfor %}</ul>
  <h3>As teaching assistant</h3>
    <ul>
      <li>At University of Toronto: Statistical Consultation, Communication, and Collaboration</li>
      <li>At Université de Montréal: </li>
    </ul>
-->

<h2>Teaching Experience</h2>
  <h3>As a course instructor</h3>
    <ul>
      <li>
        test
      </li>
    </ul>
  <h3>As a teaching assistant</h3>

<h2>Service and leadership</h2>
  
