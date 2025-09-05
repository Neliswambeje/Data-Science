# 🧠 Week 2 – Deep Learning with CNN & RNN

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-API-red?logo=keras)](https://keras.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

📌 This project explores two core deep learning architectures:
- **CNN (Convolutional Neural Network)** for image classification on **CIFAR-10** 🖼️  
- **RNN (Recurrent Neural Network / LSTM)** for sentiment analysis on **IMDB reviews** ✍️  

---

## 🚀 Overview

### 🔹 CNN – CIFAR-10
- **Dataset**: 60,000 RGB images (32×32 px) across 10 classes (airplane, car, bird, etc.)
- **Architecture**:
  - Convolutional + pooling layers for feature extraction
  - Dropout & Batch Normalization for regularization
  - Dense softmax classifier
- **Result**: ✅ Achieved ~80% accuracy

### 🔹 RNN – IMDB Sentiment
- **Dataset**: 25,000 labeled movie reviews (positive / negative)
- **Architecture**:
  - Text preprocessing + embeddings
  - LSTM layers for sequence modeling
  - Dense sigmoid output for binary classification
- **Result**: ✅ Achieved ~85% accuracy

---

## 📂 Project Structure


---

## 🛠️ Tech Stack
- **Language**: Python 3.9+
- **Frameworks**: TensorFlow (Keras API)
- **Libraries**: NumPy, Matplotlib, scikit-learn

---

## 📊 Results

| Model   | Dataset     | Accuracy |
|---------|------------|----------|
| CNN     | CIFAR-10   | ~80%     |
| RNN/LSTM| IMDB       | ~85%     |

---

## 🧪 Skills Demonstrated
✔️ Convolutional filters & pooling layers  
✔️ Sequence modeling with RNN / LSTM  
✔️ Regularization: dropout, batch normalization  
✔️ Comparing image vs. text modeling  

---

## ▶️ Run the Notebooks

1. Clone repo:
   ```bash
   git clone https://github.com/yourusername/week2-cnn-rnn.git
   cd week2-cnn-rnn

pip install -r requirements.txt
jupyter notebook

