# Customer Churn Prediction

[View the Jupyter Notebook](./Customer_Churn_Prediction.ipynb)

## 📊 Dataset
- **Source:** [Kaggle / Internal Database]
- **Description:** This dataset contains historical records of customers, including demographics, account information, and service usage. The target variable is `Churn` (whether the customer left the company or not).
- **Size:** [Number of rows] rows x [Number of columns] columns.

## 🔬 Methodology
1. **Data Preprocessing:** Handled missing values, encoded categorical variables, and scaled numerical features.
2. **Exploratory Data Analysis (EDA):** Analyzed feature correlations and visualizations to identify factors strongly correlated with churn.
3. **Modeling:** Trained and evaluated several machine learning models including Logistic Regression, Random Forest, and XGBoost.
4. **Hyperparameter Tuning:** Used Grid Search / Random Search to optimize the best performing model.

## 🏆 Hasil (Results)
- **Best Model:** XGBoost Classifier.
- **Performance:** Achieved an Accuracy of 85% and an F1-Score of 82%.
- **Key Insights:** Found that month-to-month contracts and high monthly charges were the strongest predictors of churn.
