---
title: Compositional Timing Analysis of Asynchronized Distributed Cause-Effect Chains
publication_types:
  - "2"
authors:
  - Mario Günzel
  - Kuan-Hsun Chen
  - Niklas Ueter
  - Georg von der Brüggen
  - Marco Dürr
  - Jian-Jia Chen
doi: 10.1145/3587036
publication: ACM Transactions on Embedded Computing Systems
publication_short: TECS
abstract: Real-time systems require the formal guarantee of timing constraints,
  not only for the individual tasks but also for the end-to-end latency of data
  flows. The data flow among multiple tasks, e.g., from sensors to actuators, is
  described by a cause-effect chain, independent from the priority order of the
  tasks. In this paper, we provide an end-to-end timing-analysis for
  cause-effect chains on asynchronized distributed systems with periodic task
  activations, considering the maximum reaction time (i.e., the duration of data
  processing) and the maximum data age (i.e., the worst-case data freshness). We
  first provide an analysis of the end-to-end latency on one local electronic
  control unit (ECU) that has to consider only the jobs in a bounded time
  interval. We extend our analysis to globally asynchronized systems by
  exploiting a compositional property to combine the local results. Throughout
  synthesized data based on an automotive benchmark as well as on randomized
  parameters, we show that our analytical results improve the state-of-the-art.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-06-03T13:31:30.132Z
---
