---
title: "Host-Pathogen Interactions"
collection: research
date: 2016-08-01
author_profile: false
sidebar:
  nav: "Tech"
header:
  teaser: hiv.jpg
layout: archive
---

<h2>  Publications: </h2>
{% for post in site.publications reversed %}
  {% if post.type contains 'host-pathogen' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
