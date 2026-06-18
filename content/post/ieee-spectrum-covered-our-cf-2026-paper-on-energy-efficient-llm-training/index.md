---
title: IEEE Spectrum covered our CF 2026 paper on energy-efficient LLM training
date: 2026-06-18T11:34:28.825Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Nice news from our group: the work of my PhD student Jeffrey Spaan, presented at Computing Frontiers 2026, was recently covered by IEEE Spectrum.

The paper studies how dynamic voltage and frequency scaling can be used during LLM training to reduce GPU energy consumption. Instead of applying frequency changes only at a coarse training-iteration level, the work explores more fine-grained adjustments at the kernel level. In the reported experiments, this led to up to 14% energy savings with only a very small impact on training time.

I am very happy to see Jeffrey’s work receiving this attention. The topic is also a good example of the kind of systems research I find important: looking carefully at where computing resources are wasted, and then designing practical mechanisms to reduce this waste without sacrificing performance.

Congratulations to Jeffrey and all co-authors!

Link: <https://spectrum.ieee.org/llm-training-energy-saving-trick>[](<>)