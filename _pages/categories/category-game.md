---
layout: archive
title: "즐겨하는 게임"
permalink: /categories/game
author_profile: true
toc: true
---

{% for category in site.categories %}
  {% if category[0] == "game" %}
    {% for post in category[1] %}
      {% include archive-single.html type=list %}
    {% endfor %}
  {% endif %}  
{% endfor %}