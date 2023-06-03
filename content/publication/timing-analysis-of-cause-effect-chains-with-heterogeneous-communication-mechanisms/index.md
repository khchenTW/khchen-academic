---
title: Timing Analysis of Cause-Effect Chains with Heterogeneous Communication
  Mechanisms
publication_types:
  - "1"
authors:
  - Mario Günzel
  - Niklas Ueter
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.1145/3575757.3593640
publication: The 31st International Conference on Real-Time Networks and Systems
publication_short: " RTNS"
abstract: >-
  Software applications in automotive systems are comprised of communicating
  real-time tasks, described by cause-effect chains. To guarantee functional
  correctness, it is mandatory to verify end-to-end timing latencies of the
  cause-effect chains. The analysis of end-to-end latencies highly depends on
  the communication method. Implicit communication is standardized in the
  AUTOSAR Timing Specification and ensures data consistency. To abstract
  communication from the actual execution behavior of tasks, logical execution
  time (LET) has been proposed. However, the determinism that is provided by LET
  comes at the cost of increased end-to-end latencies. In industry-grade
  systems, periodic and sporadic tasks using LET and implicit communication
  co-exist. Hence, end-to-end latency analyses should cover such heterogeneous
  cause-effect chains.


  In this work, we present the first formal analysis framework for end-to-end analysis of cause-effect chains that allows heterogeneous types of recurrent tasks and different communication mechanisms, i.e., (i) a mixed setup of sporadic and periodic tasks that (ii) communicate by a mixed setup of LET and implicit communication mechanism. In this regard, we uncover the principles that homogeneous analyses are built from and discuss how these principles can be transferred to the heterogeneous case. In particular, we cut the cause-effect chain into homogeneous parts which results in 3 different analyses: one baseline approach, one that directly uses the homogeneous results, and one that reduces the pessimism for changes of communication means. Our evaluation shows that for some systems the two more sophisticated approaches outperform the baseline significantly, while for other systems the baseline is already satisfactory.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-06-03T13:29:50.190Z
---
