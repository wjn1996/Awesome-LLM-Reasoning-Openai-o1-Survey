# Awesome LLM Reasoning Openai-o1 Survey

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  [![License](https://img.shields.io/github/license/hijkzzz/Awesome-LLM-Strawberry)](https://github.com/wjn1996/Awesome-LLM-Reasoning-Openai-o1-Survey/blob/main/LICENSE)  ![Visitors](https://visitor-badge.lithub.cc/badge?page_id=wjn1996.awesome-llm-reasoning-openai-o1-survey&left_text=Visitors)  ![Stars](https://img.shields.io/github/stars/wjn1996/Awesome-LLM-Reasoning-Openai-o1-Survey?color=yellow)  ![Forks](https://img.shields.io/github/forks/wjn1996/Awesome-LLM-Reasoning-Openai-o1-Survey?color=9cf)


The related works and background techniques about OpenAI o1, including LLM reasoning, self-play reinforcement learning, complex logic reasoning, scaling law, etc.


## Introduction


## Survey Papers
- **A Survey on Self-play Methods in Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2408.01072)] (2024)
  - Ruize Zhang, Zelai Xu, Chengdong Ma, Chao Yu, Wei-Wei Tu, Shiyu Huang, Deheng Ye, Wenbo Ding, Yaodong Yang, Yu Wang
  - Tencent, Tsinghua

## Related Papers

