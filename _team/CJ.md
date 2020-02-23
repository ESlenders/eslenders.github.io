---
title: "Caron Jacobs"
collection: team
header:
  teaser: CJ.jpg
tags: alumni
tagline: PhD Student
subject: "The nanoscale organisation of HIV cell surface receptors CD4 and CCR5."
date-start: 2014-09-01
date-end: 2018-03-01
email: 'caron.jacobs.14@alumni.ucl.ac.uk'
twitter: 'caron_g'
supervisors: 'Prof. Ricardo Henriques and Prof. Mark Marsh'
---

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Jacobs" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
