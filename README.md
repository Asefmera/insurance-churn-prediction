# Insurance Customer Churn Prediction

This project focuses on predicting customer churn for an insurance company. The main challenge was the high class imbalance,
which was addressed using advanced gradient boosting techniques.

## Key Highlights
- **Exploratory Data Analysis (EDA):** Identified key drivers of churn such as tenure and financial metrics.
- **Handling Imbalance:** Optimized the model using `scale_pos_weight` to focus on minority class (churners).
- **Model Benchmarking:** Compared Logistic Regression, Random Forest, and XGBoost.
- **Final Result:** Achieved a **Recall of 0.85** with XGBoost, identifying 85% of at-risk customers.

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Visualization: Seaborn, Matplotlib
- Machine Learning: XGBoost, Scikit-learn

## 📊 Feature Importance
The model identified **Feature_13** and **Feature_3** as the most significant predictors of customer behavior.

## 📁 Project Structure
- `Customer_Behavior_Analysis.ipynb`: Main analysis and modeling notebook.
- `requirements.txt`: List of necessary Python libraries.
- `data/`: Dataset files (Train/Test).

---
*Developed for Data Science Portfolio.*
