---
title: "Yue (Julie) Yuan"
collection: team
header:
  teaser: person.png
tags: phd
tagline: BBSRC LiDO
date: 2017-09-05
email: 'yue.yuan.17@ucl.ac.uk'
---
<!-- {::options parse_block_html="true" /} -->

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Yuan" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
