---
layout: post
title: "Hardware-Aware Low-Rank Factorization"
inline: false
related_posts: false
tags: [2026, foundational]
---

<i>This project will be performed in collaboration with Assistant Professor Georgios Keramidas from the Aristotle University of Thessaloniki 
</i>

<h3>Objective</h3>

Edge AI is a new paradigm in Machine Learning (ML) that compresses Deep Learning (DL) models for inference and training on the billions of edge devices that constitute the Internet of Things (IoT). However, Edge AI is challenging due to resource constraints of the hardware devices: typical microprocessors (MCUs) in the IoT have less than 2MB of Flash memory and 320KB of SRAM, with a processor frequency of no more than 100MHz. For this reason, existing DL architectures must be compressed and optimized for inference at the edge.

<h3>How</h3>

You will develop and implement Hardware-Aware Low-Rank Factorization (LRF) techniques tailored for optimizing Deep Neural Networks (DNNs) on specific hardware architectures [1]. Traditional LRF approaches often focus solely on model accuracy and compression without taking into account the performance characteristics of the target hardware, such as memory bandwidth, computational capabilities, and energy consumption. You will explore methods to integrate hardware awareness into the LRF process, enabling more effective optimization that maximizes performance while minimizing resource usage. You will establish best practices for implementing hardware-aware LRF.

<h3>Outputs</h3>

A new open-source compression framework of neural networks. Validation of the framework for different datasets, with an emphasis on accuracy, memory and processing requirements as well as power consumption. If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
<li> Solid understanding of Machine Learning and Deep Learning fundamentals </li>
<li> High-level coding skills in Python </li>
<li> Nice to have or willing to learn: Coding skills in C </li>
<li> Nice to have or willing to learn: Understanding the architecture of modern MCUs </li>
<li> Willingness to contribute to the state-of-the-art neural network models </li>
</ol>

<ul>
<li> [1] J. Xiao, C. Zhang, Y. Gong, M. Yin, Y. Sui, L. Xiang, D. Tao, and B. Yuan. HALOC: hardware-aware automatic low-rank compression for compact neural networks. In Proceedings of the AAAI Conference on Artificial Intelligence, 2023.</li>
</ul>