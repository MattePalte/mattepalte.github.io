---
layout: category
title: Research Projects
---

<h3>Peer-Reviewed Publications</h3>

<b>Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code</b><br>
In <a href="https://conf.researchr.org/track/ase-2021/ase-2021-papers">Research Papers of IEEE/ACM International Conference on Automated Software Engineering</a> (ASE ’21).<br>
Neural models of code are successfully tackling various prediction tasks, complementing and sometimes even outperforming traditional program analysis. While most work focuses on end-to-end evaluations of such models, it often remains unclear what the models actually learn, and to what extent their reasoning about code matches that of skilled humans. A poor understanding of the model reasoning risks deploying models that are right for the wrong reason, and taking decisions based on spurious correlations in the training dataset. This paper investigates to what extent the attention weights of effective neural models match the reasoning of skilled humans. To this end, we present a methodology for recording human attention and use it to gather 1,508 human attention maps from 91 participants, which is the largest such dataset we are aware of. Computing human-model correlations shows that the copy attention of neural models often matches the way humans reason about code (Spearman rank coefficients of 0.49 and 0.47), which gives an empirical justification for the intuition behind copy attention. In contrast, the regular attention of models is mostly uncorrelated to human attention. We find that models and humans sometimes focus on different kinds of tokens, e.g., strings are important to humans but mostly ignored by models. The results also show that human-model agreement positively correlates with accurate predictions by a model, which calls for neural models that even more closely mimic human reasoning. Beyond the insights from our study, we envision the release of our dataset of human attention maps to help understand future neural models of code and to foster work on human-inspired models.<br>
[<a href="https://software-lab.org/publications/ase2021.pdf">paper</a>]
[<a href="https://github.com/MattePalte/thinking-like-a-developer">dataset and code</a>]
