# Customer Churn & Retention Analytics

An end-to-end Machine Learning project that identifies customer churn drivers and builds a predictive engine to retain at-risk accounts.

## 📌 Project Overview
Customer churn is a critical operational metric for recurring business models. This repository provides data preprocessing, exploratory analysis, and predictive modeling using XGBoost to detect churn probability and offer business recommendations.

## 📊 Dataset Link
- **Kaggle Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🛠️ Technologies Used
- **Language:** Python 3.10+
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn, XGBoost
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 🚀 Setup & Execution Instructions

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/your-username/customer-churn-analytics.git
   cd customer-churn-analytics
   ```

2. **Install Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook Student_ProjectName.ipynb
   ```

## 📈 Key Results & Findings
- **Predictive Performance:** Achieved an ROC-AUC score > 0.82 across cross-validated test splits.
- **Primary Churn Drivers:** Month-to-month contracts and high customer support ticket volumes (>4 tickets) significantly increase churn probability.
