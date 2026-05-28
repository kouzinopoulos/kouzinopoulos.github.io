---
layout: post
title: "Efficient Multiscale Onboard Vision for Rapid Building Damage Assessment after Disasters"
inline: false
related_posts: false
tags: ["2026", applied, FPGA, space]
---

<i>This project will be performed in collaboration with Dr Angela Cratere</i>

<h3>Objective</h3>

Recent studies have shown that satellite imagery combined with computer vision models can support rapid building damage assessment after natural disasters. However, operational workflows still largely rely on image downlink followed by ground-based analysis, which can introduce critical delays. Onboard computing can help reduce this latency by enabling satellites to perform image analysis and damage assessment directly after acquisition. Hybrid CNN-ViT architectures are promising for this task because they combine precise local feature extraction with global multiscale context modelling [1-3]. However, existing approaches often rely on computationally intensive architectures, not energy-efficient, and difficult to deploy on onboard platforms. This project will develop lightweight hybrid CNN-ViT models for onboard building damage assessment, enabling satellites to identify damaged areas, prioritize regions of interest and support faster disaster-response downlink under resource constraints.

<h3>How</h3>

This project will adapt existing state-of-the-art hybrid CNN-ViT architectures to satellite-based building damage assessment using benchmark datasets [4-6]. The project will focus on hardware-software co-design to develop hardware-aware models suitable for resource-constrained onboard platforms, including FPGA boards (KV-260, ZCU-104), NN accelerators (Axelera Metis) and low-power MCUs (STM32U5, NXP FRDM). The research will employ model compression techniques such as iterative structured/unstructured pruning, PTQ/QAT, knowledge distillation and NAS/OFA to adapt to hardware constraints.

<h3>Outputs</h3>

A compressed and optimized adaptation of hybrid CNN-ViT models for onboard satellite-based building damage assessment, co-designed for multiple edge devices, including FPGA boards, embedded AI accelerators and low-power microcontrollers. The work will include a comparison of different compression and deployment strategies, with emphasis on memory footprint, latency and energy consumption. If the validation yields competitive results, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
	<li>Solid understanding of ML and DL fundamentals</li>
	<li>High-level coding skills in Python</li>
	<li>Nice to have or willing to learn: Coding skills in C/C++</li>
	<li>Nice to have or willing to learn: Understanding of modern DL compression techniques</li>
	<li>Willingness to contribute to the state-of-the-art Deep Learning computer vision models</li>
</ol>

<ul>
<li>[1] Swamy, P. A. et al. (2023) "A Hybrid Model for Disaster Damage Detection Using Satellite Images"</li>
<li>[2] Kaur, N. et al. (2023) "Large-scale building damage assessment using a novel hierarchical transformer architecture on satellite images"</li>
<li>[3] Liu, Y. et al. (2024) "Building Change Detection in Earthquake: A Multiscale Interaction Network With Offset Calibration and a Dataset"</li>
<li>[4] Gupta, R. et al. (2019) "xBD: A Dataset for Assessing Building Damage from Satellite Imagery"</li>
<li>[5] Lee, C. et al. (2022) "Ida-BD: pre- and post-disaster high-resolution satellite imagery for building damage assessment from Hurricane Ida"</li>
<li>[6] Chen, H. et al. (2026) "BRIGHT: A globally distributed multimodal building damage assessment dataset with very-high-resolution for all-weather disaster response"</li>
</ul>