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
<br>
<br>


Hi!

I am Zhengkang Guan, a Ph.D. student (Fall 2025 – Present) at the College of Computer Science and Technology, Zhejiang University, supervised by Assoc. Prof. Kun Kuang and Prof. Fei Wu. Previously, I received my Bachelor's degree from the Department of Statistics and Data Science at Xiamen University. 

My primary research interests lie in **Causality and Machine Learning**, with a particular focus on graph models and causal discovery.

<br>

# Publications

<div class='paper-box-text' markdown="1">


## [StablePFN: Stable Prediction with Causal-Aware Tabular Foundation Model](https://dl.acm.org/doi/abs/10.1145/3770855.3818030)

**Zhengkang Guan**, Yikang Chen, Haoyuan Qian, Kairong Han, Peng Cui, Fei Wu, Kun Kuang

- *The 32nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), 2026*
- [PDF](https://dl.acm.org/doi/abs/10.1145/3770855.3818030), [Code](https://github.com/GuanZhengkang/StablePFN)

</div>


<div class='paper-box-text' markdown="1">


## [Efficient Ensemble Conditional Independence Test Framework for Causal Discovery](https://arxiv.org/abs/2509.21021)

**Zhengkang Guan**, Kun Kuang

- *The 14th International Conference on Learning Representations (ICLR), 2026*
- [PDF](https://arxiv.org/abs/2509.21021), [Code](https://github.com/GuanZhengkang/ECIT)

</div>

<br>


---


# Education

- *09.2025 - Present*, Ph.D. in Computer Science and Technology. *Zhejiang University*.
  - College of Computer Science and Technology.
  - Advisors: Assoc. Prof. Kun Kuang & Prof. Fei Wu
- *09.2021 - 06.2025*, B.S. in Data Science and Big Data. *Xiamen University*.
  - School of Economics, Department of Statistics and Data Science.
  - Advisors: Prof. Jingyuan Liu








<!--

<div class='paper-box-text' markdown="1">

## [Learning Linear Mix-Gaussian Acyclic Model by MG-MAP MCMC](https://drive.google.com/file/d/1N_gtb66d8cFiIfczBREAFeytGbj_ErfP/view?usp=share_link)

**Zhengkang Guan**


- *2024 Spring Computational Statistics Course Project*   *(02.2024 - 06.2024)*
- We propose the **Linear Mixed-Gaussian Acyclic Model (LiMGAM)**, attempting causal discovery under the assumption of **mixed** Gaussian and non-Gaussian distributions.
- As long as the system contains some non-Gaussian components, we can obtain useful information (constraints) about the DAG's **topological ordering** (causal order).
- We perform MCMC in the constrained topological ordering space, which significantly **reduces the sampling space** compared to other MCMC methods used for causal discovery.
- Using existing kernel-based methods for likelihood estimation without distributional assumptions does not provide complete likelihood information; it only helps us reject very poor scenarios.

</div>

<br>

---


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3D U-NET</div><img src='images/ICDSI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Brain Tumor MRI Image Segmentation by 3D U-Net](https://drive.google.com/file/d/13WulF-Z1ah890ofi7_NX9-nh4P2hdHgL/view?usp=share_link)

**Zhengkang Guan**, Jiayin Liu, Yizhi Zhou

- **Best CV Project** --- *2024 Imperial College Data Science Winter School*   *(01.2024 - 02.2024)*
- Low-Resolution Small Dataset Version of the Brain Tumor Segmentation (LS-BraTS) Challenge
- Our experiments indicate that commonly used data augmentation methods do **not** effectively address the challenges posed by small sample sizes and low-resolution, instead leading to a significant increase in training costs.
- The accuracy improvement from enhancing the U-Net network structure is also **not** significant, even though it consumes more computational resources.
- We employ a **region-restricted normalization** approach, which significantly enhances the efficiency of the network. And it does not increase the training burden; instead, it leads to earlier convergence during network training.
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">LiNGAM</div><img src='images/LiNGAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Regression to Causal Discovery: LiNGAM Models for Real World Data](https://drive.google.com/file/d/1UK8maOWSK4uhPbgGN3gz7uRWS6SDqOgn/view?usp=share_link)

**Zhengkang Guan**


- *2023 Fall Regression Analysis Course Project*   *(10.2023 - 12.2023)*
- Simulations and feasible analysis of Linear Non-Gaussian Acyclic Model applied to real-world data
- Comparative analysis of ICA-based Algorithm and Direct Algorithm
- In contrast, direct algorithm demonstrates **pooter robustness** to non-normality assumptions and performs **inefficiently** on real-world data with simple structures.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SURVEY</div><img src='images/LiNGAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey of Causal Inference and Model Comparison](https://drive.google.com/file/d/1wb_9t16eWqzxN2YIzFUhGv-FLZ50IC8c/view?usp=share_link)

**Zhengkang Guan**
- *2023 Spring Mathematical Statistics Course Project*
- hhhhhh

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ID-UC</div><img src='images/LiNGAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Practice of Identification Algorithm for Causal Model with Unobserved Confounders](https://github.com/GuanZhengkang/Identification-Algorithm-for-Causal-Model-with-Unobserved-Confounders) **(In Progress)**

**Zhengkang Guan**
- *2024 Spring Multivariate Analysis Course Popularization Project*
- hhh

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">LORD</div><img src='images/LiNGAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[罗德悖论（Lord’s Paradox）：薛定谔的长胖](https://drive.google.com/file/d/1E8n7gisWOYCG3TB9E8bg5SqgnZ-B3ZH_/view?usp=share_link)

**Zhengkang Guan**
- *2024 Spring Multivariate Analysis Course Popularization Essay*
- hhh

</div>
</div>





- [A Survey of Causal Inference and Model Comparison](https://drive.google.com/file/d/1wb_9t16eWqzxN2YIzFUhGv-FLZ50IC8c/view?usp=share_link)
  - *2023 Spring Mathematical Statistics Course Project*   *(04.2023 - 06.2023)*

- [Practice of Identification Algorithm for Semi-Markovian Causal Model](https://github.com/GuanZhengkang/Identification-Algorithm-for-Causal-Model-with-Unobserved-Confounders) **(In Progress)**
  - *2024 Spring Multivariate Analysis Course Popularization Project*

- [罗德悖论（Lord’s Paradox）：薛定谔的长胖](https://drive.google.com/file/d/1E8n7gisWOYCG3TB9E8bg5SqgnZ-B3ZH_/view?usp=share_link)
  - *2024 Spring Multivariate Analysis Course Popularization Essay*



<br>

# Honors and Awards
<div style="display: flex; justify-content: space-between;">
    <div>Academic Excellence Scholarship (1st Class), School of Economics, XMU</div>
    <div>10.2022, 10.2023</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>Cultural and Sports Excellence Scholarship, School of Economics, XMU</div>
    <div>10.2022, 10.2023</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>1st Prize, 2023 China Undergraduate Mathematical Contest in Modeling, Fujian Division</div>
    <div>12.2023</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>2nd Prize, 2022 China Undergraduate Statistical Contest in Modeling, Zhejiang Division</div>
    <div>08.2022</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>2nd Prize, 2022 China Undergraduate Mathematical Contest in Modeling, Fujian Division</div>
    <div>12.2022</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>1st Place, 2021 Xiamen University Football Association Cup League, XMU</div>
    <div>2021-2022</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>1st Place, 2022 Xiamen University Five-a-side Football League, XMU</div>
    <div>2022-2023</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>Outstanding Referee of Xiamen University Football League</div>
    <div>2022-2023</div>
</div>

-->

