---
title: Mental State classification (Part 1)
date: 2020-06-16
---


__Oscillatory__: Testing recent and promising machine learning algorithms to classify cognitive and affective states from oscillatory-based EEG signals


<!--more-->



#### Abstract 
Estimating cognitive or affective states from brain signals is a key but challenging step in the creation of passive brain-computer interface (BCI) applications. So far, estimating mental workload or emotions from EEG signals is only feasible with modest classification accuracies, thus leading to unreliable neuroadaptive applications. However, recent machine learning algorithms, notably Riemannian geometry based classifiers (RGC) and convolutional neural networks (CNN), have shown to be promising for other BCI systems, e.g., motor imagery-BCIs. However, they have not been formally studied and compared together for cognitive or affective states classification. This paper thus explores such machine learning algorithms, proposes new variants of them, and benchmarks them with classical methods to estimate both mental workload and affective states (Valence/Arousal) from EEG signals. We study these approaches with both subject-specific and subject-independent calibration, to go towards calibration-free systems. Our results suggested that a CNN obtained the highest mean accuracy, although not significantly so, in both conditions for the mental workload study, followed by RGCs. However, this same CNN underperformed in both conditions for the emotion data set, a data set with small training data. On the contrary, RGCs proved to have the highest mean accuracy with the Filter Bank Tangent Space classifier (FBTSC) we introduced in this paper. Our results thus contributed to improve the reliability of cognitive and affective states classification from EEG. They also provide guidelines about when to use which machine learning algorithm.

#### Other members
Andrzeij Cichocki, Fabien Lotte

#### Collaborations
- RIKEN Brain Science Institue, Wakoshi, Japan
- Inria BSO, Talence, France

#### Publications

* Appriou A., Cichocki, A., Lotte, F., (2018) « Towards Robust Neuroadaptative HCI: Exploring Modern Machine Learning Methods to Estimate Mental Workload From EEG Signals », ACM CHI Conference on Human Factors in Computing Systems - Late Breaking Work - Montreal, Canada (6 pages)
* A. Appriou, A. Cichocki, and F. Lotte., (2020) « Modern machine learning  algorithms  to  classify  cognitive  and  affective states  from  electroencephalography  signals. » IEEE  Systems, Man and Cybernetics Magazine [pdf](https://www.google.com)

