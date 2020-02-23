---
title: "Pedro Matos Pereira"
collection: team
header:
  teaser: PMP.jpg
tags: alumni
tagline: Postdoc
subject: "Super-Beacons and Beacon-STORM: a new generation of small tunable photoswitching probes and Super-Resolution approaches."
date-start: 2014-01-01
date-end: 2018-12-01
email: 'pmatos@itqb.unl.pt'
twitter: 'P_Matos_Pereira'
orcid: https://orcid.org/0000-0002-1426-9540
googlescholar: https://scholar.google.co.uk/citations?user=I-dQvQ0AAAAJ&hl=en
---

<p align= "justify">

<h2> Publications (<a href="https://scholar.google.co.uk/citations?user=I-dQvQ0AAAAJ&hl=en"><span style="color:gray">Google Scholar</span></a>)</h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Pereira" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
