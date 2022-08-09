---
title: Reliability optimization on multi-core systems with multi-tasking and
  redundant multi-threading
publication_types:
  - "2"
authors:
  - Kuan-Hsun Chen
  - Georg von der Brüggen
  - Jian-Jia Chen
doi: 10.1109/TC.2017.2769044
publication: IEEE Transactions on Computers
publication_short: IEEE Transactions on Computers
abstract: Using Redundant Multithreading (RMT) for error detection and recovery
  is a prominent technique to mitigate soft-error effects in multi-core systems.
  Simultaneous Redundant Threading (SRT) on the same core or Chip-level
  Redundant Multithreading (CRT) on different cores can be adopted to implement
  RMT. However, only a few previously proposed approaches use adaptive CRT
  managements on the system level and none of them considers both SRT and CRT on
  the task level. In this paper, we propose to use a combination of SRT and CRT,
  called Mixed Redundant Threading (MRT), as an additional option on the task
  level. In our coarse-grained approach, we consider SRT, CRT, and MRT on the
  system level simultaneously, while the existing results only apply either SRT
  or CRT on the system level, but not simultaneously. In addition, we consider
  further fine-grained task level optimizations to improve the system
  reliability under hard real-time constraints. To optimize the system
  reliability, we develop several dynamic programming approaches to select the
  redundancy levels under Federated Scheduling. The simulation results
  illustrate that our approaches can significantly improve the system
  reliability compared to the state-of-the-art techniques.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2017-11-02T17:11:19.489Z
---
