---
title: "LazyTick: Lazy and Efficient Management of Job Release in  Real-Time
  Operating Systems"
subtitle: In Press
publication_types:
  - "2"
  - "1"
authors:
  - Kay Heider
  - Christian Hakert
  - Kuan-Hsun Chen
  - Jian-Jia Chen
publication: ACM SIGBED International Conference on Embedded Software (EMSOFT 2025)
publication_short: EMSOFT 2025
abstract: Releasing jobs and performing scheduling decisions in real-time
  operating systems (RTOSes) is often realized within tick interrupts. In each
  tick interrupt, a set of tasks that are waiting to release new jobs, namely
  the waiting set, is inspected to determine the jobs that should be released at
  this tick. Such a waiting set is sorted whenever a job has finished, by which
  the release process can be efficiently achieved. However, the overhead of
  sorting can vary vastly depending on the task set, which has to be taken into
  account in the worst-case timing analysis. Moreover, the tick interrupt in
  common practices is backed by a single hardware timer that is configured to
  trigger interrupts, either with a fixed period or reconfigured to the next
  release time (so-called one-shot timer). Since not necessarily at every
  interrupt a job will be released, several tick interrupts might be redundant.
  For the one-shot timers, the reconfiguration during runtime also incurs
  overheads at a variable interval. To reduce such variability and amount of
  overhead, in this work, we propose LazyTick which partitions the task set and
  distributes the subsets over multiple timers. Specifically, we propose two job
  release procedures with constant operations overhead—one for harmonic task
  sets and one for non-harmonic task sets. We implemented the support for
  multiple hardware timers in FreeRTOS and conducted intensive experimental
  evaluations. The evaluation shows that LazyTick can reduce the variability in
  overhead by up to ≈5× in peak and ≈3× on average in comparison to the default
  implementation. Additionally, the combined overhead of the job release process
  is reduced by up to ≈6.1× in peak and ≈3.6× on average.
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2025-07-22T11:33:40.718Z
---
