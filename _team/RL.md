---
title: "Romain F. Laine"
collection: team
header:
  teaser: RL.jpg
tags: post-doc
tagline: MRC Research Fellow
subject: "Study of viral infection and development of optical super-resolution microscopy"
date: 2017-12-01
email: 'r.laine@ucl.ac.uk'
---

<p align= "justify">
  
## Overview
I am interested in developing and applying advanced microscopy techniques to decipher functional and structural organisation of life at multiple scales. For this, I develop analytical and optical tools. You can find me on [**Twitter**][myTwitter], in the optics lab tinkering with microscopes or on my computer developing image analyses.

 
## Background and how I ended up coming to the LMCB?
 
French but I have been living in the UK for long enough to have forgotten how real buttery pastries taste like. I did my PhD at Imperial College in biophotonics (throwing lasers and microscopes at cells and molecules !), then moved to Cambridge for PostDoc to develop super-resolution microscopy (throwing more lasers and more microscopes at cells and molecules !). I now joined Ricardo’s lab and I want to exploit my microscopy skills to study more complex biological systems with my microscopy skills (throwing some cells at my microscope!).
 
## Reason(s) that made me get into science?
 
The idea (and ideal) of discovery!
 
## What’s keeping me busy in lab these days in the lab?
 
I am developing more intelligent imaging, especially within super-resolution microscopy, and moving away from fixed cell towards living biological systems. Applying these approaches to study viral replication.
 
## Where do I see myself in 5 years?
 
Head of my own lab, working on fast 3D microscopy to understand viral replication at cellular and sub-cellular levels.
 
 
## Any hobbies?
 
Capoeira and cooking ! (a well-balanced system of input and output of calories)


<p align= "justify">
<h2> Publications (<a href="https://scholar.google.com/citations?user=eNRcCNEAAAAJ&hl=en"><span style="color:gray">Google Scholar</span></a>)</h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Laine" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}


[myTwitter]: https://twitter.com/LaineBioImaging

