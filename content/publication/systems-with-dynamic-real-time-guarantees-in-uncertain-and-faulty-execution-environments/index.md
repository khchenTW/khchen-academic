---
title: Systems with dynamic real-time guarantees in uncertain and faulty
  execution environments
publication_types:
  - "1"
authors:
  - Georg von der Brüggen
  - Kuan-Hsun Chen
  - Wen-Hung Huang
  - Jian-Jia Chen
doi: 10.1109/RTSS.2016.037
publication: IEEE Real-Time Systems Symposium (RTSS)
publication_short: IEEE Real-Time Systems Symposium (RTSS)
abstract: In many practical real-time systems, the physical environment and the
  system platform can impose uncertain execution behaviour to the system. For
  example, if transient faults are detected, the execution time of a task
  instance can be increased due to recovery operations. Such fault recovery
  routines make the system very vulnerable with respect to meeting hard
  real-time deadlines. In theory and in practical systems, this problem is often
  handled by aborting not so important tasks to guarantee the response time of
  the more important tasks. However, for most systems such faults occur rarely
  and the results of not so important tasks might still be useful, even if they
  are a bit late. This implicates to not abort these not so important tasks but
  keep them running even if faults occur, provided that the more important tasks
  still meet their hard real time properties. In this paper, we present Systems
  with Dynamic Real-Time Guarantees to model this behaviour and determine if the
  system can provide full timing guarantees or limited timing guarantees without
  any online adaptation after a fault occurred. We present a schedulability
  test, provide an algorithm for optimal priority assignment, determine the
  maximum interval length until the system will again provide full timing
  guarantees and explain how we can monitor the system state online. The
  approaches presented in this paper can also be applied to mixed criticality
  systems with dual criticality levels.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2016-11-29T12:11:32.794Z
---
