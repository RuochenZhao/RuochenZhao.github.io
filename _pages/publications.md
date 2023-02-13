<!-- ---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

**2022

PromptSum: Planning with Mixed Prompts for Parameter-Efficient Controllable Abstractive Summarization

Mathieu Ravaut, Hailin Chen, **Ruochen Zhao**, Chengwei Qin, 
Shafiq Joty, Nancy F. Chen

Openreview

[paper](https://openreview.net/forum?id=FEBCwrGzR3j)