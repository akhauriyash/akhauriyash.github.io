---
title: "Exposing Hardware Building Blocks to Machine Learning Frameworks"
collection: arXiv
permalink: /publication/2020-10-04-paper-title-number-2
excerpt: ' In this thesis, we explore how niche domains can benefit vastly if we look at neurons as a unique boolean function of the form f:BI→BO, where B={0,1}.'
date: 2019-26-06
venue: 'IEEE'
paperurl: 'https://arxiv.org/pdf/2004.05898.pdf'
citation: 'Akhauri, Y. (2019). Exposing Hardware Building Blocks to Machine Learning Frameworks.'
---
There are a plethora of applications that demand high throughput and low latency algorithms leveraging machine learning methods. This need for real time processing can be seen in industries ranging from developing neural network based pre-distortors for enhanced mobile broadband to designing FPGA-based triggers in major scientific efforts by CERN for particle physics. In this thesis, we explore how niche domains can benefit vastly if we look at neurons as a unique boolean function of the form f:BI→BO, where B={0,1}. We focus on how to design topologies that complement such a view of neurons, how to automate such a strategy of neural network design, and inference of such networks on Xilinx FPGAs. Major hardware borne constraints arise when designing topologies that view neurons as unique boolean functions. Fundamentally, realizing such topologies on hardware asserts a strict limit on the 'fan-in' bits of a neuron due to the doubling of permutations possible with every increment in input bit-length. We address this limit by exploring different methods of implementing sparsity and explore activation quantization. Further, we develop a library that supports training a neural network with custom sparsity and quantization. This library also supports conversion of trained Sparse Quantized networks from PyTorch to VERILOG code which is then synthesized using Vivado, all of which is part of the LogicNet tool-flow. To aid faster prototyping, we also support calculation of the worst-case hardware cost of any given topology. We hope that our insights into the behavior of extremely sparse quantized neural networks are of use to the research community and by extension allow people to use the LogicNet design flow to deploy highly efficient neural networks.

[Download paper here](https://arxiv.org/pdf/2004.05898.pdf)

