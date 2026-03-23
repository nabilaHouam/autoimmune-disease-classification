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

The model relies mainly on inflammation markers (CRP, ESR),  
highlighting the difficulty of distinguishing diseases with overlapping biological profiles.

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

## 📂 Files

- `projet_final_1.ipynb` → full analysis and model

---

## 🔬 Source

Mahdi, M. F., Jahani, A., & Abd, D. H. (2025)  
Diagnosis of rheumatic and autoimmune diseases dataset  
Data in Brief
