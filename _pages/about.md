---
permalink: /
title: "Hello there, I am Zhipeng!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a seasoned scientist & engineer working in the field of Machine Learning Systems with a primary focus on the optimization of large-scale distributed training and inference systems for foundation models and large language models (LLMs). Distinct from many other ML Systems researchers, my work also extends into core modeling research. My core modeling research mainly focuses on efficient AI—particularly LLM compression, knowledge distillation, LLM post-training methodologies, Agentic Reinforcement Learning and Vision-Language Models (VLM). Some of the research findings are published in *EMNLP, ICCV, ECCV, WACV, ICML and NeurIPS etc.* 

**Some of the representative ML Systems that I was involved in the development phase** including [DeepSpeed](https://github.com/deepspeedai/DeepSpeed), one of the most popular OSS LLM distributed training library (code maintainer and TSC Committer); [fmchisel](https://github.com/linkedin/fmchisel), the state-of-the-art Foundation Models Optimization research library (e.g. knowledge distillation,compression and quantization etc); and [Liger Kernel](https://github.com/linkedin/Liger-Kernel) (Kudos to Byron Hsu and Yun Dai et al for leading the work). 

In the corporate world, I am Senior Manager/Senior Staff Research Scientist leading the Foundational AI algorithms organization at LinkedIn (subsidary of Microsoft). Previously I worked at AWS AI organization at Amazon, where I was leading the SageMaker Applied Science Team contributing to LLM Inference/Distributed Training and Evaluation Services. I was also the Tech Lead Manager/Staff Software Engineer at Google[X]/Google Research, where I was building up the machine learning team for the Moonshot project [Chorus](https://x.company/projects/chorus/) and engaged in AIDA project building [coding agent using LLM](https://x.company/projects/aida/) (now part of Gemini). I was also involved in PaLM model development work across Alphabet. Before that I was Staff Research Scientist at Apple, where I lead the development of ML Algorithms for [Sleep Apnea Detection on Apple Watch](https://www.apple.com/health/pdf/sleep-apnea/Sleep_Apnea_Notifications_on_Apple_Watch_September_2024.pdf). 

## News
- We won **Best Paper Award** in [Visual Art, Generative AI, and the Legal/Ethical Dilemma Workshop @ WACV 2026](https://sites.google.com/view/vagaled-wacv2026/) for our paper titled *"EZBlender: Efficient 3D Editing with Plan-and-React Agent"*!

<!--# Selected Experiences-->
## Talks and Tutorials 
- **[Building Efficient Large-Scale Model Systems with DeepSpeed: From Open-Source Foundations to Emerging Research](https://supercomputing-system-ai-lab.github.io/events/asplos2026-llm-tutorial/index.html)**  
  Olatunji Ruwase, Minjia Zhang, Masahiro Tanaka, Zhipeng Wang, **ASPLOS 2026 Tutorial**

- **Ray x DeepSpeed Meetup: AI at Scale**  
  Olatunji Ruwase, Masahiro Tanaka, Vinay Sridhar and Zhipeng Wang, [slides](https://docs.google.com/presentation/d/1eM3mY6oW9GYkRy1Xz0iOnbbEr5T1t0JJXOM5BKtR-Ks/edit?slide=id.g38615d6b4c2_0_87#slide=id.g38615d6b4c2_0_87)  

<style>
.pub-entry {
  display: flex;
  margin-bottom: 25px;
  align-items: flex-start;
}
.pub-img {
  flex-shrink: 0;
  width: 180px;
  margin-right: 20px;
}
.pub-img img {
  width: 180px;
  border-radius: 4px;
  object-fit: cover;
}
.pub-text {
  flex: 1;
}
.pub-title {
  font-weight: bold;
  margin-bottom: 4px;
}
.pub-authors {
  color: #555;
  font-size: 0.92em;
  margin-bottom: 2px;
}
.pub-venue {
  font-size: 0.92em;
  color: #333;
  margin-bottom: 4px;
}
.pub-highlight {
  color: #691616;
  font-weight: 600;
  font-size: 0.9em;
}
.pub-links {
  font-size: 0.9em;
  margin-top: 4px;
}
.pub-links a {
  margin-right: 8px;
}
@media (max-width: 600px) {
  .pub-entry { flex-direction: column; }
  .pub-img { width: 100%; margin-right: 0; margin-bottom: 10px; }
  .pub-img img { width: 100%; }
}
</style>

## Selected Recent Publications

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/emnlp2025_scaling_down.png" alt="Scaling Down, Serving Fast">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://aclanthology.org/2025.emnlp-industry.119.pdf">Scaling Down, Serving Fast: Compressing and Deploying Efficient LLMs for Recommendation Systems</a></div>
    <div class="pub-authors">Kayhan Behdin, Ata Fatahi, Qingquan Song, Yun Dai, Aman Gupta, <strong>Zhipeng Wang</strong> et al.</div>
    <div class="pub-venue">EMNLP 2025</div>
    <div class="pub-highlight">Oral Presentation</div>
    <div class="pub-links">[<a href="https://aclanthology.org/2025.emnlp-industry.119.pdf">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/wacv2026_evtp_ivs.png" alt="EVTP-IVS">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2508.11886">EVTP-IVS: Effective Visual Token Pruning For Unifying Instruction Visual Segmentation In Multi-Modal Large Language Models</a></div>
    <div class="pub-authors">Wenhui Zhu*, Xiwen Chen*, <strong>Zhipeng Wang</strong>*#, Shao Tang, Sayan Ghosh, Xuanzhao Dong, Rajat Koner, Yalin Wang</div>
    <div class="pub-venue">WACV 2026 (* equal contribution, # corresponding author)</div>
    <div class="pub-links">[<a href="https://arxiv.org/abs/2508.11886">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/icml2025_liger_kernel.png" alt="Liger Kernel">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://openreview.net/forum?id=36SjAIT42G">Liger-Kernel: Efficient Triton Kernels for LLM Training</a></div>
    <div class="pub-authors">Pin-Lun Hsu, Yun Dai, Vignesh Kothapalli, Qingquan Song, Shao Tang, Siyu Zhu, Steven Shimizu, Shivam Sahni, Haowen Ning, Yanning Chen, <strong>Zhipeng Wang</strong></div>
    <div class="pub-venue">ICML 2025 CODE Workshop</div>
    <div class="pub-links">[<a href="https://openreview.net/forum?id=36SjAIT42G">Paper</a>] [<a href="https://github.com/linkedin/Liger-Kernel">Code</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/iccv2025_local2global.png" alt="Local2Global">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://openaccess.thecvf.com/content/ICCV2025W/LSVOS/papers/Koner_Local2Global_query_Alignment_for_Video_Instance_Segmentation_ICCVW_2025_paper.pdf">Local2Global query Alignment for Video Instance Segmentation</a></div>
    <div class="pub-authors">Rajat Koner, <strong>Zhipeng Wang</strong>, Srinivas Parthasarathy, Chinghang Chen</div>
    <div class="pub-venue">ICCV 2025</div>
    <div class="pub-links">[<a href="https://openaccess.thecvf.com/content/ICCV2025W/LSVOS/papers/Koner_Local2Global_query_Alignment_for_Video_Instance_Segmentation_ICCVW_2025_paper.pdf">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/iclr2026_rac.png" alt="Reasoning-Aware Compression">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://openreview.net/forum?id=tyGfwG6xTh">Reasoning Models Can be Accurately Pruned Via Chain-of-Thought Reconstruction</a></div>
    <div class="pub-authors">Ryan Lucas, Kayhan Behdin, <strong>Zhipeng Wang</strong>, Qingquan Song, Shao Tang, Rahul Mazumder</div>
    <div class="pub-venue">ICLR 2026</div>
    <div class="pub-links">[<a href="https://openreview.net/forum?id=tyGfwG6xTh">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/cvpr2026_llada_medv.png" alt="LLaDA-MedV">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2508.01617">LLaDA-MedV: Exploring Large Language Diffusion Models for Biomedical Image Understanding</a></div>
    <div class="pub-authors">Xuanzhao Dong, Wenhui Zhu, Xiwen Chen, <strong>Zhipeng Wang</strong>, Peijie Qiu, Shao Tang, Xin Li, Yalin Wang</div>
    <div class="pub-venue">CVPR 2026</div>
    <div class="pub-links">[<a href="https://arxiv.org/abs/2508.01617">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/cvpr2026_otprune.png" alt="OTPrune">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2602.20205">OTPrune: Distribution-Aligned Visual Token Pruning via Optimal Transport</a></div>
    <div class="pub-authors">Xiwen Chen, Wenhui Zhu, Gen Li, Xuanzhao Dong, Yujian Xiong, Hao Wang, Peijie Qiu, Qingquan Song, <strong>Zhipeng Wang</strong>, Shao Tang, Yalin Wang, Abolfazl Razi</div>
    <div class="pub-venue">CVPR 2026</div>
    <div class="pub-links">[<a href="https://arxiv.org/abs/2602.20205">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/planner_r1.png" alt="Planner-R1">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2509.25779">Planner-R1: Reward Shaping Enables Efficient Agentic RL with Smaller LLMs</a></div>
    <div class="pub-authors">Siyu Zhu, Yanbin Jiang, Hejian Sang, Shao Tang, Qingquan Song, Biao He, Rohit Jain, <strong>Zhipeng Wang</strong>, Alborz Geramifard</div>
    <div class="pub-venue">In review with ICLR 2026</div>
    <div class="pub-links">[<a href="https://arxiv.org/abs/2509.25779">Paper</a>]</div>
  </div>
</div>

<div class="pub-entry">
  <div class="pub-img">
    <img src="/images/publications/scaling_up_slm.png" alt="Scaling Up SLM">
  </div>
  <div class="pub-text">
    <div class="pub-title"><a href="https://arxiv.org/abs/2510.22101">Scaling Up Efficient Small Language Models Serving and Deployment for Semantic Job Search</a></div>
    <div class="pub-authors">Kayhan Behdin, Qingquan Song, Sriram Vasudevan, Jian Sheng, Xiaojing Ma, Z Zhou, Chuanrui Zhu, Guoyao Li, Chanh Nguyen, Sayan Ghosh, Hejian Sang, Ata Fatahi Baarzi, Sundara Raman Ramachandran, Xiaoqing Wang, Qing Lan, Qi Guo, Caleb Johnson, <strong>Zhipeng Wang</strong>*, Fedor Borisyuk</div>
    <div class="pub-venue">MLSys 2026 (* Corresponding author)</div>
    <div class="pub-links">[<a href="https://arxiv.org/abs/2510.22101">Paper</a>]</div>
  </div>
</div>

## Open Source Contributions

I am the TSC Committer and code maintainer for [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) project, one of the most popular OSS libraries for LLM training. I also help maintain the [Liger Kernel](https://github.com/linkedin/Liger-Kernel) project, feel free to raise issues and contribute PRs. 
