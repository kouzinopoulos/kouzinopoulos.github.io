---
layout: post
title: "Hardware-Aware Neural Architecture Search for Satellite Telemetry Anomaly Detection"
inline: false
related_posts: false
tags: ["2026", applied, FPGA, space]
---

<i>This project will be performed in collaboration with Dr. Angela Cratere (DACS, Maastricht University) and Dr. Nikolaos Alachiotis (EEMCS-CS, University of Twente)</i>

<h3>Objective</h3>

Recent studies [1-5] demonstrate the potential of Machine Learning and Deep Learning models for anomaly detection in satellite telemetry data. However, existing approaches often focus mainly on detection performance, while giving limited attention to model complexity, latency, memory footprint, and suitability for onboard deployment. Moreover, sequence-based models such as LSTMs may be computationally demanding, while convolutional and MLP-based models may struggle to capture long-range temporal dependencies or evolving operational conditions. In this project, you will work on addressing these limitations by extending our satellite telemetry anomaly detection benchmark and investigating hardware-aware Neural Architecture Search (NAS) for the design of compact and efficient models suitable for FPGA-based deployment. The project will focus on identifying architectures that achieve a good trade-off between anomaly detection performance and deployability on embedded FPGA hardware. 

<h3>How</h3>

Using open-source telemetry datasets from real missions [3, 4], you will extend our current telemetry anomaly detection framework by including additional time-series architectures, potentially Gated Recurrent Units (GRUs), Temporal Convolutional Networks, and hybrid CNN-ViT architectures. The core research activity will focus on hardware-aware NAS and model optimization. You will investigate how to automatically or semi-automatically search for efficient neural architectures under deployment constraints [6, 7]. Moreover, you will also implement model compression strategies, such as pruning and quantization, to reduce memory footprint and computational cost. The project will also examine FPGA deployment using one or more toolchains, depending on the selected architecture and compatibility constraints (Vitis AI, FINN and Vitis HLS). The final goal is to assess which models are realistically suitable for onboard telemetry analysis on resource-constrained satellite platforms. 

<h3>Outputs</h3>

An extended benchmark for satellite telemetry anomaly detection. A hardware-aware NAS and optimization framework for identifying compact models suitable for FPGA implementation. A compressed and optimized set of telemetry anomaly detection models deployed on FPGA platforms using different tools. If the validation yields strong results, the publication and presentation of the results in an international workshop or conference.

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of ML and DL fundamentals</li>
	<li>High-level coding skills in Python</li>
	<li>Nice to have or willing to learn: Understanding of modern DL compression techniques</li>
	<li>Nice to have or willing to learn: FPGA deployment flows such as Vitis AI, FINN and/or Vitis HLS</li>
</ol>

<ul>
<li>[1] Wang, Y. et al., (2022). "A Deep Learning Anomaly Detection Framework for Satellite Telemetry with Fake Anomalies."</li>
<li>[2] Horne, R. et al., (2023) "Anomaly Detection Using Deep Learning Respecting the Resources on Board a CubeSat"</li>
<li>[3] Ruszczak, B. et al., (2025). "The OPS-SAT benchmark for detecting anomalies in satellite telemetry."</li>
<li>[4] Kotowski, K. et al. (2024). "Benchmark for Anomaly Detection in Satellite Telemetry." https://github.com/kplabs-pl/ESA-ADB </li>
<li>[5] Goetze, C. et al. (2025) "Deep Learning-Based Anomaly Detection in Spacecraft Telemetry on Edge Devices." </li>
<li>[6] Skobtsov, V.Y. et al (2023). "Automatic Searching the Neural Network Models for Time Series Classification of Small Spacecraft’s Telemetry Data with Genetic Algorithms."</li>
<li>[7] Pant A. R et al (2026) "FONAS: FPGA Optimized Neural Architecture Search for Hardware Efficiency through Evolutionary Search" https://github.com/FPGA-Vision/FPGA-Optimized-Neural-Architecture-Search/tree/main</li>

</ul>