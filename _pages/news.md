---
layout: archive
title: "News"
permalink: /news/
author_profile: true
tweets:
  - https://twitter.com/HenriquesLab/status/1229888626764505094?s=20
  - https://twitter.com/HenriquesLab/status/1219271650576867328?s=20
  - https://twitter.com/HenriquesLab/status/1219632763168612355?s=20

---

{% for tweet in page.tweets %}
  {% twitter tweet align=justify width=350 %}
{% endfor %}
