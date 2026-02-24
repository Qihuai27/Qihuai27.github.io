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

Hi, I am Zihan Gu (顾子涵), a Ph.D. candidate in Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS), working with Prof. Yue Hu and Hua Zhang. I received my Bachelor of Science degree in Mathematics and Applied Mathematics from Fudan University. My current research interests include interpretable AI, pre-training and post-training of multimodal models, and Diffusion LLM.

My research centers on the development of algorithms and theoretical foundations for interpretable attribution. I investigate hidden-layer representations throughout training and inference from a symbolic and structural perspective, and apply these insights to pre-training, post-training, and continual learning.

My primary objective is to enhance model capabilities through principled theoretical frameworks. This pursuit follows two complementary directions.
First, I study the physics of AI: what classes of models give rise to what capabilities under which data regimes. This line of inquiry aims to provide general laws that inform training strategies.
Second, I analyze the model’s decision-making pathways, including its dominant computational loops and the dependency structure between inputs and outputs. This perspective leads to effective forms of regularization grounded in interpretability.

I view many black-box behaviors—particularly the emergence and generalization of higher-order capabilities—as phenomena that are currently entangled but, in principle, decouplable. Achieving such decoupling is a key step toward the next generation of AI systems.

Beyond machine learning, I have a strong background in linguistics and classical Chinese poetry. A selection of my own poetry is available at <https://huaiqi.site>.

I am open to research collaborations. If these directions resonate with your interests, or if you would like to exchange ideas, please feel free to get in touch.




# 🔥 News
- *2026.02*: &nbsp;🎉🎉 One paper is accepted by **CVPR 2026**. 
- *2026.01*: &nbsp;🎉🎉 One paper is accepted by **ICLR 2026**. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/phasewin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PhaseWin Search Framework Enable Efficient Object-Level Interpretation**

**Zihan Gu**, Ruoyu Chen, Junchi Zhang, Yue Hu, Hua Zhang, Xiaochun Cao

[🌐 Project](https://Qihuai27.github.io/phasewin) &nbsp;&nbsp; [🐙 Code](https://github.com/Qihuai27/phasewin-search) &nbsp;&nbsp; [📄 arXiv](https://arxiv.org/abs/2511.10914)

By conjecturing the decision function of visual models, a near-first-order black-box attribution algorithm is proposed and validated on attribution tasks of object detection and visual grounding.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/deposit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Deconstructing Positional Information: From Attention Logits to Training Biases**

**Zihan Gu**, Ruoyu Chen, Han Zhang, Hua Zhang, Yue Hu

[🌐 Project](https://project-page.com) &nbsp;&nbsp; [🐙 Code](https://github.com/Qihuai27/Deposit-Pattern-Research) &nbsp;&nbsp; [📄 arXiv](https://arxiv.org/abs/2505.13027)

By using the expression of position encoding applied to attention logits, we conjectured the inherent characteristic of RoPE during the training phase: the deposit-pattern, and designed experiments to verify it.
</div>
</div>