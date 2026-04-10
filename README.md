📘 Character-level RNN & Text Classification Practice
📌 Overview

This repository contains practice implementations based on lecture materials.
The goal is to understand how sequence models and simple neural networks work in natural language processing tasks.

It includes:

Character-level RNN for sequence prediction
Text classification example (Naver dataset)
🧠 Contents
1. Character-level RNN (06_01_char_rnn.ipynb)
Implements an RNN-based model to predict the next character in a sequence
Learns patterns from input text at the character level
Demonstrates:
Sequence modeling
One-hot encoding
Hidden state handling
Training loop with loss optimization
2. Text Classification (06_02_naver_classification.ipynb)
Basic text classification task using labeled data
Demonstrates:
Text preprocessing
Model training
Loss calculation and optimization
Prediction and evaluation
⚙️ Key Concepts
RNN / LSTM fundamentals
Sequence data handling
CrossEntropyLoss usage
Tensor reshaping (view(-1, ...))
Training loop (forward → loss → backward → update)
🚀 How to Run
Install required libraries:
pip install torch numpy
Open notebooks:
jupyter notebook
Run each cell step by step
📎 Notes
This project is based on lecture practice code
Some parts are simplified for learning purposes
Focus is on understanding the workflow rather than performance optimization
🎯 Purpose

The main purpose of this repository is:

To build intuition for how neural networks process sequential data and perform basic NLP tasks.
