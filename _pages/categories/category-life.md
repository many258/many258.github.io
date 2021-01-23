---
layout: archive
title: "일상이야기"
permalink: /categories/life
author_profile: true
toc: true
---

{% for category in site.categories %}
  {% if category[0] == "life" %}
    {% for post in category[1] %}
      {% include archive-single.html type=list %}
    {% endfor %}
  {% endif %}  
{% endfor %}