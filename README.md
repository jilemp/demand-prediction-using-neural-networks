# 📦 Demand Forecasting with Neural Networks

This repository presents a final project focused on **predicting demand** for machinery components using machine learning techniques, with a primary emphasis on **neural networks**. Developed as part of the 4Geeks Academy Data Science & ML program, this project demonstrates how advanced models can optimize inventory and reduce costs.

---

## 📁 Project Contents

```bash
├── project_notebook.ipynb       # Full notebook with preprocessing, modeling, and evaluation
├── Predicción_de_Demanda.pdf    # Final project report (Spanish)
├── data/                        # (Optional) Input datasets used for modeling
├── README.md                    # Project overview and instructions
```

---

## 🧠 Problem Context

The company:
- Based in Ecuador, supplies machinery parts to the food industry.
- Sources products globally (Asia & Europe), with long shipping times.
- Seeks to optimize inventory by **predicting demand** based on internal and external variables.

---

## 📊 Data Overview

- 📅 **Historical Range**: 2021–2024
- 🛍 **SKU Count**: 1,105 unique items
- 📄 **Transactions**: 3,605 total
- 💡 Includes: sales, purchases, product types, and macroeconomic factors like:
  - Brent Oil Price
  - Ecuador’s CPI
  - Ecuador’s GDP

---

## 🔍 Methodology

- **ML Approach**: Neural Networks using `MLPRegressor`
- **Architecture**:
  - 8 hidden layers with 100 neurons each
  - Activation: ReLU
  - Optimizer: LBFGS
  - Tuning: GridSearch & Cross Validation

📈 **Other models tested**: Logistic Regression, AdaBoost, KNN, SVC, Random Forest

---

## 📌 Results

- 🔍 **MAE**: 12.39
- 🎯 **Impact**:
  - Reduced overstock
  - Improved forecasting accuracy
  - Inventory optimization

---

## 📈 Future Improvements

- Add seasonality, promotions, competition, and currency exchange rate data.
- Enhance feature engineering and experiment with alternative model architectures.
- Implement automated model retraining for dynamic inventory environments.

---

## 🚀 Getting Started

### Prerequisites

Install dependencies:

```bash
pip install -r requirements.txt
```

### Run the notebook

```bash
jupyter notebook project_notebook.ipynb
```

---

## 📚 References

- Investing.com – Brent Oil Prices (2021–2024)
- Trading Economics – Ecuador GDP & CPI
- Scikit-learn documentation for MLPRegressor

---

## 👥 Authors

- Alfonzo Gonzalez
- Andrés Cabrales
- José Ignacio Ibarra

---

🎓 Developed as part of the [4Geeks Academy – Data Science & Machine Learning Program](https://4geeksacademy.com)

