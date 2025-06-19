---
title: Best Paper Nomination at Euro-Par 2025
subtitle: Wedge-Parallel Triangle Counting for GPUs
date: 2025-06-19T09:40:32.326Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
I’m thrilled to share that our recent paper, led by my PhD student Jeffrey Spaan (co-supervised with Ana-Lucia Varbanescu), has received a **Best Paper Nomination** at European Conference on Parallel Processing (Euro-Par 2025)! 🏆

**Paper Title:** *Wedge-Parallel Triangle Counting for GPUs*\
**Authors:**  Jeffrey Spaan, Kuan-Hsun Chen, David A. Bader and Ana-Lucia Varbanescu

### 🔍 What’s the paper about?

Triangle counting is a fundamental task in graph analytics, used in community detection, link prediction, and more. However, making it efficient on GPUs—despite their massive parallel processing power—is far from trivial due to the irregular nature of real-world graphs.

In this paper, we present **WeTriC**, a novel **wedge-parallel** triangle counting algorithm designed specifically for GPU architectures. Unlike traditional vertex- or edge-parallel strategies, WeTriC maps *wedges*—two-hop paths that may form triangles—directly to GPU threads using a lightweight static strategy that drastically improves load balancing and parallel efficiency.

### ⚙️ Why is it special?

* 📌 **Fine-grained parallelism** for better GPU utilization
* 🧠 **Theoretical analysis** of different parallelization strategies
* ⚡ **Optimizations** that reduce memory overhead and improve cache locality
* 🚀 **Substantial speedups** over existing methods:

  * **5.63×** faster than vertex-parallel baseline
  * **4.69×** faster than edge-parallel binary search method
  * **2.86×** faster than Trust
  * **2.32×** faster than GroupTC

### 🏅 Why it matters?

WeTriC pushes the boundary of efficient GPU-based graph analytics, especially for large-scale graph datasets. The work highlights how algorithmic design and hardware-aware optimizations go hand-in-hand to achieve state-of-the-art performance.

I am incredibly proud of Jeffrey Spaan and the team for this outstanding recognition! 🎉

Stay tuned for more details once the paper is presented at Euro-Par 2025.

- - -