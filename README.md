# 🩺 Diabetes Early Stage Classification

## 📖 Project Overview
Project ini bertujuan untuk melakukan klasifikasi penyakit Diabetes tahap awal berdasarkan gejala klinis pasien menggunakan Machine Learning.

Dataset berisi informasi gejala seperti Polyuria, Polydipsia, Weakness, dan lainnya yang diklasifikasikan menjadi:

- Positive (Terindikasi Diabetes)
- Negative (Tidak Diabetes)

---

## 📂 Dataset Information

Dataset terdiri dari 17 fitur:

### 🔢 Numerical Feature
- Age

### 🔤 Categorical Features (Yes/No)
- Gender
- Polyuria
- Polydipsia
- Sudden Weight Loss
- Weakness
- Polyphagia
- Genital Thrush
- Visual Blurring
- Itching
- Irritability
- Delayed Healing
- Partial Paresis
- Muscle Stiffness
- Alopecia
- Obesity

### 🎯 Target Variable
- class (Positive / Negative)

---

## 🤖 Machine Learning Methods
Model yang digunakan dalam project ini:

- K-Nearest Neighbor (KNN)
- Decision Tree
- Random Forest

---

## ⚙️ Data Preprocessing
- Encoding categorical (Yes/No → 1/0)
- Train-test split
- Feature scaling (jika diperlukan)

---

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

---

## 🚀 How to Run

```bash
git clone https://github.com/salmanafaris03/Diabetes_Classification.git
cd Diabetes_Classification
pip install -r requirements.txt
jupyter notebook
