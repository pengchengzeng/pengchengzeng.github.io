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
I am currently a tenure-track Assistant Professor and Principal Investigator (PI) at the Institute of Mathematical Sciences, ShanghaiTech University (上海科技大学). My research interests include statistical machine learning, AI, and biomedical big data analytics. I am PI of a National Natural Science Foundation of China (NSFC) Youth Science Fund project.

Our research group develops machine learning and statistical methods grounded in theory and interpretability to tackle cutting-edge challenges in biomedical big data, including but not limited to genomics and clinical data. Our current focus areas are:
- **AI + statistics**, focusing on explainable AI, uncertainty quantification, and deep learning solutions to classical statistical problems;
- **Functional data analysis**, spanning methodology, theory, and applications;
- **Statistical genomics**, encompassing single-cell multi-omics and spatial transcriptomics;
- **Data science**, with a focus on interdisciplinary collaboration across diverse fields.

📢📢 <span style="color:red;">  We are seeking a postdoctoral fellow; prospective graduate and undergraduate students are also welcome to join my group. See [[Opportunities]](https://pengchengzeng.github.io/#-opportunities) for details.

📢📢 <span style="color:green;"> Collaborations are welcome — particularly with researchers in biomedicine (genomics, spatial omics, etc.), data science, and AI.

# 🔥 News
- *2026.05*: Our paper on "AI for joint functional registration and clustering" was accepted by *ICML 2026*.
- *2026.03*: Our paper on "Alignment for Spatial Transcriptomics" was accepted by *Briefings in Bioinformatics*.
- *2026.01*: Our paper on "AI for joint functional registration and classification" was accepted by *ICLR 2026*.
- *2025.12*: Our paper on "Transfer learning for single-cell multi-omics data" was accepted by *Bioinformatics*. The senior student Hongyao Li is the first author.

# 📘 Publications 
Group members (current and past) are in **bold**; <sup>+</sup> : co-first authors with equal contribution; <sup>#</sup> : corresponding authors with equal contribution

## (a) Statistical Machine Learning and Functional Data
- **Xinyang Xiong**<sup>+</sup>, **Siyuan Jiang**<sup>+</sup> and **Pengcheng Zeng**<sup>#</sup>. NeuralFLoC: Neural Flow-Based Joint Registration and Clustering of Functional Data. *<font color=Blue>``International Conference on Machine Learning (ICML)``</font>*(Accepted),  2026. [[pdf]](https://arxiv.org/pdf/2602.03169) 
- **Siyuan Jiang**<sup>+</sup>, **Yihan Hu**<sup>+</sup>, **Wenjie Li** and **Pengcheng Zeng**<sup>#</sup>. DeepFRC: An End-to-End Deep Learning Model for Functional Registration and Classification. *<font color=Blue>``International Conference on Learning Representations (ICLR)``</font>*, 2026. [[pdf]](https://openreview.net/forum?id=5vdw8Qmrre) [[code]](https://github.com/Drivergo-93589/DeepFRC)
- **Wenjie Li**, Jiawei Li, **Pengcheng Zeng**<sup>#</sup>, Christian Schroeder de Witt, Ameya Prabhu, Amartya Sanyal<sup>#</sup>. Delta-Influence: Unlearning Poisons via Influence Functions. *<font color=Blue>``Transactions on Machine Learning Research (TMLR)``</font>*, 2026. [[pdf]](https://openreview.net/forum?id=4XtcG8NNaG) [[code]](https://github.com/Ruby-a07/delta-influence)
- Lin Tang<sup>+</sup>, **Pengcheng Zeng**<sup>+</sup>, Jian Qing Shi<sup>#</sup> and Won-Seok Kim. Model-based joint curve registration and classification. *<font color=Blue>``Journal of Applied Statistics``</font>*, 2022. [[pdf]](https://www.tandfonline.com/doi/abs/10.1080/02664763.2021.2023118) 
- **Pengcheng Zeng**, Jian Qing Shi<sup>#</sup> and Won-Seok Kim. Simultaneous registration and clustering for multi-dimensional functional data. *<font color=Blue>``Journal of Computational and Graphical Statistics``</font>*; 4(28):943-953, 2019. [[pdf]](https://www.tandfonline.com/doi/full/10.1080/10618600.2019.1607744) 

## (b) Statistical Genomics and Computational Biology
- **Tao Ding** and **Pengcheng Zeng**<sup>#</sup>. GALA: A Unified Landmark-Free Framework for Coarse-to-Fine Spatial Alignment Across Resolutions and Modalities in Spatial Transcriptomics. *<font color=Blue>``Briefings in Bioinformatics``</font>*; 27(2):bbag181, 2026. [[pdf]](https://www.biorxiv.org/content/10.64898/2025.11.29.691288v2.full.pdf) [[code]](https://github.com/TaoDing2/GALA) 
- **Hongyao Li**<sup>+</sup>, **Yunrui Liu**<sup>+</sup> and **Pengcheng Zeng**<sup>#</sup>. Guided Co-clustering Transfer Across Unpaired and Paired Single-cell Multi-omics Data. *<font color=Blue>``Bioinformatics``</font>*; 41(12):btaf639, 2025. [[pdf]](https://academic.oup.com/bioinformatics/article/41/12/btaf639/8362267?login=false) [[code]](https://github.com/No-AgCl/GuidedCoC) 
- **Pengcheng Zeng**<sup>#</sup> and Zhixiang Lin. scICML: Information-theoretic Co-clustering-based Multi-view Learning for the Integrative Analysis of Single-cell Multi-omics data. *<font color=Blue>``IEEE/ACM Transactions on Computational Biology and Bioinformatics``</font>*, 21(1):200-207, 2024. [[pdf]](https://dl.acm.org/doi/epdf/10.1109/TCBB.2023.3305989) [[code]](https://github.com/pengchengzeng/scICML)
- **Pengcheng Zeng** and Zhixiang Lin<sup>#</sup>. scAWMV: an adaptively weighted multi-view learning framework for the integrative analysis of parallel scRNA-seq and scATAC-seq data. *<font color=Blue>``Bioinformatics``</font>*; 39(1):btac739, 2023. [[pdf]](https://academic.oup.com/bioinformatics/article/39/1/btac739/6831091?login=false) [[code]](https://github.com/pengchengzeng/scAWMV)
- Yuanyuan Ma, Zexuan Sun, **Pengcheng Zeng**, Wenyu Zhang and Zhixiang Lin<sup>#</sup>. JSNMF enables effective and accurate integrative analysis of single-cell multi-omics data. *<font color=Blue>``Briefings in Bioinformatics``</font>*; 23(3):bbac105, 2022. [[pdf]](https://academic.oup.com/bib/article/23/3/bbac105/6563185?login=false) [[code]](https://github.com/cuhklinlab/JSNMF_py)
- **Pengcheng Zeng** and Zhixiang Lin<sup>#</sup>. coupleCoC+: an information-theoretic co-clustering-based transfer learning framework for the integrative analysis of single-cell genomic data. *<font color=Blue>``PLoS Computational Biology``</font>*; 17(6):e1009064, 2021. [[pdf]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009064) [[code]](https://github.com/cuhklinlab/coupleCoC_plus)
- **Pengcheng Zeng**, Jiaxuan Wangwu and Zhixiang Lin<sup>#</sup>. Coupled co-clustering-based unsupervised transfer learning for the integrative analysis of single-cell genomic data. *<font color=Blue>``Briefings in Bioinformatics``</font>*; 22(4):bbaa34, 2021. [[pdf]](https://academic.oup.com/bib/article/22/4/bbaa347/6024740?login=false) [[code]](https://github.com/cuhklinlab/coupleCoC)

## (c) Data Science and Interdisciplinary Studies
- Chen Jason Zhang<sup>+</sup>, **Yunrui Liu**<sup>+</sup>, **Pengcheng Zeng**<sup>#</sup>, Ting Wu, Lei Chen, Pan Hui and Fei Hao. Similarity-driven and Task-driven Models for Diversity of Opinion in Crowdsourcing Markets. *<font color=Blue>``The International Journal on Very Large Data Bases (The VLDB Journal)``</font>*; 33:1377–1398, 2024. [[pdf]](https://link.springer.com/article/10.1007/s00778-024-00853-0) 
- Won-Seok Kim<sup>+</sup>, **Pengcheng Zeng**<sup>+</sup>, Jian Qing Shi<sup>#</sup>, Youngjo Lee and Nam-Jong Paik. Semi-automatic Tracking, Smoothing and Segmentation of Hyoid Bone Motion from Videoflfluoroscopic Swallowing Study. *<font color=Blue>``PLoS ONE``</font>*; 12(11):e0188684, 2017. [[pdf]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0188684) 

## *Preprints*
- **Pengcheng Zeng**<sup>+#</sup> and **Siyuan Jiang**<sup>+</sup>. Semi-parametric Functional Classification via Path Signatures Logistic Regression. arXiv, 2025. [[pdf]](https://arxiv.org/pdf/2507.06637) 
- Benyan Zhang<sup>+</sup>, ShuHong Yang<sup>+</sup>, LingYun Wang<sup>+</sup>, **TianLu Zhu**, Yu Mei, Ying Zhan , XiaoQian Huang, Huan Zhang, Fei Yuan, **Pengcheng Zeng**<sup>#</sup>, Jinling Jiang<sup>#</sup>, Jun Zhang<sup>#</sup>.   Distribution Pattern of Residual Tumour Cells in the Tumour Bed: An Innovative Efficacy Evaluation Method for Advanced Gastric Cancer after Preoperative Therapy. 

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
- *2018.07*, Ph.D. (STATISTICS), Advisor: [Prof. Jian Qing Shi](https://www.sustech.edu.cn/zh/faculties/shijianqing.html) (史建清), School of Mathematics and Statistics, Newcastle University,  UK

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
