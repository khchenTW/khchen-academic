---
title: Supporting multiprocessor resource synchronization protocols in RTEMS
publication_types:
  - "2"
authors:
  - Junjie Shi
  - Jan Duy Thien Pham
  - Malte Münch
  - Jan Viktor Hafemeister
  - Jian-Jia Chen
  - Kuan-Hsun Chen
doi: arXiv:2104.06366
publication: arXiv preprint arXiv:2104.06366
publication_short: arXiv preprint arXiv:2104.06366
abstract: When considering recurrent tasks in real-time systems, concurrent
  accesses to shared resources, can cause race conditions or data corruptions.
  Such a problem has been extensively studied since the 1990s, and numerous
  resource synchronization protocols have been developed for both uni-processor
  and multiprocessor real-time systems, with the assumption that the
  implementation overheads are negligible. However, in practice, the
  implementation overheads may impact the performance of different protocols
  depending upon the practiced scenarios, e.g., resources are accessed locally
  or remotely, and tasks spin or suspend themselves when the requested resources
  are not available. In this paper, to show the applicability of different
  protocols in real-world systems, we detail the implementation of several
  state-of-the-art multiprocessor resource synchronization protocols in RTEMS.
  To study the impact of the implementation overheads, we deploy these
  implemented protocols on a real platform with synthetic task set. The measured
  results illustrate that the developed resource synchronization protocols in
  RTEMS are comparable to the existed protocol, i.e., MrsP.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-04-13T15:09:53.857Z
---
