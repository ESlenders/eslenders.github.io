---
title: "Robert Gray"
collection: team
header:
  teaser: RG.jpg
tags: alumni
tagline: PhD Student
subject: "Understanding vaccinia virus entry by super-resolution microscopy and particle averaging"
date-start: 2015-09-01
date-end: 2018-12-01
email: 'robert.gray.14@alumni.ucl.ac.uk'
supervisors: 'Prof. Ricardo Henriques and Prof. Jason Mercer'
---

<h2> PhD Thesis</h2>

<object data="https://discovery.ucl.ac.uk/cgi/users/login?target=https%3A%2F%2Fdiscovery.ucl.ac.uk%2Fid%2Feprint%2F10067473%2F1%2FRGthesis.pdf" type="application/pdf" width="300px" height="300px">
    <embed src="https://discovery.ucl.ac.uk/cgi/users/login?target=https%3A%2F%2Fdiscovery.ucl.ac.uk%2Fid%2Feprint%2F10067473%2F1%2FRGthesis.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://discovery.ucl.ac.uk/cgi/users/login?target=https%3A%2F%2Fdiscovery.ucl.ac.uk%2Fid%2Feprint%2F10067473%2F1%2FRGthesis.pdf">Download PDF</a>.</p>
    </embed>
</object>

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Gray" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
