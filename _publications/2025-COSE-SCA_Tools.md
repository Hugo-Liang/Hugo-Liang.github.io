---
title: "Tool or Toy: Are SCA Tools Ready for Challenging Scenarios?"
collection: publications
category: manuscripts
permalink: /publication/2025-COSE-SCA_Tools
excerpt: '

    • This study proposes the first comprehensive evaluation model that integrates three core functions: dependency detection, vulnerability identification and license recognition. It covers multi-language ecosystems, source and binary forms and adversarial threats, addressing the limitations of previous research focused on single function or ecosystem.<br>

    • We construct a standardized test suite encompassing Java datasets, multi-language projects, diverse build methods, and adversarial scenarios. The datasets are derived from academic literature and leading open-source repositories over the past five years. All datasets and ground-truth lists are open-sourced to support reproducibility.<br>

    • Experiments on six datasets using four state-of-the-art tools, including RA, CleanSource, OpenSCA, and Snyk, this study identifies weaknesses in both commercial and open-source solutions and proposes targeted optimizations.
'
date: 2025-08-09
venue: 'Computers & Security'

paperurl: 'http://hugo-liang.github.io/files/2025-COSE-SCA_Tools.pdf'
bibtexurl: 'http://hugo-liang.github.io/files/2025-COSE-SCA_Tools.bib'
citation: 'Congyan Shu, Wentao Chen, Zijie Huang, Guisheng Fan<sup>*</sup>, Huiqun Yu<sup>*</sup>, Hengrun Zhang, <strong>Yuguo Liang</strong>. Tool or Toy: Are SCA Tools Ready for Challenging Scenarios? Computers & Security, 2025, 158: 104624. <a href="https://doi.org/10.1016/j.cose.2025.104624">https://doi.org/10.1016/j.cose.2025.104624</a>. [CCF-B/SCI-Q2]
'
---
 
The widespread adoption of open-source software (OSS) has introduced new security challenges to the software supply chain. While existing studies confirm the basic capabilities of Software Composition Analysis (SCA) tools, such as vulnerability detection and dependency resolution. They often focus on single ecosystems or detection aspects. This limited scope overlooks real-world complexities, including multi-language ecosystems, source and binary dependencies, and adversarial threats. Without a comprehensive evaluation, SCA tools may perform well in controlled settings but struggle in more complex scenarios. To address this gap, this study proposes a evaluation framework centered on the core functionalities of SCA tools: dependency detection, vulnerability identification, and license inspection. It covers three key dimensions including multi-language ecosystems compatibility, build forms, and attack defense. Using standardized datasets and quantitative metrics, such as precision, recall, F1-score and standard deviation, we evaluate four representative SCA tools, including both open-source and commercial options. Results reveal significant limitations in binary dependencies, language coverage, and license consistency. SCA tools also face challenges in balancing precision, coverage and robustness. The study highlights systemic shortcomings in current SCA tools, revealing that many perform like limited-use toys under real-world conditions. It offers data-driven recommendations to guide the evolution of these tools into practical, reliable solutions for supply chain security governance.