#  Titanic Survival Prediction – EDA + Machine Learning

This project explores the famous Titanic dataset to predict which passengers were more likely to survive.
 Using exploratory data analysis (EDA) and a simple logistic regression model, I uncovered patterns in the data, trained a model, and evaluated its performance — all while learning to visualize and interpret results clearly.

---

##  Project Objectives

- Understand the factors influencing survival
- Use Seaborn and Matplotlib for visualizations
- Cleaning the data
- Train a Logistic Regression model to predict survival
- Evaluate predictions using accuracy and error analysis

---

##  Key Questions Explored

I used visual EDA for the following

1. **Does gender affect survival?**  
    Yes, females had a significantly higher survival rate.

2. **Does passenger class (1st/2nd/3rd) play a role?**  
   First-class passengers had the highest survival rate, third-class the lowest.

3. **Is age a factor?**  
   Children were more likely to survive. Elderly passengers had the lowest survival rate.

4. **Did paying more help you survive?**  
   Yes. On average, passengers who paid higher fares had better survival odds.

---

## Libraries Used

- Python
- Pandas
- Seaborn & Matplotlib 
- Scikit-learn



## Data Cleaning Summary

- Dropped irrelevant or redundant columns: `deck`, `embark_town`, `alive`, `who`, etc.
- Removed rows with missing values in crucial features like `age`, `embarked`
- Converted categorical features (`sex`, `embarked`) to numeric
- Selected useful features based on EDA insights:
  - `pclass`, `sex`, `age`, `fare`, `embarked`

---

## Machine Learning Model

I used a **Logistic Regression** model to predict the `survived` column.

### Model Evaluation:
- Accuracy Score: ~78%
- Confusion Matrix: Visualized to spot false positives/negatives
- Classification Report: Precision, Recall, F1-score

---

## Insights from Error Analysis

After comparing **actual vs. predicted**, I found:
- The model sometimes **struggles with older 3rd class males**.
- Visualizations showed that **age and class together** impact the model's accuracy.
- These insights point to **potential model improvement** using more advanced techniques (e.g., Decision Trees or Ensembles).
                   
