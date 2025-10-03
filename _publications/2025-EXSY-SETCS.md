---
title: "Automatic Code Summarization Using Abbreviation Expansion and Subword Segmentation"
collection: publications
category: manuscripts
permalink: /publication/2025-EXSY-CodeSummarization
excerpt: '
• We propose the use of code abbreviation expansion to weaken the negative impact of abbreviations on program understanding and strengthen the language alignment ability of code summarization models. A series of context-based heuristic algorithms are adopted to expand abbreviations nested in code snippets of Java code summarization datasets.<br>

• We introduce the unigram subword segmentation algorithm to expose more semantic information and further enhance the program understanding performance of code summarization models. Code-specific tokenizers are developed to tokenize code-summary pairs into more granular and semantically preserved subword sequences.<br>

• We present a framework Semantic Enhanced Transformer for Code Summarization (SETCS) to better leverage the semantic information introduced by above methods. A robust baseline is designed by fusing embeddings of original and newly generated subtoken sequences, allowing for effective capture of critical information.<br>

• To the best of our knowledge, this is the first work that incorporates code abbreviation expansion and subword segmentation into the automatic code summarization task. These methods are model-agnostic and can be easily integrated into existing automatic code summarization approaches. Experiments conducted on two widely evaluated datasets demonstrate the effectiveness of our proposed methods.'
date: 2025-01-08
venue: 'Expert Systems'
[//]: # (slidesurl: 'http://academicpages.github.io/files/slides2.pdf')
paperurl: 'http://hugo-liang.github.io/files/2025-EXSY-SETCS.pdf'
bibtexurl: 'http://hugo-liang.github.io/files/2025-EXSY-SETCS.bib'
citation: '**Yuguo Liang**, Guisheng Fan, Huiqun Yu, Mingchen Li, and Zijie Huang. 2025. Automatic Code Summarization Using Abbreviation Expansion and Subword Segmentation. Expert Systems, 42: e13835. https://doi.org/10.1111/exsy.13835.
'
---

Automatic code summarization refers to generating concise natural language descriptions for code snippets. It is vital for improving the efficiency of program understanding among software developers and maintainers. Despite the impressive strides made by deep learning-based methods, limitations still exist in their ability to understand and model semantic information due to the unique nature of programming languages. We propose two methods to boost code summarization models: context-based abbreviation expansion and unigram language model-based subword segmentation. We use heuristics to expand abbreviations within identifiers, reducing semantic ambiguity and improving the language alignment of code summarization models. Furthermore, we leverage subword segmentation to tokenize code into finer subword sequences, providing more semantic information during training and inference, thereby enhancing program understanding. These methods are model-agnostic and can be readily integrated into existing automatic code summarization approaches. Experiments conducted on two widely used Java code summarization datasets demonstrated the effectiveness of our approach. Specifically, by fusing original and modified code representations into the Transformer model, our Semantic Enhanced Transformer for Code Summarizsation (SETCS) serves as a robust semantic-level baseline. By simply modifying the datasets, our methods achieved performance improvements of up to 7.3%, 10.0%, 6.7%, and 3.2% for representative code summarization models in terms of BLEU-4, METEOR, ROUGE-L and SIDE, respectively.