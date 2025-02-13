---
layout: archive
title: "Short CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- A more complete PDF version can be found <a href="/files/cv.pdf">here</a>. -->
A more complete PDF version of my CV can be provided on demand.

<h2><u>Education</u></h2>
  <ul>
    <li>
		Ph.D. in Statistics, University of Toronto, 2022<br>
		Thesis: <a href="https://mic-lalancette.github.io/files/thesis_PhD.pdf">Statistical inference for tail dependence structures</a>
	</li>
    <li>
		M.Sc. in Statistics, Université de Montréal, 2017<br>
		Thesis: <a href="https://mic-lalancette.github.io/files/thesis_MSc.pdf">Convergence d'un algorithme de type Metropolis pour une distribution cible bimodale</a>
	</li>
    <li>
		B.Sc. in Mathematics, Université de Montréal, 2015
	</li>
  </ul>

<h2><u>Grants, scholarships and awards</u></h2>
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

<!--
<h2>Publications</h2>
  <ul>{% for post in site.publications reversed %}
    <!-- {% include archive-single-cv.html %} - ->
    <li>
      {{post.authorsshort}} "{{post.title}}" ({{ post.date | default: "1900-01-01" | date: "%Y" }}).
	  <br><i>{{post.venue}}</i>
      <!--{% if post.macollection == "accepted" %}
        <br>To appear in <i>{{post.venue}}</i>
	  {& elsif post.macollection == "published" %}
		<br><i>{{post.venue}}</i>
      {% endif %}- ->
    </li>
  {% endfor %}</ul>

<h2>Talks and presentations</h2>
  <ul>{% for post in site.talks reversed %}
    <!-- {% include archive-single-talk-cv.html %} - ->
    <li>
      "{{post.title}}"<br>
      {{post.type}} at <i>{{post.venue}}.</i><br>
      <small style="font-size:75%;">{{post.location}}. {{post.date | default: "1900-01-01" | date: "%B %d, %Y" }}</small> <!-- This format used to describe the date is the "strftime format" - ->
    </li>
  {% endfor %}</ul>
-->

<h2><u>Supervision</u></h2>
<h3>Master's students</h3>
 <ul>
  <li>Galiane Charbonneau<br>
   <small style="font-size:75%;">Thesis: Extremal latent tree models (tentative title)</small></li>
  <li>James Cuin (Imperial College London, cosupervision with Yanbo Tang)<br>
   <small style="font-size:75%;">Thesis: Change Point Detection for Extremal Graphical Models (2024)</small></li>
 </ul>
<h3>Undergraduate students</h3>
 <ul>
  <li>Galiane Charbonneau<br>
   <small style="font-size:75%;">Project: Extremal latent tree models</small></li>
  <li>Alexander Ryabchenko (University of Toronto, cosupervision with Stanislav Volgushev)<br>
   <small style="font-size:75%;">Project: Adaptive learning of extremal graphical models</small></li>
 </ul>

<h2><u>Teaching</u></h2>
<h3>At UQAM</h3>
 <ul>
  <li>
   Computational statistics
  </li>
  <li>
   Scientific communication in Statistics
  </li>
  <li>
   Stochastic processes
  </li>
 </ul>
<h3>At other universities</h3>
  <ul>{% for post in site.teaching reversed %}
    <li>
      {{post.title}} ({{post.type}})<br>
      <small style="font-size:75%;">{{post.venue}}, {{post.semester}}</small>
    </li>
  {% endfor %}</ul>
<h3>As a teaching assistant</h3>
  <ul>
    <!-- <li>
      Statistical Consultation, Communication, and Collaboration (Undergraduate course)<br>
      <small style="font-size:75%;">University of Toronto, Fall 2018 - Spring 2019</small>
    </li> -->
    <li>
      Various undergraduate and graduate courses, ranging from statistical consulting to measure theoretic probability<br>
      <small style="font-size:75%;">Université de Montréal, Spring 2015 - Fall 2016<br>University of Toronto, Fall 2018 - Spring 2022</small>
    </li>
  </ul>

<h2><u>Service</u></h2>
  <ul>
    <li>I am the organizer of the <a href="https://statqam.uqam.ca/2024-2025/">STATQAM Statistics research seminar</a>.</li>
    <li>I have served as a reviewer for the <a href="https://www.tandfonline.com/toc/ucgs20/current">Journal of Computational and Graphical Statistics</a>, <a href="https://www.springer.com/journal/10687">Extremes</a>, the <a href="https://rss.onlinelibrary.wiley.com/journal/14679868">Journal of the Royal Statistical Society: Series B</a>, the <a href="https://onlinelibrary.wiley.com/journal/14679469">Scandinavian Journal of Statistics</a>, <a href="https://academic.oup.com/biomet">Biometrika</a>, the <a href="https://imstat.org/journals-and-publications/electronic-journal-of-statistics/">Electronic Journal of Statistics</a>, <a href="https://projecteuclid.org/journals/bernoulli">Bernoulli</a> and the <a href="https://onlinelibrary.wiley.com/journal/1708945x">Canadian Journal of Statistics</a>.</li>
	<li>I was an evaluator for the <a href="https://ellis.eu/">European Laboratory for Learning and Intelligent Systems</a> PhD program.</li>
	<li>I chaired the organizing committee for the <a href="http://www.fields.utoronto.ca/activities/18-19/stats-research-day">2019 edition</a> of the Statistics Graduate Student Research Day, at the Fields Institute. Responsibilities included inviting speakers, securing space and funding, managing most of the local arrangements, supervising and animating the event.</li>
    <li>I was an executive member of my graduate student union at the Université de Montréal in 2016-2017 and at the University of Toronto in 2018-2019 (as president).</li>
  </ul>
  
