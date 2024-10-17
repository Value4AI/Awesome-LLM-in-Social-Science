# Awesome-LLM-in-Social-Science


Below we compile *awesome* papers that  
- **evaluate** Large Language Models (LLMs) from a perspective of Social Science.
- **align** LLMs from a perspective of Social Science.
- employ LLMs to **facilitate research, address issues, and enhance tools** in Social Science.
- contribute **surveys** or **perspectives** on the above topics.

Evaluation, alignment, and simulation are by no means orthogonal. For example, evaluations require simulations. We categorize these papers based on our understanding of their focus. This collection has **a special focus on Psychology and Human Values**.

Welcome to contribute and discuss!

#### 🤩 Papers with a `⭐️` are contributed by the maintainers of this repository. We would appreciate it if you could give us a star or cite our paper if you find it useful.


## Table of Contents

* 1. [📚 Survey](#Survey)
* 2. [🔎 Evaluating LLM](#Evaluating-LLM)
	* 2.1. [❤️ Value](#Value)
	* 2.2. [🩷 Personality](#Personality)
	* 2.3. [🔞 Morality](#Morality)
	* 2.4. [🎤 Opinion](#Opinion)
	* 2.5. [🧠 Ability](#Ability)
* 3. [⚒️ Tool enhancement](#Tool-enhancement)
* 4. [⛑️ Alignment](#Alignment)
* 5. [🚀 Simulation](#Simulation)
* 6. [👁️‍🗨️ Perspective](#Perspective)

##  1. <a name='Survey'></a>📚 Survey 

- **Automated Mining of Structured Knowledge from Text in the Era of Large Language Models**, 2024.08, KDD 2024, [[paper]](https://dl.acm.org/doi/pdf/10.1145/3637528.3671469).
- **Affective Computing in the Era of Large Language Models: A Survey from the NLP Perspective**, 2024.07, [[paper]](https://arxiv.org/abs/2408.04638).
- **Perils and opportunities in using large language models in psychological research**, 2024.07, [[paper]](https://academic.oup.com/pnasnexus/article/3/7/pgae245/7712371).
- **The Potential and Challenges of Evaluating Attitudes, Opinions, and Values in Large Language Models**, 2024.06, [[paper]](https://arxiv.org/abs/2406.11096).
- **Can Generative AI improve social science?**, 2024.05, PNAS, [[paper]](https://www.pnas.org/doi/pdf/10.1073/pnas.2314021121).
- **Foundational Challenges in Assuring Alignment and Safety of Large Language Models**, 2024.04, [[paper]](https://arxiv.org/abs/2404.09932).
- **Large Language Model based Multi-Agents: A Survey of Progress and Challenges**, 2024.01, [[paper]](https://arxiv.org/abs/2402.01680), [[repo]](https://github.com/taichengguo/LLM_MultiAgents_Survey_Papers).
- **The Rise and Potential of Large Language Model Based Agents: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2309.07864), [[repo]](https://github.com/WooooDyy/LLM-Agent-Paper-List).
- **A Survey on Large Language Model based Autonomous Agents**, 2023, [[paper]](https://arxiv.org/abs/2308.11432), [[repo]](https://github.com/Paitesanshi/LLM-Agent-Survey).
- **AI Alignment: A Comprehensive Survey**, 2023.11, [[paper]](https://arxiv.org/abs/2310.19852), [[website]](https://alignmentsurvey.com/).
- **Aligning Large Language Models with Human: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2307.12966), [[repo]](https://github.com/GaryYufei/AlignLLMHumanSurvey).
- **Large Language Model Alignment: A Survey**, 2023, [[paper]](https://arxiv.org/abs/2309.15025).
- **Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives**, 2023.12, [[paper]](https://arxiv.org/abs/2312.11970).
- **A Survey on Evaluation of Large Language Models**, 2023.07, [[paper]](https://arxiv.org/abs/2307.03109), [[repo]](https://github.com/MLGroupJLU/LLM-eval-survey).
- **From Instructions to Intrinsic Human Values -- A Survey of Alignment Goals for Big Models**, 2023.08, [[paper]](https://arxiv.org/abs/2308.12014), [[repo]](https://github.com/ValueCompass/Alignment-Goal-Survey).

##  2. <a name='Evaluating-LLM'></a>🔎 Evaluating LLM

- **Quantifying ai psychology: A psychometrics benchmark for large language models**, 2024.07, [[paper]](https://arxiv.org/abs/2406.17675).

###  2.1. <a name='Value'></a>❤️ Value

- ⭐️ **Measuring Human and AI Values based on Generative Psychometrics with Large Language Models**, 2024.09, [[paper]](https://arxiv.org/abs/2409.12106), [[code]](https://github.com/Value4AI/gpv).

- ⭐️ **ValueBench: Towards Comprehensively Evaluating Value Orientations and Understanding of Large Language Models**, ACL 2024, [[paper]](https://arxiv.org/abs/2406.04214), [[code]](https://github.com/Value4AI/ValueBench).

- **Stick to your role! Stability of personal values expressed in large language models**, 2024.08, [[paper]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0309114).

- **Do LLMs have Consistent Values?**, 2024.07, [[paper]](https://arxiv.org/abs/2407.12878).

- **CLAVE: An Adaptive Framework for Evaluating Values of LLM Generated Responses**, 2024.07, [[paper]](https://arxiv.org/abs/2407.10725).

- **Are Large Language Models Consistent over Value-laden Questions?**, 2024.07, [[paper]](https://arxiv.org/abs/2407.02996).

- **Beyond Human Norms: Unveiling Unique Values of Large Language Models through Interdisciplinary Approaches**, 2024.04, [[paper]](https://arxiv.org/abs/2404.12744).

- **Heterogeneous Value Evaluation for Large Language Models**, 2023.03, [[paper]](https://arxiv.org/abs/2305.17147), [[code]](https://github.com/zowiezhang/A2EHV).

  TL;DR: This paper introduces the A2EHV method to assess how well these models align with a range of human values categorized under the Social Value Orientation (SVO) framework.

- **Measuring Value Understanding in Language Models through Discriminator-Critique Gap**, 2023.10, [[paper]](https://arxiv.org/abs/2310.00378).

  TL;DR: This paper introduces Value Understanding Measurement (VUM) framework to quantitatively assess an LLM's understanding of values. This is done by measuring the discriminator-critique gap (DCG), which evaluates both the model's knowledge of values ("know what") and the reasoning behind this knowledge ("know why").

- **Value FULCRA: Mapping Large Language Models to the Multidimensional Spectrum of Basic Human Values**, 2023.11, [[paper]](https://arxiv.org/abs/2311.10766).

- **Value Kaleidoscope: Engaging AI with Pluralistic Human Values, Rights, and Duties**, AAAI24, [[paper]](https://arxiv.org/abs/2309.00779), [[code]](https://github.com/tsor13/kaleido).

- **High-Dimension Human Value Representation in Large Language Models**, 2024.04, [[paper]](https://arxiv.org/abs/2404.07900), [[code]](https://github.com/HLTCHKUST/UniVaR).


###  2.2. <a name='Personality'></a>🩷 Personality

- **Incharacter: Evaluating personality fidelity in role-playing agents through psychological interviews**, ACL 2024, [[paper]](https://aclanthology.org/2024.acl-long.102/), [[code]](https://github.com/Neph0s/InCharacter)

- [*MBTI*] **Open Models, Closed Minds? On Agents Capabilities in Mimicking Human Personalities through Open Large Language Models**, 2024.01, [[paper]](https://arxiv.org/abs/2401.07115)

- **Who is ChatGPT? Benchmarking LLMs' Psychological Portrayal Using PsychoBench**, ICLR 2024, [[paper]](https://arxiv.org/abs/2310.01386), [[code]](https://github.com/CUHK-ARISE/PsychoBench)

- [*BFI*] **AI Psychometrics: Assessing the Psychological Profiles of Large Language Models Through Psychometric Inventories**, Journal, 2024.01, [[paper]](https://journals.sagepub.com/doi/full/10.1177/17456916231214460)

- **Does Role-Playing Chatbots Capture the Character Personalities? Assessing Personality Traits for Role-Playing Chatbots**, 2023.10, [[paper]](https://arxiv.org/abs/2310.17976)

- [*MBTI*] **Do LLMs Possess a Personality? Making the MBTI Test an Amazing Evaluation for Large Language Models**, 2023.07, [[paper]](https://arxiv.org/abs/2307.16180)

- [*MBTI*] **Can ChatGPT Assess Human Personalities? A General Evaluation Framework**, 2023.03, EMNLP 2023, [[paper]](https://arxiv.org/abs/2303.01248), [[code]](https://github.com/Kali-Hac/ChatGPT-MBTI).

- [*BFI*] **Personality Traits in Large Language Models**, 2023.07, [[paper]](https://arxiv.org/abs/2307.00184)

- [*BFI*] **Revisiting the Reliability of Psychological Scales on Large Language Models**, 2023.05, [[paper]](https://arxiv.org/abs/2305.19926)

- [*BFI*] **Systematic Evaluation of GPT-3 for Zero-Shot Personality Estimation**, ACL 2023 workshop, [[paper]](https://arxiv.org/abs/2306.01183)


- [*BFI*] **Have Large Language Models Developed a Personality?: Applicability of Self-Assessment Tests in Measuring Personality in LLMs**, 2023.05, [[paper]](https://arxiv.org/abs/2305.14693)

- [*BFI*] **Evaluating and Inducing Personality in Pre-trained Language Models**, NeurIPS 2023 (spotlight), [[paper]](https://arxiv.org/abs/2206.07550)


- [*BFI*] **Identifying and Manipulating the Personality Traits of Language Models**, 2022,12, [[paper]](https://arxiv.org/abs/2212.10276)

- **Who is GPT-3? An Exploration of Personality, Values and Demographics**, 2022.09, [[paper]](https://arxiv.org/abs/2209.14338)

- **Does GPT-3 Demonstrate Psychopathy? Evaluating Large Language Models from a Psychological Perspective**, 2022.12, [[paper]](https://arxiv.org/abs/2212.10529)


###  2.3. <a name='Morality'></a>🔞 Morality

- **Aligning AI With Shared Human Values**, 2020, [[paper]](https://arxiv.org/abs/2008.02275).
- **Exploring the psychology of GPT-4's Moral and Legal Reasoning**, 2023.08, [[paper]](https://arxiv.org/abs/2308.01264).

  TL;DR: The paper investigates GPT-4's moral and legal reasoning compared to humans across several domains, using vignette-based studies. It reveals significant parallels and differences in GPT-4's responses, offering insights into its alignment with human moral judgments.

- **Probing the Moral Development of Large Language Models through Defining Issues Test**

  TL;DR: Defining Issues Test (DIT) based on Kohlberg's model of moral development is used to evaluate the ethical reasoning abilities of LLMs. GPT-3 performs at random baseline level while GPT-4 achieves the highest moral development score equivalent to graduate students.

- **Moral Foundations of Large Language Models**, 2023.10, [[paper]](https://arxiv.org/abs/2310.15337).
- **Moral Mimicry: Large Language Models Produce Moral Rationalizations Tailored to Political Identity**, 2023.06, [[paper]](https://arxiv.org/abs/2209.12106)
- **Evaluating the Moral Beliefs Encoded in LLMs**, 2023.07, [[paper]](https://arxiv.org/abs/2307.14324)

###  2.4. <a name='Opinion'></a>🎤 Opinion

- **More human than human: measuring ChatGPT political bias**, 2023, [[paper]](https://link.springer.com/article/10.1007/s11127-023-01097-2).
  
  TL;DR: This paper proposed empirical designs to measure political bias in ChatGPT, showing that ChatGPT exhibits a significant and systematic political bias towards the Democrats in the US, Lula in Brazil, and the Labour Party in the UK.

- **Towards Measuring the Representation of Subjective Global Opinions in Language Models**, 2023.07, [[paper]](https://arxiv.org/abs/2306.16388), [[website]](https://llmglobalvalues.anthropic.com/).

  TL;DR: This study explores how to quantitatively assess the representation of subjective global opinions in LLMs. It introduces a dataset from cross-national surveys to capture diverse global perspectives, and develops a metric to measure the similarity between LLM-generated responses and human responses conditioned on nationality, revealing biases and stereotypes in the model's responses.

###  2.5. <a name='Ability'></a>🧠 Ability 
- **Can Language Models Reason about Individualistic Human Values and Preferences?**, 2024.10, [[paper]](https://arxiv.org/abs/2410.03868).
- **Language Models in Sociological Research: An Application to Classifying Large Administrative Data and Measuring Religiosity**, 2021, [[paper]](https://journals.sagepub.com/doi/full/10.1177/00811750211053370).
 
- **Can Large Language Models Transform Computational Social Science?**, 2023, [[paper]](https://arxiv.org/abs/2305.03514), [[code]](https://github.com/SALT-NLP/LLMs_for_CSS).

  **TL;DR**: This document provides a roadmap for using LLMs as CSS tools, including prompting best practices and an evaluation pipeline. Evaluations show that LLMs can serve as zero-shot data annotators and assist with challenging creative generation tasks.

- **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents**, 2023, [[paper]](https://arxiv.org/pdf/2310.11667.pdf), [[code]](https://www.sotopia.world/).

  TL;DR: The paper introduces SOTOPIA, a novel interactive environment for evaluating social intelligence in language agents through goal-driven social interactions. Experiments using SOTOPIA reveal gaps between SOTA models and human social intelligence, despite models showing some promising capabilities.

- **Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View**, 2023, [[paper]](https://arxiv.org/abs/2310.02124), [[code]](https://github.com/zjunlp/MachineSoM).

  TL;DR: This paper explores collaboration mechanisms among LLMs in a multi-agent system by drawing insights from social psychology. Multi-agent collaboration strategies are more important than scaling up single LLMs; fostering effective collaboration is key for more socially-aware AI.

- **Playing repeated games with Large Language Models**, 2023.05, [[paper]](https://arxiv.org/abs/2305.16867).

  TL;DR: This paper studies Large Language Models' (LLMs) cooperative and coordinated behavior by letting them play repeated 2-player games. The key findings are that LLMs like GPT-4 perform well in competitive games but struggle to coordinate and alternate strategies in games requiring more cooperation.

- **Machine Psychology: Investigating Emergent Capabilities and Behavior in Large Language Models Using Psychological Methods**, 2023, [[paper]](https://arxiv.org/abs/2303.13988).

- **Using cognitive psychology to understand GPT-3**, 2023.02, PNAS, [[paper]](https://www.pnas.org/doi/full/10.1073/pnas.2218523120?doi=10.1073%2Fpnas.2218523120).

- **Large language models as a substitute for human experts in annotating political text**, 2024.02, [[paper]](https://journals.sagepub.com/doi/10.1177/20531680241236239).

## 3. <a name='Tool-enhancement'></a>⚒️ Tool enhancement

- **PsyDI: Towards a Personalized and Progressively In-depth Chatbot for Psychological Measurements**, 2024, [[paper]](https://arxiv.org/abs/2408.03337), [[code]](https://github.com/opendilab/PsyDI).

- **ChatFive: Enhancing User Experience in Likert Scale Personality Test through Interactive Conversation with LLM Agents**, CUI 2024, [[paper]](https://dl.acm.org/doi/abs/10.1145/3640794.3665572)

- **LLM Agents for Psychology: A Study on Gamified Assessments**, 2024.02, [[paper]](https://arxiv.org/abs/2402.12326).

- **Generative Social Choice**, 2023.09, [[paper]](https://arxiv.org/abs/2309.01291)

## 4. <a name='Alignment'></a>⛑️ Alignment

- **PAD: Personalized Alignment at Decoding-Time**, 2024.10, [[paper]](https://arxiv.org/abs/2410.04070).
- **Moral Alignment for LLM Agents**, 2024.10, [[paper]](https://arxiv.org/abs/2410.01639).
- **ProgressGym: Alignment with a Millennium of Moral Progress**, NeurIPS 2024 D&B Tract Spotlight, [[paper]](https://arxiv.org/abs/2406.20087), [[code]](https://github.com/PKU-Alignment/ProgressGym).
- **Policy Prototyping for LLMs: Pluralistic Alignment via Interactive and Collaborative Policymaking**, 2024.09, [[paper]](https://arxiv.org/abs/2409.08622).
- **Modular Pluralism: Pluralistic Alignment via Multi-LLM Collaboration**, 2024.06, [[paper]](https://arxiv.org/abs/2406.15951).
- [*Value*] **What are human values, and how do we align AI to them?**, 2024.04, [[paper]](https://arxiv.org/abs/2404.10636).
- **A Roadmap to Pluralistic Alignment**, ICML 2024, [[paper]](https://arxiv.org/abs/2402.05070), [[code]](https://github.com/jfisher52/AI_Pluralistic_Alignment).
- **Agent Alignment in Evolving Social Norms**, 2024.01, [[paper]](https://arxiv.org/abs/2401.04620).
- [*Norm*] **Align on the Fly: Adapting Chatbot Behavior to Established Norms**, 2023.12, [[paper]](https://arxiv.org/abs/2312.15907), [[code]](https://github.com/GAIR-NLP/OPO).

  TL;DR: Using RAG to align LLMs with dynamic, diverse human values such as social norms.

- [*MBTI*] **Machine Mindset: An MBTI Exploration of Large Language Models**, 2023.12, [[paper]](https://arxiv.org/abs/2312.12999), [[code]](https://github.com/PKU-YuanGroup/Machine-Mindset).

  TL;DR: Train LLM toward certain MBTI via instruction tuning and direct preference optimization (DPO).

- **Training Socially Aligned Language Models in Simulated Human Society**, 2023, [[paper]](https://arxiv.org/abs/2305.16960), [[code]](https://github.com/agi-templar/Stable-Alignment).

  Keywords: Stable Alignment, social alignment, societal norms and values, simulated social interactions, contrastive supervised learning

  TL;DR: This paper presents a training paradigm that permits LMs to learn from simulated social interactions for their social alignment. The model trained under such a paradigm better handles “jailbreaking prompts”.

- **Fine-tuning language models to find agreement among humans with diverse preferences**, 2022, [[paper]](https://arxiv.org/abs/2211.15006).

  Keywords: consensus, fine-tuning, diverse preferences, alignment

  TL;DR: This work fine-tunes LLM to generate statements that maximize the expected approval for a group of people with potentially diverse opinions, especially on moral and political issues.

- **ValueNet: A New Dataset for Human Value Driven Dialogue System**, AAAI 2022, [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21368), [[dataset]](https://liang-qiu.github.io/ValueNet/).
  

##  5. <a name='Simulation'></a>🚀 Simulation
- **Large Language Models can Achieve Social Balance**, 2024.10, [[paper]](https://arxiv.org/abs/2410.04054).
- **On the limits of agency in agent-based models**, 2024.09, [[paper]](https://arxiv.org/abs/2409.10568), [[code]](https://github.com/AgentTorch/AgentTorch).
- **United in Diversity? Contextual Biases in LLM-Based Predictions of the 2024 European Parliament Elections**, 2024.09, [[paper]](https://arxiv.org/abs/2409.09045).

- **Out of One, Many: Using Language Models to Simulate Human Samples**, 2022, [[paper]](https://arxiv.org/abs/2209.06899).

  TL;DR: This work introduces "algorithmic fidelity" - the degree to which the relationships between ideas, attitudes, and contexts in a model mirror those in human groups. They propose 4 criteria for assessing algorithmic fidelity and demonstrate that GPT-3 exhibits a high degree of fidelity for modeling public opinion and political attitudes in the U.S.

- **Social Simulacra: Creating Populated Prototypes for Social Computing Systems**, 2022, [[paper]](https://dl.acm.org/doi/abs/10.1145/3526113.3545616).

  Keywords: social computing prototypes, social simulacra, LLMs, system design refinement

  TL;DR: This paper proposes Social Simulacra, a social computing prototype, to mimic authentic social interactions within a system populated by diverse community members, each with distinct behaviors such as posts, replies, and anti-social tendencies.

- **Generative Agents: Interactive Simulacra of Human Behavior**, 2023, [[paper]](https://arxiv.org/abs/2304.03442), [[code]](https://github.com/joonspk-research/generative_agents).

  Keywords: generative agents, sandbox environment, natural language communication, emergent social behaviors, Smallville

  TL;DR: This paper introduces generative agents and their architecture for memory storage, reflection, retrieval, etc. The agents produce believable individual and emergent social behaviors in an interactive sandbox environment.

- **Using Large Language Models to Simulate Multiple Humans and Replicate Human Subject Studies**, 2023, [[paper]](https://proceedings.mlr.press/v202/aher23a.html), [[code]](https://github.com/GatiAher/Using-Large-Language-Models-to-Replicate-Human-Subject-Studies).

  TL;DR: This paper presents a methodology for simulating Turing Experiments (TEs) and applies it to replicate well-established findings from economic, psycholinguistic, and social psychology experiments. The results show that larger language models provide more faithful simulations, except for a "hyper-accuracy distortion" (being unhumanly accurate) present in some recent models.

- **Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?**, 2023 [[paper]](https://www.nber.org/papers/w31122), [[code]](https://github.com/johnjosephhorton/homo_silicus).

  TL;DR: LLMs can be used like economists use homo economicus. Experiments using LLMs show qualitatively similar results to the original economic research. It is promising to use LLM to search for novel social science insights to test in the real world.

- **$S^3$: Social-network Simulation System with Large Language Model-Empowered Agents**, 2023, [[paper]](https://arxiv.org/abs/2307.14984).

  Keywords: social network simulation, agent-based simulation, information/attitude/emotion propagation, user behavior modeling

  TL;DR: This paper introduces the Social-network Simulation System (S3) to simulate social networks via LLM-based agents. Evaluations using two real-world scenarios, namely gender discrimination and nuclear energy, display high accuracy in replicating individual attitudes, emotions, and behaviors, as well as successfully modeling the phenomena of information, attitude, and emotion propagation at the population level.

- **Rethinking the Buyer’s Inspection Paradox in Information Markets with Language Agents**, 2023, [[paper]](https://openreview.net/forum?id=6werMQy1uz).

  Keywords: buyer’s inspection paradox, information economics, information market, language model, agent

  TL;DR: This work explores the buyer's inspection paradox in a simulated information marketplace, highlighting enhanced decision-making and answer quality when agents temporarily access information before purchase.

- **SocioDojo: Building Lifelong Analytical Agents with Real-world Text and Time Series**, 2023, [[paper]](https://openreview.net/forum?id=s9z0HzWJJp).

  Keywords: lifelong learning, human society analysis, hyperportfolio, time series investment, Analyst-Assistant-Actuator architecture, Hypothesis and Proof prompting

  TL;DR: The paper introduces SocioDojo, a new environment and hyperportfolio task for training lifelong agents to analyze and make decisions about human society, along with a novel Analyst-Assistant-Actuator architecture and Hypothesis & Proof prompting technique. Experiments show the proposed method achieves over 30% higher returns compared to state-of-the-art methods in the hyperportfolio task requiring societal understanding.

- **Humanoid Agents: Platform for Simulating Human-like Generative Agents**, 2023, [[paper]](https://arxiv.org/abs/2310.05418), [[code]](https://github.com/HumanoidAgents/HumanoidAgents).

  Keywords: humanoid agents, generative agents, basic needs, emotions, relationships

  TL;DR: This paper proposes Humanoid Agents, a system that guides generative agents to behave more like humans by introducing dynamic elements that affect behavior - basic needs like hunger and rest, emotions, and relationship closeness.
  
- **When Large Language Model based Agent Meets User Behavior Analysis: A Novel User Simulation Paradigm**, 2023, [[paper]](https://arxiv.org/abs/2306.02552), [[code]](https://github.com/RUC-GSAI/YuLan-Rec).

  Keywords: user behavior analysis, user simulation, recommender system, profiling/memory/action module

  TL;DR: This work employs LLM for user simulation in recommender systems. The experiments demonstrate the superiority of RecAgent over baseline simulation systems and its ability to generate reliable user behaviors.

- **Large Language Model-Empowered Agents for Simulating Macroeconomic Activities**, 2023, [[paper]](https://arxiv.org/abs/2310.10436).

  Keywords: macroeconomic simulation, agent-based modeling, prompt-engineering, perception/reflection/decision-making abilities

  TL;DR: This work leverages LLM-based agents for macroeconomic simulation. Experiments show that LLM-based agents make realistic decisions, reproducing classic macro phenomena better than rule-based or other AI agents.

- **Generative Agent-Based Modeling: Unveiling Social System Dynamics through Coupling Mechanistic Models with Generative Artificial Intelligence**, 2023, [[paper]](https://arxiv.org/abs/2309.11456).

  Keywords: Generative Agend-Based Modeling, norm diffusion, social dynamics

  TL;DR: The authors demonstrate Generative Agent-Based Modeling (GABM) through a simple model of norm diffusion, where agents decide on wearing green or blue shirts based on peer influence. The results show emergence of group norms, sensitivity to agent personas, and conformity to asymmetric adoption forces.

- **Using Imperfect Surrogates for Downstream Inference: Design-based Supervised Learning for Social Science Applications of Large Language Models**, 2023.06, NeurIPS 2023, [[paper]](https://arxiv.org/abs/2306.04746).

  TL;DR: We present a new algorithm for using outputs from LLMs for downstream statistic analyses while guaranteeing statistical properties -- like asymptotic unbiasedness and proper uncertainty quantification -- which are fundamental to CSS research.

- **Epidemic Modeling with Generative Agents**, 2023.07, [[paper]](https://arxiv.org/abs/2307.04986), [[code]](https://github.com/bear96/GABM-Epidemic).

  Keywords: epidemic modeling, generative AI, agent-based model, human behavior, COVID-19

  TL;DR: The paper presents a new epidemic modeling approach using generative AI to empower individual agents with reasoning ability. The generative agent-based model collectively flattens the epidemic curve, mimicking patterns like multiple waves, through AI-powered decision-making without imposed rules.

- **Emergent analogical reasoning in large language models**, 2023.08, nature human behavior, [[paper]](https://www.nature.com/articles/s41562-023-01659-w).

  Keywords: GPT-3, Analogical Reasoning, Zero-Shot Learning, Cognitive Processes, Human Comparison

  TL;DR: This paper investigates the emergent analogical reasoning capabilities of GPT-3, demonstrating its proficiency in various analogy tasks compared to college students. The research highlights GPT-3's potential in zero-shot learning and its similarity to human cognitive processes in problem-solving.

- **MetaAgents: Simulating Interactions of Human Behaviors for LLM-based Task-oriented Coordination via Collaborative Generative Agents**, 2023.10, [[paper]](https://arxiv.org/abs/2310.06500).

  Keywords: agent simulation, job fair environment, task-oriented coordination

  TL;DR: The paper introduces "MetaAgents" to enhance coordination in LLMs through a novel collaborative and reasoning approach, tested in a simulated job fair environment. The study reveals both the potential and limitations of LLM-based agents in complex social coordination tasks.

- **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars**, 2023.11, [[paper]](https://arxiv.org/abs/2311.17227), [[code]](https://github.com/agiresearch/WarAgent).

  TL;DR: This paper presents WarAgent, an AI system simulating historical conflicts, revealing how historical and policy factors critically drive the inevitability and nature of wars.

- **Emergence of Social Norms in Large Language Model-based Agent Societies**, 2024.03, [[paper]](https://arxiv.org/abs/2403.08251), [[code]](https://github.com/sxswz213/CRSEC).
- **Large Content And Behavior Models To Understand, Simulate, And Optimize Content And Behavior**, ICLR-2024, [[paper]](https://openreview.net/forum?id=TrKq4Wlwcz)
  TL;DR: LLMs are not conventionally designed for predicting and optimizing human behavior. In this paper, we introduce the receivers' "behavior tokens," such as shares, likes, clicks, purchases, and retweets, in the LLM's training corpora to optimize content for the receivers and predict their behaviors. Other than showing similar performance to LLMs on content understanding tasks, our trained models show generalization capabilities on the behavior dimension for behavior simulation, content simulation, behavior understanding, and behavior domain adaptation. 


##  6. <a name='Perspective'></a>👁️‍🗨️ Perspective

- **The benefits, risks and bounds of personalizing the alignment of large language models to individuals**, 2024.04, Nature Machine Intelligence, [[paper]](https://www.nature.com/articles/s42256-024-00820-y).

- **A social path to human-like artificial intelligence**, 2023.11, Nature Machine Intelligence, [[paper]](https://www.nature.com/articles/s42256-023-00754-x).

  TL;DR: This paper explores the social pathways to human intelligence, highlighting the roles of collective living, social relationships, and key evolutionary transformations in the development of intelligence.

- **Using large language models in psychology**, 2023.10, Nature reviews psychology, [[paper]](https://www.nature.com/articles/s44159-023-00241-5).
