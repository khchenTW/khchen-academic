---
title: Towards Enabling Synchronous Releases for Periodic Tasks in RTEMS
publication_types:
  - "3"
authors:
  - Tristan Seidl
  - Mario Günzel
  - Jian-Jia Chen
  - Kuan-Hsun Chen
publication: The 18th annual workshop on Operating Systems Platforms for
  Embedded Real-Time applications
publication_short: OSPERT
abstract: >-
  In addition to functional correctness, real-time systems offer temporal
  correctness which is important for safetycritical domains like avionics.
  Inherently, these systems deal with reoccurring functionality that can be
  modeled as periodic tasks. These task-sets are managed by specialized
  real-time operating systems (RTOS) because they feature predictability and
  advanced scheduling mechanisms. Within research, RTOSs are commonly used to
  evaluate analytical results.


  When periodic task-sets are analyzed in the literature, their fixed release pattern can be exploited analytically. Furthermore, if all tasks have constrained deadlines and release their first job synchronously, the schedulability can be determined by only analyzing the first job of each task. The well-established RTOS Real-Time Executive for Multiprocessor Systems (RTEMS) provides the specification of periodic tasks without task phases. Usually, without specification of phases, periodic tasks are considered synchronous. However, in this work, we demonstrate that RTEMS invokes task phases dependent on the task execution behavior. Hence, in RTEMS tasks are not released synchronously.  Furthermore, since periodic tasks do not even have a fixed release pattern, many analytical results for periodic tasks from the literature are not applicable. Our objective in this work is to shift RTEMS’ release strategy towards a fixed synchronous release of periodic task-sets with implicit deadlines. We propose two treatments that are implemented on kernel- and user-level respectively.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-07-07T22:13:34.237Z
---
