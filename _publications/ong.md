---
title: "ONG: Orthogonal Natural Gradient Descent"
collection: publications
category: workshop
permalink: /publication/ong-2025
date: 2025-09-24
venue: 'Non-Euclidean Foundation Models and Geometric Learning Workshop @ NeurIPS 2025'
authors: 'Yajat Yadav, Patrick Mendoza, Jathin Korrapati'
header:
  teaser: ong.png
paperurl: 'https://openreview.net/pdf?id=E5a7GeL4qc'
bibtexurl: 'https://patmendoza6745.github.io/files/ong.bib'
---

## Abstract

Orthogonal Gradient Descent (OGD) has emerged as a powerful method for continual learning. However, its Euclidean projections do not leverage the underlying information-geometric structure of the problem, which can lead to suboptimal convergence in learning tasks. To address this, we propose incorporating the natural gradient into OGD and present **ONG (Orthogonal Natural Gradient Descent)**.
ONG preconditions each new task-specific gradient with an efficient EKFAC approximation of the inverse Fisher information matrix, yielding updates that follow the steepest descent direction under a Riemannian metric. To preserve performance on previously learned tasks, ONG projects these natural gradients onto the orthogonal complement of prior tasks’ natural gradients. We provide an initial theoretical justification for this procedure, introduce the Orthogonal Natural Gradient Descent (ONG) algorithm, and present preliminary results on the Permuted and Rotated MNIST benchmarks. Our preliminary results, however, indicate that a naive combination of natural gradients and orthogonal projections has potential issues. This finding has motivated continued future work focused on robustly reconciling these geometric perspectives to develop a continual learning method, establishing a more rigorous theoretical foundation with formal convergence guarantees, and extending empirical validation to large-scale continual learning benchmarks.