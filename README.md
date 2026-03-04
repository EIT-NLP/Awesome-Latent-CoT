<div align="center">
<h1><img src="assets/logo.png" height="32px"/> Reasoning Beyond Language: A Comprehensive Survey on Latent Chain-of-Thought Reasoning</h1> 
</div>

<div align="center">
<b>Xinghao Chen</b><sup>1,2</sup>,
<b>Anhao Zhao</b><sup>2</sup>,
<b>Heming Xia</b><sup>1</sup>,
<b>Xuan Lu</b><sup>2</sup>,
<b>Hanlin Wang</b><sup>1</sup>,
</div>
<div align="center">
<b>Yanjun Chen</b><sup>1,2</sup>,
<b>Wei Zhang</b><sup>2</sup>,
<b>Jian Wang</b><sup>1</sup>,
<b>Wenjie Li</b><sup>1</sup>,
<b>Xiaoyu Shen</b><sup>2</sup>
</div>

<div align="center">
<sup>1</sup>Department of Computing, The Hong Kong Polytechnic University
</div>
<div align="center">
<sup>2</sup>Ningbo Digital Twin Institute, Eastern Institute of Technology, Ningbo, China
</div>

![Intro](./assets/Intro.png)

This repository contains a regularly updated paper list for **Latent CoT Reasoning**.

<p align="center">
<a href="https://arxiv.org/abs/2505.16782">
  <img src="https://img.shields.io/badge/Arxiv-2505.16782-orange.svg"></a> 
<a href="https://awesome.re">
  <img src="https://awesome.re/badge.svg" alt="Awesome"></a>
<a href="https://opensource.org/licenses/Apache-2.0">
  <img src="https://img.shields.io/badge/License-Apache_2.0-green.svg"></a> 
<a href="https://github.com/EIT-NLP/Awesome-Latent-CoT/pulls">
    <img src="https://img.shields.io/badge/Contributions-welcome-blue.svg?style=flat"></a>
<img src="https://img.shields.io/github/last-commit/EIT-NLP/Awesome-Latent-CoT/main?logo=github&color=blue" alt="Last Commit">
</p>

<p align="center"><em>
Whereof one cannot speak, thereof one must be silent.
-- Ludwig Wittgenstein
</em></p>

Reasoning in latent space shifts the way AI models think, moving beyond language tokens to represent thought processes in a more abstract, non-language space. Just as humans often think without words, latent space allows for more flexible and efficient reasoning.

### Key advantages include:
1. **Richer Thought Representation**: Latent space captures complex, non-verbal thoughts that language alone can't express.
2. **Lower Latency**: It allows for higher information density, reducing the need for token-based decoding and speeding up reasoning.

This approach brings AI closer to human-like cognition, enabling faster, more flexible, and powerful models for real-world tasks.

## Citation

If you find our survey useful for your research, please consider citing the following paper:

```bibtex
@article{eit2025latentcot,
      title={Reasoning Beyond Language: A Comprehensive Survey on Latent Chain-of-Thought Reasoning}, 
      author={Xinghao Chen and Anhao Zhao and Heming Xia and Xuan Lu and Hanlin Wang and Yanjun Chen and Wei Zhang and Jian Wang and Wenjie Li and Xiaoyu Shen},
      year={2025},
      eprint={2505.16782},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2505.16782}, 
}
```

## Updates

