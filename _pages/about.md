---
permalink: /
title: '<i class="fas fa-user ic-blue"></i> About me'
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Research Fellow at Nanyang Technological University (NTU), working with Prof. [Kelin Xia](https://personal.ntu.edu.sg/xiakelin/index.html).

Previously, I was a Research Fellow at the National University of Singapore (NUS), supervised by Prof. [Xinchao Wang](https://sites.google.com/site/sitexinchaowang/). I received my Ph.D. degree from Beijing University of Posts and Telecommunications (BUPT), where I was supervised by Prof. [Chuan Shi](http://shichuan.org/). I also collaborate with Prof. [Xiao Wang](https://wangxiaocs.github.io/) at Beihang University.

<i class="fas fa-bullhorn ic-amber"></i> News
====

<!-- News lives in _data/news.yml. Only the newest `limit` entries render. -->
{% include news-list.html items=site.data.news limit=4 %}

<i class="fas fa-microscope ic-violet"></i> Research Summary ([More](https://bdy9527.github.io/publications/))
====
My current research primarily focuses on **Deep Spectral Learning**.

I am interested in developing spectral tools or models with principled mathematics. Below are some representative topics and works.

- Spectral Analysis of Data: [Unified Dataset Distillation](https://arxiv.org/abs/2503.01212) (ICLR 2026), [Spectral Graph Distillation](https://arxiv.org/abs/2310.09202) (ICML 2024)

- Spectral Graph Neural Networks: [Full-spectrum GNN](https://arxiv.org/abs/2605.05759) (ICML 2026), [Specformer](https://arxiv.org/abs/2303.01028) (ICLR 2023), [Frequency-adaptive GCN](https://arxiv.org/abs/2101.00797) (AAAI 2021)

I also have some preliminary ideas in other areas. Feel free to email me if you are interested.

- Spectral Analysis of Model, e.g., Parameter-Efficient Fine-Tuning (PEFT), Model Merging

- Spectral Optimization, e.g., Muon

- Spectrum-based Applications, e.g., AI for Science

<i class="fas fa-gavel ic-teal"></i> Academic Service
====
- **Journal Reviewer**: IEEE TPAMI &nbsp;/&nbsp; TSP &nbsp;/&nbsp; TIP &nbsp;/&nbsp; TKDE &nbsp;
- **Conference Area Chair**: NeurIPS
- **Conference Reviewer**: NeurIPS, ICLR, ICML

<i class="fas fa-user-graduate ic-green"></i> Supervised Students
====

<!-- Students live in _data/students.yml -- edit that file, not this one. -->

{% include student-list.html items=site.data.students %}
