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

I am **Xuanyu Zhang (张轩宇)**, a Ph.D. Student at the School of Computer Science, Peking University, advised by Prof. [Jian Zhang](https://scholar.google.com/citations?hl=zh-CN&user=7brFI_4AAAAJ). Previously, I received my B.Eng degree from School of Electrical and Information Engineering, Tianjin University, advised by Prof. [Jianjun Lei](https://scholar.google.com/citations?user=z_qd4pwAAAAJ&hl=zh-CN&oi=ao), [Pengfei Zhu](https://scholar.google.com/citations?user=iS27HZ8AAAAJ&hl=zh-CN&oi=ao), and [Bo Peng](https://scholar.google.com/citations?user=a8vwUikAAAAJ&hl=zh-CN&oi=ao). Please feel free to reach out via email (xuanyuzhang21@stu.pku.edu.cn).

My recent research interests include MLLM, Visual Reinforcement Learning, AIGC, and Trustworthy AI. I have published **10+** CCF-A papers (as the first/co-first author) with a total Google Scholar citations of **1000+** at top-tier venues including CVPR, NeurIPS, ICLR, AAAI, ACM MM and IJCV, with works spanning united visual understanding and generation, Image or video quality understanding, AIGC forgery localization, multi-agent frameworks, and robust watermarking/steganography for copyright protection. For more details on my publications, please visit my profiles on [Google Scholar](https://scholar.google.com/citations?user=Sq2q-E8AAAAJ&hl=zh-CN&oi=ao).


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Two papers are accepted at CVPR 2026.
- *2026.01*: &nbsp;🎉🎉 Two papers are accepted at ICLR 2026.
- *2025.11*: &nbsp;🎉🎉 One paper is accepted as AAAI 2026 Oral.

# 📝 Publications 
(# denotes equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Oral</div><img src='images/rali.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning as Representation: Rethinking Visual Reinforcement Learning in Image Quality Assessment](https://arxiv.org/abs/2510.11369)

Shijie Zhao#, **Xuanyu Zhang#**, Weiqi Li, Junlin Li, Li Zhang, Tianfan Xue, Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">ICLR 2026 Oral</span> \\
[**Paper**](https://arxiv.org/abs/2510.11369) | [**Code** ![](https://img.shields.io/github/stars/bytedance/Q-Insight?style=social)](https://github.com/xuanyuzhang21/RALI) | [**Model**](https://huggingface.co/ByteDance/Q-Insight)\\
We revisit the reasoning mechanism in MLLM-based IQA model and propose a CLIP-based lightweight image scorer RALI. We verifies that through RL training, MLLMs leverage their reasoning capability to convert redundant visual representations into compact, cross-domain aligned text representations. This conversion is the source of the generalization exhibited by these reasoning-based IQA models. RALI uses only about 4% of Q-Insight’s parameters and inference time, while achieving comparable accuracy.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/vqinsight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VQ-Insight: Teaching VLMs for AI-Generated Video Quality Understanding via Progressive Visual Reinforcement Learning](https://arxiv.org/abs/2506.18564)

**Xuanyu Zhang**, Weiqi Li, Shijie Zhao, Junlin Li, Li Zhang, Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">AAAI 2026 Oral</span> \\
[**Paper**](https://arxiv.org/pdf/2506.18564) | [**Code** ![](https://img.shields.io/github/stars/bytedance/Q-Insight?style=social)](https://github.com/xuanyuzhang21/VQ-Insight) | [**Model**](https://huggingface.co/ByteDance/Q-Insight) \\
We propose VQ-Insight, a novel reasoning-style VLM framework for AIGC video quality assessment. Our approach features: (1) a progressive video quality learning scheme; (2) the design of multi-dimension scoring rewards, preference comparison rewards, and temporal modeling rewards.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Spotlight</div><img src='images/qinsight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Insight: Understanding Image Quality via Visual Reinforcement Learning](https://arxiv.org/abs/2503.22679)

Weiqi Li, **Xuanyu Zhang**, Shijie Zhao, Yabin Zhang, Junlin Li, Li Zhang and Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">NeurIPS 2025 Spotlight</span> \\
[**Paper**](https://arxiv.org/abs/2503.22679) | [**Code** ![](https://img.shields.io/github/stars/bytedance/Q-Insight?style=social)](https://github.com/bytedance/Q-Insight) | [**Model**](https://huggingface.co/ByteDance/Q-Insight) \\
We propose Q-Insight, a reinforcement learning-based model built upon group relative policy optimization (GRPO), which demonstrates strong visual reasoning capability for image quality understanding while requiring only a limited amount of rating scores and degradation labels.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/fakeshield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FakeShield: Explainable Image Forgery Detection and Localization via Multi-modal Large Language Models](https://openreview.net/pdf?id=pAQzEY7M03)

Zhipei Xu#, **Xuanyu Zhang#**, Runyi Li, Zecheng Tang, Qing Huang, Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">ICLR 2025</span>  \\
[**Project**](https://zhipeixu.github.io/projects/FakeShield/) | [**Code** ![](https://img.shields.io/github/stars/zhipeixu/FakeShield?style=social)](https://github.com/zhipeixu/FakeShield)\\
We propose the explainable IFDL task and design FakeShield, a multi-modal framework capable of evaluating image authenticity, generating tampered region masks, and providing a judgment basis based on pixel-level and image-level tampering clues.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/omniguard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniGuard: Hybrid Manipulation Localization via Augmented Versatile Deep Image Watermarking](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_OmniGuard_Hybrid_Manipulation_Localization_via_Augmented_Versatile_Deep_Image_Watermarking_CVPR_2025_paper.pdf)

**Xuanyu Zhang**, Zecheng Tang, Zhipei Xu, Runyi Li, Youmin Xu, Bin Chen, Feng Gao, Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">CVPR 2025</span>  \\
[**Paper**](https://arxiv.org/abs/2412.01615) | [**Code**](https://github.com/xuanyuzhang21/OmniGuard)\\
We propose OmniGuard, a novel augmented versatile watermarking approach that integrates proactive embedding with passive, blind extraction for robust copyright protection and tamper localization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/gshider.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GS-Hider: Hiding Messages into 3D Gaussian Splatting](https://proceedings.neurips.cc/paper_files/paper/2024/file/59091e8226128dfad5f1d75a58f18906-Paper-Conference.pdf)

**Xuanyu Zhang**, Jiarui Meng, Runyi Li, Zhipei Xu, Yongbing Zhang, Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">NeurIPS 2024</span>  \\
[**Paper**](https://arxiv.org/abs/2405.15118) | [**Code**](https://github.com/xuanyuzhang21/GS-Hider) ｜ [**Project**](https://xuanyuzhang21.github.io/project/gshider/)\\
We propose the **first** 3DGS steganography framework GS-Hider, which can hide an entire 3D scene or an image into the original 3D scene and accurately decode it from 3D Gaussians.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/editguard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EditGuard: Versatile Image Watermarking for Tamper Localization and Copyright Protection](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_EditGuard_Versatile_Image_Watermarking_for_Tamper_Localization_and_Copyright_Protection_CVPR_2024_paper.pdf)

**Xuanyu Zhang**, Runyi Li, Jiwen Yu, Youmin Xu, Weiqi Li, Jian Zhang \\
<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">CVPR 2024</span>  \\
[**Paper**](https://arxiv.org/pdf/2312.08883) | [**Code** ![](https://img.shields.io/github/stars/xuanyuzhang21/EditGuard?style=social)](https://github.com/xuanyuzhang21/EditGuard) | [**Project**](https://xuanyuzhang21.github.io/project/editguard/)\\
We propose a versatile deep forensic watermark for AIGC editing methods, such as stable diffusion inpaint, controlnet, SDXL and etc.
</div>
</div>

# 💻 Internships
- *2025.04* - present, ByteDance, China.

# 🎖 Honors and Awards
- *2025.12* Merit Student at Peking University  
- *2024.10* National Scholarship for Doctoral Students
- *2022.10* National Scholarship for Undergraduate Students

# 📖 Educations
- *2022.09 - 2027.06 (expected)*, Ph.D., Computer Science, Peking University
- *2018.09 - 2022.06*, B.E., Computer Science (Second Degree), Tianjin University
- *2018.09 - 2022.06*, B.E., Communication Engineering, Tianjin University

