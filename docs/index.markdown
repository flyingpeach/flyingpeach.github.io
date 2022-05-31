---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>body {text-align: justify}</style>

![](/assets/profile_picture.jpeg){:align="left" width="225"}

I'm a PhD candidate in Control + Dynamics Systems at Caltech, advised by Professor John C. Doyle. I work on distributed control theory with applications to cyberphysical systems and biology models; my research is partially supported by an NSERC PGSD. I received a B.A.Sc. from the University of Toronto in 2018. Outside of work, I enjoy playing, composing, producing, and listening to music; reading, creative writing, and staying active. I've also had the joy of working as a private piano and vocal music instructor for children and adults.

[[CV](/assets/cv_may302022.pdf){:target="_blank"}] [[Google Scholar](https://scholar.google.com/citations?user=4EQuvGEAAAAJ){:target="_blank"}] [[General GitHub](https://github.com/flyingpeach){:target="_blank"}] [[SLS GitHub](https://github.com/sls-caltech/){:target="_blank"}] [[LinkedIn](https://www.linkedin.com/in/jslisali/){:target="_blank"}] 

Email: jsli at caltech dot edu

I'm on the job market! Feel free to reach out if you think I would be a good fit for your department.

[Research Overview](#research-overview) | [Distributed Control Theory](#distributed-control-theory) | [Control Theory for Biology](#control-theory-for-biology) 

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
 <img width="600" src="/assets/centralized_vs_distributed_v2.jpeg">
</p>

I have worked on scalable structured robust control [[paper](https://arxiv.org/abs/2204.02493){:target="_blank"}], model predictive control [[paper1](https://arxiv.org/abs/2110.07010){:target="_blank"}, [paper2](https://arxiv.org/abs/2203.00780){:target="_blank"}, [paper3](https://arxiv.org/abs/2010.01292){:target="_blank"}], and nonlinear control [[paper](https://arxiv.org/abs/2205.02187){:target="_blank"}]. In older work [[paper](https://arxiv.org/abs/2006.05040){:target="_blank"}], I describe how to selectively enforce key structural and behavioral constraints via distributed algorithms. I also wrote and maintain toolboxes in MATLAB and Python [[code](https://github.com/sls-caltech/sls-code){:target="_blank"}, [paper](https://arxiv.org/abs/2004.12565){:target="_blank"}] for System Level Synthesis, an emerging technique for distributed control.

### **Control Theory for Biology** 

From sensorimotor behavior to chemical reaction networks, many biological phenomena exhibit dynamics and can be modeled and analyzed using tools from control theory. The application of control theory provides insight on fundamental functions and behaviors of biological systems, suggests further avenues of experimental investigation, and complements existing data and data-driven methods.

Insights from biological systems can also inspire new techniques for the design of cyberphysical systems. Organisms contain billions of neurons and cells which coordinate to attain high performance in a variety of survival-critical tasks (e.g. resisting infections, evading predators); they perform these tasks with a level of efficiency and robustness that is unattainable by state-of-the-art engineered systems. 

<p align="center">
 <img width="400" src="/assets/ctrl_for_bio.jpeg">
</p>

A well-documented but poorly understood phenomenon in biological systems is the prevalence of internal feedback, i.e. signal pathways that traverse the opposite direction as conventional pathways. For instance, conventional visual processing conveys signals from the eye toward the brain, while internal feedback in the visual system conveys signals from the brain toward the eye. In recent work, we outline the presence of internal feedback across a variety of organ systems and organisms [[paper](https://arxiv.org/abs/2110.05029
){:target="_blank"}], and apply both standard control theory [[paper](https://arxiv.org/abs/2109.11752
){:target="_blank"}] and distributed control theory [[paper](https://arxiv.org/abs/2109.11757
){:target="_blank"}] to explain the functionality and necessary abundance of internal feedback in systems with local and distributed processing. Local and distributed processing also feature heavily in the analysis of chemical reaction networks, which is the subject of ongoing work [[poster](/assets/buildacell_poster.pdf){:target="_blank"}].



