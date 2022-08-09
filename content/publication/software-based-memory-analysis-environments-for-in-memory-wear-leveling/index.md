---
title: Software-Based Memory Analysis Environments for In-Memory Wear-Leveling
publication_types:
  - "1"
authors:
  - Christian Hakert; Kuan-Hsun Chen; Mikail Yayla; Georg von der Brüggen;
    Sebastian Blömeke; Jian-Jia Chen
doi: 10.1109/ASP-DAC47756.2020.9045418
publication: 25th Asia and South Pacific Design Automation Conference (ASP-DAC)
publication_short: 25th Asia and South Pacific Design Automation Conference (ASP-DAC)
abstract: Emerging non-volatile memory (NVM) architectures are considered as a
  replacement for DRAM and storage in the near future, since NVMs provide low
  power consumption, fast access speed, and low unit cost. Due to the lower
  write-endurance of NVMs, several in-memory wear-leveling techniques have been
  studied over the last years. Since most approaches propose or rely on
  specialized hardware, the techniques are often evaluated based on assumptions
  and in-house simulations rather than on real systems. To address this issue,
  we develop a setup consisting of a gem5 instance and an NVMain2.0 instance,
  which simulates an entire system (CPU, peripherals, etc.) together with an NVM
  plugged into the system. Taking a recorded memory access pattern from a
  low-level simulation into consideration to design and optimize wear-leveling
  techniques as operating system services allows a cross-layer design of
  wear-leveling techniques. With the insights gathered by analyzing the recorded
  memory access patterns, we develop a software-only wear-leveling solution,
  which does not require special hardware at all. This algorithm is evaluated
  afterwards by the full system simulation.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2020-01-13T10:58:45.058Z
---
