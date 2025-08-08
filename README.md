# 💳 Credit Card Fraud Detection

This repository presents a machine learning pipeline built with **PySpark** to detect fraudulent credit card transactions. The project uses scalable data processing and classification techniques to identify potential fraud in transactional data.


### 🔗 Download Datasets

[![Download Dataset](https://img.shields.io/badge/Download-Data-brightgreen?style=for-the-badge)](https://drive.google.com/file/d/15Ppn7rdjpxe0FnnOBX2gP9Itd1Fnl1sG/view?usp=sharing)

## 📁 Files Included

- `credit_card_fraud_detection.ipynb` — Full notebook with preprocessing, model training, and evaluation
- `summary_and_findings.pdf` — Final report summarizing insights and model performance
- `README.md` — Project overview and repository guide

## 🔍 Key Insights

- **Model**: Logistic Regression and Random Forest
- **AUC Score**: 0.9663 — Excellent discrimination between fraud and non-fraud
- **Recall (Fraud Class)**: ~60.1% — Indicates moderate detection of fraud
- **False Negatives**: 6,950 — Needs improvement to reduce missed fraud cases
- **Class Imbalance**: Major challenge — future work can involve resampling and cost-sensitive learning

## 📘 Technologies Used

- Python (Jupyter Notebook)
- PySpark
- scikit-learn
- Matplotlib & Seaborn

## 📈 Visualizations

Includes:
- ROC Curve
- Precision-Recall Curve
- Confusion Matrix
- Feature Importance Plot

## 📄 Report

Read the detailed analysis in: `summary_and_findings.pdf`

## 👤 Author

**Vishnu B**  
MSc Data Science Student  

---


