---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am Jiyu Guo(郭济瑜), a senior undergraduate student from the [Harbin Institute of Technology, Shenzhen](https://www.hitsz.edu.cn/), Guangdong, China.  
My research interests lie in:
  - **Data-Efficient AI**: Current artificial intelligence models require training on massive datasets, significantly increasing the training costs of large models. My work focuses on utilizing data more efficiently, cleaning and synthesizing data more strategically, to achieve data-efficient artificial intelligence.
  - **Efficient and Trustworthy LLM**: Large language models entail significant computational costs and face reliability challenges. I explore methods to improve training and inference efficiency in large language models, while ensuring model outputs are robust, reliable, and aligned with human expectations.
    
 <!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 One paper, "Generative Data Augmentation", was accepted to NeurIPS 2025.
- *2024.12*: &nbsp;🎉🎉 One paper, "LLM-as-a-judge", was accepted by ISSTA 2025. 
- *2024.05*: &nbsp;🎉🎉 One paper, "Data Agents", was accepted by ACL 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/utilgen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

UtilGen: Utility-Centric Generative Data Augmentation with Dual-Level Task Adaptation. [PDF](https://raw.githubusercontent.com/jiyuguo-2004/jiyuguo-2004.github.io/main/paper/554_UtilGen_Utility_Centric_Ge.pdf).[Link](https://neurips.cc/virtual/2025/poster/115620).

**Jiyu Guo**, Shuo Yang, Yiming Huang, Yancheng Long, Xiaobo Xia, Xiu Su, Bo Zhao, Zeke Xie, Liqiang Nie.

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- Trainging Data Genaration.
- In this paper, we pioneer a paradigm shift from intrinsic data quality to task-specific utility optimization in generative data augmentation
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/tpami.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Robust Coreset Selection via Class-Aware Decision Boundary Reconstruction.

Shuo Yang, **Jiyu Guo**, Yujie Wei, Ruiheng Zhang, Hongxun Yao, Ping Luo, Tongliang Liu, Liqiang Nie(Under Review, **Student First Author**) 

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- Training Data Selection.
- We establish a principled coreset selection method by linking decision boundary reconstruction error to model generalization, enabling robust and efficient training data selection via decision boundary reconstruction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISSTA 2025</div><img src='images/issta.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Can LLMs Replace Human Evaluators? An Empirical Study of LLM-as-a-Judge in Software Engineering.[PDF.](https://dl.acm.org/doi/pdf/10.1145/3728963)

Ruiqi Wang, **Jiyu Guo**, Cuiyun Gao, Guodong Fan, Chun Yong Chong, Xin Xia.

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- LLM-as-a-judge.
- In this paper, we empirically explore LLM-as-a-judge methods for evaluating SE tasks, focusing on their alignment with human judgments. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/acl2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Enhancing text-to-SQL parsing through question rewriting and execution-guided refinement.[PDF.](https://aclanthology.org/2024.findings-acl.120.pdf)

Wenxin Mao, Ruiqi Wang, **Jiyu Guo**, Jichuan Zeng, Cuiyun Gao, Peiyi Han, Chuanyi Liu.

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- AI for Databases.
- We build a modular, execution-driven Text-to-SQL agent that enhances semantic alignment and query correctness via context-aware reasoning and iterative self-correction.
</div>
</div>

<!--- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**-->

# 💻 Internships
- *2023.10 - 2024.11*, Research Intern at HITSZ, advised by Prof. Cuiyun Gao.
- *2025.01 - 2025.10*, Research Intern at HITSZ, advised by Prof. Shuo Yang.

<!--# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

<!--# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->


