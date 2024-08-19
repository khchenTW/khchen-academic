---
title: Lightweight Instrumentation for Accurate Performance Monitoring in RTOSes
publication_types:
  - "1"
authors:
  - Bruno Endres Forlin
  - Kuan-Hsun Chen
  - Nikolaos Alachiotis
  - Luca Cassano
  - Marco Ottavi
publication: Design, Automation & Test in Europe Conference & Exhibition
publication_short: ""
abstract: >-
  Evaluating performance metrics in embedded systems poses challenges,
  particularly due to the limited set of

  tools available for monitoring performance counters. In addition, performance evaluation frameworks for Real-Time Operating Systems (RTOSes) often lack the sophistication and capabilities available in general-purpose operating systems like Linux, which benefit from utilities such as perf_event. To bridge this gap, this paper presents an accurate and low-overhead instrumentation utility tailored for RTOSes. Our approach utilizes performance monitoring counters to observe individual user applications within the RTOS environment. Importantly, it enables comprehensive application monitoring by strategically placing probes at points of inherent system interference, thereby minimizing additional overhead. A pre-calibration of these probes allows for fine-rained measurements within user applications. This results in the elimination of 100% of the overheads for most counters in our test configuration, impacting the context switch by only three additional instructions per monitored counter.
draft: false
featured: true
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-03-24T23:01:37.125Z
---
