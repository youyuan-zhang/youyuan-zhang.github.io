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

I am a second year Electrical Engineering master's student at McGill University, advised by Prof. James J. Clark. Prior to that, I obtained my Bachelor's degree in Honors Computer Science at McGill University. 

My research interests lie in computer vision and generative modeling, with a special focus on leveraging generative models for zero-shot inference and optimization task, including image/video editing, and efficient guidance methods for visual generation, model-based optimization and combinatorial optimization. Beside of this, I am also interested in various reasoning tasks, including visual reasoning and LLMs for reasoning.


# 📝 Publications 

- [Decoupling Training-Free Guided Diffusion by ADMM](https://github.com), Youyuan Zhang\*, Zehua Liu\*, Zenan Li\*, Zhaoyu Li\*, James J. Clark, Xujie Si, **In Submission (CVPR 2025)**
- [Design Editing for Offline Model-based Optimization](https://github.com), Ye Yuan\*, Youyuan Zhang\*, Can Chen, Haolun Wu, Zixuan Li, Jianmo Li, James J. Clark, Xue Liu, **In Submission (AAAI 2025)**
- [FastVideoEdit: Leveraging Consistency Models for Efficient Text-to-Video Editing](https://github.com), Youyuan Zhang, Xuan Ju, James J. Clark, **WACV 2025**
- [Distinctive Image Captioning via CLIP Guided Group Optimization](https://github.com), Youyuan Zhang, Jiuniu Wang, Hao Wu, Wenjia Xu, **ECCV Workshop 2022**

# 🎖 Honors and Awards
- *2024*, Grad Excellence Award, McGill University
- *2023*, Dean's Convocation Prize, McGill University
- *2023*, First Class Honours in Computer Science, McGill University
- *2021,2023*, Dean’s Honour List, McGill University
- *2018*, James McGill Scholarship, McGill University

# 📖 Educations
- *2023 - Present*, M.Sc. in Electrical Engineering, advised by Prof. James J. Clark, **McGill University**
- *2018 - 2023*, B.Sc. in Computer Science (with Honors), **McGill University**

# 💬 Invited Talks
- *2024.10*, Guiding Unconditional Diffusion Models Through Differentiable Constraints, REAP Lab, University of Toronto
