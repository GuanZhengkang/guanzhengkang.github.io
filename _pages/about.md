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

I am Zhengkang Guan, a junior undergraduate student from the Department of Statistics and Data Science at Xiamen University. Currently I am actively **seeking** opportunities to pursue a **Ph.D.** program.

I have maintained an impressive academic record with an average score of **90.13** and a GPA of 3.75/4. Furthermore, I am honored to be ranked 3rd out of 44 students in my major.

Here is my [resume](https://drive.google.com/file/d/1d7KJAqc2C6Su8ij9CYVVoq8LJUckNlsz/view?usp=share_link) and [transcript](https://drive.google.com/file/d/1lvfGm5SiJ9Slen3dVl1cSkCdLUwu9_UZ/view).

My research interests primarily lie in the domains of **Graph Model**, **Causal Inference**, **Causal Discovery**, **Computer Vision** and **Causal Reasoning (intersections with AI)**. I am eager to delve deeper into these areas during my doctoral studies.

<br>

# Research Experience and Project
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3D U-NET</div><img src='images/ICDSI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Brain Tumor MRI Image Segmentation by 3D U-Net](https://drive.google.com/file/d/13WulF-Z1ah890ofi7_NX9-nh4P2hdHgL/view?usp=share_link)

**Zhengkang Guan**, Jiayin Liu, Yizhi Zhou

- **Best CV Project** --- *2024 Imperial College Data Science Winter School*   *(01.2024 - 02.2024)*
- Low-Resolution Small Dataset Version of the Brain Tumor Segmentation (LS-BraTS) Challenge
- Using 3D-Net network for segmentation and achieving a Dice coefficient of 85.4% on the test set, securing the top position.
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
- From ordinary linear regression model to linear DAG models for causal discovery by non-Gaussianity
- Simulations and feasible analysis of Linear Non-Gaussian Acyclic Model applied to real-world data
- Comparative analysis of ICA-based Algorithm and Direct Algorithm
- In contrast, the ICA-based algorithm demonstrates **greater robustness** to non-normality assumptions and performs **effectively** on real-world data with simple structures, highlighting the potential of LiNGAM in empirical research.

</div>
</div>


<!--

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


-->


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

# Educations
- *09.2021 - 06.2025*, Bachelor of Science in Data Science and Big Data. Xiamen University, School of Economics, Department of Statistics and Data Science.
