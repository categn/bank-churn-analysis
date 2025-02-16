# bank-churn-analysis
Project developed for the course Laboratory of Data Analysis for Banking and Insurance

The goal of the project is to predict customer churn in a bank using a dataset containing information about a bank customers. We developed an end-to-end Machine Learning pipelines using SAS Model Studio. We implemented 5 Machine Learning Models that predict customer churn and determine the best performing between Logistic Regression, Decision Tree, Gradient Boosting, Random Forest, and Neural Network. The following steps were implemented:
- Create a basic pipeline to ensure clean and structured data: perform Exploratory Data Analysis, Replacement, Variable Management, and Transformation
- Implement different Logistic Regressions and assess the performance using the KS Youden, Accuracy, AUC, Cumulative Lift, F1 Score, Classification Error
- Implement Decision Tree with different hyperparameters (splitting criteria, maximum depth, minimum leaf size, number of branches) and assess the performance 
- Implement Gradient Boosting with different hyperparameters (number of trees, learning rate, regularization, number of continuous groupings) and assess the performance 
- Implement Random Forest with different hyperparameters (splitting criteria, number of trees) and assess the performance
- Implement a Neural Network with different hyperparameters (number of hidden layers, standardization, activation function) and assess performnance
- Find the best model for classification 

## Files
- `churn.csv` – dataset used for the analysis 
- `LAB_Bank_presentation.pdf` – final presentation of the project

## Tools used
- **Programming**: SAS Model Studio, SAS Viya
- **Machine Learning**: Logistic Regression, Decision Tree, Gradient Boosting, Random Forest, Neaural Network
