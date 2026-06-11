Task 1:
repeat_purchase_flag :This is the label because it contains the result that the model is trying to predict. A value of 1 means the customer made a repeat purchase within 30 days, and a value of 0 means they did not. Therefore, it serves as the target variable in the machine learning model.
discount_used_on_repeat_order:This information is only available after the repeat purchase occurs, so using it as a feature would reveal future information and cause data leakage.
Task 2:
Step 1: Data Exploration and Data Quality Checks
Before training a model, the dataset should be examined for missing values, incorrect data types, outliers, and inconsistencies to ensure the data is reliable and suitable for modeling.
Step 2: Train-Test Split and Baseline Model Creation
The data should be split into training and testing sets, and a simple baseline model should be established first to provide a benchmark for evaluating whether a more complex gradient boosting model actually improves performance.
