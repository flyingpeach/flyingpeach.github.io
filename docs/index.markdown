---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>body {text-align: justify}</style>

**This website is currently under construction.**

![](/assets/profile_picture.jpeg){:align="left" width="225"}

I'm an incoming Assistant Professor of Electrical Engineering and Computer Science at the University of Michigan, starting in Fall 2023. I work on distributed control theory with applications to neuroscience, biology, and engineering systems. I received a BASc in Engineering Science from the University of Toronto in 2018, and am currently wrapping up my PhD in Control + Dynamical Systems at Caltech. Outside of work, I enjoy playing, composing, producing, and listening to music. I’ve also had the joy of working as a private piano and vocal music instructor for children and adults.

[[CV](/assets/jsli_cv_jun21.pdf){:target="_blank"}] [[Google Scholar](https://scholar.google.com/citations?user=4EQuvGEAAAAJ){:target="_blank"}] [[GitHub](https://github.com/flyingpeach){:target="_blank"}] [[LinkedIn](https://www.linkedin.com/in/jslisali/){:target="_blank"}]

Open access to research is important to me. I endeavor to make some version of all my papers available on [arXiV](https://arxiv.org/){:target="_blank"} and [biorXiV](https://www.biorxiv.org/){:target="_blank"}.

**For prospective students (master's and PhD):** if you are interested in working with me, send me an email with your resume and a short description of your research interests. Students should have experience or coursework in control theory or related fields. Background in neuroscience and biology is welcome, but not required -- curiosity and willingness to learn are all I require on these fronts. I can be reached at jsli at caltech dot edu. More information on my mentorship style can be found [here](./mentoring.html){:target="_blank"}.


## **Research overview**

In engineering, control theory plays a crucial role in the design and analysis of robust and efficient systems -- including robots, spacecraft, and power grids. In neuroscience, control theory underlies models of motor and sensorimotor function. Control theory also has applications as a modeling tool for various biological processes, such as metabolic dynamics. I am interested in control-theoretic analysis of biological systems, which yields novel scientific explanations as well as valuable design insights, which can be applied to engineering systems.

The three foundational directions of my research are: 

<span style="color:#4ECA21;">**(1)**</span> develop theory for the design and implementation of controllers under various energy and signaling constraints 

<span style="color:#FF477E;">**(2)**</span> apply theory to develop novel models and insights for living systems, and 

<span style="color:#CE47FF;">**(3)**</span> apply theory to create scalable, robust, efficient algorithms and architectures.

<p align="center">
<img width="550" src="/assets/research_overview.png">
</p>

I am particularly interested in how biology co-designs and implements controllers using organic components, which face unique challenges compared to their electronic counterparts.

The marriage of control theory and biology is far from new, but it is an unfamiliar union to many engineers and scientists. For engineers and control theorists who wonder why one might choose biology as a main application, I offer up [the following explanation](./why_biology.html){:target="_blank"}. Conversely, for neuroscientists and biologists who are curious about controls, I elaborate on some unique benefits of control theory as a modeling tool [here](./why_controls.html){:target="_blank"}. These snippets are adapted from my PhD thesis.

## **Distributed control**

My theoretical research focuses on distributed, scalable control algorithms. These algorithms accommodate communication constraints, and enjoy complexity that scales independently of network size under mild assumptions. This is important for large-scale systems, for which centralized controllers can be intractable. I often use the system level synthesis framework in my research -- I write and maintain toolboxes in [MATLAB](https://github.com/flyingpeach/sls-code/tree/master/matlab){:target="_blank"} and [Python](https://github.com/shih-hao-tseng/SLSpy){:target="_blank"} for this framework. Representative works include scalable [structured robust control](https://arxiv.org/abs/2204.02493){:target="_blank"}, model predictive control ([1](https://arxiv.org/abs/2110.07010){:target="_blank"}, [2](https://arxiv.org/abs/2203.00780){:target="_blank"}, [3](https://arxiv.org/abs/2303.11264)), and [closed-loop and controller specifications for distributed algorithms](https://arxiv.org/abs/2006.05040){:target="_blank"}. These works may also be applied to models of neuroscience and biology, in which distributed operation and communication constraints play a key role.

<p align="center">
<img width="650" src="/assets/distributed_control.png">
</p>

## **Recent work in neuroscience**

*Internal feedback in sensorimotor systems*

The standard model of sensorimotor processing involves signal flows from sensory inputs to sensory areas, then from sensory areas to motor areas. However, massive amounts of signal flow in the opposite direction (i.e. from motor areas back toward sensory areas) are observed in the cortex; we refer to these signals as internal feedback. What function does internal feedback serve, and why does the brain contain so much of it? We answer these questions using control theory. In this set of three papers geared toward control audiences, we [outline the presence of internal feedback](https://arxiv.org/abs/2110.05029){:target="_blank"} across a variety of organ systems and organisms, and apply both [standard control theory](https://arxiv.org/abs/2109.11752){:target="_blank"} and [distributed control theory](https://arxiv.org/abs/2109.11757){:target="_blank"} to analyze internal feedback. In particular, we argue that the incorporation of local communication and localized behavior necessitates large amounts of internal feedback. We also explore additional connections to existing physiological and experimental data in [this preprint](https://arxiv.org/abs/2211.05922){:target="_blank"} geared toward a neuroscience/general audience. This work offers the first explanation for the large quantities of internal feedback observed in the cortex. Local and distributed processing also feature heavily in the analysis of chemical reaction networks, which is the subject of ongoing work.