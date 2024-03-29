---
layout: category
title: Research Projects
---

<h3>MorphQ: Metamorphic Testing of the Qiskit Quantum Computing Platform</h3><br>
In <a href="https://conf.researchr.org/track/icse-2023/icse-2023-technical-track">Research Papers of IEEE/ACM International Conference on Software Engineering</a> (ICSE ’23).<br>
As quantum computing is becoming increasingly popular, the underlying quantum computing platforms are growing both in ability and complexity. Unfortunately, testing these platforms is challenging due to the relatively small number of existing quantum programs and because of the oracle problem, i.e., a lack of specifications of the expected behavior of programs. This paper presents MorphQ, the first metamorphic testing approach for quantum computing platforms. Our two key contributions are (i) a program generator that creates a large and diverse set of valid (i.e., non-crashing) quantum programs, and (ii) a set of program transformations that exploit quantum-specific metamorphic relationships to alleviate the oracle problem. Evaluating the approach by testing the popular Qiskit platform shows that the approach creates over 8k program pairs within two days, many of which expose crashes. Inspecting the crashes, we find 13 bugs, nine of which have already been confirmed. MorphQ widens the slim portfolio of testing techniques of quantum computing platforms, helping to create a reliable software stack for this increasingly important field.<br>
[<a href="https://arxiv.org/abs/2206.01111">paper</a>]
[<a href="https://github.com/sola-st/MorphQ-Quantum-Qiskit-Testing-ICSE-23/">dataset and code</a>]
![MorphQ Overview](/assets/images/teaser_morphq.png)


<h3>Bugs in Quantum Computing Platforms: An Empirical Study</h3><br>
In <a href="https://2022.splashcon.org/track/splash-2022-oopsla">Research Papers of ACM Conference on Object Oriented Programming Systems Languages and Applications</a> (OOPSLA ’22).<br>
The interest in quantum computing is growing, and with it, the importance of software platforms to develop quantum programs. Ensuring the correctness of such platforms is important, and it requires a thorough understanding of the bugs they typically suffer from. To address this need, this paper presents the first in-depth study of bugs in quantum computing platforms. We gather and inspect a set of 223 real-world bugs from 18 open-source quantum computing platforms. Our study shows that a significant fraction of these bugs (39.9%) are quantum-specific, calling for dedicated approaches to prevent and find them. The bugs are spread across various components, but quantum-specific bugs occur particularly often in components that represent, compile, and optimize quantum programming abstractions. Many quantum-specific bugs manifest through unexpected outputs, rather than more obvious signs of misbehavior, such as crashes. Finally, we present a hierarchy of recurrent bug patterns, including ten novel, quantum-specific patterns. Our findings not only show the importance and prevalence bugs in quantum computing platforms, but they help developers to avoid common mistakes and tool builders to tackle the challenge of preventing, finding, and fixing these bugs.<br>
[<a href="https://arxiv.org/abs/2110.14560">paper</a>]
[<a href="https://github.com/MattePalte/Bugs-Quantum-Computing-Platforms/">dataset and code</a>]
![Bugs Patterns in Quantum Computing Platforms](/assets/images/teaser_bug_in_platforms.png)


<h3>Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code</h3><br>
In <a href="https://conf.researchr.org/track/ase-2021/ase-2021-papers">Research Papers of IEEE/ACM International Conference on Automated Software Engineering</a> (ASE ’21).<br>
Neural models of code are successfully tackling various prediction tasks, complementing and sometimes even outperforming traditional program analysis. While most work focuses on end-to-end evaluations of such models, it often remains unclear what the models actually learn, and to what extent their reasoning about code matches that of skilled humans. A poor understanding of the model reasoning risks deploying models that are right for the wrong reason, and taking decisions based on spurious correlations in the training dataset. This paper investigates to what extent the attention weights of effective neural models match the reasoning of skilled humans. To this end, we present a methodology for recording human attention and use it to gather 1,508 human attention maps from 91 participants, which is the largest such dataset we are aware of. Computing human-model correlations shows that the copy attention of neural models often matches the way humans reason about code (Spearman rank coefficients of 0.49 and 0.47), which gives an empirical justification for the intuition behind copy attention. In contrast, the regular attention of models is mostly uncorrelated to human attention. We find that models and humans sometimes focus on different kinds of tokens, e.g., strings are important to humans but mostly ignored by models. The results also show that human-model agreement positively correlates with accurate predictions by a model, which calls for neural models that even more closely mimic human reasoning. Beyond the insights from our study, we envision the release of our dataset of human attention maps to help understand future neural models of code and to foster work on human-inspired models.<br>
[<a href="https://software-lab.org/publications/ase2021.pdf">paper</a>]
[<a href="https://github.com/MattePalte/thinking-like-a-developer">dataset and code</a>]
![Comparison of two attention maps](/assets/images/teaser_thinking_like_a_developer.png)


<h3>Time Series Anomaly Detection for CERN Large-Scale Computing Infrastructure</h3><br>

In <a href="https://cds.cern.ch/record/2752641">CERN Document Server</a> (CERN ’20).<br>
Detecting anomalies in the CERN Data Center poses challenges due to its extensive computing infrastructure and vast data volume. Presently, anomaly spotting hinges on threshold-based alarms established by managers for performance metrics time series of each component. This study aims to simplify this intricate task by exploring automated machine learning solutions for anomaly detection. We primarily focus on unsupervised methods, considering both traditional and modern deep anomaly detection approaches. We propose novel time series-specific techniques and adapt traditional and deep learning methods for time series data, evaluating them using a comparative analysis. This research showcases the strengths of traditional methods for the specific CERN use case while highlighting deep methods' effectiveness for complex normal instance patterns. Additionally, we establish an annotation system to efficiently label time series data and offer two new datasets for anomaly detection. Alongside our study, we release an open-source proof-of-concept anomaly detection system.

[<a href="https://cds.cern.ch/record/2752641">master thesis</a>]
[<a href="https://gitlab.cern.ch/cloud-infrastructure/data-analytics/">code</a>]
![Anomaly detection system](/assets/images/teaser_cern_anomaly_detection_paltenghi.png)
