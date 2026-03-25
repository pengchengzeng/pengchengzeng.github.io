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
I am currently a tenure-track Assistant Professor and Principal Investigator (PI) at the Institute of Mathematical Sciences, ShanghaiTech University (上海科技大学). My research interests include statistical machine learning, artificial intelligence, and biomedical big data analytics. I am PI of a National Natural Science Foundation of China (NSFC) Youth Science Fund project.

The research group I lead focuses on the following areas:
- **AI and statistics**, with an emphasis on explainable AI and uncertainty quantification;
- **Statistical genomics**, including single-cell multi-omics and spatial transcriptomics;
- **Functional data analysis**, covering methodology, theory, and applications;
- **Data science**, emphasizing interdisciplinary research in collaboration with other fields.

📢📢 <span style="color:red;">  We are seeking a postdoctoral fellow; prospective graduate and undergraduate students are also welcome to join my group. See Opportunities for details.

📢📢 <span style="color:green;"> Collaborations are welcome — particularly with researchers in biomedicine (genomics, spatial omics, etc.), data science, and AI.

# 🔥 News
- *2026.03*: Our paper entitled "GALA: A Unified Landmark-Free Framework for Coarse-to-Fine Spatial Alignment Across Resolutions and Modalities in Spatial Transcriptomics" was accepted by *Briefings in Bioinformatics*.
- *2026.01*: Our paper entitled "DeepFRC: An End-to-End Deep Learning Model for Functional Registration and Classification" was accepted by *ICLR 2026*.
- *2025.12*: Our paper entitled "Guided Co-clustering Transfer Across Unpaired and Paired Single-cell Multi-omics Data" was accepted by *Bioinformatics*. The senior student Hongyao Li is the first author.

# 📘 Publications 
Group members (current and past) are in **bold**; ^+^ : co-first authors with equal contribution; ^#^ : corresponding authors with equal contribution

