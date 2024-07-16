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

<img class="my-image" src="/assets/profile_picture.jpeg" align="left" width="160">

I'm an Assistant Professor of Electrical Engineering and Computer Science at the University of Michigan. I am also affiliated with the Michigan Neuroscience Institute. I received a BASc in Engineering Science from the University of Toronto in 2018, and a PhD in Control + Dynamical Systems from Caltech in 2023. My research interests include optimal control, distributed control, resource- and communication-constrained control, sensorimotor neuroscience, and large-scale systems. My pronouns are *she/her/hers*.

<center>
<a href="/assets/jsli_cv_apr29.pdf" target="_blank">CV</a> | <a href="https://scholar.google.com/citations?user=4EQuvGEAAAAJ" target="_blank">Google Scholar</a> | <a href="https://github.com/flyingpeach" target="_blank">GitHub</a> | <a href="https://www.linkedin.com/in/jslisali/" target="_blank">LinkedIn</a>
</center>

## **Research overview**

My current research interests involve two foundational directions. First, I am interested in developing theory and algorithms for controller design under resource and communication constraints. Second, I am interested in applying said theory to produce novel models of biological sensorimotor systems. I currently use methods from linear optimal and distributed control, though I am also interested in the influence of learning, adaptation, and nonlinearity on controller structure.

### **Constrained controller design and implementation**
Large-scale (e.g. power grids, transport networks) and resource/energy-constrained (e.g. field robots, wearable devices) systems abound in both engineering and biology (see next section for more discussion on biology). These systems impart additional requirements for controller design, such as communication limitations between different subsystems within a controller --- I am interested in developing theory and algorithms that address these requirements. I often use the [system level synthesis](https://www.sciencedirect.com/science/article/pii/S1367578819300215){:target="_blank"} framework in my research --- I write and maintain toolboxes in [MATLAB](https://github.com/flyingpeach/sls-code/tree/master/matlab){:target="_blank"} and [Python](https://github.com/shih-hao-tseng/SLSpy){:target="_blank"} for this framework. Relevant works include [scalable robust control](https://ieeexplore.ieee.org/abstract/document/9992622){:target="_blank"}, scalable model predictive control ([1](https://ieeexplore.ieee.org/abstract/document/9939038){:target="_blank"}, [2](https://ieeexplore.ieee.org/abstract/document/10083211){:target="_blank"}, [3](https://ieeexplore.ieee.org/document/10229197)), and control with [minimal sensor-to-actuator communication](https://ieeexplore.ieee.org/abstract/document/10336872){:target="_blank"}.


### **Biological sensorimotor systems**
Control theory underlies models of motor and sensorimotor behavior. More concretely: control theory tools (e.g. proportional-integral-derivative, linear quadratic regulator) have been used to model behavioral quantities (e.g. limb trajectories, limb forces) under a variety of contexts (e.g. flying, balancing, reaching) for a variety of species (e.g. humans, fruit flies, salamanders). Controls-based models offer two key benefits. Firstly, controls-based models can be formulated as prior models --- that is, they predict experimental outcomes before the experiment is conducted. This is complementary to data-driven models, which rely on post-experiment analysis. Prior models can identify potentially interesting future experiments; this is particularly important as the space of available experiments grows exponentially with the advancement of experimental techniques. Additionally, control theory creates human-interpretable models from human-interpretable inputs (e.g. system, objective, and constraints), which can reveal fundamental principles that govern complex systems.

An important open question at the intersection of control theory and sensorimotor neuroscience is that of controller *implementation*. Since animals' sensorimotor behaviors (i.e. input-output characteristics) can be modelled by a controller, their nervous system must be implementing something like a controller. But how is this controller implemented by the propioceptors, neurons, and muscles of the nervous system? These organic components are uniquely limited in terms of energy, speed, precision, and communication in comparison to engineered components (e.g. transistors) --- control theory (which primarily focuses on engineering applications) does not currently have the answers to this question, and I am interested in providing answers through the development of new theory.

My most recent work uses [delay-compensated controllers](https://ieeexplore.ieee.org/abstract/document/9867794){:target="_blank"} to model [sensorimotor delays in fruit fly walking](https://www.biorxiv.org/content/10.1101/2024.04.18.589965v1){:target="_blank"}. Previously, I was interested in the phenomenon of *internal feedback* (also known as descending feedback to visual neuroscientists), which are brain signals that flow from motor areas back toward sensory areas. We explored the role of internal feedback in optimal and distributed controller structures ([1](https://ieeexplore.ieee.org/abstract/document/9867794){:target="_blank"} , [2](https://ieeexplore.ieee.org/abstract/document/9867769){:target="_blank"}), and described connections to known circuits in the brain ([1](https://ieeexplore.ieee.org/abstract/document/9867859){:target="_blank"}, [2](https://www.pnas.org/doi/abs/10.1073/pnas.2300445120){:target="_blank"}).

While sensorimotor neuroscience is my main area of interest, I am also interested in other branches of biology which are amenable to dynamical systems methods, such as [large-scale chemical reaction networks](https://ieeexplore.ieee.org/abstract/document/10156281){:target="_blank"}.
