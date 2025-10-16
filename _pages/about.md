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
# About Me
I'm a third year Ph.D student from College of information science & electronic engineering, Zhejiang University. My research interest includes model compression (typically vector quantization) and edge accelerators. 

I'm co-advised by Prof. Kejie Huang and Prof. Haibin Shen. I used to be a research intern at VIVO Mobile Communication. 

# 🔥 News
- *2025.06*: 🎉 Two papers accepted by ICCV 2025.
- *2024.12*: 🎉 One paper accepted by AAAI 2025.
- *2024.10*: 🎉 One paper accepted by ASPLOS 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASPLOS 2025</div><img src='images/ASPLOS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MVQ: Towards Efficient DNN Compression and Acceleration with Masked Vector Quantization](https://dl.acm.org/doi/abs/10.1145/3669940.3707268)

**Shuaiting Li**, Chengxuan Wang, Juncan Deng, Zeyu Wang, Zewen Ye, Zongsheng Wang, Haibin Shen, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A highly efficient HW-SW co-designed system for Vector Quantization. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/SSVQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SSVQ: Unleashing the Potential of Vector Quantization with Sign-Splitting](https://arxiv.org/abs/2503.08668)

**Shuaiting Li**, Juncan Deng, Chenxuan Wang, Kedong Xu, Rongtao Deng, Hong Gu, Haibin Shen, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A new Vector Quantization paradigm, simple but effective.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/VIMVQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ViM-VQ: Efficient Post-Training Vector Quantization for Visual Mamba](https://arxiv.org/pdf/2503.09509)

Juncan Deng, **Shuaiting Li**, Zeyu Wang, Kedong Xu, Hong Gu, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The first sub-2bit Vector Quantization solution for Visual Mambas. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/VQ4DIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers](https://ojs.aaai.org/index.php/AAAI/article/view/33782)

Juncan Deng, **Shuaiting Li**, Zeyu Wang, Hong Gu, Kedong Xu, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The first 2bit Vector Quantization solution for Diffusion in Transformers. 
</div>
</div>

- ``TCAS-II`` [Ews: An energy-efficient cnn accelerator with enhanced weight stationary dataflow](https://ieeexplore.ieee.org/abstract/document/10415881), Chengxuan Wang, Zongsheng Wang, **Shuaiting Li**, Yuanming Zhang, Haibin Shen, Kejie Huang.
- ``GRSL`` [Cross-modal adaptation for object detection in thermal infrared remote sensing imagery](https://ieeexplore.ieee.org/abstract/document/10835167), Zeyu Wang, **Shuaiting Li**, Kejie Huang.

# 📖 Educations
- *2023.09 - now*, PhD student, College of information science & electronic engineering, Zhejiang University
- *2019.09 - 2023.06*, Undergrad student, College of information science & electronic engineering, Zhejiang University

# 💻 Internships
- *2024.03 - 2025.9, Research intern at VIVO Mobile Communication, China.
