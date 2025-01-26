---
title: Evaluating the Impact of Racetrack Memory Misalignment Faults on BNNs
  Performance
publication_types:
  - "1"
authors:
  - Leonard David Bereholschi
  - Mikail Yayla
  - Jian-Jia Chen
  - Kuan-Hsun Chen
  - Asif Ali Khan
publication: "International Conference on Embedded Computer Systems:
  Architectures, Modeling and Simulation"
publication_short: SAMOS
abstract: >-
  Racetrack memory (RTM) is a promising non-volatile memory (NVM) technology
  that offers exceptional density, power and performance benefits over other NVM
  and conventional memory technologies. RTM cells have the unique capability of
  storing hundreds of data bits per cell and are equipped with one or more
  access ports. However, accessing data in an RTM cell requires the data to be
  shifted and aligned to an access port, introducing performance and energy
  overheads and potentially leading to misalignment faults. A misalignment fault
  occurs

  when after the shift operation, the desired data is not properly aligned to an access port and incorrect data is read from the RTM cell. Countermeasures have been proposed to mitigate the effects of these faults on applications’ accuracy, albeit at the cost of increased overhead. There is potential to balance the trade-offs between acceptable drops in accuracy and enhancements in performance, especially in error-resilient applications such as Binarized Neural Networks (BNNs). However, there exists no tool that enables effective exploration of this design space and assess the potential trade-offs. 

  This paper introduces NetDrift, a framework which facilitates investigation into the impact of RTM misalignment faults on BNNs accuracy at finer granularities. It enables controlled error injection in selected BNN layers with varying fault rates and simulates the impact of accumulated errors in weight tensors of several BNN models (FashionMNIST, CIFAR10, ResNet18) stored in RTM. The framework allows for tuning reliability for performance and vice versa, providing an estimate of the number of inference iterations required for a BNN model to drop below a certain lower threshold, with no protection, limited protection, and full protection, along with the associated impact on performance. The tool is openly available on Github.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2025-01-26T18:08:57.183Z
---
