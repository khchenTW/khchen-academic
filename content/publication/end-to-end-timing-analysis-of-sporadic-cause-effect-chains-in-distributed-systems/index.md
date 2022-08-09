---
title: End-to-end timing analysis of sporadic cause-effect chains in distributed
  systems
publication_types:
  - "2"
authors:
  - Marco Dürr
  - Georg Von Der Brüggen
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.1145/3358181
publication: ACM Transactions on Embedded Computing Systems (TECS)
publication_short: ACM Transactions on Embedded Computing Systems (TECS)
abstract: >-
  A cause-effect chain is used to define the logical order of data dependent
  tasks, which is independent from the execution order of the jobs of the
  (periodic/sporadic) tasks. Analyzing the worst-case End-to-End timing
  behavior, associated to a cause-effect chain, is an important problem in
  embedded control systems. For example, the detailed timing properties of
  modern automotive systems are specified in the AUTOSAR Timing Extensions.


  In this paper, we present a formal End-to-End timing analysis for distributed systems. We consider the two most important End-to-End timing semantics, i.e., the button-to-action delay (termed as the maximum reaction time) and the worst-case data freshness (termed as the maximum data age). Our contribution is significant due to the consideration of the sporadic behavior of job activations, whilst the results in the literature have been mostly limited to periodic activations. The proof strategy shows the (previously unexplored) connection between the reaction time (data age, respectively) and immediate forward (backward, respectively) job chains. Our analytical results dominate the state of the art for sporadic task activations in distributed systems and the evaluations show a clear improvement for synthesized task systems as well as for a real world automotive benchmark setting.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2019-10-17T14:39:49.121Z
---
