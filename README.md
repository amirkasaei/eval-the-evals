# Evaluating the Evaluators: Metrics for Compositional Text-to-Image Generation

## 📖 Overview
This repository contains the code and resources for our paper:

**Evaluating the Evaluators: Metrics for Compositional Text-to-Image Generation**  
Seyed Amir Kasaei, Ali Aghayari, Arash Marioriyad, Niki Sepasian, MohammadAmin Fazli,  
Mahdieh Soleymani Baghshah, Mohammad Hossein Rohban  

[Paper (arXiv)](https://arxiv.org/abs/XXXX.XXXXX) | [Project Page](https://your-project-site-link)  

---

## 🚀 Introduction
Text-to-image generation has made impressive progress, but **evaluating compositional alignment** remains a fundamental challenge.  
This project systematically analyzes widely used **evaluation metrics** to understand their reliability, limitations, and correspondence to human judgment.

We study 12 metrics across 8 compositional categories using **T2I-CompBench++**, highlighting:
- No single metric is universally reliable.
- Embedding-based metrics (e.g., ImageReward, HPS) and VQA-based metrics (e.g., DA Score, VQA Score) each have strengths and weaknesses.
- Image-only metrics (e.g., CLIP-IQA, Aesthetic Score) contribute little to compositional evaluation.

---

## 📊 Results
- **Correlation analysis** (Pearson, Kendall, Spearman) across compositional categories.  
- **Regression analysis** to examine combined contributions of metrics.  
- **Distributional study** highlighting biases and limitations.  

Key finding: *A combination of complementary metrics is essential for trustworthy evaluation.*

---

## 📂 Repository Structure
