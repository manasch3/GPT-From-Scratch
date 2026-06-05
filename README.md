# 🤖 GPT From Scratch (TensorFlow/Keras)

A GPT-style Transformer Language Model built from scratch using **TensorFlow/Keras** and trained on the **Tiny Shakespeare** dataset.

This project implements the core components behind modern language models—including embeddings, causal self-attention, transformer blocks, and autoregressive text generation—without using pre-trained models or external LLM APIs.

## 🚀 Highlights

- Built a Decoder-Only Transformer from scratch
- Implemented Multi-Head Self-Attention and Causal Masking
- Trained on 1.1M+ characters from Tiny Shakespeare
- Generated Shakespeare-inspired dialogue
- Implemented temperature-based text sampling
- No Hugging Face or pre-trained weights used

## 📊 Model Metrics

| Metric | Value |
|----------|---------:|
| Dataset Size | 1,115,394 Characters |
| Vocabulary Size | ~65 |
| Context Length | 100 |
| Parameters | 425,537 |
| Epochs | 30 |
| Train Accuracy | 60.26% |
| Validation Accuracy | 51.17% |

## ⚙️ Architecture

```text
Text
 ↓
Character Tokenization
 ↓
Token + Positional Embeddings
 ↓
Transformer Block
 ↓
Next Character Prediction
```

### Model Configuration

| Component | Value |
|------------|---------:|
| Architecture | Decoder-Only Transformer |
| Embedding Dimension | 128 |
| Attention Heads | 4 |
| Feed Forward Dimension | 512 |
| Transformer Blocks | 1 |

## 🎭 Sample Output

**Prompt**

```text
ROMEO:
```

**Generated**

```text
ROMEO:
Ther words you for the partnoies to so servand you the mister,
And as for a like a to curst to love.

PETRUCHIO:
And for his so sech you seeeks me worthy grantage.
```

## 🧠 Key Learnings

- Transformer Architecture
- Multi-Head Self-Attention
- Positional Embeddings
- Causal Masking
- Character-Level Language Modeling
- Temperature Sampling
- Text Generation from Scratch

## 🔮 Future Versions

This repository currently represents **GPT From Scratch V1.0**.

Future releases will explore:

- Deeper Transformer Architectures
- Larger Embedding Dimensions
- More Attention Heads
- Longer Context Windows
- Top-k / Nucleus Sampling
- Conversational Fine-Tuning
- Improved Text Coherence

## ✅ Status

**GPT From Scratch V1.0** — Completed

A practical implementation of a GPT-style Transformer built from scratch to understand the foundations of modern Large Language Models.
