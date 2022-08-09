---
title: EDF-Like Scheduling for Self-Suspending Real-Time Tasks
publication_types:
  - "2"
authors:
  - Mario Günzel
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.48550/arXiv.2111.09725
publication: arXiv preprint arXiv:2111.09725
publication_short: arXiv preprint arXiv:2111.09725
abstract: >-
  In real-time systems, schedulability tests are utilized to provide timing
  guarantees. However, for self-suspending task sets, current suspension-aware
  schedulability tests are limited to Task-Level Fixed-Priority~(TFP) scheduling
  or Earliest-Deadline-First~(EDF) with constrained-deadline task systems. In
  this work we provide a unifying schedulability test for the uniprocessor
  version of Global EDF-Like (GEL) schedulers and arbitrary-deadline task sets.
  A large body of existing scheduling algorithms can be considered as EDF-Like,
  such as EDF, First-In-First-Out~(FIFO), Earliest-Quasi-Deadline-First~(EQDF)
  and Suspension-Aware EDF~(SAEDF). Therefore, the unifying schedulability test
  is applicable to those algorithms. Moreover, the schedulability test can be
  applied to TFP scheduling as well.

  Our analysis is the first suspension-aware schedulability test applicable to arbitrary-deadline sporadic real-time task systems under Job-Level Fixed-Priority (JFP) scheduling, such as EDF. Moreover, it is the first unifying suspension-aware schedulability test framework that covers a wide range of scheduling algorithms. Through numerical simulations, we show that the schedulability test outperforms the state of the art for EDF under constrained-deadline scenarios. Moreover, we demonstrate the performance of different configurations under EQDF and SAEDF.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-11-18T12:23:13.597Z
---
