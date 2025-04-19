---
layout: post
image: /images/bench_mark.png
title:  "VisualPuzzles: Decoupling Multimodal Reasoning Evaluation from Domain Knowledge"
authors: "Yueqi Song, Tianyue Ou, Yibo Kong, <strong>Zecheng Li</strong>, Graham Neubig, Xiang Yue"
info: "VisualPuzzles: a benchmark that targets visual reasoning while deliberately minimizing reliance on specialized knowledge. One major source of our questions is manually translated logical reasoning questions from the Chinese Civil Service Examination."
date: 2025-04-14 00:00:00 +00:00
categories: others
website: https://neulab.github.io/VisualPuzzles/
preprint: https://arxiv.org/abs/2504.10342
code: https://huggingface.co/datasets/multimodal-reasoning/multimodal-reasoning/tree/main
---
VisualPuzzles consists of 1168 diverse questions spanning five categories: algorithmic, analogical, deductive, inductive, and spatial reasoning. Each puzzle is labeled as easy, medium, or hard. 

While there has been significant progress in curating high-quality text-only logical reasoning benchmarks, there remains a notable gap in the development of comprehensive multimodal logical reasoning benchmarks. Existing multimodal benchmarks tend to focus heavily on knowledge-based tasks, which are biased towards models pre-trained on extensive knowledge bases, making them less accessible to smaller models with limited pretraining on knowledge bases. Moreover, these benchmarks often concentrate on a single type of logical reasoning, lacking the breadth necessary to fully evaluate a model's reasoning capabilities across diverse scenarios. This narrow focus limits their utility in assessing general logical reasoning skills in multimodal contexts, underscoring the need for more balanced, diverse, and inclusive multimodal benchmarks.
