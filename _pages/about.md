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
I am a 2nd year PhD student at Fudan University and Shanghai Innovation Institute, advised by Prof. Xiangyang Xue, Prof. Yanwei Fu, and Prof. Binxing Fang. My research focuses on Embodied AI, Spatial Intelligence, and Vision-Language-Action Models. 

I am passionate about developing AI systems that integrate perception, reasoning, and action in complex environments. My work primarily involves 3D multi-modal reconstruction and how it can enable robotic manipulation. Feel free to connect with me via email: lzyzjhz@163.com.


# 🔥 News
- *2026.04*: &nbsp;🚀🚀 As a Core Contributor, we officially released and open-sourced **HY-World 2.0**！**A huge thank you to the amazing team at Tencent Hunyuan and all our collaborative partners for making this milestone possible!** 🙌
- *2025.07*: &nbsp;🎉🎉 Our works on VLA and Active Perception have been accepted by CVPR 2026. Big thank you to my co-authors!
- *2025.07*: &nbsp;🎉🎉 Our works on 3D Spatial Reasoning and Grounding have been accepted by ACMMM 2025. Big thank you to my co-authors!
- *2025.06*: &nbsp;🎉🎉 Our works on Visual Policy Learning have been accepted by ICCV 2025. Big thank you to my co-authors!
- *2025.04*: Attending China3DV at Beijing, China.
- *2025.02*: &nbsp;🎉🎉 Our works on 3D Visual Grounding and Reasoning have been accepted by CVPR 2025. Big thank you to my co-authors!

# 📝 Publications 
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge" style="background-color: #24292e;">Technical Report</div><img src='images/HYWorld2.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[HY-World 2.0: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds](https://3d-models.hunyuan.tencent.com/world/world2_0/HY_World_2_0.pdf)

**Tencent Hunyuan Team** (Core Contributor: **Zhenyang Liu**), **Technical Report 2026**

[[Project Page]](https://3d.hunyuan.tencent.com/login?redirect_url=https%3A%2F%2F3d.hunyuan.tencent.com%2FsceneTo3D) [[GitHub]](https://github.com/Tencent-Hunyuan/HY-World-2.0) [[PDF]](https://3d-models.hunyuan.tencent.com/world/world2_0/HY_World_2_0.pdf)

HY-World 2.0 is a multi-modal world model framework for world generation and world reconstruction. It accepts diverse input modalities — text, single-view images, multi-view images, and videos — and produces 3D world representations (meshes / Gaussian Splattings).
</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2026</div><img src='images/ActiveVLA.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[ActiveVLA: Injecting Active Perception into Vision-Language-Action Models for Precise 3D Robotic Manipulation](https://arxiv.org/pdf/2601.08325)

**Zhenyang Liu**, Yongchong Gu, Yikai Wang, Xiangyang Xue, Yanwei Fu,  **CVPR 2026**

[**Project**](https://zhenyangliu.github.io/ActiveVLA/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

In this work, we propose ActiveVLA, a novel vision-language-action framework with a coarse-to-fine active perception paradigm that dynamically optimizes viewpoints and 3D resolutions for high-precision fine-grained robot manipulation.
</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACMMM 2025</div><img src='images/SpatialReasoner.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[A Neural Representation Framework with LLM-Driven Spatial Reasoning for Open-Vocabulary 3D Visual Grounding](https://dl.acm.org/doi/pdf/10.1145/3746027.3754918)

**Zhenyang Liu**, Sixiao Zheng, Siyu Chen, Cairong Zhao, Longfei Liang, Xiangyang Xue, Yanwei Fu,  **ACMMM 2025**

[**Project**](https://zhenyangliu.github.io/SpatialReasoner/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

In this work, we propose SpatialReasoner, a novel neural representation-based framework with large language model (LLM)-driven spatial reasoning that constructs a visual properties-enhanced hierarchical feature field for open-vocabulary 3D visual grounding.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2025</div><img src='images/DP4.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[Spatial-Temporal Aware Visuomotor Diffusion Policy Learning](https://openaccess.thecvf.com/content/ICCV2025/papers/Liu_Spatial-Temporal_Aware_Visuomotor_Diffusion_Policy_Learning_ICCV_2025_paper.pdf)

**Zhenyang Liu**, Yikai Wang, Kuanning Wang, Longfei Liang, Xiangyang Xue, Yanwei Fu, **ICCV 2025**

[**Project**](https://zhenyangliu.github.io/DP4/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

In this work, we propose 4D Diffusion Policy (DP4), a novel visual imitation learning method that incorporates spatiotemporal awareness into diffusion-based policies. Unlike traditional approaches that rely on trajectory cloning, DP4 leverages a dynamic Gaussian world model to guide the learning of 3D spatial and 4D spatiotemporal perceptions from interactive environments.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2025</div><img src='images/ReasonGrounder.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    
  [ReasonGrounder: LVLM-Guided Hierarchical Feature Splatting for Open-Vocabulary 3D Visual Grounding and Reasoning](https://arxiv.org/abs/2503.23297)
    
  **Zhenyang Liu**, Yikai Wang, Sixiao Zheng, Tongying Pan, Longfei Liang, Yanwei Fu, Xiangyang Xue, **CVPR 2025**

  [**Project**](https://zhenyangliu.github.io/ReasonGrounder/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  ReasonGrounder is a novel LVLM-guided framework that uses hierarchical 3D feature Gaussian fields for adaptive grouping based on physical scale, enabling open-vocabulary 3D grounding and reasoning.
  </div>
</div>



# 💻 Internships
- *2025.09 - Now*, Tencent Hunyuan, Shanghai, China
- *2025.03 - 2025.09*, Shanghai AI Laboratory, Shanghai, China
- *2021.04 - 2024.06*, Media Intelligence Laboratory, Hangzhou, China
