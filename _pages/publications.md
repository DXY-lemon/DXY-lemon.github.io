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

* **[NeurIPS'26]** Agents as Neuro-Symbolic Reasoners: Path Feasibility Reasoning for Precise Static Bug Detection, **Xueying Du**, Kai Yu, Chong Wang, Yi Zou, Wentai Deng, Zuoyu Ou, Xin Peng, Yiling Lou.

* **[TOSEM'26]** VulWeaver: Weaving Broken Semantics for Grounded Vulnerability Detection, Yiheng Cao, Yihao Chen, Xin Hu, Bihuan Chen, Jiayi Deng, Zhuotong Zhou, Susheng Wu, Yiheng Huang, **Xueying Du**, Xingman Chen, Miaohua Li, Xin Peng. [[Paper]](https://arxiv.org/abs/2604.10767)

* **[TOSEM'26]** Vul-RAG: Enhancing LLM-based Vulnerability Detection via Knowledge-level RAG, **Xueying Du**, Geng Zheng, Kaixin Wang, Yi Zou, Yujia Wang, Wentai Deng, Jiayi Feng, Mingwei Liu, Bihuan Chen, Xin Peng, Tao Ma, Yiling Lou. [[Paper]](https://dl.acm.org/doi/abs/10.1145/3797277)
  
* **[ICSE'26]** Reducing False Positives in Static Bug Detection with LLMs: An Empirical Study in Industry, **Xueying Du**, Jiayi Feng, Yi Zou, Wei Xu, Jie Ma, Wei Zhang, Sisi Liu, Xin Peng, Yiling Lou. [[Paper]](https://arxiv.org/abs/2601.18844)
    
* **[TOSEM'26]** Exploring Large Language Models in Resolving Environment-Related Crash Bugs: Localizing and Repairing, **Xueying Du**, Mingwei Liu, Juntao Li, Hanlin Wang, Xin Peng, Yiling Lou.  [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3788866)

* **[ICSE'24]** Evaluating Large Language Models in Class-Level Code Generation, **Xueying Du**, Mingwei Liu, Kaixin Wang, Hanlin Wang, Junwei Liu, Yixuan Chen, Jiayi Feng, Chaofeng Sha, Xin Peng, Yiling Lou.
    [[Paper]](https://dl.acm.org/doi/epdf/10.1145/3597503.3639219) [[Benchmark github]](https://github.com/FudanSELab/ClassEval)[[Hugging Face]](https://huggingface.co/datasets/FudanSELab/ClassEval)

* **[Journal of Software 2024]** Research on Knowledge Graph Representation Learning Methods for Link Prediction: A Review (面向链接预测的知识图谱表示学习方法综述), **Xueying Du**, Mingwei Liu, Liwei Shen, Xin Peng. [[Paper]](https://www.jos.org.cn/jos/article/abstract/6902)
  
* **[FSE'23]** KG4CraSolver: Recommending Crash Solutions via Knowledge Graph, **Xueying Du**, Yiling Lou, Mingwei Liu, Xin Peng, Tianyong Yang. [[Paper]](https://mingwei-liu.github.io/assets/pdf/FSE2023-KG4CraSolver.pdf)

* **[FSE'23]<span style="color:green">[ACM SIGSOFT Distinguished Paper Award]</span>** Recommending Analogical APIs via Knowledge Graph Embedding, Mingwei Liu, Yanjun Yang, Yiling Lou, Xin Peng, Zhong Zhou, **Xueying Du**, Tianyong Yang. [[Paper]](https://2023.esec-fse.org/details/fse-2023-research-papers/64/Recommending-Analogical-APIs-via-Knowledge-Graph-Embedding)

* **[ASE'23]** CodeGen4Libs: A Two-Stage Approach for Library-Oriented Code Generation, Mingwei Liu, Tianyong Yang, Yiling Lou, **Xueying Du**, Ying Wang, Xin Peng. [[Paper]](https://mingwei-liu.github.io/files/ase2023-CodeGen4Libs.pdf)

* **[ICSME'23]** Knowledge Graph based Explainable Question Retrieval for Programming Tasks, Mingwei Liu, Simin Yu, Xin Peng, **Xueying Du**, Tianyong Yang, Huanjun Xu, Gaoyang Zhang. [[Paper]](https://mingwei-liu.github.io/files/icsme2023-KG4QuesRecomm.pdf)

## Preprints

* **[Preprint'26]** Knowledge-Centric Automated Issue Resolution: A Systematic Survey and Taxonomy, Zhenxi Chen, Mingwei Liu, Zihao Wang, Zhanhui Ren, Leyan Hu, **Xueying Du**, Ying Wang, Chenxi Zhang, Chong Wang, Zhenchang Xing, Haofen Wang, Xin Peng, Yanlin Wang. [[Project]](https://github.com/SYSUSELab/Awesome-Knowledge-for-AIR)

* **[Preprint'26]** Does Pass Rate Tell the Whole Story? Evaluating Design Constraint Compliance in LLM-based Issue Resolution, Kai Yu, Zhenhao Zhou, Junhao Zeng, Ying Wang, **Xueying Du**, Zhiqiang Yuan, Junwei Liu, Ziyu Zhou, Yujia Wang, Chong Wang, Xin Peng. [[Paper]](https://arxiv.org/abs/2604.05955)

* **[Preprint'25]** Evolving Triple Knowledge-Augmented LLMs for Code Translation in Repository Context, Guangsheng Ou, Mingwei Liu, Yuxuan Chen, **Xueying Du**, Shengbo Wang, Zekai Zhang, Xin Peng, Zibin Zheng. [[Paper]](https://arxiv.org/abs/2503.18305)

* **[Preprint'25]** Code Copycat Conundrum: Demystifying Repetition in LLM-based Code Generation, Mingwei Liu, Juntao Li, Ying Wang, **Xueying Du**, Zuoyu Ou, Qiuyuan Chen, Bingxu An, Zhao Wei, Yong Xu, Fangming Zou, Xin Peng, Yiling Lou. [[Paper]](https://arxiv.org/abs/2504.12608)
