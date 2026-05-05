---
layout: post
title: "Efficient multiscale computer vision targeting and evidence-based response to crop diseases"
inline: false
related_posts: false
tags: [2026-2027, CV, applied, hybrid, agri]
---

<h3>Objective</h3>

Recent studies[1][2] demonstrate the potential of UAV imagery combined with computer vision models for pest and disease detection. However, CNNs typically struggle to capture long-distance dependencies, while ViTs typically underperform when faced with limited training data or insufficient training time. Moreover, existing approaches often rely on computationally intensive architectures that are not energy-inefficient. You will work on addressing these limitations through a hybrid [3] CNN-ViT architecture for precise local feature extraction and global multiscale context modelling.

<h3>How</h3>

You will extend StemWin, our family of novel hybrid convolutional-Transformer architectures designed for robust multi-scale crop disease detection in high-resolution UAV imagery. The existing architectures, StemWin, StemWin-ECA and StemWin-Dual, target detection of the *Alternaria Solani* pathogen under challenging real-world conditions characterized by seasonal domain shifts and severe scale imbalance. The project will focus on wdge deployment on UAVs. The work will examine the deployability of the networks on edge devices including FPGA boards (KV-260, ZCU-104), NN accelerators (Axelera Metis) and low-power MCUs (STM32U5, NXP FRDM). Research will focus on hardware-software co-design tuning and compressing the algorithms via iterative structured/unstructured pruning[4], PTQ/QAT, knowledge distillation and NAS/OVA to adapt to hardware constraints.

<h3>Outputs</h3>

A compressed, optimized adaptation of StemWin, co-designed for multiple edge devices, including FPGA boards, NN accelerators and low-power MCUs, with an emphasis on accuracy, memory and processing requirements. If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
<li> Solid understanding of Machine Learning and Deep Learning fundamentals </li>
<li> High-level coding skills in Python </li>
<li> Nice to have or willing to learn: Coding skills in C </li>
<li> Nice to have or willing to learn: Understanding of modern DL compression techniques </li>
<li> Willingness to contribute to the state-of-the-art Deep Learning computer vision models </li>
</ol>

<ul>
<li>[1] Wieme, J. et. al., (2024). “Ultra-high-resolution UAV-imaging and supervised deep learning for accurate detection of Alternaria solani in potato fields”.</li>
<li>[2] Ksibi, A. et. al., (2022). “MobiRes-net: a hybrid deep learning model for detecting and classifying olive leaf diseases”.</li>
<li>[3] Lu, W., et. al., (2023). “A CNN-transformer hybrid model based on CSWin transformer for UAV image object detection”.</li>
<li>[4] A. Papaioannou, C.S. Kouzinopoulos, D. Ioannidis, and D. Tzovaras. "An Ultra-Low-Power Embedded AI Fire Detection and Crowd Counting System for Indoor Areas"</li>
<li>[5] Wieme, J. et. al., (2024). “Ultra-high-resolution UAV-imaging and supervised deep learning for accurate detection of Alternaria solani in potato fields”. </li>
</ul>


