# WorldModelBenchmark

[**🌐 Homepage**](https://seerkfang.github.io/world-model-benchmark.github.io/) | [**🏆 Leaderboard**](https://seerkfang.github.io/world-model-benchmark.github.io/#leaderboard) | [**📖 WorldModelBench arXiv**](https://arxiv.org/pdf/2311.16502.pdf)

This repo contains the evaluation instruction for the paper "[WorldModelBench: Judging Video Generation Models As World Models]([https://arxiv.org/abs/2409.02813](https://drive.google.com/drive/folders/1mBBGM1E14JlmXmqRFonlqs76d9uBBZ0T?usp=drive_link))".

## 🔔News

- **🔥[2025-02-23]: Our [WorldModelBench](https://seerkfang.github.io/world-model-benchmark.github.io/) is now available. We look forward to your participation! 😆**

## Introduction

### WorldModelBench

WorldModelBencha is a benchmark designed to evaluate the **world modeling capabilities** of video generation models across **7** application-driven domains (spanning from Robotics, Driving, Industry, Human Activities, Gaming, Animation, and Natural) and **56** subdomains. Each domain features 50 carefully curated prompts, comprising a text description and an initial video frame, tailored for video generation. We provide a **human-aligned** VLM (Vision-Language Model) based judger to automatically evaluate model-generated videos on **Instruction Following**, **Common Sense**, and **Physical Adherence**.

## Evaluation

🎯 Please refer to the following instructions to evaluate with WorldModelBench:

- **We have released a full suite comprising 150 development samples and 900 validation samples. However, the 10,500 test questions are available without their answers.**
- Use the **development set** for few-shot/in-context learning.
- Use the **validation set** for debugging models, selecting hyperparameters, and quick evaluations.

The answers and explanations for the test set questions are withheld. You can submit your model's predictions for the **test set** on **[EvalAI](https://eval.ai/web/challenges/challenge-page/2179/overview)**.

## Disclaimers
The guidelines for the annotators emphasized strict compliance with copyright and licensing rules from the initial data source, specifically avoiding materials from websites that forbid copying and redistribution. 
Should you encounter any data samples potentially breaching the copyright or licensing regulations of any site, we encourage you to [contact](#contact) us. Upon verification, such samples will be promptly removed.

## Contact
- Dacheng Li: dacheng177@berkeley.edu
- Yunhao Fang: seerkfang@gmail.com

## Citation

**BibTeX:**
```bibtex
@inproceedings{Li2024WorldModelBench,
  title={WorldModelBench: Judging Video Generation Models As World Models},
  author={Dacheng Li and Yunhao Fang and Yukang Chen and Shuo Yang and Shiyi Cao and Justin Wong and Xiaolong Wang and Hongxu Yin and Joseph E. Gonzalez and Ion Stoica and Song Han and Yao Lu},
  booktitle={In Submission},
  year={2025},
}
```
This website is website adapted from [MMMU](https://github.com/MMMU-Benchmark/MMMU).
