---
title: Efficient Realization of Decision Trees for Real-Time Inference
subtitle: Accepted on December 2021
publication_types:
  - "2"
authors:
  - Kuan-Hsun Chen
  - ChiaHui Su
  - Christian Hakert
  - Sebastian Buschjäger
  - Chao-Lin Lee
  - Jenq-Kuen Lee
  - Katharina Morik
  - Jian-Jia Chen
doi: 10.1145/3508019
publication: ACM Trans. Embed. Comput. Syst. (TECS)
publication_short: ACM Trans. Embed. Comput. Syst. (TECS)
abstract: "For timing-sensitive edge applications, the demand for efficient
  lightweight machine learning solutions has increased recently. Tree ensembles
  are among the state-of-the-art in many machine learning applications. While
  single decision trees are comparably small, an ensemble of trees can have a
  significant memory footprint leading to cache locality issues, which are
  crucial to performance in terms of execution time. In this work, we analyze
  memory-locality issues of the two most common realizations of decision trees,
  i.e. native and if-else trees. We highlight, that both realizations demand a
  more careful memory layout to improve caching behavior and maximize
  performance. "
draft: false
featured: true
tags:
  - Tree
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-08T09:29:25.165Z
---
We adopt a probabilistic model of decision tree inference to find the best memory layout for each tree at the application layer. Further, we present an efficient heuristic to take architecture-dependent information into account thereby optimizing the given ensemble for a target computer architecture. Our code-generation framework, which is freely available on an open-source repository, produces optimized code sessions while preserving the structure and accuracy of the trees. With several real-world data sets, we evaluate the elapsed time of various tree realizations on server hardware as well as embedded systems for Intel and ARM processors. Our optimized memory layout achieves a reduction in execution time up to 75 % execution for server-class systems, and up to 70 % for embedded systems, respectively.