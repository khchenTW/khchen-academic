---
title: Analysis of deadline miss rates for uniprocessor fixed-priority scheduling
publication_types:
  - "1"
authors:
  - Kuan-Hsun Chen
  - Georg Von Der Brüggen
  - Jian-Jia Chen
doi: 10.1109/RTCSA.2018.00028
publication: IEEE 24th International Conference on Embedded and Real-Time
  Computing Systems and Applications (RTCSA)
publication_short: IEEE 24th International Conference on Embedded and Real-Time
  Computing Systems and Applications (RTCSA)
abstract: Timeliness is an important feature for many embedded systems. Although
  soft real-time embedded systems can tolerate and allow certain deadline
  misses, it is still important to quantify them to justify whether the
  considered systems are acceptable. In this paper, we provide a way to safely
  over-approximate the expected deadline miss rate for a specific sporadic
  real-time task under fixed-priority preemptive scheduling in uniprocessor
  systems. Our approach is compatible with the existing results in the
  literature that calculate the probability of deadline misses either based on
  the convolution-based approaches or analytically. We demonstrate our approach
  by considering randomly generated task sets with an execution behavior that
  simulates jobs that are subjected to soft errors incurred by hardware
  transient faults under a given fault rate. To empirically gather the deadline
  miss rates, we implemented an event-based simulator with a fault-injection
  module and release the scripts. With extensive simulations under different
  fault rates, we evaluate the efficiency and the pessimism of our approach. The
  evaluation results show that our approach is effective to derive an upper
  bound of the expected deadline miss rate and efficient with respect to the
  required computation time.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2018-08-28T10:36:21.692Z
---
