# ML_Capstone_Project
Documentation
documentation = """
Dentistry Dataset Analysis and Model Building

1. Raw Data Collection
- Dataset: Dentistry.csv (1100 records, 14 features)
- Removed unnecessary columns: "Sl No", "Sample ID"
- Handled missing values using mean imputation.

2. Data Preprocessing
- Encoded categorical variable "Gender".
- Normalized numerical features.

3. Exploratory Data Analysis
- Heatmap for correlation analysis.
- Removed highly correlated independent variables.

4. Model Building
- Implemented Logistic Regression, Decision Tree, Random Forest, and XGBoost.
- Split data into 80% training and 20% testing.

5. Model Evaluation
- Logistic Regression performed best.
- Confusion Matrix and ROC curve plotted.

6. Conclusion
- Logistic Regression was the best model for predicting "Gender".
- Future improvements: Try hyperparameter tuning and feature engineering.
