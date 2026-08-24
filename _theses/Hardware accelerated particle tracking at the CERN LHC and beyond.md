---
layout: post
title: "Hardware accelerated particle tracking at the CERN LHC and beyond (multiple projects)"
inline: false
related_posts: false
tags: ["2026", applied, compression, LHC]
---

<i>This project will be performed in collaboration with Dr Panos Christakoglou (Maastricht Science Programme and Nikhef)
</i>

<h3>Objective</h3>

With the anticipated upgrade of the Large Hadron Collider (LHC), particle physics is entering the high-luminosity (HL) era of the accelerator. This brings new challenges to particle track reconstruction, not only due to the extreme particle multiplicities but also because of high pile-up rates (i.e. multiple independent proton-proton collisions occurring within the same time window). These conditions make the use of efficient models for particle tracking critical. Deep Learning (DL) approaches are especially promising, as they can reduce computational resource usage while maintaining or even improving physics performance.

<h3>How</h3>

You will build on our existing work for novel methods to enable efficient ambiguity resolution. You will focus on the deployment of optimized deep learning models for particle tracking, including Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs) and Graph Neural Networks (GNNs), on specialized hardware, such as GPUs and FPGAs. The goal of this project is to evaluate the trade-offs between speed, energy efficiency and physics performance when running these models on accelerated platforms.

<h3>Outputs</h3>

Benchmark of DL models on different hardware backends such as GPU and FPGAs. Measurement of impact on throughput, power consumption and eventually physics performance (e.g. efficiency vs fake track rates). If the validation yields state of the art results and if time permits, the publication and presentation of the results in an international venue.

<h4>Prerequisites</h4>

<ol>
<li> Solid understanding of Machine Learning and Deep Learning fundamentals </li>
<li> Understanding of GPU or FPGA fundamentals </li>
<li> Programming skills in Python and/or C++ </li>
</ol>

<h2><b>Project 1: Low-pT tracking performance studies for ALICE 3 at the CERN-LHC with ACTS</b></h2>

<h3>Objective</h3>

The ALICE 3 detector is a proposed next-generation experiment at CERN designed to study rare probes of the quark-gluon plasma and low-momentum particle production with unprecedented precision. The recent availability of the ALICE 3 geometry within the ACTS tracking framework enables realistic studies of its tracking performance before detector construction. Understanding the reconstruction efficiency of low-transverse-momentum (low-pT) particles is particularly important, as these particles follow strongly curved trajectories and represent one of the most challenging tracking regimes.

<h3>How</h3>

You will use the ACTS software framework to generate and reconstruct simulated particle trajectories in the ALICE 3 detector geometry. The project will focus on studying tracking efficiency, fake rates, and track-parameter resolutions as a function of particle momentum, particle species, magnetic-field configuration, and detector occupancy. Particular attention will be given to low-pT particles and looping trajectories.

<h3>Outputs</h3>

Performance characterization of the ACTS tracking chain in the ALICE 3 geometry, including efficiency and resolution studies in the low-pT regime. Identification of the main limitations of current reconstruction approaches and recommendations for future tracking developments. If the validation yields state-of-the-art results and if time permits, the publication and presentation of the results in an international conference.

<h2><b>Project 2: GPU acceleration and benchmarking of particle tracking for ALICE 3 at the CERN-LHC</b></h2>

<h3>Objective</h3>

Future particle-physics experiments will rely heavily on heterogeneous computing architectures combining CPUs and GPUs. The traccc project, developed within the ACTS ecosystem, provides GPU implementations of key tracking algorithms. The availability of the ALICE 3 geometry offers a unique opportunity to evaluate the performance and scalability of GPU-based tracking for a next-generation detector.

<h3>How</h3>

You will deploy and benchmark ACTS/traccc tracking workflows on CPU and GPU platforms. Using realistic simulated events in the ALICE 3 detector geometry, you will investigate throughput, latency, memory usage, and scalability as a function of event complexity and detector occupancy. The project will identify bottlenecks and evaluate the benefits of GPU acceleration for future tracking workloads.

<h3>Outputs</h3>

Benchmark results comparing CPU and GPU tracking performance. Quantification of scalability, throughput, and resource utilization under realistic detector conditions. Recommendations for efficient deployment of tracking workloads on heterogeneous computing systems. If the validation yields state-of-the-art results and if time permits, the publication and presentation of the results in an international conference.

<h2><b>Project 3: Machine-Learning-based seed filtering for particle tracking in ALICE 3 at the CERN-LHC</b></h2>

<h3>Objective</h3>

Particle-track reconstruction begins with a seeding stage, where detector hits are combined into initial track candidates. In high-density environments, large numbers of fake seeds are produced, increasing the computational cost of subsequent reconstruction stages. Machine-learning techniques may help reduce this combinatorial background while preserving genuine track candidates.

<h3>How</h3>

You will construct a dataset of seeds generated by the ACTS tracking framework and train machine-learning models to distinguish genuine seeds from fake combinations. Different feature representations, including geometry-based and physics-inspired variables, will be evaluated. The impact of machine-learning-based filtering on reconstruction performance and computational cost will then be assessed.

<h3>Outputs</h3>
A benchmark of machine-learning approaches for seed classification, including studies of efficiency, fake-seed rejection, and tracking performance. Assessment of the potential computational gains achievable through machine-learning-assisted seeding. If the validation yields state-of-the-art results and if time permits, the publication and presentation of the results in an international conference.

<h2><b>Project 4: Graph Neural Networks (GNN) for low-momentum particle tracking at the LHC</b></h2>

<h3>Objective</h3>

Low-transverse-momentum particles follow highly curved trajectories in magnetic fields, making their reconstruction particularly challenging for traditional tracking algorithms. Graph Neural Networks (GNNs) have emerged as a promising alternative by treating detector measurements as nodes in a graph and learning the underlying track topology directly from data.

<h3>How</h3>

You will investigate the application of GNNs to the reconstruction of low-pT particle trajectories in the ALICE 3 detector geometry. Existing graph-based tracking models will be trained and evaluated using simulated data produced with the ACTS framework. Their performance will be compared to conventional reconstruction approaches in terms of efficiency, fake rates, computational cost, and robustness to challenging topologies such as looping tracks.

<h3>Outputs</h3>
Evaluation of graph-based tracking methods for low-pT reconstruction, including performance comparisons with conventional tracking algorithms. Identification of strengths and limitations of GNN approaches in future detector environments. If the validation yields state-of-the-art results and if time permits, the publication and presentation of the results in an international conference.

