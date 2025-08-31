# Awesome SWE-bench Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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
  * [Training & Fine-tuning](#training--fine-tuning)
  * [Agentic Coding](#agentic-coding)
  * [Benchmark](#benchmark)
  * [Issue Location](#issue-location)
  * [Bug Fix](#bug-fix)
  * [Other Methods](#other-methods)
* [Resources](#resources)
* [Blogs & Talks](#blogs--talks)
* [Contribution](#contribution)

---





## Framework

* **OpenHands: An Open Platform for AI Software Developers as Generalist Agents**
  *Wang et al., 2024.07*. Generalist AI coding agent platform.
  \[[Paper](https://arxiv.org/abs/2407.16741)], \[[Code](https://github.com/All-Hands-AI/OpenHands)]

* **Agentless: Demystifying LLM-based Software Engineering Agents**
  *Xia et al., 2024.07*. \[[pdf](https://arxiv.org/abs/2407.01489)], \[[code](https://github.com/OpenAutoCoder/Agentless)]
  ![](https://img.shields.io/badge/Arxiv-orange)


---

## Papers

### Survey



---





### Benchmark

* **SWE-bench: Can Language Models Resolve Real-World GitHub Issues?**
  *Jimenez et al., 2024.10*. \[[paper](https://arxiv.org/abs/2310.06770)], \[[code](https://github.com/SWE-bench/SWE-bench/tree/main)], \[[leaderboard](https://www.swebench.com/)], \[[dataset](https://huggingface.co/datasets/princeton-nlp/SWE-bench)]

* **SWE-bench Multimodal**
  *Yang et al., 2024.10*. \[[paper](https://arxiv.org/abs/2410.03859)], \[[leaderboard](https://www.swebench.com/multimodal.html)]

* **SWE-bench Multilingual**
  *Khandpur et al., 2024*. \[[webpage](https://kabirk.com/multilingual)], \[[dataset](https://huggingface.co/datasets/SWE-bench/SWE-bench_Multilingual)]

* **Multi-SWE-bench**
  *Zan et al., 2025.04*. \[[paper](https://arxiv.org/pdf/2504.02605)], \[[code](https://github.com/multi-swe-bench/multi-swe-bench)], \[[leaderboard](https://multi-swe-bench.github.io/)]

* **SWE-PolyBench**
  *Rashid et al., 2025.04*. \[[paper](https://arxiv.org/abs/2504.08703)], \[[code](https://github.com/amazon-science/SWE-PolyBench)], \[[leaderboard](https://amazon-science.github.io/SWE-PolyBench/)], \[[dataset](https://huggingface.co/datasets/AmazonScience/SWE-PolyBench)]

* **SWE-bench Live**
  *Zhang et al., 2025.05*. \[[paper](https://arxiv.org/abs/2505.23419)], \[[code](https://github.com/microsoft/SWE-bench-Live)], \[[leaderboard](https://swe-bench-live.github.io/)], \[[dataset](https://huggingface.co/datasets/SWE-bench-Live/SWE-bench-Live)]

* **SWT-Bench**
  *Mündler et al., 2024.06*. \[[paper](https://arxiv.org/abs/2406.12952)], \[[code](https://github.com/logic-star-ai/swt-bench)], \[[leaderboard](https://swtbench.com/)]

* **SWE-rebench**
  *Badertdinov et al., 2025.05*. \[[paper](https://arxiv.org/abs/2505.20411)], \[[dataset](https://huggingface.co/datasets/nebius/SWE-rebench)], \[[leaderboard](https://swe-rebench.com/leaderboard)]

---





### Training & Fine-tuning

* **SWE-Gym: Training Software Engineering Agents and Verifiers**
  *Pan et al., 2024.12*. Provides training and evaluation environment for SWE agents.
  \[[Paper](https://arxiv.org/pdf/2412.21139)], \[[Code](https://github.com/SWE-Gym/SWE-Gym)], \[[Models](https://huggingface.co/SWE-Gym)]

* **PatchPilot: A Cost-Efficient SWE Agent with Early Formal Verification**
  *Li et al., 2025.02*. \[[pdf](https://arxiv.org/abs/2502.02747)], \[[code](https://github.com/ucsb-mlsec/PatchPilot)]

* **SWE-Fixer: Training Open-Source LLMs for GitHub Issue Resolution**
  *Xie et al., 2025.01*. \[[pdf](https://arxiv.org/abs/2501.05040)], \[[code](https://github.com/InternLM/SWE-Fixer)]

* **SoRFT: Issue Resolving with Subtask-oriented Reinforced Fine-Tuning**
  *Ma et al., 2025.02*. \[[pdf](https://arxiv.org/abs/2502.20127)]

* **SWE-Dev: Building SWE Agents with Training and Inference Scaling**
  *Wang et al., 2025.06*. \[[pdf](https://arxiv.org/abs/2506.07636)], \[[code](https://github.com/THUDM/SWE-Dev)]

* **SWE-smith: Scaling Data for Software Engineering Agents**
  *Yang et al., 2025.04*. \[[pdf](https://arxiv.org/abs/2504.21798)], \[[code](https://github.com/SWE-bench/SWE-smith)], \[[web](https://swesmith.com/)]

---





### Agentic Coding

* **SWE-agent**
  *Yang et al., 2024.05*. \[[pdf](https://arxiv.org/abs/2405.15793)], \[[code](https://github.com/SWE-agent/SWE-agent)]

* **Nemotron-CORTEXA**
  *Sohrabizadeh et al., 2025.05*. \[[pdf](https://openreview.net/pdf?id=k6p8UKRdH7)]

---





### Issue Location

* **SweRank: Software Issue Localization with Code Ranking**
  *Reddy et al., 2025.05*. \[[pdf](https://arxiv.org/abs/2505.07849)]

* **CoRet: Improved Retriever for Code Editing**
  *Fehr et al., 2025.05*. \[[pdf](https://arxiv.org/abs/2505.24715)]

* **CoSIL: Software Issue Localization via LLM-Driven Graph Searching**
  *Jiang et al., 2025.03*. \[[pdf](https://arxiv.org/abs/2503.22424)], \[[code](https://github.com/ZhonghaoJiang/CoSIL)]

* **LocAgent: Graph-Guided LLM Agents for Code Localization**
  *Chen et al., 2025.03*. \[[pdf](https://arxiv.org/abs/2503.09089)], \[[code](https://github.com/gersteinlab/LocAgent)]

* **The SWE-Bench Illusion: When LLMs Remember Instead of Reason**
  *Liang et al., 2025.06*. \[[pdf](https://arxiv.org/abs/2506.12286)]

---





### Bug Fix

* **SWE-Synth: Synthesizing Verifiable Bug-Fix Data**
  *Pham et al., 2025.04*. \[[pdf](https://arxiv.org/abs/2504.14757)], \[[code](https://github.com/FSoft-AI4Code/SWE-Synth)], \[[dataset](https://huggingface.co/swesynth)]

---





### Other Methods

* **UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench**
  *Yu et al., 2025.06*. \[[pdf](https://arxiv.org/abs/2506.09289)], \[[code](https://github.com/CUHK-Shenzhen-SE/UTBoost)]

---





## Resources

* [SWE-bench Leaderboard](https://www.swebench.com/)
* [SWE-bench Multimodal Leaderboard](https://www.swebench.com/multimodal.html)
* [SWE-bench Live Leaderboard](https://swe-bench-live.github.io/)
* [SWT-Bench Leaderboard](https://swtbench.com/)
* [SWE-PolyBench Leaderboard](https://amazon-science.github.io/SWE-PolyBench/)
* [SWE-rebench Leaderboard](https://swe-rebench.com/leaderboard)
* [Datasets on Hugging Face](https://huggingface.co/datasets)

---





## Blogs & Talks

* **Raising the bar on SWE-bench Verified with Claude 3.5 Sonnet**
  *Anthropic Engineering, 2025.05*. \[[blog](https://www.anthropic.com/engineering/swe-bench-sonnet)]

---





## Contribution

We welcome contributions! There are cases where we miss important works in this field, please feel free to contribute and promote your awesome work or other related works here! Thanks for the efforts in advance.

