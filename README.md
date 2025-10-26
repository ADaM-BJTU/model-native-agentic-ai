# 🧠 model-native-agentic-ai

<div align="center">
  <img src="logo.jpg" alt="Logo" width="800">
  <h1 align="center">Agentic AI: From Pipelines to Model-native</h1>
  <p align="center">
    This repository contains a curated list of papers referenced in our survey: <br>
    <a href="new_paradigm_shift_survey.pdf"><strong>Beyond Pipelines: A Survey of the Paradigm Shift toward Model-Native Agentic AI</strong></a><br>
    We will continuously update this list with new, relevant papers.
  </p>
  
  [![Awesome](https://awesome.re/badge.svg)](https://github.com/ADaM-BJTU/model-native-agentic-ai) 
  ![](https://img.shields.io/github/last-commit/ADaM-BJTU/model-native-agentic-ai?color=green) 

</div>


## 🙏 Citation

If you find our survey useful for your research, please consider citing our work:

```bibtex
@misc{
}
```


## 🌟 Abstract

The rapid evolution of agentic AI marks a new phase in artificial intelligence, where Large Language Models
(LLMs) no longer merely respond but act, reason, and adapt. This survey traces the paradigm shift in building
agentic AI: from **Pipeline-based** systems, where planning, tool use, and memory are orchestrated by external
logic, to the emerging **Model-native** paradigm, where these capabilities are internalized within the model’s
parameters.

We first position Reinforcement Learning (RL) as the algorithmic engine enabling this paradigm shift. By
reframing learning from imitating static data to outcome-driven exploration, RL underpins a unified solution
of *LLM + RL + Task* across language, vision and embodied domains. Building on this, the survey systematically
reviews how each capability—*Planning, Tool use, and Memory*—has evolved from externally scripted modules
to end-to-end learned behaviors. Furthermore, it examines how this paradigm shift has reshaped major agent
applications, specifically the *Deep Research agent* emphasizing long-horizon reasoning and the *GUI agent*
emphasizing embodied interaction.

We conclude by discussing the continued internalization of agentic capabilities like *Multi-agent collaboration*
and *Reflection*, alongside the evolving roles of the system and model layers in future agentic AI. Together, these
developments outline a coherent trajectory toward model-native agentic AI as an integrated learning and
interaction framework, marking the transition from constructing systems that apply intelligence to developing
models that grow intelligence through experience.

## 📒 Table of Contents

- [Core Capabilities: Planning](#-3core-capabilities-planning)
    - [Pipeline-based Paradigm](#32pipeline-based-paradigm)
    - [Model-native Paradigm](#33model-native-paradigm)
- [Core Capabilities: Tool Use](#-4core-capabilities-tool-use)
    - [Pipeline-based Paradigm](#42pipeline-based-paradigm)
    - [Model-native Paradigm](#43model-native-paradigm)
- [Core Capabilities: Memory](#-5core-capabilities-memory)
    - [Short-Term Memory: Long Context](#52short-term-memory-long-context)
    - [Short-Term Memory: Context Management](#53short-term-memory-context-management)
    - [Long-Term Memory](#54long-term-memory)
- [Applications](#-6applications)
    - [Deep Research Agent](#61deep-research-agent)
    - [GUI Agent](#62gui-agent)
- [Future Direction and Discussion: Emerging Model-native Capabilities](#-7future-direction-and-discussion)
    - [Multi-agent Collaboration](#711emerging-model-native-capabilities-multi-agent-collaboration)
    - [Reflection](#712emerging-model-native-capabilities-reflection)


# 📜 Papers

## ➤ 3&nbsp;&nbsp;Core Capabilities: Planning

### 3.2&nbsp;&nbsp;Pipeline-based Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   STRIPS  |  [Strips: A new approach to the application of theorem proving to problem solving](https://www.sciencedirect.com/science/article/pii/0004370271900105)  |  1971  | - |
|   PDDL  |  [PDDL - The Planning Domain Definition Language](https://www.cs.cmu.edu/~mmv/planning/readings/98aips-PDDL.pdf)  |  1998  | - |
|   LLM+P  |  [{LLM+P: Empowering Large Language Models with Optimal Planning Proficiency](https://arxiv.org/abs/2304.11477)  |  2023-04  | [GitHub](https://github.com/Cranial-XIX/llm-pddl) ![Stars](https://img.shields.io/github/stars/Cranial-XIX/llm-pddl) |
|   LLM+PDDL  |  [Leveraging pre-trained large language models to construct and utilize world models for model-based task planning](https://arxiv.org/abs/2305.14909)  |  2023-05  | [GitHub](https://github.com/GuanSuns/LLMs-World-Models-for-Planning) ![Stars](https://img.shields.io/github/stars/GuanSuns/LLMs-World-Models-for-Planning) |
|   CoT  |  [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)  |  2022-01  | - |
|   ToT  |  [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/pdf/2305.10601)  |  2023-05  | [GitHub](https://github.com/princeton-nlp/tree-of-thought-llm) ![Stars](https://img.shields.io/github/stars/princeton-nlp/tree-of-thought-llm) |
|   RAP  |  [Reasoning with Language Model is Planning with World Model](https://arxiv.org/abs/2305.14992)  |  2023-05  | - |
|   LLM+MCTS  |  [Planning with MCTS: Enhancing Problem-Solving in Large Language Models](https://openreview.net/forum?id=sdpVfWOUQA)  |  2024-09  | - |

### 3.3&nbsp;&nbsp;Model-native Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   ReST-MCTS*  |  [ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search](https://arxiv.org/abs/2406.03816)  |  2024-06  | [GitHub](https://github.com/THUDM/ReST-MCTS) ![Stars](https://img.shields.io/github/stars/THUDM/ReST-MCTS) |
|   Marco-o1  |  [Marco-o1: Towards Open Reasoning Models for Open-Ended Solutions](https://arxiv.org/abs/2411.14405)  |  2024-11  | [GitHub](https://github.com/AIDC-AI/Marco-o1) ![Stars](https://img.shields.io/github/stars/AIDC-AI/Marco-o1) |
|   HuatuoGPT-o1  |  [HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs](https://arxiv.org/abs/2412.18925)  |  2024-12  | [GitHub](https://github.com/FreedomIntelligence/HuatuoGPT-o1) ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT-o1) |
|   Bespoke-Stratos  |  [Bespoke-Stratos: The unreasonable effectiveness of reasoning distillation](https://www.bespokelabs.ai/blog/bespoke-stratos-the-unreasonable-effectiveness-of-reasoning-distillation)  |  2024-12  | [Dataset](https://huggingface.co/datasets/bespokelabs/Bespoke-Stratos-17k) |
|   s1  |  [s1: Simple test-time scaling](https://arxiv.org/abs/2501.19393)  |  2025-01  | [GitHub](https://github.com/SimpleScaling/s1) ![Stars](https://img.shields.io/github/stars/SimpleScaling/s1) |
|   R1-Distill-SFT  |  [Millions scale dataset distilled from R1-32b](https://huggingface.co/datasets/ServiceNow-AI/R1-Distill-SFT)  |  2025-01  | [Dataset](https://huggingface.co/datasets/ServiceNow-AI/R1-Distill-SFT) |
|   LIMO  |  [LIMO: Less is More for Reasoning](https://arxiv.org/abs/2502.03387)  |  2025-02  | [GitHub](https://github.com/GAIR-NLP/LIMO) ![Stars](https://img.shields.io/github/stars/GAIR-NLP/LIMO) |
|   BOLT  |  [BOLT: Bootstrap Long Chain-of-Thought in Language Models without Distillation](https://arxiv.org/abs/2502.03860)  |  2025-02  | - |
|   AStar  |  [Boosting Multimodal Reasoning with Automated Structured Thinking](https://arxiv.org/abs/2502.02339)  |  2025-02  | - |
|   FastMCTS  |  [FastMCTS: A Simple Sampling Strategy for Data Synthesis](https://arxiv.org/abs/2502.11476)  |  2025-02  | - |
|   OpenThoughts  |  [OpenThoughts: Data Recipes for Reasoning Models](https://arxiv.org/abs/2506.04178)  |  2025-06  | [GitHub](https://github.com/open-thoughts/open-thoughts) ![Stars](https://img.shields.io/github/stars/open-thoughts/open-thoughts) |
|   OpenR1-Math-220k  |  [Open R1: A fully open reproduction of DeepSeek-R1](https://github.com/huggingface/open-r1)  |  2025-02  | [GitHub](https://github.com/huggingface/open-r1) ![Stars](https://img.shields.io/github/stars/huggingface/open-r1) |
|   SYNTHETIC-1   |  [SYNTHETIC-1: Two Million Collaboratively Generated Reasoning Traces from Deepseek-R1](https://huggingface.co/datasets/PrimeIntellect/SYNTHETIC-1-SFT-Data)  |  2025-02  | [Dataset](https://huggingface.co/datasets/PrimeIntellect/SYNTHETIC-1-SFT-Data) |
|   WebSynthesis  |  [WebSynthesis: World-Model-Guided MCTS for Efficient WebUI-Trajectory Synthesis](https://arxiv.org/abs/2507.04370)  |  2025-07  | [GitHub](https://github.com/LucusFigoGao/WebSynthesis) ![Stars](https://img.shields.io/github/stars/LucusFigoGao/WebSynthesis) |
|   Math-Shepherd  |  [Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations](https://arxiv.org/abs/2312.08935)  |  2023-12  | [Project](https://achieved-bellflower-4d6.notion.site/Math-Shepherd-Verify-and-Reinforce-LLMs-Step-by-step-without-Human-Annotations-41b6e73c860840e08697d347f8889bac) |
|   ReFT  |  [ReFT: Reasoning with Reinforced Fine-Tuning](https://aclanthology.org/2024.acl-long.410/)  |  2024-01  | [GitHub](https://github.com/lqtrung1998/mwp_ReFT) ![Stars](https://img.shields.io/github/stars/lqtrung1998/mwp_ReFT) |
|   OmegaPRM  |  [Improve Mathematical Reasoning in Language Models by Automated Process Supervision](https://arxiv.org/abs/2406.06592)  |  2024-06  | - |
|   OpenAI o1  |  [Learning to reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/)  |  2024-09  | - |
|   RLEF  |  [RLEF: Grounding Code LLMs in Execution Feedback with Reinforcement Learning](https://arxiv.org/abs/2410.02089)  |  2024-10  | - |
|   o1-Coder  |  [o1-Coder: an o1 Replication for Coding](https://arxiv.org/abs/2412.00154)  |  2024-01  | [GitHub](https://github.com/ADaM-BJTU/O1-CODER/tree/main) ![Stars](https://img.shields.io/github/stars/ADaM-BJTU/O1-CODER) |
|   Implicit PRM  |  [Free Process Rewards without Process Labels](https://raw.githubusercontent.com/mlresearch/v267/main/assets/yuan25c/yuan25c.pdf)  |  2024-12  | - |
|   ORPS  |  [Reasoning Through Execution: Unifying Process and Outcome Rewards for Code Generation](https://api.semanticscholar.org/CorpusID:274859836)  |  2024-12  | [GitHub](https://github.com/zhuohaoyu/ORPS) ![Stars](https://img.shields.io/github/stars/zhuohaoyu/ORPS) |
|   OpenRFT  |  [OpenRFT: Adapting Reasoning Foundation Model for Domain-specific Tasks with Reinforcement Fine-Tuning](https://arxiv.org/abs/2412.16849)  |  2024-12  | [GitHub](https://github.com/ADaM-BJTU/OpenRFT) ![Stars](https://img.shields.io/github/stars/ADaM-BJTU/OpenRFT) |
|   DeepSeek R1  |  [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)  |  2025-01  | [GitHub](https://github.com/deepseek-ai/DeepSeek-R1) ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-R1) |
|   Qwen-2.5-Math-PRM  |  [The Lessons of Developing Process Reward Models in Mathematical Reasoning](https://huggingface.co/Qwen/Qwen2.5-Math-PRM-72B)  |  2025-01  | [Model](https://huggingface.co/Qwen/Qwen2.5-Math-PRM-72B) |
|   Kimi k1.5  |  [Kimi k1.5: Scaling Reinforcement Learning with LLMs](https://arxiv.org/abs/2501.12599)  |  2025-01  | - |
|   O1-Pruner  |  [O1-Pruner: Length-Harmonizing Fine-Tuning for O1-Like Reasoning Pruning](https://arxiv.org/abs/2501.12570)  |  2025-01  | [GitHub](https://github.com/StarDewXXX/O1-Pruner) ![Stars](https://img.shields.io/github/stars/StarDewXXX/O1-Pruner) |
|   PRIME  |  [Process Reinforcement through Implicit Rewards](https://arxiv.org/abs/2502.01456)  |  2025-02  | - |
|   DeepScaleR  |  [DeepScaleR: Surpassing O1-Preview with a 1.5B Model by Scaling RL](https://pretty-radio-b75.notion.site/DeepScaleR-Surpassing-O1-Preview-with-a-1-5B-Model-by-Scaling-RL-19681902c1468005bed8ca303013a4e2)  |  2025-02  | [GitHub](https://github.com/rllm-org/rllm) ![Stars](https://img.shields.io/github/stars/rllm-org/rllm) |
|   PRLCoder  |  [Process-Supervised Reinforcement Learning for Code Generation](https://arxiv.org/abs/2502.01715)  |  2025-02  | - |
|   L1  |  [L1: Controlling How Long A Reasoning Model Thinks With Reinforcement Learning](https://arxiv.org/abs/2503.04697)  |  2025.03  | [GitHub](https://github.com/cmu-l3/l1) ![Stars](https://img.shields.io/github/stars/cmu-l3/l1) |
|   DAST  |  [DAST: Difficulty-Adaptive Slow-Thinking for Large Reasoning Models](https://arxiv.org/abs/2503.04472)  |  2025.03  | [GitHub](https://github.com/AnonymousUser0520/AnonymousRepo01) ![Stars](https://img.shields.io/github/stars/AnonymousUser0520/AnonymousRepo01) |
|   QwQ  |  [QwQ-32B: Embracing the Power of Reinforcement Learning](https://qwenlm.github.io/blog/qwq-32b/)  |  2025-03  | [HuggingFace](https://huggingface.co/Qwen/QwQ-32B) |
|   Skywork or1  |  [Skywork Open Reasoner Series](https://capricious-hydrogen-41c.notion.site/Skywork-Open-Reaonser-Series-1d0bc9ae823a80459b46c149e4f51680)  |  2025-03  | [GitHub](https://github.com/SkyworkAI/Skywork-OR1) ![Stars](https://img.shields.io/github/stars/SkyworkAI/Skywork-OR1) |
|   Demystify-long-cot  |  [Demystifying Long Chain-of-Thought Reasoning in LLMs](https://arxiv.org/abs/2502.03373)  |  2025-02  | [GitHub](https://github.com/eddycmu/demystify-long-cot) ![Stars](https://img.shields.io/github/stars/eddycmu/demystify-long-cot) |
|   LLM-as-Judge  |  [Who's Your Judge? On the Detectability of LLM-Generated Judgments](https://arxiv.org/abs/2509.25154)  |  2025-09  | - |

## ➤ 4&nbsp;&nbsp;Core Capabilities: Tool Use

### 4.2&nbsp;&nbsp;Pipeline-based Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   WebGPT  |  [WebGPT: Browser-assisted question-answering with human feedback](https://arxiv.org/abs/2112.09332)  |  2021-12  | - |
|   SayCan  |  [Do As I Can, Not As I Say: Grounding Language in Robotic Affordances](https://arxiv.org/abs/2204.01691)  |  2022-04  | [GitHub](https://github.com/google-research/google-research/tree/master/saycan) ![Stars](https://img.shields.io/github/stars/google-research/google-research) 
|   WebShop  |  [WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents](https://proceedings.neurips.cc/paper_files/paper/2022/hash/82ad13ec01f9fe44c01cb91814fd7b8c-Paper-Conference.pdf)  |  2022-07  | [GitHub](https://github.com/princeton-nlp/WebShop) ![Stars](https://img.shields.io/github/stars/princeton-nlp/WebShop) |
|   Code as Policies  |  [Code as Policies: Language Model Programs for Embodied Control](https://arxiv.org/abs/2209.07753)  |  2022-09  | [GitHub](https://github.com/google-research/google-research/tree/master/code_as_policies) ![Stars](https://img.shields.io/github/stars/google-research/google-research) |
|   HuggingGPT  |  [HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face](https://proceedings.neurips.cc/paper_files/paper/2023/file/77c33e6a367922d003ff102ffb92b658-Paper-Conference.pdf)  |  2023-03  | [GitHub](https://github.com/microsoft/JARVIS) ![Stars](https://img.shields.io/github/stars/microsoft/JARVIS) |
|   AutoGen  |  [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155)  |  2023-08  | [GitHub](https://github.com/microsoft/autogen) ![Stars](https://img.shields.io/github/stars/microsoft/autogen) |
|   SWE-agent  |  [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://papers.nips.cc/paper_files/paper/2024/file/5a7c947568c1b1328ccc5230172e1e7c-Paper-Conference.pdf)  |  2024-05  | [GitHub](https://github.com/SWE-agent/SWE-agent) ![Stars](https://img.shields.io/github/stars/SWE-agent/SWE-agent) |
|   Self-Ask  |  [Measuring and Narrowing the Compositionality Gap in Language Models](https://arxiv.org/abs/2210.03350)  |  2022-10  | [GitHub](https://github.com/ofirpress/self-ask) ![Stars](https://img.shields.io/github/stars/ofirpress/self-ask) |
|   ReAct  |  [ReAct: Synergizing Reasoning and Acting in Language Models](https://openreview.net/forum?id=WE_vluYUL-X)  |  2022-10  | [GitHub](https://github.com/ysymyth/ReAct) ![Stars](https://img.shields.io/github/stars/ysymyth/ReAct) |
|   PAL  |  [PAL: Program-aided Language Models](https://openreview.net/forum?id=WE_vluYUL-X)  |  2022-11  | [GitHub](https://github.com/reasoning-machines/pal) ![Stars](https://img.shields.io/github/stars/reasoning-machines/pal) |
|   PoT  |  [Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://openreview.net/forum?id=YfZ4ZPt8zd)  |  2022-11  | [GitHub](https://github.com/TIGER-AI-Lab/Program-of-Thoughts) ![Stars](https://img.shields.io/github/stars/TIGER-AI-Lab/Program-of-Thoughts) |
|   Reflexion  |  [Reflexion: language agents with verbal reinforcement learning](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf)  |  2023-03  | [GitHub](https://github.com/NoahShinn024/reflexion) ![Stars](https://img.shields.io/github/stars/NoahShinn024/reflexion) |
|   ViperGPT  |  [ViperGPT: Visual Inference via Python Execution for Reasoning](https://openaccess.thecvf.com/content/ICCV2023/html/Suris_ViperGPT_Visual_Inference_via_Python_Execution_for_Reasoning_ICCV_2023_paper.html)  |  2023-03  | [GitHub](https://github.com/cvlab-columbia/viper) ![Stars](https://img.shields.io/github/stars/cvlab-columbia/viper) |
|   CRITIC  |  [CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing](https://openreview.net/forum?id=Sx038qxjek)  |  2023-05  | [GitHub](https://github.com/microsoft/ProphetNet/tree/master/CRITIC) ![Stars](https://img.shields.io/github/stars/microsoft/ProphetNet) |

### 4.3&nbsp;&nbsp;Model-native Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   Agent-as-Tool  |  [Agent-as-Tool: A Study on the Hierarchical Decision Making with Reinforcement Learning](https://arxiv.org/abs/2507.01489)  |  2025-07  | - |
|   AI-SearchPlanner  |  [AI-SearchPlanner: Modular Agentic Search via Pareto-Optimal Multi-Objective Reinforcement Learning](https://arxiv.org/abs/2508.20368)  |  2025-08  | - |
|   RLTR  |  [Encouraging Good Processes Without the Need for Good Answers: Reinforcement Learning for LLM Agent Planning](https://arxiv.org/abs/2508.19598)  |  2025-08  | - |
|   R1-Searcher  |  [R1-searcher: Incentivizing the search capability in llms via reinforcement learning](https://arxiv.org/abs/2503.05592)  |  2025-03  | [GitHub](https://github.com/RUCAIBox/R1-Searcher) ![Stars](https://img.shields.io/github/stars/RUCAIBox/R1-Searcher) |
|   ReSearch  |  [ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning](https://arxiv.org/abs/2503.19470)  |  2025-03  | [GitHub](https://github.com/Agent-RL/ReCall) ![Stars](https://img.shields.io/github/stars/Agent-RL/ReCall) |
|   ToRL  |  [ToRL: Tool-integrated Reinforcement Learning for LLM Agents](https://arxiv.org/abs/2503.23383)  |  2025-03  | [GitHub](https://github.com/GAIR-NLP/ToRL) ![Stars](https://img.shields.io/github/stars/GAIR-NLP/ToRL) |
|   Search-R1  |  [Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning](https://arxiv.org/abs/2503.09516)  |  2025-03  | [GitHub](https://github.com/PeterGriffinJin/Search-R1) ![Stars](https://img.shields.io/github/stars/PeterGriffinJin/Search-R1) |
|   AutoCoA  |  [Agent models: Internalizing Chain-of-Action Generation into Reasoning models](https://arxiv.org/abs/2503.06580)  |  2025-03  | [GitHub](https://github.com/ADaM-BJTU/AutoCoA) ![Stars](https://img.shields.io/github/stars/ADaM-BJTU/AutoCoA) |
|   ReTool  |  [ReTool: Reinforcement Learning for Strategic Tool Use in LLMs](https://arxiv.org/abs/2504.11536)  |  2025-04  | [GitHub](https://github.com/ReTool-RL/ReTool) ![Stars](https://img.shields.io/github/stars/ReTool-RL/ReTool) |
|   ToolRL  |  [ToolRL: Reinforcement Learning for Tool-Use in Large Reasoning Models](https://arxiv.org/abs/2504.13958)  |  2025-04  | [GitHub](https://github.com/qiancheng0/ToolRL) ![Stars](https://img.shields.io/github/stars/qiancheng0/ToolRL) |
|   OTC  |  [Acting Less is Reasoning More: Teaching Models Optimal Tool Calls via Reinforcement Learning](https://arxiv.org/abs/2504.14870)  |  2025-04  | - |
|   DeepResearcher  |  [DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments](https://arxiv.org/abs/2504.03160)  |  2025-04  | [GitHub](https://github.com/GAIR-NLP/DeepResearcher) ![Stars](https://img.shields.io/github/stars/GAIR-NLP/DeepResearcher) |
|   ARTIST  |  [Agentic Reasoning and Tool Integration for LLMs via Reinforcement Learning](https://arxiv.org/abs/2505.01441)  |  2025-04  | - |
|   WebThinker  |  [Webthinker: Empowering large reasoning models with deep research capability](https://arxiv.org/abs/2504.21776)  |  2025-04  | [GitHub](https://github.com/RUC-NLPIR/WebThinker) ![Stars](https://img.shields.io/github/stars/RUC-NLPIR/WebThinker) |
|   RAGEN  |  [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073)  |  2025-04  | [GitHub](https://github.com/RAGEN-AI/RAGEN) ![Stars](https://img.shields.io/github/stars/RAGEN-AI/RAGEN) |
|   WebDancer  |  [WebDancer: Towards Autonomous Information Seeking Agency](https://arxiv.org/abs/2505.22648)  |  2025-05  | [GitHub](https://github.com/Alibaba-NLP/WebAgent) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/WebAgent) |
|   Tool-N1  |  [Tool-N1: Training General Tool-Use in Large Reasoning Models](https://arxiv.org/abs/2505.00024)  |  2025-05  | [GitHub](https://github.com/NVlabs/Tool-N1) ![Stars](https://img.shields.io/github/stars/NVlabs/Tool-N1) |
|   Satori-SWE  |  [Satori-SWE: Evolutionary Test-Time Scaling for Sample-Efficient Software Engineering](https://arxiv.org/abs/2505.23604)  |  2025-05  | [GitHub](https://github.com/satori-reasoning/Satori-SWE) ![Stars](https://img.shields.io/github/stars/satori-reasoning/Satori-SWE) |
|   MaskSearch  |  [MaskSearch: A Universal Pre-Training Framework to Enhance Agentic Search Capability](https://arxiv.org/abs/2505.20285)  |  2025-05  | [GitHub](https://github.com/Alibaba-NLP/MaskSearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/MaskSearch) |
|   SkyRL  |  [SkyRL-v0: Train Real-World Long-Horizon Agents via Reinforcement Learning](https://novasky-ai.notion.site/)  |  2025-05  | [GitHub](https://github.com/NovaSky-AI/SkyRL) ![Stars](https://img.shields.io/github/stars/NovaSky-AI/SkyRL) |
|   ZeroSearch  |  [ZeroSearch: Incentivize the Search Capability of LLMs without Searching](https://arxiv.org/abs/2505.04588)  |  2025-05  | [GitHub](https://github.com/Alibaba-NLP/ZeroSearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/ZeroSearch) |
|   Agent RL Scaling  |  [Agent RL Scaling Law: Agent RL with Spontaneous Code Execution for Mathematical Problem Solving](https://arxiv.org/abs/2505.07773)  |  2025-05  | [GitHub](https://github.com/yyht/openrlhf_async_pipline) ![Stars](https://img.shields.io/github/stars/yyht/openrlhf_async_pipline) |
|   GIGPO  |  [Group-in-Group Policy Optimization for LLM Agent Training](https://arxiv.org/abs/2505.10978)  |  2025-05  | [GitHub](https://github.com/langfengQ/verl-agent) ![Stars](https://img.shields.io/github/stars/langfengQ/verl-agent) |
|   VTool-R1  |  [VTool-R1: VLMs Learn to Think with Images via Reinforcement Learning on Multimodal Tool Use](https://arxiv.org/abs/2505.19255)  |  2025-05  | [GitHub](https://github.com/VTool-R1/VTool-R1) ![Stars](https://img.shields.io/github/stars/VTool-R1/VTool-R1) |
|   DeepEyes  |  [DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning](https://arxiv.org/abs/2505.14362)  |  2025-05  | [GitHub](https://github.com/Visual-Agent/DeepEyes) ![Stars](https://img.shields.io/github/stars/Visual-Agent/DeepEyes) |
|   Multi-Turn-RL  |  [Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment](https://arxiv.org/abs/2505.11821)  |  2025-05  | [GitHub](https://github.com/SiliangZeng/Multi-Turn-RL-Agent) ![Stars](https://img.shields.io/github/stars/SiliangZeng/Multi-Turn-RL-Agent) |
|   StepSearch  |  [StepSearch: Igniting LLMs Search Ability via Step-Wise Proximal Policy Optimization](https://arxiv.org/abs/2505.15107)  |  2025-05  | [GitHub](https://github.com/Zillwang/StepSearch) ![Stars](https://img.shields.io/github/stars/Zillwang/StepSearch) |
|   Spa-RL  |  [SPA-RL: Reinforcing LLM Agents via Stepwise Progress Attribution](https://arxiv.org/abs/2505.20732)  |  2025-05  | [GitHub](https://github.com/WangHanLinHenry/SPA-RL-Agent) ![Stars](https://img.shields.io/github/stars/WangHanLinHenry/SPA-RL-Agent) |
|   O^2-Searcher  |  [O^2-Searcher: A Searching-based Agent Model for Open-domain QA via Reinforcement Learning](https://arxiv.org/abs/2505.16582)  |  2025-05  | [GitHub](https://github.com/Acade-Mate/O2-Searcher) ![Stars](https://img.shields.io/github/stars/Acade-Mate/O2-Searcher) |
|   MMSearch-R1  |  [MMSearch-R1: Incentivizing LMMs to Search](https://arxiv.org/abs/2506.20670)  |  2025-06  | [GitHub](https://github.com/EvolvingLMMs-Lab/multimodal-search-r1) ![Stars](https://img.shields.io/github/stars/EvolvingLMMs-Lab/multimodal-search-r1) |
|   Agent-RLVR  |  [Agent-RLVR: Training Software Engineering Agents via Guidance and Environment Rewards](https://arxiv.org/abs/2506.11425)  |  2025-06  | - |
|   AutoTIR  |  [AutoTIR: Autonomous Tools Integrated Reasoning via Reinforcement Learning](https://arxiv.org/abs/2507.21836)  |  2025-07  | [GitHub](https://github.com/weiyifan1023/AutoTIR) ![Stars](https://img.shields.io/github/stars/weiyifan1023/AutoTIR) |
|   Agent Lightning  |  [Agent Lightning: Train ANY AI Agents with Reinforcement Learning](https://arxiv.org/abs/2508.03680)  |  2025-08  | [GitHub](https://github.com/microsoft/agent-lightning) ![Stars](https://img.shields.io/github/stars/microsoft/agent-lightning) |
|   FunRL  |  [Exploring Superior Function Calls via Reinforcement Learning](https://arxiv.org/abs/2508.05118)  |  2025-08  | [GitHub](https://github.com/BingguangHao/RLFC) ![Stars](https://img.shields.io/github/stars/BingguangHao/RLFC) |
|   rStar2-Agent  |  [rStar2-Agent: Agentic Reasoning Technical Report](https://arxiv.org/abs/2508.20722)  |  2025-08  | [GitHub](https://github.com/microsoft/rStar) ![Stars](https://img.shields.io/github/stars/microsoft/rStar) |
|   ASearcher  |  [Unlocking Long-Horizon Agentic Search with Large-Scale Asynchronous Reinforcement Learning](https://arxiv.org/abs/2508.07976)  |  2025-08  | [GitHub](https://github.com/inclusionAI/ASearcher) ![Stars](https://img.shields.io/github/stars/inclusionAI/ASearcher) |

## ➤ 5&nbsp;&nbsp;Core Capabilities: Memory

### 5.2&nbsp;&nbsp;Short-Term Memory: Long Context

#### Pipeline-based paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   StreamingLLM  |  [Efficient Streaming Language Models with Attention Sinks](https://arxiv.org/abs/2309.17453)  |  2023-09  | [GitHub](https://github.com/mit-han-lab/streaming-llm) ![Stars](https://img.shields.io/github/stars/mit-han-lab/streaming-llm) |
|   MemGPT  |  [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560)  |  2023-10  | [GitHub](https://github.com/letta-ai/letta) ![Stars](https://img.shields.io/github/stars/letta-ai/letta) |
|   SelectiveContext  |  [Compressing Context to Enhance Inference Efficiency of Large Language Models](https://arxiv.org/abs/2310.06201)  |  2023-10  | [GitHub](https://github.com/liyucheng09/Selective_Context) ![Stars](https://img.shields.io/github/stars/liyucheng09/Selective_Context) |
|   LLMLingua  |  [LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models](https://aclanthology.org/2023.emnlp-main.825)  |  2023-10  | [GitHub](https://github.com/microsoft/LLMLingua) ![Stars](https://img.shields.io/github/stars/microsoft/LLMLingua) |
|   MapReduce  |  [Langchain](https://github.com/langchain-ai/langchain)  |  2022-10  | [GitHub](https://github.com/langchain-ai/langchain) ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain) |
|   GraphRAG  |  [From Local to Global: A Graph RAG Approach to Query-Focused Summarization](https://arxiv.org/abs/2404.16130)  |  2024-04  | [GitHub](https://github.com/microsoft/graphrag) ![Stars](https://img.shields.io/github/stars/microsoft/graphrag) |
|   MemoRAG  |  [MemoRAG: Boosting Long Context Processing with Global Memory-Enhanced Retrieval Augmentation](https://arxiv.org/abs/2409.05591)  |  2024-09  | [GitHub](https://github.com/qhjqhj00/MemoRAG) ![Stars](https://img.shields.io/github/stars/qhjqhj00/MemoRAG) |
|   ILM-TR  |  [Enhancing Long Context Performance in LLMs Through Inner Loop Query Mechanism](https://arxiv.org/abs/2410.12859)  |  2024-10  | - |

#### Model-native Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   RoPE  |  [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://www.sciencedirect.com/science/article/abs/pii/S0925231223011864)  |  2021-04  | - |
|   ALiBi  |  [Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation](https://arxiv.org/abs/2108.12409)  |  2021-08  | [GitHub](https://github.com/ofirpress/attention_with_linear_biases) ![Stars](https://img.shields.io/github/stars/ofirpress/attention_with_linear_biases) |
|   YaRN  |  [YaRN: Efficient Context Window Extension of Large Language Models](https://arxiv.org/abs/2309.00071)  |  2023-09  | [GitHub](https://github.com/jquesnelle/yarn) ![Stars](https://img.shields.io/github/stars/jquesnelle/yarn) |
|   LieRE  |  [LieRE: Lie Rotational Positional Encodings](https://arxiv.org/abs/2406.10322)  |  2024-06  | [GitHub](https://github.com/ofirpress/attention_with_linear_biases) ![Stars](https://img.shields.io/github/stars/ofirpress/attention_with_linear_biases) |
|   UltraLLaDA  |  [UltraLLaDA: Scaling the Context Length to 128K for Diffusion Large Language Models](https://arxiv.org/abs/2510.10481)  |  2025-10  | [GitHub](https://github.com/Relaxed-System-Lab/UltraLLaDA) ![Stars](https://img.shields.io/github/stars/Relaxed-System-Lab/UltraLLaDA) |
|   Qwen2.5-1M  |  [Qwen2.5-1M Collection (Hugging Face)](https://huggingface.co/collections/Qwen/qwen25-1m-679325716327ec07860530ba)  |  2025-01  | - |
|   Longformer/LED  |  [Longformer: The Long-Document Transformer](https://arxiv.org/abs/2004.05150)  |  2020-04  | [GitHub](https://github.com/allenai/longformer) ![Stars](https://img.shields.io/github/stars/allenai/longformer) |
|   BigBird  |  [Big Bird: Transformers for Longer Sequences](https://arxiv.org/abs/2007.14062)  |  2020-05  | [GitHub](https://github.com/google-research/bigbird) ![Stars](https://img.shields.io/github/stars/google-research/bigbird) |
|   Performer  |  [Rethinking Attention with Performers](https://arxiv.org/abs/2009.14794)  |  2020-06  | [GitHub](https://github.com/lucidrains/performer-pytorch) ![Stars](https://img.shields.io/github/stars/lucidrains/performer-pytorch) |
|   FlashAttention  |  [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://openreview.net/forum?id=H4DqfPSibmx)  |  2022-11  | [GitHub](https://github.com/Dao-AILab/flash-attention) ![Stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention) |
|   LightningAttention  |  [Efficient Language Modeling with Lightning Attention](https://arxiv.org/abs/2405.17381)  |  2023-07  | [GitHub](https://github.com/OpenNLPLab/lightning-attention) ![Stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention) |
|   LightningAttention-2  |  [Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths](https://arxiv.org/abs/2401.04658)  |  2024-01  | [GitHub](https://github.com/OpenNLPLab/lightning-attention) ![Stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention) |
|   SKVQ  |  [SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models](https://arxiv.org/abs/2405.06219)  |  2024-05  | [GitHub](https://github.com/cat538/SKVQ) ![Stars](https://img.shields.io/github/stars/cat538/SKVQ) |
|   MoBA  |  [MoBA](https://github.com/MoonshotAI/MoBA)  |  2025-02  | [GitHub](https://github.com/MoonshotAI/MoBA) ![Stars](https://img.shields.io/github/stars/MoonshotAI/MoBA) |

### 5.3&nbsp;&nbsp;Short-Term Memory: Context Management

#### Pipeline-based paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   MemoChat  |  [MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation](https://arxiv.org/abs/2308.08239)  |  2023-08  | - |
|   MemInsight  |  [MemInsight: Autonomous Memory Augmentation for LLM Agents](https://arxiv.org/html/2503.21760v1)  |  2025-03  | - |
|   HiAgent  |  [HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Models](https://arxiv.org/abs/2408.09559)  |  2024-08  | [GitHub](https://github.com/HiAgent2024/HiAgent) ![Stars](https://img.shields.io/github/stars/HiAgent2024/HiAgent) |
|   AWM  |  [Agent Workflow Memory](https://arxiv.org/abs/2409.07429)  |  2024-10  | [GitHub](https://github.com/zorazrw/agent-workflow-memory) ![Stars](https://img.shields.io/github/stars/zorazrw/agent-workflow-memory) |
|   Memary  |  [Memary](https://github.com/kingjulio8238/Memary)  |  2024-10  | [GitHub](https://github.com/kingjulio8238/Memary) ![Stars](https://img.shields.io/github/stars/kingjulio8238/Memary) |
|   COLA  |  [COLA: A Multi-agent Framework for Generating Large-Scale UI Automation Datasets on Windows](https://arxiv.org/abs/2503.09263)  |  2025-03  | - |
|   ZEP  |  [Zep: The AI Memory Server](https://docs.getzep.com/)  |  2025-01  | [GitHub](https://github.com/getzep/zep) ![Stars](https://img.shields.io/github/stars/getzep/zep) |
|   Mem0  |  [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://arxiv.org/abs/2504.19413)  |  2025-04  | [GitHub](https://github.com/mem0ai/mem0) ![Stars](https://img.shields.io/github/stars/mem0ai/mem0) |

#### Model-native Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   G-MEM  |  [G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems](https://www.researchgate.net/publication/392531451)  |  2024-12  | [GitHub](https://github.com/bingreeky/GMemory) ![Stars](https://img.shields.io/github/stars/bingreeky/GMemory) |
|   A-Mem  |  [A-MEM: Agentic Memory for LLM Agents](https://arxiv.org/abs/2502.12110)  |  2025-02  | [GitHub](https://github.com/agiresearch/A-mem) ![Stars](https://img.shields.io/github/stars/agiresearch/A-mem) |
|   Intrinsic Memory Agents  |  [Intrinsic Memory Agents: Heterogeneous Multi-Agent LLM Systems through Structured Contextual Memory](https://arxiv.org/abs/2508.08997)  |  2025-08  | - |
|   EMU  |  [Efficient Episodic Memory Utilization of Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2403.01112)  |  2024-03  | [GitHub](https://github.com/HyunghoNa/EMU) ![Stars](https://img.shields.io/github/stars/HyunghoNa/EMU) |
|   Optimus-1  |  [Optimus-1: On-device Data of Task Execution and Decision Making for LLM-based Agents](https://arxiv.org/html/2408.03615v2)  |  2025-06  | [GitHub](https://github.com/JiuTian-VL/Optimus-1) ![Stars](https://img.shields.io/github/stars/JiuTian-VL/Optimus-1) |
|   Nemori  |  [Nemori: Self-Organizing Agent Memory Inspired by Cognitive Science](https://arxiv.org/abs/2508.03341)  |  2025-08  | - |
|   RAP  |  [RAP: Retrieval-Augmented Planning with Contextual Memory for Multimodal LLM Agents](https://github.com/PanasonicConnect/rap)  |  2024-02  | [GitHub](https://github.com/PanasonicConnect/rap) ![Stars](https://img.shields.io/github/stars/PanasonicConnect/rap) |
|   TWM  |  [Temporal Working Memory: Query-Guided Segment Refinement for Enhanced Multimodal Understanding](https://arxiv.org/abs/2502.06020)  |  2025-02  | [GitHub](https://github.com/xid32/NAACL_2025_TWM) ![Stars](https://img.shields.io/github/stars/xid32/NAACL_2025_TWM) |
|   RCR-Router  |  [RCR-Router: Efficient Role-Aware Context Routing for Multi-Agent LLM Systems with Structured Memory](https://www.arxiv.org/pdf/2508.04903)  |  2025-08  | - |
|   Learn-to-Memorize  |  [Learn to Memorize: Optimizing LLM-based Agents with Adaptive Memory Framework](https://arxiv.org/abs/2508.16629)  |  2025-08  | [GitHub](https://github.com/nuster1128/learn_to_memorize) ![Stars](https://img.shields.io/github/stars/nuster1128/learn_to_memorize) |
|   Self-RAG  |  [Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection](https://arxiv.org/abs/2310.11511)  |  2023-10  | [GitHub](https://github.com/AkariAsai/self-rag) ![Stars](https://img.shields.io/github/stars/AkariAsai/self-rag) |
|   TiM  |  [Think-in-Memory: Recalling and Post-thinking Enable LLMs with Long-Term Memory](https://paperreading.club/page?id=194091)  |  2023-11  | - |
|   HippoRAG  |  [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831)  |  2024-05  | [GitHub](https://github.com/OSU-NLP-Group/HippoRAG) ![Stars](https://img.shields.io/github/stars/OSU-NLP-Group/HippoRAG) |
|   MemAgent  |  [MemAgent: Reshaping Long-Context LLM with Multi-Conversation Memory and Reinforcement Learning](https://www.alphaxiv.org/overview/2507.02259v1)  |  2025-07  | [GitHub](https://github.com/BytedTsinghua-SIA/MemAgent) ![Stars](https://img.shields.io/github/stars/BytedTsinghua-SIA/MemAgent) |
|   Memory-R1  |  [Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning](https://arxiv.org/abs/2508.19828)  |  2025-08  | - |

### 5.4&nbsp;&nbsp;Long-Term Memory

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   RETRO  |  [Improving language models by retrieving from trillions of tokens](https://arxiv.org/abs/2112.04426)  |  2021-12  | - |
|   Atlas  |  [Atlas: Few-shot Learning with Retrieval Augmented Language Models](https://arxiv.org/abs/2208.03299)  |  2022-08  | - |
|   Generative Agents  |  [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)  |  2023-04  | - |
|   Synapse  |  [Synapse: Trajectory-as-Exemplar Prompting with Memory for Computer Control](https://arxiv.org/abs/2306.07863)  |  2023-06  | - |
|   MemGPT  |  [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560)  |  2023-10  | [GitHub](https://github.com/letta-ai/letta) ![Stars](https://img.shields.io/github/stars/letta-ai/letta) |
|   GraphRAG  |  [A Graph RAG Approach to Query-Focused Summarization](https://arxiv.org/abs/2404.16130)  |  2024-04  | [GitHub](https://github.com/microsoft/graphrag) ![Stars](https://img.shields.io/github/stars/microsoft/graphrag) |
|   LMLM  |  [Pre-training Large Memory Language Models with Internal and External Knowledge](https://arxiv.org/abs/2505.15962)  |  2025-05  | - |
|   K-Adapter  |  [K-Adapter: Infusing Knowledge into Pre-Trained Models with Adapters](https://aclanthology.org/2021.findings-acl.121/)  |  2021  | [GitHub](https://github.com/microsoft/K-Adapter) ![Stars](https://img.shields.io/github/stars/microsoft/K-Adapter) |
|   Memorizing Transformers  |  [Memorizing Transformers](https://arxiv.org/abs/2203.08913)  |  2022-03  | [GitHub](https://github.com/lucidrains/memorizing-transformers-pytorch) ![Stars](https://img.shields.io/github/stars/lucidrains/memorizing-transformers-pytorch) |
|   S-LoRA  |  [S-LoRA: Serving Thousands of Concurrent LoRA Adapters](https://arxiv.org/abs/2311.03285)  |  2023-11  | - |
|   MixLoRA  |  [MixLoRA: Enhancing LLM Fine-Tuning with LoRA-based Mixture of Experts](https://arxiv.org/abs/2404.15159)  |  2024-04  | [GitHub](https://github.com/PLUM-Lab/MixLoRA) ![Stars](https://img.shields.io/github/stars/PLUM-Lab/MixLoRA) |
|   ELDER  |  [Enhancing Lifelong Model Editing with Mixture-of-LoRA](https://arxiv.org/abs/2408.11869)  |  2024-08  | - |
|   MoM  |  [MoM: Linear Sequence Modeling with Mixture-of-Memories](https://arxiv.org/abs/2502.13685)  |  2025-02  | [GitHub](https://github.com/OpenSparseLLMs/MoM) ![Stars](https://img.shields.io/github/stars/OpenSparseLLMs/MoM) |

## ➤ 6&nbsp;&nbsp;Applications

### 6.1&nbsp;&nbsp;Deep Research Agent

#### Pipeline-based paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   Query2doc  |  [Query2doc: Query expansion with large language models](https://arxiv.org/abs/2303.07678)  |  2023-03  | [GitHub](https://github.com/xbmxb/RAG-query-rewriting) ![Stars](https://img.shields.io/github/stars/xbmxb/RAG-query-rewriting) [Huggingface](https://huggingface.co/datasets/intfloat/query2doc_msmarco)|
|   Query Rewriting  |  [Query rewriting in retrieval-augmented large language models](https://aclanthology.org/2023.emnlp-main.322)  |  2023-05  | [GitHub](https://github.com/xbmxb/RAG-query-rewriting) ![Stars](https://img.shields.io/github/stars/xbmxb/RAG-query-rewriting) |
|   RECOMP  |  [Recomp: Improving retrieval-augmented lms with compression and selective augmentation](https://arxiv.org/abs/2310.04408)  |  2023-10  | [GitHub](https://github.com/carriex/recomp) ![Stars](https://img.shields.io/github/stars/carriex/recomp) |
|   LongLLMLingua  |  [Longllmlingua: Accelerating and enhancing llms in long context scenarios via prompt compression](https://arxiv.org/abs/2310.06839)  |  2023-10  | [GitHub](https://github.com/microsoft/LLMLingua) ![Stars](https://img.shields.io/github/stars/microsoft/LLMLingua) |
|   FreshLLMs  |  [Freshllms: Refreshing large language models with search engine augmentation](https://arxiv.org/abs/2310.03214)  |  2023-10  | [GitHub](https://github.com/freshllms/freshqa) ![Stars](https://img.shields.io/github/stars/freshllms/freshqa) |
|   BIDER  |  [Bider: Bridging knowledge inconsistency for efficient retrieval-augmented llms via key supporting evidence](https://arxiv.org/abs/2402.12174)  |  2024-02  | - |
|   CorpusLM  |  [Corpuslm: Towards a unified language model on corpus for knowledge-intensive tasks](https://arxiv.org/abs/2402.01176)  |  2024-02  | - |
|   GraphRAG  |  [From local to global: A graph rag approach to query-focused summarization](https://arxiv.org/abs/2404.16130)  |  2024-04  | [GitHub](https://github.com/microsoft/graphrag) ![Stars](https://img.shields.io/github/stars/microsoft/graphrag) |
|   RetroLLM  |  [Retrollm: Empowering large language models to retrieve fine-grained evidence within generation](https://arxiv.org/abs/2412.11919)  |  2024-12  | [GitHub](https://github.com/sunnynexus/RetroLLM) ![Stars](https://img.shields.io/github/stars/sunnynexus/RetroLLM) |
|   Real-World WebAgent  |  [A real-world webagent with planning, long context understanding, and program synthesis](https://arxiv.org/abs/2307.12856)  |  2023-07  | - |
|   WebVoyager  |  [Webvoyager: Building an end-to-end web agent with large multimodal models](https://arxiv.org/abs/2401.13919)  |  2024-01  | [GitHub](https://github.com/MinorJerry/WebVoyager) ![Stars](https://img.shields.io/github/stars/MinorJerry/WebVoyager) |
|   Search-o1  |  [Search-o1: Agentic search-enhanced large reasoning models](https://arxiv.org/abs/2501.05366)  |  2025-01  | [GitHub](https://github.com/RUC-NLPIR/Search-o1) ![Stars](https://img.shields.io/github/stars/RUC-NLPIR/Search-o1) |
|   ODS  |  [Open deep search: Democratizing search with open-source reasoning agents](https://arxiv.org/abs/2503.20201)  |  2025-03  | [GitHub](https://github.com/sentient-agi/OpenDeepSearch) ![Stars](https://img.shields.io/github/stars/sentient-agi/OpenDeepSearch) |
|   ReSum  |  [ReSum: Unlocking Long-Horizon Search Intelligence via Context Summarization](https://arxiv.org/abs/2509.13313)  |  2025-09  | [GitHub](https://github.com/Alibaba-NLP/DeepResearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch) |

#### Model-native Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   R1-Searcher  |  [R1-searcher: Incentivizing the search capability in llms via reinforcement learning](https://arxiv.org/abs/2503.05592)  |  2025-03  | [GitHub](https://github.com/RUCAIBox/R1-Searcher) ![Stars](https://img.shields.io/github/stars/RUCAIBox/R1-Searcher) |
|   Search-R1  |  [Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning](https://arxiv.org/abs/2503.09516)  |  2025-03  | [GitHub](https://github.com/PeterGriffinJin/Search-R1) ![Stars](https://img.shields.io/github/stars/PeterGriffinJin/Search-R1) |
|   ReSearch  |  [ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning](https://arxiv.org/abs/2503.19470)  |  2025-03  | [GitHub](https://github.com/Agent-RL/ReCall) ![Stars](https://img.shields.io/github/stars/Agent-RL/ReCall) |
|   R1-Searcher++  |  [R1-Searcher++: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning](https://arxiv.org/abs/2505.17005)  |  2025-05  | [GitHub](https://github.com/RUCAIBox/R1-Searcher-plus) ![Stars](https://img.shields.io/github/stars/RUCAIBox/R1-Searcher-plus) |
|   R-Search  |  [R-Search: Empowering LLM Reasoning with Search via Multi-Reward Reinforcement Learning](https://arxiv.org/abs/2506.04185)  |  2025-06  | [GitHub](https://github.com/QingFei1/R-Search) ![Stars](https://img.shields.io/github/stars/QingFei1/R-Search) |
|   M2IO-R1  |  [M2IO-R1: An Efficient RL-Enhanced Reasoning Framework for Multimodal Retrieval Augmented Multimodal Generation](https://arxiv.org/abs/2508.06328)  |  2025-08  | - |
|   DeepResearcher  |  [DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments](https://arxiv.org/abs/2504.03160)  |  2025-04  | [GitHub](https://github.com/GAIR-NLP/DeepResearcher) ![Stars](https://img.shields.io/github/stars/GAIR-NLP/DeepResearcher) |
|   WebThinker  |  [Webthinker: Empowering large reasoning models with deep research capability](https://arxiv.org/abs/2504.21776)  |  2025-04  | [GitHub](https://github.com/RUC-NLPIR/WebThinker) ![Stars](https://img.shields.io/github/stars/RUC-NLPIR/WebThinker) |
|   ZeroSearch  |  [ZeroSearch: Incentivize the Search Capability of LLMs without Searching](https://arxiv.org/abs/2505.04588)  |  2025-05  | [GitHub](https://github.com/Alibaba-NLP/ZeroSearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/ZeroSearch) |
|   MMSearch-R1  |  [MMSearch-R1: Incentivizing LMMs to Search](https://arxiv.org/abs/2506.20670)  |  2025-06  | [GitHub](https://github.com/EvolvingLMMs-Lab/multimodal-search-r1) ![Stars](https://img.shields.io/github/stars/EvolvingLMMs-Lab/multimodal-search-r1) |
|   WebWatcher  |  [WebWatcher: Breaking New Frontier of Vision-Language Deep Research Agent](https://arxiv.org/abs/2508.05748)  |  2025-09  | [GitHub](https://github.com/Alibaba-NLP/DeepResearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch) |
|   SFR-DeepResearch  |  [Sfr-deepresearch: Towards effective reinforcement learning for autonomously reasoning single agents](https://arxiv.org/abs/2509.06283)  |  2025-09  | - |
|   DeepDive  |  [Deepdive: Advancing deep search agents with knowledge graphs and multi-turn rl](https://arxiv.org/abs/2509.10446)  |  2025-09  | [GitHub](https://github.com/THUDM/DeepDive) ![Stars](https://img.shields.io/github/stars/THUDM/DeepDive) |
|   WebResearcher  |  [WebResearcher: Unleashing unbounded reasoning capability in Long-Horizon Agents](https://arxiv.org/html/2509.13309v1)  |  2025-09  | [GitHub](https://github.com/Alibaba-NLP/DeepResearch/tree/main) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch) |


### 6.2&nbsp;&nbsp;GUI Agent

#### Pipeline-based paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   Ringer  |  [Ringer: web automation by demonstration](https://dl.acm.org/doi/10.1145/3022671.2984020)  |  2016-11  | [GitHub](https://github.com/sbarman/webscript) ![Stars](https://img.shields.io/github/stars/sbarman/webscript) |
|   Sugilite  |  [SUGILITE: creating multimodal smartphone automation by demonstration](https://dl.acm.org/doi/10.1145/3025453.3025483)  |  2017-05  | [GitHub](https://github.com/tobyli/Sugilite_development) ![Stars](https://img.shields.io/github/stars/tobyli/Sugilite_development) |
|   SARA  |  [Sara: self-replay augmented record and replay for android in industrial cases](https://dl.acm.org/doi/10.1145/3293882.3330557)  |  2019-07  | [GitHub](https://github.com/microsoft/SARA) ![Stars](https://img.shields.io/github/stars/microsoft/SARA) |
|   SmartRPA  |  [Reactive synthesis of software robots in RPA from user interface logs](https://www.sciencedirect.com/science/article/pii/S016636152200118X)  |  2022-11  | [GitHub](https://github.com/bpm-diag/smartRPA) ![Stars](https://img.shields.io/github/stars/bpm-diag/smartRPA) |
|   Reflexion  |  [Advances in Neural Information Processing Systems](https://proceedings.neurips.cc/paper_files/paper/2023/file/1b44b878bb782e6954cd888628510e90-Paper-Conference.pdf)  |  2023-10  | [GitHub](https://github.com/noahshinn/reflexion) ![Stars](https://img.shields.io/github/stars/noahshinn/reflexion) |
|   RCI  |  [Language models can solve computer tasks](https://arxiv.org/abs/2303.17491)  |  2023-11  | [GitHub](https://github.com/posgnu/rci-agent) ![Stars](https://img.shields.io/github/stars/posgnu/rci-agent) |
|   AppAgent  |  [AppAgent: Multimodal Agents as Smartphone Users](https://arxiv.org/abs/2312.13771)  |  2024-04  | [GitHub](https://github.com/TencentQQGYLab/AppAgent) ![Stars](https://img.shields.io/github/stars/TencentQQGYLab/AppAgent) |
|   Mobile-Agent  |  [Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception](https://arXiv.org/abs/2401.16158)  |  2024-04  | [GitHub](https://github.com/X-PLUG/MobileAgent/tree/main/Mobile-Agent-v1) ![Stars](https://img.shields.io/github/stars/X-PLUG/MobileAgent) |
|   Mobile-Agent-V2  |  [Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration](https://arXiv.org/abs/2406.01014)  |  2024-06  | [GitHub](https://github.com/X-PLUG/MobileAgent/tree/main/Mobile-Agent-v2) ![Stars](https://img.shields.io/github/stars/X-PLUG/MobileAgent) |
|   MobileGPT  |  [Mobilegpt: Augmenting llm with human-like app memory for mobile task automation](https://arxiv.org/html/2312.03003v3)  |  2024-11  | [GitHub](https://github.com/mobilegptsys/MobileGPT) ![Stars](https://img.shields.io/github/stars/mobilegptsys/MobileGPT) |
|   Mobile-Agent-V  |  [Mobile-Agent-V: A Video-Guided Approach for Effortless and Efficient Operational Knowledge Injection in Mobile Automation](https://arxiv.org/abs/2505.13887)  |  2025-06  | - |

#### Model-native Paradigm

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   CogAgent  |  [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914)  |  2023-12  | [GitHub](https://github.com/zai-org/CogAgent) ![Stars](https://img.shields.io/github/stars/zai-org/CogAgent) |
|   UGround  |  [UGround: Towards Unified Visual Grounding with Unrolled Transformers](https://arxiv.org/abs/2510.03853)  |  2024-10  | [GitHub](https://github.com/OSU-NLP-Group/UGround) ![Stars](https://img.shields.io/github/stars/OSU-NLP-Group/UGround) |
|   CoAT  |  [Android in the Zoo: Chain-of-Action-Thought for GUI Agents](https://arxiv.org/abs/2403.02713)  |  2024-03  | [GitHub](https://github.com/IMNearth/COAT) ![Stars](https://img.shields.io/github/stars/IMNearth/COAT) |
|   WEPO  |  [WEPO: web element preference optimization for LLM-based web navigation](https://doi.org/10.1609/aaai.v39i25.34863)  |  2024-12  | [GitHub](https://github.com/KLGR123/WEPO) ![Stars](https://img.shields.io/github/stars/KLGR123/WEPO) |
|   STEVE  |  [STEVE: A Step Verification Pipeline for Computer-use Agent Training](https://github.com/FanbinLu/STEVE-R1?tab=readme-ov-file)  |  2025-03  | [GitHub](https://github.com/FanbinLu/STEVE) ![Stars](https://img.shields.io/github/stars/FanbinLu/STEVE) |
|   Explorer  |  [Explorer: Scaling Exploration-driven Web Trajectory Synthesis for Multimodal Web Agents](https://arxiv.org/pdf/2502.11357)  |  2025-05  | [GitHub](https://github.com/OSU-NLP-Group/Explorer) ![Stars](https://img.shields.io/github/stars/OSU-NLP-Group/Explorer) |
|   OS-Genesis  |  [OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis](https://arxiv.org/abs/2412.19723)  |  2025-06  | [GitHub](https://github.com/OS-Copilot/OS-Genesis) ![Stars](https://img.shields.io/github/stars/OS-Copilot/OS-Genesis) |
|   Aria-UI  |  [Aria-UI: Visual Grounding for GUI Instructions](https://arxiv.org/abs/2412.16256)  |  2024-12  | [GitHub](https://ariaui.github.io) ![Stars](https://img.shields.io/github/stars/AriaUI/Aria-UI) |
|   V-Droid  |  [Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment](https://arxiv.org/abs/2503.15937)  |  2025-03  | [GitHub](https://github.com/V-Droid-Agent/V-Droid) ![Stars](https://img.shields.io/github/stars/V-Droid-Agent/V-Droid) |
|   SeeClick  |  [SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/abs/2401.10935)  |  2024-02  | [GitHub]( https://github.com/njucckevin/SeeClick) ![Stars](https://img.shields.io/github/stars/njucckevin/SeeClick) |
|   MobileFlow  |  [MobileFlow: A Multimodal LLM For Mobile GUI Agent](https://arxiv.org/abs/2407.04346)  |  2024-07  | - |
|   UI-TARS  |  [UI-TARS: Pioneering Automated GUI Interaction with Native Agents](https://arxiv.org/abs/2501.12326)  |  2025-01  | [GitHub](https://github.com/bytedance/UI-TARS) ![Stars](https://img.shields.io/github/stars/bytedance/UI-TARS) |
|   GUICourse  |  [GUICourse: From General Vision Language Models to Versatile GUI Agents](https://arxiv.org/abs/2406.11317)  |  2025-05  | [GitHub](https://github.com/RUCBM/GUICourse) ![Stars](https://img.shields.io/github/stars/RUCBM/GUICourse) |
|   ZeroGUI  |  [ZeroGUI: Automating Online GUI Learning at Zero Human Cost](https://arxiv.org/abs/2505.23762)  |  2025-05  | [GitHub](https://github.com/OpenGVLab/ZeroGUI) ![Stars](https://img.shields.io/github/stars/OpenGVLab/ZeroGUI) |
|   ARPO  |  [ARPO:End-to-End Policy Optimization for GUI Agents with Experience Replay](https://arxiv.org/abs/2505.16282)  |  2025-05  | [GitHub](https://github.com/dvlab-research/ARPO) ![Stars](https://img.shields.io/github/stars/dvlab-research/ARPO) |
|   UItron  |  [UItron: Foundational GUI Agent with Advanced Perception and Planning](https://arxiv.org/abs/2508.21767)  |  2025-08  | [GitHub](https://github.com/UITron-hub/UItron) ![Stars](https://img.shields.io/github/stars/UITron-hub/UItron) |
|   GUI-Owl  |  [Mobile-Agent-v3: Foundamental Agents for GUI Automation](https://arxiv.org/abs/2508.15144)  |  2025-08  | [GitHub](https://github.com/X-PLUG/MobileAgent/tree/main/Mobile-Agent-v3) ![Stars](https://img.shields.io/github/stars/X-PLUG/MobileAgent) |
|   DART  |  [Efficient Multi-turn RL for GUI Agents via Decoupled Training and Adaptive Data Curation](https://arxiv.org/abs/2509.23866)  |  2025-09  | [GitHub](https://computer-use-agents.github.io/dart-gui/) ![Stars](https://img.shields.io/github/stars/Computer-use-agents/dart-gui) |
|   GUI-R1  |  [GUI-R1: A Generalist R1-Style Vision-Language Action Model For GUI Agents](https://arxiv.org/abs/2504.10458)  |  2025-10  | [GitHub](https://github.com/ritzz-ai/GUI-R1) ![Stars](https://img.shields.io/github/stars/ritzz-ai/GUI-R1) |
|   OpenCUA  |  [OpenCUA: Open Foundations for Computer-Use Agents](https://arXiv.org/abs/2508.09123)  |  2025-10  | [GitHub](https://github.com/xlang-ai/OpenCUA) ![Stars](https://img.shields.io/github/stars/xlang-ai/OpenCUA) |

## ➤ 7&nbsp;&nbsp;Future Direction and Discussion

### 7.1.1&nbsp;&nbsp;Emerging Model-native Capabilities: Multi-agent Collaboration

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   CAMEL  |  [CAMEL: Communicative Agents for “Mind” Exploration of Large Language Model Society](https://arxiv.org/pdf/2303.17760)  |  2023-03  | [GitHub](https://github.com/camel-ai/camel) ![Stars](https://img.shields.io/github/stars/camel-ai/camel) [Project](https://www.camel-ai.org/) |
|   MetaGPT  |  [MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://arxiv.org/pdf/2308.00352)  |  2023-08  | [GitHub](https://github.com/FoundationAgents/MetaGPT) ![Stars](https://img.shields.io/github/stars/FoundationAgents/MetaGPT) |
|   MAD  |  [Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate](https://arxiv.org/abs/2305.19118)  |  2023-05  | [GitHub](https://github.com/Skytliang/Multi-Agents-Debate) ![Stars](https://img.shields.io/github/stars/Skytliang/Multi-Agents-Debate) |
|   MoA  |  [Mixture-of-Agents Enhances Large Language Model Capabilities](https://arxiv.org/abs/2406.04692)  |  2024-06  | [GitHub](https://github.com/togethercomputer/moa) ![Stars](https://img.shields.io/github/stars/togethercomputer/moa) |
|   AFlow  |  [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762)  |  2024-10  | [GitHub](https://github.com/FoundationAgents/AFlow) ![Stars](https://img.shields.io/github/stars/FoundationAgents/AFlow) |
|   MALT  |  [MALT: Improving Reasoning with Multi-Agent LLM Training](https://arxiv.org/abs/2412.01928)  |  2024-12  | - |
|   CORY  |  [Coevolving with the Other You: Fine-Tuning LLM with Sequential Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2410.06101)  |  2024-10  | [GitHub](https://github.com/Harry67Hu/CORY) ![Stars](https://img.shields.io/github/stars/Harry67Hu/CORY) |
|   MARFT  |  [MARFT: Multi-Agent Reinforcement Fine-Tuning](https://arxiv.org/abs/2504.16129v2)  |  2025-04  | [GitHub](https://github.com/jwliao-ai/MARFT) ![Stars](https://img.shields.io/github/stars/jwliao-ai/MARFT) |
|   MAGRPO  |  [LLM Collaboration With Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2508.04652)  |  2025-08  | - |
|   RLCCF  |  [Wisdom of the Crowd: Reinforcement Learning from Coevolutionary Collective Feedback](https://arxiv.org/abs/2508.12338)  |  2025-08  | - |
|   MATPO  |  [Multi-Agent Tool-Integrated Policy Optimization](https://arxiv.org/abs/2510.04678)  |  2025-10  | [GitHub](https://github.com/mzf666/MATPO) ![Stars](https://img.shields.io/github/stars/mzf666/MATPO) |
|   MasHost  |  [MasHost Builds It All: Autonomous Multi-Agent System Directed by Reinforcement Learning](https://arxiv.org/pdf/2506.08507)  |  2025-06  | - |
|   G-Designer  |  [G-Designer: Architecting Multi-agent Communication Topologies via Graph Neural Networks](https://arxiv.org/pdf/2410.11782)  |  2024-10  | [GitHub](https://github.com/yanweiyue/GDesigner) ![Stars](https://img.shields.io/github/stars/yanweiyue/GDesigner) |
|   ARG-Designer  |  [Assemble Your Crew: Automatic Multi-agent Communication Topology Design via Autoregressive Graph Generation](https://arxiv.org/pdf/2507.18224v1)  |  2025-07  | [GitHub](https://github.com/Shiy-Li/ARG-Designer) ![Stars](https://img.shields.io/github/stars/Shiy-Li/ARG-Designer) |
|   MAGDi  |  [MAGDi: Structured Distillation of Multi-Agent Interaction Graphs Improves Reasoning in Smaller Language Models](https://github.com/dinobby/MAGDi)  |  2024-02  | [GitHub](https://github.com/dinobby/MAGDi) ![Stars](https://img.shields.io/github/stars/dinobby/MAGDi) |
|   CoA  |  [Chain-of-Agents: End-to-End Agent Foundation Models via Multi-Agent Distillation and Agentic RL](https://arxiv.org/pdf/2508.13167)  |  2025-08  | [GitHub](https://github.com/OPPO-PersonalAI/Agent_Foundation_Models) ![Stars](https://img.shields.io/github/stars/OPPO-PersonalAI/Agent_Foundation_Models) |

### 7.1.2&nbsp;&nbsp;Emerging Model-native Capabilities: Reflection

|  Short Name  |   Paper   |   Date  |  Code/Project Link |
|  :---------: |   :---:   |   :--:  |  :---------------: |
|   Reflexion  |  [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/pdf/2303.11366)  |  2023-03  | [GitHub](https://github.com/noahshinn/reflexion) ![Stars](https://img.shields.io/github/stars/noahshinn/reflexion) |
|   Self-Refine  |  [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651)  |  2023-03  | [GitHub](https://github.com/madaan/self-refine) ![Stars](https://img.shields.io/github/stars/madaan/self-refine) [Project](https://selfrefine.info/) |
|   Critic  |  [CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing](https://arxiv.org/abs/2305.11738)  |  2023-05  | [GitHub](https://github.com/microsoft/ProphetNet/tree/master/CRITIC) ![Stars](https://img.shields.io/github/stars/microsoft/ProphetNet) |
|   Conf. Matters  |  [Confidence Matters: Revisiting Intrinsic Self-Correction Capabilities of Large Language Models](https://arxiv.org/abs/2402.12563)  |  2024-02  | [GitHub](https://github.com/MBZUAI-CLeaR/IoE-Prompting) ![Stars](https://img.shields.io/github/stars/MBZUAI-CLeaR/IoE-Prompting) |
|   SCoRe  |  [Training Language Models to Self-Correct via Reinforcement Learning](https://arxiv.org/abs/2409.12917)  |  2024-09  | - |
|   CoV  |  [Retrieving, Rethinking and Revising: The Chain-of-Verification Can Improve Retrieval Augmented Generation](https://arxiv.org/abs/2410.05801)  |  2024-10  | - |
|   DPSDP  |  [Reinforce LLM Reasoning through Multi-Agent Reflection](https://arxiv.org/pdf/2506.08379)  |  2025-06  | - |
|   Agent-R  |  [Agent-R: Training Language Model Agents to Reflect via Iterative Self-Training](https://arxiv.org/pdf/2501.11425)  |  2025-01  | [GitHub](https://github.com/bytedance/Agent-R) ![Stars](https://img.shields.io/github/stars/bytedance/Agent-R) |
|   AgentRefine  |  [AgentRefine: Enhancing Agent Generalization through Refinement Tuning](https://arxiv.org/pdf/2501.01702.pdf)  |  2025-01  | [GitHub](https://github.com/Fu-Dayuan/AgentRefine) ![Stars](https://img.shields.io/github/stars/Fu-Dayuan/AgentRefine) |
|   STeP  |  [Training LLM-Based Agents with Synthetic Self-Reflected Trajectories and Partial Masking](https://arxiv.org/pdf/2505.20023)  |  2025-05  | - |
|   KnowSelf  |  [Agentic Knowledgeable Self-awareness](https://arxiv.org/abs/2504.03553)  |  2025-04  | [GitHub](https://github.com/zjunlp/KnowSelf) ![Stars](https://img.shields.io/github/stars/zjunlp/KnowSelf) |
