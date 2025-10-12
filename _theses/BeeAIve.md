---
layout: post
title: "BeeAIve: Machine Learning for Queen Presence Classification in Beehive Audio with Edge Deployment"
inline: false
related_posts: false
---

<h3>Objective</h3>

The presence of a queen bee is a key indicator of colony health. Monitoring the presence of queen bees in beehives is a critical indicator of hive health and remains challenging, particularly in nomadic beekeeping. Recent bioacoustic studies have shown that hive sounds can reveal queen status, but existing approaches often fail to generalize across hives. There are recent works in the literature that implement IoT monitoring solutions, yet they are often invasive, dependent on cloud services or they have high energy requirements, limiting their practical use in the field.

<h3>How</h3>
You will extend prior work that introduced an audio-based classification framework that employed Continuous Wavelet Transform (CWT) features with a Convolutional Neural Network (CNN) on an NXP FRDM-MCXN947 low-power device, for efficient classification of the presence of a queen bee on beehives. In this work you will explore different signal representation methods and Deep Learning (DL) models for accurate classification of queen bees. You will compress the DL models using state of the art approximation techniques (pruning, quantization, transfer learning) and deploy the complete pipeline on a low-power edge device (i.e. NXP FRDM, STM32U5, GAP9, Axelera M.2 AIPU). You will validate the solution on open-source datasets and real data.

<h3>Outputs</h3>

An extensive survey of signal representation methods and computer vision models. A new open-source compressed framework for the detection of queen bees in beehives. Deployment of the framework on a low-power edge device. Validation of the framework for different datasets, with an emphasis on accuracy, memory and processing requirements as well as power consumption. If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international conference.

<h4>Prerequisites</h4>

<ol>
<li> Solid understanding of signal processing, Machine Learning and Deep Learning fundamentals </li>
<li> High-level coding skills in Python </li>
<li> Nice to have or willing to learn: Coding skills in C </li>
<li> Nice to have or willing to learn: Understanding the architecture of modern MCUs </li>
<li> Willingness to contribute to the state-of-the-art Deep Learning models </li>
</ol>
