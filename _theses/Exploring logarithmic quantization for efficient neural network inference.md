---
layout: post
title: "Exploring logarithmic quantization for efficient neural network inference"
inline: false
related_posts: false
tags: [2026-2027, foundational, compression]
---

<i>This project will be performed in collaboration with Assistant Professor Georgios Keramidas from the Aristotle University of Thessaloniki 
</i>

<h3>Objective</h3>

Edge AI is a new paradigm in Machine Learning (ML) that compresses Deep Learning (DL) models for inference and training on the billions of edge devices that constitute the Internet of Things (IoT). However, Edge AI is challenging due to resource constraints of the hardware devices: typical microprocessors (MCUs) in the IoT have less than 2MB of Flash memory and 320KB of SRAM, with a processor frequency of no more than 100MHz. For this reason, existing DL architectures must be compressed and optimized for inference at the edge.

<h3>How</h3>

You will investigate logarithmic quantization [1] as a method to reduce the computational cost of neural network inference on resource-constrained devices. Unlike uniform quantization, logarithmic quantization maps weights to powers of two, allowing multiplications to be replaced by bit-shift operations, which are significantly faster and more energy-efficient on embedded hardware. You will implement a log quantizer for multiple neural networks and evaluate their performance improvements in terms of latency, memory usage, energy consumption and accuracy trade-offs for multiple datasets compared to standard int8 quantization.

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
<li> [1] Przewlocka-Rus, Dominika, Syed Shakib Sarwar, H. Ekin Sumbul, Yuecheng Li, and Barbara De Salvo. "Power-of-two quantization for low bitwidth and hardware compliant neural networks." arXiv preprint arXiv:2203.05025 (2022).</li>
</ul>