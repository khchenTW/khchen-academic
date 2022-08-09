---
title: Probabilistic schedulability tests for uniprocessor fixed-priority
  scheduling under soft errors
publication_types:
  - "1"
authors:
  - Kuan-Hsun Chen
  - Jian-Jia Chen
doi: 10.1109/SIES.2017.7993392
publication: 12th IEEE International Symposium on Industrial Embedded Systems (SIES)
publication_short: 12th IEEE International Symposium on Industrial Embedded Systems (SIES)
abstract: Due to rising integrations, low voltage operations, and environmental
  influences such as electromagnetic interference and radiation, transient
  faults may cause soft errors and corrupt the execution state. Such soft errors
  can be recovered by applying fault-tolerant techniques. Therefore, the
  execution time of a job of a sporadic/periodic task may differ, depending upon
  the occurrence of soft errors and the applied error detection and recovery
  mechanisms. We model a periodic/sporadic real-time task under such a scenario
  by using two different worst-case execution times (WCETs), in which one is
  with the occurrence of soft errors and another is not. Based on a
  probabilistic soft-error model, the WCETs are hence with different
  probabilities. In this paper, we present efficient probabilistic
  schedulability tests that can be applied to verify the schedulability based on
  probabilistic arguments under fixed-priority scheduling on a uniprocessor
  system. We demonstrate how the Chernoff bounds can be used to calculate the
  task workloads based on their probabilistic WCETs. In addition, we further
  consider how to calculate the probability of `-consecutive deadline misses of
  a task. The pessimism and the efficiency of our approaches are evaluated
  against the tighter and approximated convolution-based approaches, by running
  extensive evaluations under different soft-error rates. The evaluation results
  show that our approaches are effective to derive the probability of deadline
  misses and efficient with respect to the needed calculation time.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2017-06-14T10:54:07.136Z
---
