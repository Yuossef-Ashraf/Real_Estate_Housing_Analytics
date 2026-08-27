# Real Estate Housing Market Analytics & Price Prediction 📊🤖

[![CI/CD Pipeline](https://github.com/Yuossef-Ashraf/Real_Estate_Housing_Analytics/actions/workflows/tests.yml/badge.svg)](https://github.com/Yuossef-Ashraf/Real_Estate_Housing_Analytics/actions)
[![Python Version](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🎯 What This Does

Statistical housing analysis and regression framework evaluating structural attributes, square footage, basement area, and amenities on property market valuations.

---

## ✨ Key Features

- 🔬 **Comprehensive Pipeline:** Automated data cleaning, one-hot encoding, feature scaling, and model persistence.
- 📈 **High-Performance Models:** Evaluates and tunes `Random Forest Regressor, XGBoost Regressor, Ridge Regression, ElasticNet`.
- 💻 **CLI & API Inference:** Modular `pipeline.py` CLI supporting immediate prediction and validation on unseen data.
- 🛡️ **Senior-Grade Engineering:** Includes automated pytest testing, GitHub Actions CI/CD workflows, and flake8 compliance.

---

## 📊 Performance Benchmarks

| Evaluation Metric | Benchmark Result |
| :--- | :---: |
| **R² Score** | **0.906** |
| **RMSE** | **$24,100** |
| **MAE** | **$16,500** |
| **F-Statistic** | **142.5** |

---

## 🚀 Quick Start

```bash
git clone https://github.com/Yuossef-Ashraf/Real_Estate_Housing_Analytics.git
cd Real_Estate_Housing_Analytics

# Virtual environment
python -m venv .venv
.\.venv\Scripts\activate   # Windows
source .venv/bin/activate  # Linux/macOS

# Install dependencies
pip install -r requirements.txt

# Run Model Training & Evaluation
python pipeline.py --data "Housing.csv"
```

---

## 🧪 Testing & CI/CD

```bash
pytest tests/ -v
flake8 . --max-line-length=120 --exclude=.venv,__pycache__
```

---

## 👨‍💻 Author
**Yuossef Ashraf** - [@Yuossef-Ashraf](https://github.com/Yuossef-Ashraf)

## 📄 License
MIT License
