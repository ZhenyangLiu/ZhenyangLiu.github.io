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
# 🤵🏻 About me
I am a 1th year PhD student at Fudan University and Shanghai Innovation Institute, advised by Prof. Xiangyang Xue, Prof. Yanwei Fu, and Prof. Binxing Fang. My research focuses on Embodied AI, Spatial Intelligence, and Vision-Language-Action Models. 

I am passionate about developing AI systems that integrate perception, reasoning, and action in complex environments. My work primarily involves 3D multi-modal reconstruction and how it can enable robotic manipulation. Feel free to connect with me via email: lzyzjhz@163.com.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Our works on Visual Policy Learning have been accepted by ICCV 2025. Big thank you to my co-authors!
- *2025.04*: Attending China3DV at Beijing, China.
- *2025.02*: &nbsp;🎉🎉 Our works on 3D Visual Grounding and Reasoning have been accepted by CVPR 2025. Big thank you to my co-authors!

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/ReasonGrounder.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReasonGrounder: LVLM-Guided Hierarchical Feature Splatting for Open-Vocabulary 3D Visual Grounding and Reasoning](https://arxiv.org/abs/2503.23297)

**Zhenyang Liu**, Yikai Wang, Sixiao Zheng, Tongying Pan, Longfei Liang, Yanwei Fu, Xiangyang Xue, **CVPR 2025**

[**Project**](https://zhenyangliu.github.io/ReasonGrounder/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

ReasonGrounder is a novel LVLM-guided framework that uses hierarchical 3D feature Gaussian fields for adaptive grouping based on physical scale, enabling open-vocabulary 3D grounding and reasoning.

</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/DP4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatial-Temporal Aware Visuomotor Diffusion Policy Learning]()

**Zhenyang Liu**, Yikai Wang, Kuanning Wang, Longfei Liang, Xiangyang Xue, Yanwei Fu, **ICCV 2025**

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

In this work, we propose 4D Diffusion Policy (DP4), a novel visual imitation learning method that incorporates spatiotemporal awareness into diffusion-based policies. Unlike traditional approaches that rely on trajectory cloning, DP4 leverages a dynamic Gaussian world model to guide the learning of 3D spatial and 4D spatiotemporal perceptions from interactive environments.

</div>
</div>

</div>
</div>

# 💻 Internships
- *2025.04 - 2025.10*, Shanghai AI Laboratory, Shanghai, China
- *2021.04 - 2024.06*, Media Intelligence Laboratory, Hangzhou, China
