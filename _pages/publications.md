---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?hl=en&user=E_lDZdQAAAAJ}}">my Google Scholar profile</a>.</div>
{% endif %}

### 2024

* __Leveraging Machine Learning for Quantum Compilation Optimization.__ <br>
__Xiangyu Ren__, Tianyu Zhang, Xiong Xu, Yi-Cong Zheng, Shengyu Zhang. <br>
Accepted to 61st IEEE/ACM Design Automation Conference (DAC 2024).

* __A Hardware-Aware Gate Cutting Framework for Practical Quantum Circuit Knitting.__ <br>
__Xiangyu Ren__, Mengyu Zhang, Antonio Barbalace. <br>
Accepted to 2024 ACM/IEEE International Conference on Computer-Aided Design (ICCAD 2024).

* __A Scalable, Fast and Programmable Neural Decoder for Fault-Tolerant Quantum Computation Using Surface Codes__ <br>
Mengyu Zhang^, __Xiangyu Ren^__, Guanglei Xi, Zhenxing Zhang, Qiaonian Yu, Fuming Liu, Hualiang Zhang, Shengyu Zhang, Yi-Cong Zheng. <br>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
