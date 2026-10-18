# Customer Churn Prediction

## Project Overview
This project predicts whether a telecommunications customer is likely to leave the company using machine learning.

## Objectives
- Analyze customer data to identify churn patterns.
- Preprocess data and perform exploratory data analysis (EDA).
- Train and compare machine learning classification models.
- Evaluate model performance using classification metrics.

## Dataset
IBM Telco Customer Churn dataset, containing customer demographics, services, contract details, and billing information.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier

## Results

| Model | Accuracy |
| Logistic Regression | 80.31% |
| Random Forest | 78.96% |

Logistic Regression achieved the higher accuracy on the test dataset.

For Logistic Regression, churn-class recall was 57%, indicating that some customers who left were not identified by the model.

## Key Findings
- Month-to-month customers had a higher churn rate than customers with longer contracts.
- Customers who churned had shorter average tenure.
- Customers who churned had higher average monthly charges.

## Project Files
- `Customer_Churn_Prediction.ipynb`: Data analysis, preprocessing, model training, and evaluation.
- `model_results.csv`: Model accuracy comparison.

## How to Run
1. Download the IBM Telco Customer Churn dataset.
2. Open the notebook in Jupyter Notebook.
3. Update the dataset file path if needed.
4. Run the cells in order.

## Conclusion
This project demonstrates an end-to-end customer churn prediction workflow using Python and machine learning. The results can help explore customer retention patterns and identify areas for further model improvement.
