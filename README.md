# 📘 Character-level RNN & Text Classification Practice

## 📌 Overview
This repository contains practice implementations based on lecture materials.  
The goal is to understand how sequence models and basic neural networks work in NLP tasks.

---

## 🧠 Contents

### 1. Character-level RNN (`06_01_char_rnn.ipynb`)
- Predicts the next character in a sequence
- Uses RNN to learn character patterns
- Covers:
  - One-hot encoding
  - Hidden state
  - Sequence prediction
  - Training loop

---

### 2. Text Classification (`06_02_naver_classification.ipynb`)
- Performs basic text classification
- Covers:
  - Text preprocessing
  - Model training
  - Loss calculation (CrossEntropy)
  - Prediction

---

## ⚙️ Key Concepts
- RNN / LSTM fundamentals  
- Sequence data handling  
- CrossEntropyLoss  
- Tensor reshaping (`view(-1, ...)`)  
- Training loop (forward → loss → backward → update)  

---

## 🚀 How to Run

### 1. Install dependencies
```bash
pip install torch numpy
