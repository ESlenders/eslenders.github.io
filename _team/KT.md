---
title: "Kalina Tosheva"
collection: team
header:
  teaser: person.png
tags: phd
tagline: PhD Candidate
date: 2020-02-21
email: 'kalina.tosheva.16@ucl.ac.uk'
---
<!-- {::options parse_block_html="true" /} -->

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Tosheva" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
