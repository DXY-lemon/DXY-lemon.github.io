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

* <font color="blue"> [Preprint] </font>ClassEval: A Manually-Crafted Benchmark for Evaluating LLMs on Class-level Code Generation, **Xueying Du**, Mingwei Liu, Kaixin Wang, Hanlin Wang, Junwei Liu, Yixuan Chen, Jiayi Feng, Chaofeng Sha, Xin Peng, Yiling Lou. [[Paper]](https://arxiv.org/pdf/2308.01861.pdf) [[Benchmark github]](https://github.com/FudanSELab/ClassEval)

* <font color="blue"> [FSE'23] </font> KG4CraSolver: Recommending Crash Solutions via Knowledge Graph, **Xueying Du**, Yiling Lou, Mingwei Liu, Xin Peng, Tianyong Yang. [[Paper]](https://2023.esec-fse.org/details/fse-2023-research-papers/76/KG4CraSolver-Recommending-Crash-Solutions-via-Knowledge-Graph)

* <font color="blue"> [[FSE'23] </font> Recommending Analogical APIs via Knowledge Graph Embedding, Mingwei Liu, Yanjun Yang, Yiling Lou, Xin Peng, Zhong Zhou, **Xueying Du**, Tianyong Yang. [[Paper]](https://2023.esec-fse.org/details/fse-2023-research-papers/64/Recommending-Analogical-APIs-via-Knowledge-Graph-Embedding)

* <font color="blue"> [ASE'23] </font> CodeGen4Libs: A Two-Stage Approach for Library-Oriented Code Generation, Mingwei Liu, Tianyong Yang, Yiling Lou, **Xueying Du**, Ying Wang, Xin Peng. [[Paper]](https://mingwei-liu.github.io/files/ase2023-CodeGen4Libs.pdf)

* <font color="blue"> [ICSME'23] </font> Knowledge Graph based Explainable Question Retrieval for Programming Tasks, Mingwei Liu, Simin Yu, Xin Peng, **Xueying Du**, Tianyong Yang, Huanjun Xu, Gaoyang Zhang. [[Paper]](https://mingwei-liu.github.io/files/icsme2023-KG4QuesRecomm.pdf)

* <font color="blue"> [Journal of Software 2023] </font> Research on Knowledge Graph Representation Learning Methods for Link Prediction: A Review, **Xueying Du**, Mingwei Liu, Liwei Sheng, Xin Peng. [[Paper]](https://www.jos.org.cn/jos/article/abstract/6902)
