# ML Twitter Sentiment Analysis

This project explores various deep learning approaches to sentiment classification using the [dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion) dataset. The goal is to predict emotional tone (e.g., joy, sadness, anger) from tweets using different neural network architectures.

## 📊 Dataset

The dataset consists of **20,000** labeled text samples split into training, validation, and test sets. Each entry includes:

- `text`: A string of user-generated content (similar to tweets)
- `label`: An emotion category:
  - `0` – Sadness
  - `1` – Joy
  - `2` – Love
  - `3` – Anger
  - `4` – Fear
  - `5` – Surprise

---

## 🧠 Models Implemented

### ✅ Baseline Models:
- **Simple RNN**: Single and stacked layers to process sequential text data
- **LSTM (Long Short-Term Memory)**: Better captures long-term dependencies in sequences

### ✅ Advanced Models:
- **BERT (via TensorFlow Hub)**: Pre-trained transformer for contextual embedding and classification
- **Cohere Classification API**: Integration of Cohere's NLP models via API

---

## 🔧 Key Concepts & Techniques

- Tokenization and padding of input sequences
- Text sequence length distribution analysis
- Model performance visualization (accuracy/loss over epochs)
- TensorFlow's Keras API for building and training models
- Comparative analysis of RNN, LSTM, and Transformer-based models
- Integration with APIs (Cohere)
---

## 📚 Educational Value

This notebook:
- Demonstrates the evolution of NLP models from RNNs to Transformers
- Showcase best practices for evaluating sequence models
- Introduce pre-trained models and modern NLP APIs

