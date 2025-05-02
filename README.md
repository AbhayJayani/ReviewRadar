# 🎬 ReviewRadar — Movie Review Sentiment Analysis with LSTM

ReviewRadar is a deep learning-powered sentiment analysis tool that classifies movie reviews as **positive** or **negative**. Built with a BiLSTM architecture, this project explores the emotional tone behind user-generated reviews for a particular movie.

---

## 🚀 Features

- 📚 Uses the IMDB dataset for real-world movie reviews
- 🔁 Bidirectional LSTM for context-aware sequence learning
- 🧠 Built and trained using Keras & TensorFlow
- 📊 Achieves ~88% accuracy with a low validation loss
- 📉 Visualizes model performance over epochs
- 💡 Easily extensible for broader text classification tasks

---

## 🧰 Technologies Used

- Python 🐍
- TensorFlow / Keras 🔧
- NumPy & Pandas 📊
- Matplotlib & Seaborn 📈
- NLP Preprocessing (Tokenizer, Padding, Cleaning)

---

## 🧠 Model Overview

The model architecture combines **Embedding** and **Bidirectional LSTM** layers to learn both syntactic and semantic relationships in text. A stacked configuration helps the network capture both short- and long-term dependencies, enabling it to understand sentiment more accurately.

### Highlights:
- **Embedding Layer** to convert words into dense vector representations
- **BiLSTM Layers** to capture context from both directions
- **Dense Layers** with ReLU and Sigmoid activations for final classification
- **Dropout Regularization** to mitigate overfitting

---

## 📷 Sample Output

| Epoch | Accuracy | Loss |
|-------|----------|------|
| 10    | 0.88     | 0.30 |

Training and validation accuracy/loss plots are included in the notebook.

