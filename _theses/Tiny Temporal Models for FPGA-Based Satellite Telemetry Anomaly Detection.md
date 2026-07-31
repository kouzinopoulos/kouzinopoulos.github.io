---
layout: post
title: "Tiny Temporal Models for FPGA-Based Satellite Telemetry Anomaly Detection"
inline: false
related_posts: false
tags: ["2026", applied, FPGA, space]
---

<i>This project will be performed in collaboration with Dr. Angela Cratere (DACS, Maastricht University) and Dr. Nikolaos Alachiotis (EEMCS-CS, University of Twente)</i>

<h3>Objective</h3>

Recent studies have demonstrated the potential of deep learning for anomaly detection in satellite telemetry data [1]. However, architectures that achieve strong performance are not necessarily suitable for onboard deployment, particularly on FPGAs, as they may contain operators and graph structures that are unsupported by standard FPGA deployment toolchains. In this project, you will extend our existing satellite telemetry anomaly-detection framework by developing compact and hardware-compatible variants of XceptionTimePlus [2] and a Tiny Transformer [3]. The project will focus on redesigning and optimizing these models for FPGA implementation while preserving their ability to capture local, multiscale and long-range temporal dependencies. 

<h3>How</h3>

Using open-source telemetry datasets from real satellite missions [4, 5], you will implement compact temporal models for forecasting-based anomaly detection, with a focus on efficient FPGA deployment. The models will be deployed using one or more toolchains (Vitis AI, FINN+, hls4ml and Vitis HLS), depending on the compatibility constraints. You will investigate hardware-aware architectural redesign and/or Neural Architecture Search (NAS) [6] to identify configurations that are compatible with the selected deployment frameworks. The project will also explore multiple quantization levels and mixed-precision configurations.

<h3>Outputs</h3>

An extension of the existing satellite telemetry anomaly-detection repository with optimized implementations of XceptionTimePlus and a Tiny Trasformer. Hardware-compatible versions of both model families supporting multiple quantization levels. Operational deployment of at least one optimized model on FPGA hardware. An evaluation of the trade-offs between anomaly-detection performance, numerical precision and hardware performance. If the results are sufficiently strong, the publication and presentation of the work at an international venue.

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of ML and DL fundamentals</li>
	<li>High-level coding skills in Python and C++</li>
	<li>Nice to have or willing to learn: model compression techniques, FPGA deployment toolchains</li>
</ol>

<h4>References</h4>

<ul>
	<li>[1] Horne, R. et al., (2023) "Anomaly Detection Using Deep Learning Respecting the Resources on Board a CubeSat"</li>
	<li>[2] Goetze, C. et al. (2025) "Deep Learning-Based Anomaly Detection in Spacecraft Telemetry on Edge Devices."</li>
	<li>[3] Ling, T. et al. (2025) "Automating Versatile Time-Series Analysis with Tiny Transformers on Embedded FPGAs" https://github.com/tianheng-ling/TinyTransformer4TS</li>
	<li>[4] Ruszczak, B. et al., (2025). "The OPS-SAT benchmark for detecting anomalies in satellite telemetry."</li>
	<li>[5] Kotowski, K. et al. (2024). "Benchmark for Anomaly Detection in Satellite Telemetry." https://github.com/kplabs-pl/ESA-ADB</li>
	<li>[6] Pant A. R et al (2026) "FONAS: FPGA Optimized Neural Architecture Search for Hardware Efficiency through Evolutionary Search" https://github.com/FPGA-Vision/FPGA-Optimized-Neural-Architecture-Search/tree/main</li>
</ul>