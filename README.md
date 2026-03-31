# 🧠 Multimodal NLP System for Cognitive Risk Assessment using DistilBERT + SVM

## 📌 Overview
This project focuses on detecting cognitive risk levels from human language using NLP techniques. It supports both text and speech inputs and provides a risk classification (Low, Moderate, High).

Understanding cognitive patterns from language is a challenging task due to noisy, unstructured data. This project combines transformer-based embeddings with classical machine learning to address this problem.

---

## 🚀 Features
- Supports both text and speech input for real-time cognitive risk assessment.
- Speech-to-text conversion
- Text preprocessing (cleaning, stopword removal)
- DistilBERT embeddings for deep contextual understanding
- SVM classifier for prediction
- Probability-based risk scoring
  

---
## 🧠 Model Architecture
![Architecture](architecture.png)

---

## 📊 Dataset
- Data sourced from Reddit (public discussions)
- Performed manual cleaning and relabeling
- Handled noisy and inconsistent real-world data

---

## ⚙️ Tech Stack
Python | Transformers | PyTorch | Scikit-learn | NLTK | SpeechRecognition

---

## 📊 Results
![Output](clean_output.png)

- Accuracy: 72.22%
- Risk prediction based on probability scoring


---

## 🔗 How to Run
1. Install dependencies
2. Run the notebook/script
3. Provide input (text/audio)
4. Get prediction

---

## 💡 Key Learnings
- Importance of data preprocessing in NLP
- Combining deep learning with classical ML models
- Handling noisy real-world datasets
