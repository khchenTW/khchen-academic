---
abstract: For cyber-physical systems, real-time virtualization optimizes the
  hardware utilization by consolidating multiple systems into the same platform,
  while satisfying the timing constraints of their real-time tasks. This paper
  considers virtualization based on unikernels, i.e., single address space
  kernels usually constructed by using library operating systems. Each unikernel
  is a guest operating system in the virtualization and hosts a single real-time
  task.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Kuan-Hsun Chen
  - Mario Günzel
  - Boguslaw Jablkowski
  - Markus Buschhoff
  - Jian-Jia Chen
author_notes: []
publication: In *34th Euromicro Conference on Real-Time Systems (ECRTS)*
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *34th Euromicro Conference on Real-Time Systems (ECRTS)*
url_source: ""
url_video: ""
title: "Unikernel-Based Real-Time Virtualization under Deferrable Servers:
  Analysis and Realization"
doi: 10.4230/LIPIcs.ECRTS.2022.6
featured: true
tags:
  - Open-Access
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2022-08-08T08:44:19.617Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
We consider deferrable servers in the virtualization platform to schedule the unikernel-based guest operating systems and analyze the worst-case response time of a sporadic real-time task under such a virtualization architecture. Throughout synthesized tasksets, we empirically show that our analysis outperforms the restated analysis derived from the state-of-the-art, which is based on Real-Time Calculus. Furthermore, we provide insights on implementation-specific issues and offer evidence that the proposed scheduling architecture can be effectively implemented on top of the Xen hypervisor while incurring acceptable overhead.