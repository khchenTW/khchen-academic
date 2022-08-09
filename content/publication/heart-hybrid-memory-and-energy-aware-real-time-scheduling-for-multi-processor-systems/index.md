---
title: "HEART: Hybrid Memory and Energy-Aware Real-Time Scheduling for
  Multi-Processor Systems"
publication_types:
  - "2"
authors:
  - Mario Günzel
  - Christian Hakert
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: https://doi.org/10.1145/3477019
publication: ACM Transactions on Embedded Computing Systems (TECS)
publication_short: ACM Transactions on Embedded Computing Systems (TECS)
abstract: >-
  Dynamic power management (DPM) reduces the power consumption of a computing
  system when it idles, by switching the system into a low power state for
  hibernation. When all processors in the system share the same component, e.g.,
  a shared memory, powering off this component during hibernation is only
  possible when all processors idle at the same time. For a real-time system,
  the schedulability property has to be guaranteed on every processor,
  especially if idle intervals are considered to be actively introduced.


  In this work, we consider real-time systems with hybrid shared-memory architectures, which consist of shared volatile memory (VM) and non-volatile memory (NVM). Energy-efficient execution is achieved by applying DPM to turn off all memories during the hibernation mode. Towards this, we first explore the hybrid memory architectures and suggest a task model, which features configurable hibernation overheads. We propose a multi-processor procrastination algorithm (HEART), based on partitioned earliest-deadline-first (pEDF) scheduling. Our algorithm facilitates reducing the energy consumption by actively enlarging the hibernation time. It enforces all processors to idle simultaneously without violating the schedulability condition, such that the system can enter the hibernation state, where shared memories are turned off. Throughout extensive evaluation of HEART, we demonstrate (1) the increase in potential hibernation time, respectively the decrease in energy consumption, and (2) that our algorithm is not only more general but also has better performance than the state of the art with respect to energy efficiency in most cases.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-09-22T11:48:32.937Z
---
