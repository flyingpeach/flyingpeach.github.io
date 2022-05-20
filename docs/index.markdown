---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>body {text-align: justify}</style>

![](/assets/profile_picture.jpeg){:align="left" width="225"}

I'm a 4th year PhD candidate in Control + Dynamics Systems at Caltech, advised by Professor John C. Doyle. I work on distributed control theory with applications to cyberphysical systems and biology models; my research is partially supported by an NSERC PGSD. I received a B.A.Sc. from the University of Toronto in 2018.

[CV](/assets/cv.pdf){:target="_blank"} / [Google Scholar](https://scholar.google.com/citations?user=4EQuvGEAAAAJ){:target="_blank"} / [ResearchGate](https://www.researchgate.net/profile/Jing-Shuang-Li){:target="_blank"}

Contact me at jsli [at] caltech [dot] edu

---

### **Research Overview**
My work is motivated by diverse applications from two complementary perspectives:

1. The *engineering* perspective, in which we wish to *design* cyberphysical systems that perform optimally, efficiently, robustly, etc.
2. The *biological* perspective, in which we wish to *decipher* how organisms are able to perform optimally, efficiently, robustly, etc.

These perspectives are symbiotic; biology inspires novel techniques in engineering, and engineering tools form the basis for many models of biological systems. I work on broad theoretical problems motivated by both perspectives, and also collaborate with engineers and biologists to produce and apply theory with with varying levels of application specificity.

My core expertise is in *control theory*, which concerns the analysis and operation of dynamical systems. Control theory is used to design aircraft, power grids, robots, and other cyberphysical systems. In biology, control theory underlies state-of-the-art motor and sensorimotor models, and can also be used to analyze cellular systems.

<p align="center">
 <img width="600" src="/assets/engineering_and_bio.jpeg">
</p>

### **Distributed Control Theory**
My theoretical research focuses on distributed, local, and scalable control algorithms. Such algorithms are crucial to the control of cyberphysical systems such as the power grid, which faces expansions and challenges as we incorporate more and more renewable energy sources. 

<p align="center">
 <img width="600" src="/assets/centralized_vs_distributed.jpeg">
</p>

I have worked on scalable structured robust control [[paper](https://arxiv.org/abs/2204.02493){:target="_blank"}], model predictive control [[paper1](https://arxiv.org/abs/2110.07010){:target="_blank"}, [paper2](https://arxiv.org/abs/2203.00780){:target="_blank"}, [paper3](https://arxiv.org/abs/2010.01292){:target="_blank"}], and nonlinear control [[paper](https://arxiv.org/abs/2205.02187){:target="_blank"}]. In older work [[paper](https://arxiv.org/abs/2006.05040){:target="_blank"}], I describe how to selectively enforce key structural and behavioral constraints via distributed algorithms. I also wrote and maintain toolboxes in MATLAB and Python [[code](https://github.com/sls-caltech/sls-code){:target="_blank"}, [paper](https://arxiv.org/abs/2004.12565){:target="_blank"}] for System Level Synthesis, an emerging technique for distributed control.