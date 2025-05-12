# Credit Card Default Risk Analysis

This repository contains an exploratory data analysis (EDA) and predictive modeling project based on the "Default of Credit Card Clients Dataset." The goal of this analysis is to uncover key patterns and trends that influence customer default risk and to build classification models that can predict defaults based on customer attributes.

## 📊 Dataset Overview

The dataset comes from the UCI Machine Learning Repository and contains demographic and financial attributes of 30,000 credit card clients in Taiwan from April to September 2005. The key target variable is whether a client defaulted on their payment the next month.

- Instances: 30,000
- Features: 23
- Target: `default.payment.next.month` (1 = default, 0 = non-default)

## 🧠 Project Objectives

- Perform exploratory data analysis (EDA) using visualizations.
- Analyze trends in credit limits, payment history, education, marital status, and default behavior.
- Prepare data for machine learning: encoding, normalization, and feature selection.
- Train and evaluate multiple classification models (Logistic Regression, Decision Tree, etc.).
- Interpret model performance and suggest actionable insights.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn

## 📁 File Structure

- `Credit Card Clients.ipynb` – The main notebook containing data loading, EDA, and modeling steps.
- `data/` – (Optional) Directory to place raw or cleaned datasets.
- `README.md` – Project overview and instructions.

## 📈 Key Insights

- Higher default rates observed among clients with lower credit limits.
- Bill statement history and recent payment status are strong predictors of default.
- Certain demographic groups exhibit distinct payment behaviors.

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-default-risk-analysis.git
