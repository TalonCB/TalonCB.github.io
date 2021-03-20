---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints     

## 2021     
**Neural Collaborative Reasoning**       
**Hanxiong Chen**, Shaoyun Shi, Yunqi Li, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.

**User-oriented Fairness in Recommendation**      
Yunqi Li, **Hanxiong Chen**, Zuohui Fu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.

## 2020
**Neural Logic Reasoning**      
Shaoyun Shi\*, **Hanxiong Chen\***, Weizhi Ma, Jiaxin Mao, Min Zhang and Yongfeng Zhang. In *Proceedings of the 29th ACM International Conference on Information and Knowledge Management (**CIKM**)*, 2020.    
[paper]()

## 2019
**Generate Natural Language Explanations for Recommendation**      
**Hanxiong Chen**, Xu Chen, Shaoyun Shi and Yongfeng Zhang. In *Proceedings of the SIGIR 2019 Workshop on ExplainAble Recommendation and Search (**EARS**)*, 2019.

**Personalized Fashion Recommendation with Visual Explanations based on Multimodal Attention Network**      
Xu Chen, **Hanxiong Chen**, Hongteng Xu, Yongfeng Zhang, Yixin Cao, Hongyuan Zha and Zheng Qin. In *Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR**)*, 2019.

**Unified Collaborative Filtering over Graph Embeddings**      
Pengfei Wang, **Hanxiong Chen**, Yadong Zhu, Huawei Shen and Yongfeng Zhang. In *Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR**)*, 2019.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
