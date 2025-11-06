# 🧠 Fake Review Detection using Ensemble Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-orange?logo=scikit-learn)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

### 📌 Overview
A machine learning project designed to **detect fake product reviews** using an **ensemble of Logistic Regression and Naïve Bayes models**.  
Built to improve online review reliability by identifying automatically generated or spammed reviews with high accuracy.

---

### 🚀 Features
- 🧩 Trains and evaluates multiple classification models using scikit-learn  
- 🧠 Implements a **stacked ensemble** combining Logistic Regression & Naïve Bayes  
- 💬 Utilizes **TF-IDF** for text vectorization and feature extraction  
- 🌐 Interactive **Streamlit interface** for real-time single or bulk review analysis  
- 📦 Deployable using **ngrok** for remote demo access  

---

### 🗂️ Dataset
- **Size:** 40,000 reviews (20K genuine, 20K AI-generated)  
- **Type:** Text-based, CSV format  
- **Processing:** Cleaned and preprocessed using Pandas and scikit-learn utilities  

---

### 🛠️ Tech Stack
`Python` • `scikit-learn` • `Pandas` • `NumPy` • `Streamlit` • `TF-IDF`

---

### 📊 Results
- ✅ Achieved **92.16% accuracy** on test data using the stacked ensemble  
- 🔍 Ensemble model outperformed individual base learners in precision and recall  
- 🧮 Reduced misclassification through text normalization and feature weighting  

---

### 🖼️ Demo
| Input Page | Prediction Output |
|-------------|------------------|
| ![Input Example](screenshots/input.png) | ![Output Example](screenshots/output.png) |

---

### 🧩 How to Run Locally
1. **Clone the Repository**
   ```bash
   git clone https://github.com/sudhee302/Fake-Review-Detection-using-Stacking-Ensemble
   cd Fake-Review-Detection-using-Stacking-Ensemble
