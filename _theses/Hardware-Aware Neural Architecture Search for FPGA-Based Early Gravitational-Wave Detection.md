---
layout: post
title: "Hardware-Aware Neural Architecture Search for FPGA-Based Early Gravitational-Wave Detection"
inline: false
related_posts: false
tags: ["2026", applied, FPGA, GW]
---

<i>This project will be performed in collaboration with Dr. Angela Cratere (DACS, Maastricht University) and Dr. Melissa Lopez (Nikhef National Institute for Subatomic Physics)</i>

<h3>Objective</h3>

The early detection of gravitational waves (GWs) from binary neutron star (BNS) inspirals is crucial for enabling rapid electromagnetic follow-up and multi-messenger observations. The increasing sensitivity of current and future GW detectors is expected to reveal more BNS events, creating a growing need for accurate, fast and computationally efficient search algorithms. One promising approach is to accelerate deep learning (DL) models on FPGAs. Previous work developed GWaveNet [1], a DL model for detecting weak inspiral signals, and investigated its deployment on an FPGA using AMD Vitis AI and the Deep Learning Processing Unit (DPU) technology [2]. Although GWaveNet improves detection performance, it cannot currently be fully compiled and deployed because it contains operators not supported by the DPU. The objective of this project is to investigate compiler-aware Neural Architecture Search (NAS) [3, 4] as an automated architecture-repair method for GWaveNet. The NAS will replace DPU-incompatible components with hardware-compatible alternatives, while Knowledge Distillation (KD) [5] will transfer information from the original high-accuracy model to FPGA-compatible student networks. 

<h3>How</h3>

You will analyse the existing GWaveNet model and identify the operations that prevent its compilation with Vitis AI. A key part of the project will focus on defining a NAS search space containing DPU-compatible alternatives for the main GWaveNet components. The Vitis AI model inspector and compiler will be integrated into the search pipeline so that candidate models are evaluated according to both detection performance and complete graph compatibility. KD will be used to train the FPGA-compatible student models while preserving the detection performance of the original teacher model. The most promising candidates will be quantized, pruned and deployed on an FPGA device using the Vitis AI toolchain.

<h3>Outputs</h3>

Development of a compiler-aware NAS and KD pipeline for generating FPGA-compatible GW detection models. Comparison of the original GWaveNet model, manually adapted architectures and NAS-generated student models in terms of detection performance, model size and compilation success. Deployment of at least one optimized model on an FPGA board. If the validation yields state-of-the-art results and time permits, publication and presentation of the results at an international venue.

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of ML and DL fundamentals</li>
	<li>High-level coding skills in Python and C++</li>
	<li>Nice to have or willing to learn: NAS and multi-objective optimization, understanding of modern DL compression techniques, FPGA technology and the AMD Vitis AI development environment</li>
</ol>

<ul>
	<li>[1] Martins, Ana, et al. (2025). Improving early detection of gravitational waves from binary neutron stars using CNNs and FPGAs. Machine Learning: Science and Technology.</li>
	<li>[2] AMD-Xilinx, Vitis AI: https://xilinx.github.io/Vitis-AI/3.5/html/index.html</li>
	<li>[3] Chitty-Venkata, K. T., & Somani, A. K. (2022). Neural architecture search survey: A hardware perspective. ACM Computing Surveys</li>
	<li>[4] Lan, Z. et al. (2024). CoDANet: Hardware-Aware Neural Architecture Search for Optimized Deep Learning on FPGAs. 2024 2nd International Conference on Artificial Intelligence and Automation Control (AIAC)</li>
	<li>[5] Gou, J. et al. (2021) "Knowledge distillation: A survey." International journal of computer vision</li>
</ul>