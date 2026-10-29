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

I am Liu Run, a first-year Ph.D. student in the School of Artificial Intelligence at Shanghai Jiao Tong University, in a joint training program with Shanghai AI Laboratory. I obtained my Bachelor's degree in Computer Science and Technology from Wuhan University. My research lies at the intersection of agentic AI, world models, and AI safety: I aim to develop agents that build coherent, predictive models of their environments while remaining aligned, robust, and trustworthy. I am eager to learn from peers and welcome collaborations of all kinds.

I have a number of preliminary ideas in the areas of GUI agents and agent safety, and I also enjoy working on lightweight, fast-to-deploy benchmarks. My next project will focus on a visual agent harness. Feel free to reach out if these directions resonate with you—I'd be happy to chat and collaborate.


# 🔥 News
- *2026.09*:I finished work on machine unlearning and submitted it to ICLR (under review).
- *2026.07*: Our work on LLM personality, on which I am a co-first author, was posted as a preprint on arXiv.
- *2026.06*: &nbsp;🎉🎉 I was awarded the title of Outstanding Graduate of Wuhan University.
- *2026.04*: &nbsp;🎉🎉 One paper I contributed to has been accepted by ACL.
- *2025.12*: &nbsp;🎉🎉 I was awarded the Lei Jun Scholarship(10,000 RMB). I am grateful for the education and nurturing provided by my university.
- *2025.12*: &nbsp;🎉🎉 I was awarded the honorary title of Merit Student and received the Second-Class Scholarship.
- *2025.09*: &nbsp;🎉🎉 One paper I contributed to has been accepted by NeurIPS.
- *2024.12*: &nbsp;🎉🎉 I was awarded the **National Scholarship**.
- *2024.12*: &nbsp;🎉🎉 I was awarded the honorary title of Merit Student and received the First-Class Scholarship.
- *2023.12*: &nbsp;🎉🎉 I was awarded the Yisheng Scholarship (8,000 RMB).
- *2023.12*: &nbsp;🎉🎉 I was awarded the honorary title of Merit Student and received the Second-Class Scholarship.


# 📝 Publications 

## 🥇 First & Co-first Author Papers (First / Co-first Author)
[Your LLM, Your Style: Behavioral Mode Axes for LLM Behavioral Control](https://arxiv.org/abs/2608.10703)  
Haoze Liu, **Run Liu**, Haiying Xu, Jiahui Han, Siyuan Fang, Siyu Yan, Huiqi Deng, Guanchu Wang, Na Zou. **arXiv preprint, 2026**.
**Forgetting Who, Preserving What: Speaker-Identity Unlearning in Audio-Language Models**  
**Run Liu**, Jiaqi Li, Jingyu Li, Jiaxin Guo, Haoze Liu, Yingjun Shang, Hanrui Xu, Lingshuai Lin. **Under review, 2026**.

## 🤝 Collaborative Papers (Contributing Author)
**Generate Multiple Actions, Execute One: Experience-Guided Action Selection for LLM Agent Reinforcement Learning**  
Jiaxin Guo, Haosen Dong, Chenxu Zhang, Muyang Yan, **Run Liu**, Xielyu Ni, Xin Peng, Xiaoming Wu, Zhen Dong. **Under review, 2026**.

[Can We Defend Against AI-Generated Video Attacks on Real-World Crisis Events? A Systematic Evaluation of Detectors, Generators and Social Dissemination](https://arxiv.org/abs/2608.14391)  
Shuo Liang, Yixing Ma, Pengfei Zhou, Zhenglin Wan, Xingyan Chen, Zihan Mei, Manting Li, Feihan Chen, Zhiwen Wang, Bin Xu, Haotian Zhang, Jiajun Song, Shiya Su, **Run Liu**, Zhenghang Ni, Yifa Yu, Jintao Hong, Bolong Feng, Yifei Liu, Zirui Zhang, Jingxuan Zhang, Songlin Zhao, Yifan Bai, Kang Tan, Yizhe Liu, Junhao Du, Yongtao Ge, Zhaopan Xv, Xinyuan Zhang, Mengru Ma, Chunhua Shen, Wei Wang, Yang You, Zheng Zhu, Kaipeng Zhang, Wangbo Zhao. **arXiv preprint, 2026**.

[Mitigating Over-Refusal in Aligned Large Language Models via Inference-Time Activation Energy](https://openreview.net/pdf?id=oaBEvGsVQd)
Eric Hanchen Jiang, Weixuan Ou, **Run Liu**, Shengyuan Pang, Guancheng Wan, Ranjie Duan, Wei Dong, Kai-Wei Chang, XiaoFeng Wang, Ying Nian Wu, Xinfeng Li,**ACL 2026**

[Multi-order Orchestrated Curriculum Distillation for Model-Heterogeneous Federated Graph Learning](https://openreview.net/pdf?id=C9653lXaFO)
Guancheng Wan, Xu Cheng, **Run Liu**, Wenke Huang, Zitong Shi, Pinyi Jin, Guibin Zhang, Bo Du, Mang Ye,**NeurIPS 2025**

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🧩 **Projects**
- ### **LLM-Training-Data-Eval: Multi-Modality LLM Training Data Quality Evaluation Framework**
  
  [GitHub](https://github.com/lhz191/LLM-Training-Data-Eval)
  Open-source two-layer automated evaluation framework for multi-type LLM training data.

  **My Core Work**:
1. Develop the complete image-text multimodal evaluation pipeline, including data loader, format checker, visual quality & cross-modal alignment metrics.
2. Build a semi-structured knowledge graph evaluation module, supporting structural audit and semantic factual validation for graph triples.

# 🎖 Honors and Awards
- *2025.12* the Lei Jun Scholarship. 
- *2024.12* the National Scholarship.
- *2023.12* the Yisheng Scholarship.

# 📖 Educations
- *2026.09 - 2031.06*,Shanghai Jiao Tong University
- *2022.09 - 2026.06*,Wuhan University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2026.10 - 至今*, antgroup, Hangzhou.
- *2025.11 - 2026.05*, Shanghai AI Lab, Shanghai.

# 🎐 Miscellaneous

I am a passionate and open-minded individual who enjoys exploring life and embracing diverse experiences.

🤝 I have always been enthusiastic about public welfare activities, accumulating more than **200 hours of volunteer service** during my undergraduate studies. I once participated in a one-month teaching assistant program in Ganquan County, Shaanxi Province, spending a fulfilling and meaningful summer with my team.

✨ In daily life, I love exploring new things. I have taught myself 🍳 cooking, 🧶 basic knitting, 🛹 longboarding, 🏊 swimming, and I am passionate about 🏋️ fitness and 🥾 hiking. I will continue to explore diverse hobbies and enrich my life experience.

🎵 I am deeply fond of music, including Western pop and K-pop. My favorite artist of all time is **Michael Jackson**.

👋 I sincerely look forward to meeting and making friends with people from all walks of life to broaden my horizons. Feel free to reach out — I am always sincere, reliable, and easy to get along with.

My favorite motto:     **Having seen the immensity of the world, I still cherish the tenderness of all living things.**  （已识乾坤大，犹怜草木青）
