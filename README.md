# 🧠 Deep Learning Bootcamp – Week 1: MNIST Digit Classifier  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)  
![License](https://img.shields.io/badge/License-MIT-green.svg)  
![Status](https://img.shields.io/badge/Status-Completed-success)  

## 📌 Project Overview  
This project is part of my **3-month Data Scientist transition plan** 🚀.  
In **Week 1**, I built a **Deep Learning model** using **TensorFlow/Keras** to classify handwritten digits from the **MNIST dataset (0–9)**.  

The model learns from **60,000 training images** and evaluates performance on **10,000 test images**.  

---

## 📂 Project Structure  

📦 mnist-week1
├── 📓 mnist_classifier.ipynb # Main Jupyter Notebook with code + explanations
├── 📊 results/ # Model outputs, plots, and accuracy/loss graphs
├── 📄 README.md # Project documentation
└── 📜 requirements.txt # List of dependencies


---

## ⚙️ Setup Instructions  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Neliswambeje/Data-Science/tree/Deep-Learning-mnist
   cd mnist-week1

2. Create and activate environment
   conda create -n tf_env python=3.9 -y
conda activate tf_env
pip install -r requirements.txt

3. Run Jupyter Notebook
   jupyter notebook

📚 Key Learnings

✅ How to load and preprocess the MNIST dataset
✅ Building a Sequential model in TensorFlow/Keras
✅ Using dense layers with activation functions
✅ Training with SGD/Adam optimizers
✅ Plotting accuracy & loss curves with matplotlib

📊 Results

Training Accuracy: ~98%

Test Accuracy: ~97%

Model successfully recognizes handwritten digits ✨

✨ Built with ❤️ by https://github.com/Neliswambeje
