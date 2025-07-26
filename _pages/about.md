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

I am a first-year student in College of Engineering at Boston University (BU), advised by Prof. <a href="https://yigonghu.github.io/">Yigong Hu</a>.

I earned my master's degree (<strong>MPhil.</strong>) in Data Science and Analytics Thrust (DSA) at The Hong Kong University of Science and Technology (Guangzhou), supervised by Prof. <a href="https://zeyiwen.github.io/">Zeyi Wen</a> and co-supervised by Prof. <a href="https://soldierchen.github.io/">Xinyu Chen</a>. Before that, I received my bachelor's degree (<strong>B.Eng.</strong>) at Guangzhou University, where I was fortunate to work closely with Prof. <a href="https://isr.gzhu.edu.cn/info/1316/1319.htm">Xue-Feng Yuan</a> during my junior and senior years.

I used to study data sparsity problems in sequential recommender system and applications of low-rank techniques in large language models, published 6 papers (my google scholar: <a href='https://scholar.google.com/citations?user=7pDl1GsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) on these subjects during my master's research. Now, I am more interested in system reliability for my Ph.D. research, focusing on building a reliable and fast system.

# 🔥 News
- *2025.07*: &nbsp;🎓 Received my master's degree (MPhil. in Data Science and Analytics) at The Hong Kong University of Science and Techonlogy.

# 📝 Publications 

## System
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ArXiv</div>
      <img src='images/paper/gigiProfiler.jpg' alt="sym" width="100%">
    </div>
  </div>
  
<div class='paper-box-text' markdown="1">

[gigiProfiler: Diagnosing Performance Issues by Uncovering Application Resource Bottlenecks](https://arxiv.org/abs/2507.06452)

Yigong Hu, Haodong Zheng, Yicheng Liu, Dedong Xie, <strong>Youliang Huang</strong>, Baris Kasikci

- Introduce **OmniResource Profiling** to track both system-level and application-level resources to comprehensively dignose resource bottlenecks. 
- Using hybrid LLM-static analysis approach to identify application resources with LLMs and analyze performance bottlenecks with buggy execution.  
</div> 
</div>

## Large Language Models
<div class='paper-box'>
<ul>
<li>
    <code class="language-plaintext highlighter-rouge">ICCV 2025</code>
    <a href="https://iccv.thecvf.com/virtual/2025/poster/2269">Efficient Fine-Tuning of Large Models via Nested Low-Rank Adaptation</a>
    <br>
    Lujun Li, Cheng Lin, Dezhi Li, <strong>You-Liang Huang</strong>, Wei Li, Tianyu Wu, Jie Zou, Wei Xue, Sirui Han, Yike Guo 
</li>
<li>
    <code class="language-plaintext highlighter-rouge">AAAI 2025</code>
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/33923">SoLA: Leveraging Soft Activation Sparsity and Low-Rank Decomposition for Large Language Model Compression</a>
    <br>
    Xinhao Huang, <strong>You-Liang Huang</strong>, Zeyi Wen
</li>
<li>
    <code class="language-plaintext highlighter-rouge">AAAI 2025</code>
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/34530">Towards Efficient Low-order Hybrid Optimizer for Language Model Fine-tuning</a>
    <br>
    Minping Chen, <strong>You-Liang Huang</strong>, Zeyi Wen
</li>
<li>
    <code class="language-plaintext highlighter-rouge">ICML 2025</code>
    <a href="https://openreview.net/forum?id=acJ3vdFljk">MoE-SVD: Structured Mixture-of-Experts LLMs Compression via Singular Value Decomposition</a>
    <br>
    Wei Li, Lujun Li, Hao Gu, <strong>You-Liang Huang</strong>, Mark G. Lee, Shengjie Sun, Wei Xue, Yike Guo
</li>
</ul> 
</div>
<!-- Paper Partition -->

## 📊 Recommender System
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">WWW 2025 (Oral)</div>
      <img src='images/paper/MSRBench.png' alt="sym" width="100%">
    </div>
  </div>
  
<div class='paper-box-text' markdown="1">

[When Large Vision Language Models Meet Multimodal Sequential Recommendation: An Empirical Study](https://dl.acm.org/doi/10.1145/3696410.3714764)

Peilin Zhou, Chao Liu, Jing Ren, Xinfeng Zhou, Yueqi Xie, Meng Cao, Zhongtao Rao, **You-Liang Huang**, Dading Chong, Junling Liu, Jae Boum Kim, Shoujin Wang, Raymond Chi-Wing Wong, Sunghun Kim

<a href="https://github.com/PALIN2018/MSRBench"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>
- Introduces **MSRBench**, the first benchmark to systematically evaluate the integration of Large Vision Language Models (LVLMs) in multimodal sequential recommendation.
- Compares five integration strategies (recommender, item enhancer, reranker, and two combinations), identifying **reranker** as the most effective.
- Constructs the enhanced dataset **Amazon Review Plus**, with LVLM-generated image descriptions to support more flexible item modeling.
</div> 
</div>
<!-- Paper Partition -->
<div class='paper-box'>
<ul>
<li>
    <code class="language-plaintext highlighter-rouge">WWW 2024</code>
    <a href="https://dl.acm.org/doi/abs/10.1145/3589334.3645661">Is contrastive learning necessary? a study of data augmentation vs contrastive learning in sequential recommendation</a>
    <br>
    Peilin Zhou*, <strong>You-Liang Huang</strong>*, Yueqi Xie, Jingqi Gao, Shoujin Wang, Jae Boum Kim, Sunghun Kim
    <a href="https://github.com/AIM-SE/DA4Rec"><img src="https://img.shields.io/github/stars/AIM-SE/DA4Rec?style=social&amp;label=Code+Stars" alt=""></a>
</li>
<li>
    <code class="language-plaintext highlighter-rouge">ArXiv</code>
    <a href="https://arxiv.org/pdf/2311.04199"> Exploring Recommendation Capabilities of GPT-4V (ision): A Preliminary Case Study</a>
    <br>
    Peilin Zhou, Meng Cao, <strong>You-Liang Huang</strong>, Qichen Ye, Peiyan Zhang, Junling Liu, Yueqi Xie, Yining Hua, Jaeboum Kim
    <a href="https://github.com/PALIN2018/Evaluate_GPT-4V_Rec"><img src="https://img.shields.io/github/stars/PALIN2018/Evaluate_GPT-4V_Rec?style=social&amp;label=Code+Stars" alt=""></a>
</li>
</ul> 
</div>
<!-- Paper Partition -->

## 📚 Others
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Computers & Graphics</div>
      <img src='images/paper/styleterrain.jpg' alt="sym" width="100%">
    </div>
  </div>
  
<div class='paper-box-text' markdown="1">

[StyleTerrain: A novel disentangled generative model for controllable high-quality procedural terrain generation](https://doi.org/10.1016/j.cag.2023.09.002),
*Computers & Graphics, Volume 116, Pages 373-382*

**You-Liang Huang**, Xue-Feng Yuan

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- It introduces disentangled representation learning into Generative Adversarial Network (GAN)-based terrain modeling methods.
- Disentangling latent space to achieve controllable DEM generation with diverse landscape features.
</div> 
</div>

# 💁 Professional Services
- AAAI'26, Program Committee
- ICLR'25, Reviewer
- Eurographics'24, Reviewer

# 🎖 Honors and Awards
- *2023.05* Dean's List and First Price Studentship, Guangzhou University.
- *2022.11* Dean's List and First Price Studentship, Guangzhou University.
- *2021.10* Dean's List and First Price Studentship, Guangzhou University.
- *2021.08* The third price in [Computer System Development Capability Competition](https://os.educg.net/).
- *2020.11* Dean's List and First Price Studentship, Guangzhou University.

# 📖 Educations
- *2025.09 - Present*, **Ph.D. student** in Computer Engineering, Boston University.
- *2023.09 - 2025.07*, **MPhil.** in Data Science and Analytics, CGA: 3.66(4.3), Hong Kong University of Science and Technology. 
- *2019.09 - 2023.06*, **B.Eng.** in Network Engineering, GPA: 3.87(4.0), Rank: 2nd(163), Guangzhou University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.01 - 2023.10*, [DeepSE Lab](https://www.cse.ust.hk/~hunkim), The Hong Kong University of Science and Technology, China.
- *2021.11 - 2023.06*, [Institute of System Rheology](https://isr.gzhu.edu.cn), Guangzhou University, China.

# 🗺️ Visitor Map
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=vFIVVM9kTlwKUhv5DzQAHpxJlqJjHR6Oeq4SKS3CKFg&cl=ffffff&w=a"></script>