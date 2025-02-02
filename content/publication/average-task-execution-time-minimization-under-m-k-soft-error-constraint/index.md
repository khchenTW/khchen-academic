---
title: Average Task Execution Time Minimization under (m,k) Soft-Error Constraint
subtitle: Just accepted
publication_types:
  - "1"
authors:
  - Junjie Shi
  - Niklas Ueter
  - Jian-Jia Chen
  - Kuan-Hsun Chen
publication: IEEE Real-Time and Embedded Technology and Applications Symposium
publication_short: IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS)
abstract: >-
  Safety-critical systems are often subjected to transient faults. Since these
  transient faults may lead to soft errors that cause catastrophic consequences,
  error-handling must be addressed by design. Full-protection against faults is
  too costly in terms of resource usage. A common approach to relax the resource
  demands and limit the impact of errors is to consider (m, k)-constraints,
  which requires that at least $m$ jobs out of any k consecutive jobs are
  error-free. To assure (m, k)-compliance, static patterns are widely used to
  select the job execution modes, i.e., either in an error-free mode at the cost
  of increased worst-case execution time or in an error-prone mode with the
  advantage of less execution time. 


  Although static patterns have been shown to be effective in energy-aware designs, 

  resource over-provision is inevitable due to the relatively low rate of error probability.

  In this work, we propose two dynamic (and adaptive) approaches that allow the scheduler to dynamically select execution modes based on the error-history of the past jobs and the actual error probability. We firstly propose a Markov Chain based solution if the error-probability is known and static and secondly a reinforcement learning-based approach that can handle unknown error probabilities. Experimental evaluations show that our approaches outperform the state-of-the-art in most of the evaluated cases in terms of average utilization for each task and the overall utilization for multitask systems.
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-02-12T09:50:22.398Z
---