- 2025-05-22: 📝 The survey is now available on [arXiv](https://arxiv.org/abs/2505.16782)!
- 2025-02-16: 🚀 Latent CoT Repo launched!

## Content

- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
    - [Token-wise Strategies](#token-wise-strategies)
        - [Discrete Tokens](#discrete-tokens)
        - [Continuous Tokens](#continuous-tokens)
    - [Internal Mechanisms](#internal-mechanisms)
        - [Structural CoT](#structural-cot)
        - [Representational CoT](#representational-cot)
    - [Analysis and Interpretability](#analysis-and-interpretability)
    - [Applications and Future Directions](#applications-and-future-directions)
- [Resources](#resources)
- [Acknowledgements](#acknowledgements)

## Keywords Convention

![](https://img.shields.io/badge/Coconut-blue) Abbreviation

![](https://img.shields.io/badge/NIPS2024-orange) Conference

![](https://img.shields.io/badge/Reconstruction-lightgray) Main Features

## Papers

### Token-wise Strategies

#### Discrete Tokens

- **Think before you speak: Training language models with pause tokens**  
  *Sachin Goyal,Ziwei Ji, Ankit Singh Rawat, Aditya Krishna Menon, Sanjiv Kumar, Vaishnavh Nagarajan*. [[pdf](https://arxiv.org/pdf/2310.02226)], 2023.10. ![](https://img.shields.io/badge/ICLR2024-orange) ![](https://img.shields.io/badge/pause_tokens-blue) ![](https://img.shields.io/badge/Pretraining-lightgray)
- **Guiding Language Model Reasoning with Planning Tokens**  
  *Xinyi Wang, Lucas Caccia, Oleksiy Ostapenko, Xingdi Yuan, William Yang Wang, Alessandro Sordoni*. [[pdf](https://arxiv.org/pdf/2310.05707)], [[code](https://github.com/WANGXinyiLinda/planning_tokens)], 2023.10. ![](https://img.shields.io/badge/COLM2024-orange) ![](https://img.shields.io/badge/planning_tokens-blue)
- **Thinking Tokens for Language Modeling**  
  *David Herel, Tomas Mikolov*. [[pdf](https://arxiv.org/pdf/2405.08644)],  2024.05. ![](https://img.shields.io/badge/AITP2023-orange) ![](https://img.shields.io/badge/thinking_tokens-blue)
- **Let's think dot by dot: Hidden computation in transformer language models**  
  *Jacob Pfau, William Merrill, Samuel R. Bowman*. [[pdf](https://arxiv.org/pdf/2404.15758)], [[code](https://github.com/JacobPfau/fillerTokens)], 2024.04. ![](https://img.shields.io/badge/COLM2024-orange) ![](https://img.shields.io/badge/filler_tokens-blue)
- **Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking**  
  *Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman*. [[pdf](https://arxiv.org/pdf/2403.09629)], 2024.03. ![](https://img.shields.io/badge/COLM2024-orange) ![](https://img.shields.io/badge/Quiet--STaR-blue) ![](https://img.shields.io/badge/Pretraining-lightgray)
- **Reasoning to Learn from Latent Thoughts**  
  *Yangjun Ruan, Neil Band, Chris J. Maddison, Tatsunori Hashimoto*. [[pdf](https://arxiv.org/pdf/2503.18866)], [[code](https://github.com/ryoungj/BoLT)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/BoLT-blue)
- **Mining Hidden Thoughts from Texts: Evaluating Continual Pretraining with Synthetic Data for LLM Reasoning**  
  *Yoichi Ishibashi, Taro Yano, Masafumi Oyamada*. [[pdf](https://arxiv.org/pdf/2505.10182)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CPT-blue)
- **Disentangling Memory and Reasoning Ability in Large Language Models**  
  *Mingyu Jin, Weidi Luo, Sitao Cheng, Xinyi Wang, Wenyue Hua, Ruixiang Tang, William Yang Wang, Yongfeng Zhang*. [[pdf](https://arxiv.org/pdf/2411.13504)], [[code](https://github.com/MingyuJ666/Disentangling-Memory-and-Reasoning)], 2024.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Token Assorted: Mixing Latent and Text Tokens for Improved Language Model Reasoning**  
  *DiJia Su, Hanlin Zhu, Yingchen Xu, Jiantao Jiao, Yuandong Tian, Qinqing Zheng*. [[pdf](https://arxiv.org/pdf/2502.03275)], 2025.02.  ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/VQ--VAE-lightgray)
- **Latent Preference Coding: Aligning Large Language Models via Discrete Latent Codes**  
  *Zhuocheng Gong, Jian Guan, Wei Wu, Huishuai Zhang, Dongyan Zhao*. [[pdf](https://arxiv.org/pdf/2505.04993)], 2025.02.  ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LPC-blue)
- **Efficient Pretraining Length Scaling**  
  *Bohong Wu, Shen Yan, Sijun Zhang, Jianqiao Lu, Yutao Zeng, Ya Wang, Xun Zhou*. [[pdf](https://arxiv.org/pdf/2504.14992)], 2025.04.  ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/PHD--Transformer-blue)
- **Fast Thinking for Large Language Models**  
  *Haoyu Zheng, Zhuonan Wang, Yuqian Yuan, Tianwei Lin, Wenqiao Zhang, Zheqi Lv, Juncheng Li, Siliang Tang, Yueting Zhuang, Hongyang He*. [[pdf](https://arxiv.org/pdf/2509.23633)], 2025.09.  ![](https://img.shields.io/badge/Arxiv-orange)

#### Continuous Tokens 

- **Training Large Language Models to Reason in a Continuous Latent Space**  
  *Shibo Hao, Sainbayar Sukhbaatar, DiJia Su, Xian Li, Zhiting Hu, Jason Weston, Yuandong Tian*. [[pdf](https://arxiv.org/pdf/2412.06769)], [[code](https://github.com/facebookresearch/coconut)], 2024.12. ![](https://img.shields.io/badge/COLM2025-orange) ![](https://img.shields.io/badge/Coconut-blue)
- **Compressed Chain of Thought: Efficient Reasoning Through Dense Representations**  
  *Jeffrey Cheng, Benjamin Van Durme*. [[pdf](https://arxiv.org/pdf/2412.13171)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CCoT-blue) ![](https://img.shields.io/badge/Compressed_representations-lightgray)
- **Expediting and Elevating Large Language Model Reasoning via Hidden Chain-of-Thought Decoding**  
  *Tianqiao Liu, Zui Chen, Zitao Liu, Mi Tian, Weiqi Luo*. [[pdf](https://arxiv.org/pdf/2409.08561)], 2024.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/HCoT-blue) 
- **LightThinker: Thinking Step-by-Step Compression**  
  *Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, Shuofei Qiao, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang*. [[pdf](https://arxiv.org/pdf/2502.15589)], 2025.02. ![](https://img.shields.io/badge/EMNLP2025-orange) ![](https://img.shields.io/badge/LightThinker-blue)
- **CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation**  
  *Zhenyi Shen, Hanqi Yan, Linhai Zhang, Zhanghao Hu, Yali Du, Yulan He*. [[pdf](https://arxiv.org/pdf/2502.21074)], 2025.02. ![](https://img.shields.io/badge/EMNLP2025-orange) ![](https://img.shields.io/badge/CODI-blue)
- **SoftCoT: Soft Chain-of-Thought for Efficient Reasoning with LLMs**  
  *Yige Xu, Xu Guo, Zhiwei Zeng, Chunyan Miao*. [[pdf](https://arxiv.org/pdf/2502.12134)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SoftCoT-blue)
- **SoftCoT++: Test-Time Scaling with Soft Chain-of-Thought Reasoning**  
  *Yige Xu, Xu Guo, Zhiwei Zeng, Chunyan Miao*. [[pdf](https://arxiv.org/pdf/2505.11484)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SoftCoT++-blue)
- **LLM Pretraining with Continuous Concepts**  
  *Jihoon Tack, Jack Lanchantin, Jane Yu, Andrew Cohen, Ilia Kulikov, Janice Lan, Shibo Hao, Yuandong Tian, Jason Weston, Xian Li*. [[pdf](https://arxiv.org/pdf/2502.08524)], [[code](https://github.com/facebookresearch/RAM/tree/main/projects/cocomix)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CoCoMix-blue) ![](https://img.shields.io/badge/Pretraining-lightgray)
- **Soft Thinking: Unlocking the Reasoning Potential of LLMs in Continuous Concept Space**  
  *Zhen Zhang, Xuehai He, Weixiang Yan, Ao Shen, Chenyang Zhao, Shuohang Wang, Yelong Shen, Xin Eric Wang*. [[pdf](https://arxiv.org/pdf/2505.15778)], [[code](https://github.com/eric-ai-lab/Soft-Thinking)], 2025.05. ![](https://img.shields.io/badge/NIPS2025-orange) ![](https://img.shields.io/badge/Soft_Thinking-blue) ![](https://img.shields.io/badge/Training_free-lightgray)
- **Think Silently, Think Fast: Dynamic Latent Compression of LLM Reasoning Chains**  
  *Wenhui Tan, Jiaze Li, Jianzhong Ju, Zhenbo Luo, Jian Luan, Ruihua Song*. [[pdf](https://arxiv.org/pdf/2505.16552)], [[code](https://colar-latent-reasoning.github.io/)], 2025.05. ![](https://img.shields.io/badge/NIPS2025-orange) ![](https://img.shields.io/badge/CoLaR-blue) ![](https://img.shields.io/badge/RL-lightgray)
- **Hybrid Latent Reasoning via Reinforcement Learning**  
  *Zhenrui Yue, Bowen Jin, Huimin Zeng, Honglei Zhuang, Zhen Qin, Jinsung Yoon, Lanyu Shang, Jiawei Han, Dong Wang*. [[pdf](https://arxiv.org/pdf/2505.18454)], [[code](https://github.com/Yueeeeeeee/HRPO)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/HRPO-blue) ![](https://img.shields.io/badge/RL-lightgray)
- **Seek in the Dark: Reasoning via Test-Time Instance-Level Policy Gradient in Latent Space**  
  *Hengli Li, Chenxi Li, Tong Wu, Xuekai Zhu, Yuxuan Wang, Zhaoxin Yu, Eric Hanchen Jiang, Song-Chun Zhu, Zixia Jia, Ying Nian Wu, Zilong Zheng*. [[pdf](https://arxiv.org/pdf/2505.13308)], [[code](https://github.com/Yueeeeeeee/HRPO)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LATENTSEEK-blue) ![](https://img.shields.io/badge/RL-lightgray)
- **Enhancing Latent Computation in Transformers with Latent Tokens**  
  *Yuchang Sun, Yanxi Chen, Yaliang Li, Bolin Ding*. [[pdf](https://arxiv.org/pdf/2505.12629)], [[code](https://github.com/Yueeeeeeee/HRPO)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange)
- **System-1.5 Reasoning: Traversal in Language and Latent Spaces with Dynamic Shortcuts**  
  *Xiaoqiang Wang, Suyuchen Wang, Yun Zhu, Bang Liu*. [[pdf](https://arxiv.org/pdf/2505.18962)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/System--1.5_Reasoning-blue)
- **Text Generation Beyond Discrete Token Sampling**  
  *Yufan Zhuang, Liyuan Liu, Chandan Singh, Jingbo Shang, Jianfeng Gao*. [[pdf](https://arxiv.org/pdf/2505.14827)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/MoI-blue)
- **Efficient Post-Training Refinement of Latent Reasoning in Large Language Models**  
  *Xinyuan Wang, Dongjie Wang, Wangyang Ying, Haoyue Bai, Nanxu Gong, Sixun Dong, Kunpeng Liu, Yanjie Fu*. [[pdf](https://arxiv.org/pdf/2506.08552)], [[code](https://anonymous.4open.science/r/Lateng-Reasoning-5C1D/README.md)], 2025.06. ![](https://img.shields.io/badge/Arxiv-orange) 
- **DART: Distilling Autoregressive Reasoning to Silent Thought**  
  *Nan Jiang, Ziming Wu, De-Chuan Zhan, Fuming Lai, Shaobing Lian*. [[pdf](https://arxiv.org/pdf/2506.11752)], 2025.06. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/DART-blue)
- **Parallel Continuous Chain-of-Thought with Jacobi Iteration**  
  *Haoyi Wu, Zhihao Teng, Kewei Tu*. [[pdf](https://arxiv.org/pdf/2506.18582)], 2025.06. ![](https://img.shields.io/badge/EMNLP2025-orange) ![](https://img.shields.io/badge/PCCoT-blue)
- **LLMs are Single-threaded Reasoners: Demystifying the Working Mechanism of Soft Thinking**  
  *Junhong Wu, Jinliang Lu, Zixuan Ren, Gangqiang Hu, Zhi Wu, Dai Dai, Hua Wu*. [[pdf](https://arxiv.org/pdf/2508.03440)], 2025.08. ![](https://img.shields.io/badge/Arxiv-orange) 
- **SynAdapt: Learning Adaptive Reasoning in Large Language Models via Synthetic Continuous Chain-of-Thought**  
  *Jianwei Wang, Ziming Wu, Fuming Lai, Shaobing Lian, Ziqian Zeng*. [[pdf](https://arxiv.org/pdf/2508.00574)], 2025.08. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SynAdapt-blue)
- **LTA-thinker: Latent Thought-Augmented Training Framework for Large Language Models on Complex Reasoning**  
  *Jiaqi Wang, Binquan Ji, Haibo Luo, Yiyang Qi, Ruiting Li, Huiyan Wang, Yuantao Han, Cangyi Yang, jiaxu Zhang, Feiliang Ren*. [[pdf](https://arxiv.org/pdf/2509.12875)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LTA--thinker-blue)
- **Soft Tokens, Hard Truths**  
  *Natasha Butt, Ariel Kwiatkowski, Ismail Labiad, Julia Kempe, Yann Ollivier*. [[pdf](https://arxiv.org/pdf/2509.19170)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange)
- **SIM-CoT: Supervised Implicit Chain-of-Thought**  
  *Xilin Wei, Xiaoran Liu, Yuhang Zang, Xiaoyi Dong, Yuhang Cao, Jiaqi Wang, Xipeng Qiu, Dahua Lin*. [[pdf](https://arxiv.org/pdf/2509.20317)], [[code](https://github.com/InternLM/SIM-CoT)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SIM--CoT-blue)
- **R-Capsule: Compressing High-Level Plans for Efficient Large Language Model Reasoning**  
  *Hongyu Shan, Mingyang Song, Chang Dai, Di Liang, Han Chen*. [[pdf](https://arxiv.org/pdf/2509.22131)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/R--Capsule-blue)
- **Pretraining LLM with Latent Thoughts in Continuous Space**  
  *Boyi Zeng, He Li, Shixiang Song, Yixuan Wang, Ziwei He, Xinbing Wang, Zhouhan Lin*. [[pdf](https://arxiv.org/pdf/2509.23184)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Pythia_Arch-blue)
- **MARCOS: Deep Thinking by Markov Chain of Continuous Thoughts**  
  *Jiayu Liu, Zhenya Huang, Anya Sims, Enhong Chen, Yee Whye Teh, Ning Miao*. [[pdf](https://arxiv.org/pdf/2509.25020)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/MARCOS-blue)
- **Latent Thinking Optimization: Your Latent Reasoning Language Model Secretly Encodes Reward Signals in its Latent Thoughts**  
  *Hanwen Du, Yuxin Dong, Xia Ning*. [[pdf](https://arxiv.org/pdf/2509.26314)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LTO-blue)
- **LatentEvolve: Self-Evolving Test-Time Scaling in Latent Space**  
  *Guibin Zhang, Fanci Meng, Guancheng Wan, Zherui Li, Kun Wang, Zhenfei Yin, Lei Bai, Shuicheng Yan*. [[pdf](https://arxiv.org/pdf/2509.24771)], [[code](https://github.com/jins7/LatentEvolve)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LatentEvolve-blue)
- **SwiReasoning: Switch-Thinking in Latent and Explicit for Pareto-Superior Reasoning LLMs**  
  *Dachuan Shi, Abedelkadir Asi, Keying Li, Xiangchi Yuan, Leyan Pan, Wenke Lee, Wen Xiao*. [[pdf](https://arxiv.org/pdf/2510.05069)], [[code](https://github.com/sdc17/SwiReasoning)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SwiReasoning-blue)
- **KaVa: Latent Reasoning via Compressed KV-Cache Distillation**  
  *Anna Kuzina, Maciej Pioro, Paul N. Whatmough, Babak Ehteshami Bejnordi*. [[pdf](https://arxiv.org/pdf/2510.02312)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/KaVa-blue)
- **Parallel Test-Time Scaling for Latent Reasoning Models**  
  *Runyang You, Yongqi Li, Meng Liu, Wenjie Wang, Liqiang Nie, Wenjie Li*. [[pdf](https://arxiv.org/pdf/2510.07745)], [[code](https://github.com/YRYangang/LatentTTS)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LatentRM-blue)
- **Thinking on the Fly: Test-Time Reasoning Enhancement via Latent Thought Policy Optimization**  
  *Wengao Ye, Yan Liang, Lianlei Shan*. [[pdf](https://arxiv.org/pdf/2510.04182)], [[code](https://github.com/ltpo2025/LTPO)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LTPO-blue)
- **Towards Inference-time Scaling for Continuous Space Reasoning**  
  *Minghan Wang, Thuy-Trang Vu, Ehsan Shareghi, Gholamreza Haffari*. [[pdf](https://arxiv.org/pdf/2510.12167)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange)
- **Latent Reasoning in LLMs as a Vocabulary-Space Superposition**  
  *Jingcheng Deng, Liang Pang, Zihao Wei, Shichen Xu, Zenghao Duan, Kun Xu, Yang Song, Huawei Shen, Xueqi Cheng*. [[pdf](https://arxiv.org/pdf/2510.15522)], [[code](https://github.com/DJC-GO-SOLO/Latent-SFT)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Latent--SFT-blue)
- **LaDiR: Latent Diffusion Enhances LLMs for Text Reasoning**  
  *Haoqiang Kang, Yizhe Zhang, Nikki Lijing Kuang, Nicklas Majamaki, Navdeep Jaitly, Yi-An Ma, Lianhui Qin*. [[pdf](https://www.arxiv.org/pdf/2510.04573)], [[code](https://github.com/mk322/LaDiR)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LVR-blue)
- **SemCoT: Accelerating Chain-of-Thought Reasoning through Semantically-Aligned Implicit Tokens**  
  *Yinhan He, Wendy Zheng, Yaochen Zhu, Zaiyi Zheng, Lin Su, Sriram Vasudevan, Qi Guo, Liangjie Hong, Jundong Li*. [[pdf](https://arxiv.org/pdf/2510.24940)], [[code](https://github.com/YinhanHe123/SemCoT)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/SemCoT-blue)
- **SofT-GRPO: Surpassing Discrete-Token LLM Reinforcement Learning via Gumbel-Reparameterized Soft-Thinking Policy Optimization**  
  *Zhi Zheng, Yu Gu, Wei Liu, Yee Whye Teh, Wee Sun Lee*. [[pdf](https://arxiv.org/pdf/2511.06411)], [[code](https://github.com/zz1358m/SofT-GRPO-master)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/SofT--GRPO-blue)
- **Think Consistently, Reason Efficiently: Energy-Based Calibration for Implicit Chain-of-Thought**  
  *Zhikang Chen, Sen Cui, Deheng Ye, Yu Zhang, Yatao Bian, Tingting Zhu*. [[pdf](https://arxiv.org/pdf/2511.07124)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/EBM--CoT-blue)
- **SpiralThinker: Latent Reasoning through an Iterative Process with Text-Latent Interleaving**  
  *Shengmin Piao, Sanghyun Park*. [[pdf](https://arxiv.org/pdf/2511.08983)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/SpiralThinker-blue)
- **Think-at-Hard: Selective Latent Iterations to Improve Reasoning Language Models**  
  *Tianyu Fu, Yichen You, Zekai Chen, Guohao Dai, Huazhong Yang, Yu Wang*. [[pdf](https://arxiv.org/pdf/2511.08577)], [[code](https://github.com/thu-nics/TaH)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/TaH-blue)
- **Improving Latent Reasoning in LLMs via Soft Concept Mixing**  
  *Kang Wang, Xiangyu Duan, Tianyi Du*. [[pdf](https://arxiv.org/pdf/2511.16885)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/SCM-blue)
- **Learning When to Stop: Adaptive Latent Reasoning via Reinforcement Learning**  
  *Alex Ning, Yen-Ling Kuo, Gabe Gomes*. [[pdf](https://arxiv.org/abs/2511.21581)], [[code](https://github.com/apning/adaptive-latent-reasoning)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Lightweight Latent Reasoning for Narrative Tasks**  
  *Alexander Gurung, Nikolay Malkin, Mirella Lapata*. [[pdf](https://arxiv.org/pdf/2512.02240)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LiteReason-blue)
- **Reinforcement Learning for Latent-Space Thinking in LLMs**  
  *Enes Özeren, Matthias Aßenmacher*. [[pdf](https://arxiv.org/pdf/2512.11816)], [[code](https://github.com/enesozeren/latent-space-thinking-model)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)
- **JEPA-Reasoner: Decoupling Latent Reasoning from Token Generation**  
  *Bingyang Kelvin Liu, Ziyu Patrick Chen, David P. Woodruff*. [[pdf](https://arxiv.org/pdf/2512.19171)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/JEPA--Reasoner-blue)
- **Dynamic Large Concept Models: Latent Reasoning in an Adaptive Semantic Space**  
  *Xingwei Qu, Shaowen Wang, Zihao Huang, Kai Hua, Fan Yin, Rui-Jie Zhu, Jundong Zhou, Qiyang Min, Zihao Wang, Yizhi Li, Tianyu Zhang, He Xing, Zheng Zhang, Yuxuan Song, Tianyu Zheng, Zhiyuan Zeng, Chenghua Lin, Ge Zhang, Wenhao Huang*. [[pdf](https://arxiv.org/pdf/2512.24617)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/DLCM-blue)
- **iCLP: Large Language Model Reasoning with Implicit Cognition Latent Planning**  
  *Sijia Chen, Di Niu*. [[pdf](https://www.arxiv.org/pdf/2512.24014)], [[code](https://github.com/AgenticFinLab/latent-planning)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/iCLP-blue)
- **Beyond Imitation: Reinforcement Learning for Active Latent Planning**  
  *Zhi Zheng, Wee Sun Lee*. [[pdf](https://arxiv.org/pdf/2601.21598)], [[code](https://github.com/zz1358m/ATP-Latent-master)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ATP--Latent-blue)
- **Latent Chain-of-Thought as Planning: Decoupling Reasoning from Verbalization**  
  *Jiecong Wang, Hao Peng, Chunyang Liu*. [[pdf](https://arxiv.org/pdf/2601.21358)], [[code](https://github.com/zz1358m/ATP-Latent-master)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/PLaT-blue)
- **Chain Of Thought Compression: A Theoritical Analysis**  
  *Juncai Li, Ru Li, Yuxiang Zhou, Boxiang Ma, Jeff Z. Pan*. [[pdf](https://arxiv.org/pdf/2601.21576)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ALiCoT-blue)
- **Render-of-Thought: Rendering Textual Chain-of-Thought as Images for Visual Latent Reasoning**  
  *Yifan Wang, Shiyu Li, Peiming Li, Xiaochen Yang, Yang Tang, Zheng Wei*. [[pdf](https://arxiv.org/pdf/2601.14750)], [[code](https://github.com/TencentBAC/RoT)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/RoT-blue)
- **ImgCoT: Compressing Long Chain of Thought into Compact Visual Tokens for Efficient Reasoning of Large Language Model**  
  *Xiaoshu Chen, Sihang Zhou, Ke Liang, Taichun Zhou, Xinwang Liu*. [[pdf](https://arxiv.org/pdf/2601.22730)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ImgCoT-blue)
- **ReGuLaR: Variational Latent Reasoning Guided by Rendered Chain-of-Thought**  
  *Fanmeng Wang, Haotian Liu, Guojiang Zhao, Hongteng Xu, Zhifeng Gao*. [[pdf](https://arxiv.org/pdf/2601.23184)], [[code](https://github.com/FanmengWang/ReGuLaR)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ReGuLaR-blue)

### Internal Mechanisms

#### Structural CoT

- **CoTFormer: A Chain-of-Thought Driven Architecture with Budget-Adaptive Computation Cost at Inference**   
  *Amirkeivan Mohtashami, Matteo Pagliardini, Martin Jaggi*. [[pdf](https://arxiv.org/abs/2310.10845)], 2024.08. ![](https://img.shields.io/badge/ICLR2025-orange) ![](https://img.shields.io/badge/CoTFormer-blue)
- **Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach**  
  *Jonas Geiping, Sean McLeish, Neel Jain, John Kirchenbauer, Siddharth Singh, Brian R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Tom Goldstein*. [[pdf](https://arxiv.org/pdf/2502.05171)], [[code](https://github.com/seal-rg/recurrent-pretraining)], [[model](https://huggingface.co/tomg-group-umd/huginn-0125)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Huggin-blue) ![](https://img.shields.io/badge/Depth_Recurrence-lightgray)
- **Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning**   
  *Qifan Yu, Zhenyu He, Sijie Li, Xun Zhou, Jun Zhang, Jingjing Xu, Di He*. [[pdf](https://arxiv.org/pdf/2502.08482)], [[code](https://github.com/qifanyu/RELAY)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/RELAY-blue)
- **Inner Thinking Transformer: Leveraging Dynamic Depth Scaling to Foster Adaptive Internal Thinking**  
  *Yilong Chen, Junyuan Shang, Zhenyu Zhang, Yanxi Xie, Jiawei Sheng, Tingwen Liu, Shuohuan Wang, Yu Sun, Hua Wu, Haifeng Wang*. [[pdf](https://arxiv.org/pdf/2502.13842)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ITT-blue)
- **Reasoning with Latent Thoughts: On the Power of Looped Transformers**  
  *Nikunj Saunshi, Nishanth Dikkala, Zhiyuan Li, Sashank J. Reddi, Sanjiv Kumar*. [[pdf](https://arxiv.org/pdf/2502.17416)], 2025.01. ![](https://img.shields.io/badge/ICLR2025-orange) ![](https://img.shields.io/badge/Looped_Transformers-blue)
- **Pretraining Language Models to Ponder in Continuous Space**  
  *Boyi Zeng, Shixiang Song, Siyuan Huang, Yixuan Wang, He Li, Ziwei He, Xinbing Wang, Zhiyu Li, Zhouhan Lin*. [[pdf](https://arxiv.org/pdf/2505.20674)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Pondering%20LM-blue)
- **The 4th Dimension for Scaling Model Size**  
  *Ruike Zhu, Hanwen Zhang, Tianyu Shi, Chi Wang, Tianyi Zhou, Zengyi Qin*. [[pdf](https://arxiv.org/pdf/2506.18233)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/VLD-blue)
- **Hierarchical Reasoning Model**  
  *Guan Wang, Jin Li, Yuhao Sun, Xing Chen, Changling Liu, Yue Wu, Meng Lu, Sen Song, Yasin Abbasi Yadkori*. [[pdf](https://arxiv.org/pdf/2506.21734)], [[code](https://github.com/sapientinc/HRM)], 2025.06. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/HRM-blue)
- **Skip a Layer or Loop it? Test-Time Depth Adaptation of Pretrained LLMs**  
  *Ziyue Li, Yang Li, Tianyi Zhou*. [[pdf](https://arxiv.org/pdf/2507.07996)], 2025.07. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CoLa-blue)
- **Mixture-of-Recursions: Learning Dynamic Recursive Depths for Adaptive Token-Level Computation**  
  *Sangmin Bae, Yujin Kim, Reza Bayat, Sungnyun Kim, Jiyoun Ha, Tal Schuster, Adam Fisch, Hrayr Harutyunyan, Ziwei Ji, Aaron Courville, Se-Young Yun*. [[pdf](https://arxiv.org/pdf/2507.10524)], 2025.07. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/MoR-blue)
- **Less is More: Recursive Reasoning with Tiny Networks**  
  *Alexia Jolicoeur-Martineau*. [[pdf](https://www.arxiv.org/pdf/2510.04871)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/TRM-blue)
- **Encode, Think, Decode: Scaling test-time reasoning with recursive latent thoughts**  
  *Yeskendir Koishekenov, Aldo Lipani, Nicola Cancedda*. [[pdf](https://arxiv.org/pdf/2510.07358)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ETD-blue)
- **Unlocking Out-of-Distribution Generalization in Transformers via Recursive Latent Space Reasoning**  
  *Awni Altabaa, Siyu Chen, John Lafferty, Zhuoran Yang*. [[pdf](https://arxiv.org/pdf/2510.14095)], [[code](https://github.com/Awni00/algorithmic-generalization-transformer-architectures)] 2025.10. ![](https://img.shields.io/badge/Arxiv-orange)
- **Scaling Latent Reasoning via Looped Language Models**  
  *Rui-Jie Zhu, Zixuan Wang, Kai Hua, Tianyu Zhang, Ziniu Li, Haoran Que, Boyi Wei, Zixin Wen, Fan Yin, He Xing, Lu Li, Jiajun Shi, Kaijing Ma, Shanda Li, Taylor Kergan, Andrew Smith, Xingwei Qu, Mude Hui, Bohong Wu, Qiyang Min, Hongzhi Huang, Xun Zhou, Wei Ye, Jiaheng Liu, Jian Yang, Yunfeng Shi, Chenghua Lin, Enduo Zhao, Tianle Cai, Ge Zhang, Wenhao Huang, Yoshua Bengio, Jason Eshraghian*. [[pdf](https://arxiv.org/pdf/2510.25741)], [[code](https://ouro-llm.github.io/)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Ouro-blue)
- **Parallel Loop Transformer for Efficient Test-Time Computation Scaling**  
  *Bohong Wu, Mengzhao Chen, Xiang Luo, Shen Yan, Qifan Yu, Fan Xia, Tianqi Zhang, Hongrui Zhan, Zheng Zhong, Xun Zhou, Siyuan Qiao, Xingyan Bin*. [[pdf](https://arxiv.org/pdf/2510.24824)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/PLT-blue)
- **MeSH: Memory-as-State-Highways for Recursive Transformers**  
  *Chengting Yu, Xiaobo Shu, Yadao Wang, Yizhen Zhang, Haoyi Wu, Jiaang Li, Rujiao Long, Ziheng Chen, Yuchi Xu, Wenbo Su, Bo Zheng*. [[pdf](https://arxiv.org/pdf/2510.07739)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/MeSH-blue) 
- **LSRL: Process-Supervised GRPO on Latent Recurrent States Improves Mathematical Reasoning**  
  *Hangliang Ren*. [[pdf](https://aclanthology.org/2025.findings-emnlp.669.pdf)], 2025.11. ![](https://img.shields.io/badge/EMNLP2025-orange) ![](https://img.shields.io/badge/LSRL-blue) 
- **Teaching Pretrained Language Models to Think Deeper with Retrofitted Recurrence**  
  *Sean McLeish, Ang Li, John Kirchenbauer, Dayal Singh Kalra, Brian R. Bartoldson, Bhavya Kailkhura, Avi Schwarzschild, Jonas Geiping, Tom Goldstein, Micah Goldblum*. [[pdf](https://arxiv.org/pdf/2511.07384)], [[code](https://github.com/mcleish7/retrofitting-recurrence)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Accelerating Training Speed of Tiny Recursive Models via Curriculum Guided Adaptive Recursion**  
  *Kaleem Ullah Qasim, Jiashu Zhang*. [[pdf](https://arxiv.org/pdf/2511.08653)], [[code](https://github.com/mcleish7/retrofitting-recurrence)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CGAR-blue) 
- **Deep Improvement Supervision**  
  *Arip Asadulaev, Rayan Banerjee, Fakhri Karray, Martin Takac*. [[pdf](https://arxiv.org/pdf/2511.16886)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange) 
- **Universal Reasoning Model**  
  *Zitian Gao, Lynx Chen, Yihao Xiao, He Xing, Ran Tao, Haoming Luo, Joey Zhou, Bryan Dai*. [[pdf](https://arxiv.org/pdf/2512.14693)], [[code](https://github.com/zitian-gao/URM)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/URM-blue)
- **Recursive Language Models**  
  *Alex L. Zhang, Tim Kraska, Omar Khattab*. [[pdf](https://arxiv.org/pdf/2512.24601v1)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/RLMs-blue) 
- **Depth-Recurrent Attention Mixtures: Giving Latent Reasoning the Attention it Deserves**  
  *Jonas Knupp, Jan Hendrik Metzen, Jeremias Bohn, Georg Groh, Kristian Kersting*. [[pdf](https://arxiv.org/pdf/2601.21582)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Dreamer-blue) 

#### Representational CoT

- **Implicit Chain of Thought Reasoning via Knowledge Distillation**  
  *Yuntian Deng, Kiran Prasad, Roland Fernandez, Paul Smolensky, Vishrav Chaudhary, Stuart Shieber*. [[pdf](https://arxiv.org/pdf/2311.01460)], [[code](https://github.com/da03/implicit_chain_of_thought/)], 2023.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/ICoT-blue) 
- **From Explicit CoT to Implicit CoT: Learning to Internalize CoT Step by Step**  
  *Yuntian Deng, Yejin Choi, Stuart Shieber*. [[pdf](https://arxiv.org/pdf/2405.14838)], [[code](https://github.com/da03/Internalize_CoT_Step_by_Step)], 2024.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Stepwise_Internalization-lightgray)
- **Distilling System 2 into System 1**   
  *Ping Yu, Jing Xu, Jason Weston, Ilia Kulikov*. [[pdf](https://arxiv.org/pdf/2407.06023)], 2024.06. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/System_2_Distillation-lightgray)

### Analysis and Interpretability

- **On the Biology of a Large Language Model**  
  *Anthropic*. [[pdf](https://transformer-circuits.pub/2025/attribution-graphs/biology.html)], 2025.03. ![](https://img.shields.io/badge/BLOG-orange)
- **Jump to Conclusions: Short-Cutting Transformers with Linear Transformations**  
  *Alexander Yom Din, Taelin Karidi, Leshem Choshen, Mor Geva*. [[pdf](https://arxiv.org/pdf/2303.09435)], 2023.03. ![](https://img.shields.io/badge/LREC--COLING2024-orange)
- **Towards a Mechanistic Interpretation of Multi-Step Reasoning Capabilities of Language Models**  
  *Yifan Hou, Jiaoda Li, Yu Fei, Alessandro Stolfo, Wangchunshu Zhou, Guangtao Zeng, Antoine Bosselut, Mrinmaya Sachan*. [[pdf](https://arxiv.org/pdf/2310.14491)], 2023.10. ![](https://img.shields.io/badge/EMNLP2023-orange)
- **A Mechanistic Analysis of a Transformer Trained on a Symbolic Multi-Step Reasoning Task**  
  *Jannik Brinkmann, Abhay Sheshadri, Victor Levoso, Paul Swoboda, Christian Bartelt*. [[pdf](https://arxiv.org/pdf/2402.11917)], 2024.02. ![](https://img.shields.io/badge/ACL2024Findings-orange)
- **Do Large Language Models Latently Perform Multi-Hop Reasoning?**  
  *Sohee Yang, Elena Gribovskaya, Nora Kassner, Mor Geva, Sebastian Riedel*. [[pdf](https://arxiv.org/pdf/2402.16837)], 2024.02. ![](https://img.shields.io/badge/ACL2024-orange)
- **Understanding and Patching Compositional Reasoning in LLMs**  
  *Zhaoyi Li, Gangwei Jiang, Hong Xie, Linqi Song, Defu Lian, Ying Wei*. [[pdf](https://arxiv.org/pdf/2402.14328)], 2024.02. ![](https://img.shields.io/badge/ACL2024Findings-orange) ![](https://img.shields.io/badge/CREME-blue)
- **Distributional reasoning in LLMs: Parallel reasoning processes in multi-hop reasoning**  
  *Yuval Shalev, Amir Feder, Ariel Goldstein*. [[pdf](https://arxiv.org/abs/2406.13858)], 2024.06. ![](https://img.shields.io/badge/Arxiv-orange)
- **Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to the Edge of Generalization**  
  *Boshi Wang, Xiang Yue, Yu Su, Huan Sun*. [[pdf](https://arxiv.org/pdf/2405.15071)], 2024.05. ![](https://img.shields.io/badge/Arxiv-orange)
- **Can Language Models Learn to Skip Steps?**  
  *Tengxiao Liu, Qipeng Guo, Xiangkun Hu, Cheng Jiayang, Yue Zhang, Xipeng Qiu, Zheng Zhang*. [[pdf](https://arxiv.org/pdf/2411.01855)], [[code](https://github.com/tengxiaoliu/LM_skip)], 2024.09. ![](https://img.shields.io/badge/NIPS2024-orange)
- **Think-to-Talk or Talk-to-Think? When LLMs Come Up with an Answer in Multi-Step Reasoning**  
  *Keito Kudo, Yoichi Aoki, Tatsuki Kuribayashi, Shusaku Sone, Masaya Taniguchi, Ana Brassard, Keisuke Sakaguchi, Kentaro Inui*. [[pdf](https://arxiv.org/pdf/2412.01113)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange)
- **Do LLMs Really Think Step-by-step In Implicit Reasoning?**  
  *Yijiong Yu*. [[pdf](https://arxiv.org/pdf/2411.15862)], [[code](https://github.com/yuyijiong/if_step_by_step_implicit_CoT)], 2024.11. ![](https://img.shields.io/badge/Arxiv-orange)
- **Implicit Reasoning in Transformers is Reasoning through Shortcuts**  
  *Tianhe Lin, Jian Xie, Siyu Yuan, Deqing Yang*. [[pdf](https://arxiv.org/pdf/2503.07604)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange)
- **Uncovering Latent Chain of Thought Vectors in Language Models**  
  *Jason Zhang, Scott Viteri*. [[pdf](https://arxiv.org/pdf/2409.14026)], 2024.09. ![](https://img.shields.io/badge/ICLR2025Workshop-orange)
- **Latent Space Chain-of-Embedding Enables Output-free LLM Self-Evaluation**  
  *Yiming Wang, Pei Zhang, Baosong Yang, Derek F. Wong, Rui Wang*. [[pdf](https://arxiv.org/pdf/2409.14026)], 2024.10. ![](https://img.shields.io/badge/ICLR2025-orange) ![](https://img.shields.io/badge/CoE-blue) 
- **Internal Chain-of-Thought: Empirical Evidence for Layer-wise Subtask Scheduling in LLMs**  
  *Zhipeng Yang, Junzhuo Li, Siyu Xia, Xuming Hu*. [[pdf](https://arxiv.org/pdf/2505.14530)], [[code](https://github.com/yzp11/Internal-Chain-of-Thought)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) 
- **To CoT or To Loop? A Formal Comparison Between Chain-of-Thought and Looped Transformers**  
  *Kevin Xu, Issei Sato*. [[pdf](https://arxiv.org/pdf/2505.19245)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) 
- **Reasoning by Superposition: A Theoretical Perspective on Chain of Continuous Thought**  
  *Hanlin Zhu, Shibo Hao, Zhiting Hu, Jiantao Jiao, Stuart Russell, Yuandong Tian*. [[pdf](https://arxiv.org/pdf/2505.12514)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange)
- **Continuous Chain of Thought Enables Parallel Exploration and Reasoning**  
  *Halil Alperen Gozeten, M. Emrullah Ildiz, Xuechen Zhang, Hrayr Harutyunyan, Ankit Singh Rawat, Samet Oymak*. [[pdf](https://www.arxiv.org/pdf/2505.23648)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CoT2-blue)
- **Do Language Models Use Their Depth Efficiently?**  
  *Róbert Csordás, Christopher D. Manning, Christopher Potts*. [[pdf](https://arxiv.org/pdf/2505.13898)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange)
- **Language models can learn implicit multi-hop reasoning, but only if they have lots of training data**  
  *Yuekun Yao, Yupei Du, Dawei Zhu, Michael Hahn, Alexander Koller*. [[pdf](https://arxiv.org/pdf/2505.17923)], 2025.05. ![](https://img.shields.io/badge/EMNLP2025-orange)
- **Latent Chain-of-Thought? Decoding the Depth-Recurrent Transformer**  
  *Wenquan Lu, Yuechuan Yang, Kyle Lee, Yanshu Li, Enqi Liu*. [[pdf](https://arxiv.org/pdf/2507.02199)], 2025.07. ![](https://img.shields.io/badge/Arxiv-orange)
- **LLMs Have a Heart of Stone: Demystifying the Soft Thinking Ability of Large Reasoning Models**  
  *Chünhung Wu, Jinliang Lu, Zixuan Ren, Gangqiang Hu, Zhi Wu, Dai Dai, Hua Wu*. [[pdf](https://arxiv.org/pdf/2508.03440)], 2025.08. ![](https://img.shields.io/badge/Arxiv-orange)
- **A Formal Comparison Between Chain-of-Thought and Latent Thought**  
  *Kevin Xu, Issei Sato*. [[pdf](https://arxiv.org/pdf/2509.25239)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange)
- **Emergence of Superposition: Unveiling the Training Dynamics of Chain of Continuous Thought**  
  *Hanlin Zhu, Shibo Hao, Zhiting Hu, Jiantao Jiao, Stuart Russell, Yuandong Tian*. [[pdf](https://arxiv.org/pdf/2509.23365)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange)
- **Hierarchical Reasoning Models: Perspectives and Misconceptions**  
  *Renee Ge, Qianli Liao, Tomaso Poggio*. [[pdf](https://arxiv.org/pdf/2510.00355v2)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange)
- **Scratchpad Thinking: Alternation Between Storage and Computation in Latent Reasoning Models**  
  *Sayam Goyal, Brad Peters, María Emilia Granda, Akshath Vijayakumar Narmadha, Dharunish Yugeswardeenoo, Callum Stuart McDougall, Sean O'Brien, Ashwinee Panda, Kevin Zhu, Cole Blondin*. [[pdf](https://openreview.net/pdf?id=EV30qkZXrR)], [[code](https://github.com/sayam-goyal/Scratchpad-Thinking)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange)
- **Interpreting the Latent Structure of Operator Precedence in Language Models**  
  *Dharunish Yugeswardeenoo, Harshil Nukala, Cole Blondin, Sean O Brien, Vasu Sharma, Kevin Zhu*. [[pdf](http://arxiv.org/pdf/2510.13908)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange)
- **Do Latent Tokens Think? A Causal and Adversarial Analysis of Chain-of-Continuous-Thought**  
  *Yuyi Zhang, Boyu Tang, Tianjie Ju, Sufeng Duan, Gongshen Liu*. [[pdf](https://www.arxiv.org/pdf/2512.21711)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)
- **Layer-Order Inversion: Rethinking Latent Multi-Hop Reasoning in Large Language Models**  
  *Yuyi Zhang, Boyu Tang, Tianjie Ju, Sufeng Duan, Gongshen Liu*. [[pdf](https://arxiv.org/pdf/2601.03542)], [[code](https://github.com/laquabe/Layer-Order-Inversion)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)
- **Large Reasoning Models Are (Not Yet) Multilingual Latent Reasoners**  
  *Yihong Liu, Raoyuan Zhao, Hinrich Schütze, Michael A. Hedderich*. [[pdf](https://arxiv.org/pdf/2601.02996)], [[code](https://github.com/cisnlp/multilingual-latent-reasoner)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)
- **Are Your Reasoning Models Reasoning or Guessing? A Mechanistic Analysis of Hierarchical Reasoning Models**  
  *Zirui Ren, Ziming Liu*. [[pdf](https://arxiv.org/pdf/2601.10679)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)
- **Do Latent-CoT Models Think Step-by-Step? A Mechanistic Study on Sequential Reasoning Tasks**  
  *Jia Liang, Liangming Pan*. [[pdf](https://arxiv.org/pdf/2602.00449)], [[code](https://github.com/jialiang19/latent-cot-thinking)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)
- **Capabilities and Fundamental Limits of Latent Chain-of-Thought**  
  *Jiaxuan Zou, Yaozhong Xiong, Yong Liu*. [[pdf](https://arxiv.org/pdf/2602.01148)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)
- **Beyond What Seems Necessary: Hidden Gains from Scaling Training-Time Reasoning Length under Outcome Supervision**  
  *Yihao Xue, Allan Zhang, Jianhao Huang, Amit Sahai, Baharan Mirzasoleiman*. [[pdf](https://arxiv.org/pdf/2602.00927)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)
- **Imagination Helps Visual Reasoning, But Not Yet in Latent Space**  
  *You Li, Chi Chen, Yanghao Li, Fanhu Zeng, Kaiyu Huang, Jinan Xu, Maosong Sun*. [[pdf](https://arxiv.org/pdf/2602.22766)], [[code](https://github.com/AI9Stars/CapImagine)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CapImagine-blue)

### Applications and Future Directions

- **Efficient Reasoning with Hidden Thinking**  
  *Xuan Shen, Yizhou Wang, Xiangxi Shi, Yanzhi Wang, Pu Zhao, Jiuxiang Gu*. [[pdf](https://arxiv.org/pdf/2501.19201)], [[code](https://github.com/shawnricecake/Heima)], 2025.01. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Heima-blue)
  
- **Learning More Effective Representations for Dense Retrieval through Deliberate Thinking Before Search**  
  *Yifan Ji, Zhipeng Xu, Zhenghao Liu, Yukun Yan, Shi Yu, Yishan Li, Zhiyuan Liu, Yu Gu, Ge Yu, Maosong Sun*. [[pdf](https://arxiv.org/pdf/2502.12974)], [[code](https://github.com/OpenBMB/DEBATER)], 2025.02. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/DEBATER-blue)
  
- **Think Before Recommend: Unleashing the Latent Reasoning Power for Sequential Recommendation**  
  *Jiakai Tang, Sunhao Dai, Teng Shi, Jun Xu, Xu Chen, Wen Chen, Wu Jian, Yuning Jiang*. [[pdf](https://arxiv.org/pdf/2503.22675)], [[code](https://github.com/TangJiakai/ReaRec)], 2025.03. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/ReaRec-blue)
  
- **Enhancing Non-Core Language Instruction-Following in Speech LLMs via Semi-Implicit Cross-Lingual CoT Reasoning**
  *Hongfei Xue, Yufeng Tang, Hexin Liu, Jun Zhang, Xuelong Geng, Lei Xie*. [[pdf](https://arxiv.org/pdf/2504.20835)], 2025.04. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/XS--CoTs-blue)
  
- **Diffusion of Thoughts: Chain-of-Thought Reasoning in Diffusion Language Models**  
  *Jiacheng Ye, Shansan Gong, Liheng Chen, Lin Zheng, Jiahui Gao, Han Shi, Chuan Wu, Xin Jiang, Zhenguo Li, Wei Bi, Lingpeng Kong*. [[pdf](https://arxiv.org/pdf/2402.07754)], 2024.02. ![](https://img.shields.io/badge/NIPS2024-orange) ![](https://img.shields.io/badge/DoT-blue)
  
- **Reinforcing the Diffusion Chain of Lateral Thought with Diffusion Language Models**  
  *Zemin Huang, Zhiyang Chen, Zijun Wang, Tiancheng Li, Guo-Jun Qi*. [[pdf](https://arxiv.org/pdf/2505.10446)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/DCoLT-blue)
  
- **Multimodal Latent Language Modeling with Next-Token Diffusion**  
  *Yutao Sun, Hangbo Bao, Wenhui Wang, Zhiliang Peng, Li Dong, Shaohan Huang, Jianyong Wang, Furu Wei*. [[pdf](https://arxiv.org/pdf/2412.08635)], 2024.12. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LatentLM-blue)
  
- **SEAL: Steerable Reasoning Calibration of Large Language Models for Free**  
  *Runjin Chen, Zhenyu Zhang, Junyuan Hong, Souvik Kundu, Zhangyang Wang*. [[pdf](https://arxiv.org/pdf/2504.07986)], [[code](https://github.com/VITA-Group/SEAL)], 2025.04. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Training_free-lightgray)
  
- **SSR: Enhancing Depth Perception in Vision-Language Models via Rationale-Guided Spatial Reasoning**  
  *Yang Liu, Ming Ma, Xiaomin Yu, Pengxiang Ding, Han Zhao, Mingyang Sun, Siteng Huang, Donglin Wang*. [[pdf](https://arxiv.org/pdf/2505.12448)], [[code](https://yliu-cs.github.io/SSR/)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/SSR-blue) 
  
- **Beyond Chains of Thought: Benchmarking Latent-Space Reasoning Abilities in Large Language Models**  
  *Thilo Hagendorff, Sarah Fabi*. [[pdf](https://arxiv.org/pdf/2504.10615)], 2025.04. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/benchmark-lightgray)
  
- **Machine Mental Imagery: Empower Multimodal Reasoning with Latent Visual Tokens**  
  *Zeyuan Yang, Xueyang Yu, Delin Chen, Maohao Shen, Chuang Gan*. [[pdf](https://arxiv.org/pdf/2506.17218)], [[code](https://github.com/UMass-Embodied-AGI/Mirage)], 2025.06. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Mirage-blue)
  
- **Bridging Search and Recommendation through Latent Cross Reasoning**  
  *Teng Shi, Weicong Qin, Weijie Yu, Xiao Zhang, Ming He, Jianping Fan, Jun Xu*. [[pdf](https://arxiv.org/pdf/2508.04152)], 2025.08. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LCR--SER-blue)
  
- **LARES: Latent Reasoning for Sequential Recommendation**  
  *Enze Liu, Bowen Zheng, Xiaolei Wang, Wayne Xin Zhao, Jinpeng Wang, Sheng Chen, Ji-Rong Wen*. [[pdf](https://arxiv.org/pdf/2505.16865)], 2025.06. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LARES-blue)
  
- **Reinforced Latent Reasoning for LLM-based Recommendation**  
  *Yang Zhang, Wenxin Xu, Xiaoyan Zhao, Wenjie Wang, Fuli Feng, Xiangnan He, Tat-Seng Chua*. [[pdf](https://arxiv.org/pdf/2505.19092)], 2025.05. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LatentR3-blue) 
  
- **Multimodal Chain of Continuous Thought for Latent-Space Reasoning in Vision-Language Models**  
  *Tan-Hanh Pham, Chris Ngo*. [[pdf](https://arxiv.org/pdf/2508.12587)], 2025.08. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/MCOUT-blue)
  
- **Latent Visual Reasoning**  
  *Bangzheng Li, Ximeng Sun, Jiang Liu, Ze Wang, Jialian Wu, Xiaodong Yu, Hao Chen, Emad Barsoum, Muhao Chen, Zicheng Liu*. [[pdf](https://arxiv.org/pdf/2509.24251)], 2025.09. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LVR-blue)
  
- **Reasoning in the Dark: Interleaved Vision-Text Reasoning in Latent Space**  
  *Chao Chen, Zhixin Ma, Yongqi Li, Yupeng Hu, Yinwei Wei, Wenjie Li, Liqiang Nie*. [[pdf](https://arxiv.org/pdf/2510.12603)], [[code](https://github.com/FYYDCC/IVT-LR)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LVT--LR-blue)
  
- **Latent Chain-of-Thought for Visual Reasoning**  
  *Guohao Sun, Hang Hua, Jian Wang, Jiebo Luo, Sohail Dianat, Majid Rabbani, Raghuveer Rao, Zhiqiang Tao*. [[pdf](https://arxiv.org/pdf/2510.23925)], [[code](https://github.com/heliossun/LaCoT)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/LaCoT--LR-blue)
  
- **Latent Sketchpad : Sketching Visual Thoughts to Elicit Multimodal Reasoning in MLLMs**  
  *Huanyu Zhang, Wenshan Wu, Chengzu Li, Ning Shang, Yan Xia, Yangyu Huang, Yifan Zhang, Li Dong, Zhang Zhang, Liang Wang, Tieniu Tan, Furu Wei*. [[pdf](https://arxiv.org/pdf/2510.24514)], [[code](https://latent-sketchpad.github.io/)], 2025.10. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/Latent Sketchpad-blue)
  
- **CoCoVa: Chain of Continuous Vision-Language Thought for Latent Space Reasoning**  
  *Jizheng Ma, Xiaofei Zhou, Yanlong Song, Han Yan*. [[pdf](https://arxiv.org/pdf/2511.02360)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange) ![](https://img.shields.io/badge/CoCoVa-blue)
  
- **Enabling Agents to Communicate Entirely in Latent Space**  
  *Zhuoyun Du, Runze Wang, Huiyu Bai, Zouying Cao, Xiaoyong Zhu, Bo Zheng, Wei Chen, Haochao Ying*. [[pdf](https://arxiv.org/pdf/2511.09149)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/Interlat-blue)
  
- **Monet: Reasoning in Latent Visual Space Beyond Images and Language**  
  *Qixun Wang, Yang Shi, Yifei Wang, Yuanxing Zhang, Pengfei Wan, Kun Gai, Xianghua Ying, Yisen Wang*. [[pdf](https://arxiv.org/pdf/2511.21395)], [[code](https://github.com/NOVAglow646/Monet)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/Monet-blue)
  
- **Latent Collaboration in Multi-Agent Systems**  
  *Jiaru Zou, Xiyuan Yang, Ruizhong Qiu, Gaotang Li, Katherine Tieu, Pan Lu, Ke Shen, Hanghang Tong, Yejin Choi, Jingrui He, James Zou, Mengdi Wang, Ling Yang*. [[pdf](https://arxiv.org/pdf/2511.21395)], [[code](https://github.com/Gen-Verse/LatentMAS)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LatentMAS-blue)
  
- **Chain-of-Visual-Thought: Teaching VLMs to See and Think Better with Continuous Visual Tokens**  
  *Yiming Qin, Bomin Wei, Jiaxin Ge, Konstantinos Kallidromitis, Stephanie Fu, Trevor Darrell, Xudong Wang*. [[pdf](https://arxiv.org/pdf/2511.19418)], [[code](https://wakalsprojectpage.github.io/comt-website/)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/CoVT-blue)
  
- **VisMem: Latent Vision Memory Unlocks Potential of Vision-Language Models**  
  *Xinlei Yu, Chengming Xu, Guibin Zhang, Zhangquan Chen, Yudong Zhang, Yongbo He, Peng-Tao Jiang, Jiangning Zhang, Xiaobin Hu, Shuicheng Yan*. [[pdf](https://arxiv.org/pdf/2511.11007)], [[code](https://github.com/YU-deep/VisMem)], 2025.11. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/VisMem-blue)
  
- **Latent Chain-of-Thought World Modeling for End-to-End Driving**  
  *Shuhan Tan, Kashyap Chitta, Yuxiao Chen, Ran Tian, Yurong You, Yan Wang, Wenjie Luo, Yulong Cao, Philipp Krahenbuhl, Marco Pavone, Boris Ivanovic*. [[pdf](https://arxiv.org/pdf/2512.10226)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LCDrive-blue)
  
- **Reasoning Within the Mind: Dynamic Multimodal Interleaving in Latent Space**  
  *Chengzhi Liu, Yuzhe Yang, Yue Fan, Qingyue Wei, Sheng Liu, Xin Eric Wang*. [[pdf](https://arxiv.org/pdf/2512.12623)], [[code](https://mllm-dmlr.github.io/)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/DMLR-blue)
  
- **Interleaved Latent Visual Reasoning with Selective Perceptual Modeling**  
  *Shuai Dong, Siyuan Wang, Xingyu Liu, Zhongyu Wei*. [[pdf](https://arxiv.org/pdf/2512.05665)], [[code](https://github.com/XD111ds/ILVR)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/ICVR-blue)
  
- **Mull-Tokens: Modality-Agnostic Latent Thinking**  
  *Arijit Ray, Ahmed Abdelkader, Chengzhi Mao, Bryan A. Plummer, Kate Saenko, Ranjay Krishna, Leonidas Guibas, Wen-Sheng Chu*. [[pdf](https://arxiv.org/pdf/2512.10941)], [[code](http://arijitray.com/multimodal_thinking/)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/Mull_Tokens-blue)
  
- **VL-JEPA: Joint Embedding Predictive Architecture for Vision-language**  
  *Delong Chen, Mustafa Shukor, Theo Moutakanni, Willy Chung, Jade Yu, Tejaswi Kasarla, Allen Bolourchi, Yann LeCun, Pascale Fung*. [[pdf](https://arxiv.org/pdf/2512.10942)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/VL--JEPA-blue)
  
- **Sketch-in-Latents: Eliciting Unified Reasoning in MLLMs**  
  *Jintao Tong, Jiaqi Gu, Yujing Lou, Lubin Fan, Yixiong Zou, Yue Wu, Jieping Ye, Ruixuan Li*. [[pdf](https://arxiv.org/pdf/2512.16584)], 2025.12. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/SkiLa-blue)
  
- **Thinking Broad, Acting Fast: Latent Reasoning Distillation from Multi-Perspective Chain-of-Thought for E-Commerce Relevance** 
  *Baopu Qiu, Hao Chen, Yuanrong Wu, Changtong Zan, Chao Wei, Weiru Zhang, Xiaoyi Zeng*. [[pdf](https://arxiv.org/pdf/2601.21611)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LRKD-blue)
  
- **Fast-ThinkAct: Efficient Vision-Language-Action Reasoning via Verbalizable Latent Planning**
  *Chi-Pin Huang, Yunze Man, Zhiding Yu, Min-Hung Chen, Jan Kautz, Yu-Chiang Frank Wang, Fu-En Yang*. [[pdf](https://arxiv.org/pdf/2601.09708)], [[code](https://jasper0314-huang.github.io/fast-thinkact/)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/Fast--ThinkAct-blue)
  
- **Fast-ThinkAct: Efficient Vision-Language-Action Reasoning via Verbalizable Latent Planning**
  *Yubo Wang, Juntian Zhang, Yichen Wu, Yankai Lin, Nils Lukas, Yuhan Liu*. [[pdf](https://arxiv.org/pdf/2601.06803)], [[code](https://github.com/ybb6/laser/tree/main)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/DWAL-blue)
  
- **LaST0: Latent Spatio-Temporal Chain-of-Thought for Robotic Vision-Language-Action Model**
  *Zhuoyang Liu, Jiaming Liu, Hao Chen, Ziyu Guo, Chengkai Hou, Chenyang Gu, Jiale Yu, Xiangju Mi, Renrui Zhang, Zhengping Che, Jian Tang, Pheng-Ann Heng, Shanghang Zhang*. [[pdf](https://arxiv.org/pdf/2601.05248)], [[code](https://sites.google.com/view/last0)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LaST0-blue)
  
- **Reasoning While Recommending: Entropy-Guided Latent Reasoning in Generative Re-ranking Models**
  *Changshuo Zhang*. [[pdf](https://arxiv.org/pdf/2601.13533)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/EGLR-blue)
  
- **Parallel Latent Reasoning for Sequential Recommendation**
  *Jiakai Tang, Xu Chen, Wen Chen, Jian Wu, Yuning Jiang, Bo Zheng*. [[pdf](https://arxiv.org/pdf/2601.03153)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/PLR-blue)
  
- **ReGuLaR: Variational Latent Reasoning Guided by Rendered Chain-of-Thought**
  
  *Fanmeng Wang, Haotian Liu, Guojiang Zhao, Hongteng Xu, Zhifeng Gao*. [[pdf](https://arxiv.org/pdf/2601.23184)], [[code](https://github.com/FanmengWang/ReGuLaR)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/ReGuLaR-blue)

- **LaViT: Aligning Latent Visual Thoughts for Multi-modal Reasoning**

  *Linquan Wu, Tianxiang Jiang, Yifei Dong, Haoyu Yang, Fengji Zhang, Shichaang Meng, Ai Xuan, Linqi Song, Jacky Keung*. [[pdf](https://arxiv.org/pdf/2601.10129)], [[code](https://github.com/Svardfox/LaViT)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LaViT-blue)
  
- **LoopViT: Scaling Visual ARC with Looped Transformers**

  *Wen-Jie Shu, Xuerui Qiu, Rui-Jie Zhu, Harold Haodong Chen, Yexin Liu, Harry Yang*. [[pdf](https://arxiv.org/pdf/2602.02156)], [[code](https://github.com/Svardfox/LaViT)], 2026.01. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LoopViT-blue)
  
- **Latent Reasoning VLA: Latent Thinking and Prediction for Vision-Language-Action Models**

  *Shuanghao Bai, Jing Lyu, Wanqi Zhou, Zhe Li, Dakai Wang, Lei Xing, Xiaoguang Zhao, Pengwei Wang, Zhongyuan Wang, Cheng Chi, Badong Chen, Shanghang Zhang*. [[pdf](https://arxiv.org/pdf/2602.01166)], [[code](https://loveju1y.github.io/Latent-Reasoning-VLA/)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LaRA--VLA-blue)
  
- **Learning Modal-Mixed Chain-of-Thought Reasoning with Latent Embeddings**

  *Yifei Shao, Kun Zhou, Ziming Xu, Mohammad Atif Quamar, Shibo Hao, Zhen Wang, Zhiting Hu, Biwei Huang*. [[pdf](https://arxiv.org/pdf/2602.00574)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)
  
- **Show, Don’t Tell: Morphing Latent Reasoning into Image Generation**

  *Harold Haodong Chen, Xinxiang Yin, Wen-Jie Shu, Hongfei Zhang, Zixin Zhang, Chenfei Liao, Litao Guo, Qifeng Chen, Ying-Cong Chen*. [[pdf](https://arxiv.org/pdf/2602.02227)], [[code](https://github.com/EnVision-Research/LatentMorph)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/LatentMorph-blue)
  
- **Multimodal Latent Reasoning via Hierarchical Visual Cues Injection**

  *Yiming Zhang, Qiangyu Yan, Borui Jiang, Kai Han*. [[pdf](https://arxiv.org/pdf/2602.05359)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/HIVE-blue)
  
- **CoLT: Reasoning with Chain of Latent Tool Calls**

  *Fangwei Zhu, Zhifang Sui*. [[pdf](https://arxiv.org/pdf/2602.04246)], 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/CoLT-blue)

- **Vision-aligned Latent Reasoning for Multi-modal Large Language Model**

  *Byungwoo Jeon, Yoonwoo Jeong, Hyunseok Lee, Minsu Cho, Jinwoo Shin*. [[pdf](https://arxiv.org/pdf/2602.04476)], [[code](https://rootyjeon.github.io/valr/)] 2026.02. ![](https://img.shields.io/badge/Arxiv-orange)![](https://img.shields.io/badge/VaLR-blue)

## Resources

For most recent **Efficient Reasoning** research, see [Awesome-Efficient-Reasoning](https://github.com/hemingkx/Awesome-Efficient-Reasoning), and [Awesome-Efficient-Reasoning-Models](https://github.com/fscdc/Awesome-Efficient-Reasoning-Models) [[Paper](https://arxiv.org/pdf/2504.10903)].

[LatentCoT-Horizon](https://github.com/multimodal-art-projection/LatentCoT-Horizon): a list of papers contains a larger scope of latent reasoning.

[awesome-llm-implicit-reasoning](https://github.com/digailab/awesome-llm-implicit-reasoning): a list of papers contains implicit reasoning in LLMs.


## Acknowledgements

If We’ve accidentally missed your papers on the list, please reach out to us, and we’ll make sure to add them as soon as possible!
