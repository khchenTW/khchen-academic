---
title: ETS 2026 Acceptance!
date: 2026-02-17T09:00:15.666Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
I’m excited to share that our paper **“Efficient Hash-to-Index via Rejection Sampling for Online Fault Detection with Bloom/Cuckoo Filters”** has been accepted at **ETS 2026**!

In this work, we revisit a classic idea — *rejection sampling* — and show how it can be used as a practical, hardware-efficient alternative to division or multiplication for mapping hashes to table indices. This enables:

* **Arbitrary table sizes** (no power-of-two constraint)
* **No division or DSP blocks**
* **Zero extra latency in hardware**

We integrate the approach into Bloom and Cuckoo filters on FPGA and show that it achieves comparable accuracy with significantly lower hardware cost — ideal for embedded and real-time systems.

👏 Congratulations to Elijah for leading this work — a very well-deserved achievement!