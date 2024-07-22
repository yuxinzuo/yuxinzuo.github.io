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

I am a first-year master candidate (2024-2027) in the Key Laboratory of Network Data Science & Technology, Institute of Computing Technology, Chinese Academy of Sciences (中国科学院计算技术研究所), advised by [Xiaolong Jin (靳小龙)](http://www.bigdatalab.ac.cn/jxl/).
I received a bachelor's degree and the presidential award from Northeastern University (China) in 2024, majoring in software engineering (AI track).

My primary research interests include natural language processing and large language models, with my current research interests remaining open. I have previously researched In-Context Learning, Information Extraction, and Machine Translation.

Previously, I was an intern at **NJUNLP Lab** (2023, Neural Machine Translation) advised by [Shujian Huang (黄书剑)](https://scholar.google.com/citations?user=HF3-E9kAAAAJ&hl=zh-CN), and at **NEUNLP Lab** (2024, Multimodal Machine Translation) advised by [Tong Xiao (肖桐)](https://scholar.google.com/citations?user=-fov7zkAAAAJ). I also work closely with [Bei Li (李北)](https://libeineu.github.io).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Hello, World!🍾🍾

# 📝 Publications 

\* indicates equal contribution.

### 📖 Information Extraction
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 (Main)</div><img src='images/knowcoder.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KnowCoder: Coding Structured Knowledge into LLMs for Universal Information Extraction](https://arxiv.org/pdf/2403.07969)

**Yuxin Zuo\***, Zixuan Li\*, Yutao Zeng\*,  Weicheng Ren\*, Wenxuan Liu, Miao Su, Yucan Guo, Yantao Liu, Xiang Li, Zhilei Hu, Long Bai, Wei Li, Yidan Liu, Pan Yang, Xiaolong Jin, Jiafeng Guo, and Xueqi Cheng

<!-- 
[**ACL 2024 (Main)**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=5TRLpyIAAAAJ&sortby=pubdate&citation_for_view=5TRLpyIAAAAJ:yxAilOxaV9sC) <strong><span class='show_paper_citations' data='5TRLpyIAAAAJ:yxAilOxaV9sC'></span></strong> -->

[![arXiv](https://img.shields.io/badge/Paper-ACL_2024-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2403.07969) [![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-KnowCoder-orange.svg)](https://ict-goknow.github.io/knowcoder/) [![project](https://img.shields.io/badge/%F0%9F%92%AC%20Demo-KnowCoder-green.svg)](http://gomate.ac.cn:10521/) [![model](https://img.shields.io/badge/%F0%9F%A4%97%20Huggingface-Collections-blue.svg)](https://huggingface.co/collections/golaxy/knowcoder-65fc3cd385d98567da412abf) [![](https://img.shields.io/github/stars/ICT-GoKnow/KnowCoder?style=social&label=Code+Stars)](https://github.com/ICT-GoKnow/KnowCoder)

- Invitation code for demo registration: **G4O7M1A5T6E3**.
- We propose a novel method to encode structured knowledge into large language models (LLMs) for universal information extraction (UIE).
</div>
</div>


### 📚 Machine Translation
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 (Findings)</div><img src='images/mmt-vqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Incorporating Probing Signals into Multimodal Machine Translation via Visual Question-Answering Pairs](https://aclanthology.org/2023.findings-emnlp.978.pdf)

**Yuxin Zuo\***, Bei Li\*, Chuanhao Lv, Tong Zheng, Tong Xiao, and JingBo Zhu

<!-- [**EMNLP 2023 (Findings)**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=wzbJ5EIAAAAJ&sortby=pubdate&citation_for_view=wzbJ5EIAAAAJ:bEWYMUwI8FkC) <strong><span class='show_paper_citations' data='wzbJ5EIAAAAJ:bEWYMUwI8FkC'></span></strong> -->

[![arXiv](https://img.shields.io/badge/Paper-EMNLP_2023-b31b1b.svg?style=plastic&logo=arXiv)](https://aclanthology.org/2023.findings-emnlp.978.pdf) [![](https://img.shields.io/github/stars/libeineu/MMT-VQA?style=social&label=Code+Stars)](https://github.com/libeineu/MMT-VQA)

- This paper presents an in-depth study of multimodal machine translation (MMT), examining the prevailing understanding that MMT systems exhibit decreased sensitivity to visual information when text inputs are complete.
</div>
</div>


<!-- #### 📖 Information Extraction

- [KnowCoder: Coding Structured Knowledge into LLMs for Universal Information Extraction](https://github.com/ICT-GoKnow/KnowCoder)

**Yuxin Zuo\***, Zixuan Li\*, Yutao Zeng\*,  Weicheng Ren\*, Wenxuan Liu, Miao Su, Yucan Guo, Yantao Liu, Xiang Li, Zhilei Hu, Long Bai, Wei Li, Yidan Liu, Pan Yang, Xiaolong Jin, Jiafeng Guo, and Xueqi Cheng

**ACL 2024 (Main)**

#### 📚 Machine Translation

- [Incorporating Probing Signals into Multimodal Machine Translation via Visual Question-Answering Pairs](https://github.com/libeineu/MMT-VQA)

**Yuxin Zuo\***, Bei Li\*, Chuanhao Lv, Tong Zheng, Tong Xiao, and JingBo Zhu

**EMNLP 2023 (Findings)**

#### 🧑‍🎨 In-Context Learning -->


# 🎖 Honors and Awards
- *2024.05* Presidential Award of Northeastern University (China) (东北大学 校长奖章) **[[Page]](https://mp.weixin.qq.com/s/we-Leze1c7VKOCP9KBOBiw) [10 Winners]**


# 📖 Educations
- **[University of Chinese Academy of Sciences](https://www.ucas.ac.cn) [(ICT/CAS)](http://www.ict.ac.cn)**, *2024.09 - 2027.06 (Expected)*

  M.S. in Computer Science and Technology.

- **[Northeastern University (China)](https://www.neu.edu.cn)**, *2020.09 - 2024.06*

  B.E. in Software Engineering (AI track).

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->