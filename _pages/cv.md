---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, University of Washington (Paul G. Allen School of Computer Science & Engineering), 2025 – present
* B.S. in Computer Engineering with Distinction, University of Washington (Paul G. Allen School of Computer Science & Engineering), 2025
* B.A. in Comparative History of Ideas, University of Washington (College of Arts and Sciences), 2025


Research experience
======
* Jun. 2026 – present: Graduate Student Researcher
  * Allen Institute for AI (Ai2), AllenNLP Scaling Team
  * Integrating multimodal capabilities into OLMo-core for mixture-of-experts LLMs
  * Raised MMMU from 64.92% to 81.75% and CharXiv from 33.00% to 40.60% on 4B and 12B MoE OLMo models
  * Improved OLMo-eval infrastructure to support multimodal evaluation benchmarks
  * Increased training throughput 8x in wall-clock time and 4x in GPU efficiency

* Sep. 2025 – present: Graduate Student Researcher
  * Ai2 PRIOR/Robotics & RAIVN Lab, University of Washington
  * Advisor: Prof. Ranjay Krishna
  * Core contributor to MolmoAct2; built the data-processing and tokenizer pipeline
  * Contributed to MolmoSpaces; built the Isaac Sim conversion pipeline
  * Training a G1 humanoid robot using motion retargeting derived from human video data

* Mar. 2025 – present: Graduate/Undergraduate Researcher
  * Social RL Lab, University of Washington
  * Advisor: Prof. Natasha Jaques
  * Working on self-play RL for generating secure code
  * Steered state-of-the-art LLMs toward human-like behavior using multi-turn RL (OpenRLHF)

* Nov. 2024 – Mar. 2025: Undergraduate Researcher
  * ZLab & RSE Lab, University of Washington
  * Advisors: Prof. Luke Zettlemoyer & Prof. Dieter Fox
  * Investigated internet-scale, unsupervised learning for complex robotic tasks in diverse environments
  * Fine-tuned video-diffusion models to generate robot trajectory videos in a RoboCasa-like environment

* Jan. 2024 – Aug. 2025: Honors Undergraduate Researcher
  * ACME Lab (HLS4ML Group), University of Washington
  * Advisor: Prof. Scott Hauck
  * Authored an honors thesis benchmarking automated neural network hardware acceleration
  * Implemented a neural network in SystemVerilog to compare against HLS code

Industry experience
======
* Jun. 2024 – Sep. 2024: Software Engineer Intern
  * Amazon, AWS SageMaker (Seattle)
  * Architected CI/CD infrastructure using the AWS Cloud Development Kit to automate testing and releases
  * Automated release workflows via conda-forge, eliminating 2–3 weeks of manual work per release
  * Automated AWS-based tests for every contribution to the open-source repository

Skills
======
* Languages: Python, Java, C/C++, Verilog/SystemVerilog, Rust, Bash
* Frameworks & ML systems: PyTorch, CUDA, vLLM, DeepSpeed, OpenRLHF, OLMo-core, open-instruct
* Robotics & simulation: NVIDIA Isaac Sim/Lab, MuJoCo, RoboCasa
* Infrastructure & developer tools: AWS (CDK, SageMaker), Slurm, Docker, Linux, Git, Conda

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
