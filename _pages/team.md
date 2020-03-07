---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

<hr-bold>
<h2>Principal Investigator</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'PI' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Post-Doctoral Researchers</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'post-doc' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
  </div>
  </div>

<hr-bold>
<h2>PhD Students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'phd' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>
  
<hr-bold>
<h2>Technicians</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'technician' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Internship Students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'internship' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Alumni</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'alumni' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>