## (a) Statistical Genomics and Computational Biology
- **Tao Ding** and **Pengcheng Zeng**^#^. GALA: A Unified Landmark-Free Framework for Coarse-to-Fine Spatial Alignment Across Resolutions and Modalities in Spatial Transcriptomics. *Briefings in Bioinformatics*(Accepted), 2026. [[pdf]](https://www.biorxiv.org/content/10.64898/2025.11.29.691288v2.full.pdf) [[code]](https://github.com/TaoDing2/GALA) 
- **Hongyao Li**+, **Yunrui Liu**+ and **Pengcheng Zeng**#. Guided Co-clustering Transfer Across Unpaired and Paired Single-cell Multi-omics Data. *Bioinformatics*; 41(12):btaf639, 2025. [[pdf]](https://watermark02.silverchair.com/btaf639.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA3EwggNtBgkqhkiG9w0BBwagggNeMIIDWgIBADCCA1MGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMO8lKm74YkyVYq__PAgEQgIIDJC5LTMWkJa1ORJ3mVPF0mQT2qI5nYofOkZ8vK6hot7MPQv_WW7M4hBX4nbw_S-4D2yP7Rpe2JGzdOvUF8DAfnqQl8TQa4lv3OLtfWm-DSEJ5Lh-NyIrSFKmZIgCCXMSyp2DJ4wU4eypgz4twZubO3L34aCywfjeUVsc50q9Ybg7BXhvXumhyHmVtqCGqf2S1xGa1XU65G_sDx15dQ0UM90Nlf2p_Gl60hXEhXgZQwc0NO3-o0gxEMLIiZ6WBufh6_9uweHL0dk5TzM4qbS052i-kzIiOebLAoRDbbdkUml5-CgeosxAZCe9yF5hXvtnbGgGlIBHzdLiEfevY_qDHy05snF2hjcFjJcbtp5E9TpYzyYyq-AdYGPq8vuqI0Tki-6kNVllUU4t95LanFT-qyZpbE7ZP5Dwh0x1UwSWve2oOgr2D2Yk44oNngwr2QHiU1zjReP78L2cXhj9LOb8pqT_CVu6hv0B1vJme3dfZLEAC3QhI9LNFiQpHSeNCL4V5wUzpz0SLz-jpGHKR0lIxC3E9Bbi5BHjm8v5Qg8tqgyxefsfUyaitQHKlekBufYFN_xGLFOiiEAHtfKh7rfKJK_52ryl-KjbkjHcYY4cT3GiqWixOvfiyiXdk87TsysrUKRbmXUyEWxrDIa56rYDCc8c66JgLMO0ZRnF11seOxMTxGooqGCn-fYYQ5WYOzU5tTljepH2mdvj3D5_PfVPdHbC6lKJhbliMxf_CIOyquOcjOKcDoOz042bvnvtDBTRY5NmNGFHIKFVYQ8go8jGcWKaRJpEhm2HvlQ096PLK4UUrBM6bWCnjotBPOsPfBaYe95yQsZDhhpbNpIvZy09KadmE1ziPRXGeI2oO_Ln-lmeWkinP1N5auSkkwVdhx-u5XQ8t5trdTwYDLIu_1iCnaK0_uXsoLGIoHZ5aY5BEXogb6KYZbdB-aD9QU8V2Gp56c0hWDb2DwlXDrmUyRdrQV3sFIEGzQZhqqA5uCu6x_-eaf6OT1zGqM3yTGb1lrX2V4XGsXDtp2AQoDLaksNWycfxnfJDW2l6_wNrVsoe4ivxIRiBebQ) [[code]](https://github.com/No-AgCl/GuidedCoC) 
- **Pengcheng Zeng#** and Zhixiang Lin. scICML: Information-theoretic Co-clustering-based Multi-view Learning for the Integrative Analysis of Single-cell Multi-omics data. *IEEE/ACM Transactions on Computational Biology and Bioinformatics*, 2024. DOI : 10.1109/TCBB.2023.3305989. (CCF-B)
- **Pengcheng Zeng** and Zhixiang Lin#. scAWMV: an adaptively weighted multi-view learning framework for the integrative analysis of parallel scRNA-seq and scATAC-seq data. *<font color=Blue>``Bioinformatics``</font>*; 39(1): btac739, 2023.
- Yuanyuan Ma, Zexuan Sun, **Pengcheng Zeng**, Wenyu Zhang and Zhixiang Lin*. JSNMF enables effective and accurate integrative analysis of single-cell multi-omics data. *<font color=Blue>``Briefings in Bioinformatics``</font>*; 23(3):bbac105, 2022.
- **Pengcheng Zeng** and Zhixiang Lin*. coupleCoC+: an information-theoretic co-clustering-based transfer learning framework for the integrative analysis of single-cell genomic data. *<font color=Blue>``PLoS Computational Biology``</font>*; 17 (6): e1009064, 2021.
- **Pengcheng Zeng**, Jiaxuan Wangwu and Zhixiang Lin*. Coupled co-clustering-based unsupervised transfer learning for the integrative analysis of single-cell genomic data. *<font color=Blue>``Briefings in Bioinformatics``</font>*; 22(4):bbaa34, 2021

## (b) Statistical Machine Learning and Functional Data
- **Siyuan Jiang+**, **Yihan Hu+**, **Wenjie Li** and **Pengcheng Zeng#**. DeepFRC: An End-to-End Deep Learning Model for Functional Registration and Classification. *<font color=Blue>``International Conference on Learning Representations (ICLR) 2026``</font>*. (<font color=Blue>``CCF-A``</font>).
- **Wenjie Li**, Jiawei Li, **Pengcheng Zeng#**, Christian Schroeder de Witt, Ameya Prabhu, Amartya Sanyal#. (2026) Delta-Influence: Unlearning Poisons via Influence Functions. *<font color=Blue>``Transactions on Machine Learning Research (TMLR)``</font>*, 2026.
- Lin Tang+, **Pengcheng Zeng+**, Jian Qing Shi* and Won-Seok Kim. Model-based joint curve registration and classification. *<font color=Blue>``Journal of Applied Statistics``</font>*, 2022. https://doi.org/10.1080/02664763.2021.2 023118.
- **Pengcheng Zeng**, Jian Qing Shi# and Won-Seok Kim. Simultaneous registration and clustering for multi-dimensional functional data. *<font color=Blue>``Journal of Computational and Graphical Statistics``</font>*; 4(28): 943-953, 2019

