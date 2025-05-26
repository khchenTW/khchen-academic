---
title: Talk at CompSys 2025
abstract: >-
  Last week I was in CompSys 2025 at Utrecht in the Netherlands to present our
  work, entitled "InTreeger: An End-to-End Framework for Integer-Only Decision
  Tree Inference". It is a joint work, initialized by two PhD students Duncan
  Bart and Bruno Endes Forlin, together with my colleagues Ana-Lucia Varbanescu
  and Marco Ottavi. It provides an easy-to-use framework for tree-based
  ensembles, which generates interger-only implementations in standalone C
  without fancy libraries. We believe it has the potential to save application
  domain experts a lot of time and effort, as it automates processes that can be
  quite time-consuming for people without experience dealing with various tools,
  such as finding the right training methods, fixing dependencies, or optimizing
  the inference process.


  Integer quantization has emerged as a critical technique to facilitate deployment on resource-constrained devices. Although they do reduce the complexity of the learning models, their inference performance is often prone to quantization-induced errors. To this end, we introduce InTreeger: an end-to-end framework that takes a training dataset as input, and outputs an architecture-agnostic integer-only C implementation of tree-based machine learning model, without loss of precision. This framework enables anyone, even those without prior experience in machine learning, to generate a highly optimized integer-only classification model that can run on any hardware simply by providing an input dataset and target variable. We evaluated our generated implementations across three different architectures (ARM, x86, and RISC-V), resulting in significant improvements in inference latency. In addition, we show the energy efficiency compared to typical decision tree implementations that rely on floating-point arithmetic. The results underscore the advantages of integer-only inference, making it particularly suitable for energy- and area-constrained devices such as embedded systems and edge computing platforms, while also enabling the execution of decision trees on existing ultra-low power devices.


  Photo credited to Mitra Nasri. You can read the original paper here on https://arxiv.org/html/2505.15391v1
location: Carlton President Hotel in Utrecht
date: 2025-05-22T10:00:41.713Z
date_end: 2025-05-22T10:15:00.000Z
all_day: true
event: CompSys 2025
event_url: https://www.compsys.science/conference/current/pages/program/
publishDate: 2025-05-26T13:29:42.849Z
draft: false
featured: false
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
