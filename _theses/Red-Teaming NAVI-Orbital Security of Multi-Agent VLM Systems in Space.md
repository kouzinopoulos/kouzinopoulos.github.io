---
layout: post
title: "Red-Teaming NAVI-Orbital Security of Multi-Agent VLM Systems in Space"
inline: false
related_posts: false
tags: ["2026", applied, space]
---

<i>This project will be performed in collaboration with Dr. Misha Glazunov (DACS, Maastricht University) and Dr. Angela Cratere (DACS, Maastricht University)</i>

<h3>Objective</h3>

Earth observation (EO) satellites can generate more imagery than can be efficiently downlinked or inspected on Earth, making onboard filtering and semantic compression increasingly important [1]. NAVI-Orbital [2] recently demonstrated a Vision-Language Model (VLM) onboard a LEO spacecraft to classify EO imagery and generate natural-language scene descriptions. However, the original study did not evaluate adversarial prompts or malicious inputs, and its existing validation mechanisms cannot fully prevent unreliable outputs. The objective of this project is to investigate the security and robustness of a NAVI-Orbital-style onboard VLM system, including attacks that target individual agents as well as those that exploit the interactions between them, and to explore and develop some lightweight defenses to reduce the attack surface. 

<h3>How</h3>

Using the NAVI-Orbital pipeline [2] and the open-access EO datasets [e.g., 3, 4], the project will investigate multiple attack vectors against onboard multimodal AI. You will consider different attack surfaces, including inference-time attacks, such as prompt-based attacks [5, 6] and image-based attacks [7], as well as training-time attacks such as a controlled backdoor introduced by fine-tuning a LoRA adapter [8, 9]. Because the system is multi-agent, you will also investigate attacks that exploit the interactions between agents, such as indirect prompt injection, control-flow manipulation, and resource-exhaustion attacks that degrade scarce onboard compute [6]. For each attack type, you will define a realistic threat model, implement the attack, and measure its impact on model outputs. You will then propose and evaluate defence strategies designed to reduce attack success.  

<h3>Outputs</h3>

The project will deliver a reproducible security evaluation framework of a NAVI-Orbital-style multimodal pipeline, including implementations of the aforementioned attacks, together with lightweight defence strategies to reduce the attack surface. If the validation yields strong results, they could lead to a publication and presentation at an international venue.

<h4>Prerequisites</h4>

<ol>
	<li>Good Python skills, good machine learning and LLM knowledge as well as interest in space systems, security and LLM-based agent systems.</li>
</ol>

<ul>
	<li>[1] Nguyen, Loc X., et al. (2026). "A Comprehensive Survey on Semantic Communication in Non-Terrestrial Networks: Architectures, Methodologies, and Challenges." arXiv.</li>
	<li>[2] Victoria, J. M. D et al., (2026). "NAVI-Orbital: First In-Orbit Demonstration of a Zero-Shot Vision-Language Model for Autonomous Earth Observation." arXiv.  </li>
	<li>[3] Xia, G. S. et al. (2017). "AID: A Benchmark Dataset for Performance Evaluation of Aerial Scene Classification." IEEE Transactions on Geoscience and Remote Sensing.  </li>
	<li>[4] Helber, P. et al. (2019). "EuroSAT: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification." IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing.  </li>
	<li>[5] Greshake et al. (2023). "Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection". AISec, ACM CCS. </li>
	<li>[6] Debenedetti, E. et al. (2024). "AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents." NeurIPS 2024 Track Datasets and Benchmarks. </li>
	<li>[7] Zhao, X. et al. (2026). "Pushing the Frontier of Black-Box LVLM Attacks via Fine-Grained Detail Targeting." arXiv.</li>  
	<li>[8] Li, Y. et al. (2025) "BACKDOORLLM: A Comprehensive Benchmark for Backdoor Attacks and Defenses on Large Language Models." NeurIPS 2025 Track Datasets and Benchmarks. </li>
	<li>[9] Google AI for Developers. (2026). "Fine-Tune Gemma for Vision Tasks Using Hugging Face Transformers and QLoRA." https://ai.google.dev/gemma/docs/core/huggingface_vision_finetune_qlora</li>
</ul>