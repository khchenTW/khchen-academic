---
title: Efficiently Approximating the Worst-Case Deadline Failure Probability under EDF
publication_types:
  - "1"
authors:
  - Georg von der Brüggen
  - Nico Piatkowski
  - Kuan-Hsun Chen
  - Jian-Jia Chen
  - Katharina Morik
  - Björn Brandenburg
doi: 10.1109/RTSS52674.2021.00029
publication: IEEE Real-Time Systems Symposium (RTSS)
publication_short: IEEE Real-Time Systems Symposium (RTSS)
abstract: Probabilistic timing guarantees enable a tradeoff between system
  safety and hardware costs in embedded real-time systems. A key metric for
  assessing whether timing requirements can be satisfied with sufficiently high
  probability is the worst-case deadline failure probability (WCDFP). This paper
  studies the WCDFP under earliest-deadline first (EDF) scheduling for tasks
  with several probabilistic execution modes (e.g., a low-needs "typical" mode
  and a resource-intensive exceptional" mode). Under EDF, no known approach can
  bound the WCDFP for practically sized workloads since the time complexity of
  prior approaches is exponential in the number of jobs. This paper examines the
  structure of the EDF WCDFP problem and establishes a safe, efficiently
  computable over-approximation by restricting the analysis to a set of specific
  intervals and providing a criterion to stop the derivation early without
  risking under-approximation. The analysis first assumes independent jobs and
  is then extended to handle dependencies (i.e., acyclic task chains). An
  evaluation shows that (i) even if 99.9999% of the jobs must meet their
  deadlines, a significantly higher utilization is possible than in the
  deterministic case, (ii) the analysis is scalable to 30 tasks with more than
  10^60 jobs in the hyperperiod, and (iii) assuming independence in the presence
  of dependent tasks can severely under-estimate the WCDFP.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-12-07T10:03:46.824Z
---
