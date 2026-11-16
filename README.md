# Deep Learning — A Mathematical Approach

> **From mathematical first principles to production Computer Vision and Persian Plate OCR.**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PouryaDadlouie98/Deep-Learning-mathematical-approach-/blob/main/Basis.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📌 Project Overview

This repository documents an engineering and mathematical journey through Deep Learning—bridging low-level calculus and autograd mechanics with production-ready PyTorch architectures.

The roadmap progresses from foundational scalar differentiation and tensor operations to **Convolutional Neural Networks (CNNs)** and full-pipeline **Persian License Plate Recognition (CRNN + CTC)**.

---

## 📚 Curriculum & Notebooks

| # | Chapter / Notebook | Focus & Core Concepts | Status | Colab |
|---|--------------------|-----------------------|:------:|:-----:|
| **01** | **[`Basis.ipynb`](Basis.ipynb)** | **Foundations**: Scalar Autograd engine from scratch (`Value`), PyTorch tensor mechanics (4D image indexing/slicing), gradient sensitivity intuition (`w.grad`, `b.grad`), 5-step `torch.optim` loop, and canonical `torch.nn.Module` architecture. | 🟢 Completed | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PouryaDadlouie98/Deep-Learning-mathematical-approach-/blob/main/Basis.ipynb) |
| **02** | `02_cnn_foundations.ipynb` | **Computer Vision**: Convolution arithmetic (`nn.Conv2d`), receptive fields, spatial pooling (`nn.MaxPool2d`), feature map transformations, and training on FashionMNIST. | 🟡 In Progress | *Coming soon* |
| **03** | `03_advanced_vision.ipynb` | **Generalization & Regularization**: Batch Normalization, Dropout, data augmentation pipelines, learning rate schedulers, and diagnostics. | ⚪ Planned | *Coming soon* |
| **04** | `04_plate_ocr_crnn.ipynb` | **Persian Plate OCR**: End-to-end character recognition combining CNN feature extractors, Bidirectional RNNs (LSTM/GRU), and Connectionist Temporal Classification (CTC Loss). | ⚪ Planned | *Coming soon* |

---

## 🚀 Getting Started

### 1. Run Online (Google Colab)
No setup required. Click the badge below to run the interactive notebooks on GPU:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PouryaDadlouie98/Deep-Learning-mathematical-approach-/blob/main/Basis.ipynb)

### 2. Run Locally
```bash
# Clone the repository
git clone https://github.com/PouryaDadlouie98/Deep-Learning-mathematical-approach-.git
cd Deep-Learning-mathematical-approach-

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install torch torchvision jupyterlab matplotlib
```

---

## 👤 Author

**Pourya Dadlouie**  
- GitHub: [@PouryaDadlouie98](https://github.com/PouryaDadlouie98)
