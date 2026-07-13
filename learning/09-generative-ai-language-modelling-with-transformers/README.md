# Generative AI Language Modeling with Transformers

> Hands-on implementation of Transformer-based language models using **PyTorch**, covering attention mechanisms, positional encoding, Transformer encoders and decoders, GPT, BERT, language translation, and practical NLP applications.

---

## Overview

This module builds upon the foundations of Generative AI and Transformer architecture by implementing the core components that power modern Large Language Models (LLMs).

The notebooks progressively introduce attention mechanisms, positional encoding, Transformer-based text classification, decoder-only GPT models, encoder-only BERT models, and encoder-decoder architectures for machine translation.

By the end of this module, you'll understand how modern language models are constructed and how Transformers are adapted for language understanding, text generation, and translation.

---

## Learning Objectives

After completing this module, you will be able to:

- Understand positional encoding and its importance in Transformer architectures.
- Explain and implement self-attention and scaled dot-product attention.
- Understand Query, Key, and Value (QKV) representations.
- Build Transformer-based text classification models.
- Implement decoder-only language models similar to GPT.
- Understand causal language modeling and next-token prediction.
- Build encoder-only models inspired by BERT.
- Understand Masked Language Modeling (MLM) and Next Sentence Prediction (NSP).
- Prepare training data for BERT using tokenization and masking.
- Build encoder-decoder Transformer models for machine translation.
- Compare GPT, BERT, and Encoder-Decoder Transformer architectures.

---

# Repository Structure

```text
09-generative-ai-language-modelling-with-transformers/
│
├── README.md
└── notebooks/
    ├── 01-Attention-Mechanism-And-Positional-Encoding.ipynb
    ├── 02-Applying-Transformers-For-Classification.ipynb
    ├── 03-Decoder-Causal-LM-GPT-Like-Models.ipynb
    ├── 04-Encoder-Models-With-Baby-BERT.ipynb
    ├── 05-Data-Preparations-For-BERT.ipynb
    └── 06-Transformers-For-Translation.ipynb
```

---

# Notebook Summary

| Notebook | Topics |
|----------|--------|
| **01. Attention Mechanism and Positional Encoding** | Word Embeddings, Positional Encoding, Self-Attention, Query-Key-Value, Scaled Dot-Product Attention, Multi-Head Attention |
| **02. Applying Transformers for Classification** | Transformer Encoder, Text Classification, Dataset, DataLoader, Classification Head |
| **03. Decoder Causal LM (GPT-like Models)** | Decoder Architecture, GPT, Causal Language Modeling, Next Token Prediction |
| **04. Encoder Models with Baby BERT** | BERT Architecture, Encoder, Masked Language Modeling (MLM), Next Sentence Prediction (NSP) |
| **05. Data Preparations for BERT** | Tokenization, Masking, Special Tokens, MLM Dataset, NSP Dataset |
| **06. Transformers for Translation** | Encoder-Decoder Architecture, Cross Attention, Machine Translation, Teacher Forcing |

---

# ⭐ Featured Notebooks

These notebooks demonstrate the core concepts behind modern Transformer-based language models and are the highlights of this module.

| Notebook | Why It Matters |
|----------|----------------|
| **01. Attention Mechanism and Positional Encoding** | Implements the core building blocks of Transformers, including Query-Key-Value (QKV), Self-Attention, Scaled Dot-Product Attention, Multi-Head Attention, and Positional Encoding. |
| **03. Decoder Causal LM (GPT-like Models)** | Builds a decoder-only Transformer similar to GPT and demonstrates causal language modeling, next-token prediction, and autoregressive text generation. |
| **04. Encoder Models with Baby BERT** | Implements a simplified BERT model and introduces Masked Language Modeling (MLM), Next Sentence Prediction (NSP), and bidirectional language understanding. |
| **06. Transformers for Translation** | Builds an Encoder–Decoder Transformer from scratch using PyTorch, demonstrating Cross-Attention, Teacher Forcing, and neural machine translation. |

These notebooks collectively demonstrate the core architectures that power modern Foundation Models and Large Language Models.

---

# Concepts Covered

## Transformer Fundamentals

- Word Embeddings
- Positional Encoding
- Query, Key, Value (QKV)
- Self-Attention
- Scaled Dot-Product Attention
- Multi-Head Attention
- Feed Forward Networks
- Layer Normalization
- Residual Connections

---

## Transformer Architectures

- Encoder-Only (BERT)
- Decoder-Only (GPT)
- Encoder-Decoder (Translation)

---

## Language Modeling

- Causal Language Modeling (CLM)
- Masked Language Modeling (MLM)
- Next Sentence Prediction (NSP)
- Next Token Prediction

---

## NLP Applications

- Text Classification
- Language Modeling
- Machine Translation
- Text Generation

---

## PyTorch Topics

- Dataset
- DataLoader
- Embedding Layer
- Transformer Encoder
- Transformer Decoder
- Training Loop
- Loss Functions
- Model Evaluation

---

# Transformer Learning Journey

```text
Word Embeddings
        │
        ▼
Positional Encoding
        │
        ▼
Self-Attention
        │
        ▼
Scaled Dot-Product Attention
        │
        ▼
Multi-Head Attention
        │
        ▼
Transformer Encoder
        │
        ▼
Transformer Decoder
        │
        ▼
GPT
        │
        ▼
BERT
        │
        ▼
Machine Translation
```

---

# Practical Skills Gained

By completing this module, you will gain practical experience in:

- Building Transformer architectures using PyTorch.
- Implementing self-attention mechanisms.
- Creating positional encodings.
- Developing GPT-like decoder models.
- Building BERT-like encoder models.
- Preparing datasets for MLM and NSP training.
- Applying Transformers for text classification.
- Building Transformer-based translation models.
- Understanding how modern Large Language Models work internally.

---

# Related Notes

This module aligns with the following engineering notes:

- `language-modeling.md`
- `llm-data-preparation.md`
- `transformer-architecture.md`
- `attention-and-positional-encoding.md`
- `gpt-and-bert-architecture.md`
- `transformer-applications.md`

---

# Key Takeaways

- Transformers replaced recurrent neural networks as the foundation of modern NLP.
- Self-attention enables efficient parallel processing and contextual understanding.
- Positional encoding preserves word order within Transformer models.
- GPT uses a decoder-only architecture for autoregressive text generation.
- BERT uses an encoder-only architecture for bidirectional language understanding.
- Encoder-decoder Transformers power machine translation and many sequence-to-sequence tasks.
- Modern Large Language Models are built upon these fundamental Transformer components.

---

# References

- IBM AI Engineering Professional Certificate (Coursera)
- Attention Is All You Need (Vaswani et al., 2017)
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
- GPT Research Papers
- PyTorch Documentation
- Hugging Face Transformers Documentation