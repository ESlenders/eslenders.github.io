---
title: "Cell Division"
collection: research
date: 2016-08-01
author_profile: false
sidebar:
  nav: "Tech"
header:
  teaser: division.jpg
layout: archive
---

<h2>  Publications: </h2>
{% for post in site.publications reversed %}
  {% if post.type contains 'cell division' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
