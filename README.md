# Assessment-Task-repo

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

**Time Taken**

**Approximately 3 hours including**

Data analysis
Feature engineering
Model development
Hyperparameter tuning
Documentation



