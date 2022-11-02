---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>body {text-align: justify}</style>

![](/assets/profile_picture.jpeg){:align="left" width="225"}

I'm a PhD candidate in Control + Dynamics Systems at Caltech, advised by John Doyle. I work on distributed control theory with applications to engineering systems and biology models; my research is partially supported by an [NSERC PGSD](https://www.nserc-crsng.gc.ca/Students-Etudiants/PG-CS/BellandPostgrad-BelletSuperieures_eng.asp){:target="_blank"}. I received a B.A.Sc. in Engineering Science from the University of Toronto in 2018. Outside of work, I enjoy playing, composing, producing, and listening to music; reading, creative writing, and staying active. I've also had the joy of working as a private piano and vocal music instructor for children and adults.

[[CV](/assets/jsli_cv_nov02.pdf){:target="_blank"}] [[Google Scholar](https://scholar.google.com/citations?user=4EQuvGEAAAAJ){:target="_blank"}] [[Personal GitHub](https://github.com/flyingpeach){:target="_blank"}] [[SLS Toolboxes](https://github.com/sls-caltech/){:target="_blank"}] [[LinkedIn](https://www.linkedin.com/in/jslisali/){:target="_blank"}] 

Email: jsli at caltech dot edu

I'm on the job market! [[Research Statement](/assets/jsli_research_statement_nov02.pdf){:target="_blank"}] [[Teaching Statement](/assets/jsli_teaching_statement_nov01.pdf){:target="_blank"}] [[DEI Statement](/assets/jsli_dei_statement_nov01.pdf){:target="_blank"}]

[Research Overview](#research-overview) | [Distributed Control](#distributed-control) | [Control Theory for Biology](#control-theory-for-biology) 

### **Research Overview**
In engineering, control theory plays a crucial role in the design and analysis of robust and efficient systems – including robots, spacecraft, and power grids. In biology, control theory underlies sensorimotor models of organisms, and also has applications as a modeling tool for immune systems and metabolic networks. As an engineer and control theorist, I am interested in the analysis of biological systems, both for its standalone value and for the insights biology can provide for engineers and theorists. The three foundational directions of my research are:
<span style="color:#4ECA21;">**(1)**</span> develop theory for the design, control, and analysis of complex architectures, <span style="color:#FF477E;">**(2)**</span> apply theory to develop models and provide insights for living systems, and <span style="color:#CE47FF;">**(3)**</span> apply theory to create scalable, robust, efficient algorithms and architectures.

<p align="center">
 <img width="700" src="/assets/diagram_research_directions.png">
</p>

### **Distributed Control**
My theoretical research focuses on distributed, scalable control algorithms. These algorithms enjoy complexity that scales independently of network size, under mild assumptions.  This is important for large-scale systems, for which centralized controllers can be intractable. I often use the System Level Synthesis (SLS) framework in my research -- I write and maintain toolboxes in [MATLAB](https://github.com/sls-caltech/sls-code/tree/master/matlab){:target="_blank"} and [Python](https://github.com/shih-hao-tseng/SLSpy){:target="_blank"} for SLS. Representative works include scalable [structured robust control](https://arxiv.org/abs/2204.02493){:target="_blank"}, model predictive control [[paper1](https://arxiv.org/abs/2110.07010){:target="_blank"}, [paper2](https://arxiv.org/abs/2203.00780){:target="_blank"}], and [closed-loop and controller specifications for distributed algorithms](https://arxiv.org/abs/2006.05040){:target="_blank"}. 

<p align="center">
 <img width="600" src="/assets/diagram_distributed_ctrl.png">
</p>

### **Control Theory for Biology** 
From sensorimotor behavior to chemical reaction networks, many biological phenomena exhibit dynamics and can be modeled and analyzed using tools from control theory. The application of control theory provides insights on physiology and behavior, and suggests avenues of experimental investigation. An eventual aim of this research direction is to create models that have diagnostic and therapeutic impact – for instance, sensorimotor models that inform therapeutic directions for degenerative diseases.

Insights from biological systems can also inspire new techniques for the design of cyberphysical systems. Organisms are composed of billions of cells which coordinate to attain high performance in a variety of tasks (e.g. infection resistance, predator evasion); they perform these tasks with a level of efficiency and robustness that is unattainable by state-of-the-art cyberphysical systems. A better understanding of the mechanisms by which organisms achieve such high performance, efficiency, and robustness will shed light on how engineers can design improved cyberphysical systems.

<p align="center">
 <img width="400" src="/assets/diagram_ctrl_for_bio.png">
</p>

#### **Internal feedback in sensorimotor systems**
The standard model of sensorimotor processing involves signal flows from sensory inputs to sensory areas, then from sensory areas to motor areas. However, massive amounts of signal flow in the opposite direction (i.e. from motor areas back toward sensory areas) are observed in the cortex; we refer to these signals as internal feedback. What function does internal feedback serve, and why does the brain contain so much of it? We answer these questions using control theory; we [outline the presence of internal feedback](https://arxiv.org/abs/2110.05029
){:target="_blank"} across a variety of organ systems and organisms , and apply both [standard control theory](https://arxiv.org/abs/2109.11752
){:target="_blank"} and [distributed control theory](https://arxiv.org/abs/2109.11757
){:target="_blank"} to analyze internal feedback. In particular, we argue that the incorporation of local communication and localized behavior necessitates large amounts of internal feedback. This work offers the first explanation for the large quantities of internal feedback observed in the cortex. Local and distributed processing also feature heavily in the analysis of chemical reaction networks, which is the subject of ongoing work.


