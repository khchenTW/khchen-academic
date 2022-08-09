---
title: Overrun Handling for Mixed-Criticality Support in RTEMS
publication_types:
  - "1"
authors:
  - Kuan-Hsun Chen
  - Georg Von Der Brüggen
  - Jian-Jia Chen
publication: Workshop on Mixed Criticality Systems
publication_short: Workshop on Mixed Criticality Systems
abstract: Real-time operating systems are not only used in embedded real-time
  systems but also useful for the simulation and validation of those systems.
  During the evaluation of our paper about Systems with Dynamic Real-Time
  Guarantees that appears in RTSS 2016 we discovered certain unexpected system
  behavior in the open-source real-time operating system RTEMS. In the current
  implementation of RTEMS (version 4.11), overruns of an implicit-deadline task,
  i.e., deadline misses, result in unexpected system behavior as they may lead
  to a shift of the release pattern of the task. This also has the consequence
  that some task instances are not released as they should be. In this paper we
  explain the reason why such problems occur in RTEMS and our solutions.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2016-11-19T17:19:12.571Z
---