### Complex Logical Reasoning
- **Generative Language Modeling for Automated Theorem Proving** [[Paper](https://arxiv.org/pdf/2009.03393)] (2020)
  - Stanislas Polu, Ilya Sutskever
  - OpenAI
- **Hypothesis Search: Inductive Reasoning with Language Models** [[Paper](https://openreview.net/pdf?id=G7UtIGQmjm)] (ICLR 2024)
  - Ruocheng Wang, Eric Zelikman, Gabriel Poesia, Yewen Pu, Nick Haber, Noah D. Goodman
  - Stanford, Autodesk Research
- **Phenomenal Yet Puzzling: Testing Inductive Reasoning Capabilities of Language Models with Hypothesis Refinement** [[Paper](https://openreview.net/pdf?id=bNt7oajl2a)] (ICLR 2024)
  - Linlu Qiu, Liwei Jiang, Ximing Lu, Melanie Sclar, Valentina Pyatkin, Chandra Bhagavatula, Bailin Wang, Yoon Kim, Yejin Choi, Nouha Dziri, Xiang Ren
  - MIT, Allen AI, UW, USC
- **Training Verifiers to Solve Math Word Problems** [[Paper](https://arxiv.org/pdf/2110.14168)] (2021)
  - Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman
  - OpenAI
- **To CoT or not to CoT? Chain-of-thought Helps Mainly on Math and Symbolic Reasoning** [[Paper](https://arxiv.org/pdf/2409.12183)] (2024.9)
  - Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, Dongwei Jiang, Manya Wadhwa, Prasann Singhal, Xinyu Zhao, Xi Ye, Kyle Mahowald, Greg Durrett
  - The University of Texas at Austin, Johns Hopkins University, Princeton University

### Reasoning Bootstrapping
- **STaR: Self-Taught Reasoner Bootstrapping Reasoning With Reasoning** [[Paper]](https://papers.nips.cc/paper_files/paper/2022/file/639a9a172c044fbb64175b5fad42e9a5-Paper-Conference.pdf) [[Github]](https://github.com/ezelikman/STaR) (NeurIPS 2022)
  - Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman
  - Stanford, Google
- **Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking** [[Paper](https://arxiv.org/pdf/2403.09629)] [[Github](https://github.com/ezelikman/quiet-star)] (2022)
  - Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman
  - Stanford, Notbad AI
- **Training Chain-of-thought via Latent-variable Inference** [[Paper](https://papers.nips.cc/paper_files/paper/2023/file/e69a9560c450ca76584d9eb37e7f5ae8-Paper-Conference.pdf)] (NeurIPS 2023)
  - Du Phan, Matthew D. Hoffman, David Dohan, Sholto Douglas, Tuan Anh Le, Aaron Parisi, Pavel Sountsov, Charles Sutton, Sharad Vikram, Rif A. Saurous
  - Google
- **Chain-of-thought Reasoning without Prompting** [[Paper](https://arxiv.org/pdf/2402.10200)] (2024)
  - Xuezhi Wang, Denny Zhou
  - Google DeepMind
- **Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers** [[Paper](https://arxiv.org/pdf/2408.06195)] [[Github](https://github.com/zhentingqi/rStar)] (2024)
  - Zhenting Qi, Mingyuan Ma, Jiahang Xu, Li Lyna Zhang, Fan Yang, Mao Yang
  - MSRA, Harvard University

### Reasoning Scaling Law
- **Large Language Monkeys: Scaling Inference Compute with Repeated Sampling** [[Paper](https://arxiv.org/pdf/2407.21787)] (2024)
  - Bradley Brown, Jordan Juravsky, Ryan Ehrlich, Ronald Clark, Quoc V. Le, Christopher Ré, Azalia Mirhoseini
  - Stanford, Oxford, Google DeepMind
- **Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters** [[Paper](https://arxiv.org/pdf/2408.03314)] (2024)
  - Charlie Snell, Jaehoon Lee, Kelvin Xu, Aviral Kumar
  - UC Berkeley, Google DeepMind
- **An Empirical Analysis of Compute-Optimal Inference for Problem-Solving with Language Models** [[Paper](https://arxiv.org/pdf/2408.00724)] (2024)
  - Yangzhen Wu, Zhiqing Sun, Shanda Li, Sean Welleck, Yiming Yang
  - Tsinghua, CMU
- **Training Language Models to Self-Correct via Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2409.12917)] (2024)
  - Evan Wang, Federico Cassano, Catherine Wu, Yunfeng Bai, Will Song, Vaskar Nath, Ziwen Han, Sean Hendryx, Summer Yue, Hugh Zhang
  - Google DeepMind
- **From Medprompt to o1: Exploration of Run-Time Strategies for Medical Challenge Problems and Beyond** [[https://arxiv.org/abs/2411.03590]] (2024)
  - Harsha Nori, Naoto Usuyama, Nicholas King, Scott Mayer McKinney, Xavier Fernandes, Sheng Zhang, Eric Horvitz
  - Microsoft, OpenAI

### Self-play Learning
- **Mastering Chess and Shogi by Self-play with a General Reinforcement Learning Algorithm** [[Paper](https://arxiv.org/pdf/1712.01815)] (2017)
  - David Silver, Thomas Hubert, Julian Schrittwieser, Ioannis Antonoglou, Matthew Lai, Arthur Guez,Marc Lanctot, Laurent Sifre, Dharshan Kumaran, Thore Graepel, Timothy Lillicrap, Karen Simonyan, Demis Hassabis
  - Google DeepMind
- **Language Models Can Teach Themselves to Program Better** [[Paper](https://openreview.net/pdf?id=SaRj2ka1XZ3)] [[Github](https://github.com/microsoft/PythonProgrammingPuzzles)] (ICLR 2023)
  - Patrick Haluptzok, Matthew Bowers, Adam Tauman Kalai
  - Microsoft Research, MIT
- **Large Language Models Can Self-Improve** [[Paper](https://aclanthology.org/2023.emnlp-main.67.pdf)]
  - Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han
  - University of Illinois at Urbana-Champaign, Google
- **Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models** [[Paper](https://openreview.net/pdf?id=O4cHTxW9BS)] [[Github](https://github.com/uclaml/SPIN)] (ICML 2024)
  - Zixiang Chen, Yihe Deng, Huizhuo Yuan, Kaixuan Ji, Quanquan Gu
  - UCLA
- **Self-Play Preference Optimization for Language Model Alignment** [[Paper](https://arxiv.org/pdf/2405.00675)] [[Github](https://github.com/uclaml/SPPO)] (2024)
  - Yue Wu, Zhiqing Sun, Huizhuo Yuan, Kaixuan Ji, Yiming Yang, Quanquan Gu
  - UCLA
- **Scalable Online Planning via Reinforcement Learning Fine-Tuning** [[Paper](https://arxiv.org/pdf/2109.15316)] (NeurIPS 2021)
  - Arnaud Fickinger, Hengyuan Hu, Brandon Amos, Stuart Russell, Noam Brown
- **Generative Verifiers: Reward Modeling as Next-Token Prediction** [[Paper](https://arxiv.org/pdf/2408.15240)] (2024)
  - Lunjun Zhang, Arian Hosseini, Hritik Bansal, Mehran Kazemi, Aviral Kumar, Rishabh Agarwal
  - Google DeepMind
- **Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo Tree Self-refine with LLaMa-3 8B** [[Paper](https://arxiv.org/pdf/2406.07394)] (2024)
  - Di Zhang, Xiaoshui Huang, Dongzhan Zhou, Yuqiang Li, Wanli Ouyang
  - Fudan University, Shanghai AI Lab
- **Interpretable Contrastive Monte Carlo Tree Search Reasoning** [[Paper](https://arxiv.org/abs/2410.01707)] (2024)
  - Zitian Gao, Boye Niu, Xuzheng He, Haotian Xu, Hongzhang Liu, Aiwei Liu, Xuming Hu, Lijie Wen
  - The University of Sydney, Peking University, Xiaohongshu, Shanghai AI Lab, Tsinghua, HKUST

### Step-wise and Process-based Optimization
- **Solving Math Word Problems with Process-and Outcome-based Feedback** [[Paper](https://arxiv.org/pdf/2211.14275)] (2022)
  - Jonathan Uesato, Nate Kushman, Ramana Kumar, Francis Song, Noah Siegel, Lisa Wang, Antonia, Creswell, Geoffrey Irving, Irina Higgins
  - Google DeepMind
- **Thinking Fast and Slow With Deep Learning and Tree Search** [[Paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/d8e1344e27a5b08cdfd5d027d9b8d6de-Paper.pdf)] (NeurIPS 2017)
  - Thomas Anthony, Zheng Tian, David Barber
  - University College Londo, Alen
- **Let’s Verify Step by Step** [[Paper](https://arxiv.org/pdf/2305.20050)] (2023)
  - Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe
  - OpenAI
- **OVM, Outcome-supervised Value Models for Planning in Mathematical Reasoning**  [[Paper](https://arxiv.org/abs/2311.09724)] (Findings of NAACL 2024)
  - Fei Yu, Anningzhe Gao, Benyou Wang
  - The Chinese University of Hong Kong, Shenzhen (CUHKSZ) & Shenzhen Research Insitute of Big Data (SRIBD)
- **LLM Critics Help Catch LLM Bugs** [[Paper](https://arxiv.org/pdf/2407.00215v1)] (2024)
  - Nat McAleese, Rai Michael Pokorny, Juan Felipe Ceron Uribe, Evgenia Nitishinskaya, Maja Trebacz, Jan Leike
  - OpenAI
- **Self-critiquing Models for Assisting Human Evaluators** [[Paper](https://arxiv.org/pdf/2206.05802)] (2022)
  - William Saunders, Catherine Yeh, Jeff Wu, Steven Bills, Long Ouyang, Jonathan Ward, Jan Leike
  - OpenAI
- **Improve Mathematical Reasoning in Language Models by Automated Process Supervision** [[Paper](https://arxiv.org/pdf/2406.06592)] (2024)
  - Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun, Abhinav Rastogi
  - Google DeepMind
- **Q\*: Improving Multi-step Reasoning for LLMs with Deliberative Planning** [[Paper](https://arxiv.org/pdf/2406.14283)] (2024)
  - Chaojie Wang, Yanchen Deng, Zhiyi Lyu, Liang Zeng, Jujie He, Shuicheng Yan, Bo An
  - Skywork AI, NTU
- **Math-shepherd: Verify and Reinforce LLMs step-by-step without Human Annotations** [[Paper](https://aclanthology.org/2024.acl-long.510.pdf)] (ACL 2024)
  - Peiyi Wang, Lei Li, Zhihong Shao, Runxin Xu, Damai Dai, Yifei Li, Deli Chen, Yu Wu, Zhifang Sui
  - Peking University, DeepSeek AI, HKU, Tsinghua University, The Ohio State University

## Social News

## Applications beyond Math
- **HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs** [[Paper](https://arxiv.org/abs/2412.18925)] (2024)
-  Junying Chen, Zhenyang Cai, Ke Ji, Xidong Wang, Wanlong Liu, Rongsheng Wang, Jianye Hou, Benyou Wang
-  The Chinese University of Hong Kong, Shenzhen (CUHKSZ)


## Open-source Projects

- **O1-Journey** [[Github](https://github.com/GAIR-NLP/O1-Journey#about-the-team)]
- **OpenReasoner** [[Github](https://github.com/openreasoner/openr)]
- **g1** [[Github](https://github.com/bklieger-groq/g1)]
- **HuatuoGPT-o1** [[Github](https://github.com/FreedomIntelligence/HuatuoGPT-o1)]


## Communication Groups


## Contributions

We welcome every researcher who contributes to this repository.