## (c) Data Science and Interdisciplinary Studies
- Chen Jason Zhang+, **Yunrui Liu+**, **Pengcheng Zeng#**, Ting Wu, Lei Chen, Pan Hui and Fei Hao. Similarity-driven and Task-driven Models for Diversity of Opinion in Crowdsourcing Markets. *<font color=Blue>``The International Journal on Very Large Data Bases (The VLDB Journal)``</font>*; 33: 1377–1398, 2024. https://doi.org/10.1007/s00778-024-00853-0.  <font color=Blue>``(CCF-A)``</font>
- Won-Seok Kim+, **Pengcheng Zeng+**, Jian Qing Shi*, Youngjo Lee and Nam-Jong Paik. Semi-automatic Tracking, Smoothing and Segmentation of Hyoid Bone Motion from Videoflfluoroscopic Swallowing Study. *<font color=Blue>``PLoS ONE``</font>*; 12(11): e0188684, 2017. https://doi.org/10.1371/journal. 

## *Preprints*
- **Xinyang Xiong+**, **Siyuan Jiang+** and **Pengcheng Zeng#**. (arXiv 2026) NeuralFLoC: Neural Flow-Based Joint Registration and Clustering of Functional Data arXiv:2602.03169.
- **Pengcheng Zeng+*** and **Siyuan Jiang+**. (arXiv 2025) Semi-parametric Functional Classification via Path Signatures Logistic Regression. https://arxiv.org/abs/2507.06637.
- Benyan Zhang+, ShuHong Yang+, LingYun Wang+, **TianLu Zhu**, Yu Mei, Ying Zhan , XiaoQian Huang, Huan Zhang, Fei Yuan, **Pengcheng Zeng#**, Jinling Jiang#, Jun Zhang#.   Distribution Pattern of Residual Tumour Cells in the Tumour Bed: An Innovative Efficacy Evaluation Method for Advanced Gastric Cancer after Preoperative Therapy. 

# 👥 Group Members
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Autumn 2025</div><img src='images/group_photo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- Postdoctoral Fellow
  
  Tao Ding (ShanghaiTech University, 2024 Spring)
  
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

### Research Assistants

  Yihan Hu (2024-2025, next position: MS in data science, Columbia University)
  
  Tianlu Zhu (2023-2024, next position: MS in data science, University of California, San Franciso (UCSF))

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
- *2014.09*  Full Ph.D. Studentship funded by UK

# 🎓 Experiences
- *2021.12 – present*, Assistant Professor, Institute of Mathematical Sciences, ShanghaiTech University, Shanghai, China
- *2019.09 – 2021.11*, Postdoctoral Fellow, Advisor: [Prof. Zhixiang Lin](https://www.sta.cuhk.edu.hk/peoples/zxlin/) , Department of Statistics, The Chinese University of Hong Kong, China
- *2018.05 – 2019.08*, Data Scientist, Bright Dream Robotics Co., Ltd., Foshan, China
- *2018.07*, Ph.D. (STATISTICS), Advisor: [Prof. Jian Qing Shi](https://www.sustech.edu.cn/zh/faculties/shijianqing.html) (史建清), School of Mathematics & Statistics, Newcastle University,  UK

# 🔍 Opportunities
## Postdoctoral Researcher (New Post)
We seek a postdoctoral fellow to work on methodology and theory in explainable AI and uncertainty quantification, or statistical modeling in single-cell multi-omics and spatial transcriptomics. Prior experience in machine learning, statistics, or computational biology is highly preferred. Strong programming skills are highly valued.

The start date is negotiable and can be immediate. This is a two-year contract, renewable upon satisfactory performance. Salary is competitive and commensurate with experience, with benefits.

To apply, please send the following items to pchzeng at shanghaitech dot edu dot cn:

- CV
- Writing sample (e.g., a published article or preprint)
- Research statement
- Teaching statement
- Contact information for four references

## Graduate and Undergraduate Students
For students interested in joining the research group, please contact me to discuss.
