---
layout: post
title: "Edge AI for Space Debris Streaks Detection"
inline: false
related_posts: false
tags: [2026, applied, FPGA, space]
---

<i>This project will be performed in collaboration with Dr Angela Cratere</i>

<h3>Objective</h3>

The detection of faint, fast-moving objects in astronomical images, such as space debris, is a key challenge in space situational awareness (SSA). These targets often appear as low-contrast streaks, with signal levels close to the background noise [1]. Existing deep learning (DL)-based detection approaches are often designed for offline analysis and rely on computationally intensive models, limiting their applicability to real-time and onboard processing. Optimizing these models for operation on low-resource hardware is therefore essential to enable autonomous onboard detection capabilities. The objective of this project is to investigate DL-based methods for detecting faint streaks in astronomical images and to optimize them for deployment on FPGA-based hardware, enabling low-latency and power-efficient inference.

<h3>How</h3>

You will evaluate a DL detection model (e.g., YOLO [2]) for streak detection using a real astronomical dataset [3]. A key part of the project will focus on hardware-aware optimization within the Vitis AI toolchain [4] and on deploying the model on an FPGA board. You will investigate model optimization techniques such as post-training quantization, quantization-aware training, pruning and neural architecture search, and assess their impact on accuracy and efficiency. The optimized models will be deployed on FPGA and evaluated in terms of latency, memory usage and power consumption.

<h3>Outputs</h3>

Application and comparison of various model compression techniques to assess their impact on model size, latency, and detection performance. Deployment of the optimized model on an FPGA board for real-time, low-power inference. If the validation yields state-of-the-art results and if time permits, the publication and presentation of the results in an international conference. 

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of Machine Learning and DL fundamentals</li>
	<li>High-level coding skills in Python</li>
	<li>Nice to have or willing to learn: Understanding of modern DL compression techniques</li>
	<li>Nice to have or willing to learn: Understanding of the FPGA technology and Vitis AI development environment</li>
</ol>

<ul>
	<li>[1] Jeffries, C. et al. (2023). "Detection of Streaks in Astronomical Images Using Machine Learning"</li>
	<li>[2] Guo, Y. et al. (2025). "Enhanced YOLOv8 based method for space debris detection using cross scale feature fusion"</li>
	<li>[3] Parisot, O. et al. (2024). "StreaksYoloDataset: labeled raw astronomical images for streaks detection" https://doi.org/10.5281/zenodo.14047944</li>
	<li>[4] AMD-Xilinx, Vitis AI: https://xilinx.github.io/Vitis-AI/3.5/html/index.html </li>

</ul>