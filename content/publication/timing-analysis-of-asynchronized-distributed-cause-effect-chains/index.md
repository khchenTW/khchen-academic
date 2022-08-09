---
title: Timing analysis of asynchronized distributed cause-effect chains
publication_types:
  - "1"
authors:
  - Mario Günzel
  - Kuan-Hsun Chen
  - Niklas Ueter
  - Georg von der Brüggen
  - Marco Dürr
  - Jian-Jia Chen
doi: 10.1109/RTAS52030.2021.00012
publication: IEEE 27th Real-Time and Embedded Technology and Applications Symposium (RTAS)
publication_short: IEEE 27th Real-Time and Embedded Technology and Applications Symposium (RTAS)
abstract: Real-time systems require the formal guarantee of timing-constraints,
  not only for the individual tasks but also for the data-propagation paths. A
  cause-effect chain describes the data flow among multiple tasks, e.g., from
  sensors to actuators, independent from the priority order of the tasks. In
  this paper, we provide an end-to-end timing-analysis for cause-effect chains
  on asynchronized distributed systems with periodic task activations,
  considering the maximum reaction time (duration of data processing) and the
  maximum data age (worst-case data freshness). On one local electronic control
  unit (ECU), we present how to compute the exact local (worst-case) end-to-end
  latencies when the execution time of the periodic tasks is fixed. We further
  extend our analysis to globally asynchronized systems by combining the local
  results. Throughout synthesized data based on an automotive benchmark as well
  as on randomized parameters, we show that our analytical results improve the
  state-of-the-art for periodic task activations.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-05-18T09:17:19.066Z
---
