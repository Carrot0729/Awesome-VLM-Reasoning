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
    <li><a href="#Reinforce-Learn">Reinforce Learning</a>
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

| Title                                                                                                                                                               | Venue |    Date    |                        Code                         |                              Starts                               |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----:|:----------:|:---------------------------------------------------:|:-----------------------------------------------------------------:| 
| [**Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning**](https://arxiv.org/abs/2403.16999) | arXiv | 2024-03-16 |  [GitHub](https://github.com/deepcs233/Visual-CoT)  |  ⭐ ![GitHub Repo stars](https://github.com/deepcs233/Visual-CoT)  |
| [**Multimodal Chain-of-Thought Reasoning in Language Models**](https://arxiv.org/abs/2403.16999)                                                                    | arXiv | 2024-05-20 | [GitHub](https://github.com/amazon-science/mm-cot/) | ⭐ ![GitHub Repo stars](https://github.com/amazon-science/mm-cot/) |
| [**Visual SKETCHPAD: Sketching as a Visual Chain of Thought for Multimodal Language Models**](https://arxiv.org/abs/2406.09403)                                     | arXiv | 2024-06-09 |    [GitHub](https://visualsketchpad.github.io/)     |    ⭐ ![GitHub Repo stars](https://visualsketchpad.github.io/)     |
| [**Imagine while Reasoning in Space: Multimodal Visualization-of-Thought **](https://arxiv.org/abs/2501.07542)                                                      | arXiv | 2025-01-07 |                          -                          |                                 -                                 |
| [**Satori: Reinforcement Learning with Chain-of-Action-Thought Enhances LLM Reasoning via Autoregressive Search**](https://arxiv.org/abs/2502.02508)                | arXiv | 2025-02-02 |    [GitHub](https://satori-reasoning.github.io/)    |    ⭐ ![GitHub Repo stars](https://satori-reasoning.github.io/)    |
| [**AlphaMaze: Enhancing Large Language Models' Spatial Intelligence via GRPO **](https://arxiv.org/abs/2502.14669)                                                  | arXiv | 2025-02-14 |                          -                          |                                 -                                 |
| [**VOILA: EVALUATION OF MLLMS FOR PERCEPTUAL UNDERSTANDING AND ANALOGICAL REASONING**](https://arxiv.org/abs/2503.00043)                                            | arXiv | 2025-03-04 |     [GitHub](https://github.com/nlylmz/Voila/)      |     ⭐ ![GitHub Repo stars](https://github.com/nlylmz/Voila/)      |

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## Benchmarks

| Title                                                                                                                                             | Venue |    Date    |                               Code                                |
|:--------------------------------------------------------------------------------------------------------------------------------------------------|:-----:|:----------:|:-----------------------------------------------------------------:|
| [**MindGYM: Enhancing Vision-Language Models via Synthetic Self-Challenging Questions**](https://arxiv.org/abs/2503.09499)                        | arXiv | 2025-03-12 | [GitHub]( https://github.com/modelscope/datajuicer/tree/MindGYM/) |
| [**MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models**](https://arxiv.org/abs/2502.00698v1)                           | arXiv | 2025-02-02 |       [Homepage](https://acechq.github.io/MMIQ-benchmark/)        |
| [**VERIFY: A Benchmark of Visual Explanation and Reasoning for Investigating Multimodal Reasoning Fidelity**](https://arxiv.org/abs/2503.11557v1) | arXiv | 2025-03-14 |           [ProjectPage](https://verify-eqh.pages.dev/)            |

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## Reinforce Learn

### 🔤Based On DPO

| Title                                                                                                                                                 | Venue |    Date    | Code |
|:------------------------------------------------------------------------------------------------------------------------------------------------------|:-----:|:----------:|:----:|
| [**Accelerated Preference Optimization for Large Language Model Alignment**](https://arxiv.org/abs/2410.06293v1)                                      | arXiv | 2024-10-08 |  -   |
| [**MPPO: Multi Pair-wise Preference Optimization for LLMs with Arbitrary Negative Samples**](https://arxiv.org/abs/2412.15244v1)                      | arXiv | 2024-12-13 |  -   |
| [**Improving Multi-Step Reasoning Abilities of Large Language Models with Direct Advantage Policy Optimization**](https://arxiv.org/abs/2412.18279v1) | arXiv | 2024-12-24 |  -   |
| [**Gradient Imbalance in Direct Preference Optimization**](https://arxiv.org/abs/2502.20847v1)                                                        | arXiv | 2025-02-28 |  -   |

### 🧠Based On PPO

| Title                                                                                                                                            | Venue |    Date    |                            Code                             |
|:-------------------------------------------------------------------------------------------------------------------------------------------------|:-----:|:----------:|:-----------------------------------------------------------:|
| [**Reward Fine-Tuning Two-Step Diffusion Models via Learning Differentiable Latent-Space Surrogate Reward**](https://arxiv.org/abs/2411.15247v1) | arXiv | 2024-11-22 |                              -                              |
| [**Can We Generate Images with CoT? Let’s Verify and Reinforce Image Generation Step by Step**](https://arxiv.org/abs/2501.13926)                | arXiv | 2025-01-23 | [GitHub](https://github.com/ZiyuGuo99/Image-Generation-CoT) |
| [**Enhancing Multi-Step Reasoning Abilities of Language Models through Direct Q-Function Optimization**](https://arxiv.org/abs/2410.09302v2)     | arXiv | 2025-02-11 |                              -                              |
| [**Lean and Mean: Decoupled Value Policy Optimization with Global Value Guidance**](https://arxiv.org/abs/2502.16944v1)                          | arXiv | 2025-02-24 |                              -                              |
| [**Q♯: Provably Optimal Distributional RL for LLM Post-Training**](https://arxiv.org/abs/2502.20548v1)                                           | arXiv | 2025-02-27 |         [GitHub](https://github.com/jinpz/q_sharp)          |

### 🤏Based On RLHF

| Title                                                                                                                                    | Venue |    Date    | Code |
|:-----------------------------------------------------------------------------------------------------------------------------------------|:-----:|:----------:|:----:|
| [**Enhancing LLMs for Physics Problem-Solving using Reinforcement Learning with Human-AI Feedback**](https://arxiv.org/abs/2412.06827v1) | arXiv | 2024-12-06 |  -   |
| [**RLHS: Mitigating Misalignment in RLHF with Hindsight Simulation**](https://arxiv.org/abs/2503.09499)                                  | arXiv | 2025-02-10 |  -   |

### 🔗Others-RL

| Title                                                                                                     | Venue |    Date    |                              Code                              |
|:----------------------------------------------------------------------------------------------------------|:-----:|:----------:|:--------------------------------------------------------------:|
| [**Fast Best-of-N Decoding via Speculative Rejection**](https://arxiv.org/abs/2410.20290v2)               | arXiv | 2024-10-31 | [GitHub](https://github.com/Zanette-Labs/SpeculativeRejection) |
| [**Distributionally Robust Optimization**](https://arxiv.org/abs/2411.02549)                              | arXiv | 2024-11-04 |                               -                                |
| [**Continual SFT Matches Multimodal RLHF with Negative Supervision**](https://arxiv.org/abs/2411.14797v1) | arXiv | 2024-11-22 |                               -                                |

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>
