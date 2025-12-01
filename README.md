# Tiny GPT-2 Implementation

A "tiny" implementation of GPT-2 trained on a Haiku dataset, designed to run on limited resources (like a single T4 GPU on Google Colab).

## Project Description

This project demonstrates how to build and train a small-scale GPT-2 model from scratch. The goal is to understand the architecture and mechanics of Transformers by implementing them, rather than just using pre-trained models.

Key features:
- **Byte-Level BPE Tokenization**: Handling text efficiently.
- **Transformer Architecture**: Implementing Self-Attention, LayerNorm, and FeedForward networks.
- **Training**: Autoregressive training on a dataset of haikus.
- **Generation**: Sampling new haikus from the trained model.

## Links

- **Google Colab Notebook**: [Run the Code](https://colab.research.google.com/drive/1zmiC_-CCRgKn0fWWwn5x-_wJseZ4APCt?usp=sharing)
- **Detailed Blog Post**: [Read the Tutorial](https://tonar.xyz/blog/2025/gpt2_tutorial/)

## Usage

The easiest way to run this project is via the Google Colab link above.

If you wish to run it locally, ensure you have the necessary dependencies installed (PyTorch, Transformers, etc.) and run the notebook `GPT_2_Implementation.ipynb`.

## References

1. [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
2. [OpenAI GPT-2 Paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
