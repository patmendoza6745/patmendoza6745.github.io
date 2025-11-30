---
title: "GradShield: Alignment Preserving Finetuning"
collection: publications
category: under_review
permalink: /publication/gradshield-2025
date: 2025-10-07
venue: 'ICLR 2026'
authors: 'Zhanhao Hu*, Xiao Huang*, Patrick Mendoza, Emad A. Alghamdi, Raluca Ada Popa, David Wagner'
header:
  teaser: gradshield.png
paperurl: 'https://openreview.net/pdf?id=YYUNm7IibC'
bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
---

## Abstract

Large Language Models (LLMs) pose a significant risk of safety misalignment after finetuning, as models can be compromised by both explicitly and implicitly harmful data. Even some seemingly benign data can inadvertently steer a model towards unsafe behaviors. To address this, we introduce GradShield, a principled filtering method that safeguards LLMs during finetuning by identifying and removing harmful data points before they corrupt the model’s alignment. It removes potentially harmful data by computing a Finetuning Implicit Harmfulness Score (FIHS) for each data point and employs an adaptive thresholding algorithm. We apply GradShield to multiple utility fine-tuning tasks combined with different levels of harmful data, and evaluate the safety and utility performance of the resulting LLMs under various metrics. Our results show that GradShield outperforms all baseline methods, as it consistently maintains a low Attack Success Rate (ASR) of under $$6\%$$, while preserving the utility performance.