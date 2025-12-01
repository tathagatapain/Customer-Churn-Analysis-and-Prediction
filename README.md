# Customer Churn Analysis and Prediction with Model Deployment

This repository contains the code and documentation for a project that analyzes customer churn data and builds a predictive model to identify potential churners. The project also includes a model deployment component that allows the model to be used to make predictions on new data.

# Project Overview

Customer churn is a significant problem for businesses, as it can lead to lost revenue and increased customer acquisition costs. By analyzing customer data, businesses can identify patterns and trends that can help them predict which customers are at risk of churning. This information can then be used to develop targeted interventions to retain these customers.

This project aims to build a predictive model to identify potential churners using a dataset of customer data. The model will be trained on historical data and then used to make predictions on new data. The project also includes a model deployment component that allows the model to be used to make predictions in a real-world setting.

# Data Analysis

The first step in the project was to perform exploratory data analysis (EDA) on the customer data. This involved examining the distribution of variables, identifying missing values, and exploring relationships between variables. The EDA helped to identify key features that could be used to predict churn.

# Model Development

After performing EDA, the next step was to develop a predictive model. Two machine learning algorithms, decision trees and random forests, were used to build the models. To improve the performance of the models, the SMOTE (Synthetic Minority Oversampling Technique) was used to address the class imbalance in the data. Additionally, principal component analysis (PCA) was used to reduce the dimensionality of the data before fitting the models.

# Model Evaluation

The performance of the models was evaluated using a variety of metrics, including accuracy, precision, recall, and F1-score. The results of the evaluation showed that the models were able to accurately predict churn with a high degree of confidence.

# Model Deployment

The final step in the project was to deploy the model to a production environment. This involved using the Flask web framework to create a web application that allows users to input customer data and receive predictions about their churn risk.

# Instructions

To run the project, follow these steps:

* Clone the repository to your local machine.
* Create a virtual environment and install the required dependencies using the requirements.txt file.
* Run the data analysis notebook (data_analysis.ipynb) to explore the data and identify key features.
* Run the model development notebook (model_development.ipynb) to train and evaluate the predictive models.
* Run the model deployment notebook (model_deployment.ipynb) to deploy the model to a web application.
