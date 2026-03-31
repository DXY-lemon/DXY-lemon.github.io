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

* **[TOSEM'26]** Vul-RAG: Enhancing LLM-based Vulnerability Detection via Knowledge-level RAG, **Xueying Du**, Geng Zhang, Kaixin Wang, Jiayi Feng, Wentai Deng, Mingwei Liu, Bihuan Chen, Xin Peng, Tao Ma, Yiling Lou.   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3797277)
  
* **[ICSE'26]** Reducing False Positives in Static Bug Detection with LLMs: An Empirical Study in Industry, **Xueying Du**, Jiayi Feng, Yi Zou, Jiayi Feng, Wei Xu, Jie Ma, Wei Zhang, Sisi Liu, Xin Peng, Yiling Lou.
    
* **[TOSEM'26]** Exploring Large Language Models in Resolving Environment-Related Crash Bugs: Localizing and Repairing, **Xueying Du**, Mingwei Liu, Juntao Li, Hanlin Wang, Xin Peng, Yiling Lou.  [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3788866)

* **[ICSE'24]** Evaluating Large Language Models in Class-Level Code Generation, **Xueying Du**, Mingwei Liu, Kaixin Wang, Hanlin Wang, Junwei Liu, Yixuan Chen, Jiayi Feng, Chaofeng Sha, Xin Peng, Yiling Lou.
    [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3597503.3639219) [[Benchmark github]](https://github.com/FudanSELab/ClassEval)[[Hugging Face]](https://huggingface.co/datasets/FudanSELab/ClassEval)

* **[FSE'23]** KG4CraSolver: Recommending Crash Solutions via Knowledge Graph, **Xueying Du**, Yiling Lou, Mingwei Liu, Xin Peng, Tianyong Yang. [[Paper]](https://mingwei-liu.github.io/assets/pdf/FSE2023-KG4CraSolver.pdf)

* **[FSE'23]<span style="color:green">[ACM SIGSOFT Distinguished Paper Award]</span>** Recommending Analogical APIs via Knowledge Graph Embedding, Mingwei Liu, Yanjun Yang, Yiling Lou, Xin Peng, Zhong Zhou, **Xueying Du**, Tianyong Yang. [[Paper]](https://2023.esec-fse.org/details/fse-2023-research-papers/64/Recommending-Analogical-APIs-via-Knowledge-Graph-Embedding)

* **[ASE'23]** CodeGen4Libs: A Two-Stage Approach for Library-Oriented Code Generation, Mingwei Liu, Tianyong Yang, Yiling Lou, **Xueying Du**, Ying Wang, Xin Peng. [[Paper]](https://mingwei-liu.github.io/files/ase2023-CodeGen4Libs.pdf)

* **[ICSME'23]** Knowledge Graph based Explainable Question Retrieval for Programming Tasks, Mingwei Liu, Simin Yu, Xin Peng, **Xueying Du**, Tianyong Yang, Huanjun Xu, Gaoyang Zhang. [[Paper]](https://mingwei-liu.github.io/files/icsme2023-KG4QuesRecomm.pdf)

* **[Journal of Software 2023]** Research on Knowledge Graph Representation Learning Methods for Link Prediction: A Review, **Xueying Du**, Mingwei Liu, Liwei Sheng, Xin Peng. [[Paper]](https://www.jos.org.cn/jos/article/abstract/6902)
