# Awesome SWE-bench Research

A curated list of research papers, benchmark, frameworks, and resources related to **SWE-bench** and large language models for software engineering.
This repository aims to provide a comprehensive and regularly updated collection of works on evaluation, methods, and applications.

[![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](./LICENSE)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/goodmanpzh/Awesome-SWE-bench/main?logo=github\&color=blue)
![Static Badge](https://img.shields.io/badge/Contributions-welcome-blue.svg?style=flat)

---





## Content

* [Framework](#framework)
* [Papers](#papers)
  * [Survey](#survey)
  * [Benchmark](#benchmark)
  * [Training & Fine-tuning](#training--fine-tuning)
  * [Agentic Coding](#agentic-coding)
  * [Issue Location](#issue-location)
  * [Bug Fix](#bug-fix)
  * [Other Methods](#other-methods)
* [Resources](#resources)
* [Blogs & Talks](#blogs--talks)
* [Contribution](#contribution)

---





## Framework

* **OpenHands: An Open Platform for AI Software Developers as Generalist Agents** <br>
  *Wang et al., 2024.07*. Generalist AI coding agent platform.
  \[[pdf](https://arxiv.org/abs/2407.16741)], \[[code](https://github.com/All-Hands-AI/OpenHands)]

* **Agentless: Demystifying LLM-based Software Engineering Agents** <br>
  *Xia et al., 2024.07*. Localization, fix, verification.
  \[[pdf](https://arxiv.org/abs/2407.01489)], \[[code](https://github.com/OpenAutoCoder/Agentless)]

* **mini-SWE-agent** 
  *2025.05*. \[[code](https://github.com/SWE-agent/mini-SWE-agent)]

* **SWE-agent** 
  \[[code](https://github.com/SWE-agent/SWE-agent)]

* **Trae Agent: An LLM-based Agent for Software Engineering with Test-time Scaling** <br>
  *Trae Research Team et al., 2025.07*. [[pdf](https://arxiv.org/abs/2507.23370)], [[code](https://github.com/bytedance/trae-agent)]

---

## Papers

### Survey

* **Challenges and Paths Towards AI for Software Engineering** <br>
  *Hou et al., 2024.03*. [[pdf](https://arxiv.org/abs/2503.22625)]

* **Software Development Life Cycle Perspective: A Survey of Benchmarks for CodeLLMs and Agents** <br>
  *Zhu et al., 2024.05*. [[pdf](https://arxiv.org/abs/2505.05283)]

---




### Benchmark

* **SWE-bench: Can Language Models Resolve Real-World GitHub Issues?** <br>
  *Jimenez et al., 2024*. [[pdf](https://arxiv.org/abs/2310.06770)], [[code](https://github.com/SWE-bench/SWE-bench/tree/main)], [[leaderboard](https://www.swebench.com/)], [[dataset](https://huggingface.co/datasets/princeton-nlp/SWE-bench)]

* **SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?** <br>
  *Yang et al., 2024*. [[pdf](https://arxiv.org/abs/2410.03859)], [[code](https://github.com/SWE-bench/SWE-bench/tree/main)], [[leaderboard](https://www.swebench.com/multimodal.html)]

* **SWE-bench Multilingual** <br>
  *Khandpur et al., 2024*. [[webpage](https://kabirk.com/multilingual)], [[code](https://github.com/SWE-bench/SWE-bench/tree/main)], [[dataset](https://huggingface.co/datasets/SWE-bench/SWE-bench_Multilingual)]

* **Multi-SWE-bench: A Multilingual Benchmark for Issue Resolving** <br>
  *Zan et al., 2025*. [[pdf](https://arxiv.org/pdf/2504.02605)], [[code](https://github.com/multi-swe-bench/multi-swe-bench)], [[leaderboard](https://multi-swe-bench.github.io/)]

* **SWE-PolyBench: A Multi-language Benchmark for Repository Level Evaluation of Coding Agents** <br>
  *Rashid et al., 2025*. [[pdf](https://arxiv.org/abs/2504.08703)], [[code](https://github.com/amazon-science/SWE-PolyBench)], [[leaderboard](https://amazon-science.github.io/SWE-PolyBench/)], [[dataset](https://huggingface.co/datasets/AmazonScience/SWE-PolyBench)]

* **SWE-bench Goes Live!** <br>
  *Zhang et al., 2025*. [[pdf](https://arxiv.org/abs/2505.23419)], [[code](https://github.com/microsoft/SWE-bench-Live)], [[leaderboard](https://swe-bench-live.github.io/)], [[dataset](https://huggingface.co/datasets/SWE-bench-Live/SWE-bench-Live)]

* **SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents** <br>
  *Mündler et al., 2024*. [[pdf](https://arxiv.org/abs/2406.12952)], [[code](https://github.com/logic-star-ai/swt-bench)], [[leaderboard](https://swtbench.com/)]

* **SWE-Factory: Your Automated Factory for Issue Resolution Training Data and Evaluation Benchmarks** <br>
  *Guo et al., 2025.06*. [[pdf](https://arxiv.org/abs/2506.10954)], [[code](https://github.com/DeepSoftwareAnalytics/swe-factory)]

* **SWE-Bench-CL: Continual Learning for Coding Agents** <br>
  *Kocman et al., 2025.07*. [[pdf](https://arxiv.org/abs/2507.00014)]

* **SPICE: An Automated SWE-Bench Labeling Pipeline for Issue Clarity, Test Coverage, and Effort Estimation** <br>
  *Oliva et al., 2025.07*. [[pdf](https://arxiv.org/abs/2507.09108)]

---





### Training & Fine-tuning

* **SWE-Gym: Training Software Engineering Agents and Verifiers with SWE-Gym** <br>
  *Pan et al., 2024.12*. Provides training and evaluation environment for SWE agents.
  \[[pdf](https://arxiv.org/pdf/2412.21139)], \[[code](https://github.com/SWE-Gym/SWE-Gym)], \[[models](https://huggingface.co/SWE-Gym)]

* **PatchPilot: A Cost-Efficient SWE Agent with Early Formal Verification** <br>
  *Li et al., 2025.02*. \[[pdf](https://arxiv.org/abs/2502.02747)], \[[code](https://github.com/ucsb-mlsec/PatchPilot)]

* **SWE-Fixer: Training Open-Source LLMs for GitHub Issue Resolution** <br>
  *Xie et al., 2025.01*. \[[pdf](https://arxiv.org/abs/2501.05040)], \[[code](https://github.com/InternLM/SWE-Fixer)]

* **SoRFT: Issue Resolving with Subtask-oriented Reinforced Fine-Tuning** <br>
  *Ma et al., 2025.02*. \[[pdf](https://arxiv.org/abs/2502.20127)]

* **SWE-Dev: Building SWE Agents with Training and Inference Scaling** <br>
  *Wang et al., 2025.06*. \[[pdf](https://arxiv.org/abs/2506.07636)], \[[code](https://github.com/THUDM/SWE-Dev)]

* **SWE-smith: Scaling Data for Software Engineering Agents** <br>
  *Yang et al., 2025.04*. \[[pdf](https://arxiv.org/abs/2504.21798)], \[[code](https://github.com/SWE-bench/SWE-smith)], \[[web](https://swesmith.com/)]

* **Skywork-SWE: Unveiling Data Scaling Laws for Software Engineering in LLMs** <br>
  *Zeng et al., 2025.06*. [[pdf](https://arxiv.org/abs/2506.19290)]

* **Agent-RLVR: Training Software Engineering Agents via Guidance and Environment Rewards** <br>
  *Da et al., 2025.06*. [[pdf](https://arxiv.org/abs/2506.11425)]

* **Training Long-Context, Multi-Turn Software Engineering Agents with Reinforcement Learning** <br>
  *Zhang et al., 2025.08*. [[pdf](https://arxiv.org/abs/2508.03501)]

* **SWE-Flow: Synthesizing Software Engineering Data in a Test-Driven Manner** <br>
  *Luo et al., 2025.06*. [[pdf](https://arxiv.org/abs/2506.09003)]

* **Repository Structure-Aware Training Makes SLMs Better Issue Resolver** <br>
  *Zhou et al., 2024.12*. [[pdf](https://arxiv.org/abs/2412.19031)]

* **RepoForge: Training a SOTA Fast-thinking SWE Agent with an End-to-End Data Curation Pipeline Synergizing SFT and RL at Scale** <br>
  *Chen et al., 2025.08*. Training a state-of-the-art fast-thinking software engineering agent via an end-to-end data curation pipeline combining SFT and RL.
  \[[pdf](https://arxiv.org/abs/2508.01550)]

---





### Agentic Coding

* **SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering** <br>
  *Yang et al., 2024.05*. \[[pdf](https://arxiv.org/abs/2405.15793)], \[[code](https://github.com/SWE-agent/SWE-agent)]

* **NEMOTRON-CORTEXA: Enhancing LLM Agents for Software Engineering Tasks via Improved Localization and Solution Diversity** <br>
  *Sohrabizadeh et al., 2025.05*. \[[pdf](https://openreview.net/pdf?id=k6p8UKRdH7)]

* **Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute** <br>
  *Ma et al., 2025.03*. [[pdf](https://arxiv.org/abs/2503.23803)], [[code](https://github.com/yingweima2022/SWE-Reasoner)]

* **Unified Software Engineering Agent as AI Software Engineer** <br>
  *Applis et al., 2025.06*. [[pdf](https://arxiv.org/abs/2506.14683)]

* **SemAgent: A Semantics Aware Program Repair Agent** <br>
  *Pabba et al., 2025.06*. [[pdf](https://arxiv.org/abs/2506.16650)]

* **SWE-Exp: Experience-Driven Software Issue Resolution** <br>
  *Da et al., 2025.07*. [[pdf](https://arxiv.org/abs/2507.23361)]

* **Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents** <br>
  *Srinivasa et al., 2025.05*. [[pdf](https://arxiv.org/abs/2505.13652)]

* **CodeR: Issue Resolving with Multi-Agent and Task Graphs** <br>
  *Ma et al., 2024.06*. [[pdf](https://arxiv.org/abs/2406.01304)], [[code](https://github.com/yingweima2022/CodeR)]
---





### Issue Location

* **SweRank: Software Issue Localization with Code Ranking** <br>
  *Reddy et al., 2025.05*. \[[pdf](https://arxiv.org/abs/2505.07849)]

* **CoRet: Improved Retriever for Code Editing** <br>
  *Fehr et al., 2025.05*. \[[pdf](https://arxiv.org/abs/2505.24715)]

* **CoSIL: Software Issue Localization via LLM-Driven Graph Searching** <br>
  *Jiang et al., 2025.03*. \[[pdf](https://arxiv.org/abs/2503.22424)], \[[code](https://github.com/ZhonghaoJiang/CoSIL)]

* **LocAgent: Graph-Guided LLM Agents for Code Localization** <br>
  *Chen et al., 2025.03*. \[[pdf](https://arxiv.org/abs/2503.09089)], \[[code](https://github.com/gersteinlab/LocAgent)]

* **The SWE-Bench Illusion: When LLMs Remember Instead of Reason** <br>
  *Liang et al., 2025.06*. \[[pdf](https://arxiv.org/abs/2506.12286)]

---





### Bug Fix

* **SWE-Synth: Synthesizing Verifiable Bug-Fix Data** <br>
  *Pham et al., 2025.04*. \[[pdf](https://arxiv.org/abs/2504.14757)], \[[code](https://github.com/FSoft-AI4Code/SWE-Synth)], \[[dataset](https://huggingface.co/swesynth)]

* **Exploring the Potential of Conversational Test Suite Based Program Repair on SWE-bench** <br>
  *Fan et al., 2024.10*. [[pdf](https://arxiv.org/abs/2410.04485)]

* **Co-PatcheR: Collaborative Software Patching with Component(s)-specific Small Reasoning Models** <br>
  *Tang et al., 2025.05*. Collaborative software patching using component-specific small reasoning models.
  \[[pdf](https://arxiv.org/abs/2505.18955)]

---





### Other Methods

* **UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench** <br>
  *Yu et al., 2025.06*. \[[pdf](https://arxiv.org/abs/2506.09289)], \[[code](https://github.com/CUHK-Shenzhen-SE/UTBoost)]

* **SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents** <br>
  *Mündler et al., 2024*. BenchMark fot Testing Generation. [[pdf](https://arxiv.org/abs/2406.12952)], \[[code](https://github.com/logic-star-ai/swt-bench)], \[[Leaderboard](https://swtbench.com/)]

* **Code Graph Model (CGM): A Graph-Integrated Large Language Model for Repository-Level Software Engineering Tasks** <br>
  *Tao et al., 2025.05*. [[pdf](https://arxiv.org/abs/2505.16901)]

* **SWE-Exp: Experience-Driven Software Issue Resolution** <br>
  *Chen et al., 2025.07*. Experience-driven approach for software issue resolution.
  \[[pdf](https://arxiv.org/abs/2507.23361)]

---





## Resources

* [SWE-bench Leaderboard](https://www.swebench.com/)
* [Awesome-LLM-SWE-Bench](https://github.com/wasiahmad/Awesome-LLM-SWE-Bench)

---





## Blogs & Talks

* **Raising the bar on SWE-bench Verified with Claude 3.5 Sonnet** <br>
  *Anthropic Engineering, 2025.05*. \[[blog](https://www.anthropic.com/engineering/swe-bench-sonnet)]

---





## Contribution

We welcome contributions! There are cases where we miss important works in this field, please feel free to contribute and promote your awesome work or other related works here! Thanks for the efforts in advance.








