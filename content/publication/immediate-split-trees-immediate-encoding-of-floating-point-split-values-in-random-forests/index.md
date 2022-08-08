---
title: "Immediate Split Trees: Immediate Encoding of Floating Point Split Values
  in Random Forests"
subtitle: Just accepted
publication_types:
  - "1"
authors:
  - Christian Hakert
  - Kuan-Hsun Chen
  - Jian-Jia Chen
publication: European Conference on Machine Learning and Principles and Practice
  of Knowledge Discovery in Databases (ECML PKDD)
publication_short: European Conference on Machine Learning and Principles and
  Practice of Knowledge Discovery in Databases (ECML PKDD)
abstract: Random forests and decision trees are increasingly interesting
  candidates for resource-constrained machine learning models. In order to make
  the execution of these models efficient under resource limitations, various
  optimized implementations have been proposed in the literature, usually
  implementing either native trees or if-else trees. While a certain motivation
  for the optimization of if-else trees is to benefit the behavior of dedicated
  instruction caches, in this work we highlight that if-else trees might also
  strongly depend on data caches.
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-08T09:07:22.630Z
---
We identify one crucial issue of if-else tree implementations and propose an optimized implementation, which keeps the logic tree structure untouched and thus does not influence the accuracy, but eliminates the need
to load comparison values from the data caches. Experimental evaluation of this implementation shows that we can greatly reduce the amount of data cache misses by up to ≈ 99%, while not increasing the amount of instruction cache misses in comparison to the state-of-the-art. We additionally highlight various scenarios, where the reduction of data cache misses draws important benefit on the allover execution time