# ML Model for Profit Prediction of Companies
This repository contains code in Python for constructing and comparing different regression algorithms to predict the profit value of a company based on its R&D Spend, Administration Cost, and Marketing Spend.

# Dataset
The dataset used in this project consists of 50 companies' information, including their R&D Spend, Administration Cost, Marketing Spend, and the corresponding profit earned. The goal is to develop a machine learning model that can accurately predict the profit of a company given its R&D Spend, Administration Cost, and Marketing Spend.

# Regression Algorithms
Several regression algorithms were implemented and compared to determine the best model for profit prediction. The algorithms used are:

Linear Regression
Decision Tree Regression
Random Forest Regression
Support Vector Regression
Gradient Boosting Regression
Each algorithm was trained on the provided dataset to learn the relationship between the input variables (R&D Spend, Administration Cost, Marketing Spend) and the target variable (Profit).

# Train-Test Split
To evaluate the performance of the regression models, the dataset was divided into a training set and a test set. The training set was used to train the models, while the test set was used to assess their predictive accuracy. The data split was performed using a predefined ratio (e.g., 80% training and 20% testing).

# Regression Metrics
Different regression metrics were calculated to evaluate the performance of each model. The metrics used include:

Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R-squared (R2) score
These metrics provide insights into the accuracy and reliability of the models in predicting the profit values.

# Best Model Selection
After comparing the performance of the different regression algorithms based on the calculated metrics, the model with the best performance was chosen. The selection was based on minimizing the error metrics (MSE, RMSE, MAE) and maximizing the R-squared (R2) score.

# Conclusion
The chosen model provides a reliable prediction of the profit value for a company based on its R&D Spend, Administration Cost, and Marketing Spend. This repository includes the Python code used to implement and compare the regression algorithms, as well as the evaluation of their performance.

Feel free to explore the code and dataset to understand the details of the ML model and its predictions.




