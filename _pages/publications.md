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

* **[Preprint]** Vul-RAG: Enhancing LLM-based Vulnerability Detection via Knowledge-level RAG, **Xueying Du**, Geng Zhang, Kaixin Wang, Jiayi Feng, Wentai Deng, Mingwei Liu, Bihuan Chen, Xin Peng, Tao Ma, Yiling Lou.   [[Paper]](https://arxiv.org/pdf/2406.11147)
  
* **[Preprint]** Resolving Crash Bugs via Large Language Models: An Empirical Study, **Xueying Du**, Mingwei Liu, Juntao Li, Hanlin Wang, Xin Peng, Yiling Lou.  [[Paper]](https://arxiv.org/abs/2312.10448)

* **[ICSE'24]** ClassEval: A Manually-Crafted Benchmark for Evaluating LLMs on Class-level Code Generation,
   **Xueying Du**, Mingwei Liu, Kaixin Wang, Hanlin Wang, Junwei Liu, Yixuan Chen, Jiayi Feng, Chaofeng Sha, Xin Peng, Yiling Lou.
    [[Paper]](https://arxiv.org/pdf/2308.01861.pdf) [[Benchmark github]](https://github.com/FudanSELab/ClassEval)

* **[FSE'23]** KG4CraSolver: Recommending Crash Solutions via Knowledge Graph, **Xueying Du**, Yiling Lou, Mingwei Liu, Xin Peng, Tianyong Yang. [[Paper]](https://2023.esec-fse.org/details/fse-2023-research-papers/76/KG4CraSolver-Recommending-Crash-Solutions-via-Knowledge-Graph)

* **[FSE'23]<span style="color:green">[ACM SIGSOFT Distinguished Paper Award]</span>** Recommending Analogical APIs via Knowledge Graph Embedding, Mingwei Liu, Yanjun Yang, Yiling Lou, Xin Peng, Zhong Zhou, **Xueying Du**, Tianyong Yang. [[Paper]](https://2023.esec-fse.org/details/fse-2023-research-papers/64/Recommending-Analogical-APIs-via-Knowledge-Graph-Embedding)

* **[ASE'23]** CodeGen4Libs: A Two-Stage Approach for Library-Oriented Code Generation, Mingwei Liu, Tianyong Yang, Yiling Lou, **Xueying Du**, Ying Wang, Xin Peng. [[Paper]](https://mingwei-liu.github.io/files/ase2023-CodeGen4Libs.pdf)

* **[ICSME'23]** Knowledge Graph based Explainable Question Retrieval for Programming Tasks, Mingwei Liu, Simin Yu, Xin Peng, **Xueying Du**, Tianyong Yang, Huanjun Xu, Gaoyang Zhang. [[Paper]](https://mingwei-liu.github.io/files/icsme2023-KG4QuesRecomm.pdf)

* **[Journal of Software 2023]** Research on Knowledge Graph Representation Learning Methods for Link Prediction: A Review, **Xueying Du**, Mingwei Liu, Liwei Sheng, Xin Peng. [[Paper]](https://www.jos.org.cn/jos/article/abstract/6902)
