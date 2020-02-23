---
title: "Jerzy Samolej"
collection: team
header:
  teaser: JS.jpg
tags: alumni
tagline: PhD Student
subject: "Identification of anti-poxviral agents by high-throughput image-based screening."
date-start: 2015-09-01
date-end: 2018-12-01
email: 'jerzy.samolej.14@alumni.ucl.ac.uk'
twitter: 'SamolejJ'
supervisors: 'Prof. Jason Mercer and Prof. Ricardo Henriques'
---

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Samolej" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
