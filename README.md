# Awesome LLM Reasoning Openai-o1 Survey

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  [![License](https://img.shields.io/github/license/hijkzzz/Awesome-LLM-Strawberry)](https://github.com/wjn1996/Awesome-LLM-Reasoning-Openai-o1-Survey/blob/main/LICENSE)  ![Visitors](https://visitor-badge.lithub.cc/badge?page_id=wjn1996.awesome-llm-reasoning-openai-o1-survey&left_text=Visitors)  ![Stars](https://img.shields.io/github/stars/wjn1996/Awesome-LLM-Reasoning-Openai-o1-Survey?color=yellow)  ![Forks](https://img.shields.io/github/forks/wjn1996/Awesome-LLM-Reasoning-Openai-o1-Survey?color=9cf)


The related works and background techniques about OpenAI o1, including LLM reasoning, self-play reinforcement learning, complex logic reasoning, scaling law, etc.


## Introduction


## Survey Papers


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


### Reasoning Bootstrapping
- **STaR: Self-Taught Reasoner Bootstrapping Reasoning With Reasoning** [[Paper]](https://papers.nips.cc/paper_files/paper/2022/file/639a9a172c044fbb64175b5fad42e9a5-Paper-Conference.pdf) [[Github]](https://github.com/ezelikman/STaR) (NeurIPS 2022)
  - Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman
  - Stanford, Google
- **Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking** [[Paper](https://arxiv.org/pdf/2403.09629)] [[Github](https://github.com/ezelikman/quiet-star)] (2022)
  - Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman
  - Stanford, Notbad AI
- **Training chain-of-thought via latent-variable inference** [[Paper](https://papers.nips.cc/paper_files/paper/2023/file/e69a9560c450ca76584d9eb37e7f5ae8-Paper-Conference.pdf)] (NeurIPS 2023)
  - Du Phan, Matthew D. Hoffman, David Dohan, Sholto Douglas, Tuan Anh Le, Aaron Parisi, Pavel Sountsov, Charles Sutton, Sharad Vikram, Rif A. Saurous
  - Google
- **Chain-of-thought reasoning without prompting** [[Paper](https://arxiv.org/pdf/2402.10200)] (2024)
  - Xuezhi Wang, Denny Zhou
  - Google DeepMind


### Reasoning Scaling Law
- **Large Language Monkeys: Scaling Inference Compute with Repeated Sampling** [[Paper](https://arxiv.org/pdf/2407.21787)] (2024)
  - Bradley Brown, Jordan Juravsky, Ryan Ehrlich, Ronald Clark, Quoc V. Le, Christopher Ré, Azalia Mirhoseini
  - Stanford, Oxford, Google DeepMind
- **Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters** [[Paper](https://arxiv.org/pdf/2408.03314)] (2024)
  - Charlie Snell, Jaehoon Lee, Kelvin Xu, Aviral Kumar
  - UC Berkeley, Google DeepMind


### Self-play Learning
- **Mastering chess and shogi by self-play with a general reinforcement learning algorithm** [[Paper](https://arxiv.org/pdf/1712.01815)] (2017)
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
### Step-wise Optimization



### Process-based Supervised
- **Solving math word problems with process-and outcome-based feedback** [[Paper](https://arxiv.org/pdf/2211.14275)] (2022)
  - Jonathan Uesato, Nate Kushman, Ramana Kumar, Francis Song, Noah Siegel, Lisa Wang, Antonia, Creswell, Geoffrey Irving, Irina Higgins
  - Google DeepMind
- **Thinking fast and slow with deep learning and tree search** [[Paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/d8e1344e27a5b08cdfd5d027d9b8d6de-Paper.pdf)] (NeurIPS 2017)
  - Thomas Anthony, Zheng Tian, David Barber
  - University College Londo, Alen



## Social News



## Open-source Projects



## Communication Groups


## Contributions

We welcome every researcher who contributes to this repository.
