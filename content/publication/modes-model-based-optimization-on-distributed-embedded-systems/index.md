---
title: "MODES: model-based optimization on distributed embedded systems"
publication_types:
  - "2"
authors:
  - Junjie Shi
  - Jiang Bian
  - Jakob Richter
  - Kuan-Hsun Chen
  - Jörg Rahnenführer
  - Haoyi Xiong
  - Jian-Jia Chen
doi: https://doi.org/10.1007/s10994-021-06014-6
publication: Machine Learning
publication_short: Machine Learning
abstract: "The predictive performance of a machine learning model highly depends
  on the corresponding hyper-parameter setting. Hence, hyper-parameter tuning is
  often indispensable. Normally such tuning requires the dedicated machine
  learning model to be trained and evaluated on centralized data to obtain a
  performance estimate. However, in a distributed machine learning scenario, it
  is not always possible to collect all the data from all nodes due to privacy
  concerns or storage limitations. Moreover, if data has to be transferred
  through low bandwidth connections it reduces the time available for tuning.
  Model-Based Optimization (MBO) is one state-of-the-art method for tuning
  hyper-parameters but the application on distributed machine learning models or
  federated learning lacks research. This work proposes a framework MODES that
  allows to deploy MBO on resource-constrained distributed embedded systems.
  Each node trains an individual model based on its local data. The goal is to
  optimize the combined prediction accuracy. The presented framework offers two
  optimization modes: (1) MODES-B considers the whole ensemble as a single black
  box and optimizes the hyper-parameters of each individual model jointly, and
  (2) MODES-I considers all models as clones of the same black box which allows
  it to efficiently parallelize the optimization in a distributed setting. We
  evaluate MODES by conducting experiments on the optimization for the
  hyper-parameters of a random forest and a multi-layer perceptron. The
  experimental results demonstrate that, with an improvement in terms of mean
  accuracy (MODES-B), run-time efficiency (MODES-I), and statistical stability
  for both modes, MODES outperforms the baseline, i.e., carry out tuning with
  MBO on each node individually with its local sub-data set."
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-06-04T11:41:22.374Z
---
