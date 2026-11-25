# Shakespeare AI — Intelligent Text Generation

### Bringing Classical Literature into the World of Generative AI

Shakespeare AI is a transformer-based text generation project designed to explore the power of modern language models. By fine-tuning **DistilGPT-2** on Shakespearean literature, the system learns linguistic patterns, dialogue structures, and classical writing styles to generate context-aware text from simple prompts.

## Project Overview

This project demonstrates an end-to-end Generative AI workflow, from dataset preparation and tokenization to model fine-tuning, evaluation, and text generation.

The goal is to transform a pretrained language model into a specialized text generator capable of producing Shakespeare-inspired continuations.

## Key Capabilities

- **Domain-Specific Fine-Tuning:** Adapted DistilGPT-2 to Shakespearean text.
- **Context-Aware Generation:** Generates text based on user-provided prompts.
- **Advanced Sampling:** Experiments with Temperature, Top-K, and Top-P strategies.
- **Repetition Control:** Uses repetition penalty and n-gram restrictions to improve output diversity.
- **Model Evaluation:** Tracks training and validation loss to monitor learning behavior.

## Technology Stack

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- DistilGPT-2
- NumPy, Pandas, Matplotlib

## Model & Dataset

| Component | Selection |
|---|---|
| Base Model | DistilGPT-2 |
| Dataset | Trelis/Tiny-Shakespeare |
| Learning Approach | Fine-Tuning |
| Task | Causal Language Modeling |
| Output | Shakespeare-inspired text |

## Project Workflow

1. Dataset loading and exploration
2. Text preprocessing and tokenization
3. Sequence preparation
4. Pretrained model initialization
5. Model fine-tuning
6. Training and validation analysis
7. Text generation and sampling experiments

## Getting Started

Install the required libraries:

```bash
pip install torch transformers datasets numpy pandas matplotlib
```

Load the pretrained model, prepare the dataset, and run the fine-tuning pipeline using the provided notebook.

## Project Objective

This project represents a practical step toward understanding and building Generative AI systems. It demonstrates how pretrained transformer architectures can be adapted to specialized language-generation tasks through fine-tuning and controlled decoding.

---

**Built to explore. Designed to generate. Powered by Transformers.**
