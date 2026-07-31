# Assessment-Task

**Technologies Used**

Programming
Python
Data Processing
Pandas
NumPy
Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-learn
XGBoost
Imbalanced-learn
Model Persistence
Joblib

## Project Workflow

1. Loaded and explored the dataset.
2. Performed data cleaning and preprocessing.
3. Performed feature engineering (created, transformed, or selected features)
4. Encoded categorical features and handled missing values.
5. Split the data into training and testing sets.
6. Trained three machine learning models:
   - Logistic Regression
   - Random Forest
   - XGBoost
7. Evaluated each model using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC
8. Compared model performance and selected the best-performing model.
9. Analyzed feature importance to identify the most influential features.
10. Saved the trained model for future predictions.

**Assumptions**
Historical customer behavior represents future churn patterns.
Available customer features contain meaningful information for prediction.
The dataset represents a realistic customer subscription environment.
Trade-offs and Decisions

**Why SMOTE?**

The dataset had fewer churn examples compared to non-churn customers. SMOTE was used to improve the model's ability to learn churn patterns.

*Why Tree-Based Models?*

Customer churn depends on complex interactions between features. Tree-based models such as Random Forest and XGBoost can capture nonlinear relationships effectively.


**Testing**

The notebook was tested by:

Running all cells sequentially
Validating preprocessing outputs
Comparing multiple models
Checking evaluation metrics
Saving and verifying model artifacts
Future Improvements

**With additional time, the following improvements could be added**

Cross-validation on all models
SHAP-based model explainability
Automated ML pipeline
Model monitoring
API deployment using FastAPI
Interactive dashboard using Streamlit
docker
git
githubactions ci/cd
aptuna
Cloud deployment

**Final Results**
Three machine learning models (Logistic Regression, Random Forest, and XGBoost) were trained and evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC. Random Forest achieved the best overall performance with 84.49% accuracy and an AUC of 0.8447, making it the selected model for the final solution.

**Time Taken**

**Approximately 3 hours including**

Data analysis
Feature engineering
Model development
Hyperparameter tuning
Documentation



