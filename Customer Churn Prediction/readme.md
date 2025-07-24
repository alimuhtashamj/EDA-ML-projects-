
---

## Steps Covered

- Loaded and cleaned the dataset  
- Performed exploratory data analysis (EDA)  
- Encoded categorical variables  
- Scaled the features  
- Trained a Logistic Regression model  
- Evaluated performance using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC Curve
- Interpreted model coefficients to understand feature impact

---

## Final Accuracy

The logistic regression model achieved:

**Accuracy**: Approximately 80%  
**Precision for Churn class**: Around 64%  
**Recall for Churn class**: Around 57%

This is a good starting point. Performance can be improved using more complex models.

---

## Key Insights

- Tenure, MonthlyCharges, and Contract type were among the most influential features.
- Customers with longer tenure or yearly contracts were less likely to churn.
- Month-to-month contract customers were more likely to churn.

---

## Tools Used

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Logistic Regression

---

## Next Steps (If Continued)

- Try advanced models (Random Forest, XGBoost)
- Implement cross-validation
- Deploy using Flask or Streamlit
- Build an interactive dashboard for predictions

---

## About Me

I'm learning machine learning through hands-on projects. This project helped reinforce key concepts in data preprocessing, model training, evaluation, and interpretation.

I welcome feedback and suggestions for improvement.

---
