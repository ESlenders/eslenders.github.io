---
title: "Romain Laine"
collection: team
header:
  teaser: RL.jpg
tags: post-doc
tagline: MRC Fellow
date: 2017-12-01
email: 'r.laine@ucl.ac.uk'
---

<p align= "justify">
I am interested in developing and applying advanced microscopy techniques to decipher functional and structural organisation of life at multiple scales. For this, I develop analytical and optical tools.

<p align= "justify">
<h2> Publications (<a href="https://scholar.google.com/citations?user=eNRcCNEAAAAJ&hl=en"><span style="color:gray">Google Scholar</span></a>)</h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Laine" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
