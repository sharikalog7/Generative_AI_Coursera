# Coursera - Generative AI with Large Language Models  

## Overview

This repository contains my work for the Coursera course labs on Generative AI for Dialogue Summarization (Aug 2023 – Sep 2023). The labs explore prompt engineering, model fine-tuning, and reinforcement learning techniques to optimize dialogue summarization using state-of-the-art Large Language Models (LLMs).

---

## Table of Contents

- [Lab 1: Dialogue Summarization with Generative AI](#lab-1-dialogue-summarization-with-generative-ai)
- [Lab 2: Fine-Tune a Generative AI Model](#lab-2-fine-tune-a-generative-ai-model)
- [Lab 3: RLHF and PEFT for Less-Toxic Summaries](#lab-3-rlhf-and-peft-for-less-toxic-summaries)
- [Running on AWS SageMaker](#running-on-aws-sagemaker)
- [Skills & Technologies](#skills--technologies)
- [References](#references)

---

## Lab 1: Dialogue Summarization with Generative AI

- Explored dialogue summarization tasks using generative AI.
- Investigated the influence of input text and prompt engineering on model output.
- Analyzed zero-shot, one-shot, and few-shot inference to optimize LLM performance.
- Demonstrated how prompt engineering can enhance the quality and efficiency of dialogue summarization.

---

## Lab 2: Fine-Tune a Generative AI Model

- Fine-tuned the Longformer-Encoder-Decoder model (Hugging Face) and FLAN-T5 for improved dialogue summarization.
- Employed ROUGE metrics for evaluating summarization quality.
- Experimented with Parameter Efficient Fine-Tuning (PEFT) to streamline the process.
- Showcased iterative fine-tuning and evaluation for continuous improvement.

---

## Lab 3: RLHF and PEFT for Less-Toxic Summaries

- Utilized FLAN-T5 and Meta AI's hate speech reward model to reduce toxicity in generated summaries.
- Applied Proximal Policy Optimization (PPO) reinforcement learning for safer content generation.
- Demonstrated the use of RLHF (Reinforcement Learning from Human Feedback) and PEFT for responsible AI.

---

## Running on AWS SageMaker

### 1. Launch a SageMaker Notebook Instance

- Go to AWS SageMaker Console.
- Click **Notebook instances** > **Create notebook instance**.
- Choose an instance type (e.g., `ml.t3.medium` for CPU, `ml.p3.2xlarge` for GPU).

### 2. Open the Jupyter Notebook

- Once the instance is running, click **Open Jupyter**.

### 3. Change the Kernel

- In Jupyter, go to the notebook menu:  
  **Kernel > Change kernel > [Choose Python 3 (Data Science) or PyTorch/TensorFlow (GPU)]**

### 4. Select CPU or GPU

- The instance type determines CPU/GPU usage:
    - For **CPU**, use a CPU-based instance (e.g., `ml.t3.medium`).
    - For **GPU**, use a GPU-based instance (e.g., `ml.p3.2xlarge`).
- To switch, stop your instance, change the instance type, and restart.

### 5. Upload and Run Notebooks

- Upload your lab notebooks (`.ipynb`) to the Jupyter environment.
- Install required packages:
    ```
    !pip install transformers datasets peft accelerate rouge-score
    ```
- Run each cell step by step.

---

## Skills & Technologies

- Generative AI
- Prompt Engineering
- Model Fine-Tuning (Longformer, FLAN-T5)
- Parameter Efficient Fine-Tuning (PEFT)
- Reinforcement Learning (PPO, RLHF)
- Toxicity Mitigation (Meta AI Hate Speech Reward Model)
- AWS SageMaker (CPU/GPU)

---

## References

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [AWS SageMaker Documentation](https://docs.aws.amazon.com/sagemaker/)
- [Meta AI Hate Speech Reward Model](https://github.com/facebookresearch/)

---

---

**Author:** Sharika Loganathan  
**Course:** Coursera - Generative AI with Large Language Models  
**Issued:** Aug 2023  
**Credential ID:** EEZS92GAYUAZ  
[Show Credential](https://www.coursera.org/account/accomplishments/certificate/EEZS92GAYUAZ)


