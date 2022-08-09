---
title: " Implementation and Evaluation of Multiprocessor Resource
  Synchronization Protocol (MrsP)"
publication_types:
  - "1"
authors:
  - Junjie Shi
  - Kuan-Hsun Chen
  - Shuai Zhao
  - Wen-Hung Huang
  - Jian-Jia Chen
  - Andy Wellings
publication: 13th Workshop on Operating Systems Platforms for Embedded Real-Time
  Applications (OSPERT)
publication_short: 13th Workshop on Operating Systems Platforms for Embedded
  Real-Time Applications (OSPERT)
abstract: Preventing race conditions or data corruptions for concurrent shared
  resource accesses of real-time tasks is a challenging problem. By adopting the
  resource synchronization protocols, such a problem has been studied in the
  literature, but there are not enough evaluations that consider the overhead
  from the implementations of different protocols. In this paper, we discuss our
  implementation of the Multiprocessor Resource Sharing Protocol (MrsP) and the
  Distributed Non-Preemptive Protocol (DNPP) on LITMUS^RT. Both of them are
  released in open source under GNU General Public License (GPL2). To study the
  impact of the implementation overhead, we deploy different synchronization
  scenarios with generated task sets and measure the performance with respect to
  the worst-case response time. The results illustrate that generally the
  implementation overhead is acceptable, whereas some unexpected system overhead
  may happen under distributed synchronization protocols on LITMUS^RT.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2017-01-01T17:12:49.942Z
---
