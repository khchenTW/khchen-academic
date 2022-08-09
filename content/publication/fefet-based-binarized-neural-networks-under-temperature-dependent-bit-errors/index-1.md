---
title: FeFET-based Binarized Neural Networks Under Temperature-dependent Bit Errors
publication_types:
  - "2"
authors:
  - Mikail Yayla
  - Sebastian Buschjager
  - Aniket Gupta
  - Jian-Jia Chen
  - Jorg Henkel
  - Katharina Morik
  - Kuan-Hsun Chen
  - Hussam Amrouch
doi: 10.1109/TC.2021.3104736
publication: IEEE Transactions on Computers
publication_short: IEEE Transactions on Computers
abstract: "Ferroelectric FET (FeFET) is a highly promising emerging non-volatile
  memory (NVM) technology, especially for binarized neural network (BNN)
  inference on the low-power edge. The reliability of such devices, however,
  inherently depends on temperature. Hence, changes in temperature during run
  time manifest themselves as changes in bit error rates. In this work, we
  reveal the temperature-dependent bit error model of FeFET memories, evaluate
  its effect on BNN accuracy, and propose countermeasures. We begin on the
  transistor level and accurately model the impact of temperature on bit error
  rates of FeFET. This analysis reveals temperature-dependent asymmetric bit
  error rates. Afterwards, on the application level, we evaluate the impact of
  the temperature-dependent bit errors on the accuracy of BNNs. Under such bit
  errors, the BNN accuracy drops to unacceptable levels when no countermeasures
  are employed. We propose two countermeasures: (1) Training BNNs for bit error
  tolerance by injecting bit flips into the BNN data, and (2) applying a bit
  error rate assignment algorithm (BERA) which operates in a layer-wise manner
  and does not inject bit flips during training. In experiments, the BNNs, to
  which the countermeasures are applied to, effectively tolerate
  temperature-dependent bit errors for the entire range of operating
  temperature."
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-08-13T11:39:53.129Z
---
