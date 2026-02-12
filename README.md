
# 📊 Customer Churn Prediction — SyriaTel

## 🔎 Project Overview
Customer churn represents a direct revenue risk for telecommunications companies. This project aims to predict which customers are likely to leave (churn) so the business can take proactive retention actions.

By identifying at-risk customers early, the company can improve customer retention, reduce revenue loss, and allocate resources more effectively.

---

## 🎯 Business Objective
- Identify customers likely to churn
- Enable proactive retention strategies
- Reduce revenue loss and operational costs
- Support data-driven decision-making

---

## 📁 Dataset Summary
- Total test samples: **667**
- Non-churn customers: **570**
- Churn customers: **97**
- Dataset is imbalanced (minority churn class)

---

## 🧠 Models Evaluated
1. Logistic Regression (baseline)
2. Random Forest (tuned)
3. XGBoost (final model)

---

## 📈 Model Performance Comparison

| Metric | Logistic Regression | Random Forest | XGBoost |
|--------|--------------------|---------------|---------|
| Accuracy | 85.9% | 92–93% | **94.1%** |
| Churn Recall | 24% | 64–79% | **78%** |
| Churn Precision | 53% | 71–86% | **81%** |
| Churn F1-score | 0.33 | 0.73–0.75 | **0.80** |

---

## 🏆 Final Model: XGBoost

### Key Results
- **Accuracy:** 94%
- **Churn Recall:** 78%
- **Churn Precision:** 81%
- **F1-score:** 0.80

### Business Impact
- Detects most at-risk customers
- Significantly reduces missed churn cases
- Maintains low false alarms
- Enables targeted retention campaigns

---

## ⚙️ Key Techniques Used
- Handling class imbalance (`scale_pos_weight`, class weighting)
- One-hot encoding for categorical variables
- Hyperparameter tuning
- Threshold optimization
- Model comparison and evaluation

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC AUC
- Confusion Matrix

---

## 📌 Conclusion
Transitioning from Logistic Regression to XGBoost significantly improved churn detection. The final model achieves 94% accuracy and identifies 78% of churn cases, providing strong business value and supporting proactive customer retention strategies.

---

## 🚀 Future Improvements
- Deploy model with real-time scoring
- Monitor performance drift
- Incorporate additional behavioral features
- Experiment with advanced ensemble techniques

---

## 👤 Author
Isaac Macharia
