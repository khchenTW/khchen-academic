---
title: Language-Based Deployment Optimization for Random Forest
publication_types:
  - "1"
authors:
  - Jannik Malcher
  - Daniel Biebert
  - Kuan-Hsun Chen
  - Sebastian Buschjäger
  - Christian Hakert
  - Jian-Jia Chen
doi: 10.1145/3652032.3659366
publication: ACM SIGPLAN/SIGBED International Conference on Languages,
  Compilers, Tools and Theory of Embedded Systems
publication_short: LCTES
abstract: Arising popularity for resource-efficient machine learning models
  makes random forests and decision trees famous models in recent years.
  Naturally, these models are tuned, optimized, and transformed to feature
  maximally low-resource consumption. A subset of these strategies targets the
  model structure and model logic and therefore induces a trade-off between
  resource-efficiency and prediction performance. An orthogonal set of
  approaches targets hardware-specific optimizations, which can improve
  performance without changing the behavior of the model. Since such
  hardware-specific optimizations are usually hardware-dependent and inflexible
  in their realizations, this paper envisions a more general application of such
  optimization strategies at the level of programming languages. We therefore
  discuss a set of suitable optimization strategies first in general and
  envision their application in LLVM IR, i.e. a flexible and
  hardware-independent ecosystem.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-05-31T22:06:02.744Z
---
