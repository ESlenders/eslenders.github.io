---
title: "Kalina Tosheva"
collection: team
header:
  teaser: person.png
tags: phd
tagline: MRC-LMCB
subject: "Quantitative evaluation of phototoxicity for live-cell super-resolution microscopy"
date: 2017-09-05
email: 'kalina.tosheva.16@ucl.ac.uk'
prom: "Supervision: Prof. Ricardo Henriques"
---
My project aims to adapt single molecule localisation super-resolution techniques to light-sheet microscopy.

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Tosheva" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
