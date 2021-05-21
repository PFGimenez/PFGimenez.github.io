---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education and work experience
- Since 2020: Associate professor in cybersecurity
    - CentraleSupelec and Inria (Rennes, France)
    - Intrusion detection and malware analysis
- 2018-2020: Postdoc in cybersecurity
    - LAAS-CNRS (Toulouse, France)
    - Intrusion detection based on machine learning
* 2015-2018: PhD in artificial intelligence
    - IRIT (Toulouse, France)
    - Preferences learning and application to e-commerce
- 2012-2015: engineering student
    - Télécom SudParis (Evry, France)
    - Specialization in statistics

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks -->
<!-- ====== -->
<!--   <ul>{% for post in site.talks %} -->
<!--     {% include archive-single-talk-cv.html %} -->
<!--   {% endfor %}</ul> -->
  
## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
