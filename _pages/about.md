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

👋 Hello, this is Wu Ran. I am currently a postdoc. at Shanghai Jiao Tong University, supervised by [prof. Chao Ma](https://vision.sjtu.edu.cn). Before that, I obtained my Ph.D. of computer science at Fudan University, supervised by [Prof. Hong Lu](https://faculty.fudan.edu.cn/mvl/zh_CN/index.htm).

🖼️ I am currently focusing on vision foundation model distillation, driving scene reconstruction, and vision-language models. I am also interested in computer graphics techniques. In the future, I will build my career primarily on adopting vision foundation models, VLMs for various downstream tasks.

🌴 During my doctoral period, I have maintained a repository [DerainResearch](https://github.com/Schizophreni/DerainResearch), an extension to [DerainZoo](https://github.com/nnUyi/DerainZoo), to collect the latest image restoration and image deraining papers. I will keep on maintaining this repo.

# 🔥 News
- *2025.09.19*: &nbsp;🎉 One paper has been accepted as NeurIPS poster.
- *2025.07.06*: &nbsp;🎉 One co-author paper has been accepted by ACM'MM.
- *2025.06.26*: &nbsp;🎉 One co-author paper has been accepted by ICCV.
- *2025.03.29*: &nbsp;🎉 One co-author paper has been accepted by IEEE TMM.
- *2025.02.14*: &nbsp; Invited as a reviewer for ACM'MM 2025.
<!-- - *2024.09.02*: &nbsp;🎉 Serve as a reviewer for IEEE TCSVT. -->
<!-- - *2024.08.13*: &nbsp;🎉 Invited to be a reviewer for upcoming ICLR 2025.  -->
<!-- - *2024.07.04*: &nbsp;🎉 Serve as a reviewer for IEEE TMM.
- *2024.07.16*: &nbsp;🎉🎉 One paper was accepted by ACM'MM 2024 as a poster. 
- *2024.06.19*: &nbsp;🎉🎉 Obtained a doctoral degree.
- *2024.01.16*: &nbsp;🎉🎉 One paper was accepted by ICLR 2024 as a poster.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/correlated_lora.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Correlated Low-Rank Adaptation for ConvNets](https://openreview.net/pdf/b9f88bd5ef72c19b08153ef1173f3fb4a5d070b2.pdf)

**Wu Ran**, Weijia Zhang, Shuyang Pang, Qi Zhu, Jinfan Liu, Jingsheng Liu, Xin Cao, Qiang Li, Yichao Yan, Chao Ma.

[[**code**]](https://github.com/VISION-SJTU/CoLoRA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2024</div><img src='images/rainmer_motivation.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rainmer: Learning Multi-view Representations for Comprehensive Image Deraining and Beyond](https://openreview.net/pdf?id=rEh8KTz9Ba)

**Wu Ran**, Peirong Ma, Zhiquan He, and Hong Lu.

[[**code**]](https://github.com/Schizophreni/Rainmer) (*codes are available. Pre-traianed models will be uploaded soon*)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/coic.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Harnessing joint rain-/detail-aware representations to eliminate intricate rains](https://arxiv.org/pdf/2404.12091)

**Wu Ran**, Peirong Ma, Zhiquan He, Hao Ren, and Hong Lu.

[[**code**]](https://github.com/Schizophreni/CoIC)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2023</div><img src='images/trnr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TRNR: Task-driven image rain and noise removal with a few images based on patch analysis [[*arxiv*]](https://arxiv.org/pdf/2112.01924)[[*IEEE*]](https://ieeexplore.ieee.org/abstract/document/10007859)

**Wu Ran**, Bohong Yang, Peirong Ma, and Hong Lu.

[[**code**]](https://github.com/Schizophreni/MSResNet-TRNR)
</div>
</div>

## Other publications
- Implicit retinex decomposition with chromaticity disentanglement for low-light image enhancement, M. Liu, **W. Ran**, Z. He, H. Lu, and P. Ma, *ACM'MM*, 2025.
- Cross-architecture distillation made simple with redundancy suppression, W. Zhang, Y. Liu, **W. Ran**, and C. Ma, *ICCV*, 2025.
- Unleashing the potential of hierarchical region clues for open-vocabulary multi-label classification, P. Ma, **W. Ran**, Z. He, J. Pu, and H. Lu, *IEEE TMM*, 2025.
- Feature decoupling and reorganization network for single image deraining, Y. Cheng, J. Huang, H. Ren, **W. Ran**, and H. Lu, *Multimedia Systems 2024*
- A transferable generative framework for multi-label zero-shot learning, P. Ma, Z. He, **W. Ran**, and H. Lu, *IEEE TCSVT 2024*
- Low-light image enhancement with multi-scale attention and frequency-domain optimization, * Z.He, * **W. Ran**, S. Liu, K. Li, J. Lu, C. Xie, Y. Liu, and H. Lu, *IEEE TCSVT 2024* (* equal contribution)
- Weakly-supervised temporal action localization with adaptive clustering and refining network, H. Ren, **W. Ran**, X. Liu, H. Ren, H. Lu, R. Zhang, and C. Jin, *ICME 2023 oral*
- Weakly-supervised temporal action localization with multi-head cross-modal attention, H. Ren, H. Ren, **W. Ran**, H. Lu, and C. Jin, *PRICAI 2022*
- Semantic-related feature generation for generalized zero-shot learning, P. Ma, **W. Ran**, and H. Lu, *ICME 2022*
- Hybrid uncalibrated near-light photometric stereo in realistic environment, **W. Ran**, X. Liu, W. Feng, H. Lu, B. Yang, X. Zhu, and J. Luo, *ISCAS 2022*
- GAN-MVAE: A discriminative latent feature generation framework for generalized zero-shot learning, P. Ma, H. Lu, B. Yang, and **W. Ran**, *PRL 2022*
- Multi-classes and motion properties for concurrent visual slam in dynamic environments, B. Yang, **W. Ran**, L. Wang, H. Lu, and Y.P.P Chen, *IEEE TMM 2021*
- Multi-directional convolution networks with spatial-temporal feature pyramid module for action recognition, B. Yang, Z. Wang, **W. Ran**, H. Lu, and Y.P.P Chen, *ICASSP 2021*
- Rddan: A residual dense dilated aggregated network for single image deraining, Y. Yang, **W. Ran**, and H. Lu, *ICME 2020*
- Single image rain removal boosting via directional gradient, **W. Ran**, Y. Yang, and H. Lu, *ICME 2020 oral*

# 🎖 Honors and Awards
- *2024* Outstanding graduate, Fudan University. 
- *2021-2023* Doctoral study scholarship.
- *2020* Huawei Scholarship
- *2019* Honor class certificate in Physics, Fudan University
- *2016* National encouragement scholarship

# 📖 Educations
- *2021.09 - 2024.06*, I focused on low-level vision problems under the supervision of Prof. Hong Lu at the School of Computer Science, Fudan University. In June 2024, I obtained my doctoral degree.
- *2019.09 - 2021.06*, I was pursuing a master's degree in the School of Computer Science, Fudan University, supervised by Prof. Hong Lu. At that time, I was devoted to image deraining problems. 
- *2015.09 - 2019.06*, I was pursuing a bachelor's degree at Fudan University, majoring in Physics. 

# 💬 Academic Presentations
- *2022*, oral presentation for "Weakly-supervised temporal action localization with multi-head cross-modal attention" at PRICAI 2022. 
- *2022*, "Review on prior- and learning-based image deraining" at the academic seminar of the Computer Science Departement, Fudan University.
- *2020*, oral presentation for "Single image rain removal boosting via directional gradient" at ICME 2020. 

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->