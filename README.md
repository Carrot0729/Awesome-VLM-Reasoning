<a name="readme-top"></a>

<p align="center"></p>

<h1 align="center">Awesome VLM Reasoning</h1>

<p align="center">
    <b> A carefully curated collection of papers and resources exploring methods to advance reasoning in Vision-Language Models (VLMs).</b>
</p>

<details>
  <summary>🗂️ Table of Contents</summary>
  <ol>
    <li><a href="#Multi-modality COT Reasoning">Multi-modality COT Reasoning</a></li>
    <li><a href="#Benchmarks">Benchmarks</a></li>
    <li><a href="#Reinforce Learn">Reinforce Learning</a>
      <ul>
        <li><a href="#based-on-dpo">🔤 <em>DPO-based</em> reinforcement learning method</a></li>
        <li><a href="#based-on-ppo">🧠 <em>PPO-based</em> reinforcement learning method</a></li>
        <li><a href="#based-on-rlhf">🤏 <em>RLHF-based</em> reinforcement learning method</a></li>
        <li><a href="#others-rl">🔗 Other reinforcement learning methods</a></li>
      </ul>
    </li>
  </ol>
</details>

## Multi-modality COT Reasoning

### 2024

1. **[Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning](https://arxiv.org/abs/2403.16999)**

    *Hao Shao, Shengju Qian, Han Xiao, Guanglu Song, Zhuofan Zong, Letian Wang, Yu Liu, Hongsheng Li.*

2. **[Multimodal Chain-of-Thought Reasoning in Language Models.](https://arxiv.org/pdf/2302.00923)**

    *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.*

3. **[Visual SKETCHPAD: Sketching as a Visual Chain of Thought for Multimodal Language Models.](https://arxiv.org/abs/2406.09403)**

    *Yushi Hu, Weijia Shi, Xingyu Fu, Dan Roth, Mari Ostendorf, Luke Zettlemoyer, Noah A. Smith, Ranjay Krishna*

4. **[Imagine while Reasoning in Space: Multimodal Visualization-of-Thought.](https://arxiv.org/abs/2501.07542)** 

    *Chengzu Li, Wenshan Wu, Huanyu Zhang, Yan Xia, Shaoguang Mao, Li Dong, Ivan Vulic´, Furu Wei*

### 2025

1. **[Satori: Reinforcement Learning with Chain-of-Action-Thought Enhances LLM Reasoning via Autoregressive Search.](https://arxiv.org/abs/2502.02508)**

    *Maohao Shen, Guangtao Zeng, Zhenting Qi, Zhang-Wei Hong, Zhenfang Chen, Wei Lu, Gregory Wornell, Subhro Das, David Cox, Chuang Gan.*


### 🔗Others

1. **[AlphaMaze: Enhancing Large Language Models' Spatial Intelligence via GRPO.](https://arxiv.org/abs/2502.14669)**

    *Alan Dao (Gia Tuan Dao), Dinh Bach Vu1.*

2. **[VOILA: EVALUATION OF MLLMS FOR PERCEPTUAL UNDERSTANDING AND ANALOGICAL REASONING.](https://arxiv.org/abs/2503.00043)** 

    *Nilay Yilmaz, Maitreya Patel, Yiran Lawrence Luo, Tejas Gokhale, Chitta Baral, Suren Jayasuriya, Yezhou Yang*

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## Benchmarks
1. **[MindGYM: Enhancing Vision-Language Models via Synthetic Self-Challenging Questions.](https://arxiv.org/abs/2503.09499)**

    *Zhe Xu, Daoyuan Chen, Zhenqing Ling, Yaliang Li, Ying Shen.*

2. **[MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models.](https://arxiv.org/abs/2502.00698v1)** 

    *Huanqia Cai, Yijun Yang, Winston Hu*

3. **[VERIFY: A Benchmark of Visual Explanation and Reasoning for Investigating Multimodal Reasoning Fidelity.](https://arxiv.org/abs/2503.11557v1)** 

    *Jing Bi, Junjia Guo, Susan Liang, Guangyu Sun, Luchuan Song, Yunlong Tang, Jinxi He, Jiarui Wu, Ali Vosoughi, Chen Chen, Chenliang Xu*

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



## Reinforce Learn
### 🔤Based On DPO
1. **[Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor.](https://arxiv.org/pdf/1801.01290)**

    *Tuomas Haarnoja, Aurick Zhou, Pieter Abbeel, Sergey Levine.*
2. **[Accelerated Preference Optimization for Large Language Model Alignment.](https://arxiv.org/abs/2410.06293v1)**

    *Jiafan He, Huizhuo Yuan, Quanquan Gu.*
3. **[Gradient Imbalance in Direct Preference Optimization.](https://arxiv.org/abs/2502.20847v1)**

    *Qinwei Ma, Jingzhe Shi, Can Jin, Jenq-Neng Hwang, Serge Belongie, Lei Li.*
4. **[MPPO: Multi Pair-wise Preference Optimization for LLMs with Arbitrary Negative Samples.](https://arxiv.org/abs/2412.15244v1)**

    *Shuo Xie, Fangzhi Zhu, Jiahui Wang, Lulu Wen, Wei Dai, Xiaowei Chen, Junxiong Zhu, Kai Zhou, Bo Zheng.*
5. **[Improving Multi-Step Reasoning Abilities of Large Language Models with Direct Advantage Policy Optimization.](https://arxiv.org/abs/2412.18279v1)**

    *Jiacai Liu, Chaojie Wang, Chris Yuhao Liu, Liang Zeng, Rui Yan, Yiwen Sun, Yang Liu, Yahui Zhou.*

### 🧠Based On PPO
1. **[Reward Fine-Tuning Two-Step Diffusion Models via Learning Differentiable Latent-Space Surrogate Reward.](https://arxiv.org/abs/2411.15247v1)**

    *Zhiwei Jia, Yuesong Nan, Huixi Zhao, Gengdai Liu.*
2. **[Can We Generate Images with CoT? Let’s Verify and Reinforce Image Generation Step by Step.](https://arxiv.org/abs/2501.13926)**

    *Ziyu Guo, Renrui Zhang, Chengzhuo Tong, Zhizheng Zhao, Peng Gao, Hongsheng Li, Pheng-Ann Heng.*
3. **[Lean and Mean: Decoupled Value Policy Optimization with Global Value Guidance.](https://arxiv.org/abs/2502.16944v1)**

    *Chenghua Huang, Lu Wang, Fangkai Yang, Pu Zhao, Zhixu Li, Qingwei Lin, Dongmei Zhang, Saravan Rajmohan, Qi Zhang.*
4. **[Q♯: Provably Optimal Distributional RL for LLM Post-Training.](https://arxiv.org/abs/2502.20548v1)**

    *Jin Peng Zhou, Kaiwen Wang, Jonathan Chang4, Zhaolin Gao, Nathan Kallus, Kilian Q. Weinberger, Kianté Brantley, Wen Sun.*
5. **[Enhancing Multi-Step Reasoning Abilities of Language Models through Direct Q-Function Optimization.](https://arxiv.org/abs/2410.09302v2)**

    *Kaixuan Ji, Guanlin Liu, Ning Dai, Qingping Yang, Renjie Zheng, Zheng Wu, Chen Dun, Quanquan Gu, Lin Yan.*

### 🤏Based On RLHF
1. **[RLHS: Mitigating Misalignment in RLHF with Hindsight Simulation.](https://arxiv.org/abs/2503.09499)**

    *Kaiqu Liang, Haimin Hu, Ryan Liu, Thomas L. Griffiths, Jaime Fernández Fisac.*
2. **[Enhancing LLMs for Physics Problem-Solving using Reinforcement Learning with Human-AI Feedback.](https://arxiv.org/abs/2412.06827v1)**

    *Avinash Anand, Kritarth Prasad, Chhavi Kirtani, Ashwin R Nair, Mohit Gupta, Saloni Garg, Anurag Gautam, Snehal Buldeo, Rajiv Ratn Shah.*

### 🔗Others-RL
1. **[Distributionally Robust Optimization.](https://arxiv.org/abs/2411.02549)**

    *Daniel Kuhn, Soroosh Shafiee, Wolfram Wiesemann.*
2. **[Continual SFT Matches Multimodal RLHF with Negative Supervision.](https://arxiv.org/abs/2411.14797v1)**

    *Ke Zhu, Yu Wang, Yanpeng Sun, Qiang Chen, Jiangjiang Liu, Gang Zhang, Jingdong Wang.*
3. **[Fast Best-of-N Decoding via Speculative Rejection.](https://arxiv.org/abs/2410.20290v2)**

    *Hanshi Sun, Momin Haider, Ruiqi Zhang, Huitao Yang, Jiahao Qiu, Ming Yin, Mengdi Wang, Peter L. Bartlett, Andrea Zanette.*

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>
