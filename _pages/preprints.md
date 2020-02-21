---
layout: archive
title: "Preprints"
permalink: /preprints/
author_profile: true
---
{% include base_path %}

You can find the complete biorxiv preprint list on <a href="https://rxivist.org/authors/204048">
<span style="color:gray">my Rxivist profile</span></a>.


<ul>
{% for post in site.preprints reversed %}

  {% assign currentdate = post.date | date: "%Y" %}
  {% if currentdate != date %}
    {% unless forloop.first %}</ul>{% endunless %}
    <h2 id="y{{post.date | date: "%Y"}}"><span style="color:gray">{{ currentdate }}</span></h2>
    <ul>
    {% assign date = currentdate %}
  {% endif %}
  {% if post.authors contains 'Ricardo Henriques' %}
    {% include archive-single-pub.html %}
  {% endif %}
  {% if forloop.last %}</ul>{% endif %}

{% endfor %}
