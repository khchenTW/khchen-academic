---
title: Scheduling Periodic Segmented Self-Suspending Tasks without Timing Anomalies
subtitle: Just accepted
publication_types:
  - "1"
authors:
  - Ching-Chi Lin
  - Mario Günzel
  - Junjie Shi
  - Tristan Taylan Seidl
  - Kuan-Hsun Chen
  - Jian-Jia Chen
publication: IEEE Real-Time and Embedded Technology and Applications Symposium
publication_short: RTAS'23
abstract: >-
  Timing guarantee is an important aspect and must be ensured for every
  individual task in real-time systems. Even for periodic tasks, providing
  timing guarantees for segmented self-suspending tasks is challenging due to
  timing anomalies, i.e., the reduction of execution or suspension time of some
  jobs enlarges the response time of another job. The existing worst-case
  response time analyses for sporadic self-suspending tasks are only
  over-approximations and lead to overly pessimistic results. 


  In this paper, we focus on eliminating timing anomalies without negative impacts on the worst-case response time (WCRT) analysis when scheduling periodic tasks with segmented self-suspension behavior. We propose two treatments, segment release time enforcement and segment priority modification, and prove that both treatments eliminate timing anomalies. In our evaluation, the proposed treatments achieve higher acceptance ratios in terms of schedulability compared to state-of-the-art scheduling algorithms. We also implement the segment-level fixed-priority scheduling mechanism on RTEMS, and showcase the validity of the treatment segment priority modification.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-02-12T09:58:55.470Z
---
