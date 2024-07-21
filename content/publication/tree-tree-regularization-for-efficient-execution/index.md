---
title: "TREE: Tree Regularization for Efficient Execution"
publication_types:
  - "3"
authors:
  - Lena Schmid
  - Daniel Biebert
  - Christian Hakert
  - Kuan-Hsun Chen
  - Michel Lang
  - Markus Pauly
  - Jian-Jia Chen
doi: 10.48550/arXiv.2406.12531
publication: arXiv
publication_short: arXiv
abstract: >-
  The rise of machine learning methods on heavily resource constrained devices
  requires not only the choice of a suitable model architecture for the target
  platform, but also the optimization of the chosen model with regard to
  execution time consumption for inference in order to optimally utilize the
  available resources. Random forests and decision trees are shown to be a
  suitable model for such a scenario, since they are not only heavily tunable
  towards the total model size, but also offer a high potential for optimizing
  their executions according to the underlying memory architecture.

  In addition to the straightforward strategy of enforcing shorter paths through decision trees and hence reducing the execution time for inference, hardware-aware implementations can optimize the execution time in an orthogonal manner. One particular hardware-aware optimization is to layout the memory of decision trees in such a way, that higher probably paths are less likely to be evicted from system caches. This works particularly well when splits within tree nodes are uneven and have a high probability to visit one of the child nodes.

  In this paper, we present a method to reduce path lengths by rewarding uneven probability distributions during the training of decision trees at the cost of a minimal accuracy degradation. Specifically, we regularize the impurity computation of the CART algorithm in order to favor not only low impurity, but also highly asymmetric distributions for the evaluation of split criteria and hence offer a high optimization potential for a memory architecture-aware implementation.

  We show that especially for binary classification data sets and data sets with many samples, this form of regularization can lead to an reduction of up to approximately four times in the execution time with a minimal accuracy degradation.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-06-17T22:19:23.718Z
---
