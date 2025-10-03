---
title: "Automatic Identification of Extrinsic Bug Reports for Just-In-Time Bug Prediction"
collection: publications
category: manuscripts
permalink: /publication/2025-SCP-CAN
excerpt: '

    • We extract bug reports from the OpenStack project and apply various text classification techniques to evaluate the effectiveness of identifying extrinsic bugs. Experimental results indicate that text classification techniques can effectively identify extrinsic bugs by analyzing bug reports. Our proposed CAN model demonstrates the best performance in terms of the F1 score.<br>

    • We examine the role of source code in identifying extrinsic bugs. We hypothesize that valuable information can be extracted from the source code present in bug reports and conduct experiments to compare the classification performance of datasets incorporating and excluding code. The experimental results indicate that datasets incorporating source code as text enhance the models' ability to identify extrinsic bugs, while excluding source code generally degrades models' performance.<br>

    • We employ LIME to analyze feature importance in the CAN model’s correct predictions. Experimental results show that words such as "line" and "py" play a significant role in classifying intrinsic bugs, while terms like "test" and "api" strongly influence the classification of extrinsic bugs.
'
date: 2025-08-16
venue: 'Science of Computer Programming'
[//]: # (slidesurl: 'http://academicpages.github.io/files/slides2.pdf')
paperurl: 'http://hugo-liang.github.io/files/paper1.pdf'
[//]: # (bibtexurl: 'http://hugo-liang.github.io/files/2025-EXSY-SETCS.bib')
citation: 'Guisheng Fan, <strong>Yuguo Liang</strong>, Longfei Zu, Huiqun Yu, Zijie Huang, Wentao Chen. Automatic Identification of Extrinsic Bug Reports for Just-In-Time Bug Prediction. Science of Computer Programming 2025. [CCF-C][大修返回]
'
---

In software development, developers create bug reports within Issue Tracking System (ITS) to describe the cause, symptoms, severity, and other technical details of bugs. ITS includes reports of both intrinsic bugs (i.e., those originating within the software itself) and extrinsic bugs (i.e., those arising from third-party dependencies). Although extrinsic bugs do not appear in any activities within the Version Control System (VCS), Just-In-Time (JIT) bug prediction can still leverage internal software information, such as VCS process metrics.

Previous research has shown that excluding extrinsic bugs can significantly improve JIT bug prediction model's performance. However, manually classifying intrinsic and extrinsic bugs is time-consuming and prone to errors. To address this issue, we propose a CAN model that integrates the local feature extraction capability of TextCNN with the nonlinear approximation advantage of the Kolmogorov-Arnold Network (KAN). Experiments on 1,880 labeled data samples from the OpenStack project demonstrate that the CAN model outperforms benchmark models such as BERT and CodeBERT, achieving an accuracy of 0.7492 and an F1-score of 0.8072. By comparing datasets with and without source code, we find that incorporating source code information enhances model performance. Finally, using the Local Interpretable Model-agnostic Explanations (LIME), an explainable artificial intelligence technique, we identify that keywords such as "test" and "api" in bug reports significantly contribute to the prediction of extrinsic bugs.