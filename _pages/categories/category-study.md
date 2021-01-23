---
layout: archive
title: "꾸준히 공부하기"
permalink: /categories/study
author_profile: true
toc: true
---

{% for category in site.categories %}
  {% if category[0] == "study" %}
    {% for post in category[1] %}
      {% include archive-single.html type=list %}
    {% endfor %}
  {% endif %}  
{% endfor %}