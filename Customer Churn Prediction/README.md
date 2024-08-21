# Customer Churn Prediction

## Overview

This project involves developing a predictive model to identify customers likely to churn from a subscription-based service or business. By leveraging historical customer data, including usage behavior and demographics, the model helps in predicting which customers are at risk of leaving. The Logistic Regression algorithm was used to build this predictive model.

## Table of Contents

- [Dataset](#dataset)
- [Modeling Techniques](#modeling-techniques)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)

## Dataset

The dataset used for this project includes historical customer data, featuring variables such as:

- **Customer Demographics**: Age, gender, income level, etc.
- **Usage Behavior**: Frequency of service use, duration of subscription, etc.
- **Subscription Details**: Subscription type, payment method, etc.

This dataset can be sourced from a company's internal database or publicly available datasets.

## Modeling Techniques

### 1. Data Preprocessing

- Handling missing values
- Encoding categorical variables
- Feature scaling

### 2. Feature Selection

- Identifying the most significant features contributing to churn prediction using techniques like correlation analysis and feature importance.

### 3. Classification Algorithm

- **Logistic Regression**: A statistical model that estimates the probability of a binary outcome (in this case, churn or no churn) based on one or more predictor variables. Logistic Regression was chosen for its simplicity and interpretability.

## Evaluation

The model was evaluated using several performance metrics, including:

- **Accuracy**: The proportion of correct predictions out of all predictions.
- **Precision**: The number of true positive predictions divided by the total number of positive predictions.
- **Recall**: The number of true positive predictions divided by the total number of actual positive cases (churned customers).
- **F1 Score**: The harmonic mean of precision and recall, providing a balance between the two.

Cross-validation was used to assess the model's generalizability and to fine-tune the model's hyperparameters.

## Results

The Logistic Regression model achieved the following results:

- **Accuracy**: [Your accuracy result here]%
- **Precision**: [Your precision result here]%
- **Recall**: [Your recall result here]%
- **F1 Score**: [Your F1 score result here]

These results demonstrate the model's effectiveness in predicting customer churn, helping the business take proactive measures to retain customers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
