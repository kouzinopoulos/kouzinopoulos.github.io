---
layout: post
title: "Binary Neural Networks for Post-Disaster Change Detection on FPGA"
inline: false
related_posts: false
tags: [2026, applied, FPGA, space]
---

<i>This project will be performed in collaboration with Dr Angela Cratere</i>

<h3>Objective</h3>

Near-real-time change detection from Earth Observation (EO) data is increasingly important for disaster response and environmental monitoring. Recent advances in machine learning and deep learning (DL) have shown strong potential for enabling onboard change detection, allowing satellites to autonomously identify and prioritize relevant image regions before transmission [1-4]. However, deploying DL models onboard small satellites remains challenging due to strict constraints in memory, power consumption, and computational resources. Binary Neural Networks (BNNs), where weights and activations are quantized to 1 bit, offer an attractive solution for onboard intelligence because they replace expensive matrix multiplications with lightweight bitwise operations such as XNOR and PopCount [5]. Recent work has shown that BNNs can be specifically adapted to change detection [6]; however, their use for EO data and onboard satellite applications remains largely unexplored. In this project, you will investigate BNNs for efficient onboard change detection in satellite imagery, with particular emphasis on model compactness, computational efficiency and suitability for deployment on FPGA-based embedded hardware.

<h3>How</h3>

Near-real-time change detection from Earth Observation (EO) data is increasingly important for disaster response and environmental monitoring. Recent advances in machine learning and deep learning (DL) have shown strong potential for enabling onboard change detection, allowing satellites to autonomously identify and prioritize relevant image regions before transmission [1-4]. However, deploying DL models onboard small satellites remains challenging due to strict constraints in memory, power consumption, and computational resources. Binary Neural Networks (BNNs), where weights and activations are quantized to 1 bit, offer an attractive solution for onboard intelligence because they replace expensive matrix multiplications with lightweight bitwise operations such as XNOR and PopCount [5]. Recent work has shown that BNNs can be specifically adapted to change detection [6]; however, their use for EO data and onboard satellite applications remains largely unexplored. In this project, you will investigate BNNs for efficient onboard change detection in satellite imagery, with particular emphasis on model compactness, computational efficiency, and suitability for deployment on FPGA-based embedded hardware.

<h3>Outputs</h3>

A framework for BNN-based onboard change detection in satellite imagery, enabling efficient identification and prioritization of disaster-affected regions. Validation of the framework on publicly available EO datasets, with emphasis on detection accuracy, computational cost, and FPGA deployment feasibility. The project will provide a comparative assessment between full-precision, quantized, and binary models, highlighting whether BNNs can provide a suitable trade-off between accuracy and onboard efficiency for disaster monitoring applications. If the validation yields strong results, the publication and presentation of the results in an international workshop or conference.

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of Machine Learning and DL fundamentals</li>
	<li>High-level coding skills in Python and C++</li>
	<li>Nice to have or willing to learn: Understanding of modern DL compression techniques</li>
	<li>Nice to have or willing to learn: Understanding of the FPGA technology and HLS development environment</li>
</ol>

<ul>
<li>[1] Růžička, V. et al., (2022) "RaVÆn: unsupervised change detection of extreme events using ML on-board satellites." https://doi.org/10.1038/s41598-022-19437-5</li>
<li>[2] Valsamis, D. et al., (2024) "Towards Advanced Wildfire Analysis: A Siamese Network-Based Change Detection Approach Through Self-Supervised Learning." doi: 10.1109<li>/CBMI62980.2024.10858874.</li>
<li>[3] Herec, J. et al., (2026) "STTORM-CD low-demand and high-impact disaster monitoring onboard satellites using change detection." https://doi.org/10.1038/<li>s41598-025-32598-3</li>
<li>[4] Fang, H. et al. (2025), "Leveraging Satellite Image Time Series for Accurate Extreme Event Detection." doi: 10.1109/WACVW65960.2025.00060</li>
<li>[5] Yuan, C. et al., (2023) "A comprehensive review of Binary Neural Network." https://doi.org/10.1007/s10462-023-10464-w</li>
<li>[6] Yin, K. et al. (2025). "Information-Bottleneck Driven Binary Neural Network for Change Detection." doi: 10.1109/ICCV51701.2025.00674</li>
<li>[7] Růžička, V. et al., "RaVÆn dataset" (2022). https://github.com/spaceml-org/RaVAEn</li>
<li>[8] Jonáš H. et al., "STTORM-CD-Floods" (2025). https://zenodo.org/records/14891438</li>
<li>[9] Valsamis D. et al., "Sentinel-2 Wildfire Change Detection (S2-WCD)" (2025). https://ieee-dataport.org/documents/sentinel-2-wildfire-change-detection-s2-wcd </li>
</ul>