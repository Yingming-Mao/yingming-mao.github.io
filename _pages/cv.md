---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* **Ph.D. in Control Science and Engineering**, Xi'an Jiaotong University & Shanghai Institute of Intelligent Science and Technology, 2022 – Present
* **B.E. in Automation**, Xi'an Jiaotong University, 2018 – 2022

Work Experience
======

* **Huawei Technologies**, Terminal Device Memory Optimization Intern, 2024.07 – 2024.09
  * Optimized memory parameters for 16G RAM devices using white-box proxy models for parameter space search.
  * Improved performance testing frameworks to support memory trace capture and latency analysis.

* **Meituan**, Grid Warehouse Routing Optimization Intern (Meituan Youxuan), 2024.05 – 2024.07
  * Developed a routing optimization algorithm using greedy clustering, reducing vehicle requirements by over 10%.

* **Huawei Technologies**, OpenHarmony Development Intern, 2023.07 – 2023.09
  * Participated in OpenHarmony driver interface development and debugging.

Research Projects & Collaborations
======

* **DCN Topology & Traffic Engineering (Huawei Collaboration)** 2024.11 – 2025.03
  * Designed the **ASDO** (Alternating Source-Destination Optimization) algorithm for fast routing in large-scale DCNs.
  * Achieved 60%+ reduction in MLU compared to non-deep learning methods while maintaining significant speed advantages.

* **AI Training GPU Mapping (Huawei Collaboration)** 2024.09 – 2025.03
  * Proposed a greedy clustering and integer programming method for collision-free mapping of logical and physical GPUs in Large Model training.
  * Reduced computation time by over 95%, awarded as **Huawei Excellent School-Enterprise Cooperation Project**.

* **Backbone Network Traffic Scheduling (Huawei Collaboration)** 2023.05 – 2024.06
  * Developed a fast orchestration algorithm for backbone networks with 10,000+ service flows.
  * Achieved 98% orchestration rate and improved load balancing by 15% using Lagrangian relaxation.
  
Skills
======

* **Research Domains**
  * AI Infrastructure (AI Infra)
  * Data Center Networks (DCN): Traffic Engineering, Topology Engineering
  * Power Systems: Microgrid Scheduling, Linear Power Flow Modeling
* **Programming & Tools**
  * Languages: Python, C++, MATLAB
  * Tools: Git, LaTeX, PyTorch
* **Languages**
  * English (Professional working proficiency)
  * Chinese (Native)

Honors & Awards
======

* **Huawei Scholarship**, 2025
* **Best Oral Presentation Award**, 5th International Conference on Frontiers of Energy and Environment Engineering (CFEEE), 2022
* **Outstanding Undergraduate Graduation Thesis**, Shaanxi Province, 2022

Publications
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======

* Currently signed in to 43 different slack teams
