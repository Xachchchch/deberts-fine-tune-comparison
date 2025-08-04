# DeBERTa Fine-Tuning Comparison

This project is experimenting with LoRA vs head-only fine-tuning for DeBERTa on sentiment analysis

## Description

We compare two setups:
- Fine-tuning only the classifier head
- Fine-tuning with LoRA applied to the transformer backbone

The goal is to evaluate the trade-offs in performance and resource usage.

## Datasets

You can use any classification dataset compatible with HuggingFace datasets, such as:
- SST-2
- IMDb
- Your custom dataset (CSV/JSON)

## How to Run

### 1. Clone the repo
```bash
git clone https://github.com/your-username/deberta-lora-finetune.git
cd deberta-lora-finetune```
```
### 2.Install dependencies
```bash
pip install -r requirements.txt
