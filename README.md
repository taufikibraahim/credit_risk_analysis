# 💳 Credit Risk Analysis
### Prediksi Risiko Gagal Bayar dengan Machine Learning

---

## 📌 Overview
Project ini menganalisis data nasabah kredit untuk 
memprediksi kemungkinan gagal bayar menggunakan 
algoritma Machine Learning. Tujuannya adalah membantu 
lembaga keuangan membuat keputusan kredit yang lebih 
akurat dan meminimalkan risiko kredit macet.

---

## 🎯 Business Problem
Sebuah lembaga keuangan ingin:
- Memprediksi apakah nasabah akan **gagal bayar** 
  atau **tidak**
- Mengidentifikasi **faktor utama** yang mempengaruhi 
  risiko kredit
- Membuat **strategi mitigasi risiko** berbasis data

---

## 🛠️ Tools & Libraries
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib,
  Seaborn, Scikit-learn
- **Environment:** Jupyter Notebook

---

## 📊 Dataset
- **Source:** German Credit Risk Dataset 
  (Kaggle — kabure/german-credit-data-with-risk)
- **Size:** 1,000 nasabah, 10 fitur asli
- **Target:** Risk (good=0, bad=1)
- **Distribusi:** 70% Good, 30% Bad

---

## 🔍 Methodology

### 1. Data Understanding
- 1,000 nasabah × 10 kolom
- Distribusi target: 70% Good, 30% Bad
- Missing values di Saving & Checking account

### 2. Data Preprocessing
- Handle missing values → fillna('unknown')
- Label Encoding untuk ko
