# 📉 US Company Bankruptcy Prediction with Machine Learning

## 📌 Business Problem
Financial distress and bankruptcy pose serious risks to investors, lenders, and regulatory bodies. Early identification of at‑risk companies helps stakeholders take proactive actions to mitigate losses and improve decision-making processes.

---

## 🎯 Objective
Build a machine learning model that predicts the likelihood of bankruptcy for U.S. companies using financial indicators and performance data. The goal is to support stakeholders in identifying at‑risk firms before financial deterioration becomes irreversible.

---

## 📍 Data & Approach

### 📊 Data Description
- Financial ratios and key performance indicators for U.S. companies  
- Variables include profitability, liquidity, leverage, and operational efficiency metrics  
- Target label indicates bankruptcy status

### 🛠 Methodology
1. **Data Preprocessing**  
   - Impute missing values and normalize financial features  
   - Identify and handle outliers

2. **Feature Engineering**  
   - Derived ratio features to capture operational and financial risk signals  
   - Correlation analysis to prioritize informative predictors

3. **Model Training & Evaluation**  
   - Tested classification models (e.g., Logistic Regression, Random Forest, XGBoost)  
   - Evaluated using accuracy, precision, recall, and ROC-AUC metrics

4. **Model Interpretation**  
   - Feature importance reveals key risk drivers  
   - Misclassification analysis highlights performance limitations

---

## 📈 Key Insights

- **Profitability & Leverage:** Lower profitability and higher leverage ratios are strong predictors of bankruptcy.  
- **Liquidity Signals:** Companies with strained liquidity metrics are more likely to experience financial distress.  
- **Feature Importance:** Certain financial ratios consistently rank high across models as significant risk indicators.

---

## 💡 Business Recommendation

- **Risk Monitoring:** Financial institutions and investors can integrate the model into risk monitoring dashboards to flag high‑risk firms.  
- **Portfolio Adjustment:** Investors may adjust portfolio exposure based on predicted bankruptcy risk.  
- **Decision Support:** Analysts can prioritize due diligence on flagged companies to inform strategic decisions.

---

## 🧰 Tools & Techniques
- Python (Pandas, Scikit‑Learn, XGBoost)
- Feature Engineering & Data Preprocessing
- Classification Models & Model Evaluation
- ROC‑AUC and Feature Importance Analysis

---
🔗 **Full Code & Notebook**  
https://github.com/lilasu086/US-Company-Bankruptcy-Prediction-with-Machine-Learning
