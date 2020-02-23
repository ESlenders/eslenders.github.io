---
title: "Pedro Matos Pereira"
collection: team
header:
  teaser: PMP.jpg
tags: alumni
tagline: Postdoc
subject: "Super-Beacons and Beacon-STORM: a new generation of small tunable photoswitching probes and Super-Resolution approaches."
date: 2014-01-01
email: 'pmatos@itqb.unl.pt>'
---

<p align= "justify">
<h2> Publications (<a href="https://scholar.google.co.uk/citations?user=I-dQvQ0AAAAJ&hl=en"><span style="color:gray">Google Scholar</span></a>)</h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Pereira" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
