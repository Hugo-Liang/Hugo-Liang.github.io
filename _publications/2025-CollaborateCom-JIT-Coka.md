---
title: "JIT-Coka: An Improved Framework for Just-in-Time Defect Prediction and Localization Using Fused Features of Code Change"
collection: publications
category: conferences
permalink: /publication/2025-CollaborateCom-JIT-Coka
excerpt: '

    • We perform comprehensive experiments on representative JIT-DP and DL models using the high quality JIT-Defects4J dataset and evaluate them with multiple metrics to fill the evaluation gap in prior studies.<br>

    • We develop JIT-Coka, a model applicable to both JIT-DP and DL tasks. On the DP task, JIT-Coka achieves significantly better performance than the current state-of-the-art model (JIT-Smart) in terms of Precision and MCC, while maintaining comparable performance in DL.<br>

    • We conduct a comprehensive ablation study to validate the effectiveness of each component of JIT-Coka. Moreover, the implementation and trained models are made publicly available to facilitate future research.

'
date: 2025-08-31
venue: '21th EAI International Conference on Collaborative Computing: Networking, Applications and Worksharing'
paperurl: 'http://hugo-liang.github.io/files/2025-CollaborateCom-JIT-Coka.pdf'
[//]: # (bibtexurl: 'http://hugo-liang.github.io/files/2025-CS-SCA_Tools.bib')
citation: '<strong>Yuguo Liang</strong>, Chengcheng Wu, Wentao Chen, Guisheng Fan, Huiqun Yu. JIT-Coka: An Improved Framework for Just-in-Time Defect Prediction and Localization Using Fused Features of Code Change. Collaborative Computing: Networking, Applications and Worksharing. CollaborateCom 2025. [CCF-C][预出版]
'
---

Just-in-Time Defect Prediction and Localization (JIT-DP and DL) play a crucial role in software quality assurance by identifying defective code changes and locating faulty lines at the time of code submission. While existing methods leverage either handcrafted expert features or semantic features extracted by deep learning models, few explicitly distinguish or effectively fuse these two types of information. In this paper, we propose JIT-Coka, an improved framework for JIT-DP and DL tasks that combines an encoder-decoder based pre-trained model of code (CodeT5) with KANLinear, which is a spline-based adaptive nonlinear classifier used to model fine-grained nonlinear relationships between semantic and expert features. We conduct comprehensive experiments on the high-quality JIT-Defects4J dataset, evaluating JIT-Coka and representative baselines using multiple metrics. Results show that JIT-Coka significantly outperforms state-of-the-art models in defect prediction, improving F1 and MCC by 6.8% and 8.5% respectively compared to JIT-Smart, while maintaining competitive performance in DL.