
# 🧠 Anxiety Level Detection AI Model

This repository contains an AI model designed to detect the **anxiety level** of users based on text input from chatbot conversations. It is part of a broader system aimed at supporting mental health through intelligent interaction and personalized care.

---

## 🎯 Objective

The model classifies user input into one of four anxiety levels:

- **Mild Anxiety**
- **Moderate Anxiety**
- **Severe Anxiety**

It is built to assist in early identification and help guide recommendations in a mental health app.

---

## 📦 Features

- Text preprocessing and tokenization  
- Multi-class classification using deep learning (PyTorch)  
- Model training and evaluation pipelines  
- Predict anxiety level from new user responses  
- Exported model for integration into web applications  

---

## 🚀 Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/ArvdSrh/AnxRelief-AI-Model.git
cd AnxRelief-AI-Model
```

### 2. Start the server

Make sure you have Python 3.8+

```sh
uvicorn app:app --reload
```

---

## 📁 Project Structure

- `app.py` – Prediction server runs on http://localhost:8000

---

## 🧪 Dataset

The model was trained using a curated dataset of mental health responses, each labeled with an anxiety category.  
Labels were assigned based on psychological screening questions and clinical benchmarks.

---

## 🔗 Integration

This model is designed to integrate with the **AI-Assisted Anxiety Detection and Relief Companion** app, where it processes chatbot answers and returns an anxiety level. The result is used to generate appropriate recommendations.

---

## 📜 License

This project is for academic and research purposes only.

---

## 🤝 Contact

For collaborations, contact:  
**Arvind S Suresh** – arvindssuresh@gmail.com

---
