---
title: "Register Your Forests: Decision Tree Ensemble Optimization by Explicit
  CPU Register Allocation"
publication_types:
  - "3"
authors:
  - Daniel Biebert
  - Christian Hakert
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.48550/arXiv.2404.06846
publication: arXiv
publication_short: arXiv
abstract: Bringing high-level machine learning models to efficient and
  well-suited machine implementations often invokes a bunch of tools, e.g.~code
  generators, compilers, and optimizers. Along such tool chains, abstractions
  have to be applied. This leads to not optimally used CPU registers. This is a
  shortcoming, especially in resource constrained embedded setups. In this work,
  we present a code generation approach for decision tree ensembles, which
  produces machine assembly code within a single conversion step directly from
  the high-level model representation. Specifically, we develop various
  approaches to effectively allocate registers for the inference of decision
  tree ensembles. Extensive evaluations of the proposed method are conducted in
  comparison to the basic realization of C code from the high-level machine
  learning model and succeeding compilation. The results show that the
  performance of decision tree ensemble inference can be significantly improved
  (by up to ), if the methods are applied carefully to the appropriate scenario.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-04-09T22:21:59.073Z
---
