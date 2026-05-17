* Built a credit risk default prediction project on a real-world banking dataset of around 2.5 GB by working with 7+ connected CSV files containing customer, loan, bureau, and repayment data.
* Handled complex relational data where one customer could have multiple previous loans, bureau records, and installment histories, and merged/aggregated them into a usable ML dataset.
* Created 45+ custom features related to repayment behavior, overdue amounts, debt ratios, approval/refusal history, active loans, and payment delays to improve prediction quality.
* Trained and compared Logistic Regression, Random Forest, and XGBoost models, and repeatedly checked ROC-AUC scores across many experiments to understand what was actually improving the model.
* Improved model performance from basic baseline models to around 0.77 ROC-AUC through feature engineering, debugging, and behavioral pattern analysis instead of blindly tuning models.
* Built proper preprocessing pipelines using Scikit-learn Pipeline and ColumnTransformer for missing values, encoding categorical columns, scaling numerical data, and preventing data leakage.
* Used Stratified K-Fold cross-validation on imbalanced banking data to get more reliable evaluation results instead of depending on a single train-test split.
* Solved practical issues during development such as dataframe fragmentation, NaN/infinity errors, parquet saving issues, pipeline mismatches, multiprocessing problems, and large dataframe handling.
* Gained practical understanding of banking and lending data, including customer repayment behavior, overdue risk, credit exposure, and default prediction patterns while building the project.
* Used Git and GitHub to track experiments, manage project versions, and maintain a structured machine learning workflow.
