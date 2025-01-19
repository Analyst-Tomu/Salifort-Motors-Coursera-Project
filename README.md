# Salifort-Motors HR Predictive Model Analysis

## Project Overview  
This project analyzes a dataset to build predictive models that can provide insights to the Human Resources (HR) department of a large consulting firm. By evaluating the dataset, we aim to predict key factors that influence employee retention and performance, offering valuable insights for strategic decision-making.

## Project Description and Deliverables  

The primary objective of this project is to analyze HR-related data and build predictive models that assist in employee management. We focus on evaluating different machine learning models, specifically a decision tree and logistic regression, to predict employee retention, performance, and key HR metrics.

### Deliverables:
- **Model Evaluation:** A detailed comparison between the decision tree model and the logistic regression model, including performance metrics such as F1 score, accuracy, precision, recall, and feature importance.
- **Data Visualizations:** Clear, insightful visualizations that highlight the trends, correlations, and significant patterns in the data.
- **Ethical Considerations:** Considerations around the data's use, fairness, and potential biases in the models.

## Methodology  

### Decision Tree Model:  
The decision tree model significantly outperforms the logistic regression model in multiple key areas:

- **F1 Score:** The decision tree achieves an impressive `94.35%` F1 score, far surpassing the logistic model’s `68.15%`.
- **Accuracy:** The decision tree provides a high `97.27%` accuracy, showcasing its reliability in predicting correct outcomes.
- **Precision:** With a precision score of `98.10%`, the decision tree excels at minimizing false positives.
- **Recall:** A recall score of `92.74%` demonstrates the model's ability to effectively identify positive cases.
- **Confusion Matrix:** The decision tree minimizes false negatives (type II errors), with only `70` incorrect predictions compared to `314` made by the logistic model.

### Grid Search Cross-Validation:  
Grid search cross-validation was employed to avoid overfitting, ensuring that the model’s performance is robust and generalizable across unseen data.

### Feature Importance:  
The decision tree also provided insights into the most important features influencing employee retention and performance. The top five factors identified are:
- Satisfaction Level
- Time Spent at the Company
- Workload
- Last Evaluation
- Number of Projects
- Average Monthly Hours

These insights provide valuable guidance for HR departments to focus on key metrics when evaluating employee performance and retention strategies.

## Technologies Used  
- **Programming Language:** Python  
- **Libraries:**  
  - `scikit-learn` (for machine learning models and evaluation metrics)  
  - `matplotlib` and `seaborn` (for data visualization)  
  - `pandas` (for data processing and manipulation)  
  - `numpy` (for numerical operations)

## Getting Started  

### 1. Clone the Repository  
Clone this repository to your local machine:  
