---
title: " Timing-Aware ROS2 Architecture and System Optimization"
publication_types:
  - "1"
authors:
  - Harun Teper
  - Tobias Betz
  - Georg von der Brüggen
  - Kuan-Hsun Chen
  - Johannes Betz
  - Jian-Jia Chen
publication: "The 29th IEEE International Conference on Embedded and Real-Time
  Computing Systems and Applications "
publication_short: RTCSA
abstract: ROS2 is a set of software libraries for developing robot applications,
  such as autonomous driving systems, that consist of multiple interacting
  components. In ROS2, each component is implemented as a node, which contains
  time-triggered and event-triggered tasks. These tasks communicate either via
  ROS2 topics or shared memory, and are scheduled by a ROS2 executor. In ROS2
  systems, the system configuration and callback execution can have significant
  impact on system performance, including end-to-end latencies, message loss,
  and memory usage. In this paper, we provide a bound on the timer period of
  ROS2 timers to prevent sensor undersampling, and a subscription buffer size
  limit that prevents message loss and minimizes memory usage. Furthermore, we
  explain the occurrence of message loss and high end-to-end latencies in ROS2
  systems, which are caused by the system configuration and subscription buffer
  size choice. Based on our observations, we propose a heuristic for callback
  prioritization and an executor callback prioritization that can be applied to
  existing systems to reduce end-to-end latencies and subscription buffer sizes.
  We demonstrate our findings using case studies based on Autoware.Universe and
  provide further evaluation to highlight the benefits of our heuristic.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-06-03T13:36:36.299Z
---
