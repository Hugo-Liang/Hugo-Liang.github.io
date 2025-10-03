---
title: "Aligning XAI explanations with software developers’ expectations: A case study with code smell prioritization
"
collection: publications
category: manuscripts
permalink: /publication/2024-ESWA-XAI4CodeSmellPrioritization
excerpt: '

    • We summarize the concerns of developers related to their decision-making toward code smell criticality, including code design and implementation, code evolution, code functionality, and developer-related factors.<br>

    • To our knowledge, we propose the first work that quantifies the gap between XAI explanation and developers’ expectations in code smell prioritization. The expectation could be huge even if all their concerns are captured by the features, e.g., more than 40% of the concerns of the developers do not appear in simple explanations.<br>

    • We discover that the gap could be narrowed to an acceptable extent by adapting to developers’ when selecting features, i.e., preserving the features related to the major concerns of developers as much as possible.<br>

    • We conclude that if the gap is narrowed, inspecting the top 3 to 5 important features is sufficient to meet the developers’ expectations in explaining issues with simpler causes such as Spaghetti Code, but the explanation may be less helpful for novice users in issues with complex or controversial causes such as Shotgun Surgery.<br>

    • We outline the challenges and opportunities of XAI for code smell prioritization and SQA in terms of feature engineering, problem definition, and XAI methodologies.
'
date: 2024-03-15
venue: 'Expert Systems with Applications'

[//]: # (slidesurl: 'http://academicpages.github.io/files/slides1.pdf')
paperurl: 'http://hugo-liang.github.io/files/2024-ESWA-XAI4CodeSmellPrioritization.pdf'
bibtexurl: 'http://hugo-liang.github.io/files/2024-ESWA-XAI4CodeSmellPrioritization.bib'
citation: 'Zijie Huang, Huiqun Yu, Guisheng Fan, Zhiqing Shao, Mingchen Li, #Yuguo Liang. Aligning XAI explanations with software developers’ expectations: A case study with code smell prioritization. Expert Systems with Applications, 238: 121640. https://doi.org/10.1016/j.eswa.2023.121640.'
---
EXplainable Artificial Intelligence (XAI) aims at improving users’ trust in black-boxed models by explaining their predictions. However, XAI techniques produced unreasonable explanations for software defect prediction since expected outputs (e.g., causes of bugs) were not captured by features used to build models. To set aside feature engineering limitations and evaluate whether XAI could adapt to developers, we exploit XAI for code smell prioritization (i.e., predicting criticalities of sub-optimal coding practices and design choices), whose features could capture developers’ major expectations. We assess the gap between XAI explanations and developers’ expectations in terms of (1) the accuracy of prediction, (2) the coverage of explanations on expectations, and (3) the complexity of explanations. We also narrow the gap by preserving the features related to developers’ expectations as much as possible in feature selection. We find that XAI can explain smells with simpler causes in top 3 to 5 features. Complex smells can be explained in around 10 features, which need more expertise to interpret. Selecting features adapting to the developers’ expectations improves coverage by 5% to 29%, with almost no negative impact on accuracy and complexity. Results also highlight the need of dividing coarse-grained prediction targets and developing fine-grained feature engineering.
