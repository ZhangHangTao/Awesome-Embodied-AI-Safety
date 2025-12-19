# Awesome-Embodied-AI-Safety [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of publications on safety in Embodied AI, including topics like adversarial attacks, alignment, backdoor, jailbreak, prompt injection, surveys, and safety frameworks.

<strong>Last Update: Oct. 20th, 2025</strong>.

#### Please feel free to send me [pull requests](https://github.com/ZhangHangTao/Awesome-Embodied-AI-Safety/blob/main/how-to-PR.md) or [email](mailto:zhanghangtao7@163.com) to add papers! <br>

If you find this repository useful, please consider STARing this list.

---
## Overview

  - [Surveys](#Surveys)
  - [Jailbreak Attack and Defense](#Jailbreak-Attack-and-Defense)
  - [Adversarial Attack and Defense](#Adversarial-Attack-and-Defense)
  - [Backdoor Attack and Defense](#Backdoor-Attack-and-Defense)
  - [Prompt Injection Attack and Defense](#Prompt-Injection-Attack)
  - [Alignment and Safety Frameworks](#Alignment-and-Safety-Frameworks)

---
## Surveys
* "Towards Robust and Secure Embodied AI: A Survey on Vulnerabilities and Attacks", *Arxiv 2025*, [[pdf](https://arxiv.org/abs/2502.13175)]


## Jailbreak Attack and Defense
* "BadRobot: Jailbreaking Embodied LLMs in the Physical World", *ICLR 2025*, `Three jailbreak attacks in the black-box setting`, [[pdf](https://arxiv.org/abs/2407.20242)]
* "Jailbreaking LLM-Controlled Robot", *ICRA 2025*, `Jailbreak attacks in the white-box, gray-box, and black-box settings`, [[pdf](https://arxiv.org/abs/2410.13691)]
* "POEX: Policy Executable Embodied AI Jailbreak Attacks". *Arxiv 2024*, [[pdf](https://arxiv.org/abs/2412.16633)]
* "Concept Enhancement Engineering: A Lightweight and Efficient Robust Defense Against Jailbreak Attacks in Embodied AI". *Arxiv 2025*, [[pdf](https://arxiv.org/abs/2504.13201)]

## Adversarial Attack and Defense
* "Highlighting the Safety Concerns of Deploying LLMs/VLMs in Robotics (On the Vulnerability of LLM/VLM-Controlled Robotics)", ArXiv 2024, `Studying system robustness to input modality (image/text) perturbations`, [[pdf](https://arxiv.org/abs/2402.10340)] 

* "Exploring the Adversarial Vulnerabilities of Vision-Language-Action Models in Robotics", ArXiv 2024, `Adversarial Attacks aginst VLA models`, [[pdf](https://arxiv.org/abs/2411.13587)]

* "Rethinking Robustness Assessment: Adversarial Attacks on Learning-based Quadrupedal Locomotion Controllers", ArXiv 2024, [[pdf](https://arxiv.org/abs/2405.12424)]

* "Exploring the Robustness of Decision-Level Through Adversarial Attacks on LLM-Based Embodied Models", ACM MM 2024, [[pdf](https://arxiv.org/abs/2405.19802)] 

* "Malicious Path Manipulations via Exploitation of Representation Vulnerabilities of Vision-Language Navigation Systems", IROS 2024, [[pdf](https://arxiv.org/abs/2407.07392)] 

* "Spatiotemporal Attacks for Embodied Agents", ECCV 2020, [[pdf](https://arxiv.org/abs/2405.19802)] 

* "Embodied red teaming for auditing robotic foundation models", NeurIPS Workshop 2024, `Evaluating instruction-following performance`, [[pdf](https://arxiv.org/abs/2411.18676)]

## Backdoor Attack and Defense
* "TrojanRobot: Backdoor Attacks Against LLM-based Embodied Robots in the Physical World", Arxiv 2024, `Inserting LLM-as-a-backdoor into Embodied Systems`, [[pdf](https://arxiv.org/abs/2411.11683)]

* "Compromising Embodied Agents with Contextual Backdoor Attacks", TIFS 2025, `Poisoning LLM's ICL to generate backdoored programs`, [[pdf](https://arxiv.org/abs/2408.02882)] 

* "Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-Based Decision-Making Systems", ICLR 2025, `Data Poisoning Backdoor Attacks on LLM Decision-Making Systems`, [[pdf](https://arxiv.org/abs/2405.20774)]

* "BadVLA: Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization", Arxiv 2025, `Untargeted Backdoor Attacks Against Visual Encoders`, [[pdf](https://arxiv.org/abs/2505.16640)]

## Prompt Injection Attack 
* "A Study on Prompt Injection Attack Against LLM-Integrated Mobile Robotic Systems", ISSRE Wksp 2024, [[pdf](https://ieeexplore.ieee.org/abstract/document/10771340/)] 




## Alignment and Safety Frameworks
* "Robots Enact Malignant Stereotypes", FAccT 2022, [[pdf](https://dl.acm.org/doi/abs/10.1145/3531146.3533138)] 

* "LLM-Driven Robots Risk Enacting Discrimination, Violence, and Unlawful Actions", ArXiv 2024, [[pdf](https://arxiv.org/abs/2406.08824)] 

* "EAIRiskBench: Towards Evaluating Physical Risk Awareness for Task Planning of Foundation Model-based Embodied AI Agents", ArXiv 2024, [[pdf](https://arxiv.org/abs/2408.04449)] 

* "SafeVLA: Towards Safety Alignment of Vision-Language-Action Model via Safe Reinforcement Learning", Arxiv 2025, [[pdf](https://arxiv.org/abs/2503.03480)]

* "Don’t Let Your Robot be Harmful: Responsible Robotic Manipulation", ArXiv 2024, [[pdf](https://arxiv.org/abs/2411.18289)]

* "Safeembodai: A Safety Framework for Mobile Robots in Embodied AI Systems", ArXiv 2024, [[pdf](https://arxiv.org/abs/2409.01630)] 

* "Beyond Model Jailbreak: Systematic Dissection of the \"Ten Deadly Sins\" in Embodied Intelligence", Arxiv 2025, `System-level audit of Unitree Go2; taxonomy of ten cross-layer vulnerabilities beyond model jailbreak`, [[pdf](https://arxiv.org/abs/2512.06387)]






If this repository has supported your research in any way, we would be sincerely grateful for your consideration of citing our work :)
```
@inproceedings{zhangbadrobot,
  title={BadRobot: Jailbreaking Embodied LLM Agents in the Physical World},
  author={Zhang, Hangtao and Zhu, Chenyu and Wang, Xianlong and Zhou, Ziqi and Yin, Changgan and Li, Minghui and Xue, Lulu and Wang, Yichen and Hu, Shengshan and Liu, Aishan and others},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2025}
}
```
