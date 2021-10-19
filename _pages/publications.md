---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(\* represents equal contribution)

## 2021     
**Graph Logic Reasoning for Recommendation and Link Prediction **       
**Hanxiong Chen**, Yunqi Li, Shaoyun Shi, Shuchang Liu, He Zhu, Yongfeng Zhang. In *Proceedings of the 15th ACM International Conference on Web Search and Data Mining in  (**WSDM**)*, 2022.       

**Towards Personalized Fairness based on Causal Notion**       
Yunqi Li, **Hanxiong Chen**, Shuyuan Xu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the 44nd International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR**)*, 2021.       

**Neural Collaborative Reasoning**       
**Hanxiong Chen**, Shaoyun Shi, Yunqi Li, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.      
[[paper]](https://arxiv.org/pdf/2005.08129.pdf) [[code]](https://github.com/rutgerswiselab/NLR)

**User-oriented Fairness in Recommendation**      
Yunqi Li, **Hanxiong Chen**, Zuohui Fu, Yingqiang Ge, Yongfeng Zhang. In *Proceedings of the Web Conference (**WWW**)*, 2021.      
[[paper]](https://arxiv.org/pdf/2104.10671.pdf)

## 2020
**Neural Logic Reasoning**      
Shaoyun Shi\*, **Hanxiong Chen\***, Weizhi Ma, Jiaxin Mao, Min Zhang and Yongfeng Zhang. In *Proceedings of the 29th ACM International Conference on Information and Knowledge Management (**CIKM**)*, 2020.    
[[paper]](/files/Neural_Logic_Reasoning.pdf) [[code]](https://github.com/rutgerswiselab/NCR)

## 2019
**Generate Natural Language Explanations for Recommendation**      
**Hanxiong Chen**, Xu Chen, Shaoyun Shi and Yongfeng Zhang. In *Proceedings of the SIGIR 2019 Workshop on ExplainAble Recommendation and Search (**EARS**)*, 2019.      
[[paper]](https://arxiv.org/pdf/2101.03392.pdf)

**Personalized Fashion Recommendation with Visual Explanations based on Multimodal Attention Network**      
Xu Chen, **Hanxiong Chen**, Hongteng Xu, Yongfeng Zhang, Yixin Cao, Hongyuan Zha and Zheng Qin. In *Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR**)*, 2019.     
[[paper]](/files/chen-sigir2019.pdf)

**Unified Collaborative Filtering over Graph Embeddings**      
Pengfei Wang, **Hanxiong Chen**, Yadong Zhu, Huawei Shen and Yongfeng Zhang. In *Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR**)*, 2019.      
[[paper]](/files/wang-sigir2019a.pdf)

## Workshops
**MRC2021: The 1st International Workshop on Machine Reasoning**      
Yongfeng Zhang, Min Zhang, Hanxiong Chen, Xu Chen, Xianjie Chen, Chuang Gan, Tong Sun, Xin Luna Dong. In *Proceedings of the 14th ACM International Conference on Web Search and Data Mining (WSDM 2021)*, March 8 - 12, 2021, Jerusalem, Israel.      
[Homepage](https://mrc2021.github.io/)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
