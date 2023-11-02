---
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
{% endfor %}

* <font color="blue"> [Preprint] </font> ClassEval: A Manually-Crafted Benchmark for Evaluating LLMs on Class-level Code Generation
**Xueying Du**, Mingwei Liu, Kaixin Wang, Hanlin Wang, Junwei Liu, Yixuan Chen, Jiayi Feng, Chaofeng Sha, Xin Peng, Yiling Lou.
[[Paper]](https://arxiv.org/pdf/2308.01861.pdf) 
[[Paper]](https://arxiv.org/pdf/2308.01861.pdf) [[Benchmark github]](https://github.com/FudanSELab/ClassEval)
