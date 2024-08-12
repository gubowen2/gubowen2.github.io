---
layout: page
title: publication 5
description: Scalable information extraction from free text electronic health records using large language models
img: assets/img/Scalable information extraction from free text electronic health records using large language models.png
importance: 2
category: 2024
---

Authors: Bowen Gu, Vivian Shao, Ziqian Liao, Valentina Carducci, Santiago Romero-Brufau, Jie Yang, Rishi Desai

Published on: medRxiv

Background: A vast amount of potentially useful information such as description of patient symptoms, family, and social history is recorded as free-text notes in electronic health records (EHRs) but is difficult to reliably extract at scale, limiting their utility in research. This study aims to assess whether an "out of the box" implementation of open-source large language models (LLMs) without any fine-tuning can accurately extract social determinants of health (SDoH) data from free-text clinical notes.

Methods: We conducted a cross-sectional study using EHR data from the Mass General Brigham (MGB) system, analyzing free-text notes for SDoH information. We selected a random sample of 200 patients and manually labeled nine SDoH aspects. Eight advanced open-source LLMs were evaluated against a baseline pattern-matching model. Two human reviewers provided the manual labels, achieving 93% inter-annotator agreement. LLM performance was assessed using accuracy metrics for overall, mentioned, and non-mentioned SDoH, and macro F1 scores.

Results: LLMs outperformed the baseline pattern-matching approach, particularly for explicitly mentioned SDoH, achieving up to 40% higher Accuracy_mentioned. openchat_3.5 was the best performing model, surpassing the baseline in overall accuracy across all nine SDoH aspects. The refined pipeline with prompt engineering reduced hallucinations and improved accuracy.

Conclusions: Open-source LLMs are effective and scalable tools for extracting SDoH from unstructured EHRs, surpassing traditional pattern-matching methods. Further refinement and domain-specific training could enhance their utility in clinical research and predictive analytics, improving healthcare outcomes and addressing health disparities

The full paper is available at <a href="https://www.medrxiv.org/content/10.1101/2024.08.08.24311237v1">medRxiv</a>.