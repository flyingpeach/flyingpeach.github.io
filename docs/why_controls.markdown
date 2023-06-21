---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<style>body {text-align: justify}</style>

### **Benefits of applying control theory to biology**
#### *(for biologists)*

I start with an obvious caveat: control theory is not applicable to the entirety of biology. However, it is a cornerstone of models in the area of sensorimotor neuroscience. Adjacent fields, such as motor control and locomotion, naturally also benefit from control theory. For biologists working in more distant areas, a general guideline is that if the biological entities of interest can be described with differential equations, then applying concepts from dynamical systems and control theory may provide additional insights and models.

Control theory is fundamentally concerned with **optimization**: given some dynamical system, objective, and constraints, what is the best behavior possible, and how is this behavior obtained? This is a natural way of looking at biological systems, which are optimized for various survival-critical tasks through evolution. Interpreting biology from this perspective offers two key benefits: prior modeling and human-interpretable models. Firstly, control-based models can be formulated as **prior** models -- that is, they can predict experimental outcomes before the experiment is conducted. This is complementary to data-driven models, which provide insights via analysis only after experiments have been performed. Prior models can identify potentially interesting future experiments; this is particularly important as the space of available experiments grows exponentially with the advancement of experimental techniques. Additionally, control theory creates human-interpretable models from human-interpretable inputs (i.e. system, objective, and constraints), which can reveal fundamental principles that govern complex systems.

In the domain of sensorimotor neuroscience, control theory also provides the mathematical tools needed to translate longstanding qualitative ideas on closed-loop sensing and action into quantitative models. These ideas are concerned with the analysis of sensory areas (e.g. vision) not as standalone modules, but as part of the larger sensorimotor feedback loop. The general underlying principle is that all neural processes serve motor output; sensory processing is only useful insofar as it produces appropriate actions. While analysis of solitary modules such as vision are dominated (and rightfully so) by other mathematical approaches, the analysis of the full loop necessitates the use of control theory, which is fundamentally concerned with the closed-loop relationship between sensing, action, and environment. Unique insights can come of looking at the brain from this closed-loop perspective as opposed to individual modules, as shown in recent work ([1](https://arxiv.org/abs/2109.11757){:target="_blank"}, [2](https://arxiv.org/abs/2211.05922){:target="_blank"}).