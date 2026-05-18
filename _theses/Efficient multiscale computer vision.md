---
layout: post
title: "Optimized hybrid CNN-Transformer architectures for Pareto-efficient vision systems"
inline: false
related_posts: false
tags: [2026, CV, foundational, hybrid]
---

<h3>Objective</h3>

Recent advances in hybrid CNN-Transformer architectures demonstrate that combining convolutional inductive biases with Transformer-based global context modelling can significantly improve computer vision performance across diverse tasks. However, many state-of-the-art hybrid models remain computationally expensive and fail to achieve favorable Pareto trade-offs between Top-1 accuracy, throughput, latency, memory footprint and energy efficiency. Existing architectures are often designed primarily for accuracy, with limited consideration of deployment constraints and hardware-aware optimization.

This project focuses on foundational research in efficient hybrid vision architectures targeting improved Pareto fronts for accuracy versus throughput. The goal is to design, analyze and optimize hybrid CNN-Transformer models that maintain competitive Top-1 accuracy while significantly improving inference efficiency across heterogeneous computing platforms.

<h3>How</h3>

You will investigate novel hybrid architectural design principles combining convolutional operators, token mixing mechanisms and attention modules to achieve efficient multiscale feature extraction with reduced computational complexity. The work will build toward generalized hardware-aware hybrid models applicable across multiple computer vision domains.

Research directions may include:

<ul>
<li>Efficient tokenization and hierarchical feature fusion strategies</li>
<li>Lightweight self-attention and sparse attention mechanisms</li>
<li>Hybrid CNN-Mamba-Transformer operator exploration</li>
</ul>

The developed models will be evaluated on modern heterogeneous edge and accelerated computing platforms including GPUs, FPGA boards (KV260, ZCU104), neural accelerators (Axelera Metis) and low-power embedded systems. The project will emphasize both algorithmic innovation and hardware-software co-design.

<h3>Outputs</h3>

An optimized hybrid CNN-Transformer architecture with significantly improved Pareto efficiency in terms of Top-1 accuracy versus throughput, latency and energy consumption. Expected outcomes include extensive benchmarking, hardware-aware optimization methodologies. If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
<li> Solid understanding of Machine Learning and Deep Learning fundamentals </li>
<li> High-level coding skills in Python </li>
<li>Strong interest in computer vision architectures and optimization</li>
<li> Nice to have or willing to learn: Coding skills in C </li>
<li> Nice to have or willing to learn: Understanding of modern DL compression techniques </li>
<li> Willingness to contribute to foundational research in efficient deep learning architectures </li>
</ol>

<ul>
<li>[1] Liu, Ze, et al. "Swin transformer: Hierarchical vision transformer using shifted windows." Proceedings of the IEEE/CVF international conference on computer vision. 2021.</li>
<li>[2] Liu, Ze, et al. "Swin transformer v2: Scaling up capacity and resolution." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022.</li>
<li>[3] Li, Jiashi, et al. "Next-vit: Next generation vision transformer for efficient deployment in realistic industrial scenarios." arXiv preprint arXiv:2207.05501 (2022).</li>
<li>[4] Hatamizadeh, Ali, and Jan Kautz. "Mambavision: A hybrid mamba-transformer vision backbone." Proceedings of the Computer Vision and Pattern Recognition Conference. 2025.</li>
</ul>
