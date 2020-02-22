---
title: "Yue (Julie) Yuan"
collection: team
header:
  teaser: YY.jpg
tags: phd
tagline: BBSRC LiDO
subject: "Understanding the dynamics and mechanisms of HIV-1 cell entry"
date: 2017-09-05
email: 'yue.yuan.17@ucl.ac.uk'
supervisors: Prof. Ricardo Henriques, Prof. Mark Marsh, Prof. Dylan Owen
---

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Yuan" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
