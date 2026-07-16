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

Hi, I am Wenjing Lu, a fourth-year Ph.D. student at Shanghai Jiao Tong University (SJTU), advised by [Prof. Yang Yang](https://compbio.sjtu.edu.cn) and [Prof. Yi Hong](https://scholar.google.com/citations?user=16OATcwAAAAJ). I am currently a Student Trainee at the RIKEN Center for Advanced Intelligence Project (AIP), supervised by [Dr. Qibin Zhao](https://scholar.google.com/citations?user=cSQGe3YAAAAJ). Before that, I received my master's degree from the National University of Singapore (NUS).

My research interests center on two closely connected directions: **(1) principled theories and methods for uncertainty quantification**, with a focus on calibration, reliability, and robust decision-making, and **(2) medical image analysis**, especially uncertainty-aware learning for segmentation and foundation model adaptation. Recently, I have also become interested in **uncertainty modeling for agentic AI systems**, where reliable uncertainty quantification is crucial for selecting actions, such as querying, orchestrating, routing, or stopping. 

*Please feel free to email me for research, collaborations, or a casual chat.*

Email: luluerji [at] sjtu.edu.cn / wenjing.lu [at] riken.jp

<font color="red"><b><i>I am seeking postdoctoral and industrial research opportunities and would be glad to connect.</i></b></font>


<!-- *Please consider giving me [anonymous feedback](https://docs.google.com/forms/d/e/1FAIpQLSeE4_y14QlUtJ8MhltnGnWwco7J1sWprXnlGoFWFo002k26lw/viewform?usp=sf_link).* -->

# 📣 News

<div class="news-scroll" markdown="1">
- **2026.05**: Our paper "Calibrating Uncertainty for Zero-Shot Adversarial CLIP" is accepted by [ICML 2026](https://arxiv.org/pdf/2512.12997).
- **2026.02**: Our paper "Harmonizing Generalization and Specialization: Uncertainty-Informed Collaborative Learning for Semi-supervised Medical Image Segmentation" is accepted by [IEEE TMI](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11397067).
</div>

# 📖 Educations
- **2025.04 - present**, Student Trainee, RIKEN AIP, advised by [Dr. Qibin Zhao](https://scholar.google.com/citations?user=cSQGe3YAAAAJ).
- **2022.09 - present**, Ph.D. Candidate, AGI Institute, School of Computer Science, Shanghai Jiao Tong University (SJTU), advised by [Prof. Yang Yang](https://scholar.google.com/citations?user=-PN_6coAAAAJ) and [Prof. Yi Hong](https://scholar.google.com/citations?user=16OATcwAAAAJ).
- **2021.08 – 2022.06**, M.S, National University of Singapore (NUS).
- **2017.09 - 2021.06**, B.Eng, University of Electronic Science and Technology of China (UESTC).

<!-- # 📝 Featured Publications
TODO -->


# 📝 Selected Publications
✉️ Corresponding author.


<div class='paper-box'><div class='paper-box-image'><div>
<img src="{{ '/images/UCAT_poster_ICML.png' | relative_url }}" alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-ICML'26-blue)]() **Calibrating Uncertainty for Zero-Shot Adversarial CLIP**. 

**Wenjing Lu**, Zerui Tao, Dongping Zhang, Yuning Qiu, Yang Yang✉️, Qibin Zhao✉️. 

[[paper]](https://arxiv.org/pdf/2512.12997)
[[code]](https://github.com/VivienLu/UCAT)
[[poster]](https://github.com/VivienLu/wenjing.lu/blob/master/images/UCAT_poster_ICML-5.pdf)
<!-- [[code]]()
[[slides]]()
[[poster]]()
[[CN-video]]()
[[EN-video]]()    -->
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<img src="{{ '/images/UnCoL-framework.png' | relative_url }}" alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Journal-IEEETMI'26-green)]() **Harmonizing Generalization and Specialization: Uncertainty-Informed Collaborative Learning for Semi-supervised Medical Image Segmentation**.  

**Wenjing Lu**, Yi Hong✉️, Yang Yang✉️.

[[paper]](https://arxiv.org/pdf/2512.13101)
[[code]](https://github.com/VivienLu/UnCoL)
<!-- [[EN-video]]()    -->
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<img src="{{ '/images/UP-SAM_framework.png' | relative_url }}" alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-BIBM'24-blue)]() **UP-SAM: Uncertainty-Informed Adaptation of Segment Anything Model for Semi-Supervised Medical Image Segmentation**.  

**Wenjing Lu**, Yi Hong✉️, Yang Yang✉️.

[[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10822398)
[[slides]](files/B939-UP-SAM.pdf)
<!--[[slides]](./data/slides/NeurIPS24_CoPA.pdf)
[[poster]](./data/poster/neurips24_CoPA.pdf)
[[CN-video]](https://www.bilibili.com/video/BV1vaUNYTEr3/?spm_id_from=333.999.0.0&vd_source=a1aae47e2835186f922fa2e1c94933c9)
[[EN-video]](https://recorder-v3.slideslive.com/?share=93487&s=0f9f72ed-d9ad-4f34-a0aa-154e07b6f3d7)-->   
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<img src="{{ '/images/UPCoL_framework.png' | relative_url }}" alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-MICCAI'23-blue)]() **UPCoL: Uncertainty-informed Prototype Consistency Learning for Semi-supervised Medical Image Segmentation**.  

**Wenjing Lu**, Jiahao Lei, Peng Qiu, Rui Sheng, Jinhua Zhou, Xinwu Lu, Yang Yang✉️.

[[paper]](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_63)
[[code]](https://github.com/VivienLu/UPCoL)
[[poster]](images/UPCoL_poster-4.pdf)
  
</div>
</div>
<!--<details>
<summary>Quick Introduction</summary>
 In cross-domain few-shot classification (CFC), recent works mainly focus on adapting a simple transformation head on top of a frozen pre-trained backbone with few labeled data to project embeddings into a task-specific metric space where classification can be performed by measuring similarities between image instance and prototype representations. Technically, an assumption implicitly adopted in such a framework is that the prototype and image instance embeddings share the same representation transformation. However, in this paper, we find that there naturally exists a gap, which resembles the modality gap, between the prototype and image instance embeddings extracted from the frozen pre-trained backbone, and simply applying the same transformation during the adaptation phase constrains exploring the optimal representation distributions and shrinks the gap between prototype and image representations. <br><br>
 To solve this problem, we propose a simple yet effective method, contrastive prototype-image adaptation (CoPA), to adapt different transformations for prototypes and images similarly to CLIP by treating prototypes as text prompts. <br><br>
Extensive experiments on Meta-Dataset demonstrate that CoPA achieves the state-of-the-art performance more efficiently. Meanwhile, further analyses also indicate that CoPA can learn better representation clusters, enlarge the gap, and achieve the minimum validation loss at the enlarged gap.
</details>-->



# 🎖 Awards
- **2026.05**, Golden Reviewer Award, ICML'26, Seoul.
- **2024.12**, Student Travel Award, BIBM'24, Lisbon.
- **2022.05**, Second Prize Award for AI paper presentation, AI Research Student Conference 2022 (ARSC‘22), Singapore.
- **2021.06**, Outstanding Graduate of UESTC.


# 💻 Services
- Area Chair: ICLR 2026 Workshop DeLTa, ICML 2026 Workshop FoGen.
- Conference Reviewer for ICML, NeurIPS, MICCAI.
- Journal Reviewer for EAAI and NN.


# 🏫 Teaching
- **CS7336** (G) Machine Learning, Sem. 2, 2023 - 2024

<!-- # 📖 Academic Experiences -->
<!-- - *2026.03 - 2026.06*, Visiting student @[RIKEN Imperfect Information Learning Team](https://www.riken.jp/en/research/labs/aip/generic_tech/imperfect_inf_learn/index.html), advised by [Dr. Takashi Ishida](https://takashiishida.github.io/) and [Prof. Masashi Sugiyama](https://www.ms.k.u-tokyo.ac.jp/sugi/). -->
<!-- - *2023.09 - present*, PhD student @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Dr. Bo Han. -->
<!-- - *2022.07 - 2023.05*, Research intern @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Dr. Bo Han and Dr. Feng Liu.
 -->

# 🏢 Experiences
- **2021.08 - 2022.05**, Research Intern @A*STAR I²R, host by Prof. Bharadwaj Veeravalli and Dr. Zeng Zeng.

  
<!-- <div align=center> -->
<!-- <a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=400&t=tt&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a> -->
<!--<a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=a&t=m&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a>-->
<!-- <a href="https://clustrmaps.com/site/1bztd" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=9WmKAuGZx-jp_Cqemh_qyo-Fhw-l77tju_9bukYAC-o&cl=ffffff"></a> -->
<!-- </div> -->
