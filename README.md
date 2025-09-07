<div align="center">

# 🧠 SLM: Build Your Own Small Language Model 🧠

**A from-scratch implementation of a Transformer-based language model in PyTorch, trained to write children's stories.**

</div>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-2.0%2B-ee4c2c?style=for-the-badge&logo=pytorch">
  <a href="https://github.com/J-anubhav/SLM/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge">
  </a>
  <a href="https://youtu.be/pOFcwcwtv3k?si=v-qqfaxNka9Sqmq1">
    <img alt="YouTube Tutorial" src="https://img.shields.io/badge/YouTube-Tutorial-red?style=for-the-badge&logo=youtube">
  </a>
</p>

---

<p align="center">
  This project demystifies the magic behind models like GPT by building a small-scale version from the ground up. It handles everything from raw text processing to generating new, coherent stories.
</p>

<div align="center">

**Check out the amazing tutorial that inspired this project:**

[![YouTube Tutorial Video](https://img.youtube.com/vi/pOFcwcwtv3k/0.jpg)](https://youtu.be/pOFcwcwtv3k?si=v-qqfaxNka9Sqmq1)

</div>

---

## ✨ What's Inside?

This repository contains all you need to replicate the project:

-   **🤖 Transformer Model:** A complete implementation of the core architecture, including Multi-Head Attention, Positional Embeddings, and Layer Normalization.
-   **📦 Efficient Data Pipeline:** Raw text is tokenized and stored in memory-efficient `.bin` files, ready for training.
-   **⚡ Optimized Training Loop:** Features an AdamW optimizer, a cosine decay learning rate schedule, and automatic mixed precision for faster training.
-   **📝 Jupyter Notebook:** All the code is contained in a single, well-documented notebook (`Vizuara_AI_Labs_Small_Language_Model_Scratch_Final.ipynb`).
-   **📊 Pre-Trained Model:** The final trained model weights (`best_model_params.pt`) are included, so you can start generating text right away!

---

## 🚀 Getting Started

### 1. Prerequisites
Make sure you have **Git LFS** installed to handle the large model and data files.
```bash
# Install Git LFS (if you haven't already)
git lfs install
```

### 2. Clone the Repository
This will automatically download the large files via Git LFS.
```bash
git clone [https://github.com/J-anubhav/SLM.git](https://github.com/J-anubhav/SLM.git)
cd SLM
```

### 3. Install Dependencies
Set up your environment with the required libraries.
```bash
pip install torch numpy transformers tiktoken jupyter
```

### 4. Launch and Run!
Open the Jupyter Notebook to explore the code and run the cells.
```bash
jupyter notebook Vizuara_AI_Labs_Small_Language_Model_Scratch_Final.ipynb
```

---

## 🙏 Acknowledgements & Credit

This project is a direct implementation of the concepts taught in the incredible tutorial by **The AI Guy**. All credit for the architecture and methodology goes to him. Please support his channel!

-   **Creator**: Vizuara
-   **Video Link**: [Build a Large Language Model (From Scratch)](https://youtu.be/pOFcwcwtv3k?si=v-qqfaxNka9Sqmq1)

---
<p align="center">
  Made with curiosity by Anubhav Jha
</p>
