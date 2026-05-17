---
title: Presenting Our Work on Care-Taking Tasks at RTAS 2026
abstract: >-
  I was delighted to participate in RTAS 2026, the 32nd IEEE Real-Time and
  Embedded Technology and Applications Symposium, held as part of CPS-IoT Week
  2026 in Saint-Malo, France. RTAS is one of the leading venues for research on
  systems with timing requirements, covering methodologies, tools, algorithms,
  operating systems, middleware, and hardware/software innovations for
  time-critical systems.


  Saint-Malo provided a wonderful setting for the event. The city’s historic walled old town, narrow streets, sea views, and distinctive maritime atmosphere made the symposium experience especially memorable. Beyond the technical program, it was a pleasure to spend time in such a charming coastal city and to enjoy informal discussions with colleagues in this unique setting.


  At RTAS 2026, I presented our paper “Releaser Design and Schedulability Analysis for Care-Taking Tasks in Real-Time Systems” in Session 2: Scheduling, chaired by Eduardo Tovar. The paper is joint work with Nils Hölscher, Kay Heider, Georg von der Brüggen, Mario Günzel, and Jian-Jia Chen.


  The work studies an important but often implicit phenomenon in cyber-physical and embedded real-time systems: many systems include not only high-frequency control tasks, but also less frequent tasks that “take care” of shared resources or system components. Examples include sensor calibration and wear-leveling for endurance-limited memories. Although these care-taking activities are executed less frequently, they may still block or interfere with real-time tasks, and poor release timing can lead to unnecessary deadline misses.


  In the talk, I discussed how we model such care-taking tasks, how conventional schedulability analysis can be extended to account for them, and why a straightforward worst-case treatment can be overly pessimistic. The key idea of our approach is to exploit the release-time flexibility of care-taking tasks: instead of allowing multiple care-taking jobs to cluster and create interference spikes, we introduce a notion of sparsity and design a low-overhead releaser that spreads these jobs over time.


  Our results show that this sparse-release perspective can improve schedulability analysis compared with more direct approaches. We also implemented the proposed releaser in FreeRTOS and evaluated its overhead, supporting the practicality of the design.


  Many thanks to my co-authors for the collaboration, to the RTAS organizers for putting together an excellent program, and to the audience for the engaging questions and feedback.


  Photo credit: Mario Günzel.
location: CPS-IoT Week 2026 in Saint-Malo, France
date: 2026-05-12T12:20:03.920Z
date_end: 2026-05-12T12:50:56.802Z
all_day: false
event: IEEE Real-Time and Embedded Technology and Applications Symposium
event_url: https://2026.rtas.org/program/
publishDate: 2026-05-17T10:48:26.486Z
draft: false
featured: false
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
