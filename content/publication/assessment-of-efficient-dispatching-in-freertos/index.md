---
title: " Assessment of Efficient Dispatching in FreeRTOS"
publication_types:
  - "3"
authors:
  - Florian Hagens
  - Kuan-Hsun Chen
publication: The 17th annual workshop on Operating Systems Platforms for
  Embedded Real-Time applications
publication_short: OSPERT
abstract: This study investigates the efficiency of task dispatchers in
  real-world implementations. We focus on evaluating various task dispatching
  methods based on five distinct data structures and their impact on computation
  overhead and performance in FreeRTOS. By using a real-world setup, we analyze
  the merits and drawbacks of each data structure and corresponding task
  dispatcher implementation. Our preliminary findings suggest that task
  dispatcher efficiency highly depends on the task set size and their respective
  periods, with alternative dispatchers potentially outperforming the List-based
  implementation, which is presently utilized in FreeRTOS, in certain scenarios.
  Ultimately, this study seeks to provide valuable insights for system designers
  and developers, emphasizing the importance of tailoring task dispatchers to
  specific task sets for improved efficiency and reliability in real-time
  systems.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-06-03T13:34:37.921Z
---
