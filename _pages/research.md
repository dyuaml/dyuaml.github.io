---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My doctoral research in active learning aims to tackle the critical challenges of data efficiency, model robustness, and adaptability. By extending AL to handle noisy, dynamic, and complex data, and by adapting it for the foundation model era, my work seeks to make machine learning both more powerful and more accessible across domains. As a faculty member, I look forward to expanding this research, fostering interdisciplinary collaborations, and training the next generation of scientists to push the boundaries of what machine learning can achieve in the real world.


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
