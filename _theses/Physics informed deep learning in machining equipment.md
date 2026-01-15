---
layout: post
title: "Physics informed deep learning in machining equipment"
inline: false
related_posts: false
---

<h3>Description</h3>

Modern manufacturing environments require accurate and reliable estimates of tool-wear and remaining useful life under changing cutting conditions. Project partner Sirris has collected a comprehensive multimodal dataset [1] of cutting-edge images, accelerometer data, microphone recordings and three-axis force signals from CNC milling and has established baselines using conventional machine learning (ML) models. The project will investigate whether physics-informed neural networks (PINNs) can be leveraged to obtain results that outperform established baselines.

Recent approaches in machine wear modelling rely on deep learning over images and sensor streams for wear estimation, while machining practice has long used Taylor’s tool-life equation [2] to capture how operating conditions drive wear and life. Physics-informed machine learning [3] shows that adding lightweight physical constraints or priors can improve generalization, robustness and trust in scientific and industrial settings.

In parallel, effective fusion of heterogeneous sensor modalities and the deployment of computationally efficient models are critical for practical adoption in real-world production environments. This project will explore advanced multimodal data fusion strategies in combination with model compression and efficiency techniques, enabling accurate and deployable wear estimation models that outperform existing baselines.

<h3>How</h3>

During the project you will develop PINN models under the guidance of Sirris domain experts. The goal of the project is to improve on existing baselines by developing multimodal models that integrate physics principles into their modelling process. You will investigate and compare data fusion techniques at different levels (early, intermediate and late fusion) to effectively combine image-based and signal-based information. In addition, you will explore model compression and efficiency methods, including structured pruning, quantization and knowledge distillation, to reduce computational and memory requirements without sacrificing predictive performance, with a view toward real-time or edge deployment in industrial environments.

<h4>Prerequisites</h4>

<ol>
	<li> Solid understanding of Machine Learning and Deep Learning fundamentals </li>
	<li> High-level coding skills in Python </li>
	<li> Interest in physics informed modelling and/or mechanical engineering </li>
</ol>

<ul>
	<li> [1] De Pauw, Lars, Tom Jacobs, and Toon Goedemé. "MATWI: A multimodal automatic tool wear inspection dataset and baseline algorithms." International Conference on Computer Vision Systems. Cham: Springer Nature Switzerland, 2023. </li>
	<li> [2] Lee, Yong Ju, and Hae-Sung Yoon. "Modeling of cutting tool life with power consumption using Taylor’s equation." Journal of Mechanical Science and Technology 37.6 (2023): 3077-3085. </li>
	<li> [3] Cuomo, Salvatore, et al. "Scientific machine learning through physics–informed neural networks: Where we are and what’s next." Journal of Scientific Computing 92.3 (2022): 88 </li>
</ul>