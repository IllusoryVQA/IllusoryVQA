# IllusoryVQA

## 📚 Project Overview

This repository contains the code, experiments, and results for our project titled *Illusory VQA: Benchmarking and Enhancing Multimodal Models on Visual Illusions*. For more info, check out our paper: [Link](https://drive.google.com/file/d/1VdpI-vgYQfLrWZPbrIGUYanfV-yfXk-Z/view). 

🎉 Our paper has been accepted for presentation at the [Multimodal Algorithmic Reasoning (MAR) Workshop](https://marworkshop.github.io/neurips24/) at NeurIPS 2024 as a Spotlight Paper!

📊 Access the datasets: [Repo](https://huggingface.co/VQA-Illusion)

🎥 Watch the presentation: [Video](https://recorder-v3.slideslive.com/#/share?share=97904&s=90373c05-e3d3-419b-af24-fd160ac8c1f3) | [Slides](/Slides.pdf)

![Project Overview](/IllusoryVQA_Poster.png)

---

### 🎨 Abstract
In recent years, Visual Question Answering (VQA) has made significant strides, particularly with the advent of multimodal models that integrate vision and language understanding. However, existing VQA datasets often overlook the complexities introduced by image illusions, which pose unique challenges for both human perception and model interpretation. In this study, we introduce a novel task called Illusory VQA, along with four specialized datasets: **IllusionMNIST**, **IllusionFashionMNIST**, **IllusionAnimals**, and **IllusionChar**. These datasets evaluate the performance of state-of-the-art multimodal models in recognizing and interpreting visual illusions. 

We assess the zero-shot performance of various models, fine-tune selected models on our datasets, and propose a simple yet effective solution for illusion detection using Gaussian and blur low-pass filters. Our findings highlight the disparity between human and model perception of illusions and demonstrate that fine-tuning and specific preprocessing techniques can significantly enhance model robustness. This work contributes to developing more human-like visual understanding in multimodal models and suggests future directions for adapting filters using learnable parameters.

---

## 📂 Repository Structure

### **1. `Experiments/`**
This folder contains experiments conducted with various models under two setups:

#### **1.1 ✨ `Experiments/Fine-Tuned/`**
Fine-tuned versions of the models with code and outputs specific to each dataset:
- **`Experiments/Fine-Tuned/BLIP-2/`**
- **`Experiments/Fine-Tuned/BLIP/`**
- **`Experiments/Fine-Tuned/CLIP/`**
- **`Experiments/Fine-Tuned/LLaVA/`**

#### **1.2 🚀 `Experiments/Zero-Shot/`**
Zero-shot experiments for the following models:
- **`Experiments/Zero-Shot/BLIP-2/`**
- **`Experiments/Zero-Shot/BLIP/`**
- **`Experiments/Zero-Shot/CLIP/`**
- **`Experiments/Zero-Shot/GPT-4o/`**
- **`Experiments/Zero-Shot/Gemini/`**
- **`Experiments/Zero-Shot/KOSMOS-2/`**
- **`Experiments/Zero-Shot/LLaVA/`**
- **`Experiments/Zero-Shot/miniGPT_V2/`**

### **2. `Results/`**
This folder includes the following:

#### **2.1 ✨ `Results/Fine-Tuned/`**
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
For any questions, feel free to reach out:

- [mohammadmostafarostamkhani@gmail.com](mailto:mohammadmostafarostamkhani@gmail.com)
- [hoorieh95@gmail.com](mailto:hoorieh95@gmail.com)

