# 💰 Loan Eligibility Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Classification-orange?style=flat-square&logo=scikit-learn)
![Model](https://img.shields.io/badge/Model-Deployed%20.pkl-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> ML pipeline that predicts loan approval outcomes — automating lending risk assessment using classification models, with the trained model exported for reuse.

> **Legacy / Learning Project.** One of my early ML notebooks, kept public as a record of the learning path (classic scikit-learn pipelines, EDA, model comparison). Superseded in portfolio terms by the shipped risk/fraud/governance systems in [Jeevan-0508](https://github.com/Jeevan-0508) — this repo is archived, not deleted.

## 📌 Problem Statement
Manual loan evaluation is inconsistent and slow. This project automates the eligibility decision using a trained classifier that assesses applicant risk from demographic and financial features, then exports a deployment-ready `.pkl` model.

## 🎯 Key Objectives
- Binary classification: Approved ✅ / Rejected ❌
- Identify top risk factors driving loan decisions
- Export trained model for downstream deployment
- Compare multiple classification algorithms

## 🔬 Models Compared
| Model | Notes |
|-------|-------|
| Logistic Regression | Interpretable baseline |
| Decision Tree | Rule-based explainability |
| Random Forest | Best accuracy |
| K-Nearest Neighbours | Distance-based comparison |

## 📦 Key Files
| File | Description |
|------|-------------|
| `loan-eligibility-prediction-machine-learning.ipynb` | Full EDA + training pipeline |
| `logistic_model.pkl` | Saved production-ready model |

## 🛠️ Tech Stack
`Python` · `pandas` · `scikit-learn` · `pickle` · `matplotlib` · `Jupyter`

## 📊 Top Features by Importance
1. **Credit History** ⭐ — strongest predictor
2. Applicant + Co-applicant Income
3. Loan Amount & Term
4. Property Area
5. Education & Employment Status

## 🚀 Run Locally
```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook "loan-eligibility-prediction-machine-learning.ipynb"
```

## 🔗 Relevance to Risk Management
Loan eligibility models are foundational to credit risk management — the same ML framework underlies fraud risk tiering, insurance underwriting, and regulatory credit decisioning.

---
*Jeevan Siddhabhaktula · Risk & Data Science Portfolio*
