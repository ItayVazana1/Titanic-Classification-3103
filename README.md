# Titanic-Classification-3103

In this experiment, I applied a machine learning flow using various feature engineering techniques and model evaluations to predict the target variable.

The process involved several steps:

## Feature Engineering:

I created a new binned feature for age, calculated family size, and scaled the 'Fare' feature using MinMaxScaler.
The transformed dataset provided multiple versions for experimentation, allowing a comprehensive evaluation of feature impact.

## Model Selection and Hyperparameter Tuning:

I experimented with different machine learning models, including Gradient Boosting, Naive Bayes, SVM, Random Forest, Logistic Regression, and Decision Trees.
For each model, hyperparameter tuning was conducted using GridSearchCV to identify the best parameters.

## Model Evaluation:

The models were evaluated using cross-validation, and the F1 score was chosen as the primary performance metric due to its effectiveness in handling imbalanced datasets.
The best performing model was trained on the entire dataset, followed by evaluation on both training and test data.

## Results:

The best model was a Gradient Boosting Classifier with specific hyperparameters to prevent overfitting. The model was tested on both training and test datasets to assess its generalization.
The final evaluation metrics, including the F1 score and the classification report, were analyzed to gauge the model's effectiveness.
