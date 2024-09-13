# bank_churn
This is an experiment in churn prediction of bank customers using ML models. Churn prediction is the process of determining which customers are likely to leave a business in the near future. The dataset is a dataset of 10,000 customers from the American Bank of Commerce. Various algorithms were trained on the dataset, and a Random Forest algorithm obtained the best result:

|   | Precision | Accuracy  | F1-score |
| ------------- | ------------- | ------------- | ------------- |
| No churn  | 0.90  | 0.90  | 0.90 |
| Churn  | 0.61  | 0.62  | 0.61 |
| Weighted avg  | 0.85  | 0.84  | 0.85 |

In short, the model correctly predicts the outcome 84% of the time. 61% of the customers likely to churn are identified by the model. The model is better at identifying customers unlikely to churn, which it does correctly 90% of the time. The unweighted F1-score is 0.76, which indicates an overall good performance. There is room for improvement, but this would probably require a better dataset with more features or more data. A deep learning model might offer some improvements to model performance but by far the largest issue is the lack of features in the dataset.

The model is capable of determining the likelihood of a customer churning based off factors like the customer's country, income, gender, balance and age. Most customers have a very low chance to churn, with a smaller group of customers having a large chance to churn.

Source for dataset: https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset/code?datasetId=2445309
