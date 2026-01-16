---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Education
======
* Ph.D in Computer Science, Zhejiang University, 2022-present (expected 2026)
* B.S. in Computer Science, Zhejiang University, 2018-2022

Research Interests
======
* Multi-focus Image Fusion
* Deep Learning (CNNs, Transformers, State Space Models)
* Microscopic Image Processing
* Computer Vision

Skills
======
* **Programming**: Python, C++, MATLAB
* **Deep Learning**: PyTorch, TensorFlow
* **Computer Vision**: OpenCV, PIL, scikit-image
* **Tools**: Git, Docker, Linux

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Featured Projects
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
