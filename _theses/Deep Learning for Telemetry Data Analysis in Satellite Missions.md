---
layout: post
title: "Deep Learning for Telemetry Data Analysis in Satellite Missions "
inline: false
related_posts: false
---

<i>This project will be performed in collaboration with Dr Angela Cratere</i>

<h3>Objective</h3>

The detection of anomalies in telemetry data is a critical function for ensuring the reliability and safety of satellite missions. Spacecraft telemetry data provide continuous insight into system health and are traditionally monitored using rule-based techniques and predefined thresholds. While effective for known failure modes, these approaches require significant manual analysis by ground operators and struggle to capture evolving operational conditions [1]. Recent advances in machine learning (ML) and deep learning (DL) have shown strong potential for autonomous anomaly detection and fault diagnosis in satellite telemetry, both for ground-based operations and for enabling onboard fault detection, isolation, and recovery [2,3]. In this project, you will investigate data-driven approaches for anomaly detection in satellite telemetry time series, with particular emphasis on model robustness, computational efficiency, and suitability for deployment on embedded hardware. 

<h3>How</h3>

You will explore and evaluate ML and DL techniques using publicly available telemetry datasets from real satellite missions [3, 4]. Both supervised and unsupervised approaches will be considered, including but not limited to classical machine learning models (e.g., random forest), sequence-based models (e.g., recurrent neural networks), convolutional architectures, and variational autoencoders.  A comparative analysis will be performed to assess the trade-offs between performance, model complexity and suitability for onboard deployment. To this end, the project will also investigate model compression strategies, such as pruning and quantization, to reduce memory footprint and computational cost. 

<h3>Outputs</h3>

A framework for DL-based analysis of satellite telemetry, enabling autonomous anomaly detection. Validation of the framework on publicly available satellite telemetry datasets [3, 4], with emphasis on detection accuracy, false alarm rate, and model complexity. If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international conference.

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
<li>[4] Kotowski, K. et al., (2024). "Benchmark for Anomaly Detection in Satellite Telemetry." https://github.com/kplabs-pl/ESA-ADB</li>
</ul>