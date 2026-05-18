---
layout: post
title: "One shot vs. iterative pruning"
inline: false
related_posts: false
tags: ["2026", foundational, compression]
---

<h3>Objective</h3>

Edge AI is a new paradigm in Machine Learning (ML) that compresses Deep Learning (DL) models for inference and training on the billions of edge devices that constitute the Internet of Things (IoT). However, Edge AI is challenging due to resource constraints of the hardware devices: typical microprocessors (MCUs) in the IoT have less than 2MB of Flash memory and 320KB of SRAM, with a processor frequency of no more than 100MHz. For this reason, existing DL architectures must be compressed and optimized for inference at the edge.

<h3>How</h3>

Understanding of the fundamental computer vision models for image classification (i.e. [1][2]) and object detection ([3][4]) is key for this thesis. You will gain familiarity with existing resource-constrained DL architectures ([5][6]) and get to know the deployment process for DL models on modern MCUs, such as the STM32U5 series, MCX N94x or GAP9. You will explore the use of different structured pruning techniques following one-shot, iterative and hybrid pruning strategies [7] on different YOLO models, including YOLOv8n and YOLOv10n. The proposed techniques will be validated on existing datasets (i.e. [7]) and/or real-world data.

<h3>Outputs</h3>

A new open-source compression framework of YOLO models for object detection. Validation of the framework for different datasets, with an emphasis on accuracy, memory and processing requirements as well as power consumption. If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
<li> Solid understanding of Machine Learning and Deep Learning fundamentals </li>
<li> High-level coding skills in Python </li>
<li> Nice to have or willing to learn: Coding skills in C </li>
<li> Nice to have or willing to learn: Understanding the architecture of modern MCUs </li>
<li> Willingness to contribute to the state-of-the-art Deep Learning models </li>
</ol>

<ul>
<li> [1] Howard, Andrew G., Menglong Zhu, Bo Chen, Dmitry Kalenichenko, Weijun Wang, Tobias Weyand, Marco Andreetto, and Hartwig Adam. "MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications"</li>
<li> [2] Tan, Mingxing, and Quoc V. Le. "EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks"</li>
<li> [3] R. Girshick, J. Donahue, T. Darrell, and J. Malik, "Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation"</li>
<li> [4] Wang, Chien-Yao, I-Hau Yeh, and Hong-Yuan Mark Liao. "Yolov9: Learning what you want to learn using programmable gradient information" </li>
<li> [5] Lin, Ji, Wei-Ming Chen, Yujun Lin, John Cohn, Chuang Gan, and Song Han. "MCUNet: Tiny Deep Learning on IoT Devices."</li>
<li> [6] A. Papaioannou, C.S. Kouzinopoulos, D. Ioannidis, and D. Tzovaras. "An Ultra-Low-Power Embedded AI Fire Detection and Crowd Counting System for Indoor Areas"</li>
<li> [7] Janusz, Mikołaj, et al. "One Shot vs. Iterative: Rethinking Pruning Strategies for Model Compression." arXiv preprint arXiv:2508.13836 (2025).</li>
</ul>