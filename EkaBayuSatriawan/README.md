# Logistic Regression Model Evaluation

This project evaluates a logistic regression model using different test sizes and maximum iteration values (max_iter). The ai4i2020 dataset from the UCI Machine Learning Repository is used for analysis.

## Steps Overview

1. Import Libraries: Essential libraries for data handling, modeling, and visualization are imported.
2. Load and Preprocess Data: The dataset is loaded and preprocessed by dropping irrelevant columns, encoding categorical features, handling missing values, and standardizing the data.
3. Define Model Evaluation Function: A function is defined to train and evaluate the logistic regression model with specified test size and max_iter, returning accuracy, precision, recall, and F1-score.
4. Evaluate Model for Different Test Sizes: The model is evaluated using various test sizes, and performance metrics are stored in a DataFrame.
5. Visualize Metrics with Heatmaps: Heatmaps are created to visualize model performance metrics across different test sizes and max_iter values.
6. Evaluate Model for Different max_iter Values: The model is further evaluated using different max_iter values, and results are recorded.
7. Display Classification Report and Confusion Matrix: The classification report and confusion matrix are displayed for a specified configuration (test_size = 0.3 and max_iter = 1000).

## Conclusion

This project demonstrates the evaluation of logistic regression models, emphasizing parameter tuning and performance visualization through heatmaps. It provides insights into model performance across various configurations and showcases the importance of parameter optimization in machine learning tasks.
