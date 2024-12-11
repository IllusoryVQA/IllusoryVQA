# IllusoryVQA

# README

## 📚 Project Overview

This repository contains the code, experiments, and results for our project titled *Illusory VQA: Benchmarking and Enhancing Multimodal Models on Visual Illusions*. For more info, check our paper: *[link]*. 

---

### 🎨 Abstract
In recent years, Visual Question Answering (VQA) has made significant strides, particularly with the advent of multimodal models that integrate vision and language understanding. However, existing VQA datasets often overlook the complexities introduced by image illusions, which pose unique challenges for both human perception and model interpretation. In this study, we introduce a novel task called Illusory VQA, along with four specialized datasets: **IllusionMNIST**, **IllusionFashionMNIST**, **IllusionAnimals**, and **IllusionChar**. These datasets evaluate the performance of state-of-the-art multimodal models in recognizing and interpreting visual illusions. 

We assess the zero-shot performance of various models, fine-tune selected models on our datasets, and propose a simple yet effective solution for illusion detection using Gaussian and blur low-pass filters. Our findings highlight the disparity between human and model perception of illusions and demonstrate that fine-tuning and specific preprocessing techniques can significantly enhance model robustness. This work contributes to developing more human-like visual understanding in multimodal models and suggests future directions for adapting filters using learnable parameters.

---

## 📂 Repository Structure

### **1. `Experiences/`**
This folder contains experiments conducted with various models under two setups:

#### **1.1 ✨ `Experiences/Fine-Tuned/`**
Fine-tuned versions of the models with code and outputs specific to each dataset:
- **`Experiences/Fine-Tuned/BLIP-2/`**
- **`Experiences/Fine-Tuned/BLIP/`**
- **`Experiences/Fine-Tuned/CLIP/`**
- **`Experiences/Fine-Tuned/LLaVA/`**

#### **1.2 🚀 `Experiences/Zero-Shot/`**
Zero-shot experiments for the following models:
- **`Experiences/Zero-Shot/BLIP-2/`**
- **`Experiences/Zero-Shot/BLIP/`**
- **`Experiences/Zero-Shot/CLIP/`**
- **`Experiences/Zero-Shot/GPT-4o/`**
- **`Experiences/Zero-Shot/Gemini/`**
- **`Experiences/Zero-Shot/KOSMOS-2/`**
- **`Experiences/Zero-Shot/LLaVA/`**
- **`Experiences/Zero-Shot/miniGPT_V2/`**

### **2. `Results/`**
This folder includes the following:

#### **2.1 ✨ `Results/fine-tuned/`**
Outputs for models fine-tuned on the datasets.

#### **2.2 🚀 `Results/Zero-Shot/`**
Outputs for models evaluated in a zero-shot setup.

#### **2.3 👥 `Results/Human-Evaluation/`**
Contains CSV files with annotations from four annotators for parts of each dataset. Each annotator's work is represented in a separate file:
- **`Results/Human-Evaluation/annotator1.csv`**
- **`Results/Human-Evaluation/annotator2.csv`**
- **`Results/Human-Evaluation/annotator3.csv`**
- **`Results/Human-Evaluation/annotator4.csv`**

---

## 🛠️ How to Use the Repository

**Clone the Repository**:
```bash
   git clone https://github.com/IllusoryVQA/IllusoryVQA.git
   cd [repository folder]
```
Explore experiments or results and run the notebooks.

---

## 📖 Citation
If you find our work useful, please cite our paper:

---

## 📩 Contact
For any queries, feel free to reach out:

- [Email](mailto:hoorieh95@gmail.com)

