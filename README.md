# 🧬 Autoimmune Disease Classification using Machine Learning
🚀 Machine learning project applied to real-world clinical data (12,000+ patients)

👉 Can biological markers alone distinguish between autoimmune diseases?

## 🎯 Objective

Build a machine learning model to classify autoimmune and rheumatic diseases using clinical biomarkers.

---

## 📊 Dataset

This project uses a real-world medical dataset of 12,085 patients.

It includes:
- Inflammation markers (CRP, ESR)
- Autoantibodies (RF, Anti-CCP, ANA, Anti-Ro, Anti-La, Anti-dsDNA, Anti-Sm)
- Demographic data (Age, Gender)

The dataset is designed for early diagnosis of autoimmune diseases.

---

## 🔍 Methodology

- Missing data analysis (Chi-square + predictor analysis)
- Imputation using MICE (BayesianRidge)
- One-hot encoding of categorical variables
- Random Forest model

---

## 📈 Results

- Accuracy ≈ 85%
- Strong performance for:
  - Rheumatoid Arthritis
  - Systemic Lupus Erythematosus

- More difficult classification for:
  - Ankylosing Spondylitis
  - Reactive Arthritis

---

## 🧠 Key Insight

The model relies heavily on general inflammation markers (CRP, ESR),  
rather than disease-specific biomarkers.

👉 This reveals a key limitation:

Different autoimmune diseases often share overlapping biological profiles,  
making accurate classification inherently difficult.

This mirrors real-world clinical challenges in diagnosis.

---

## ⚠️ Limitations

- Biomarkers alone are not sufficient for perfect diagnosis
- Imputation may reduce variability
- No external validation dataset

---

## 📌 Conclusion

Machine learning can support diagnosis,  
but cannot replace clinical reasoning.

---
## 💡 Why This Project Matters

Autoimmune diseases are difficult to diagnose due to:
- overlapping symptoms
- lack of highly specific biomarkers
- variability across patients

This project shows how machine learning can help —  
but also highlights its current limitations in real clinical settings.

---
## 📂 Files

- `projet_final_1.ipynb` → full analysis and model

---

## 🔬 Source

Mahdi, M. F., Jahani, A., & Abd, D. H. (2025)  
Diagnosis of rheumatic and autoimmune diseases dataset  
Data in Brief
