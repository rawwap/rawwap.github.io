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

I am **Anpeng Wang (王安鹏)**, currently a Master's student at the School of Control Science and Engineering, Shandong University. I am fortunate to study under the supervision of Professor [Runmin Cong](https://rmcong.github.io/) and am affiliated with the [Multimedia and Vision Processing Group (MVP Group)](https://rmcong.github.io/MVPLab.html), which is attached to the Key Laboratory of Machine Intelligence and System Control, Ministry of Education.

I am interested in one of the most basic and distinctive capabilities of human intelligence: the ability to adapt to unfamiliar environments, rapidly and flexibly. Humans can generalize from prior experience, learn rapidly from a few new examples, and use these abilities to acquire surprisingly rich knowledge about the world.

I study how models can develop similar capabilities. How can models generalize out of distribution? How can they effectively reason with available evidence and prior knowledge? When existing knowledge is insufficient, how can they rapidly learn new concepts and capabilities from a few examples? And how should we train models to develop these abilities?

My current research approaches these questions through vision and multimodal models, with a particular focus on **few-shot learning**, **cross-domain learning**, and **visual reasoning**. I am also broadly interested in in-context learning, continual learning, and knowledge internalization.

Feel free to contact me at [rawwap@mail.sdu.edu.cn](mailto:rawwap@mail.sdu.edu.cn) for academic discussions or collaborations.
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.03*: &nbsp;🎉🎉🎉 A paper has been accepted by IEEE ICME 2026!
- *2026.02*: &nbsp;🎉🎉🎉 A cooperative paper has been accepted by CVPR 2026!
- *2026.01*: Attend AAAI 2026 in Singapore and give an oral presentation.
- *2025.11*: &nbsp;🎉🎉🎉 My first paper has been accepted by AAAI 2026 (Oral)!
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/AAAI26_DCDNet4CDFSS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Divide-and-Conquer Decoupled Network for Cross-Domain Few-Shot Segmentation](https://arxiv.org/abs/2511.07798)

Runmin Cong, **Anpeng Wang**, Bin Wan, Cong Zhang, Xiaofei Zhou, Wei Zhang

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
[**Code**](https://github.com/rawwap/DCDNet)
- This paper focuses on Cross-Domain Few-Shot Segmentation, leveraging feature disentanglement enabled by contrastive-adversarial learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/CVPR26_ADSeeker.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ADSeeker: A Knowledge-Grounded Reasoning Framework for Industry Anomaly Detection and Reasoning]()

Kai Zhang, Zekai Zhang, Xihe Sun, **Anpeng Wang**, et al.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!--[**Code**](https://github.com/rawwap/DCDNet)-->
- This paper proposes the ADSeeker framework to improve fine-grained reasoning and zero-shot performance for industrial anomaly detection.
- We construct the first visual document knowledge base SEEK-M&V and the largest anomaly detection dataset MulA to address data scarcity and insufficient type-level annotations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2026</div><img src='images/ICME26_P3SAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[P³-SAM: SAM with Perceptual Parallel Prompt for Few-Shot Strip Steel Surface Defect Segmentation]()

Qian Xu, Hang Xiong, **Anpeng Wang\***, et al. ( \* corresponding author )

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!--[**Code**](https://github.com/rawwap/DCDNet)-->
- This paper proposes the P³-SAM model, which optimizes SAM via two core strategies of POE and PPG to address the challenges of few-shot strip steel surface defect segmentation.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2026.03* Shandong University Outstanding Graduate
- *2026.01* Shandong University OpenAtom Open Source Pioneer Scholarship
- *2024.09* Shandong University Outstanding Student Scholarship
- *2024.07* Shandong University Innovation and Entrepreneurship Scholarship
- *2023.12* APMCM Asia-Pacific Mathematical Contest in Modeling First Prize
- *2023.09* Shandong University Outstanding Student Scholarship
- *2023.08* National University Students Intellingent Car Race National Second Prize

# 📖 Educations
- *2026.09 - present*, Master, School of Control Science and Engineering, Shandong University, Jinan, China. Advisor: [Prof. Runmin Cong](https://rmcong.github.io/)
- *2022.09 - 2026.07*, Undergraduate, School of Control Science and Engineering, Shandong University, Jinan, China. Advisor: [Prof. Runmin Cong](https://rmcong.github.io/)

# 💻 Professional Services
- *2026*, Reviewer for IEEE International Conference on Multimedia and Expo (ICME'26)
- *2025*, Reviewer for Association for the Advancement of Artificial Intelligence (AAAI'26)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->