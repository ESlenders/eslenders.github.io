<style>
a:link {
  color: blue; 
  background-color: transparent; 
  text-decoration: none;
}
  

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
<p> <b>Overview:</b>
I am interested in developing and applying advanced microscopy techniques to decipher functional and structural organisation of life at multiple scales. For this, I develop analytical and optical tools. You can find me on Twitter (@LaineBioImaging), in the optics lab tinkering with microscopes or on my computer developing image analyses. </p>

<p> <b> Links</b>
 <br> <a href="https://twitter.com/LaineBioImaging">Twitter @LaineBioImaging</a> 
 <br> <a href="https://scholar.google.co.uk/citations?hl=en&user=eNRcCNEAAAAJ">Google scholar</a> 
 <br> <a href="https://www.ucl.ac.uk/lmcb/users/romain-laine"> MRC-LMCB </a></p>
 
 
<p> <b>Background and how I ended up coming to the LMCB? </b>
  <p align= "justify">
French but I have been living in the UK for long enough to have forgotten how real buttery pastries taste like. I did my PhD at Imperial College in biophotonics (throwing lasers and microscopes at cells and molecules !), then moved to Cambridge for PostDoc to develop super-resolution microscopy (throwing more lasers and more microscopes at cells and molecules !). I now joined Ricardo’s lab and I want to exploit my microscopy skills to study more complex biological systems with my microscopy skills (throwing some cells at my microscope!).</p>
 
<p> <b>Reason(s) that made me get into science?</b>
  <p align= "justify">
 
The idea (and ideal) of discovery!</p>

<p><b>Where do I see myself in 5 years?</b>
  <p align= "justify">
 
Head of my own lab, working on fast 3D microscopy to understand viral replication at cellular and sub-cellular levels.</p>
 
<p><b>Any hobbies?</b>
  <p align= "justify">
 
Capoeira and cooking ! (a well-balanced system of input and output of calories). </p>


<p align= "justify">
<h2> Publications (<a href="https://scholar.google.com/citations?user=eNRcCNEAAAAJ&hl=en"><span style="color:gray">Google Scholar</span></a>)</h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Laine" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}


