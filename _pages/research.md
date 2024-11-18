---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My doctoral research in active learning aims to tackle the critical challenges of data efficiency, model robustness, and adaptability. The development of machine learning (ML) models has traditionally relied on the availability of vast amounts of labeled data. However, in many domains—particularly those that are knowledge-intensive or high-stakes, such as healthcare, environmental science, and materials science-labeling data is both time-consuming and costly. Active Learning (AL) presents an exciting solution to this challenge, aiming to identify and label only the most informative samples, thus reducing the overall labeling effort while achieving high model accuracy. My research focuses on extending and enhancing AL methods to make machine learning more accessible, efficient, and capable of adapting to complex, real-world scenarios. Besides contributing to more powerful AL algorithms for challenging tasks such as multi-label AL and noisy labels, I also aspire to realize better AL evaluation to make AL research more accessible and reliable. By extending AL to handle noisy, dynamic, and complex data, and by adapting it for the foundation model era, my work seeks to make machine learning both more powerful and more accessible across domains. 


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
