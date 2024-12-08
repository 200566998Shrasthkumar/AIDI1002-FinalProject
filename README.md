# AIDI 1002 Final Project

This repository contains the implementation of a research paper selected for the AIDI 1002 final project. The project focuses on replicating the methodology and contributing to the research paper with a significant enhancement.

## Overview
- **Research Paper**: [BERT: Pre-training of Deep Bidirectional Transformers for
Language Understanding](https://arxiv.org/pdf/1810.04805)
- **Publication Year**: (2019)
- **GitHub Repository**: [BERT GitHub Repository](https://github.com/google-research/bert)

This project replicates the results of the selected research paper and includes a significant contribution to the methodology.

## Key Highlights of the Paper
1. BERT uses a bidirectional transformer to understand the context of words from both directions simultaneously.
2. Pre-trained on large datasets for masked language modeling and next sentence prediction tasks.
3. Fine-tunable for specific NLP tasks like question answering, sentiment analysis, and named entity recognition.

## Project Steps

### 1. Reproducibility
- **Pre-training**: Implemented pre-training using masked language modeling and next sentence prediction tasks, as described in the paper.
- **Fine-tuning**: Fine-tuned the pre-trained BERT model on specific downstream tasks (e.g., sentiment analysis, question answering).
- Successfully reproduced the results using pre-trained BERT models available from the original repository.

### 2. Contribution
- Tested BERT on additional datasets to evaluate its effectiveness in diverse contexts.
- Experimented with hyperparameter tuning to observe changes in model performance.
- Deployed a new model MLP to compare and evulate with the BERT model.

## Prerequisites
- Python 3.8+
- Libraries: TensorFlow, PyTorch, NumPy, Pandas, Matplotlib.

## Authors
  - Steve Kuruvilla (200573392)
  - Shrasth Kumar (200566998)
