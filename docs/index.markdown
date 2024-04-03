---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>
body {text-align: justify}
.my-image {margin-right: 20px}
</style>

<center>
<a href="./index.html">Home</a> | <a href="./team.html">Research Team</a> | <a href="./prospectives.html">Prospective Students</a> | <a href="./mentoring.html">Mentoring Style</a> | <a href="./miscellany.html">Miscellany</a>
</center>
<br>

<img class="my-image" src="/assets/profile_picture.jpeg" align="left" width="180">

I'm an Assistant Professor of Electrical Engineering and Computer Science at the University of Michigan. I am also affiliated with the Michigan Neuroscience Institute. My research focuses on distributed and resource-constrained control theory with applications to biology and engineering systems. I received a BASc in Engineering Science from the University of Toronto in 2018, and a PhD in Control + Dynamical Systems from Caltech in 2023. My pronouns are *she/her/hers*.

<center>
<a href="/assets/jsli_cv_feb03.pdf" target="_blank">CV</a> | <a href="https://scholar.google.com/citations?user=4EQuvGEAAAAJ" target="_blank">Google Scholar</a> | <a href="https://github.com/flyingpeach" target="_blank">GitHub</a> | <a href="https://www.linkedin.com/in/jslisali/" target="_blank">LinkedIn</a>
</center>

<br>
## **Research overview**

In engineering, control theory plays a crucial role in the design and analysis of robust and efficient systems --- including robots, spacecraft, and power grids. In neuroscience, control theory underlies models of motor and sensorimotor function. Control theory also has applications as a modeling tool for various biological processes, such as metabolic dynamics. I am interested in control-theoretic analysis of biological systems, which yields novel scientific explanations as well as valuable design insights, which can be applied to engineering systems.

The three foundational directions of my research are: 

<span style="color:#4ECA21;">**(1)**</span> develop theory for the design and implementation of controllers under various energy and signaling constraints 

<span style="color:#FF477E;">**(2)**</span> apply theory to develop novel models and insights for biological systems, and 

<span style="color:#CE47FF;">**(3)**</span> apply theory to create scalable, robust, efficient algorithms and architectures.

<p align="center">
<img width="550" src="/assets/research_overview.png">
</p>

The marriage of control theory and biology is far from new, but it is an unfamiliar union to many engineers and scientists. If you want to better understand the motivation behind the integration of these disciplines, read these:

For engineers and control theorists: [why biology?](./why_biology.html){:target="_blank"}

For biologists and neuroscientists: [why control theory?](./why_controls.html){:target="_blank"}

<br>
## **Distributed control**

My theoretical research focuses on distributed, scalable control algorithms. These algorithms accommodate communication constraints, and enjoy complexity that scales independently of network size under mild assumptions. This is important for large-scale systems, for which centralized controllers can be intractable. I often use the [system level synthesis](https://www.sciencedirect.com/science/article/pii/S1367578819300215){:target="_blank"} framework in my research --- I write and maintain toolboxes in [MATLAB](https://github.com/flyingpeach/sls-code/tree/master/matlab){:target="_blank"} and [Python](https://github.com/shih-hao-tseng/SLSpy){:target="_blank"} for this framework. Representative works include scalable [structured robust control](https://ieeexplore.ieee.org/abstract/document/9992622){:target="_blank"}, model predictive control ([1](https://ieeexplore.ieee.org/abstract/document/9939038){:target="_blank"}, [2](https://ieeexplore.ieee.org/abstract/document/10083211){:target="_blank"}, [3](https://ieeexplore.ieee.org/document/10229197)), and [closed-loop and controller specifications for distributed algorithms](https://ieeexplore.ieee.org/abstract/document/9147736){:target="_blank"}. These works may also be applied to models of neuroscience and biology, in which distributed operation and communication constraints play a key role.

<p align="center">
<img width="650" src="/assets/distributed_control.png">
</p>

<br>
## **Neuroscience and biology**

*Internal feedback in sensorimotor systems*

The standard model of sensorimotor processing involves signal flows from sensory inputs to sensory areas, then from sensory areas to motor areas. However, massive amounts of signal flow in the opposite direction (i.e. from motor areas back toward sensory areas) are observed in the cortex; we refer to these signals as internal feedback. What function does internal feedback serve, and why does the brain contain so much of it? We answer these questions using control theory. In this set of three papers geared toward control audiences, we [outline the presence of internal feedback](https://ieeexplore.ieee.org/abstract/document/9867859){:target="_blank"} across a variety of organ systems and organisms, and apply both [standard control theory](https://ieeexplore.ieee.org/abstract/document/9867794){:target="_blank"} and [distributed control theory](https://ieeexplore.ieee.org/abstract/document/9867769){:target="_blank"} to analyze internal feedback. In particular, we argue that the incorporation of local communication and localized behavior necessitates large amounts of internal feedback. We also explore additional connections to existing physiological and experimental data in [this paper](https://www.pnas.org/doi/abs/10.1073/pnas.2300445120){:target="_blank"} geared toward a general scientific audience. This work offers the first explanation for the large quantities of internal feedback observed in the cortex. Local and distributed processing also feature heavily in the analysis of chemical reaction networks, which is the subject of ongoing work.