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

# 👨‍🎓 About Me
I am currently a tenure-track Assistant Professor and Principal Investigator (PI) at the Institute of Mathematical Sciences, ShanghaiTech University. My research focuses on statistical machine learning, artificial intelligence, and biomedical big data analytics. I received my Ph.D. in Statistics from Newcastle University, UK, in 2018, under the supervision of [Prof. Jian Qing Shi](https://www.sustech.edu.cn/zh/faculties/shijianqing.html) (史建清).

The research group I lead focuses on the following areas:
- **AI and statistics**, with an emphasis on explainable AI and uncertainty quantification;
- **Functional data analysis**, covering methodology, theory, and applications;
- **Statistical genomics**, including single-cell multi-omics and spatial transcriptomics;
- Interdisciplinary research bridging **data science** with other fields.

📢📢 <span style="color:red;"> My group is recruiting postdoctoral fellows to work on methodology and theory in **explainable AI and uncertainty quantification**, as well as their applications in **single-cell multi-omics and spatial transcriptomics** (see the details in Positions). 

# 🔥 News
- *2026.01*: Our paper entitled "DeepFRC: An End-to-End Deep Learning Model for Functional Registration and Classification" was accepted by ICLR 2026.
- *2025.12*: Our paper entitled "Guided Co-clustering Transfer Across Unpaired and Paired Single-cell Multi-omics Data" was accepted by Bioinformatics.

# 📘 Publications 
___boldface denotes group members___
___+ denotes co-first authors with equal contribution___
___* denotes corresponding author with equal contribution___

## Statistical Machine Learning and Functional Data
- **Siyuan Jiang+**, **Yihan Hu+**, **Wenjie Li** and **Pengcheng Zeng***. (2026) DeepFRC: An End-to-End Deep Learning Model for Functional Registration and Classification. (<font color=Blue>``International Conference on Learning Representations (ICLR) 2026, CCF-A``</font>).
- **Wenjie Li**, Jiawei Li, **Pengcheng Zeng***, Christian Schroeder de Witt, Ameya Prabhu, Amartya Sanyal*. (2026) Delta-Influence: Unlearning Poisons via Influence Functions. Transactions on Machine Learning Research (TMLR). Accepted.
- Lin Tang+, **Pengcheng Zeng+**, Jian Qing Shi* and Won-Seok Kim. (2022) Model-based joint curve registration and classification. Journal of Applied Statistics. https://doi.org/10.1080/02664763.2021.2 023118.
- **Pengcheng Zeng**, Jian Qing Shi* and Won-Seok Kim. (2019) Simultaneous registration and clustering for multi-dimensional functional data. Journal of Computational and Graphical Statistics; 4(28): 943-953. 

## Statistical Genetics and Bioinformatics
- **Hongyao Li+**, **Yunrui Liu+** and **Pengcheng Zeng***. (2025) Guided Co-clustering Transfer Across Unpaired and Paired Single-cell Multi-omics Data. Bioinformatics; 41(12):btaf639.
- **Pengcheng Zeng*** and Zhixiang Lin. (2024) scICML: Information-theoretic Co-clustering-based Multi-view Learning for the Integrative Analysis of Single-cell Multi-omics data. IEEE/ACM Transactions on Computational Biology and Bioinformatics. DOI : 10.1109/TCBB.2023.3305989. (CCF-B)
- **Pengcheng Zeng** and Zhixiang Lin*. (2023) scAWMV: an adaptively weighted multi-view learning framework for the integrative analysis of parallel scRNA-seq and scATAC-seq data. Bioinformatics; 39(1): btac739.
- Yuanyuan Ma, Zexuan Sun, **Pengcheng Zeng**, Wenyu Zhang and Zhixiang Lin*. (2022) JSNMF enables effective and accurate integrative analysis of single-cell multi-omics data. Briefings in Bioinformatics; 23(3):bbac105.
- **Pengcheng Zeng** and Zhixiang Lin*. (2021) coupleCoC+: an information-theoretic co-clustering-based transfer learning framework for the integrative analysis of single-cell genomic data. PLoS Computational Biology; 17 (6): e1009064.
- **Pengcheng Zeng**, Jiaxuan Wangwu and Zhixiang Lin*. (2021) Coupled co-clustering-based unsupervised transfer learning for the integrative analysis of single-cell genomic data. Briefings in Bioinformatics; 22(4):bbaa34. 

## Data Science and Interdisciplinary Studies
- Chen Jason Zhang+, **Yunrui Liu+**, **Pengcheng Zeng***, Ting Wu, Lei Chen, Pan Hui and Fei Hao. (2024) Similarity-driven and Task-driven Models for Diversity of Opinion in Crowdsourcing Markets. The International Journal on Very Large Data Bases (The VLDB Journal); 33: 1377–1398. https://doi.org/10.1007/s00778-024-00853-0. (CCF-A)
- Won-Seok Kim+, **Pengcheng Zeng+**, Jian Qing Shi*, Youngjo Lee and Nam-Jong Paik. (2017) Semi-automatic Tracking, Smoothing and Segmentation of Hyoid Bone Motion from Videoflfluoroscopic Swallowing Study. PLoS ONE; 12(11): e0188684. https://doi.org/10.1371/journal. 

## *Preprints*
- **Xinyang Xiong+**, **Siyuan Jiang+** and **Pengcheng Zeng***. (arXiv 2026) NeuralFLoC: Neural Flow-Based Joint Registration and Clustering of Functional Data arXiv:2602.03169.
- **Pengcheng Zeng+*** and **Siyuan Jiang+**. (arXiv 2025) Semi-parametric Functional Classification via Path Signatures Logistic Regression. https://arxiv.org/abs/2507.06637.
- **Tao Ding** and **Pengcheng Zeng***. (arXiv 2025) A Unified Landmark-Free Framework for Coarse-to-Fine Spatial Alignment Across Resolutions and Modalities in Spatial Transcriptomics. https://www.biorxiv.org/content/10.64898/2025.11.29.691288v1
- Benyan Zhang+, ShuHong Yang+, LingYun Wang+, **TianLu Zhu**, Yu Mei, Ying Zhan , XiaoQian Huang, Huan Zhang, Fei Yuan, **Pengcheng Zeng***, Jinling Jiang*, Jun Zhang*.   Distribution Pattern of Residual Tumour Cells in the Tumour Bed: An Innovative Efficacy Evaluation Method for Advanced Gastric Cancer after Preoperative Therapy. 

# 📋 Group Members
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Autumn Outing 2025</div><img src='images/group_photo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- Postdoctoral Fellow
  
  Tao Ding
  
- PhD students
  
  Siyuan Jiang (ShanghaiTech University, 2023 Fall)
  
  Yunrui Liu (ShanghaiTech University, 2023 Fall)
  
- Master students
  
  Zhenhong Gui (ShanghaiTech University, 2024 Fall)
  
  Xinyang Xiong (ShanghaiTech University, 2024 Fall)
  
  Wenjie Li (ShanghaiTech University, 2022 Fall)

- Research Assistants
  
  Hongyao Li (ShanghaiTech University, 2024 Fall)
  
  Peida Wu (ShanghaiTech University, 2024 Fall)

</div>
</div>

## *Alumni*
  
  Yihan Hu (RA, next position: master in)
  
  Tianlu Zhu (RA, next position: master in )

# 👨‍🏫 Teaching
## Master courses
- *Statistical Foundation of Data Science*: 2026 Spring
- *Data Science: Principle and Practice*: 2024 Autumn
- *Statistical InferenceⅠ*: 2023 Spring, 2024 Spring, 2025 Spring

## Undergraduate courses
- *Linear Algebra Ⅰ*: 2025 Autumn
- *Probability and Statistics Ⅰ*: 2022 Spring &Autumn, 2023 Autumn
- *Undergraduate Seminar*: 2024 Autumn


# 🏆 Honors and Awards
- *2024.01* “Pearl Elite Talents of 2024” of Shanghai City
- *2024.01* “Excellent Faculty of 2023” of ShanghaiTech University
- *2023.01* “Overseas Leading Talents of 2023” of Shanghai City
- *2014.09*  Ph.D. Full Scholarship

# 🎓 Experiences
- *2021.12 – present*, Assistant Professor, Institute of Mathematical Sciences, ShanghaiTech University, Shanghai, China
- *2019.09 – 2021.11*, Postdoctoral Fellow, Department of Statistics, The Chinese University of Hong Kong, Hong Kong SAR, China
- *2018.05 – 2019.08*, Data Scientist, Bright Dream Robotics Co., Ltd., Foshan, China
- *2018.07*, Ph.D. (STATISTICS), School of Mathematics & Statistics, Newcastle University, Newcastle upon Tyne, UK

# 🏆 Positions
- *2025.05* Huawei Scholarship
- *2024.07* Graduated from the 1st National Training for College Cybersecurity Teachers
- *2023.12* Best Paper Award of IEEE Cybermatics Congress 2023
- *2021.01* Outstanding Graduates of Tianjin University
- *2020.08* OnMicro Scholarship
