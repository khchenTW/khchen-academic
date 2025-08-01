---
title: Realization of random forest for real-time evaluation through tree framing
publication_types:
  - "1"
authors:
  - Sebastian Buschjager
  - Kuan-Hsun Chen
  - Jian-Jia Chen
  - Katharina Morik
doi: 10.1109/ICDM.2018.00017
publication: IEEE International Conference on Data Mining (ICDM)
publication_short: IEEE International Conference on Data Mining (ICDM)
abstract: The optimization of learning has always been of particular concern for
  big data analytics. However, the ongoing integration of machine learning
  models into everyday life also demand the evaluation to be extremely fast and
  in real-time. Moreover, in the Internet of Things, the computing facilities
  that run the learned model are restricted. Hence, the implementation of the
  model application must take the characteristics of the executing platform into
  account Although there exist some heuristics that optimize the code,
  principled approaches for fast execution of learned models are rare. In this
  paper, we introduce a method that optimizes the execution of Decision Trees
  (DT). Decision Trees form the basis of many ensemble methods, such as Random
  Forests (RF) or Extremely Randomized Trees (ET). For these methods to work
  best, trees should be as large as possible. This challenges the data and the
  instruction cache of modern CPUs and thus demand a more careful memory layout.
  Based on a probabilistic view of decision tree execution, we optimize the two
  most common implementation schemes of decision trees. We discuss the
  advantages and disadvantages of both implementations and present a
  theoretically well-founded memory layout which maximizes locality during
  execution in both cases. The method is applied to three computer
  architectures, namely ARM (RISC), PPC (Extended RISC) and Intel (CISC) and is
  automatically adopted to the specific architecture by a code generator. We
  perform over 1800 experiments on several real-world data sets and report an
  average speed-up of 2 to 4 across all three architectures by using the
  proposed memory layout. Moreover, we find that our implementation outperforms
  sklearn, which was used to train the models by a factor of 1500.
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2018-11-17T11:08:46.985Z
---
