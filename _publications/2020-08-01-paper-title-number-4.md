---
title: "LogicNets: Co-Designed Neural Networks and Circuits for Extreme-Throughput Applications"
collection: publications
permalink: /publication/2020-08-01-paper-title-number-4
excerpt: 'We present a novel method for designing neural network topologies that directly map to a highly efficient FPGA implementation.'
date: 2020-08-01
venue: 'IEEE'
paperurl: 'https://ieeexplore.ieee.org/document/9221584'
citation: 'Y. Umuroglu, Y. Akhauri, N. J. Fraser and M. Blott, "LogicNets: Co-Designed Neural Networks and Circuits for Extreme-Throughput Applications," 2020 30th International Conference on Field-Programmable Logic and Applications (FPL), 2020, pp. 291-297, doi: 10.1109/FPL50879.2020.00055.'
---
Deployment of deep neural networks for applications that require very high throughput or extremely low latency is a severe computational challenge, further exacerbated by inefficiencies in mapping the computation to hardware. We present a novel method for designing neural network topologies that directly map to a highly efficient FPGA implementation. By exploiting the equivalence of artificial neurons with quantized inputs/outputs and truth tables, we can train quantized neural networks that can be directly converted to a netlist of truth tables, and subsequently deployed as a highly pipelinable, massively parallel FPGA circuit. However, the neural network topology requires careful consideration since the hardware cost of truth tables grows exponentially with neuron fan-in. To obtain smaller networks where the whole netlist can be placed-and-routed onto a single FPGA, we derive a fan-in driven hardware cost model to guide topology design, and combine high sparsity with few-bit activation quantization to limit the neuron fan-in. We evaluate our approach on two tasks with very high intrinsic throughput requirements in high-energy physics and network intrusion detection. We show that the combination of sparsity and few-bit activation quantization results in high-speed circuits with small logic depth and low LUT cost, demonstrating competitive accuracy with less than 15 ns of inference latency and throughput in the hundreds of millions of inferences per second.
[Download paper here](https://ieeexplore.ieee.org/document/9221584)


Recommended citation: Y. Umuroglu, Y. Akhauri, N. J. Fraser and M. Blott, "LogicNets: Co-Designed Neural Networks and Circuits for Extreme-Throughput Applications," 2020 30th International Conference on Field-Programmable Logic and Applications (FPL), 2020, pp. 291-297, doi: 10.1109/FPL50879.2020.00055.