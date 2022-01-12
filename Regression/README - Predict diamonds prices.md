Problem statement:
Predict the price of diamonds given diamonds typical's attributes (carat, cut, color, etc)
Dataset taken from https://www.kaggle.com/shivam2503/diamonds, consisting of:
53940 rows and 10 features

Project Pipeline:
- Collect data
- EDA
- Model selection and hyperparameter turning (GridSearch CV)
  - Start with Linear Regression
  - Compare other regressors' performance: Ridge, Lasso, SVR, Decision Tree, Random Forest and XGBoost
  - Use Cross-validation for model selection
- Run best models on unseen data
