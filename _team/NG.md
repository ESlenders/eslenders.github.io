---
title: "Nils Gustafsson"
collection: team
header:
  teaser: NG.jpg
tags: alumni
tagline: PhD Student
subject: "Enabling live-cell super-resolution microscopy by computational analysis and fluorescent probe design."
date-start: 2014-09-01
date-end: 2017-10-01
email: 'nils.gustafsson.13@alumni.ucl.ac.uk'
twitter: 'nilsg1'
supervisors: 'Prof. Ricardo Henriques'
---

<h2> PhD Thesis</h2>

<object data="https://discovery.ucl.ac.uk/id/eprint/10025032/2/NGustafsson_PhD_eThesis_18-10-2017.pdf" type="application/pdf" width="300px" height="300px">
    <embed src="https://discovery.ucl.ac.uk/id/eprint/10025032/2/NGustafsson_PhD_eThesis_18-10-2017.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://discovery.ucl.ac.uk/id/eprint/10025032/2/NGustafsson_PhD_eThesis_18-10-2017.pdf">Download PDF</a>.</p>
    </embed>
</object>

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Gustafsson" %}
    {% include archive-single-pub-associate.html %}
  {% endif %}
{% endfor %}
