---
title: "OCTO+: Optimized Checkpointing of B+ Trees for Non-Volatile Main Memory
  Wear-Leveling"
publication_types:
  - "1"
authors:
  - Christian Hakert
  - Roland Kühn
  - Kuan-Hsun Chen
  - Jian-Jia Chen
  - Jens Teubner
doi: 10.1109/NVMSA53655.2021.9628460
publication: 10th Non-Volatile Memory Systems and Applications Symposium (NVMSA)
publication_short: 10th Non-Volatile Memory Systems and Applications Symposium (NVMSA)
abstract: Steady deployment of byte addressable non-volatile memories (NVMs) as
  main memory in server class computers yields challenges on software. In order
  to overcome shortcomings, as for instance low cell endurance and high access
  latencies, working data can be kept in DRAM and continuously be checkpointed
  to the NVM. Although this reduces the impact of the NVM on usual execution, it
  shifts the endurance and latency issue to the checkpointing. Alongside widely
  studied generic wear-leveling solutions, we propose an application cooperative
  wear-leveling scheme for B+ trees, that realizes an interplay of the
  application and the wear-leveling. We collect memory usage statistics during
  tree operations and dynamically choose a memory mapping between the DRAM
  footprint and the NVM checkpoint of the B+ tree. In an experimental
  evaluation, we achieve 3× improvement in terms of memory lifetime.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-08-18T09:34:26.372Z
---
