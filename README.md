# Large Language Models: Reasoning in Latent Space
<p align="center"><em>
The continuous latent space is analogous to the superposition states in Hilbert space in quantum mechanics. Discretizing it into tokens is akin to measurement collapsing the superposition into a definite outcome.
</em></p>

This repository contains a regularly updated paper list for **LLMs-reasoning-in-latent-space**.

Reasoning in latent space shifts the way AI models think, moving beyond language tokens to represent thought processes in a more abstract, non-language space. Just as humans often think without words, latent space allows for more flexible and efficient reasoning.

### Key advantages include:
1. **Richer Thought Representation**: Latent space captures complex, non-verbal thoughts that language alone can't express.
2. **Lower Latency**: It allows for higher information density, reducing the need for token-based decoding and speeding up reasoning.

This approach brings AI closer to human-like cognition, enabling faster, more flexible, and powerful models for real-world tasks.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](./LICENSE) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/EIT-NLP/Awesome-Latent-CoT/main?logo=github&color=blue)

## Content

- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
    - [Pre-training](#pre-training)
    - [Supervised-Finetuning](#supervised-finetuning)
        - [Vertical Level](#vertical-level)
        - [Horizontal Level](#horizontal-level)
            - [Discrete Tokens](#discrete-tokens)
            - [Continuous Tokens](#continuous-tokens)
    - [Analysis and Interpretability](#analysis-and-interpretability)
    - [Applications](#applications)
    - [Other related work](#other-related-work-or-pending-to-be-specified)
- [Resources](#resources)
- [Acknowledgements](#acknowledgements)

## Keywords Convention

![](https://img.shields.io/badge/Coconut-blue) Abbreviation

![](https://img.shields.io/badge/NIPS2024-orange) Conference

![](https://img.shields.io/badge/Reconstruction-lightgray) Main Features

## Papers

### Pre-training and Continue Pre-training

- **Think before you speak: Training language models with pause tokens**  
  *Sachin Goyal,Ziwei Ji, Ankit Singh Rawat, Aditya Krishna Menon, Sanjiv Kumar, Vaishnavh Nagarajan*. [[pdf](https://arxiv.org/pdf/2310.02226)], 2023.10. ![](https://img.shields.io/badge/ICLR2024-orange) ![](https://img.shields.io/badge/pause_tokens-blue)
- **Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking**  
  *Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman*. [[pdf](https://arxiv.org/pdf/2403.09629)], 2024.03. ![](https://img.shields.io/badge/COLM2024-orange) ![](https://img.shields.io/badge/Quiet--STaR-blue)
- **Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach**  
  *Jonas Geiping, Sean McLeish, Neel Jain, John Kirchenbauer, Siddharth Singh, Brian R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Tom Goldstein*. [[pdf](https://arxiv.org/pdf/2502.05171)], [[code](https://github.com/seal-rg/recurrent-pretraining)], [[model](https://huggingface.co/tomg-group-umd/huginn-0125)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Huggin-blue) ![](https://img.shields.io/badge/Depth_Recurrence-lightgray)
- **LLM Pretraining with Continuous Concepts**  
  *Jihoon Tack, Jack Lanchantin, Jane Yu, Andrew Cohen, Ilia Kulikov, Janice Lan, Shibo Hao, Yuandong Tian, Jason Weston, Xian Li*. [[pdf](https://arxiv.org/pdf/2502.08524)], [[code](https://github.com/facebookresearch/RAM/tree/main/projects/cocomix)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Coconut-blue)
- **Inner Thinking Transformer: Leveraging Dynamic Depth Scaling to Foster Adaptive Internal Thinking**  
  *Yilong Chen, Junyuan Shang, Zhenyu Zhang, Yanxi Xie, Jiawei Sheng, Tingwen Liu, Shuohuan Wang, Yu Sun, Hua Wu, Haifeng Wang*. [[pdf](https://arxiv.org/pdf/2502.13842)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ITT-blue)
- **Scalable Language Models with Posterior Inference of Latent Thought Vectors**  
  *Deqian Kong, Minglu Zhao, Dehong Xu, Bo Pang, Shu Wang, Edouardo Honig, Zhangzhang Si, Chuan Li, Jianwen Xie, Sirui Xie, Ying Nian Wu*. [[pdf](https://arxiv.org/pdf/2502.01567)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LTM-blue)
- **Reasoning to Learn from Latent Thoughts**  
  *Yangjun Ruan, Neil Band, Chris J. Maddison, Tatsunori Hashimoto*. [[pdf](https://arxiv.org/pdf/2503.18866)], [[code](https://github.com/ryoungj/BoLT)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/BoLT-blue)
- **Efficient Pretraining Length Scaling**  
  *Bohong Wu, Shen Yan, Sijun Zhang, Jianqiao Lu, Yutao Zeng, Ya Wang, Xun Zhou*. [[pdf](https://arxiv.org/pdf/2504.14992)], 2025.04.  ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/PHD--Transformer-blue)

### Supervised-Finetuning 

#### Vertical Level

- **Implicit Chain of Thought Reasoning via Knowledge Distillation**  
  *Yuntian Deng, Kiran Prasad, Roland Fernandez, Paul Smolensky, Vishrav Chaudhary, Stuart Shieber*. [[pdf](https://arxiv.org/pdf/2311.01460)], [[code](https://github.com/da03/implicit_chain_of_thought/)], 2023.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Diffusion of Thoughts: Chain-of-Thought Reasoning in Diffusion Language Models**  
  *Jiacheng Ye, Shansan Gong, Liheng Chen, Lin Zheng, Jiahui Gao, Han Shi, Chuan Wu, Xin Jiang, Zhenguo Li, Wei Bi, Lingpeng Kong*. [[pdf](https://arxiv.org/pdf/2402.07754)], 2024.02. ![](https://img.shields.io/badge/NIPS2024-orange) ![](https://img.shields.io/badge/DoT-blue)
- **From Explicit CoT to Implicit CoT: Learning to Internalize CoT Step by Step**  
  *Yuntian Deng, Yejin Choi, Stuart Shieber*. [[pdf](https://arxiv.org/pdf/2405.14838)], [[code](https://github.com/da03/Internalize_CoT_Step_by_Step)], 2024.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ICoT-blue) ![](https://img.shields.io/badge/Stepwise_Internalization-lightgray)
- **Distilling System 2 into System 1**   
  *Ping Yu, Jing Xu, Jason Weston, Ilia Kulikov*. [[pdf](https://arxiv.org/pdf/2407.06023)], 2024.06. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/System_2_Distillation-lightgray)
- **CoTFormer: A Chain-of-Thought Driven Architecture with Budget-Adaptive Computation Cost at Inference**   
  *Amirkeivan Mohtashami, Matteo Pagliardini, Martin Jaggi*. [[pdf](https://arxiv.org/abs/2310.10845)], 2024.08. ![](https://img.shields.io/badge/ICLR2025-orange) ![](https://img.shields.io/badge/CoTFormer-blue)
- **Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning**   
  *Qifan Yu, Zhenyu He, Sijie Li, Xun Zhou, Jun Zhang, Jingjing Xu, Di He*. [[pdf](https://arxiv.org/pdf/2502.08482)], [[code](https://github.com/qifanyu/RELAY)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/RELAY-blue)
- **TwT: Thinking without Tokens by Habitual Reasoning Distillation with Multi-Teachers' Guidance**   
  *Jingxian Xu, Mengyu Zhou, Weichang Liu, Hanbing Liu, Shi Han, Dongmei Zhang*. [[pdf](https://arxiv.org/pdf/2503.24198)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/TwT-blue)

#### Horizontal Level

##### Discrete Tokens

- **Guiding Language Model Reasoning with Planning Tokens**  
  *Xinyi Wang, Lucas Caccia, Oleksiy Ostapenko, Xingdi Yuan, William Yang Wang, Alessandro Sordoni*. [[pdf](https://arxiv.org/pdf/2310.05707)], [[code](https://github.com/WANGXinyiLinda/planning_tokens)], 2023.10. ![](https://img.shields.io/badge/COLM2024-orange) ![](https://img.shields.io/badge/planning_tokens-blue)
- **Let's think dot by dot: Hidden computation in transformer language models**  
  *Jacob Pfau, William Merrill, Samuel R. Bowman*. [[pdf](https://arxiv.org/pdf/2404.15758)], [[code](https://github.com/JacobPfau/fillerTokens)], 2024.04. ![](https://img.shields.io/badge/COLM2024-orange) ![](https://img.shields.io/badge/filler_tokens-blue)
- **Disentangling Memory and Reasoning Ability in Large Language Models**  
  *Mingyu Jin, Weidi Luo, Sitao Cheng, Xinyi Wang, Wenyue Hua, Ruixiang Tang, William Yang Wang, Yongfeng Zhang*. [[pdf](https://arxiv.org/pdf/2411.13504)], [[code](https://github.com/MingyuJ666/Disentangling-Memory-and-Reasoning)], 2024.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Token Assorted: Mixing Latent and Text Tokens for Improved Language Model Reasoning**  
  *DiJia Su, Hanlin Zhu, Yingchen Xu, Jiantao Jiao, Yuandong Tian, Qinqing Zheng*. [[pdf](https://arxiv.org/pdf/2502.03275)], 2025.02.  ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/VQ--VAE-lightgray)

##### Continuous Tokens

- **Expediting and Elevating Large Language Model Reasoning via Hidden Chain-of-Thought Decoding**  
  *Tianqiao Liu, Zui Chen, Zitao Liu, Mi Tian, Weiqi Luo*. [[pdf](https://arxiv.org/pdf/2409.08561)], 2024.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/HCoT-blue)
- **Training Large Language Models to Reason in a Continuous Latent Space**  
  *Shibo Hao, Sainbayar Sukhbaatar, DiJia Su, Xian Li, Zhiting Hu, Jason Weston, Yuandong Tian*. [[pdf](https://arxiv.org/pdf/2412.06769)], [[code](https://github.com/facebookresearch/coconut)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Coconut-blue)
- **Compressed Chain of Thought: Efficient Reasoning Through Dense Representations**  
  *Jeffrey Cheng, Benjamin Van Durme*. [[pdf](https://arxiv.org/pdf/2412.13171)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CCoT-blue) ![](https://img.shields.io/badge/Compressed_representations-lightgray)
- **SoftCoT: Soft Chain-of-Thought for Efficient Reasoning with LLMs**  
  *Yige Xu, Xu Guo, Zhiwei Zeng, Chunyan Miao*. [[pdf](https://arxiv.org/pdf/2502.12134)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SoftCoT-blue) 
- **LightThinker: Thinking Step-by-Step Compression**  
  *Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, Shuofei Qiao, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang*. [[pdf](https://arxiv.org/pdf/2502.15589)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LightThinker-blue)
- **CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation**  
  *Zhenyi Shen, Hanqi Yan, Linhai Zhang, Zhanghao Hu, Yali Du, Yulan He*. [[pdf](https://arxiv.org/pdf/2502.21074)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CODI-blue)

### Analysis and Interpretability
- **Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to the Edge of Generalization**  
  *Boshi Wang, Xiang Yue, Yu Su, Huan Sun*. [[pdf](https://arxiv.org/pdf/2405.15071)], 2024.05. ![](https://img.shields.io/badge/Arxiv-orange)
- **Distributional reasoning in LLMs: Parallel reasoning processes in multi-hop reasoning**  
  *Yuval Shalev, Amir Feder, Ariel Goldstein*. [[pdf](https://arxiv.org/abs/2406.13858)], 2024.06. ![](https://img.shields.io/badge/Arxiv-orange)
- **Can Language Models Learn to Skip Steps?**  
  *Tengxiao Liu, Qipeng Guo, Xiangkun Hu, Cheng Jiayang, Yue Zhang, Xipeng Qiu, Zheng Zhang*. [[pdf](https://arxiv.org/pdf/2411.01855)], [[code](https://github.com/tengxiaoliu/LM_skip)], 2024.09. ![](https://img.shields.io/badge/NIPS2024-orange)
- **Do LLMs Really Think Step-by-step In Implicit Reasoning?**  
  *Yijiong Yu*. [[pdf](https://arxiv.org/pdf/2411.15862)], [[code](https://github.com/yuyijiong/if_step_by_step_implicit_CoT)], 2024.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **The Semantic Hub Hypothesis: Language Models Share Semantic Representations Across Languages and Modalities**  
  *Zhaofeng Wu, Xinyan Velocity Yu, Dani Yogatama, Jiasen Lu, Yoon Kim*. [[pdf](https://arxiv.org/pdf/2502.17416)], [[code](https://github.com/ZhaofengWu/semantic-hub)], 2024.11. ![](https://img.shields.io/badge/ICLR2025-orange)
- **Think-to-Talk or Talk-to-Think? When LLMs Come Up with an Answer in Multi-Step Reasoning**  
  *Keito Kudo, Yoichi Aoki, Tatsuki Kuribayashi, Shusaku Sone, Masaya Taniguchi, Ana Brassard, Keisuke Sakaguchi, Kentaro Inui*. [[pdf](https://arxiv.org/pdf/2412.01113)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange)
- **Reasoning with Latent Thoughts: On the Power of Looped Transformers**  
  *Nikunj Saunshi, Nishanth Dikkala, Zhiyuan Li, Sashank J. Reddi, Sanjiv Kumar*. [[pdf](https://arxiv.org/pdf/2502.17416)], 2025.01. ![](https://img.shields.io/badge/ICLR2025-orange) ![](https://img.shields.io/badge/Looped_Transformers-blue)
- **Implicit Reasoning in Transformers is Reasoning through Shortcuts**  
  *Tianhe Lin, Jian Xie, Siyu Yuan, Deqing Yang*. [[pdf](https://arxiv.org/pdf/2503.07604)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange)
- **Language Models Are Implicitly Continuous**  
  *Samuele Marro, Davide Evangelista, X. Angelo Huang, Emanuele La Malfa, Michele Lombardi, Michael Wooldridge*. [[pdf](https://arxiv.org/pdf/2504.03933)], 2025.04. ![](https://img.shields.io/badge/ICLR2025-orange)
- **Chain-of-Thought Tokens are Computer Program Variables**  
  *Fangwei Zhu, Peiyi Wang, Zhifang Sui*. [[pdf](https://arxiv.org/pdf/2505.04955)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange)


### Applications

- **Multi-modal latent space learning for chain-of-thought reasoning in language models**  
  *Liqi He, Zuchao Li, Xiantao Cai, Ping Wang*. [[pdf](https://arxiv.org/pdf/2312.08762)], [[code](https://github.com/shimurenhlq/DPMM-COT)], 2023.12. ![](https://img.shields.io/badge/AAAI2024-orange)
- **Multimodal Latent Language Modeling with Next-Token Diffusion**  
  *Yutao Sun, Hangbo Bao, Wenhui Wang, Zhiliang Peng, Li Dong, Shaohan Huang, Jianyong Wang, Furu Wei*. [[pdf](https://arxiv.org/pdf/2412.08635)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LatentLM-blue)
- **Efficient Reasoning with Hidden Thinking**  
  *Xuan Shen, Yizhou Wang, Xiangxi Shi, Yanzhi Wang, Pu Zhao, Jiuxiang Gu*. [[pdf](https://arxiv.org/pdf/2501.19201)], [[code](https://github.com/shawnricecake/Heima)], 2025.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Heima-blue)

- **Learning More Effective Representations for Dense Retrieval through Deliberate Thinking Before Search**  
  *Yifan Ji, Zhipeng Xu, Zhenghao Liu, Yukun Yan, Shi Yu, Yishan Li, Zhiyuan Liu, Yu Gu, Ge Yu, Maosong Sun*. [[pdf](https://arxiv.org/pdf/2502.12974)], [[code](https://github.com/OpenBMB/DEBATER)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/DEBATER-blue)
- **Think Before Recommend: Unleashing the Latent Reasoning Power for Sequential Recommendation**  
  *Jiakai Tang, Sunhao Dai, Teng Shi, Jun Xu, Xu Chen, Wen Chen, Wu Jian, Yuning Jiang*. [[pdf](https://arxiv.org/pdf/2503.22675)], [[code](https://github.com/TangJiakai/ReaRec)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ReaRec-blue)
- **Enhancing Non-Core Language Instruction-Following in Speech LLMs via Semi-Implicit Cross-Lingual CoT Reasoning**
  *Hongfei Xue, Yufeng Tang, Hexin Liu, Jun Zhang, Xuelong Geng, Lei Xie*. [[pdf](https://arxiv.org/pdf/2504.20835)], 2025.04. ![](https://img.shields.io/badge/Arxiv-orange)
  

### Other related work or pending to be specified

- **Language Models are Hidden Reasoners: Unlocking Latent Reasoning Capabilities via Self-Rewarding**  
  *Haolin Chen, Yihao Feng, Zuxin Liu, Weiran Yao, Akshara Prabhakar, Shelby Heinecke, Ricky Ho, Phil Mui, Silvio Savarese, Caiming Xiong, Huan Wang*. [[pdf](https://arxiv.org/pdf/2411.04282)], [[code](https://github.com/SalesforceAIResearch/LaTRO)], 2024.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Searching Latent Program Spaces**  
  *Clément Bonnet, Matthew V Macfarlane*. [[pdf](https://arxiv.org/pdf/2411.08706)], [[code](https://github.com/clement-bonnet/lpn)], 2024.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Deliberation in Latent Space via Differentiable Cache Augmentation**  
  *Luyang Liu, Jonas Pfeiffer, Jiaxing Wu, Jun Xie, Arthur Szlam*. [[pdf](https://arxiv.org/abs/2412.17747)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange)
- **Large Concept Models: Language Modeling in a Sentence Representation Space**  
  *LCM team, Loïc Barrault, Paul-Ambroise Duquenne, Maha Elbayad, Artyom Kozhevnikov, Belen Alastruey, Pierre Andrews, Mariano Coria, Guillaume Couairon, Marta R. Costa-jussà, David Dale, Hady Elsahar, Kevin Heffernan, João Maria Janeiro, Tuan Tran, Christophe Ropers, Eduardo Sánchez, Robin San Roman, Alexandre Mourachko, Safiyyah Saleem, Holger Schwenk*. [[pdf](https://arxiv.org/pdf/2412.08821)], [[code](https://github.com/facebookresearch/large_concept_model)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange)
- **Beyond Words: A Latent Memory Approach to Internal Reasoning in LLMs**  
  *José I. Orlicki*. [[pdf](https://arxiv.org/pdf/2502.21030)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange)
- **SEAL: Steerable Reasoning Calibration of Large Language Models for Free**  
  *Runjin Chen, Zhenyu Zhang, Junyuan Hong, Souvik Kundu, Zhangyang Wang*. [[pdf](https://arxiv.org/pdf/2504.07986)], [[code](https://github.com/VITA-Group/SEAL)], 2025.04. ![](https://img.shields.io/badge/Arxiv-orange)

## Resources
For most recent **Efficient Reasoning** research, see [Awesome-Efficient-Reasoning](https://github.com/hemingkx/Awesome-Efficient-Reasoning).

## Acknowledgements

If I’ve accidentally missed your papers on the list, please reach out to me, and I’ll make sure to add them as soon as possible!
