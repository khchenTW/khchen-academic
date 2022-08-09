---
title: "Shared-resource-centric limited preemptive scheduling: A comprehensive
  study of suspension-based partitioning approaches"
publication_types:
  - "1"
authors:
  - Zheng Dong
  - Cong Liu
  - Soroush Bateni
  - Kuan-Hsun Chen
  - Jian-Jia Chen
  - Georg von der Brüggen
  - Junjie Shi
doi: 10.1109/RTAS.2018.00026
publication: IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS)
publication_short: IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS)
abstract: This paper studies the problem of scheduling a set of hard real-time
  sporadic tasks that may access CPU cores and a shared resource. Motivated by
  the observation that the CPU resource is often abundant compared to the shared
  resources in multi-core and many-core systems, we propose to resolve this
  problem from a counter-intuitive shared-resource-centric perspective, focusing
  on judiciously prioritizing and scheduling tasks' requests in a limited
  preemptive manner on the shared resource while viewing the worst-case latency
  a task may experience on the CPU cores as suspension delays. We develop a
  rather comprehensive set of task partitioning algorithms that partition tasks
  onto the shared resource with the objective of guaranteeing schedulability
  while minimizing the required size of the shared resource, which plays a
  critical role in reducing the overall cost and complexity of building
  resource-constrained embedded systems in many application domains. A GPU-based
  prototype case study and extensive simulation-based experiments have been
  conducted, which validate both our shared-resource-centric scheduling
  philosophy and the efficiency of our suspension-based partitioning solutions
  in practice.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2018-04-11T10:49:52.382Z
---
