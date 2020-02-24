---
title: "Probes"
collection: research
date: 2016-08-01
author_profile: false
sidebar:
  nav: "Tech"
header:
  teaser: beacons.jpg
layout: archive
---

<h2>  Publications: </h2>
{% for post in site.publications reversed %}
  {% if post.type contains 'probes' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
