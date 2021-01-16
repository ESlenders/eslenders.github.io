---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

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


