---
layout: post
title: "Towards FPGA-Deployable Continual Learning for Satellite Telemetry Anomaly Detection"
inline: false
related_posts: false
tags: ["2026", applied, FPGA, space]
---

<i>This project will be performed in collaboration with Dr. Angela Cratere (DACS, Maastricht University) and Dr. Nikolaos Alachiotis (EEMCS-CS, University of Twente)</i>

<h3>Objective</h3>

Recent studies [1-5] demonstrate the potential of Machine Learning and Deep Learning models for anomaly detection in satellite telemetry data. However, most existing approaches rely on static training and evaluation settings, assuming that the data distribution remains stable over time. In real satellite missions, telemetry data may evolve due to changing operational modes or concept drift. This can reduce model reliability, increase false alarms, and require repeated retraining or manual intervention. In this project, you will address these limitations by investigating continual learning (CL) and concept drift-aware anomaly detection for satellite telemetry time series. The project will build on our existing telemetry anomaly detection benchmark and will focus on developing adaptive models that can learn from sequential telemetry data while limiting catastrophic forgetting. A second objective will be to assess the feasibility of deploying such models, or parts of the continual learning pipeline, on FPGA for onboard satellite applications. 

<h3>How</h3>

Using open-source telemetry datasets from real missions [3, 4], you will extend our current telemetry anomaly detection framework from a static train/test setup to a CL scenario. Several CL strategies will be compared, including naïve fine-tuning, periodic cumulative retraining, replay-based CL [6], and regularization-based CL, combined with concept drift detection mechanisms to trigger model adaptation. The project will also investigate model compression strategies, such as pruning and quantization, to reduce memory footprint and computational cost. Finally, the project will examine FPGA deployment using Vitis AI, FINN, and/or Vitis HLS [7, 8].

<h3>Outputs</h3>

A CL framework for satellite telemetry anomaly detection and forecasting. A comparative evaluation of different CL strategies, with emphasis on model performance, adaptability, catastrophic forgetting, and memory requirements, integrated with a concept drift-aware model adaptation pipeline. A feasibility study of FPGA deployment using different toolchains, including an assessment of which components of the CL pipeline can be implemented on resource-constrained onboard platforms. If the validation yields state-of-the-art results, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of ML and DL fundamentals</li>
	<li>High-level coding skills in Python</li>
	<li>Nice to have or willing to learn: Understanding of modern DL compression techniques</li>
</ol>

<ul>
<li>[1] Wang, Y. et al., (2022). "A Deep Learning Anomaly Detection Framework for Satellite Telemetry with Fake Anomalies."</li>
<li>[2] Horne, R. et al., (2023) "Anomaly Detection Using Deep Learning Respecting the Resources on Board a CubeSat"</li>
<li>[3] Ruszczak, B. et al., (2025). "The OPS-SAT benchmark for detecting anomalies in satellite telemetry."</li>
<li>[4] Kotowski, K. et al. (2024). "Benchmark for Anomaly Detection in Satellite Telemetry." https://github.com/kplabs-pl/ESA-ADB </li>
<li>[5] Goetze, C. et al. (2025) "Deep Learning-Based Anomaly Detection in Spacecraft Telemetry on Edge Devices." </li>
<li>[6] De Canio C. et al. (2025) "Advancing spacecraft health monitoring and control with AI through continual learning."</li>
<li>[7] Aggarwal, S. (2023) "Chameleon: Dual Memory Replay for Online Continual Learning on Edge Devices." </li>
<li>[8] Akram, M. S. (2024) "Continual Learning on FPGAs for Efficient Cardiac Diagnosis through Mix-Precision Quantized DNNs."</li>
</ul>