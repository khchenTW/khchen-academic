---
title: CF 2026 Acceptance!
date: 2026-03-09T13:19:18.968Z
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
<!--StartFragment-->

I’m happy to share that our paper **“How Much Energy Is Wasted in LLM Operations? Evidence from Kernel-Level DVFS”** has been accepted at the **ACM International Conference on Computing Frontiers**.

This work is led by my PhD student **Jeffrey Spaan**, co-supervised with **Ana-Lucia Varbanescu**. In this paper, we study **energy waste in Large Language Model (LLM) operations** running on GPU-based systems.

Reducing the energy consumption of LLM workloads has become an important challenge as AI infrastructure continues to scale. A commonly used technique is **Dynamic Voltage and Frequency Scaling**, which lowers hardware frequency to save energy. However, existing approaches typically apply DVFS at coarse granularity (e.g., per iteration or per training pass), which often leads to noticeable slowdowns.

In this work, we explore a **fine-grained, kernel-level DVFS strategy** that adjusts GPU frequency configurations for individual kernels during LLM training. Our experiments show that this approach can significantly reduce energy waste while maintaining performance. For example, in a GPT-3 training scenario, pass-level DVFS reduces energy consumption by about **2% without performance loss**, while our **kernel-level approach achieves up to 14.6% energy savings with only a 0.6% slowdown**. We also show that the discovered frequency configurations translate well across both **data parallelism and tensor parallelism**.

Overall, this work highlights that **substantial energy waste still exists in current LLM operations**, and that **kernel-level DVFS can reduce this waste with negligible performance impact**.

<!--EndFragment-->