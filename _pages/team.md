---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

<hr-bold>
<h2>Principal Investigator</h2>
<hr><br>
<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'PI' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
<br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<hr-bold>
<h2>Post-doctoral researchers</h2>
<hr><br>

<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'post-doc' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>


<hr-bold>
<h2>PhD students</h2>
<hr><br>
<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'phd' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br>
<br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>


<hr-bold>
<h2>Master students</h2>
<hr><br>
<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'master' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<br><br><br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
