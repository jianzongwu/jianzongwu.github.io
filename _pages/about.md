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

Hi, I am **Jianzong Wu (吴健宗)**, a **PhD Student** at [School of Intelligence Science and Technology](https://www.cis.pku.edu.cn/), [Peking University (PKU)](https://www.pku.edu.cn/), advised by [Prof. Yunhai Tong](https://scholar.google.com/citations?hl=zh-CN&user=T4gqdPkAAAAJ). Previously, I obtained my bachelor's degree at [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/). I work closely with [Dr. Xiangtai Li](https://lxtgh.github.io/) from NTU, [Dr. Jingbo Wang](https://wangjingbo1219.github.io/) from CUHK (MMLAB), [Dr. Yanhong Zeng](https://zengyh1900.github.io/) from SAI, and [Dr. Xin Tao](https://www.xtao.website/) from Kling team..

My research interests focus on leveraging AIGC technologies to create practical application tools that can improve people's daily lives and drive innovations in academia.
My primary research areas include multimodal learning and controllable generation of images, videos, and artistic creations.

I will graduate in 2026 Summer. I'm looking for a job. Please contact me through [email](jzwu@stu.pku.edu.cn).


# 🔥 News

- *2025.03*: &nbsp;🎉🎉 Congradulations! Three papers were accepted by CVPR 2025!
- *2024.12*: &nbsp;🎉🎉 I have started my internship at Kling Team, Kuaishou!
- *2024.09*: &nbsp;🎉🎉 [MotionBooth](https://jianzongwu.github.io/projects/motionbooth) is accepted by NeurIPS 2024 as spotlight!
- *2024.02*: &nbsp;🎉🎉 [LGVI](https://jianzongwu.github.io/projects/rovi/) is accepted by CVPR!
- *2024.02*: &nbsp;🎉🎉 [Towards Robust Referring Image Segmentation](https://arxiv.org/abs/2209.09554) is accepted by TIP!
- *2024.01*: &nbsp;🎉🎉 [Towards Open Vocabulary Learning: A Survey](https://arxiv.org/abs/2306.15880) is accepted by TPAMI!
- *2023.07*: &nbsp;🎉🎉 [CGG](https://arxiv.org/abs/2301.00805) is accepted by ICCV-2023!

# 📝 Selected Publications 

Full publications can be seen [here](https://scholar.google.com/citations?user=Q_fbCwkAAAAJ&hl=zh-CN)

\* means equal contribution.

<!-- VMoBA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Submission</div><img src='images/papers/VMoBA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VMoBA: Mixture-of-Block Attention for Video Diffusion Models](https://arxiv.org/abs/2506.23858)

**Jianzong Wu**, Liang Hou, Haotian Yang, Xin Tao, Ye Tian, Pengfei Wan, Di Zhang, Yunhai Tong

[**Code**](https://github.com/KwaiVGI/VMoBA)<img src="https://img.shields.io/github/stars/KwaiVGI/VMoBA?style=flat&amp;logo=github&amp;logoColor=black&amp;labelColor=beige&amp;color=green" alt="KwaiVGI/VMoBA Repo">

- The first sparse attention mechanism based on MoBA, designed for video diffusion model **training**.

</div>
</div>

<!-- DiffSensei -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/papers/DiffSensei.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffSensei: Bridging Multi-Modal LLMs and Diffusion Models for Customized Manga Generation](https://arxiv.org/abs/2412.07589)

**Jianzong Wu**, Chao Tang, Jingbo Wang, Yanhong Zeng, Xiangtai Li, Yunhai Tong

[**Project**](https://jianzongwu.github.io/projects/diffsensei)
|
[**Code**](https://github.com/jianzongwu/DiffSensei)<img src="https://img.shields.io/github/stars/jianzongwu/DiffSensei?style=flat&amp;logo=github&amp;logoColor=black&amp;labelColor=beige&amp;color=green" alt="jianzongwu/DiffSensei Repo">

- DiffSensei can generate controllable black-and-white manga panels with flexible character adaptation.

</div>
</div>

<!-- MotionBooth -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Spotlight</div><img src='images/papers/MotionBooth.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MotionBooth: Motion-Aware Customized Text-to-Video Generation](https://arxiv.org/abs/2406.17758)

**Jianzong Wu**, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen

[**Project**](https://jianzongwu.github.io/projects/motionbooth)
|
[**Code**](https://github.com/jianzongwu/MotionBooth)<img src="https://img.shields.io/github/stars/jianzongwu/MotionBooth?style=flat&amp;logo=github&amp;logoColor=black&amp;labelColor=beige&amp;color=green" alt="jianzongwu/MotionBooth Repo">

- Let's animate customized subjects with precise control over both object and camera movements!

</div>
</div>

<!-- LGVI -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/papers/LGVI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Language-Driven Video Inpainting via Multimodal Large Language Models](https://arxiv.org/abs/2401.10226)

**Jianzong Wu**, Xiangtai Li, Chenyang Si, Shangchen Zhou, Jingkang Yang, Jiangning Zhang, Yining Li, Kai Chen, Yunhai Tong, Zewei Liu, Chen Change Loy

[**Project**](https://jianzongwu.github.io/projects/rovi/)
|
[**Code**](https://github.com/jianzongwu/Language-Driven-Video-Inpainting)<img src="https://img.shields.io/github/stars/jianzongwu/Language-Driven-Video-Inpainting?style=flat&amp;logo=github&amp;logoColor=black&amp;labelColor=beige&amp;color=green" alt="jianzongwu/Language-Driven-Video-Inpainting Repo">

- Novel language-driven video inpainting task, dataset, and model.

</div>
</div>

<!-- OV Survey -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/papers/OV-survey.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Open Vocabulary Learning: A Survey](https://arxiv.org/abs/2306.15880)

**Jianzong Wu\***, Xiangtai Li\*, Shilin Xu\*, Haobo Yuan, Henghui Ding, Xia Li, Jiangning Zhang, Yunhai Tong, Xudong Jiang, Bernard Ghanem, Dacheng Tao

[**Code**](https://github.com/jianzongwu/Awesome-Open-Vocabulary)<img src="https://img.shields.io/github/stars/jianzongwu/Awesome-Open-Vocabulary?style=flat&amp;logo=github&amp;logoColor=black&amp;labelColor=beige&amp;color=green" alt="jianzongwu/Awesome-Open-Vocabulary Repo">

- A survey on open vocabulary learning.

</div>
</div>

<!-- CGG -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/papers/CGG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Betrayed by Captions: Joint Caption Grounding and Generation for Open Vocabulary Instance Segmentation](https://arxiv.org/abs/2301.00805)

**Jianzong Wu\***, Xiangtai Li\*, Henghui Ding, Xia Li, Guangliang Cheng, Yunhai Tong, Chen Change Loy

[**Code**](https://github.com/jianzongwu/betrayed-by-captions)

- Query-based open vocabulary segmentation aided by caption generation.

</div>
</div>

<!-- R-RIS -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP</div><img src='images/papers/R-RIS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Robust Referring Image Segmentation](https://arxiv.org/abs/2209.09554)

**Jianzong Wu**, Xiangtai Li, Xia Li, Henghui Ding, Yunhai Tong, Dacheng Tao

[**Code**](https://github.com/jianzongwu/robust-ref-seg)

- Novel robust referring image segmentation (R-RIS) task, dataset, and model.

</div>
</div>

<!-- # 🎖 Honors and Awards -->

# 📖 Educations_
- *2021.07 - now*, PhD Student in Peking University (PKU) 
- *2017.09 - 2021.07*, Bachelor in University of Science and Technology of China (USTC)

<!-- # 💬 Invited Talks -->

# 💻 Internships
- *2024.12 - now*, Kling Team，Kuaishou，mentored by [Haotian Yang](https://yanght321.github.io/).
- *2023.11 - 2024.12*, Shanghai Artificial Intelligence Laboratory, mentored by [Dr. Yining Li](https://scholar.google.com.hk/citations?user=y_cp1sUAAAAJ&hl=en), [Dr. Jingbo Wang](https://wangjingbo1219.github.io/), and [Dr. Xiangtai Li](https://scholar.google.com/citations?user=FL3ReD0AAAAJ).
- *2020.10 - 2021.09*, Search Technology Center Asia (STCA), Microsoft, mentored by [Dr. Congrui Huang](https://scholar.google.com/citations?user=-ETO4kgAAAAJ) and [Dr. Yujing Wang](https://scholar.google.com/citations?user=YgL4rywAAAAJ)
