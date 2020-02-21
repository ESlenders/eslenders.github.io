---
title: "Siân Culley"
collection: team
header:
  teaser: SC.jpg
tags: post-doc
tagline: Wellcome Funded
date: 2014-01-01
email: 's.culley@ucl.ac.uk'
---

<!-- {::options parse_block_html="true" /} -->

<p align= "justify">
My research centres on developing novel approaches for live-cell super-resolution microscopy. The resolution of conventional fluorescence microscopy is limited to ~200-300nm by the diffraction of light, and as such processes and structures on smaller scales than this cannot be accurately resolved. Super-resolution microscopy techniques extend the resolving capabilities of fluorescence microscopy down to tens of nanometres; however the majority of these techniques use high intensity lasers and/or require lengthy imaging times. This severely limits their compatibility with live-cell imaging. We recently published Super-Resolution Radial Fluctuations (SRRF), which enables super-resolution imaging on any modern fluorescence microscope with conventional fluorophores such as GFP. Importantly, SRRF is capable of increasing resolution without the need for high laser intensities and so can be used for imaging living, dynamic systems. I am currently developing computational and optical approaches to further limit the light dose to samples for SRRF imaging. In collaboration with the Baum lab, I am currently building a super-resolution microscope for imaging the cytoskeleton of live Archaea. The system is designed such that imaging can be performed at 70-80ºC and at low pH, and will be capable of performing super-resolution imaging using SRRF, SIM and STORM modalities.

<p align= "justify">
<h2> Publications (<a href="https://scholar.google.com/citations?hl=en&user=yQfJ1loAAAAJ"><span style="color:gray">Google Scholar</span></a>)</h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Culley" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
