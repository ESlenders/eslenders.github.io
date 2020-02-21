---
title: "Lucas Von Chamier (Primary)"
collection: team
header:
  teaser: person.png
tags: phd
tagline: MRC-LMCB PhD Programme
date: 2017-09-04
email: 'lucas.chamier.13@ucl.ac.uk'
---
<!-- {::options parse_block_html="true" /} -->

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Chamier" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
