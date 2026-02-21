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

My recent research interests include MLLM, Reinforcement learning in visual understanding and generation, Reward Model, and Trustworthy AI. I have published **10+** CCF-A papers at top-tier venues including CVPR, NeurIPS, ICLR, AAAI, ACM MM and IJCV, with works spanning united visual understanding and generation, Image or video quality understanding, AIGC forgery localization, multi-agent frameworks, and robust watermarking/steganography for copyright protection. For more details on my publications, please visit my profiles on [Google Scholar](https://scholar.google.com/citations?user=Sq2q-E8AAAAJ&hl=zh-CN&oi=ao).


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Two papers are accepted at CVPR 2026.
- *2026.01*: &nbsp;🎉🎉 Two papers are accepted at ICLR 2026.
- *2025.11*: &nbsp;🎉🎉 One paper is accepted as AAAI 2026 Oral.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Oral</div><img src='images/rali.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning as Representation: Rethinking Visual Reinforcement Learning in Image Quality Assessment](https://arxiv.org/abs/2510.11369)

Shijie Zhao#, **Xuanyu Zhang#**, Weiqi Li, Junlin Li, Li Zhang, Tianfan Xue, Jian Zhang (# denotes equal contribution)

<span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">ICLR 2026 Oral</span>

[**Paper**](https://arxiv.org/abs/2510.11369) | [**Code**](https://github.com/xuanyuzhang21/RALI)<strong><span class='show_paper_citations' data='504N5M0AAAAJ:f2IySw72cVMC'></span></strong>

We revisit the reasoning mechanism in MLLM-based IQA model and propose a CLIP-based lightweight image scorer RALI. We verifies that through RL training, MLLMs leverage their reasoning capability to convert redundant visual representations into compact, cross-domain aligned text representations. This conversion is the source of the generalization exhibited by these reasoning-based IQA models. RALI uses only about 4% of Q-Insight’s parameters and inference time, while achieving comparable accuracy.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/vqinsight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VQ-Insight: Teaching VLMs for AI-Generated Video Quality Understanding via Progressive Visual Reinforcement Learning](https://arxiv.org/abs/2506.18564)

**Xuanyu Zhang**, Weiqi Li, Shijie Zhao, Junlin Li, Li Zhang, Jian Zhang <span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">AAAI 2026 Oral</span>

[**Paper**](https://arxiv.org/pdf/2506.18564) | [**Code**](https://github.com/xuanyuzhang21/VQ-Insight)<strong><span class='show_paper_citations' data='Sq2q-E8AAAAJ&hl=zh-CN&oi=ao'></span></strong>

- We propose VQ-Insight, a novel reasoning-style VLM framework for AIGC video quality assessment. Our approach features: (1) a progressive video quality learning scheme; (2) the design of multi-dimension scoring rewards, preference comparison rewards, and temporal modeling rewards.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Spotlight</div><img src='images/qinsight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Q-Insight: Understanding Image Quality via Visual Reinforcement Learning](https://arxiv.org/abs/2503.22679)

Weiqi Li, **Xuanyu Zhang**, Shijie Zhao, Yabin Zhang, Junlin Li, Li Zhang and Jian Zhang <span style="background-color: #fff9c4; color: #333; padding: 2px 8px; border-radius: 6px; font-weight: bold;">NeurIPS 2025 Spotlight</span>

[**Paper**](https://arxiv.org/abs/2503.22679) | [**Code**](https://github.com/bytedance/Q-Insight)<strong><span class='show_paper_citations' data='504N5M0AAAAJ:f2IySw72cVMC'></span></strong>

We propose Q-Insight, a reinforcement learning-based model built upon group relative policy optimization (GRPO), which demonstrates strong visual reasoning capability for image quality understanding while requiring only a limited amount of rating scores and degradation labels.

</div>
</div>



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.