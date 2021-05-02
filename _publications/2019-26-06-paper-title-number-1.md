---
title: "Hadanets: Flexible quantization strategies for neural networks"
collection: publications
permalink: /publication/2019-26-06-paper-title-number-1
excerpt: 'HadaNets introduce a flexible train-from-scratch tensor quantization scheme by pairing a full precision tensor to a binary tensor in the form of a Hadamard product.'
date: 2019-26-06
venue: 'IEEE'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9025370'
citation: 'Akhauri, Y. (2019). HadaNets: Flexible Quantization Strategies for Neural Networks. 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW).'
---
On-board processing elements on UAVs are currently inadequate for training and inference of Deep Neural Networks. This is largely due to the energy consumption of memory accesses in such a network. HadaNets introduce a flexible train-from-scratch tensor quantization scheme by pairing a full precision tensor to a binary tensor in the form of a Hadamard product. Unlike wider reduced precision neural network models, we preserve the train-time parameter count, thus out-performing XNOR-Nets without a train-time memory penalty. Such training routines could see great utility in semi-supervised online learning tasks. Our method also offers advantages in model compression, as we reduce the model size of ResNet-18 by 7.43 times with respect to a full precision model without utilizing any other compression techniques. We also demonstrate a 'Hadamard Binary Matrix Multiply' kernel, which delivers a 10-fold increase in performance over full precision matrix multiplication with a similarly optimized kernel.

[Download paper here](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9025370)

Recommended citation: Akhauri, Y. (2019). HadaNets: Flexible Quantization Strategies for Neural Networks. 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW).

