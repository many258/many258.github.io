---
layout: archive
title: "새로운 장소 탐험"
permalink: /categories/travel
author_profile: true
toc: true
---

{% for category in site.categories %}
  {% if category[0] == "travel" %}
    {% for post in category[1] %}
      {% include archive-single.html type=list %}
    {% endfor %}
  {% endif %}  
{% endfor %}