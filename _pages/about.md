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

My research focuses on developing algorithms and their principles that can be used for interpretable attribution, analyzing the hidden layer states in the model training and inference process from a symbolic perspective, and applying these theories to model pre-training, post-training, and incremental training.

My core pursuit is to apply theoretical models to improve model capabilities. Theoretically, I trace this back to two main approaches: firstly, studying the physics of AI—that is, what kind of model will exhibit what kind of capabilities on what kind of data; secondly, studying the decision-making interpretation pathways of the model, including the model's main computational loops and the dependence of model decisions on inputs. The former provides general insights that can be used to improve training strategies, while the latter provides effective regularization schemes. I believe that all the black-box behaviors of a model, especially the generalization of higher-order capabilities, are in a state of decoupling or awaiting decoupling. Successful decoupling will drive the further development of artificial intelligence systems.

I am open to research collaborations. If my research or ideas resonate with you, or if you have any interesting thoughts to share, please don't hesitate to contact me.




# 🔥 News
- *2026.02*: &nbsp;🎉🎉 One paper is accepted by **CVPR 2026**. 
- *2026.01*: &nbsp;🎉🎉 One paper is accepted by **ICLR 2026**. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/phasewin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PhaseWin Search Framework Enable Efficient Object-Level Interpretation**

**Zihan Gu**, Ruoyu Chen, Junchi Zhang, Yue Hu, Hua Zhang, Xiaochun Cao

[🌐 Project](https://project-page.com) &nbsp;&nbsp; [🐙 Code](https://github.com/Qihuai27/phasewin-search) &nbsp;&nbsp; [📄 arXiv](https://arxiv.org/abs/2511.10914)

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