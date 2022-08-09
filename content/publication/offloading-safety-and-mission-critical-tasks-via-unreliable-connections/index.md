---
title: Offloading safety-and mission-critical tasks via unreliable connections
publication_types:
  - "1"
authors:
  - Lea Schönberger
  - Georg von der Brüggen
  - Kuan-Hsun Chen
  - Benjamin Sliwa
  - Hazem Youssef
  - Aswin Karthik Ramachandran Venkatapathy
  - Christian Wietfeld
  - Michael ten Hompel
  - Jian-Jia Chen
doi: 10.4230/LIPIcs.ECRTS.2020.18
publication: 32nd Euromicro Conference on Real-Time Systems (ECRTS 2020)
publication_short: 32nd Euromicro Conference on Real-Time Systems (ECRTS 2020)
abstract: For many cyber-physical systems, e.g., IoT systems and autonomous
  vehicles, offloading workload to auxiliary processing units has become
  crucial. However, since this approach highly depends on network connectivity
  and responsiveness, typically only non-critical tasks are offloaded, which
  have less strict timing requirements than critical tasks. In this work, we
  provide two protocols allowing to offload critical and non-critical tasks
  likewise, while providing different service levels for non-critical tasks in
  the event of an unsuccessful offloading operation, depending on the respective
  system requirements. We analyze the worst-case timing behavior of the local
  cyber-physical system and, based on these analyses, we provide a sufficient
  schedulability test for each of the proposed protocols. In the course of
  comprehensive experiments, we show that our protocols have reasonable
  acceptance ratios under the provided schedulability tests. Moreover, we
  demonstrate that the system behavior under our proposed protocols is strongly
  dependent on probability of unsuccessful offloading operations, the percentage
  of critical tasks in the system, and the amount of offloaded workload.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-06-30T10:02:33.202Z
---
