---
title: Paper accepted in FPT 2023
date: 2023-11-15T11:27:20.731Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
C﻿ongratulations to Frank Ridder and Nikolaos Alachiotis that our paper “Accelerated Real-Time Classification of Evolving Data Streams using Adaptive Random Forests” is accepted by FPT 2023!

Machine learning is increasingly applied to a wide range of real-time applications, with classification tasks playing a critical role in enabling intelligent decision-making. However, the phenomenon of concept drift, where the underlying data
distribution changes over time, presents a significant challenge to maintaining the accuracy of machine learning models in applications with evolving data streams such as health monitoring or sensor-data analyses. 

The Adaptive Random Forest (ARF), as one prominent algorithm addresses this issue by coupling multiple Hoeffding Trees with a drift detector to adapt to concept drift. As training a forest of growing decision trees is a high-latency operation,
custom-hardware acceleration is needed to meet the stringent latency requirements for real-time use of ARF. This work describes the first FPGA implementation of the ARF algorithm, focusing on achieving high hardware efficiency, scalability, and adaptability for four different datasets. 