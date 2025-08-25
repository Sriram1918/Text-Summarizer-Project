# Text Summarizer Project

## Overview
This project implements an **abstractive text summarization model** using Hugging Face Transformers. It leverages the **Pegasus model** (`google/pegasus-cnn_dailymail`), and evaluates it on the **SAMSum dataset**, which contains dialogue-to-summary pairs. The goal is to automatically generate concise summaries of conversations or longer texts.

## Features
- Hugging Face **Transformers** and **Datasets** integration  
- Pretrained model: `google/pegasus-cnn_dailymail`  
- Dataset: **SAMSum dialogue dataset**  
- GPU/CPU compatibility via PyTorch  
- Evaluation metrics: **ROUGE** score  
- Example dialogues with generated summaries  

## Installation
```bash
pip install transformers[sentencepiece] datasets sacrebleu rouge_score py7zr
pip install --upgrade accelerate
pip install matplotlib pandas tqdm nltk torch
