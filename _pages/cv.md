---
layout: archive
title: "Short CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A more complete PDF version can be found <a href="/files/Lalancette_CV_web.pdf">here</a>.

<h2>Education</h2>
  <ul>
    <li>Ph.D. in Statistics, University of Toronto, 2022 (expected)</li>
    <li>M.Sc. in Statistics, Université de Montréal, 2017</li>
    <li>B.Sc. in Mathematics, Université de Montréal, 2015</li>
  </ul>

<h2>Scholarships and awards</h2>
  <ul>{% for post in site.awards reversed %}
    <li>
      {{post.title}}<br>
      Awarded by <i>{{post.organization}}</i>,
      {% if post.dateend %}
        {{ post.date | date: "%m/%Y" }}-{{ post.dateend | date: "%m/%Y" }}<br>
      {% else %}
        {{ post.date | date: "%m/%Y" }}<br>
      {% endif %}
      <small style="font-size:75%;">Value: {{post.value}}</small>
    </li>
  {% endfor %}</ul>

<h2>Publications</h2>
  <ul>{% for post in site.publications reversed %}
    <!-- {% include archive-single-cv.html %} -->
    <li>
      {{post.authorsshort}} "{{post.title}}" ({{ post.date | default: "1900-01-01" | date: "%Y" }}).
	  <br><i>{{post.venue}}</i>
      <!--{% if post.macollection == "accepted" %}
        <br>To appear in <i>{{post.venue}}</i>
	  {& elsif post.macollection == "published" %}
		<br><i>{{post.venue}}</i>
      {% endif %}-->
    </li>
  {% endfor %}</ul>

<h2>Talks and presentations</h2>
  <ul>{% for post in site.talks reversed %}
    <!-- {% include archive-single-talk-cv.html %} -->
    <li>
      "{{post.title}}"<br>
      {{post.type}} at <i>{{post.venue}}.</i><br>
      <small style="font-size:75%;">{{post.location}}. {{post.date | default: "1900-01-01" | date: "%B %d, %Y" }}</small> <!-- This format used to describe the date is the "strftime format" -->
    </li>
  {% endfor %}</ul>

<h2>Teaching experience</h2>
<h3>As a course instructor</h3>
  <ul>{% for post in site.teaching reversed %}
    <li>
      {{post.title}} ({{post.type}})<br>
      <small style="font-size:75%;">{{post.venue}}, {{post.semester}}</small>
    </li>
  {% endfor %}</ul>
<h3>As a teaching assistant</h3>
  <ul>
    <li>
      Statistical Consultation, Communication, and Collaboration (Undergraduate course)<br>
      <small style="font-size:75%;">University of Toronto, Fall 2018 - Spring 2019</small>
    </li>
    <li>
      Various undergraduate courses in Statistics and Probability<br>
      <small style="font-size:75%;">Université de Montréal, Spring 2015 - Fall 2016</small>
    </li>
  </ul>

<h2>Service and leadership</h2>
  <ul>
    <li>I have served as a reviewer for the <a href="https://www.tandfonline.com/toc/ucgs20/current">Journal of Computational and Graphical Statistics</a>, for <a href="https://www.springer.com/journal/10687">Extremes</a> and for the <a href="https://rss.onlinelibrary.wiley.com/journal/14679868">Journal of the Royal Statistical Society: Series B</a>.</li>
  <li>I chaired the organizing committee for the <a href="http://www.fields.utoronto.ca/activities/18-19/stats-research-day">2019 edition</a> of the Statistics Graduate Student Research Day, at the Fields Institute. Responsibilities included inviting speakers, securing space and funding, managing most of the local arrangements, supervising and animating the event.</li>
    <li>I was an executive member of my graduate student union at the Université de Montréal in 2016-2017 and at the University of Toronto in 2018-2019 (as president).</li>
  </ul>
  
