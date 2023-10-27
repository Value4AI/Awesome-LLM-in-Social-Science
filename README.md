# Awesome-LLM-in-Social-Science

[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://github.com/henry-yeh/Awesome-LLM-for-Simulation) [![License: MIT](https://camo.githubusercontent.com/fd551ba4b042d89480347a0e74e31af63b356b2cac1116c7b80038f41b04a581/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667)](https://opensource.org/licenses/MIT) <img src="https://img.shields.io/github/last-commit/tensorflow/tensorflow.svg"/> [![img](https://camo.githubusercontent.com/eafac29b763e18c4d80c680d6a179f348cfa2afbc8d3a45642df19fd580d2404/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d57656c636f6d652d726564)](https://camo.githubusercontent.com/eafac29b763e18c4d80c680d6a179f348cfa2afbc8d3a45642df19fd580d2404/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d57656c636f6d652d726564)

Below we compile *awesome* papers that  
- evaluate or aligns Large Language Models (LLMs) from a perspective of Social Science.
- employ LLMs to create simulation environments, facilitating research in diverse fields in Social Science.
- can be considered a subset of those related to LLM-based agents.

This is a preliminary repo. Welcome to contribute and discuss!

## Paper list

### Survey 
- **The Rise and Potential of Large Language Model Based Agents: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2309.07864), [[repo]](https://github.com/WooooDyy/LLM-Agent-Paper-List).
- **A Survey on Large Language Model based Autonomous Agents**, 2023, [[paper]](https://arxiv.org/abs/2308.11432), [[repo]](https://github.com/Paitesanshi/LLM-Agent-Survey).

---

- **Social Simulacra: Creating Populated Prototypes for Social Computing Systems**, 2022, [[paper]](https://dl.acm.org/doi/abs/10.1145/3526113.3545616).

  Keywords: social computing prototypes, social simulacra, LLMs, system design refinement

  TL;DR: This paper proposes Social Simulacra, a social computing prototype, to mimic authentic social interactions within a system populated by diverse community members, each with distinct behaviors such as posts, replies, and anti-social tendencies.

- **Can Large Language Models Transform Computational Social Science?**, 2023, [[paper]](https://arxiv.org/abs/2305.03514), [[code]](https://github.com/SALT-NLP/LLMs_for_CSS).

  Keywords: Computational Social Science (CSS), evaluation

  TL;DR: This document provides a roadmap for using LLMs as CSS tools, including prompting best practices and an evaluation pipeline. Evaluations show that LLMs can serve as zero-shot data annotators and assist with challenging creative generation tasks.

- **Generative Agents: Interactive Simulacra of Human Behavior**, 2023, [[paper]](https://arxiv.org/abs/2304.03442), [[code]](https://github.com/joonspk-research/generative_agents).

  Keywords: generative agents, sandbox environment, natural language communication, emergent social behaviors, Smallville

  TL;DR: This paper introduces generative agents and their architecture for memory storage, reflection, retrival, etc. The agents produce believable individual and emergent social behaviors in an interactive sandbox environment.

- **Using Large Language Models to Simulate Multiple Humans and Replicate Human Subject Studies**, 2023, [[paper]](https://proceedings.mlr.press/v202/aher23a.html), [[code]](https://github.com/GatiAher/Using-Large-Language-Models-to-Replicate-Human-Subject-Studies).

  Keywords: Turing Experiment, human subject research, hyper-accuracy distortion

  TL;DR: This paper presents a methodology for simulating Turing Experiments (TEs) and applies it to replicate well-established findings from economic, psycholinguistic, and social psychology experiments. The results show that larger language models provide more faithful simulations, except for a "hyper-accuracy distortion" (being unhumanly accurate) present in some recent models.

- **$S^3$: Social-network Simulation System with Large Language Model-Empowered Agents**, 2023, [[paper]](https://arxiv.org/abs/2307.14984).

  Keywords: social network simulation, agent-based simulation, information/attitude/emotion propagation, user behavior modeling

  TL;DR: This paper introduces the Social-network Simulation System (S3) to simulate social networks via LLM-based agents. Evaluations using two real-world scenarios, namely gender discrimination and nuclear energy, display high accuracy in replicating individual attitudes, emotions, and behaviors, as well as successfully modeling the phenomena of information, attitude, and emotion propagation at the population level.

- **Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?**, 2023 [[paper]](https://www.nber.org/papers/w31122), [[code]](https://github.com/johnjosephhorton/homo_silicus).

  Keywords: simulated economic agents, Homo Silicus, Behavioral Economics

  TL;DR: LLMs can be used like economists use homo economicus. Experiments using LLMs show qualitatively similar results to the original economic research. It is promising to use LLM to search for novel social science insights to test in the real world.

- **Rethinking the Buyer’s Inspection Paradox in Information Markets with Language Agents**, 2023, [[paper]](https://openreview.net/forum?id=6werMQy1uz).

  Keywords: buyer’s inspection paradox, information economics, information market, language model, agent

  TL;DR: This work explores the buyer's inspection paradox in a simulated information marketplace, highlighting enhanced decision-making and answer quality when agents temporarily access information before purchase.

- **SocioDojo: Building Lifelong Analytical Agents with Real-world Text and Time Series**, 2023, [[paper]](https://openreview.net/forum?id=s9z0HzWJJp).

  Keywords: lifelong learning, human society analysis, hyperportfolio, time series investment, Analyst-Assistant-Actuator architecture, Hypothesis and Proof prompting

  TL;DR: The paper introduces SocioDojo, a new environment and hyperportfolio task for training lifelong agents to analyze and make decisions about human society, along with a novel Analyst-Assistant-Actuator architecture and Hypothesis & Proof prompting technique. Experiments show the proposed method achieves over 30% higher returns compared to state-of-the-art methods in the hyperportfolio task requiring societal understanding.

- **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents**, 2023, [[paper]](https://arxiv.org/pdf/2310.11667.pdf), [[code]](https://www.sotopia.world/).

  Keywords: social intelligence, interactive evaluation, language agents, goal-driven interaction, multi-agent simulation, commonsense reasoning

  TL;DR: The paper introduces SOTOPIA, a novel interactive environment for evaluating social intelligence in language agents through goal-driven social interactions. Experiments using SOTOPIA reveal gaps between SOTA models and human social intelligence, despite models showing some promising capabilities.

- **Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View**, 2023, [[paper]](https://arxiv.org/abs/2310.02124), [[code]](https://github.com/zjunlp/MachineSoM).

  Keywords: multi-agent systems, LLMs, collaboration strategies, social psychology, debate vs. reflection, conformity and majority rule

  TL;DR: This paper explores collaboration mechanisms among LLMs in a multi-agent system by drawing insights from social psychology. Multi-agent collaboration strategies are more important than scaling up single LLMs; fostering effective collaboration is key for more socially-aware AI.

- **Humanoid Agents: Platform for Simulating Human-like Generative Agents**, 2023, [[paper]](https://arxiv.org/abs/2310.05418), [[code]](https://github.com/HumanoidAgents/HumanoidAgents).

  Keywords: humanoid agents, generative agents, basic needs, emotions, relationships

  TL;DR: This paper proposes Humanoid Agents, a system that guides generative agents to behave more like humans by introducing dynamic elements that affect behavior - basic needs like hunger and rest, emotions, and relationship closeness.
  
- **When Large Language Model based Agent Meets User Behavior Analysis: A Novel User Simulation Paradigm**, 2023, [[paper]](https://arxiv.org/abs/2306.02552), [[code]](https://github.com/RUC-GSAI/YuLan-Rec).

  Keywords: user behavior analysis, user simulation, recommender system, profiling/memory/action module

  TL;DR: This work employs LLM for user simulation in recommender systems. The experiments demonstrate the superiority of RecAgent over baseline simulation systems and its ability to generate reliable user behaviors.

- **Large Language Model-Empowered Agents for Simulating Macroeconomic Activities**, 2023, [[paper]](https://arxiv.org/abs/2310.10436).

  Keywords: macroeconomic simulation, agent-based modeling, prompt-engineering, perception/reflection/decision-making abilities

  TL;DR: This work leverages LLM-based agents for macroeconomic simulation. Experiments show the LLM-based agents make realistic decisions, reproducing classic macro phenomena better than rule-based or other AI agents.

- **Using large language models in psychology**, 2023, [[paper]](https://www.nature.com/articles/s44159-023-00241-5).

  Keywords: LLM, psychology, applications, measurement

  TL;DR: This paper explores the potential applications and concerns of using LLMs in psychological research, and recommends investments in high-quality datasets, performance benchmarks, and infrastructure to enable responsible use of LLMs.

---

You may also be interested in LLM as optimizers: https://github.com/AGI-Edgerunners/LLM-Optimizers-Papers
